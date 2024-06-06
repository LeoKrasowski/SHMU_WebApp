#Grafické rozhranie
![image](https://github.com/LeoKrasowski/SHMU_WebApp/assets/95176162/b6324015-93d9-43d2-ae24-b64c0b8c0fef)

Popis
Táto webová aplikácia slúži na evidenciu publikačnej činnosti meteorologických odborníkov a poskytuje prehľad aktivít jednotlivých zamestnancov.
Použité Technológie
Frontend:
Thymleaf
Bootstrap
HTML

Backend:
Java
Spring Boot

Databáza:
MySQL

Databázová Tabuľka

Tabuľka: post
nazov (VARCHAR 255): Názov publikácie

datum (DATE): Dátum publikácie

type (VARCHAR 255): Typ publikácie

zamestanec (VARCHAR 255): Meno zamestnanca

popis (TEXT): Popis publikácie

Postup Vývoja

Návrh Databázy:
Vytvorenie schémy MySQL databázy s tabuľkou post.

Nastavenie Backend:
Vytvorenie Java Spring Boot aplikácie.
Konfigurácia pripojenia k MySQL databáze.
Vytvorenie modelov pre databázovu tabuľku.
Implementácia repository vrstvy pre prístup k dátam.
Implementácia kontroléra pre spracovanie HTTP požiadaviek.

Vývoj Frontend:
Vytvorenie HTML šablóny pomocou Thymleaf.
Použitie Bootstrap pre štýlovanie.
Implementácia stranky pre zobrazenie prehľadu publikácií zamestnancov.
