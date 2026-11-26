# Een client-servervoorbeeld - Kotlin Android / NestJS (2026)

Deze repository hoort bij de cursus **"Een client-servervoorbeeld - Kotlin Android / NestJS (2026)"**, gepubliceerd op:

**https://stahe.github.io/nl-kotlin-android-nestjs-oct-2026/**

## Overzicht

Dit document past de educatieve app **RdvMedecins** (een app voor het plannen van afspraken bij de arts), die al is behandeld in cursussen over Angular, React, Vue.js en Flutter, aan tot een native Android-app. Hier wordt een **Android**-versie gepresenteerd: een client geschreven in **Kotlin** met **Jetpack Compose** (Material 3), die gebruikmaakt van een **NestJS**-server (TypeScript) die een JSON-API aanbiedt, beveiligd met JWT-authenticatie (rollen ADMIN / USER).

Dit document is een stap-voor-stapgids die de voortgang volgt van de cursus [Een client-servervoorbeeld - Flutter / NestJS (2026)](https://stahe.github.io/nl-flutter-nestjs-sept-2026/), waaraan het de server, de database en de clientarchitectuur ontleent: elk Jetpack Compose-concept wordt gekoppeld aan zijn Flutter-equivalent. De basis van de taal Kotlin wordt behandeld in de [Kotlin-cursus](https://stahe.github.io/nl-kotlin-oct-2026/).

De cursus behandelt:

- het inrichten van de ontwikkelomgeving (Android Studio, Android SDK, Gradle, een Compose-project aanmaken, emulator en Android-telefoon);
- het installeren en starten van de NestJS-server van de app (MySQL-database, configuratie, testen met een browser en met Postman);
- een inleiding tot Android en Jetpack Compose (activities, `@Composable`-functies, toestand en recompositie, `CompositionLocal`, coroutines, levenscyclus en `ViewModel`);
- een gedetailleerde, bestand-voor-bestandbespreking van de Kotlin-client van de app RdvMedecins (OkHttp, kotlinx.serialization, SharedPreferences, Material 3);
- het draaien van de app op een emulator en op een telefoon, waarbij mobielspecifieke valkuilen aan bod komen (serveradres, `adb reverse`, onversleuteld HTTP-verkeer, schermrotatie, smalle schermen), het bouwen van een APK en een overzicht van Kotlin Multiplatform;
- een conclusie over wat is gebouwd en suggesties om verder te verkennen.

## Auteur

- **Hoofdauteur:** AI Claude (Anthropic)
- **Nagelezen door:** [Serge Tahé](https://stahe.github.io)
