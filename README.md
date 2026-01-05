<p align="center">
<img src="https://raw.githubusercontent.com/adriahf/titita/refs/heads/main/logo.png" alt="Titità Logo" width="200" style="border-radius: 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

<h1 align="center">Titità ♫ ♩ - Entrenador de Ritme</h1>

<p align="center">
<strong>Una aplicació web interactiva per entrenar la precisió rítmica, gamificada i accessible per a tothom.</strong>
</p>
<br>

## 📖 Sobre el projecte

**Titità** és un joc educatiu musical dissenyat per millorar la precisió rítmica de músics, estudiants i aficionats. A través d'una interfície neta i moderna, els usuaris han d'escoltar patrons rítmics i reproduir-los (clicant o prement espai) amb la màxima exactitud possible.

L'aplicació està construïda com una **SPA (Single Page Application)** lleugera, sense necessitat de backend ni bases de dades, utilitzant tecnologies web estàndard i llibreries d'àudio avançades per garantir una latència mínima.

## ✨ Funcionalitats Clau

* **📅 Repte Diari:** Un puzle rítmic únic generat cada dia a partir de la data actual. Tothom juga el mateix nivell cada dia!

* **🏆 Mode Campanya:** 100 nivells de dificultat progressiva ("The Rhythm Journey"), des de negres simples fins a tresets, síncopes i tempos ràpids.

* **🔀 Mode Aleatori:** Practica sense límits amb ritmes generats proceduralment.

* **⚙️ Sistema de Calibratge:** Algoritme integrat per detectar i compensar la latència de dispositius Bluetooth o pantalles tàctils.

* **🌐 Multi-idioma:** Traducció automàtica a **Català, Castellà i Anglès** segons la configuració del navegador (amb selector manual).

* **📊 Anàlisi Visual:** Gràfics detallats post-partida per veure exactament on t'has avançat o endarrerit (en mil·lisegons).

* **💾 Persistència Local:** El progrés i les puntuacions es guarden al navegador de l'usuari (localStorage).

## 🛠️ Tecnologies Utilitzades

El projecte segueix la metodologia **KISS** (Keep It Simple, Stupid), evitant frameworks pesats innecessaris.

* **HTML5 / CSS3:** Disseny responsiu adaptat a mòbils i escriptori.

* **JavaScript (Vanilla ES6+):** Tota la lògica del joc, generació de nivells i gestió d'estat.

* [**Tone.js**](https://tonejs.github.io/)**:** Per a la síntesi d'àudio precisa i la planificació temporal (scheduling) crítica per a la música.

* [**VexFlow**](https://www.vexflow.com/)**:** Per al renderitzat dinàmic i vectorial de les partitures musicals en format SVG.


## 🤝 Contribucions

Aquest projecte és de codi obert i està pensat per circular lliurement! Si ets desenvolupador, músic o docent i vols millorar-lo:

1. Fes un **Fork** del projecte.

2. Crea una branca per a la teva millora (`git checkout -b feature/NovaFuncionalitat`).

3. Fes **Commit** dels canvis (`git commit -m 'Afegida nova funcionalitat'`).

4. Fes **Push** a la branca (`git push origin feature/NovaFuncionalitat`).

5. Obre un **Pull Request**.

## 📄 Llicència

Aquest projecte està distribuït sota la **Llicència Pública General GNU v3.0 (GNU GPLv3)**.

Això significa que ets lliure de:

* Utilitzar el programa per a qualsevol propòsit.

* Estudiar com funciona i modificar-lo.

* Redistribuir còpies.

* Millorar el programa i fer públiques les millores.

*Sempre que les versions modificades es distribueixin sota la mateixa llicència lliure.*

<p align="center">Fet amb ❤️ i ritme.</p>
