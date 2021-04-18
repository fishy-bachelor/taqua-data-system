# Kildekode: Bachelor Tytlandsvik Aqua - Data Visualisering

Dette repoet inneholder kildekoden til bachelor skrevet i sammarbeid med Tytlandsvik Aqua for visualisering av data fra to av deres systemer.

## Bemerkninger

- Koden kan ikke kjøres direkte uten konfigurering. Alle nøkler i forbindelse med testmiljøer og produksjon er fjernet. Disse er erstattet med XXX. Nøkler som er erstattet er:
  - Tilkoblingsstrenger til databaser
  - Innlogging for JobScheduler
  - Azure ApplicationInsights sporingsnøkler
  - JWT secret
  - URL til produksjon- og testmiljø

## Ulike tjenester:

API: Inneholder koden tilknyttet data prossesering og eksponering.

FRONTEND: Inneholder kode tilknyttet webapplikasjon for interaksjon med data.

JOBSCHEDULER: Inneholder kode tilknyttet jobber for automatisk innhenting av informasjon.

SCRIPTS: Inneolder scripts som er bennyttet for å løse oppgaver som hadde vært tidkrevende å gjort manuelt.
