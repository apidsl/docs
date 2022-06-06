
## About [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/DOCS/ABOUT.md)

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

---

I did last time some wrapper for bash, python, ... with such format: load("domains.txt")

I am using it to build multiplatform scripts, where the same sentence will be executed on PHP, Python, JS, ...

### The Inspiration was coming from such projects:

+ [jQuery, DOM Traversal and Manipulation](https://jquery.com/)
+ [Apache Camel uses a Java Domain Specific Language or DSL for creating Enterprise Integration Patterns or Routes in a variety of domain-specific languages (DSL)](https://camel.apache.org/manual/dsl.html)

