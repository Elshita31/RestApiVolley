<h2>REST API VOLLEY</h2>
<h3>Apa itu Rest Api?</h3>
<pre>
      API adalah singkatan dari Application Programming Interface yaitu sebuah software
  yang memungkinkan para developer untuk mengintegrasikan dan mengizinkan dua aplikasi yang
  berbeda secara bersamaan untuk saling terhubung satu sama lain.
      Tujuan penggunaan dari API adalah untuk saling berbagi data antar aplikasi yang berbeda
  tersebut, dan juga untuk mempercepat proses pengembangan aplikasi dengan cara menyediakan
  sebuah function yang terpisah sehingga para developer tidak perlu lagi membuat fitur yang
  serupa.
      Cara kerja dari RESTful API yaitu REST client akan melakukan akses pada
  data/resource pada REST server dimana masing-masing resource. Atau data/resource tersebut
  akan dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
  Jadi, Nantinya data yang diberikan oleh REST server itu bisa berupa format text, JSON atau
  XML. Dan saat ini format yang paling populer dan paling banyak digunakan adalah format
  JSON.
</pre>
<h3>Apa perbedaan dari Rest Api Volley dan Retrofit</h3>
<h4>Rest Api Volley</h4>
<pre>
      Volley adalah library HTTP yang mempermudah dan yang terpenting mempercepat networking untuk aplikasi Android.
  Tetapi Library buatan Google ini kurang populer dibanding kedua Library sebelumnya,
  karena fitur yang dimilikinya pun sedikit.
      Secara default, Volley menggunakan metode sinkronisasi. Jadi kalian tidak perlu membuat sebuah Method
  atau fungsi yang menggunakan Class Asynctask. Dalam penggunaannya memang 'sedikit' sulit.
  Volley tidak cocok untuk operasi download atau streaming yang besar karena Volley menyimpan semua respons
  dalam memori selama mengambil data API.
</pre>

<h4>Rest Api Retrofit</h4>
<pre>
      Retrofit ini merupakan Library turunan dari OkHTTP yang dibuat oleh Square yang digunakan sebagai
  REST Client pada Android, yang pasti akan memudahkan kita. Karena kita tidak perlu lagi untuk membuat
  Method sendiri untuk menggunakan REST Client API dari Backend.
      Library ini menyediakan framework yang powerfull untuk authenticating dan 
  berinteraksi dengan API dengan mengirimkan request menggunakan OkHTTP. Library Retrofit ini juga banyak 
  digunakan oleh perusahaan-perusahaan Startup dalam aplikasi Mobile-nya, salah satunya Tokopedia dan OVO. 
  Tidak hanya itu, aplikasi Sosmed yang kita gunakan sehari-hari juga menggunakan Library Retrofit.
</pre>

<h3>Screenshot Project RestAPI Volley</h3>
<h5>Pada project ini menampilkan karakter-karakter dari game Dota</h5>
Menu Utama | Full Project
--- | ---
![main_page] | ![full_page]

[main_page]: https://github.com/Elshita31/RestApiVolley/blob/master/1.jpeg
[full_page]: https://github.com/Elshita31/RestApiVolley/blob/master/2.gif

