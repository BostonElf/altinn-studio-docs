---
title: Hva er nytt?
description: Oversikt over endringer som ble introdusert i versjon 7.
toc: true
---

## 7.0.0

### Features
- Forenklet app template. Det meste av kode er flyttet ut av templaten og inn i nugets. Redusert antall Altinn nugets fra to til tre.
- Mulig å skrive separat logikk for når en steg i prosessen er avbrutt. Tidligere ble samme kode som når et steg var ferdig kjørt.
- Mulig å skrive legge til egen logikk når et steg i prosessen starter. Denne koden blir kjørt før Altinn sin standard logikk.

### Bugfixes
- PDF generering støtter nå dynamiske options i repeterende grupper