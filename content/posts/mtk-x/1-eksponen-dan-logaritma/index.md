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
> **Definisi 1.3** Untuk $ a $ bilangan real dan $ a \not = 0, m $ bilangan bulat positif, didefinisikan dengan $ a^{-m} = \left(\vcenter{\hbox{$\cfrac{1}a$}}\right)^m $
>> **Contoh 1.3 :** Jika nilai $ x = -2 $ dan $ y = 2 $, tentukan nilai $ x^{-3}\left(y^4\right)! $
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned} x^{-3}\left(y^4\right) &= \left(\vcenter{\hbox{$\cfrac{1}x$}}\right)^3\left(y^4\right) \\\\ &= \left(\cfrac{1^3}{x^3} \right).\left(y^4 \right) \\\\ &= \left(\cfrac{1}{x^3} \right).\left(y^4 \right) \\\\ &= \cfrac{y^4}{x^3} \\\\ &= \cfrac{2^4}{(-2)^3} \\\\ &= \cfrac{16}{-8} \\\\ &= -2 \end{aligned} $$
{{< /admonition >}}

### 1.3 Pangkat Nol
> **Definisi 1.4** Untuk $ a $ bilangan real dan $ a \not = 0 $ , maka $ a^0 = 1 $
>> **Contoh 1.4 :** $ 2^0 = 1, 5^0=1, \left(\cfrac{2}{3}\right)^0=1 $

### 1.4 Sifat-sifat Pangkat Bulat Positif
> **Sifat-1** Jika $ a $ bilangan real, $m$ dan $n$ bilangan bulat positif maka $a^m \times a^n = a^{m+n}$.
>> **Contoh :** Berapakah $2^4 \times 2^3$ ?
{{< admonition tip "Pembahasan" >}}
$$  \begin{aligned}  2^4 \times 2^3 &= 2^{4+3} \\\\  &= 2^7  \end{aligned} $$
{{< /admonition >}}

> **Sifat-2** Jika $ a $ bilangan real dan $a \not = 0$, $m$ dan $n$ bilangan bulat positif maka $\cfrac{a^m}{a^n} = a^{m-n}$.
>> **Contoh :** Berapakah $\cfrac{2^5}{2^3}$ ?
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
$a^{\tfrac{p}{q}}=c$, sehingga $c=\sqrt[q]{a^p}$
---
> **Sifat-4** Misalkan $a$ adalah bilangan real dan $a \not = 0$, dengan $a>0, \cfrac{p}{n}$ dan $\cfrac{m}{n}$ adalah bilangan pecahan $n \not = 0$.
Jika $n, q \ge 2$, maka $\left(a^{\frac{m}{n}}\right)\left(a^{\frac{p}{n}}\right)=\left(a^{\frac{m+p}{n}}\right)$.
___
> **Sifat-5** Jika $a$ adalah bilangan real dan $a \not = 0$ dengan $a>0, \cfrac{m}{n}$ dan $\cfrac{p}{q}$ bilangan pecahan $q, n\not=0$, maka $\left(a^{\frac{m}{n}}\right)\left(a^{\frac{p}{q}}\right)=\left(a^{\frac{m}{n}+\frac{p}{q}}\right)$.

### 1.6 Kuis
> **Petunjuk Kuis**
\
Kerjakan soal-soal kuis berikut di kertas kemudian hasil jawaban dikirimkan dalam bentuk PDF $\to$ {{< link "https://forms.gle/Mz3byTjp6N6dhdSM9" Form_Tugas "Form Pengumpulan Tugas!" >}}

{{< admonition question "1. Sederhanakanlah operasi bilangan berpangkat berikut:" >}}
- [x] $2^5 \times 2^9 \times 2^{12}=$
- [x] $\cfrac{2^5 \times 3^5 \times 4^2}{12^2}=$
{{< /admonition >}}

{{< admonition question "2. Dengan menggunakan sifat bilangan berpangkat, sederhanakanlah bentuk berikut:" >}}
- [x] $2x^3 \times 7x^4 \times (3x)^2=$
- [x] $\cfrac{-4a^3 \times 2b^5}{\cfrac{8a}{b}}=$
{{< /admonition >}}

{{< admonition question "3. Hitunglah hasil operasi bilangan berpangkat berikut:" >}}
- [x] $\left(-\cfrac{2}{3} \right)^4 \times \left(\cfrac{1}{2} - \cfrac{1}{6} \right)^2$
- [x] $\cfrac{3x^2 \times y^3}{24x} \times (2y)^2$ untuk $x=2$ dan $y=3$
{{< /admonition >}}

{{< admonition question "4. Tentukan nilai $x$ yang memenuhi:" >}}
- [x] $2^x = 8$
- [x] $4^x = 0,125$
{{< /admonition >}}

{{< image src="/images/avatar.webp" caption="avatar (`image`)" >}}

<!--- ---------------Logaritma-------------------- -->
## 2 LOGARITMA
### 2.1 Bentuk akar
Pengakaran (penarikan akar) suatu bilangan merupakan inversi dari pemangkatan suatu bilangan. Dengan kata lain **akar** adalah kebalikan dari **bilangan berpangkat**. Akar dilambangkan dengan notasi "$\sqrt{}$".
> **Definisi 1.7** Misalkan $a$ bilangan real dan $n$ bilangan bulat positif. $\sqrt[n]{a}$ disebut bentuk akar jika dan hanya jika hasil $\sqrt[n]{a}$ adalah bilangan irrasional.
>> Bilangan irrasional yang menggunakan tanda akar ($\sqrt{}$) dinamakan _bentuk akar_. Tetapi tidak semua bilangan yang Berada dalam tanda akar merupakan bilangan irrasional.
\
Contoh: $\sqrt{25}$ dan $\sqrt{64}$ bukan termasuk bentuk akar, karena jika disederhanakan $\sqrt{25}$ menjadi 5 dan $\sqrt{64}$ menjadi 8, keduanya bukan bilangan irrasional.

### 2.2 Operasi pada Bentuk akar
#### 2.2.1 Operasi Penjumlahan dan Pengurangan Bentuk Akar
> Operasi penjumlahan dan pengurangan pada bentuk akar dapat dilakukan apabila bentuk akarnya senama. Bentuk akar senama adalah bentuk akar yang mempunyai eksponen dan basis sama.
$$ {\fcolorbox{red}{aqua}{$p\sqrt[n]{r}+q\sqrt[n]{r}=(p+q)\sqrt[n]{r}$}} $$
$$ {\fcolorbox{red}{aqua}{$p\sqrt[n]{r}-q\sqrt[n]{r}=(p-q)\sqrt[n]{r}$}} $$

> **Contoh 1.6** Tentukan hasil penjumlahan dan pengurangan berikut dalam bentuk yang sederhana!
{{< admonition question "$3\sqrt{5}+4\sqrt{5}=$" >}}
$$  \begin{aligned}  3\sqrt{5}+4\sqrt{5} &= (3+4)\sqrt{5} \\\\  &= 7\sqrt{5} \end{aligned} $$
{{< /admonition >}}
{{< admonition question "$\sqrt{5}+\sqrt{3}=$" >}}
(tidak dapat disederhanakan karena akarnya tidak senama, $5 \not = 3$)
{{< /admonition >}}
{{< admonition question "$2\sqrt[3]{4}-3\sqrt[3]{4}=$" >}}
$$  \begin{aligned}  2\sqrt[3]{4}-3\sqrt[3]{4} &= (2-3)\sqrt[3]{4} \\\\  &= -\sqrt[3]{4} \end{aligned} $$
{{< /admonition >}}
{{< admonition question "$3\sqrt[3]{x}-\sqrt[3]{x}=$" >}}
$$  \begin{aligned}  3\sqrt[3]{x}-\sqrt[3]{x} &= (3-1)\sqrt[3]{x} \\\\  &= 2\sqrt[3]{x} \end{aligned} $$
{{< /admonition >}}

#### 2.2.2 Operasi Perkalian dan Pembagian Bentuk Akar
Sifat perkalian dan pembagian bentuk akar dapat dicermati pada beberapa contoh berikut:
> **Contoh 1.7** Sederhanakan bentuk akar berikut:
{{< admonition question "$\sqrt[3]{8}$" >}}
$$  \begin{aligned} \sqrt[3]{8} &= \sqrt[3]{2^3} \\\\ &= 2^{\frac{3}{3}} \\\\ &= 2^1 \\\\ &= 2 \end{aligned} $$
{{< /admonition >}}
{{< admonition question "$\sqrt[6]{64}$" >}}
$$  \begin{aligned} \sqrt[6]{64} &= \sqrt[6]{2^6} \\\\  &= 2^{\frac{6}{6}} \\\\ &= 2^1 \\\\ &= 2 \end{aligned} $$
{{< /admonition >}}
{{< admonition question "$4\sqrt[3]{5} \times 2\sqrt[3]{7}$" >}}
$$  \begin{aligned} 4\sqrt[3]{5} \times 2\sqrt[3]{7} &= (4 \times 2)(\sqrt[3]{5 \times 7}) \\\\  &= 8 \sqrt[3]{35} \end{aligned} $$
{{< /admonition >}}
{{< admonition question "$3\sqrt[5]{5} \times 5\sqrt[7]{5}$" >}}
$$  \begin{aligned} 3\sqrt[5]{5} \times 5\sqrt[7]{5} &= (3 \times 5)(5^{\frac{1}{5}} \times 5^{\frac{1}{7}}) \\\\  &= 15(5^{\frac{12}{35}}) \\\\ &= 15 \sqrt[35]{5^{12}} \end{aligned} $$
{{< /admonition >}}
{{< admonition question "$\cfrac{3\sqrt[3]{4}}{4\sqrt[3]{5}}$" >}}
$$  \begin{aligned} \cfrac{3\sqrt[3]{4}}{4\sqrt[3]{5}} &= \cfrac{3}{4}\sqrt[3]{\cfrac{4}{5}} \end{aligned} $$
{{< /admonition >}}

#### 2.2.3 Merasionalkan Penyebut Bentuk Akar
* > **Merasionalkan bentuk $\cfrac{p}{\sqrt{q}}$** \
Bentuk $\cfrac{p}{\sqrt{q}}$ dirasionalkan dengan cara mengalikan dengan sekawannya, yaitu $\cfrac{\sqrt{q}}{\sqrt{q}}$
$$  \begin{aligned} \cfrac{p}{\sqrt{q}} &= \cfrac{p}{\sqrt{q}}.\cfrac{\sqrt{q}}{\sqrt{q}} \\\\ &= \cfrac{p}{q}\sqrt{q} \end{aligned} $$
{{< admonition question "Contoh: Rasionalkan penyebut dari $\cfrac{2}{\sqrt{3}}$" >}}
Karena sekawan dari penyebut ($\sqrt{3}$) adalah $\sqrt{3}$, maka
$$  \begin{aligned} \cfrac{2}{\sqrt{3}} &= \cfrac{2}{\sqrt{3}} \times {\fcolorbox{red}{aqua}{$\cfrac{\sqrt{3}}{\sqrt{3}}$}} \to sekawan  \\\\ &= \cfrac{2 \times \sqrt{3}}{\sqrt{3}\times \sqrt{3}} \\\\ &= \cfrac{2 \sqrt{3}}{3} \to \cfrac{2}{3}\sqrt{3} \end{aligned} $$
{{< /admonition >}}

* > **Merasionalkan bentuk $\cfrac{r}{p+\sqrt{q}} ~, \cfrac{r}{p-\sqrt{q}} ~, \cfrac{r}{\sqrt{p}+\sqrt{q}} ~, \cfrac{r}{\sqrt{p}-\sqrt{q}}$** \
Bentuk $(p+\sqrt{q})$ dan bentuk $(p-\sqrt{q})$ saling sekawan, bentuk $(\sqrt{p}+\sqrt{q})$ dan $(\sqrt{p}-\sqrt{q})$ juga saling sekawan. Jika perkalian bentuk sekawan tersebut dilakukan maka dapat merasionalkan bentuk akar.
{{< admonition question "Contoh-1: Rasionalkan penyebut dari $\cfrac{2}{4+\sqrt{3}}$" >}}
Karena sekawan dari penyebut ($4+\sqrt{3}$) adalah $4-\sqrt{3}$, maka
$$  \begin{aligned} \cfrac{2}{4+\sqrt{3}} &= \cfrac{2}{4+\sqrt{3}} \times {\fcolorbox{red}{aqua}{$\cfrac{4-\sqrt{3}}{4-\sqrt{3}}$}} \to sekawan  \\\\ &= \cfrac{2 \times (4-\sqrt{3})}{(4+\sqrt{3})\times (4-\sqrt{3})} \\\\ &= \cfrac{2(4) - (2\sqrt{3})}{4(4)-\sqrt{3}(\sqrt{3})} \\\\ &= \cfrac{8-2\sqrt{3}}{16-3} \\\ &= \cfrac{8-2\sqrt{3}}{13} \to \frac{8}{13}-\cfrac{2}{13}\sqrt{3} \end{aligned} $$
{{< /admonition >}}
{{< admonition question "Contoh-2: Rasionalkan penyebut dari $\cfrac{3}{\sqrt{2}-\sqrt{5}}$" >}}
Karena sekawan dari penyebut $\left( \sqrt{2}-\sqrt{5} \right)$ adalah $\left(\sqrt{2}+\sqrt{5} \right)$, maka
$$  \begin{aligned} \cfrac{3}{\sqrt{2}-\sqrt{5}} &= \cfrac{3}{\sqrt{2}-\sqrt{5}} \times {\fcolorbox{red}{aqua}{$\cfrac{\sqrt{2}+\sqrt{5}}{\sqrt{2}+\sqrt{5}}$}} \to sekawan  \\\\ &= \cfrac{3(\sqrt{2}+\sqrt{5})}{(\sqrt{2}-\sqrt{5})(\sqrt{2}+\sqrt{5})} \\\\ &= \cfrac{3(\sqrt{2}+\sqrt{5})}{(\sqrt{2}.\sqrt{2})-(\sqrt{5}.\sqrt{5})} \\\\ &= \cfrac{3(\sqrt{2}+\sqrt{5})}{4-5} \\\\ &= \cfrac{3(\sqrt{2}+\sqrt{5})}{-1} \\\\ &= -3(\sqrt{2}+\sqrt{5}) \to \fcolorbox{red}{aqua}{$-3\sqrt{2}-3\sqrt{5}$} \end{aligned} $$
{{< /admonition >}}

* > **Menyederhanakan bentuk $\sqrt{(p+q)\pm2{\sqrt{pq}}}$** \
{{< admonition question "Contoh-1: Sederhanakan $\sqrt{8+2{\sqrt{15}}}$" >}}
$$  \begin{aligned} \sqrt{\textcolor{blue}{8}+2{\sqrt{\textcolor{green}{15}}}} &= \sqrt{(\textcolor{blue}{5}+\textcolor{blue}{3})+2{\sqrt{\textcolor{green}{5\times3}}}} \\\\ &= \sqrt{\textcolor{blue}{5}+2{\sqrt{\textcolor{green}{5\times3}}}+\textcolor{blue}{3}} \to \fcolorbox{blue}{yellow}{$\sqrt{p+2{\sqrt{p\times q}}+q} = \sqrt{\left(\sqrt{p}+\sqrt{q} \right)^2}$} \\\\ &= \sqrt{\left(\sqrt {5}+ \sqrt{3} \right)^2} \\\\ &= \sqrt{5}+\sqrt {3} \end{aligned} $$
{{< /admonition >}}
{{< admonition question "Contoh-2: Sederhanakan $\sqrt{9-4{\sqrt{5}}}$" >}}
$$  \begin{aligned} \sqrt{\textcolor{blue}{9}-4{\sqrt{5}}} &=  \sqrt{\textcolor{blue}{5}-4{\sqrt{5}}+\textcolor{blue}{4}} \\\\ &= \sqrt{\left(\sqrt {5} - 2 \right)^2} \\\\ &= \sqrt{5} - 2 \end{aligned} $$
{{< /admonition >}}
### 2.3 Konsep Logaritma
> **Definisi 1.8** Misalkan $a, b, c \in R, a>0, a \not= 1, $ dan $b>0$ maka ${^a}\log{b}=c$ jika dan hanya jika ${a^c}=b$
>> **Keterangan:** \
$a$ disebut basis ($0<a<1$ atau $a>1$)\
$b$ disebut numerus ($b>0$)\
$c$ disebut hasil logaritma

Berdasarkan definisi di atas, perhatikan contoh berikut!
{{< admonition question "Ubahlah ke bentuk logaritma" >}}
* $2^x=5 \Harr x={^2}\log{5}$ (notasi $\Harr$ dibaca **jika dan hanya jika**)
* $3^y=8 \Harr y={^3}\log{8}$
* $5^z=3 \Harr z={^5}\log{3}$
{{< /admonition >}}
{{< admonition tip "Catatan" >}}
* Jika logaritma dengan basis $e$ ($e$ adalah bilangan ***Euler***, $e \approx$ 2,718)
* Bilangan pokok (basis) 10 tidak ditulis, sehingga $^{10}\log{a}=\log{a}$
{{< /admonition >}}

> **Definisi 1.9** Fungsi Logaritma adalah suatu fungsi yang didefinisikan oleh $y=f(x)= {^a}\log {x}$ dengan $a$ bilangan real, $a>0, a \not= 1$ serta $x>0$.\
$x$ adalah variabel (peubah bebas) dan $a$ adalah bilangan pokok atau basis.
### 2.4 Sifat-sifat Logaritma
{{< admonition tip "Sifat-1">}}
Untuk $a, b$, dan $c$ bilangan real positif, $a \not= 1$, dan $b>0$, berlaku $\fcolorbox{red}{aqua}{${^a\log{(b \times c)}=~ ^a\log b+~ ^a\log c}$}$
{{< /admonition >}}
{{< admonition tip "Sifat-2">}}
Untuk $a, b$, dan $c$ bilangan real dengan $a>0, a \not= 1$, dan $b>0$, berlaku $\fcolorbox{red}{aqua}{${^a\log{\left( \cfrac {b}{c} \right) }=~ ^a\log b-~ ^a\log c}$}$
{{< /admonition >}}
{{< admonition tip "Sifat-3">}}
Untuk $a, b$, dan $n$ bilangan real, $a>0, b>0$, dan $a \not= 1$, berlaku $\fcolorbox{red}{aqua}{${^a\log{b^n}=~ n.^a\log b}$}$
{{< /admonition >}}
{{< admonition tip "Sifat-4">}}
Untuk $a, b$, dan $c$ bilangan real positif, $a \not= 1, b \not= 1$, dan $c \not= 1$, berlaku $\fcolorbox{red}{aqua}{${^a\log{b}=~ \cfrac{^c \log{b}}{^c \log{a}}}=\cfrac{1}{^b \log{a}}$}$
{{< /admonition >}}
{{< admonition tip "Sifat-5">}}
Untuk $a, b$, dan $c$ bilangan real positif dengan $a \not= 1$ dan $c \not= 1$, berlaku $\fcolorbox{red}{aqua}{${^a\log{b} \times ~^b\log{c} =~ ^a\log{c}}$}$
{{< /admonition >}}
{{< admonition tip "Sifat-6">}}
Untuk $a$ dan $b$ bilangan real positif dengan $a \not= 1$, berlaku $\fcolorbox{red}{aqua}{${{^a}^m\log b^n =~ \frac{n}{m}(^a\log b)}$}$
{{< /admonition >}}
{{< admonition tip "Sifat-7">}}
Untuk $a$ dan $b$ bilangan real positif, $a \not= 1$, berlaku $\fcolorbox{red}{aqua}{$a^{^a\log{b}}=b$}$
{{< /admonition >}}
### 2.5 Kuis



<!--- Placeholder
> **Title** description.
>> **Example**
{{< admonition tip "Pembahasan" >}}

Pembahasan ditulis di sini
$$  \begin{aligned}  a &= b+c \\\\  &= d+f  \end{aligned} $$

{{< /admonition >}}
-->
