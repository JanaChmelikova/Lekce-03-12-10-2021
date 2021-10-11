# HTML a CSS 1: lekce 03

---

Podzim 2021, Praha (12. října 2021)

---

# Pozicování
![CSS Position Property](https://miro.medium.com/max/2000/1*8OQ7qwYSCuVVwGFTC82KrQ.png)

<small>Credit for  [Geronimo Morisot Morla
](https://medium.com/@geromorla/css-position-property-starters-guide-3602431df059)</small>


---

# Vlastnost position

- Říkáme jak má být prvek na stránce umístěný

---

# Position: static

- Mají implicitně všechny prvky
- Prvek se zobrazí tam, kde na něj vyjde řada

---

# Position: relative

- Prvek posune relativně vůči jeho výchozí pozici, prvek zůstává v přirozeném toku stránky na své půvpdní pozici
- Vůči tomuto prvku mohu pozicovat další s vlastností position: absolute
- Vlastnosti <kbd>top</kbd>, <kbd>left</kbd>, <kbd>right</kbd>, <kbd>bottom</kbd> určují posun vůči výchozí pozici
- Záporná hodnota posouvá v opačném směru

---

# Position: absolute

- Prvek zcela vyjme z toku dokumentu a lze jej libovolně umístit
- Pozicuje se vzhledem ke svému nejbližšímu rodiči který nemá position: static
- Pokud takový rodič neexistuje, pozicuje se vůči stránce
- Zároveň z něj může být “kotva” pro další prvek s pozicí absolute

---

# Vzájemné překrývání prvků

- Standardní pořadí, jak jsou v dokumentu
- Prvky které nemají position: static jsou ve vrstvě nahoře
- Lze řídit přes vlastnost <kbd>z-index</kbd>

---

# Position: fixed
- Zůstává na obrazovce i když posouvám obrazovku
- Stejně jako pozice absolute, i tato vyjímá prvek z přirozeného toku stránky
- Zabírá použitý prostor na obrazovce
- Pozor na mobily!!!

---

# Position: sticky
- Kombinace relative a fixed
- Prvek se posouvá tak, aby byl vidět uvnitř svého rodiče

# Zadání prvního povinného domácího úkolu
- https://classroom.github.com/a/0OmaTeWN
