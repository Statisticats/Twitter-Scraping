# Twitter Data Scraping dan Exploration
Dalam repository ini, dilakukan scraping data Twitter menggunakan R, eksplorasi data dan network analysis menggunakan Python. Scraping dilakukan pada pukul 22.00 29 April 2022 - 22.00 6 Mei 2022 dengan menggunakan kata kunci **"mudik"**. Penarikan data dilakukan setiap pukul 12.00 dan pukul 22.00. Secara keseluruhan terdapat 156,059 _unique tweet_ yang berasal dari 88,514 _unique account_. 

## Twitter Scraping
Scraping dilakukan pada pukul 22.00 29 April 2022 - 22.00 6 Mei 2022 dengan menggunakan kata kunci **"mudik"**. Scraping dilakukan dengan menggunakan R dengan library **"rtweet"**. Setiap pengambilan diambil sebanyak 18.000 _tweet_ terbaru tanpa memasukkan _tweet_ yang merupakan _retweet_ dari _tweet_ lainnya.

## Twitter Data Exploration
### Package yang digunakan
<ol>
  <li>pandas</li>
  <li>isodate</li>
  <li>numpy</li>
  <li>seaborn</li>
  <li>sklearn</li>
  <li>matplotlib</li>
  <li>squarify</li>
</ol>

### Eksplorasi
<ol>
  <li>Banyak dan rata-rata tweet per jam</li>
  <li>Akun dengan tweet mudik terbanyak</li>
  <li>Treemap hashtag</li>
  <li>Akun yang paling banyak dimention</li>
  <li>Tweet yang paling banyak diretweet</li>
</ol>

## Phrase Network Analysis
Phrase Network Analysis dilakukan dengan menggunakan frasa 2 kata yang sering digunakan pada _tweet_ dengan kata kunci "mudik". Dengan menggunakan network analysis dapat diketahui kata apa saja yang dikaitkan dengan kata "mudik" dan kata apa saja yang dianggap "penting" dalam network tersebut. 

### Package yang digunakan
<ol>
  <li>pandas</li>
  <li>re</li>
  <li>Sastrawi</li>
  <li>nltk</li>
  <li>sklearn</li>
  <li>numpy</li>
  <li>networkx</li>
  <li>matplotlib</li>
  <li>operator</li>
</ol>

### Tahapan
<ol>
  <li>Praproses data</li>
  <li>Mendapatkan N-gram sebagai frasa</li>
  <li>Melakukan network analysis</li>
</ol>

## User Network Analysis
### Package yang digunakan
<ol>
  <li>pandas</li>
  <li>numpy</li>
  <li>networkx</li>
  <li>matplotlib</li>
  <li>seaborn</li>
</ol>

### Tahapan
<ol>
  <li>Praproses data</li>
  <li>Network Akun yang terverifikasi</li>
  <li>Network Akun yang tidak terverifikasi</li>
</ol>

## Find more
Instagram : <a href="https://www.instagram.com/statisticats.co">statisticats.co</a>

Medium    : <a href="https://medium.com/@statisticats">Statisticats</a>

## Contributors
<ul>
  <li>Aisyah Fadila          : <a href="https://github.com/Aisyahfdl14">@AisyahFdl14</a></li> 
  <li>Nindi Pigitha          : <a href="https://github.com/pigithanindi">@pigithanindi</a></li>
  <li>Tiara Lutfiah Adisti   : <a href="https://github.com/adisti24">@adisti24</a></li>
</ul>
