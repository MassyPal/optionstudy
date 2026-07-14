# Guida Completa ai Marcatori Markdown

Questo documento raccoglie tutte le possibili combinazioni di Marcatori Markdown con relative descrizioni. Per ogni elemento trovi la **sintassi** (cosa scrivere) e l'**anteprima** (come appare).

---

## 1. Titoli (Headings)

I titoli si creano con il simbolo `#` seguito da uno spazio.

### Sintassi
```markdown
# Titolo di livello 1
## Titolo di livello 2
### Titolo di livello 3
#### Titolo di livello 4
##### Titolo di livello 5
###### Titolo di livello 6
```

### Anteprima

# Titolo di livello 1
## Titolo di livello 2
### Titolo di livello 3
#### Titolo di livello 4
##### Titolo di livello 5
###### Titolo di livello 6

---

## 2. Formattazione del Testo

### Grassetto

**Sintassi:**
```markdown
**testo in grassetto**
__testo in grassetto__
```

**Anteprima:**

**testo in grassetto**

__testo in grassetto__

---

### Corsivo

**Sintassi:**
```markdown
*testo in corsivo*
_testo in corsivo_
```

**Anteprima:**

*testo in corsivo*

_testo in corsivo_

---

### Grassetto e Corsivo

**Sintassi:**
```markdown
***testo in grassetto e corsivo***
___testo in grassetto e corsivo___
```

**Anteprima:**

***testo in grassetto e corsivo***

___testo in grassetto e corsivo___

---

### Barrato

**Sintassi:**
```markdown
~~testo barrato~~
```

**Anteprima:**

~~testo barrato~~

---

### Sottolineato (estensione)

**Sintassi:**
```markdown
<u>testo sottolineato</u>
```

**Anteprima:**

<u>testo sottolineato</u>

---

### Codice inline

**Sintassi:**
```markdown
`codice inline`
```

**Anteprima:**

`codice inline`

---

## 3. Elenchi

### Elenco non ordinato

**Sintassi:**
```markdown
- Elemento 1
- Elemento 2
  - Sotto-elemento 2.1
  - Sotto-elemento 2.2
- Elemento 3

* Alternativa con asterisco
+ Alternativa con più
```

**Anteprima:**

- Elemento 1
- Elemento 2
  - Sotto-elemento 2.1
  - Sotto-elemento 2.2
- Elemento 3

* Alternativa con asterisco
+ Alternativa con più

---

### Elenco ordinato

**Sintassi:**
```markdown
1. Primo elemento
2. Secondo elemento
3. Terzo elemento
```

**Anteprima:**

1. Primo elemento
2. Secondo elemento
3. Terzo elemento

---

### Elenco con caselle di spunta (Checklist)

**Sintassi:**
```markdown
- [ ] Task da fare
- [x] Task completato
```

**Anteprima:**

- [ ] Task da fare
- [x] Task completato

---

## 4. Link

### Link inline

**Sintassi:**
```markdown
[Testo del link](https://esempio.com)

[Link con titolo](https://esempio.com "Titolo opzionale")
```

**Anteprima:**

[Testo del link](https://esempio.com)

[Link con titolo](https://esempio.com "Titolo opzionale")

---

### Link a sezioni del documento

**Sintassi:**
```markdown
[Vai ai titoli](#1-titoli-headings)
```

**Anteprima:**

[Vai ai titoli](#1-titoli-headings)

---

### Link automatico

**Sintassi:**
```markdown
<https://esempio.com>
<email@esempio.com>
```

**Anteprima:**

https://esempio.com

email@esempio.com

---

## 5. Immagini

**Sintassi:**
```markdown
![Testo alternativo](https://esempio.com/immagini/foto.jpg)

![Immagine con titolo](https://esempio.com/immagini/foto.jpg "Titolo immagine")
```

**Anteprima:**

![Testo alternativo](https://via.placeholder.com/150)

![Immagine con titolo](https://via.placeholder.com/150 "Titolo immagine")

---

### Immagine con dimensioni (HTML)

**Sintassi:**
```markdown
<img src="https://via.placeholder.com/150" width="100" height="100">
```

**Anteprima:**

<img src="https://via.placeholder.com/150" width="100" height="100">

---

## 6. Citazioni (Blockquotes)

**Sintassi:**
```markdown
> Questa è una citazione su una riga

> Questa è una citazione
> su più righe

> Citazione nidificata
>> Citazione di secondo livello
```

**Anteprima:**

> Questa è una citazione su una riga

> Questa è una citazione
> su più righe

> Citazione nidificata
>> Citazione di secondo livello

---

## 7. Codice

### Blocco di codice inline

**Sintassi:**
```markdown
Ecco un esempio: `console.log('Hello')`
```

**Anteprima:**

Ecco un esempio: `console.log('Hello')`

---

### Blocco di codice multilinea

**Sintassi:**
````markdown
```
function hello() {
  console.log('Hello World');
}
```
````

**Anteprima:**

```
function hello() {
  console.log('Hello World');
}
```

---

### Blocco di codice con linguaggio (Syntax Highlighting)

**Sintassi:**
````markdown
```javascript
function hello() {
  console.log('Hello World');
}
```

```python
def hello():
    print("Hello World")
```

```html
<div>Ciao</div>
```
````

**Anteprima:**

```javascript
function hello() {
  console.log('Hello World');
}
```

```python
def hello():
    print("Hello World")
```

```html
<div>Ciao</div>
```

---

## 8. Linee Orizzontali

**Sintassi:**
```markdown
---

***

___
```

**Anteprima:**

---

***

___

---

## 9. Tabelle

**Sintassi:**
```markdown
| Colonna 1 | Colonna 2 | Colonna 3 |
|-----------|-----------|-----------|
| Dato 1    | Dato 2    | Dato 3    |
| Dato 4    | Dato 5    | Dato 6    |
```

**Anteprima:**

| Colonna 1 | Colonna 2 | Colonna 3 |
|-----------|-----------|-----------|
| Dato 1    | Dato 2    | Dato 3    |
| Dato 4    | Dato 5    | Dato 6    |

---

### Tabella con allineamenti

**Sintassi:**
```markdown
| Sinistra | Centrato | Destra |
|:---------|:--------:|-------:|
| testo    |  testo   |  testo |
```

**Anteprima:**

| Sinistra | Centrato | Destra |
|:---------|:--------:|-------:|
| testo    |  testo   |  testo |

---

## 10. Note a piè di pagina

**Sintassi:**
```markdown
Questo è un testo con una nota.[^1]

[^1]: Questa è la nota a piè di pagina.
```

**Anteprima:**

Questo è un testo con una nota.[^1]

[^1]: Questa è la nota a piè di pagina.

---

## 11. Liste di definizioni

**Sintassi:**
```markdown
Termine 1
: Definizione del termine 1

Termine 2
: Prima definizione
: Seconda definizione
```

**Anteprima:**

Termine 1
: Definizione del termine 1

Termine 2
: Prima definizione
: Seconda definizione

---

## 12. Emoji

**Sintassi:**
```markdown
🎉 🚀 ✅ ❌ 🔥 💡 📝
:smile: :heart: :thumbsup:
```

**Anteprima:**

🎉 🚀 ✅ ❌ 🔥 💡 📝

---

## 13. HTML Inline

**Sintassi:**
```markdown
Ecco un <strong>testo in grassetto</strong> con HTML.

Emoji: 🎉 🚀 ✅

<cite>Citazione HTML</cite>
```

**Anteprima:**

Ecco un <strong>testo in grassetto</strong> con HTML.

Emoji: 🎉 🚀 ✅

<cite>Citazione HTML</cite>

---

## 14. Escape dei caratteri

Alcuni caratteri speciali possono essere preceduti da `\` per essere visualizzati letteralmente:

**Sintassi:**
```markdown
\* Questo asterisco non crea un elenco
\# Questo hash non crea un titolo
\[ Questo non crea un link
\`Questo\` non è codice
```

**Anteprima:**

\* Questo asterisco non crea un elenco

\# Questo hash non crea un titolo

\[ Questo non crea un link

\`Questo\` non è codice

---

## 15. Combinazioni utili

### Codice in grassetto

**Sintassi:**
```markdown
**`codice in grassetto`**
```

**Anteprima:**

**`codice in grassetto`**

---

### Link con codice

**Sintassi:**
```markdown
[`console.log()`](https://developer.mozilla.org)
```

**Anteprima:**

[`console.log()`](https://developer.mozilla.org)

---

### Immagine con link

**Sintassi:**
```markdown
[![Testo](https://via.placeholder.com/100)](https://esempio.com)
```

**Anteprima:**

[![Testo](https://via.placeholder.com/100)](https://esempio.com)

---

### Task list avanzata

**Sintassi:**
```markdown
- [ ] **Task importante**
- [x] Task completato con *enfasi*
- [ ] Task con [`codice`]
```

**Anteprima:**

- [ ] **Task importante**
- [x] Task completato con *enfasi*
- [ ] Task con [`codice`]

---

## Riepilogo rapido

| Marcatore | Risultato |
|-----------|-----------|
| `#` - `######` | Titoli (H1-H6) |
| `**testo**` | **Grassetto** |
| `*testo*` | *Corsivo* |
| `~~testo~~` | ~~Barrato~~ |
| `` `testo` `` | `Codice` |
| `-` o `*` | • Elenco |
| `1.` | 1. Elenco ordinato |
| `- [ ]` | ☐ Checklist |
| `[testo](url)` | [Link](#4-link) |
| `![alt](url)` | [Immagine](#5-immagini) |
| `> ` | > Citazione |
| ` ``` ` | Blocco codice |
| `---` | Linea orizzontale |
| `\|` | Tabella |

---

*Guida generata per comprendere la struttura dei file Markdown*