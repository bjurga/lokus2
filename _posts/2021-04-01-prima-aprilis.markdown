---
layout: post
title:  "Tabelki na PrimaAprilis"
description: Bartek wyjaśnia jak w Markdown'nie robić tabelki.
---

Filozoji wielkiej tu nie ma - tabelki się "maluje" klawiaturą.

{%- highlight markdown -%}
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
{%- endhighlight -%}


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

{%- highlight markdown -%}
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
{%- endhighlight -%}

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
