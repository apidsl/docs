
![logo.apidsl.com](https://logo.apidsl.com/1/cover.png)

# [Documentation - docs.apidsl.com](https://docs.apidsl.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/MD/MENU.md) 

+ [Sourcecode - bash.apidsl.com](http://bash.apidsl.com)
+ [Examples - examples.apidsl.com](http://examples.apidsl.com)
+ [Blog - www.apidsl.com](https://www.apidsl.com/)
+ [Logotyp - logo.apidsl.com](https://logo.apidsl.com/)

+ [LICENSE](../LICENSE)



## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/MD/ABOUT.md)

One of the benefit of modularization is to have a modular architecture with independent modules from a programming language, so we present here an example langauge the APIDSL, which bring together different languages on shell level

I did last time some wrapper for bash, python, ... with such format: load("domains.txt")

```apidsl
load("domains.txt")
.split("/n")
.http()
.xpath("title")
.appendToFile("titles.txt")
```

I am using it to build multiplatform scripts, where the same sentence will be executed on PHP, Python, JS, ...

### The Inspiration was coming from such projects:


+ [jQuery, DOM Traversal and Manipulation](https://jquery.com/)
+ [Apache Camel uses a Java Domain Specific Language or DSL for creating Enterprise Integration Patterns or Routes in a variety of domain-specific languages (DSL)](https://camel.apache.org/manual/dsl.html)

## Czym jest APIDSL


![apidsllayers](apidsl-layers.png)


APIDSL to zwykły skrypt o niezwykłych możliwościach
+ napisany w bash-u
+ jako lokalny skrypt bash, po skopiowaniu z repozytorium
+ jako komenda w systemie linux, po skopiowaniu do /usr/local/bin
+ z zarządzaniem zalezności: install, update ze wsparciem dla dla maven, composer, node

APIDSL tworzy abstrakcyjną warstwę w multi-języklowych projektach do celów łatwiejszego re-użycia kodu bibliotek i projektów.
APIDSL mapuje i uruchamia funkcje i skrypty z róznych języków programowania.
Mapowanie pozwala na kierowanie strumienia danych neizaleznie od języka programowania do endpoint-u.
Mapowanie skyrptów łączących się z API usług SaaS pozwala na łatwą integrację usług i tworzenie nowych.
Deklaratywny zapis opisuje działanie połączonych ze sobą bibliotek i api, co pozwala na deployment i testowanie całej infrastruktury.

Ten sam zapis APIDSL pozwala w zależnośći od załadowanych zależnosć uruchomić jak i przetestować infratsrukturę.


Taki użycie kodu nie ogranicza nas do stosowania jednej technologii czy środowiska,
a pozwala na łączenie najlepszych rozwiązań z różnych języków, bibliotek, frameworków, projektów opensorce czy API.


I did last time some wrapper for bash, python, ... with such format: load("domains.txt")

I am using it to build multiplatform scripts, where the same sentence will be executed on PHP, Python, JS, ...

[Programowanie imperatywne oraz deklaratywne | Codenga](https://codenga.pl/artykuly/poradniki/programowanie-imperatywne-oraz-deklaratywne)

> Programowanie imperatywne oraz deklaratywne

https://pl.wikipedia.org/wiki/Imperatyw
Imperatyw (łac. imperativus – rozkazujący) – nakaz, reguła, zasada, która nie podlega dyskusji i którą można bezpośrednio wywieść z założeń teoretycznych.

Paradygmat imperatywny można opisać tak: “mówimy jak komputer ma wykonać daną rzecz”. Czyli skupiamy się na poszczególnych krokach, które prowadzą do rozwiązania problemu.

Możesz sobie wyobrazić program napisany imperatywnie jako ciąg instrukcji.


Paradygmat deklaratywny można opisać tak: “mówimy komputerowi co ma dla nas zrobić”. Ważny jest dla nas wynik jaki uzyskamy - nie wnikamy w jaki sposób komputer ten wynik. osiągnie.

Taki styl programowania pozwala skupić się więc na celu. Na tym, co chcemy osiągnąć. Mniej ważne są tutaj kroki, które do tego celu prowadzą.
### The Inspiration was coming from such projects:

+ [jQuery, DOM Traversal and Manipulation](https://jquery.com/)
+ [Apache Camel uses a Java Domain Specific Language or DSL for creating Enterprise Integration Patterns or Routes in a variety of domain-specific languages (DSL)](https://camel.apache.org/manual/dsl.html)





Git fork
Contributing

There are many ways you can help make Camel better - please dive in and help!Identify areas you can contribute first. You don’t have to be an expert in an area, the Apache Camel developers are available to offer help and guidance.

Read More

Person talking
User Stories

This page is intended as a place to collect user stories and feedback on Apache Camel. If you are using or have tried Apache Camel please add an entry or comment; or post to the mailing list.

Read More

Article
Articles

Articles are divided into several sections. As the lists grow, further sectioning refinements may be necessary. The article section includes camel videos and general articles and other categories.

Read More

Books
Books

This page lists the known books about Apache Camel. If you happen to know a book which is not listed then please contact us.

Read More

People
Team

This page lists who we are. By all means add yourself to the list - lets sort it in alphabetical order. When posting to the mailing lists, use plain text mails. Do not use HTML mails.



## Supported technologies  [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/MD/SUPPORTED.md)


### Languages:
+ js
+ php
+ bash
+ python

### Environment
+ docker
+ logs

## Data formats

+ ini
+ json
+ yaml
+ csv
+ html
+ xml


## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/MD/ABOUT.md)

W jaki sposób opisuje Pan procesy i jak modeluje Pan zmiany, jak testuje Pan jeszcze przed wdrożeniem skutki tych zmian?

Brzmi ciekawe, jednak, w mojej ocenie to kultura pracy i niewiedza, stoi na przeszkodzie zmianom, również tym na lepsze.
Często nie wchodzi się w merytoryczną dyskusję uzasadniając to brakiem czasu czy kompetencjami, a hierarchia skutecznie blokuje zmiany od wewnątrz.
Odpowiedzialność za wykonanie procesu, a rozumienie zasady działania i świadomość wdrożenia zmiany to odległe planety.


słuszne uwagi, warto korzystać z luksusu zarządzania popartego wiedzą i kontrolę organizacji zautomatyzować na poziomie języka domenowego, tak zmieniamy IT w Softreck gdzie piszemy i książki i programy komputerowe.

Co do samej kultury organizacyjnej to jest ona również zależna od oprogramowania a może i nawet determinowana tym jakich partnerów i dostawców wybieramy.

Warto przemyśleć w dobie technokracji czy nie delegujemy ryzyka utraty biznesu poprzez outsourcing?

Nie jedna marka została pogrążona przez wyciek danych, jaki system operacyjny używała? Czy to przypadek, że to często usługa microsoft? Wiedza o oprogramowaniu i umiejętność wykorzystania go również zweryfikowała przydatność managerów podczas tzw. pandemii, lockdown-u i pracy zdalnej.

Kluczowe okazało się oprogramowanie.


I'm grateful for such positive feedback!
#book #iac #infrastructure #apidsl

I am excited to announce the launch of my new project!

#apidsl #newproject #DSL Domain-specific language


ponieważ sam utrzymuję ponad 700 domen internetowych, a pod nimi kilkaset małych stronek, poszukiwałem rrozwiazania do automatyzacji deploymentu i monitoringu.
rezultatem jest jezyk DSL, który pozwala na opisanie sieci połączeń pomiędzy usługami a tym samym przeprowadzenie wdrożenia i monitorowania usług.

Co więcej samo pisanie tej mapy powiązań można zautomatyzować, tzn, jeśli planujemy migrację to robimy mapę - zapis w języku DSL, aby w momencie uruchomienia ponownie sprawdzić na podstawie tej mapy czy infratstruktura działa
to jest opis wysokopiozmowy, niezlaęzny od jezyka programowania, dlatego dopiero badam granice użycia
nie wiem czy ta oferta jest trafiona, czy jest zapotrzebowanie, dlatego piszę o tym co to robi, bo zastosowań może być więcej. Samo APIDSL działa na linuxie w shellu, jest to wrapper/adapter na biblioteki, usługi w środowisku uruchomionym na systemie linux

aktualnie testowane zastosowanie: robienie zrzutów ekranów wielu stron jednocześnie, czy sparwdzanie statusów, także boty logujące się na stronach i wykonujące jakieś czynności



Celem jest automatyzacja pracy administratora infrastruktury, ale w sposób niezależny od platformy i języka programowania

mamy dostęp do wszystkiego co jest kodem, uruchamiamy to i używamy

nie jesteśmy zależni od tech-stack-a

jest to też owocem metodologii hipermodularyzacji

https://www.hipermodularyzacja.pl/

TODO: przenieść do examples
przykładowo aby zrobić zrzuty ekranu setek stron wystarczy lista plików w pliku tekstowym oraz 4 komendy w jednej linii

+ [screenshot # make a screenshot](http://examples.apidsl.com/screenshot)





## get [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/LET.md)

get dependencies from file

```bash
apidsl --get "apidsl.txt"
```

## let [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/LET.md)

let define variable 

example


## put [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/PUT.md)

put variable to the data stream

```bash
apidsl 'put("invoice","company","year")'
```

```bash
apidsl -l 'put("invoice","company","year")'
```

## run [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/RUN.md)

run file script

run as option param
```bash
apidsl --run "test.apidsl"
```

run as command

```bash
apidsl 'run("test.apidsl")'
```

with logs 
```bash
apidsl -l 'run("test.apidsl")'
```

## get [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/LET.md)

```bash
apidsl --init
```

## LOGS [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/EXAMPLE/LOGS.md)


## LOGS

print logs for latest run
```bash
apidsl -l
```

## get [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/LET.md)

get library from url

## get [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/COMMAND/LET.md)

get library from url
```bash
apidsl --version
```


---

+ [edit](https://github.com/apidsl/docs/edit/main/README.md)
+ [apidsl/docs](https://github.com/apidsl/docs)
