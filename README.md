# Edukator+

**Edukator+** je Java Spring Boot aplikacija za upravljanje edukacijskim radionicama u neprofitnim organizacijama. Omogućuje evidenciju polaznika, radionica i prisustava putem REST API-ja, uz dodatne funkcionalnosti za testiranje i analizu.

> Izrađeno kao projekt za kolegij **Informacijsko-komunikacijska infrastruktura** (FFOS, Odsjek za informacijske znanosti), pod mentorstvom **izv. prof. dr. sc. Tomislava Jakopeca**, koristeći znanja stečena i kroz kolegij **Programiranje 2 (P2)**.

## ✨ Funkcionalnosti

- ✅ CRUD operacije za:
  - **Polaznike**
  - **Radionice**
  - **Prisustva**
- ✅ Validacija unosa (annotacije, greške klijentu)
- ✅ Evidentiranje prisustva polaznika na radionici
- ✅ Statistika prisustva po radionici (`prisutni` / `odsutni`)
- ✅ Filtriranje polaznika po godini rođenja
- ✅ Dohvat svih polaznika po radionici
- ✅ Generiranje demo podataka (n polaznika, n radionica, n prisustava)
- ✅ Realistična imena, naslovi i datumi uz korištenje **JavaFaker-a**
- ✅ Swagger dokumentacija (OpenAPI 3)

## 🔧 Tehnologije

- Java 17  
- Spring Boot 3.x  
- Spring Data JPA  
- Hibernate  
- MySQL  
- Swagger UI (springdoc-openapi)  
- Maven  
- JavaFaker (za realistične testne podatke)

## ▶️ Pokretanje

1. Kloniraj repozitorij:
   ```bash
   git clone https://github.com/romanuspopulsque/edukator-plus.git
2. U MySQL-u kreiraj bazu:
CREATE DATABASE edukatorplus;
3. Ažuriraj application.properties s vlastitim korisničkim podacima.
4. Pokreni aplikaciju u NetBeansu / IntelliJ-u / terminalu:
mvn spring-boot:run
5. Otvori Swagger dokumentaciju na:
http://localhost:8080/swagger-ui/index.html

📬 Autor
Roman Šimunović
📧 romansimunovic21@gmail.com
📍 Osijek, 2025.
Osijek, 2025.
