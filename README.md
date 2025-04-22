# 📚 Språktrender i lærebøker

**Visualisering av språkbruk i norske lærebøker fra 2013 og fremover.**  
Bygget for Språkrådet med data fra Nasjonalbiblioteket – og litt hjelp fra en superduper utgave av ChatGPT 🤖

---

## 🌐 Live app

👉 [Åpne appen i nettleseren](https://yoonsen.github.io/Spraaktrender_utdanning/)

Installerbar som PWA ✔️ Fungerer offline ✔️ Auto-oppdatering ✔️

---

## 🛠️ Teknologi

- HTML + JavaScript (vanilla)
- [Bootstrap 5](https://getbootstrap.com/)
- [Plotly.js](https://plotly.com/javascript/)
- PWA: manifest + service worker
- Data fra [api.nb.no](https://api.nb.no/)
- 💡 Utviklet med støtte fra OpenAI / ChatGPT

---

## 📦 Bruk

1. Skriv inn årstall og eventuelt emneord
2. Trykk “Hent data” eller bruk Enter
3. Grafen viser antall bøker per språk og år

---

## 🗂️ Filstruktur

* index.html # Hovedappen 
* manifest.json # PWA metadata 
* sw.js # Service worker for cache og oppdatering


