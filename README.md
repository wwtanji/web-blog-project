# Prehľad projektu

Tento repozitár obsahuje webovú aplikáciu, ktorá zahŕňa rôzne funkcie, ako sú používateľská autentifikácia, správa blogov, zobrazovanie príspevkov podľa kategórií a ďalšie. Projekt je navrhnutý v PHP a obsahuje front-endové prvky, ako sú CSS a JavaScript, pre interaktívne a responzívne užívateľské rozhranie.

---

## Funkcie

### 1. **Autentifikačný systém**
- **Registrácia**: Noví používatelia si môžu vytvoriť účet prostredníctvom súborov `signup.php` a `signup-logic.php`.
- **Prihlásenie**: Registrovaní používatelia sa môžu prihlásiť prostredníctvom `signin.php`, pričom logika je spracovaná v `signin-logic.php`.
- **Odhlásenie**: Používatelia sa môžu odhlásiť pomocou `logout.php`.

### 2. **Správa obsahu**
- **Blogové príspevky**: Aplikácia obsahuje blogový systém s dynamickým zobrazovaním príspevkov prostredníctvom `blog.php` a `post.php`.
- **Filtrovanie podľa kategórií**: Používatelia môžu prehliadať príspevky podľa kategórií pomocou `category-posts.php`.
- **Vyhľadávanie**: Funkcia vyhľadávania je implementovaná v `search.php`.

### 3. **Informačné stránky**
- `about.php`: Stránka O nás.
- `services.php`: Stránka Služby popisujúca ponuku platformy.
- `contact.php`: Stránka Kontaktujte nás.

### 4. **Administračný panel**
- Adresár `admin` pravdepodobne obsahuje nástroje na správu používateľov, príspevkov a ďalších administratívnych funkcií (obsah by mal byť podrobnejšie preskúmaný).

### 5. **Súbory so zdrojmi**
- **CSS**: Štýly pre webovú aplikáciu sa nachádzajú v adresári `css`.
- **JavaScript**: Dynamické funkcie sú podporované skriptmi v adresári `js`.
- **Obrázky**: Multimediálne súbory sa nachádzajú v adresári `images`.

### 6. **Časti šablón**
- Adresár `partials` obsahuje opakovane použiteľné komponenty, ako sú hlavičky, päty alebo navigačné ponuky, čím sa zabezpečuje konzistentnosť aplikácie.

### 7. **Konfigurácia**
- Adresár `config` pravdepodobne obsahuje konfiguračné súbory pre pripojenie k databáze, premenné prostredia alebo iné nastavenia.

---

## Štruktúra súborov

```plaintext
Project-main/
├── about.php
├── admin/
├── blog.php
├── category-posts.php
├── config/
├── contact.php
├── css/
├── images/
├── index.php
├── js/
├── logout.php
├── partials/
├── post.php
├── search.php
├── services.php
├── signin-logic.php
├── signin.php
├── signup-logic.php
├── signup.php
