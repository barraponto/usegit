# Annotations to remember after the end of the courses !

For searching a word in existing files under the current directory and sub directories, we can do :
```grep -rnw './' -e 'test' ```
1. r stands for recursive, it will search the word in all sub directories
2. n will print the line where the text was found
3. w will match only if the whole word is found, and will not accept text like "test11" (or you can ommit it to see the whole line with the given text)
4. -e will try to match the given pattern next to it ('test' here)

The command will return something like :
./<file_name>.<extension>:<line where the text was found>:test
EX : ./newFile.txt:2:test


We can count how many time the text was found by adding "wc -l" to the command, so :
```grep -rnw './' 'test' | wc -l```

And if we care about getting only the first occurence in each file, wa can pipe the results with "uniq" :
```grep -rnw './' 'test' | uniq``` 

Or alternatively, we can use the command "find" to get ONLY the name of files which contain the text :
```find . -name "*test*" -print```
> NOTE : the command is recursive by default, but we can add -maxdepth <number> if we want to limit the number of sub folders to search
