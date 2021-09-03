---
title: "1 Geometri Dimensi Tiga"
date: 2021-08-22T19:33:55+07:00
author: "Ferilee"
authorLink: "https://t.me/ferilee"
description: ""
resources:
- name: "featured-image"
  src: "featured-image.webp"
- name: "featured-image-preview"
  src: "featured-image-preview.webp"

tags: ["Geometri"]
categories: ["Matematika-XII"]

lightgallery: true

toc:
  auto: false
---

Discover what the Hugo - **FeelIt** theme is all about and the core-concepts behind it. tes teks

{{< myshortcodes >}}

{{< mermaid >}}
graph LR;
    A[Dimensi Tiga] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}


<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/w7Ft2ymGmfc?autoplay=1" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div>



<!--more-->

## 1 JARAK ANTAR TITIK
## 2 JARAK TITIK KE GARIS
## 3 JARAK TITIK KE BIDANG

> {{< admonition tip "Aturan Sinus" >}}
Untuk sembarang segitiga $ABC$, dengan panjang sisi-sisi $a, b, c$ dan $\angle~A, \angle~B, \angle~C$, berlaku:
$$ {\fcolorbox{red}{aqua}{${\cfrac{a}{sin A}}={\cfrac{b}{sin B}}={\cfrac{c}{sin C}}$}} $$
{{< /admonition >}}
>> **Contoh 1 :** Perhatikan segitiga $ABC$ berikut. Panjang $AB=8, BC=8 \sqrt{2}, AC=b, \angle BAC=45 \degree , \angle ACB = y \degree $ dan $\angle ABC = x \degree $. Tentukan panjang $b$ !
{{< admonition tip "Alternatif Penyelesaian" >}}
* Dengan menggunakan aturan sinus, maka diperoleh:
$$  \begin{aligned} \cfrac{BC}{sin~A}=\cfrac{AB}{sin~y\degree} &\iff \cfrac{8\sqrt{2}}{sin~45\degree} = \cfrac{8}{sin~y\degree} \\\\ &\iff \cfrac{8\sqrt{2}}{\cfrac{1}{2}\sqrt{2}} = \cfrac{8}{sin~y\degree} \\\\ &\iff 16 = \cfrac{8}{sin~y\degree} \\\\ &\iff sin~y\degree = \cfrac{1}{2} \\\\ &\iff y\degree = 30\degree \end{aligned} $$
Jumlah ketiga sudut pada segitiga adalah $\angle A + \angle B + \angle C = 180\degree$, sehingga $45\degree + 30\degree + x\degree = 180\degree \to x\degree = 105\degree$.
* Dengan menggunakan aturan sinus kembali, maka diperoleh:
$$ \begin{aligned} \cfrac{AC}{sin~x\degree}=\cfrac{AB}{sin~y\degree} &\iff \cfrac{b}{sin~105\degree} = \cfrac{8}{sin~30\degree} \\\\ &\iff \cfrac{b}{sin~105\degree} = \cfrac{8}{\frac{1}{2}} \\\\ &\iff \cfrac{b}{sin~105\degree} = 16 \\\\ &\iff b = 16.sin~105\degree \end{aligned} $$
Dengan memanfaatkan tabel sinus atau kalkulator maka diperoleh:
$$ \begin{aligned} b &= 16.sin~105\degree \\\\ &= 16 \times 0,9659 \\\\ &= 15,4548 \end{aligned} $$
Jadi, panjang sisi $AC$ adalah 15,4548 satuan panjang.
{{< /admonition >}}

## 2 ATURAN COSINUS
> {{< admonition tip "Aturan Cosinus" >}}
Untuk sembarang segitiga $ABC$, dengan panjang sisi-sisi $a, b, c$ dan $\angle~A, \angle~B, \angle~C$, berlaku:
$$ {\fcolorbox{red}{aqua}{$a^2=b^2+c^2-2bc.cos~A$}} $$
$$ {\fcolorbox{red}{aqua}{$b^2=a^2+c^2-2ac.cos~B$}} $$
$$ {\fcolorbox{red}{aqua}{$c^2=a^2+b^2-2ab.cos~C$}} $$

{{< /admonition >}}
>> **Contoh 1 :** Perhatikan segitiga $ABC$ berikut. Panjang $AB=8, BC=8 \sqrt{2}, AC=b, \angle BAC=45 \degree , \angle ACB = y \degree $ dan $\angle ABC = x \degree $. Tentukan panjang $b$ !
{{< admonition tip "Alternatif Penyelesaian" >}}
* Dengan menggunakan aturan sinus, maka diperoleh:
$$  \begin{aligned} \cfrac{BC}{sin~A}=\cfrac{AB}{sin~y\degree} &\iff \cfrac{8\sqrt{2}}{sin~45\degree} = \cfrac{8}{sin~y\degree} \\\\ &\iff \cfrac{8\sqrt{2}}{\cfrac{1}{2}\sqrt{2}} = \cfrac{8}{sin~y\degree} \\\\ &\iff 16 = \cfrac{8}{sin~y\degree} \\\\ &\iff sin~y\degree = \cfrac{1}{2} \\\\ &\iff y\degree = 30\degree \end{aligned} $$
Jumlah ketiga sudut pada segitiga adalah $\angle A + \angle B + \angle C = 180\degree$, sehingga $45\degree + 30\degree + x\degree = 180\degree \to x\degree = 105\degree$.
* Dengan menggunakan aturan sinus kembali, maka diperoleh:
$$ \begin{aligned} \cfrac{AC}{sin~x\degree}=\cfrac{AB}{sin~y\degree} &\iff \cfrac{b}{sin~105\degree} = \cfrac{8}{sin~30\degree} \\\\ &\iff \cfrac{b}{sin~105\degree} = \cfrac{8}{\frac{1}{2}} \\\\ &\iff \cfrac{b}{sin~105\degree} = 16 \\\\ &\iff b = 16.sin~105\degree \end{aligned} $$
Dengan memanfaatkan tabel sinus atau kalkulator maka diperoleh:
$$ \begin{aligned} b &= 16.sin~105\degree \\\\ &= 16 \times 0,9659 \\\\ &= 15,4548 \end{aligned} $$
Jadi, panjang sisi $AC$ adalah 15,4548 satuan panjang.
{{< /admonition >}}

## 3 LUAS SEGITIGA
> **Definisi 1.4** Untuk $ a $ bilangan real dan $ a \not = 0 $ , maka $ a^0 = 1 $
>> **Contoh 1.4 :** $ 2^0 = 1, 5^0=1, \left(\cfrac{2}{3}\right)^0=1 $



## 4 KUIS
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
