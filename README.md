# SENTIMEN TWITTER TERHADAP 'UU ITE' DAN 'KRITIK'
 ## About
![Figure 1](https://github.com/boxside/analisis-sentimen-twitter/blob/main/figure/twitter.jpg)

 Code and Resources Used 
  **Python Version:** 3.7  
  **Packages:** pandas, tweepy, matplotlib, seaborn,
parameter:
data diambil dari tanggal 14/02/2021
keyword : "UU ITE" or "kritik"
jumlah tweet : 382/???

## HASIL
analisa ini menggunakan metode Rule-based sentiment analysis, yang mana menilai kalimat berdasarkan kamus sentimen, lalu nilai tersebut dijumlahkan. maka didapatkan distribusi nilai sentimen sebagai berikut:
![Figure 2](https://github.com/boxside/analisis-sentimen-twitter/blob/main/figure/distribusi.png)

setelah didapatkan nilai sentimen, lalu kita melakukan labeling untuk setiap tweet, dimana bila bernilai <0 maka sentimen tweet "negatif",bila nilai = 0 maka "netral" dan bila nilai>0 maka sentimen tweet "positif", didapat alokasi sentimen sebagai berikut:

![Figure 3](https://github.com/boxside/analisis-sentimen-twitter/blob/main/figure/segmen.png)
![Figure 4](https://github.com/boxside/analisis-sentimen-twitter/blob/main/figure/date.png)
![Figure 5](https://github.com/boxside/analisis-sentimen-twitter/blob/main/figure/hour.png)
