# HelloWorkshop

\[!\[Build](https://github.com/KajaRabka/warp-lab01-hello-workshop/actions/workflows/build.yml/badge.svg)](https://github.com/KajaRabka/warp-lab01-hello-workshop/actions/workflows/build.yml)



Aplikacja konsolowa .NET stworzenia podczas laboratorium.

## Kontakt

Autor: Student - Warsztat Programisty

## Uruchomienie

```bash
dotnet run
```

Test automatycznego uruchamiania GitHub Actions po pushu.



\## Continuous Integration



Workflow uruchamia się ręcznie, po pushu do gałęzi main

oraz po utworzeniu lub aktualizacji Pull Requesta do main.



Sprawdzany projekt: HelloWorkshop.csproj.

Wersja .NET: 10.0.x.



Automatyczne kontrole:

\- Sprawdzenie struktury repozytorium.

\- Przywrócenie zależności (restore).

\- Kompilacja projektu (build).

\- Publikacja aplikacji (publish).

\- Przesłanie artefaktu.

\- Uruchomienie aplikacji (run).



Artefakt ma nazwę app-${{ github.sha }} i jest

przechowywany przez 7 dni.



Logi można znaleźć w zakładce Actions na GitHubie,

po wybraniu konkretnego uruchomienia workflow.

Artefakty znajdują się w sekcji Artifacts na stronie Summary.

