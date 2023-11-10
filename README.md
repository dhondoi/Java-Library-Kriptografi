<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">Kriptografi</h1>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
      <ul>
          <li><a href="#about-the-prototype">About The Prototype</a></li>
          <li><a href="#MonoAlphabet">MonoAlphabet</a></li>
          <li><a href="#PolyAlphabet">PolyAlphabet</a></li>
          <li><a href="#PolyAlphabet-Block">PolyAlphabet Block</a></li>
          <li><a href="#PolyAlphabet-Character">PolyAlphabet Character</a></li>
          <li><a href="#PolyAlphabet-Zigzag">PolyAlphabet Zigzag</a></li>
          <li><a href="#MonoAlphabet-Slide">MonoAlphabet Slide</a></li>
          <li><a href="#Vigenere-Numerical">Vigenere Numerical</a></li>
          <li><a href="#Vigenere-Alphabet">Vigenere Alphabet</a></li>
          <li><a href="#Play-Fair">Play Fair</a></li>
          <li><a href="#Transposition">Transposition</a></li>
          <li><a href="#Transposition-Zigzag">Transposition Zigzag</a></li>
          <li><a href="#Transposition-Triangle">Transposition Triangle</a></li>
          <li><a href="#Transposition-Spiral">Transposition Spiral</a></li>
          <li><a href="#Transposition-Diagonal">Transposition Diagonal</a></li>
      </ul>
</details>

<!-- ABOUT THE PROJECT -->
## About The Prototype

Prototipe kumpulan teknik kriptografi. Kriptografi bisa pula diartikan sebagai suatu ilmu atau seni menjaga keamanan pesan. Untuk mencoba, silahkan gunakan file .jar yang sudah terlampir.

![Theory][theory]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## MonoAlphabet

![MonoAlphabet][monoalphabet]

```java
 // siapkan teks yang akan di cipher dan jumlah pergeseran
 MonoAlphabet monoalphabet = new MonoAlphabet(text,range);
 String encrypt = monoalphabet.encrypt();
 System.out.println(encrypt);
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LINK BADGE & IMAGE-->
<!-- https://github.com/Ileriayo/markdown-badges -->

[theory]: images/theory.png
[monoalphabet]: images/monoalphabet.png
