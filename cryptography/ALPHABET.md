# ALPHABET
#cryptography #ALPHABET #ctfr #LAY0UT_team 

Soal :

> Apa yang kalian ketahui tentang Alphabet, Sebuah Huruf A sampai Z dan Angka 0 sampai 9 kan. Nah saya beri Contoh tentang Enkripsi ini "Ayam" akan menjadi "Alfa Yankee Alfa Mike". Enkripsi nya sangat simpel, kita hanya mencocokkan huruf paling depannya saja, tapi bagaimana dengan angka ? Contoh "123" akan menjadi "One Two Three". Sudah paham kan sampe sini, Nah coba decode Flag ini  
> 
> Flag : **Charlie Tango Foxtrot Romeo { Sierra One Mike Papa Lima Three _ Four Lima Papa Hotel Four Bravo Three Tango }**  
_Selalu ingat yaa, Format Flag harus Kapital_

Penyelesaian :
Berdasarkan penjelasan dari soal tersebut, maka dapat saya simpulkan bahwa enkripsi yang digunakan bernama [NATO phonetic alphabet](https://en.wikipedia.org/wiki/NATO_phonetic_alphabet) . Biasanya untuk menyelesaiakn soal dengan tipe seperti ini, kita cukup mengamati huruf awal dari setiap kata saja untuk mendapatkan pesan yang aslinya(Flagnya), namun kita juga dapat menggunakan tools online jika string yang akan didecrypt terlalu panjang

![alphabt](https://user-images.githubusercontent.com/46299092/130033850-af9e6167-d1c5-4126-95ee-4dda2f6fcb77.png)


Link : [NATO phonetic alphabet online translator — Cryptii](https://cryptii.com/pipes/nato-phonetic-alphabet)

##### Note : Jangan lupa, untuk mengubah stringnya dari `ctfr{abcd}` menjadi `CTFR{abcd}`

