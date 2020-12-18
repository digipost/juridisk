# Vilkår for bruk av Digiposts postkasse-API-er for privatpersoner

## Hva er Digiposts postkasse-API-er for privatpersoner?

Digipost tilbyr flere API-er som privatpersoner eller bedrifter kan benytte for å få tilgang til privatpersoners digitale postkasser i Digipost. Tilgangen til API-ene reguleres av Posten Norge AS, mens tilgangen til den enkelte postkasse reguleres av den privatpersonen som eier postkassen.

Utviklere som benytter Digiposts API-er for privatpersoner, må overholde akseptere følgende vilkår.

## Informasjon om opprinnelse

Det skal fremgå av applikasjonen som integreres hva som er datagrunnlaget, enten datagrunnlaget helt eller delvis er hentet fra Digipost. Applikasjonen skal merkes som følger:

«Datagrunnlag: Digipost av Posten Norge AS» (norsk bokmål eller nynorsk)
«Data source: Digipost by Norway Post» (engelsk)

Informasjonen må være synlig for brukeren, enten lett tilgjengelig i grensesnittet for applikasjonen, eller idet applikasjonen starter. Det er ikke tillatt å fremstille det som at data hentet via dette API-et opprinner fra et annet sted.

## Identitet

Det må ikke utarbeides applikasjoner som fremstår som om de er laget av Posten Norge AS.

## Krav til registrering

Den som utvikler en applikasjon som integreres mot Digiposts API-er, må registrere applikasjonen som anvist på https://www.digipost.no/plattform/annet/oauth/. Den som registrerer applikasjonen her aksepterer ved registreringen disse vilkårene.

Det er Posten Norge AS som står for innhenting og lagring av samtykker fra den enkelte privatperson for tilgang til postkassen. Utvikleren som integrerer sin applikasjon mot Digipost må implementere slik flyt i sin applikasjon, ellers utleveres ingen data i API-et.

## Manipulering av data

Det er ikke tillatt å manipulere datagrunnlaget i de originale data som utleveres fra Digipost.

### Strid med norsk lovgivning

Det er ikke lov å benytte innholdet på nettsider som bryter med norsk lov.

## Spørsmål

Spørsmål relatert til retningslinjene kan rettes til support@digipost.no.
