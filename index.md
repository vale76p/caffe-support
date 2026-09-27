---
title: Supporto · Support
---

# Caffè

[Italiano](#italiano) · [English](#english) · [Privacy](privacy.html)

## Italiano

Caffè tiene sveglio il Mac dalla barra dei menu: scegli una durata e il Mac non va in
stop finché il tempo non è scaduto.

**Serve aiuto?** Apri una segnalazione su
[github.com/vale76p/caffe-support/issues](https://github.com/vale76p/caffe-support/issues):
descrivi cosa succede e indica la versione di Caffè (in fondo al pannello) e di macOS.

**Domande frequenti**

- *Dov'è l'app?* Caffè vive solo nella barra dei menu: cerca l'icona ☕ in alto a destra.
  Non compare nel Dock.
- *Come si spegne?* Con l'interruttore del pannello, portando lo slider su Spento o con un
  clic destro sull'icona. Uscendo da Caffè (⌘Q) il Mac torna a dormire normalmente.
- *Come verifico che funzioni?* Nel Terminale, `pmset -g assertions` mostra le asserzioni
  di nome "Caffe" mentre è acceso.
- *Sistema non tiene sveglio il Mac a batteria.* È voluto: macOS consente di bloccare lo
  stop del sistema solo con l'alimentatore collegato.

## English

Caffè keeps your Mac awake from the menu bar: pick a duration and your Mac won't sleep
until time is up.

**Need help?** Open an issue at
[github.com/vale76p/caffe-support/issues](https://github.com/vale76p/caffe-support/issues):
describe what happens and include your Caffè version (at the bottom of the panel) and
your macOS version.

**FAQ**

- *Where is the app?* Caffè lives only in the menu bar: look for the ☕ icon at the top
  right. It doesn't appear in the Dock.
- *How do I turn it off?* With the switch in the panel, by moving the slider to Off, or by
  right-clicking the icon. When you quit Caffè (⌘Q) your Mac sleeps normally again.
- *How can I check it works?* In Terminal, `pmset -g assertions` lists assertions named
  "Caffe" while it is on.
- *System doesn't keep my Mac awake on battery.* That's by design: macOS only lets apps
  prevent system sleep while the charger is connected.
