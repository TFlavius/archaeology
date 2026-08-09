# Opera Presto: цифровая археология / Digital Archaeology

**Читать на сайте: [tflavius.github.io/archaeology](https://tflavius.github.io/archaeology/)**<br />
**Read online: [tflavius.github.io/archaeology](https://tflavius.github.io/archaeology/)**

**[RU](#оглавление-ru)** | **[EN](#table-of-contents-en)**

---

## Оглавление [RU]

### Часть 1. Движок, который мы потеряли: цифровая археология Opera Presto

[Читать здесь](opera-presto-archaeology.md) · [читать на сайте](https://tflavius.github.io/archaeology/ru/)

* **[I. Эпоха до монополии: чем была Opera и почему её больше нет](opera-presto-archaeology.md#i-эпоха-до-монополии-чем-была-opera-и-почему-её-больше-нет)**
* **[II. Цифровая археология трёх миллионов строк кода](opera-presto-archaeology.md#ii-цифровая-археология-трёх-миллионов-строк-кода)**
  * [II.I Как собиралась Opera?](opera-presto-archaeology.md#iii-как-собиралась-opera)
  * [II.II Как писалась Opera?](opera-presto-archaeology.md#iiii-как-писалась-opera)
  * [II.III Как тестировалась Опера?](opera-presto-archaeology.md#iiiii-как-тестировалась-опера)
  * [II.IV Кем написана Опера?](opera-presto-archaeology.md#iiiv-кем-написана-опера)
* **[III. История одной лжи](opera-presto-archaeology.md#iii-история-одной-лжи)**
  * [III.I Нераспиливаемый монолит UI](opera-presto-archaeology.md#iiii-нераспиливаемый-монолит-ui)
  * [III.II Отговорки вместо исходников](opera-presto-archaeology.md#iiiii-отговорки-вместо-исходников)
* **[IV. Архитектурные бриллианты (и немного безумия)](opera-presto-archaeology.md#iv-архитектурные-бриллианты-и-немного-безумия)**
* **[V. Разморозка и проверка работоспособности](opera-presto-archaeology.md#v-разморозка-и-проверка-работоспособности)**
  * [V.I Переезд на OpenSSL](opera-presto-archaeology.md#vi-переезд-на-openssl)
  * [V.II Обновление стороннего кода](opera-presto-archaeology.md#vii-обновление-стороннего-кода)
  * [V.III Смерть Pike и другие приключения](opera-presto-archaeology.md#viii-смерть-pike-и-другие-приключения)
  * [V.IV Музей мёртвых фич](opera-presto-archaeology.md#viv-музей-мёртвых-фич)
* **[VI. Что дальше?](opera-presto-archaeology.md#vi-что-дальше)**

### Часть 2. Движок, который мы оживляем: новые трюки для Opera Presto

[Читать здесь](opera-presto-revival.md) · [читать на сайте](https://tflavius.github.io/archaeology/ru/revival/)

* **[VII. Есть только путь](opera-presto-revival.md#vii-есть-только-путь)**
* **[VIII. «Храповик»](opera-presto-revival.md#viii-храповик)**
* **[IX. Новые трюки](opera-presto-revival.md#ix-новые-трюки)**
  * [IX.I Документ, которого нет](opera-presto-revival.md#ixi-документ-которого-нет)
  * [IX.II Конвертер аргументов, опередивший время](opera-presto-revival.md#ixii-конвертер-аргументов-опередивший-время)
  * [IX.III Два бита](opera-presto-revival.md#ixiii-два-бита)
* **[X. Баги](opera-presto-revival.md#x-баги)**
* **[XI. Ещё бриллианты (и ещё безумие)](opera-presto-revival.md#xi-ещё-бриллианты-и-ещё-безумие)**
* **[XII. Прекрасная Опера будущего](opera-presto-revival.md#xii-прекрасная-опера-будущего)**

### Часть 3. Движок, который чему-то учится: современный JavaScript и древние баги Opera Presto

[Читать здесь](opera-presto-modern-js.md) · [читать на сайте](https://tflavius.github.io/archaeology/ru/modern/)

* **[XIII. Новый язык для старого Carakan](opera-presto-modern-js.md#xiii-новый-язык-для-старого-carakan)**
* **[XIV. Три смерти одной страницы](opera-presto-modern-js.md#xiv-три-смерти-одной-страницы)**
* **[XV. Схватка двух якодзун](opera-presto-modern-js.md#xv-схватка-двух-якодзун)**
* **[XVI. Как (и зачем) правильно притворяться](opera-presto-modern-js.md#xvi-как-и-зачем-правильно-притворяться)**
* **[XVII. Патчи для всего интернета и другие безумные находки](opera-presto-modern-js.md#xvii-патчи-для-всего-интернета-и-другие-безумные-находки)**
* **[XVIII. Что дальше](opera-presto-modern-js.md#xviii-что-дальше)**

### Часть 4. Движок, которому нужен CSS

[Читать здесь](opera-presto-modern-css.md) · [читать на сайте](https://tflavius.github.io/archaeology/ru/css/)

* **[XIX. Как завести CSS?](opera-presto-modern-css.md#xix-как-завести-css)**
* **[XX. Эффект домино](opera-presto-modern-css.md#xx-эффект-домино)**
* **[XXI. Что дальше?](opera-presto-modern-css.md#xxi-что-дальше)**

---

## Table of Contents [EN]

### Part 1. The Engine We Lost: Digital Archaeology of Opera Presto

[Read here](opera-presto-archaeology-en.md) · [read online](https://tflavius.github.io/archaeology/)

* **[I. The Pre-Monopoly Era: What Opera Was and Why It's Gone](opera-presto-archaeology-en.md#i-the-pre-monopoly-era-what-opera-was-and-why-its-gone)**
* **[II. Digital Archaeology of Three Million Lines of Code](opera-presto-archaeology-en.md#ii-digital-archaeology-of-three-million-lines-of-code)**
  * [II.I How was Opera Built?](opera-presto-archaeology-en.md#iii-how-was-opera-built)
  * [II.II How was Opera Written?](opera-presto-archaeology-en.md#iiii-how-was-opera-written)
  * [II.III How was Opera Tested?](opera-presto-archaeology-en.md#iiiii-how-was-opera-tested)
  * [II.IV Who Wrote Opera?](opera-presto-archaeology-en.md#iiiv-who-wrote-opera)
* **[III. A History of a Lie](opera-presto-archaeology-en.md#iii-a-history-of-a-lie)**
  * [III.I The Uncuttable UI Monolith](opera-presto-archaeology-en.md#iiii-the-uncuttable-ui-monolith)
  * [III.II Excuses Instead of Source Code](opera-presto-archaeology-en.md#iiiii-excuses-instead-of-source-code)
* **[IV. Architectural Diamonds (and a bit of madness)](opera-presto-archaeology-en.md#iv-architectural-diamonds-and-a-bit-of-madness)**
* **[V. Defrosting and Health Check](opera-presto-archaeology-en.md#v-defrosting-and-health-check)**
  * [V.I Moving to OpenSSL](opera-presto-archaeology-en.md#vi-moving-to-openssl)
  * [V.II Updating Third-Party Code](opera-presto-archaeology-en.md#vii-updating-third-party-code)
  * [V.III The Death of Pike and Other Adventures](opera-presto-archaeology-en.md#viii-the-death-of-pike-and-other-adventures)
  * [V.IV Museum of Dead Features](opera-presto-archaeology-en.md#viv-museum-of-dead-features)
* **[VI. What's Next?](opera-presto-archaeology-en.md#vi-whats-next)**

### Part 2. The Engine We're Bringing Back to Life: New Tricks for Opera Presto

[Read here](opera-presto-revival-en.md) · [read online](https://tflavius.github.io/archaeology/revival/)

* **[VII. This Is the Way](opera-presto-revival-en.md#vii-this-is-the-way)**
* **[VIII. The Ratchet](opera-presto-revival-en.md#viii-the-ratchet)**
* **[IX. New Tricks](opera-presto-revival-en.md#ix-new-tricks)**
  * [IX.I The Document That Doesn't Exist](opera-presto-revival-en.md#ixi-the-document-that-doesnt-exist)
  * [IX.II An Argument Converter Ahead of Its Time](opera-presto-revival-en.md#ixii-an-argument-converter-ahead-of-its-time)
  * [IX.III Two Bits](opera-presto-revival-en.md#ixiii-two-bits)
* **[X. Bugs](opera-presto-revival-en.md#x-bugs)**
* **[XI. More Gems (and More Madness)](opera-presto-revival-en.md#xi-more-gems-and-more-madness)**
* **[XII. The Beautiful Opera of the Future](opera-presto-revival-en.md#xii-the-beautiful-opera-of-the-future)**

### Part 3. The Engine That Learns: Modern JavaScript and Ancient Bugs of Opera Presto

[Read here](opera-presto-modern-js-en.md) · [read online](https://tflavius.github.io/archaeology/modern/)

* **[XIII. A New Language for the Old Carakan](opera-presto-modern-js-en.md#xiii-a-new-language-for-the-old-carakan)**
* **[XIV. Three Deaths of a Single Page](opera-presto-modern-js-en.md#xiv-three-deaths-of-a-single-page)**
* **[XV. The Clash of Two Yokozunas](opera-presto-modern-js-en.md#xv-the-clash-of-two-yokozunas)**
* **[XVI. How (and Why) to Properly Pretend](opera-presto-modern-js-en.md#xvi-how-and-why-to-properly-pretend)**
* **[XVII. Patches for the Entire Internet and Other Insane Discoveries](opera-presto-modern-js-en.md#xvii-patches-for-the-entire-internet-and-other-insane-discoveries)**
* **[XVIII. What's Next](opera-presto-modern-js-en.md#xviii-whats-next)**

### Part 4. The Engine That Needs CSS

[Read here](opera-presto-modern-css-en.md) · [read online](https://tflavius.github.io/archaeology/css/)

* **[XIX. How Do You Get CSS Running?](opera-presto-modern-css-en.md#xix-how-do-you-get-css-running)**
* **[XX. The Domino Effect](opera-presto-modern-css-en.md#xx-the-domino-effect)**
* **[XXI. What's Next?](opera-presto-modern-css-en.md#xxi-whats-next)**
