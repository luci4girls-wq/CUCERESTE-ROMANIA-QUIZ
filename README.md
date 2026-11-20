# România – Explorează Județele

Joc educativ construit cu React, TypeScript și Vite, împachetat ca aplicație desktop Windows cu Electron.

## Rulare locală

Ai nevoie de Node.js LTS instalat.

```bash
npm install
npm run dev
```

## Construire instalator Windows (.exe)

Pe Windows, din folderul proiectului:

```bash
npm install
npm run dist:win
```

Instalatorul va apărea în folderul `release/`.

## Salvarea datelor

Progresul, istoricul întrebărilor și clasamentul sunt salvate local în profilul aplicației/browserului Electron, pe calculatorul pe care rulează jocul. Nu se sincronizează automat între calculatoare.
