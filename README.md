<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Dashboard Informasi Fasilitas Pelayanan dan SDM Kesehatan Indonesia Tahun 2016-2020

![dashboard](https://user-images.githubusercontent.com/107851682/174741865-102abc8e-ab2e-4b90-8873-bc861a483951.PNG)

Kesehatan merupakan hal penting dalam kehidupan, terutama dalam menjalankan semua aktivitas. Beberapa bagian dari kesehatan diantaranya adalah fasilitas pelayanan kesehatan dan sumber daya manusia di bidang kesehatan. Keduanya penting karena dalam memberikan pelayanan kesehatan diperlukan fasilitas pelayanan kesehatan yang baik dan sumber daya manusia kesehatan yang cukup untuk meminimalisir kemugkinan buruk terjadi. Dashboard informasi yang dibuat merupakan dashboard yang memberikan informasi tentang fasilitas pelayanan kesehatan di Indonesia dari tahun 2016 sampai 2020 disertai dengan sumber daya manusia kesehatannya. Fasilitas kesehatan yang di maksud terdiri dari puskesmas dan rumah sakit. Pada fasilitas kesehatan berupa rumah sakit, akan dibedakan berdasarkan kelas dan kepemilikannya. Selain itu, ditampilkan juga tentang rasio tempat tidur rumah sakit. Kemudian, pada sumber daya kesehatan terdiri dari jumlah tenaga kesehatan dan sumber daya manusia kesehatan. Oleh karena itu, infomasi data kesehatan sangat diperlukan dan dalam menampilkan data kesehatan tersebut dapat divisualisasikan dengan pembuatan dashboard informasi. Dashboard informasi dibuat mengunakan software Tableau dengan memvisualisasikan data dalam berbagai grafik seperti choropleth map, bar chart, line chart, dan lain-lain sesuai dengan karakteristik data dan tujuannya. Pembangunan dashboard informasi ini diharapkan dapat menampilkan data dalam bentuk yang lebih dipahami pengguna. Selain itu, penelitian ini didukung juga dengan pengujian usability dashboard menggunakan metode System Usability Scale (SUS).

Visualiasinya meliputi :

- Choropleth map, digunakan untuk memvisualisasikan pesebaran dari tenaga kesehatan menurut Provinsi.
- Line chart, digunakan untuk memvisualisasikan perkembangan SDM Kesehtan menurut jenisnya.
- Tree map, digunakan untuk memvisualisasikan Rumah Sakit di Indonesia menurut kepemilikan.
- Bar chart, digunakan untuk memvisualisasikan rasio tempat tidur rumah sakit per 1000 penduduk di Indonesia.
- Clustered bar chart, digunakan untuk memvisualisasikan Rumah Sakit di Indonesia menurut kelas..

Use the `BLANK_README.md` to get started.

<p align="right">(<a href="#top">back to top</a>)</p>

### Sumber Data

Data yang digunakan terdiri atas :

- Data Sekunder, data tentang fasilitas pelayanan kesehatan dan SDM kesehatan yang diperoleh dari publikasi Profil Kesehatan Indonesia tahun 2016-2020 yang meliputi :
  1. Jumlah Tenaga kesehatan Menurut Provinsi di Indonesia
  2. Sumber Daya Manusia Kesehatan Indonesia Menurut Jenis
  3. Rumah Sakit Berdasarkan Kelas di Indonesia
  4. Rumah Sakit Berdasarkan Kepemilikan di Indonesia
  5. Rasio Tempat Tidur Rumah Sakit Per 1.000 Penduduk di Indonesia Menurut Provinsi di Indonesia
- Data Primer, yaitu data yang dikumpulkan secara langsung. pada penelitian ini, data yang dikumpulkan berupa pertanyaan terkait uji System Usability Scale (SUS) yang digunakan untuk mengevaluasi dashboard yang telah dibuat.

<p align="right">(<a href="#top">back to top</a>)</p>

## Proses Pembuatan Dashboard

Proses pembuatan dashboard informasi yang dilakukan terdiri dari beberapa tahapan, yaitu :

1. Preprosesing data, meliputi pengumpulan data yang akan digunakan sebagai input dari tableau.
2. Implementasi dengan pembuatan dashboard informasi berdasarkan data yang dikumpulkan
3. Evaluasi dashboard dengan melakukan pengujian usability menggunakan metode system usability scale(SUS)

<!-- GETTING STARTED -->

## Preprosesing Data

Preprocessing data dilakukan dengan menggabungkan data yang diperlukan sesuai dengan variabel yang akan divisualisasikan. Kemudian memasukkannya ke dalam file microsoft excel untuk nantinya digunakan sebagai data input yang akan dimasukkan ke dalam tableau untuk dibuat visualisasinya.

## Implementasi

Pembuatan dashboard informasi fasilitas pelayanan dan sumber daya manusia kesehatan Indonesia menggunakan software Tableau.
Visualiasinya meliputi :

- Choropleth Map Persebaran Tenaga Kesehatan Indonesia Tahun 2016-2020. Choropleth map digunakan untuk melihat persebaran jumlah tenaga kesehatan di Indonesia menurut Provinsi untuk melihat perbedaan antarwilayah. Semakin gelap warna suatu Provinsi pada peta menunjukkan semakin banyak jumlah tenaga kesehatan di wilayah tersebut
- Line Chart Sumber Daya Manusia Kesehatan Indonesia Tahun 2016-2020. Line chart dibuat untuk menampilkan perkembangan sumber daya manusia kesehatan rumah sakit di Indonesia dari tahun 2016 hingga 2020. Pada dashboard informasi yang dibuat, Line chart bersifat dinamis dengan fungsi untuk memilih SDM kesehatan yang ingin dilihat perkembangannya dari tahun 2016 sampai 2020. Terdapat 16 pilihan dalam SDM kesehatan yang dapat dipilih, seperti dokter umum, dokter gigi, tenaga keperawatan, kefarmasian, kebidanan, dan lain-lain. Selain itu, terdapat pengkategorian juga berdasarkan fasilitas pelayanan kesehatannya yaitu Indonesia (keseluruhan di semua fasilitas kesehatan), puskesmas, dan rumah sakit.
- Cluster Bar Chart Rumah Sakit Berdasarkan Kelas di Indonesia Tahun 2016-2020. Clustered bar chart digunakan untuk membandingkan berbagai data sejenis dalam satu item. Pada visualisasi ini, clustered bar chart digunakan untuk merepresentasikan rumah sakit di Indonesia berdasarkan kelasnya.
- Tree Map Rumah Sakit Umum Berdasarkan Penyelenggaraan di Indonesia Tahun 2016-2020. Tree map dalam dashboard ini digunakan untuk melihat proporsi suatu kepemilikan rumah sakit dengan jumlah rumah sakit secara keseluruhan. Tree map yang dibuat akan sersifat dinamis dengan pilihan serupa tahun yang datanya ingin ditampilkan. Selain itu, akan muncul keterangan berupa jenis kepemilikan rumah sakitnya beserta jumlah rumah sakit yang tergolong dalam jenis itu. Semakin besar ukuran persegi tree map dan semakin pekat warnanya, maka semakin besar juga jumlah rumah sakitnya.
- Bar Chart Rasio Tempat Tidur Rumah Sakit Per 1.000 Penduduk di Indonesia Menurut Provinsi Tahun 2016-2020. Pada dashboard informasi fasilitas pelayanan dan SDM kesehatan Indonesia, Bar Chart dibuat untuk membandingkan rasio tempat tidur rumah sakit per 1000 penduduk. Bar chart yang dibuat bersifat dinamis dan interaktif. Fitur yang ada yaitu dapat memilih tahun dan urutan dari rasio tempat tidur masing-masing provinsi yang ingin ditampilkan, 10 provinsi dengan rasio tempat tidur teratas atau terbawah. Kemudian, ketika tanda panah diarahkan ke batang yang dipilih akan menampilkan informasi terkait nama provinsi yang dipilih dan rasio tempat tidurnya

## Evaluasi

Pada dashboard informasi fasilitas pelayanan dan sumber daya manusia kesehatan Indonesia tahun 2016-2020, metode yang digunakan yaitu System Usability Scale (SUS). Evaluasi dashboard dimulai dengan pembuatan kuesioner yang terdiri dari 10 pertanyaan utama dan beberapa pertanyaan tambahan seperti identitas responden menggunakan google form. Responden dalam evaluasi dashboard yang dibuat yaitu mahasiswa Politeknik Statistika STIS, tingkat 1-4, yang berjumlah 22 orang. Berdasarkan uji usabilitas menggunakan metode SUS, didapatkan rata-rata sebesar 78,41. Hal tersebut berarti dashboard informasi fasilitas pelayanan dan SDM Kesehatan Indonesia tahun 2016-2020 tergolong acceptable dengan grade scale C dan rating excellent. Dengan kata lain, dashboard yang dibuat sudah memenuhi standar usabilitas.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Link Penting

- [Sumber Data](https://www.kemkes.go.id/folder/view/01/structure-publikasi-pusdatin-profil-kesehatan.html)
- [Dashboard pada Tableau public](https://public.tableau.com/app/profile/zubaidah.pangestika/viz/DashboardFasilitasPelayanandanSDMKesehatan/Dashboard3)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

-

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Zubaidah Pangestika

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

-

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
