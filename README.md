## BTK Akademi Veri Bilimi İçin Python ve Tensorflow eğitimi kapsamında gerçekleştirilen Regresyon Problemi Projesidir.

### Preprocessing 
- Önişlem sürecinde dataset incelendi. Eksik veri kontrolü, verilerin dağılım grafiği, korelasyon kontrolleri yapıldı. Gerekli Data Manipulation işlemleri gerçekleştirildi. 

![image](https://user-images.githubusercontent.com/41507884/196035507-e179419b-3462-4ba6-916b-38117ff1b665.png)

### Model
- Sklearn ile dataset üzerinde gerekli ayrıştırma yapıldı. Burada test_size=0.3 belirlendi. 
- Scaler işlemi gerçekleştirildi. Scaling: yapacağımız işlem hızlı ve kolay olması amacıyla veri setinin küçültülmesi işlemidir.
- Model oluşturuldu. Optimizer için Adam, loss için MSE kullanıldı. Batch size 256, Epoch ise 300 belirlendi.

![image](https://user-images.githubusercontent.com/41507884/196035842-eaf1bff4-cc92-40c7-812b-03b1558358fc.png)![image](https://user-images.githubusercontent.com/41507884/196035848-cf957b74-5c9b-4f55-9193-69359d49ed59.png)
