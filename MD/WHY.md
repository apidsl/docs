
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

