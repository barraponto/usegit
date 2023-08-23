# Welcome to the [Use Git](https://github.com/barraponto/usegit) course!

## Pre-requisites

You're going to need some terminal:

- Windows users may use Windows Terminal with WSL2 
- Mac users may use iTerm2
- Linux users are fine, all terminals are welcome (yes even xterm)
    - Capi uses Kitty

Then, make sure to install git:

- Windows users can `apt install git` from their WSL2 terminal
- Mac users probably have git, but `brew install git` will give you the latest version
- Linux users should try `which git` before using the package managers to install git

## The actual course

Use the `annotations` folder for notes based on the lessons.
Adding more stuff there is up to you, annotate at will!
Just try to keep the notes in the right files, like `annotations/01-notes.md`

The `lessons` folder holds the actual slides (except for intro, which is the slides.md).
Feel free to edit them and send pull requests!

The `exports` folder holds pdf versions of the slides used in class.
You may find them almost as bare as the annotations, but they're in there anyway.

The `quizzes` folder holds quizzes.
Rubrics should be copies of the quizzes, but answered in markdown.
Try the quizes before looking into the rubrics, so you learn more ;)

The `recipes` folder holds sample data for the git repo examples.

The `suggestions` folder should hold suggestions in markdown format.
Use files like `suggestions/commitizen.md` to add a suggestion and explain why it is a good idea.

## So you want to hack the course?

Cool! You don't have to edit slides or generate the slides, but if you want to:

- `npm install`
- `npx slidev ./path/to/slide.md` will start the presentation (ctrl+c to quit)
- visit http://localhost:3030

Alternatively, run `npx slidev export --dark ./path/to/slide.md` to generate a pdf from any presentation!

Learn more about Slidev on [documentations](https://sli.dev/).

## Contributing back your changes

Fork the repo, branch off, send pull requests.
Try to respect commitizen -- use `npx git-cz` to commit changes with nice messages :)
