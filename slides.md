---
theme: ./theme
background: >-
  https://images.unsplash.com/photo-1551269901-5c5e14c25df7?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=3450&q=80
class: text-center
lineNumbers: false
info: |
  ## Webfont Wizardry
title: Webfont Wizardry
---

# Webfont Wizardry

Darshak Parikh


---
layout: center
---

# OpenType features

---

## Alternate glyphs

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem;">Magizoology</p>

```css
font-family: 'Vollkorn';
font-feature-settings: normal;
```

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-feature-settings: 'ss01';">Magizoology</p>

```css
font-family: 'Vollkorn';
font-feature-settings: 'ss01';
```

---

## Ligatures

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-variant-ligatures: common-ligatures;">Niffler</p>

```css
font-family: 'Vollkorn';
font-variant-ligatures: common-ligatures; /* default */
```

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-variant-ligatures: no-common-ligatures;">Niffler</p>

```css
font-family: 'Vollkorn';
font-variant-ligatures: no-common-ligatures;
```

---

## Ligatures

<p style="margin: 4rem 0 3rem; font-family: 'Fira Code'; font-size: 6rem; font-variant-ligatures: contextual;">=> !== |></p>

```css
font-family: 'Fira Code';
font-variant-ligatures: contextual;
```

<p style="margin: 4rem 0 3rem; font-family: 'Fira Code'; font-size: 6rem; font-variant-ligatures: no-contextual;">=> !== |></p>

```css
font-family: 'Fira Code';
font-variant-ligatures: no-contextual;
```

---

## Figures

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-variant-numeric: lining-nums;">1234567890</p>

```css
font-family: 'Vollkorn';
font-variant-numeric: lining-nums;
```

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-variant-numeric: oldstyle-nums;">1234567890</p>

```css
font-family: 'Vollkorn';
font-variant-numeric: oldstyle-nums;
```

---

## Figures

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-variant-numeric: proportional-nums;">1234567890</p>

```css
font-family: 'Vollkorn';
font-variant-numeric: proportional-nums;
```

<p style="margin: 4rem 0 3rem; font-family: 'Vollkorn'; font-size: 6rem; font-variant-numeric: tabular-nums;">1234567890</p>

```css
font-family: 'Vollkorn';
font-variant-numeric: tabular-nums;
```

---

## Figures

|               |`tabular-nums`           |`proportional-nums`        |
|---------------|-------------------------|---------------------------|
|`lining-nums`  |even width, even height  |uneven width, even height  |
|`oldstyle-nums`|even width, uneven height|uneven width, unveen height|

---
layout: center
---

# Variable fonts

---

## Variable weight

<p style="margin: 2rem 0; font-family: 'Literata'; font-size: 4rem; font-weight: 600;">Grindelwald</p>

```css
font-family: 'Literata';
font-weight:  600;
```

<p style="margin: 2rem 0; font-family: 'Literata'; font-size: 4rem; font-weight: 666;">Grindelwald</p>

```css
font-family: 'Literata';
font-weight:  666;
```

<p style="margin: 2rem 0; font-family: 'Literata'; font-size: 4rem; font-weight: 700;">Grindelwald</p>

```css
font-family: 'Literata';
font-weight:  700;
```

---

## Optical size

<p style="margin: 2rem 0; font-family: 'Literata'; font-size: 4rem; font-optical-sizing: auto;">Dumbledore</p>

```css
font-family: 'Literata';
font-optical-sizing: auto;
```

<p style="margin: 2rem 0; font-family: 'Literata'; font-size: 4rem; font-optical-sizing: none;">Dumbledore</p>

```css
font-family: 'Literata';
font-optical-sizing: none;
```

<p style="margin: 2rem 0; font-family: 'Literata'; font-size: 4rem; font-variation-settings: 'opsz' 24;">Dumbledore</p>

```css
font-family: 'Literata';
font-variation-settings: 'opsz' 24;
```

---

## Wacky axes

---

## App support

---

## Resources

- [Wakamai Fondue](https://wakamaifondue.com/) by Roel Nieskens
- [Boiling eggs and fixing the variable font inheritance problem](https://pixelambacht.nl/2019/fixing-variable-font-inheritance/) by Roel Nieskens
- [Typography Tips](https://rwt.io/typography-tips) by Jason Pamental
- [v-fonts.com](https://v-fonts.com/)
- MDN Web Docs (duh)
