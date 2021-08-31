---
title: "1 Eksponen Dan Logaritma"
date: 2021-08-22T19:33:55+07:00
author: "Ferilee"
authorLink: "https://t.me/ferilee"
description: ""
resources:
- name: "featured-image"
  src: "featured-image.webp"
- name: "featured-image-preview"
  src: "featured-image-preview.webp"

tags: ["Eksponen dan Logaritma"]
categories: ["Matematika-X"]

lightgallery: true
math: true
toc:
  auto: false
---

Discover what the Hugo - **FeelIt** theme is all about and the core-concepts behind it.

<!--more-->

## 1 EKSPONEN
### 1.1 Konsep Eksponen
> **Definisi 1.1** Misalkan $ a $ bilangan real dan $ n $ bilangan bulat positif. $ a^n $ adalah hasil kali bilangan $ a $ sebanyak $ n $ faktor, dapat ditulis $ a^n = \underbrace{a \times a \times a \times ... \times a}_{\text{n faktor}} $ dengan $ a $ sebagai basis bilangan pokok dan $ n $ sebagai pangkat.
>> **Contoh 1.1 :** $ 4^3 = 4 \times 4 \times 4 $
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned}  4^3 &= 4 \times 4 \times 4 \\\\  &= 64  \end{aligned} $$
{{< /admonition >}}

> **Definisi 1.2**
>> Fungsi Eksponen adalah suatu fungsi yang dinyatakan dalam bentuk $ y = f(x) = a(b^{cx}) $ dengan $ a, b, $ dan $ c $ bilangan real.
{{< admonition note "Keterangan" >}}
$x$ adalah variabel

$b$ adalah bilangan pokok atau basis

$c$ adalah koefisien $x$

$cx$ adalah eksponen dari $b$
{{< /admonition >}}

### 1.2 Pangkat Bulat Negatif
> **Definisi 1.3** Untuk $ a $ bilangan real dan $ a \not = 0, m $ bilangan bulat positif, didefinisikan dengan $ a^{-m} = \left(\vcenter{\hbox{$\frac{1}a$}}\right)^m $
>> **Contoh 1.3 :** Jika nilai $ x = -2 $ dan $ y = 2 $, tentukan nilai $ x^{-3}\left(y^4\right)! $
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned} x^{-3}\left(y^4\right) &= \left(\vcenter{\hbox{$\frac{1}x$}}\right)^3\left(y^4\right) \\\\ &= \left(\frac{1^3}{x^3} \right).\left(y^4 \right) \\\\ &= \left(\frac{1}{x^3} \right).\left(y^4 \right) \\\\ &= \frac{y^4}{x^3} \\\\ &= \frac{2^4}{(-2)^3} \\\\ &= \frac{16}{-8} \\\\ &= -2 \end{aligned} $$
{{< /admonition >}}

### 1.3 Pangkat Nol
> **Definisi 1.4** Untuk $ a $ bilangan real dan $ a \not = 0 $ , maka $ a^0 = 1 $
>> **Contoh 1.4 :** $ 2^0 = 1, 5^0=1, \left(\frac{2}{3}\right)^0=1 $

### 1.4 Sifat-sifat Pangkat Bulat Positif
> **Sifat-1** Jika $ a $ bilangan real, $m$ dan $n$ bilangan bulat positif maka $a^m \times a^n = a^{m+n}$.
>> **Contoh :** Berapakah $2^4 \times 2^3$ ?
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned}  2^4 \times 2^3 &= 2^{4+3} \\\\  &= 2^7  \end{aligned} $$
{{< /admonition >}}

> **Sifat-2** Jika $ a $ bilangan real dan $a \not = 0$, $m$ dan $n$ bilangan bulat positif maka $\frac{a^m}{a^n} = a^{m-n}$.
>> **Contoh :** Berapakah $\frac{2^5}{2^3}$ ?
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned}  \frac{2^5}{2^3} &= 2^{5-3} \\\\  &= 2^2 \\\\ &= 4  \end{aligned} $$
{{< /admonition >}}

> **Sifat-3** Jika $a$ bilangan real dan $a \not = 0$, $m$ dan $n$ bilangan bulat positif maka $\left(a^m \right)^n = a^{mn}$.
>> **Contoh :** Berapakah $\left(3^2 \right)^3$ ?
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned}  \left(3^2 \right)^3 &= 3^{(2 \times 3)} \\\\  &= 3^6 \end{aligned} $$
{{< /admonition >}}

### 1.5 Pangkat Pecahan
> **Definisi 1.5** Misalkan $a$ bilangan real dan $a \not = 0, m$ dan $n$ bilangan bulat positif maka $a^{\frac{m}{n}} = \left({a}^\frac{1}{n}\right)^m$.
\
> **Definisi 1.6** Misalkan $a$ bilangan real dan $a \not = 0$ dengan $a>0, \frac{p}{q}$ adalah bilangan pecahan $q \not = 0, q \ge 2$.
\
$a^{\frac{p}{q}}=c$, sehingga $c=\sqrt[q]{a^p}$
---
> **Sifat-4** Misalkan $a$ adalah bilangan real dan $a \not = 0$, dengan $a>0, \frac{p}{n}$ dan $\frac{m}{n}$ adalah bilangan pecahan $n \not = 0$.
Jika $n, q \ge 2$, maka $\left(a^{\frac{m}{n}}\right)\left(a^{\frac{p}{n}}\right)=\left(a^{\frac{m+p}{n}}\right)$.
___
> **Sifat-5** Jika $a$ adalah bilangan real dan $a \not = 0$ dengan $a>0, \frac{m}{n}$ dan $\frac{p}{q}$ bilangan pecahan $q, n\not=0$, maka $\left(a^{\frac{m}{n}}\right)\left(a^{\frac{p}{q}}\right)=\left(a^{\frac{m}{n}+\frac{p}{q}}\right)$.

### 1.6 Kuis
1. Sederhanakanlah operasi bilangan berpangkat berikut:
  - [x] $2^5 \times 2^9 \times 2^{12}=$
  [x] $\cfrac{2^5 \times 3^5 \times 4^2}{12^2}=$
2. Dengan menggunakan sifat bilangan berpangkat, sederhanakanlah bentuk berikut:
  * $2x^3 \times 7x^4 \times (3x)^2$
  * $\cfrac{-4a^3 \times 2b^5}{\cfrac{8a}{b}}$
3. Hitunglah hasil operasi bilangan berpangkat berikut:
  * $\left(-\cfrac{2}{3} \right)^4 \times \left(\cfrac{1}{2} - \cfrac{1}{6} \right)^2$
  * $\cfrac{3x^2 \times y^3}{24x} \times (2y)^2$ untuk $x=2$ dan $y=3$
4. Tentukan nilai $x$ yang memenuhi:
  * $2^x = 8$
  * $4^x = 0,125$

<!--- ---------------Logaritma-------------------- -->
## 2 LOGARITMA
### 2.1 Bentuk akar
### 2.2 Hubungan Bentuk Akar dan Bilangan Berpangkat
### 2.3 Operasi pada Bentuk akar
#### 2.3.1 Operasi Penjumlahan dan Pengurangan Bentuk Akar
#### 2.3.2 Operasi Perkalian dan Pembagian Bentuk Akar
#### 2.3.3 Merasionalkan Penyebut Bentuk Akar
### 2.4 Konsep Logaritma
### 2.5 Sifat-sifat Logaritma
### 2.6 Kuis



<!--- Placeholder
> **Title** description.
>> **Example**
{{< admonition tip "Pembahasan" >}}

Pembahasan ditulis di sini
$$  \begin{aligned}  a &= b+c \\\\  &= d+f  \end{aligned} $$

{{< /admonition >}}
-->
