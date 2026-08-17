<div align="center">

# 🌤️ SkyGlance

**Nowoczesna, intuicyjna i przejrzysta aplikacja pogodowa z prognozą na żywo, jakością powietrza i astronomią.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-skyglance.pages.dev-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://skyglance.pages.dev/)
[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-Hosting-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://pages.cloudflare.com/)
[![WeatherAPI](https://img.shields.io/badge/Data-WeatherAPI.com-00A86B?style=for-the-badge&logo=weatherdotcom&logoColor=white)](https://www.weatherapi.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Client--Side-10B981?style=for-the-badge&logo=shieldcheckered&logoColor=white)](privacy.md)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0%20(Vanilla)-06B6D4?style=for-the-badge&logo=npm&logoColor=white)](#%EF%B8%8F-architektura-i-stack-technologiczny)
[![GitHub Stars](https://img.shields.io/github/stars/Jacekarino/skyglance.pl?style=for-the-badge&logo=github&color=EAB308)](https://github.com/Jacekarino/skyglance.pl/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Jacekarino/skyglance.pl?style=for-the-badge&logo=github&color=6366F1)](https://github.com/Jacekarino/skyglance.pl/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/Jacekarino/skyglance.pl?style=for-the-badge&logo=github&color=EC4899)](https://github.com/Jacekarino/skyglance.pl/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-22C55E?style=for-the-badge&logo=github)](https://github.com/Jacekarino/skyglance.pl/pulls)
[![License: MIT](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge&logo=open-source-initiative&logoColor=white)](license.txt)

<br />

<p align="center">
  <img src="https://raw.githubusercontent.com/Jacekarino/skyglance.pl/main/brand/thumbnail.png" alt="SkyGlance Interface Preview" width="720" />
</p>
<br />

</div>

---

## 🌟 Overview / Przegląd

**SkyGlance** to lekka, minimalistyczna i wysoce responsywna aplikacja internetowa do monitorowania pogody w czasie rzeczywistym. Zaprojektowana z myślą o czytelności oraz estetyce *Glassmorphism*, łączy szczegółowe dane meteorologiczne z prostotą obsługi.

Aplikacja umożliwia błyskawiczne sprawdzenie aktualnej aury, prognozy wielodniowej, czystości powietrza (AQI) oraz danych astronomicznych dla dowolnego miasta na świecie lub na podstawie bieżącej lokalizacji GPS użytkownika.

---

## ✨ Features / Funkcjonalności

- 🌡️ **Aktualne Warunki i Temperatura Odczuwalna** — Precyzyjne dane o bieżącej temperaturze, zachmurzeniu oraz dynamicznie dobieranych ikonach stanu pogody.
- 📊 **Szczegółowe Wskaźniki Atmosferyczne** — Panel parametrów: wilgotność powietrza, siła i kierunek wiatru, ciśnienie atmosferyczne (hPa), indeks promieniowania UV, widoczność oraz prawdopodobieństwo opadów deszczu.
- 🍃 **Monitorowanie Jakości Powietrza (AQI)** — Odczyt wskaźnika czystości powietrza z polskimi interpretacjami (od *Świetna* do *Niebezpieczna*).
- 🌙 **Panel Astronomiczny** — Godziny wschodu i zachodu słońca oraz przetłumaczone fazy księżyca (m.in. *Nów*, *Pełnia*, *Kwadry*).
- 📅 **Prognoza 3-Dniowa** — Zestawienie temperatur minimalnych i maksymalnych oraz przewidywanych zjawisk na kolejne dni tygodnia.
- 📍 **Inteligentna Geolokalizacja (GPS)** — Automatyczne pobieranie współrzędnych przez HTML5 Geolocation API przy starcie aplikacji, z możliwością manualnego wyszukiwania dowolnej miejscowości.
- 💾 **Pamięć Ostatniego Miasta** — Ostatnio przeglądana lokalizacja jest bezpiecznie zapisywana w `localStorage` Twojej przeglądarki.
- 🎨 **Elegancki Design Glassmorphic** — Nowoczesny ciemny motyw z akcentami przezroczystości, dopasowany do ekranów smartfonów, tabletów i komputerów.
- 🔒 **Zero Śledzenia (Privacy-First)** — 100% przetwarzania po stronie klienta, brak ciasteczek reklamowych i brak logowania danych telemetrycznych.

---

## 🚀 Live Instances / Dostęp Online

Aplikacja jest stale dostępna online pod adresem:

| Provider | URL | Status |
| :--- | :--- | :--- |
| **Cloudflare Pages** | [https://skyglance.pages.dev/](https://skyglance.pages.dev/) | ![Active](https://img.shields.io/badge/online-emerald?style=flat-square) |

---

## 🛠️ Architektura i Stack Technologiczny

| Komponent | Technologie | Rola w projekcie |
| :--- | :--- | :--- |
| **Warstwa UI & Prezentacji** | Semantyczny HTML5, Nowoczesny CSS3 (Glassmorphism, Flexbox/Grid) | Lekki, w pełni responsywny interfejs użytkownika |
| **Logika Kliencka** | Pure Vanilla JavaScript (ES6+ Fetch API, Async/Await) | Asynchroniczna komunikacja z API, geolokalizacja i obsługa DOM |
| **Źródło Danych** | [WeatherAPI.com REST API](https://www.weatherapi.com/) | Dostarczanie danych pogodowych, jakości powietrza i astronomii |
| **Typografia & Ikony** | [Poppins (Google Fonts)](https://fonts.google.com/specimen/Poppins), [Font Awesome 6](https://fontawesome.com/) | Nowoczesna identyfikacja wizualna i wektorowe piktogramy |
| **Infrastruktura & Hosting** | Cloudflare Pages | Błyskawiczna dystrybucja statyczna Edge CDN |

---

## 💻 Getting Started / Uruchomienie Lokalne

Aplikacja nie wymaga instalacji Node.js ani żadnych zewnętrznych menedżerów pakietów!

### 1. Sklonuj repozytorium
```bash
git clone https://github.com/Jacekarino/skyglance.pl.git
cd skyglance.pl
```

### 2. Otwórz w przeglądarce
Wystarczy uruchomić plik `index.html` bezpośrednio:

```bash
# Na Windows (PowerShell)
Start-Process index.html

# Na macOS
open index.html

# Na Linux
xdg-open index.html
```

Lub z wykorzystaniem dowolnego lokalnego serwera:
```bash
# Używając Pythona
python -m http.server 8080

# Używając Node / npx
npx serve .
```

Aplikacja będzie dostępna pod adresem: `http://localhost:8080`

---

## 📂 Struktura Projektu

```text
skyglance.pl/
├── brand/                    # Logotypy, ikony oraz zrzuty ekranu
│   ├── sglogo-blank.png      # Główny logotyp aplikacji
│   ├── sgicon-circle.png     # Okrągła ikona aplikacji
│   └── thumbnail.png         # Oficjalny zrzut ekranu do dokumentacji
├── favicon.ico               # Favicon przeglądarki
├── index.html                # Główny szkielet strony i semantyczne sekcje
├── privacy.md                # Polityka prywatności aplikacji
├── license.txt               # Treść licencji MIT
├── readme.md                 # Dokumentacja techniczna projektu
├── script.js                 # Integracja z WeatherAPI, geolokalizacja i logika widoku
└── style.css                 # Stylistyka Glassmorphism, animacje i responsywność
```

---

## 🤝 Contributing / Wkład w projekt

Wszelkie propozycje usprawnień, zgłoszenia problemów oraz Pull Requesty są mile widziane!

1. Sforkuj projekt (**Fork**)
2. Stwórz swoją gałąź funkcjonalną (`git checkout -b feature/NowaFunkcja`)
3. Zatwierdź zmiany (`git commit -m 'Dodano nową funkcję'`)
4. Wypchnij gałąź na GitHub (`git push origin feature/NowaFunkcja`)
5. Otwórz **Pull Request**

---

## 📬 Kontakt

**Jacek Kowalczyk**
- 📧 Email: [jacekarino@duck.com](mailto:jacekarino@duck.com)
- 🐙 Profil GitHub: [@Jacekarino](https://github.com/Jacekarino)

---

## 📄 Licencja

Projekt dystrybuowany na licencji **MIT**. Szczegółowe informacje znajdują się w pliku [`license.txt`](license.txt).

---

<div align="center">

Made with ♡ by [**Jacekarino**](https://github.com/Jacekarino)

</div>
