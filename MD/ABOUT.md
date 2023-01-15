
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

