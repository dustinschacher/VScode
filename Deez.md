# Deez
% Prasentation in Markdown
% Referent: Dustin Schacher
% Date: \today


---
theme: "AnnArbor"
header-includes:
colortheme: "albatross"
fonttheme: "structurebold"
---

# Erste Folie
Dies ist eine Markdown Präsentation
````bash
pandoc -t beamer <filename.md> -o <praesentationname>.pdf
````
# Aufzählung

- punkt 1 mit *kursivem Text*
- punkt 2 mit **fettem Text**
- punkt 3 mit

# Formeln und Quoting
**Merke**
Markdown und Pandoc sind cool und mächtig.

$$ \int_a \limits ^\infty
\frac{x^2-a}{e^{x-b}}
$$

# Bilder einbinden
deez