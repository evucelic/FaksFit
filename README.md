# FaksFit

**FaksFit** je projektni zadatak iz kolegija *Programsko Inženjerstvo*, grupa G04, čija je svrha olakšati studentima prolazak kolegija **Tjelesna i zdravstvena kultura**.

### Deployed aplikacija: [FaksFit](https://faksfit-7du1.onrender.com/)

### PDF dokumentacije projekta: [PDF](https://github.com/eugen-vucelic/FaksFit/blob/5f84d78f4d81080ca61cf086e7dbf8d36c2f6f24/FaksFit_merged.pdf)

## Sadržaj
1. [Opis projekta](#opis-projekta)
2. [Funkcijski zahtjevi](#funkcijski-zahtjevi)
3. [Tehnologije](#tehnologije)
4. [Instalacija i pokretanje](#instalacija-i-pokretanje)
5. [Podaci za testiranje](#podaci-za-testiranje-po-ulogama)
6. [Članovi tima](#članovi-tima)

---

## Opis projekta

Prolazak kolegija Tjelesne i zdravstvene kulture na fakultetu zna biti kompliciran i nejasan proces. Glavni cilj **FaksFit** aplikacije je:
- Centralizacija aktivnosti vezanih za kolegij,
- Olakšana prijava termina,
- Pregled ostvarenih bodova,
- Jednostavniji pristup informacijama kolegija.

Projekt je rezultat timskog rada u sklopu kolegija [Programsko inženjerstvo](https://www.fer.unizg.hr/predmet/proinz) na Fakultetu elektrotehnike i računarstva Sveučilišta u Zagrebu.

---

## Funkcijski zahtjevi

- Pregled i prijava dostupnih termina od strane studenta
- Pregled ostvarenih bodova i bodova potrebnih za prolaz
- Potvrđivanje bodova i prolaska od strane nastavnika
- Dodavanje novih termina od strane voditelja
- Pregled liste studenata od strane nastavnika
- Mogućnost registracije i prijave u sustav
- Implementacija Google Maps značajke

---

## Tehnologije

- **Spring Boot**
- **React**
- **Java**
- **JavaScript**
- **Postgres**
- **HTML, CSS**
- **Docker**
- **Render**

---

## Instalacija i pokretanje

### Lokalno

1. **Kloniranje repozitorija**
   ```bash
   git clone https://github.com/eugen-vucelic/FaksFit.git
   git checkout dev

2. **Pokretanje backenda**
   ```bash
   cd backend
   ./mvnw spring-boot:run
   ```
    backend će se pokrenuti na [http://localhost:8080](http://localhost:8080)

3. **Pokretanje frontenda**
   ```bash
    cd frontend
    npm install
    npm run dev  
    ```
   frontend će se pokrenuti na [http://localhost:5173](http://localhost:5173)

---

## Podaci za testiranje po ulogama

Login podaci za testiranje (login putem Google računa):

- **Student**  
email: `student.faksfit@gmail.com` \
lozinka: `nastavnik`


- **Voditelj**  
email: `voditelj.faksfit@gmail.com` \
lozinka: `faksfitvoditelj`

- **Nastavnik**  
email: `nastavnik.faksfit@gmail.com` \
lozinka: `nastavnik`

---
## Članovi tima
- Dominik Gračner – Backend, Organizacija
- Eugen Vucelić – Backend, Baza, Deployment
- Lucija Burić – Backend, Baza, Testovi
- Stjepan Rajković – Frontend
- Vitomir Brebrić – Frontend
- Adrian Šarotar – Frontend
- Dean Rakić – Dokumentacija
