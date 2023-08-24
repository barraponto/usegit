---
Tytul: Jak uzywac terminal
Info:
  Jak uzywac Git - Lekcja 1 : Jak uzywac terminal
  Wiecej informacji na : https://github.com/barraponto/usegit
transition: slide-left
drawings:
  persist: false
exportFilename: 01-le-terminal.pdf
---

# Jak uzywac terminal

## Z Capi Etheriel 
[@barraponto](https://github.com/barraponto)

# Czym jest terminal ?

<div class="max-w-prose mx-auto">
<v-clicks>

Terminal reprezentuje interfejs przez ktory uzytkownik moze napisac tak zwanych "shell command".
Te commandy umozliwiaja uzytkownika do stworzenia uzytkowych programow.

</v-clicks>
</div>

# Czym jest shell ?

<div class="max-w-prose mx-auto">
<v-clicks>

Shell jest programem ktory eksponuje serwisy dostepne na kernelu komputera poprzez roznych interfejsow. 

Istnieja tutaj dwie roznych interfejsow :
1. Graphical User Interface (GUI) reprezentuje graficzna czesc shellu, jak na przyklad Windows, gdzie mamy mozliwosc korzystania z serwisow naszego komputera poprzez roznych ikonow i klikow

2. Command-line Interface (CLI) jest wlasnie terminalem, tutaj nie mamy mozliwosci klikniecia w ikonow, musimy sami napisac tych command jesli checmy korzystac z serwisow naszego komputera (poprzez napisanie command, otrzymujemy odpowiedz na nia w postacie textu ktory sie sam napisze w interfejs)

</v-clicks>
</div>

# Czym jest "command" ?

<div class="max-w-prose mx-auto">
<v-clicks>

Command jest tekstualna reprezentacja do czego wymagamy od naszego komputera.
Na przyklad, jakbysmy chcieli wyslac naszemu szefowi maila gdzie pytamy o podwyzke, i gdzie zawartosc naszego maila juz jest napisana w pliku zwanym "contents.txt", moglibysmy napisac command :

```
mail --subject="Potrzebuje podwyzke !" boss@company.com < ./contents.txt
```

</v-clicks>
</div>

---
layout: intro
---

# Otworzcie terminal (Powershell, Ubuntu, Debian etc)

---
layout: intro
---

# Skonfigurowac swoj terminal

---
layout: intro
---

# Czy jakis program aktualnie dziala ?

---
layout: statement
---

# Czym jest interpretator ?

<div class="max-w-prose mx-auto">
<v-clicks>

Interpretator jest programem ktory przymuje nasze commandy i wykonuje je poprzez wykorzystanie roznych programow potrzebnych do dobrej interpretacji.

Umozliwia on rowniez stworzenia logiki, jak warunki "if else" i petli "for".

Interpretator jest rowniez tak zwanym "REPL" (Read-Eval-Print Loop) do jezyka programowania zwanym **script shell**.

</v-clicks>
</div>

---
layout: intro
---

# Jak shell odnajduje potrzebnych programow ?

---
layout: statement
---

# Czym jest zmienna PATH ?

<div class="max-w-prose mx-auto">
<v-clicks>

`PATH` jest srodowiskowa zmienna gdzie napisane sa lista folderow i ich sciezka gdzie interpretor moze szukac dany program jak na przyklad "cat", "ls" itp.
Pierwszy folder majacy imie danego programu bedzie uzywany do interpretacji commandy.

</v-clicks>
</div>

---
layout: statement
---

# Czym jest zmienna srodowiskowa ?

<div class="max-w-prose mx-auto">
<v-clicks>

Zmienna srodowiskowa jest wartosc z imieniem napisana na naszym komputerze (jak PATH na przyklad). 

Sa one dostepny z CLI lub command, mozna otrzymac ich wartosc poprzez napisanie.
```echo $VAR_NAME```
Gdzie "echo" odpisze dana wartosc, a $VAR_NAME jest imie naszej zmiennej.

Niektore zmienne srodowiskowe sa standardowe (oznacza to ze kazdy system ma ich w swoim register od samego poczatku), jak `PWD`, `PATH`, `PS1`.

Mozna rowniez napisac wlasnych zmiennych srodowiskowych.


</v-clicks>
</div>

---
layout: intro
---

# Jak moge zobaczyc wartosci swoich zmiennych srodowiskowych ?

R : `env`

---
layout: intro
---

# Jak mozna skonfigurowac swoich zmiennych ?

R : `.bashrc` albo `.zshrc`, zalezy od waszego shell.

---
layout: intro
---

# Z jakiego shell aktualnie korzystam ?

R : `echo $0`

---
---

# Czas na troche praktyki !
<br>

Cel : zainstalowac tealdeer

1. Stworzyc folder "downloads"
2. Wejsc do tego folderu za pomoca commandy "cd"
3. Pobrac tealdeer poprzez link : https://github.com/dbrgn/tealdeer/releases
4. Uzyc tealdeer dzieki './tealdeer'
   4.1 Zmienic uprawnienia jak najdzie taka potrzeba
5. Dac sciezke do tealdeer do zmiennej PATH
6. Zmienic imie tealdeer (opcjonalne)
7. Uzyc tldr
