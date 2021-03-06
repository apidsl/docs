
## EXAMPLES [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/apidsl/docs/edit/main/DOCS/EXAMPLES.md)


Rozwiązanie #apidsl służy pisaniu komend do wcześniej napisanych skryptów, bibliotek, aplikacji.
Zamiast ścieżek do plików używamy nazw jako funkcji z parametrem. Korzyść? re-użycie kodu, zamiast refaktoryzacji! APIDSL to jedno z rozwiązań w (pisanej jeszcze) książce #hipermodularyzacja

API + DSL = Application Programming Interface controlled over Domain Specific Language
#apidsl is available for testing
#hypermodularity #hyperprogramming #mvp #prototyping #programming #testing

### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```

```js
load("domains.txt")
.split("/n")
.http()
.xpath("title")
.appendToFile("titles.txt")
```


### xpath from functions

```bash
./apidsl.sh 'f.http("https://softreck.com").f.xpath("title")'
```


### tag from letpath

```bash
./apidsl.sh 'f.http("https://softreck.com").letpath.tag("title")'
```


### nameservers

```bash
./apidsl.sh 'whois.ns("softreck.com")'
```

### loop

```bash
./apidsl.sh 'f.load("domains.txt").split("/n").f.http().f.xpath("title").f.appendToFile("titles.txt")'
```

more examples with scripts
# test.deploymat.com

```bash
./apidsl.sh 'import("https://github.com/letpath/bash","path").path.load("apifork.txt")'
./apidsl.sh 'path.load("apifork.txt")'
```

## LOGS

print logs for latest run
```bash
./apidsl.sh -l
```

## DEBUG

show infos after run
```bash
./apidsl.sh -d 'import("https://github.com/letpath/bash","path").path.load("apifork.txt")'
```