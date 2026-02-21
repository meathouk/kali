# mv Ne ise yarar? 
    - Dosya tasima ve yeniden adlandirma icin  kullanilir.

# cp Ne ise yarar?
    - Dosya ve dizin kopyalama islemi yapmaktadir. 

# mv komutu ile cp komutunun arasindaki farklar.
    - cp komutu dosya veya bir dizini kopyala-yapistir olarak dusunursek mv komutu kes-yapistir olarak dusunebiliriz.


# mv komutu ile birlikte joker kullanimi.
   `mv *.txt test/test2` 
    - bu komut dizininizdeki tum txt dosyalarini test/test2 dizinine tasimaktadir.


# mv komutunun uzerine yazmasini engellemek icin -n opsiyonu kullanilir. -i opsiyonu ise etkilesimli dosya tasimasi yapmaktadir.
    `mv -n move_file target_directory`
    `mv -i move_file target_directory`

# -b opsiyonu ile uzerine yazilan dosyanin yedegini olusturma.
    `mv -b file.txt target_dir/file.txt`    
    `ls target_dir`
    `file.txt file.txt~`
    - Yedeklenen dosya ~ sonu ile biter. Bunu -S secenegi ile  degistirilebilir.
    `mv  -S .back -b file.txt target_dir/file.txt`
    `ls target_dir`
    `file.txt file.txt.back`

# -u secenegi ise hedef dosya eski veya mevcut degil ise uzerine yaz.

# uzerine yazma korumali dosyalari -f secenegi ile dosyayi zorla uzerine yazdirilabilir.

