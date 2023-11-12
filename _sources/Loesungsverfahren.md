---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.15.2
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

+++ {"editable": true, "slideshow": {"slide_type": ""}}

# Lösungsverfahren

In der mathematischen Anwendung werden immer wieder Verfahren benötigt, mit deren Hilfe eine Gleichung geläst werden kann.
Mit Gleichung lösen ist hierbei gemeint, dass jenes Unbekannte $x$ gefunden wird, welche die Gleichung wahr werden lässt.

+++ {"editable": true, "slideshow": {"slide_type": ""}}

## Anwendungen
Der Klassiker ist die Bestimmung von $x$, unter welchem die Funktion $f(x)$ einen Wert $a$ annimmt.

```{prf:example} Stelle finden
:label: "EinText
Wenn wird beispielsweise wissen wollen, bei welchem $x$ die Funktion mit der Vorschrift $0,5x^3-17x$ den Funktionswert $29$ annimmt, starten wir unsere Suche mit dem Ansatz:

$$
\begin{align*}
f(x)&=29\\\
0,5x^3-17x&=29
\end{align*}
$$

Um die Gleichung $0,5x^3-17x=29$ lösen zu können, brauchen wir die Lösungsverfahren. (Hier: S.d.N und pq-Formel)
```

Der wohl bekannteste, gesuchte Funktionswert ist die $0$.  

```{code-cell} ipython3
---
editable: true
slideshow:
  slide_type: ''
---

```
