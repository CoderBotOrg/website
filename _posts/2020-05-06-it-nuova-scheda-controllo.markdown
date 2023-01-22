---
layout: it/post
title: "Nuova scheda di controllo per CoderBot"
subtitle: "Nuova scheda di controllo con I/O aggiuntivi che consente di pilotare gli encoder dei motori e altro ancora."
splash: "blog/coderbot_control_board_v5_splash.png"
date: 2020-05-08 10:00:00
category: blog
tags: news
author: CoderBot
language: it
---

![coderbot_control_board_v5]({{site.baseurl}}/img/blog/coderbot_control_board_v5.jpg)

CoderBot è basato sul computer di bordo Raspberry Pi, su cui è montata una scheda di controllo di sensori e attuatori personalizzata (denominata Raspberry Pi "hat") per collegare il Raspberry Pi a sensori e attuatori.

![coderbot_control_board_v5]({{site.baseurl}}/img/blog/coderbot_control_board_v5_design.png)

Siamo lieti di presentare un "hat" di controllo del motore completamente riprogettato che espande le opzioni di input e output disponibili per i programmatori CoderBot.

La nuova scheda offre diverse nuove funzionalità:

- Supporto per due encoder digitali dei motori
- Piattaforma inerziale integrata (MPU) con accelerometro, giroscopio e bussola
- Atmega328p integrato per fornire 12 GPIO digitali aggiuntivi (ingresso/uscita) e 2 ingressi analogici
 -Supporto per un sensore a ultrasuoni aggiuntivo

Gli encoder digitali vengono utilizzati dal software CoderBot per migliorare il movimento direzionale regolando la potenza del motore tramite un algoritmo PID.

La MPU può essere utilizzata nei blocchi di programmazione a blocchi e può essere utilizzata come input nei programmi creati dall'utente.

Anche gli ingressi e le uscite atmega328p sono integrati nel software e sono accessibili tramite blocchi speciali per leggere o scrivere sui GPIO aggiuntivi.

Oltre alle funzionalità avanzate, la nuova scheda ha anche un design meccanico migliorato, ha le dimensioni standard per Raspberry Pi e presenta fori sui bordi per un montaggio sicuro sulla parte superiore del Raspberry Pi.