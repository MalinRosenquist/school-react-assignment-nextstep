# 🪶 Nextstep

## 🔎 Project Description

**Nextstep** är en React-app som bygger en egen “Platsbanken”-upplevelse ovanpå Arbetsförmedlingens öppna **JobSearch API**. Appen följer kursens krav: dataservice för API-anrop, React-router för flöden, delad state/contexts (t.ex. sparade annonser) och UI enligt Arbetsförmedlingens designsystem.

## 🌍 Live Demo

👉 [Live demo of Nextstep](https://malinrosenquist.github.io/school-react-assignment-nextstep/)

## ✨ Features

- **Sök jobbannonser** via `https://jobsearch.api.jobtechdev.se/`
- **Filtrera på kommun** (hämtas via egen municipalities-service)
- **Paginering** av träfflistan
- **Jobbsida (detaljvy)** `/jobad/:id` med uppdelad mobil/desktop-vy
- **Spara jobb** till en lista (toggle och vy under “Saved Jobs”)
- **Felvy** och enkel laddningsindikator
- **Designsystem**: använder `@digi/arbetsformedlingen` och `@digi/arbetsformedlingen-react`

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
[![Arbetsförmedlingens Designsystem](https://img.shields.io/badge/Arbetsf%C3%B6rmedlingens%20Designsystem-%20-0B60A9?style=for-the-badge&labelColor=0B60A9&color=0B60A9)](https://jobtechdev.se/sv/components)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)

🔗 API & Docs

- JobSearch (öppna data): https://jobtechdev.se/sv/components/jobsearch
- Getting started: https://gitlab.com/arbetsformedlingen/education/education-api/-/blob/main/GETTING_STARTED.md

## 👩‍💻 Authors

- [Malin Rosenquist](https://www.github.com/malinrosenquist)
- [Valentin Björkli](https://github.com/Valentin-dot-com)
- [Alice Swahn](https://github.com/Aliceswahn)

## 📸 Screenshots

![Screen width 1800px](./docs/screenshots/screenshot-1800.png)

![Screen width 320px](./docs/screenshots/screenshot-320.png)

## 📄 License

This project is open source and available under the [MIT License](./LICENSE).
