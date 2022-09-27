# Demo Day Machine Learning with TensorFlow  
## Prediksi Produksi Padi dan Jagung dengan LSTM dan RNN oleh AGRI 6
**Summary :**   
Padi merupakan bahan makanan pokok bagi sebagian besar penduduk di Indonesia, sedangkan jagung merupakan bahan makanan pokok alternatif kedua setelah padi  atau beras (Erviyana, 2014).  

Penelitian ini bertujuan untuk menjawab permasalahan, bagaimana model prediksi untuk produksi padi dan jagung dengan menggunakan metode LSTM (Muklis, Kustiyo, dan Suharso, 2021) dan RNN (Kustiyo, Mukhlis, Suharso, 2022) untuk memperoleh gambaran ketersediaannya.

## Youtube :
https://youtu.be/MQiZuMksba0

## Branches Anggota:
Adriana_Dina_152236035100-825 : https://github.com/relesa/demo_day_mlt2/tree/Adriana_Dina_152236035100-825  
Arna_Fariza_152236035100-9 : https://github.com/relesa/demo_day_mlt2/tree/Arna_Fariza_152236035100-9  
Enjun_Junaeti_Junaeti-152236035100-61 : https://github.com/relesa/demo_day_mlt2/tree/Enjun_Junaeti_Junaeti-152236035100-61  
Relesa_Anggita_Permata_T_W-152236035100-685 : https://github.com/relesa/demo_day_mlt2/tree/Relesa_Anggita_Permata_T_W-152236035100-685  
Septi_Dwi_Kurnia_Sari-152236035100-1145 : https://github.com/relesa/demo_day_mlt2/tree/Septi_Dwi_Kurnia_Sari-152236035100-1145  
Yunita_Nur_Afifah-152236035100-247 : https://github.com/relesa/demo_day_mlt2/tree/Yunita_Nur_Afifah-152236035100-247  

## Dataset : 
https://github.com/relesa/demo_day_mlt2/blob/main/Jagung.csv 
https://github.com/relesa/demo_day_mlt2/blob/main/Padi.csv 

## Explorasi Dataset
**Snippet data dari Jagung.cvs dan Padi.cvs**
&nbsp;
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/dataset_head.PNG)
&nbsp;

**Preprocessing : Hasil Transpose Dataset Jagung.cvs dan Padi.cvs**
&nbsp;
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/dataset_transpose.PNG)
&nbsp;

**Plot Dataset Jagung.cvs dan Padi.cvs**
&nbsp;
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/prov_code.PNG)
&nbsp;

## Modeling & Training
**Normalize**
&nbsp;
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/normalize.PNG)
&nbsp;

**Split Data : Training and Validation**
&nbsp;
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/split.PNG)
&nbsp;

**Model RNN**
&nbsp;
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/rnn.PNG)
&nbsp;

**Model LSTM**
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/lstm.PNG)
&nbsp;

**RNN Training Loss**
&nbsp;\
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/loss_rnn.png)
&nbsp;

**LSTM Training Loss**
&nbsp;\
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/loss_lstm.png)
&nbsp;

## Prediction
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/predict.PNG)

**RNN Prediction**
&nbsp;\
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/loss_rnn.png)
&nbsp;

**LSTM Prediction**
&nbsp;\
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/loss_lstm.png)
&nbsp;

## Modal Evaluate
**MSE & RMSE**
&nbsp;\
![alt text](https://github.com/relesa/demo_day_mlt2/blob/Resources/mse_rmse.PNG)
&nbsp;
