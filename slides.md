---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1551269901-5c5e14c25df7?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=3450&q=80
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
# highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Webfont Wizardry
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

|               |`proportional-nums`      |`tabular-nums`           |
|---------------|-------------------------|-------------------------|
|`lining-nums`  |uneven width, even height|even width and height    |
|`oldstyle-nums`|uneven width and height  |even width, uneven height|

---
layout: center
---

# Variable fonts

---

## Variable weight

Mephisto
Literata
`font-weight: 666;`

---

## Optical size

The Watcher
Literata
`font-size: 24px;`

---

## Wacky axes

---

## App support

---

## Resources

- Wakamai Fondue
- Scrambled Eggs
- Axis Praxis
