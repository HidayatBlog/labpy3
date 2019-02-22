## Tugas Ketiga                                                                                                                                    

## Membuat Latihan Pertama, Kedua, dan Ketiga

**1. Latihan Pertama**                                                                                                                                

**Menampilkan bilangan acak yang lebih kecil dari 0,5 serta menggunakan syntac perulangan dan random**                                                                                                                           

**1**. Buka aplikasi [Pycharm](https://www.jetbrains.com/pycharm/)                                                              
**2**. Buka New Scratch File                                                                                                    
**3**. ketik syntac **Print('Bilangan Acak Yang Lebih Kecil Dari 0,5')**                                                        
Kita gunakan sebagai *Judul* dari program yang akan kita buat

![untitled1 1](https://user-images.githubusercontent.com/46746119/53140226-a92f0480-35be-11e9-9dcc-1a68a9f9e63f.jpg)

**4**. Ketik Syntax :                                                                                                                                      
   **import random**                                                                                                                                                                                                                                           
   **n = int(input("masukan Nilai N:"))**                                                                                         

   **a**. *Import random*																									                                                      
   berfungsi meng-acak hasil dari perulangan yang akan kita buat                                                               

   **b**. *n = int(input("masukan Nilai N:"))*														                                                      
   sedangkan untuk syntac ini kita gunakan untuk memasukan Variabel  		pada nilai N

![untitled1 2](https://user-images.githubusercontent.com/46746119/53140227-a9c79b00-35be-11e9-9930-60338d0cefd2.jpg)

**5**. Ketik Syntax :                                                                                                                                                    
   **a=0**                                                                                                                                      
   **for c in range(n) :**                                                                                                                                                                                                                                                  
   
   **a**. *a=0*																												
   sebagai Variabel yang mana nanti gunakan untuk mengurutkan data
   
   **b**. *for c in range(n)*																								
   sebagai perintah perulangan data dari variabel (N)
   
![untitled1 3](https://user-images.githubusercontent.com/46746119/53140228-a9c79b00-35be-11e9-96b9-a1d43ec07484.jpg)

**6**. ketik Syntax :                                                                                                                               
   **a+= 1**                                                                                                                                                                                                                                                                                                                     
    **b = random.uniform(.0,.5)**                                                                                                                     
    **print('data ke:',a,'==>',b)**                                                                                                                
**print("selesai")**                                                                                                                               

**a**. *a+= 1* :															
sebagai bentuk perintah untuk mengurutkan data yang kita buat sebelumnya							

**b**. *b = random.uniform(.0,.5)* :													
digunakan sebagai variabel peng-acakan pada nilai (b)										

**c**. *print('data ke:',a,'==>',b)* :											
digunakan untuk memunculkan hasil data (a) *pengurutan* dan (b) *pengacakan*							

**d**. *print("selesai")* :													
memunculkan pernyataan bahwa hasil telah di temukan dan selesai									                                                             

Dan jalankan syntax yang sudah di buat dengan menu **RUN** yang terdapat pada aplikasi [Pycharm](https://www.jetbrains.com/pycharm/)

![untitled1 5](https://user-images.githubusercontent.com/46746119/53140232-aa603180-35be-11e9-927f-26d4f4316a26.jpg)

**2. Latihan Kedua**                                                                                                                                                                                                                                                                       
***Mencari bilangan dan menampilkan bilangan terbesar dari (n) sebuah data yang diinputkan.***                                                                                
***Dan Memasukkan angka 0 untuk berhenti.***                                                                                                             

**1**. Ketikan Syntax :                                                                                                                                                                                                                                                                   
**print('====== Menentukan Bilangan Terbesar ======')**                                                                                                           
**max=0**                                                                                                                                             
**while True:**                                                                                                                                       
**a=int(input('Masukkan bilangan = '))**                                                                                                           
   **if max < a**                                                                                                                                                                                                                                                                                            
  **max = a**                                                                                                                                           
  **if a==0:**                                                                                                                                          
  **break**                                                                                                                                                                                                                                                                        
**print('Bilangan terbesarnya adalah = ',max)**  

**a**. *print('====== Menentukan Bilangan Terbesar ======')* :                                                                                    
Digunakan untuk memberikan judul dari program yang akan dibuat                                                                                        

**b**. *max=0*                                                                                                                                       
Di gunakan untuk memberikan varibel pada *max*                                                                                               

**c**. *while True:*                                                                                                                                 
bentuk syntax *Perulangan*                                                                                                                                  

**d**. *a=int(input('Masukkan bilangan = '))*                                                                                                             
di gunakan untuk memasukan bilangan variabel pada nilai (a)                                                                                           

**e**. *if max < a*                                                                                                                                                                                                                                                                                                                                                                                                                                 
**f**. *max = a*                                                                                                                                     
Di gunakan sebagai penegasan bahwa jika *max* lebih kecil dari nilai(a) maka *max* = nilai(a)                                                      

**g**. *if a==0:*                                                                                                                                                                                                                                                                              
**h**. *break*                                                                                                                                       
dan ini di gunakan untuk perintah apabila nilai (a) di isi (0) maka pencarian nilai berhenti dengan menggunakan *break*                

**i**. *print('Bilangan terbesarnya adalah = ',max)*                                                                                                    
dan perintah ini untuk menampilkan hasil bilangan yang dimasukan dan terbesar                                                                      

![untitled2 1](https://user-images.githubusercontent.com/46746119/53140234-aaf8c800-35be-11e9-8685-f41bc40628cb.jpg)

Pilih menu *Run* pada menu [Pycharm](https://www.jetbrains.com/pycharm/) untuk menjalankan hasil dari syntax yang kita buat                  

![untitled2 2](https://user-images.githubusercontent.com/46746119/53140236-aaf8c800-35be-11e9-9260-2a440d9ad99b.jpg)

**3. Latihan Ketiga**														

***Membuat program sederhana dengan perulangan: "program1".py***	

**1**. Seorang pengusaha menginvestasikan uang untuk memulai usahanya dengan modal awal 100 juta,																						
**2**. pada bulan pertama dan kedua belum mendapatkan laba.						
**3**. pada bulan ketiga baru mulai mendapatkan laba sebesar 1%				
**4**. dan pada bulan ke 5, pendapatan meningkat 5%,									
**5**. selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%																														
**6**. sehingga laba menjadi 3%.																			
**7**. Hitung total keuntungan selama 8 bulan berjalan usahanya.*	

**1**.Ketikan syntax :														 

**x=100000000**																												
**sum=0 y=0**															 														
**lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) .5, int(x) * .5, int(x) * .5, int(x) .2]**				

**print('modal awal seorang pengusaha :',x)**											

**for i in lb :															 
sum=sum+i															 
y+=1																 
print('laba bulan ke-', y ,'sebesar :',i)**											

**print('total laba yang di dapet adalah :',sum)**										

**a**. *x=100000000*																									
di gunakan untuk meberikan variabel pada nilai(x) sebagai modal awal

**b**. *sum=0*																												
Digunakan untuk memberikan variabel pada syntax penjumlahan(Sum)

**c**. *y=0*																													
Digunakan untuk memberikan variabel pada nilai (y) untuk mengurutkan keterangan laba pada bulan

**d**. *lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) .5, int(x) * .5, int(x) * .5, int(x) *.2] *															
menerangkan bahwa (lb) = hasil atau persenan dari modal awal

**e**. *print('modal awal seorang pengusaha :',x)*										
menampilkan hasil dari hitungan laba di atas

**f**. *for i in lb :*																								
syntax ini berfungsi mengulang dan memasukan laba ke dalam nilai(i)

**g**. *sum=sum+i* 																										
menjumlah kan nilai laba yang berada di dalam nilai(i)

**h**. *y+=1* 																												
mengurutkan nilai pada laba,

**i**. *print('laba bulan ke-', y ,'sebesar :',i)* 										
menampilkan hasil dari variabel yang di dapat

**j**. *print('total laba yang di dapet adalah :',sum)*								
menampilkan hasil jumlahan variabel atau hasil laba

![untitled3 1](https://user-images.githubusercontent.com/46746119/53223519-2ed8b000-36a4-11e9-9ccf-7d5bf0af7874.jpg)

Pilih menu *Run* pada menu [Pycharm](https://www.jetbrains.com/pycharm/) untuk menjalankan hasil dari syntax yang kita buat

![untitled3 2](https://user-images.githubusercontent.com/46746119/53223520-2ed8b000-36a4-11e9-8b3a-2d50808f6efd.jpg)

***SEKIAN TUGAS DARI SAYA***

*Rahman Hidayat*
*Terima Kasih*
