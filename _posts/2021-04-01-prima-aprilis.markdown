---
layout: post
title:  "Tabelki na PrimaAprilis"
date:   2015-12-15
description: Bartek wyjaśnia jak w Markdown'nie robić tabelki.
---

Filozoji wielkiej tu nie ma - tabelki się "maluje" klawiaturą.

<pre>
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
</pre>


| Tabelki                     | Są               | Spoko |
| ----------------------------|:----------------:| -----:|
| kolumna 3 jest do prawej    | right-aligned    | $1600 |
| Kolumna 2 jest wyśrodkowana | centered         |   $12 |
| Wiersze malowane jak zebra? | lepiej sie czyta |    $1 |


Brzydki przykład, który mimo to działa:
- zwenętrzne `|` nie są wymagane
- "rury" nie muszą być w linji jak wyżej
- minimum 3 pauzy zeby odzielić nagłówek
- W środku nadal działa formatowanie

<pre>
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
</pre>

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
