# DittNAV meta-repo

Meta-repo for alle DittNAV sine microservices, som gjør det mulig å jobbe med alle disse under ett som om det var et mono-repo.
Verktøyet [meta](https://github.com/mateodelnorte/meta) brukes for å kunne utføre git-kommandoer på mange git-repo-er samtidig, eller man kan bruke git på 
vanlig vis for å jobbe mot en og en microservice.

# Kom i gang
Det må installeres et par ting før man kan ta i bruk meta.
1. Installer `nvm`, f.eks.`brew install nvm`.
2. Installer `meta`, `npm install -g meta`.
3. Hent ned alle repo-ene, `meta git update`.
4. Bygg alle modulene: `gradle clean assemble`.
5. Alle microservice-ene skal nå ha fått et blått ikon på seg i fil-treet i IntelliJ. Hvis ikke så kan 
`Reload All Gradle Projects` aktiveres i Gradle-fanen.
6. Meta kan nå brukes for å utføre git-operasjoner på flere repo-er samtidig, f.eks. skrifte branch for alle 
microservice-ene: `meta git checkout enAnnenBranch`

# Henvendelser

Spørsmål knyttet til koden eller prosjektet kan rettes mot https://github.com/orgs/navikt/teams/personbruker

## For NAV-ansatte

Interne henvendelser kan sendes via Slack i kanalen #team-personbruker.
