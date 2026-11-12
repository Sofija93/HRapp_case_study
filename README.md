# 👨‍💻 HRapp Case Study

Jednostavna Java konzolna aplikacija razvijena kao praktičan primer (case study) za upravljanje zaposlenima i odeljenjima unutar jedne organizacije. Projekat demonstrira osnovne koncepte objektno-orijentisanog programiranja (OOP) u Javi.

## 🚀 Tehnologije

* **Jezik:** Java (Standard Edition)
* **Razvojno okruženje / IDE:** IntelliJ IDEA (ili bilo koje standardno Java okruženje)

## 📋 Ključne funkcionalnosti

* **Upravljanje zaposlenima (`Employee`):** Kreiranje zaposlenih sa jedinstvenim identifikatorom (`ID`), imenom i platom (`salary`).
* **Upravljanje odeljenjima (`Department`):** 
  * Dodavanje zaposlenih u odeljenje (sa ograničenim kapacitetom niza).
  * Filtriranje i pretraga zaposlenih po ID broju.
  * Automatsko računanje ukupne mase plata (`getTotalSalary`) za celo odeljenje.
  * Izračunavanje prosečne plate zaposlenih (`getAverageSalary`).
* **Demonstracija rada (`Main`):** Inicijalizacija test podataka, dodavanje zaposlenih u odeljenje "Education" i ispis rezultata poslovanja u konzolu.

## 🗂️ Struktura projekta

* `Employee.java` – Klasa koja definiše entitet zaposlenog (ID, ime, plata) sa konstruktorima, geterima, seterima i `toString` metodom.
* `Department.java` – Klasa koja upravlja kolekcijom zaposlenih unutar odeljenja i implementira poslovnu logiku i finansijske obračune.
* `Main.java` – Ulazna tačka aplikacije (entry point) koja pokreće demonstraciju sistema.

## ⚙️ Pokretanje projekta

1. Klonirajte repozitorijum ili preuzmite fajlove.
2. Otvorite projekat u svom omiljenom Java IDE-u (npr. IntelliJ IDEA, Eclipse).
3. Pokrenite klasu `Main.java` da biste videli izvršavanje programa i ispis u konzoli.
