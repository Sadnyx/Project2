# Project2
Customer Churn Prediction
# Problem: 

**Şirketi terk edecek müşterileri tahmin edebilecek bir makine öğrenmesi modeli geliştirebilir misiniz?**

- Amaç bir bankanın müşterilerinin bankayı terk etme ya da terk etmeme durumunun tahmin edilmesidir.

- Müşteri terkini tanımlayan olay müşterinin banka hesabını kapatmasıdır.

**Veri Seti Hikayesi:**

- 10000 gözlemden ve 12 değişkenden oluşmaktadır. 
- Bağımsız değişkenler müşterilere ilişkin bilgiler barındırmaktadır.
- Bağımlı değişken müşteri terk durumunu ifade etmektedir.

**Değişkenler:**

- Surname : Soy isim
- CreditScore : Kredi skoru
- Geography : Ülke (Germany/France/Spain)
- Gender : Cinsiyet (Female/Male)
- Age : Yaş
- Tenure : Kaç yıllık müşteri
- Balance : Bakiye(In banking, the account balance is the amount of money you have available in your checking or savings)
- NumOfProducts : Kullanılan banka ürünü
- HasCrCard : Kredi kartı durumu (0=No,1=Yes)
- IsActiveMember : Aktif üyelik durumu (0=No,1=Yes)
- EstimatedSalary : Tahmini maaş
- Exited : Terk mi değil mi? (0=No,1=Yes)

# Accomplishments
## Cross Validation Results
### Models Without Preprocessing
LR: 0.783\
KNN: 0.7565\
CART: 0.7885\
RF: 0.854\
SVC: 0.7865\
XGBoost: 0.8465\
LGBM: 0.8515

### Models Without Hyperparameter Optimization
LR: 0.809076682316119\
KNN: 0.8215962441314554\
CART: 0.7949921752738655\
RF: 0.8612415232133542\
SVC: 0.844548774126239\
XGBoost: 0.8633281168492436\
LGBM: 0.8633281168492436

## Solving Imbalances
### RandomForestClassifier Score With Smote
RFC : 0.9047424366312347

