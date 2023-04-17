# Diabetes_Feature_Engineering
 
## ENG
**Problem :** Developing a machine learning model that can predict whether people have diabetes when their characteristics are specified.
is requested. You are expected to perform the necessary data analysis and feature engineering steps before developing the model.

### The story of the dataset:
  The dataset is part of the large dataset held at the National Institutes of Diabetes-Digestive-Kidney Diseases in the USA.
  Pima Indian women aged 21 and over living in Phoenix, the 5th largest city in the State of Arizona in the USA
  Data used for diabetes research. It consists of 768 observations and 8 numerical independent variables.
 
  The target variable is specified as **"outcome"**; 1 indicates positive diabetes test result, 0 indicates negative.

### Variables in the dataset
- Pregnancies: Number of pregnancies
- Glucose: Glucose
- BloodPressure: Blood pressure (Diastolic(Small Blood Pressure))
- SkinThickness: Skin Thickness
- Insulin: Insulin.
- BMI: Body mass index.
- DiabetesPedigreeFunction: A function that calculates our probability of having diabetes based on our ancestry.
- Age: Age (years)
- Outcome: Information whether the person has diabetes or not. Have the disease (1) or not (0)


### DISCOVERY DATA ANALYSIS
             Step 1: Examine the overall picture.
             Step 2: Capture the numeric and categorical variables.
             Step 3: Analyze the numerical and categorical variables.
             Step 4: Perform target variable analysis. (The mean of the target variable according to the categorical variables, the mean of the numeric variables according to the target variable)
             Step 5: Perform outlier analysis.
             Step 6: Perform missing observation analysis.
             Step 7: Perform correlation analysis.

### FEATURE ENGINEERING
             Step 1: Take necessary actions for missing and outlier values. There are no missing observations in the data set, but Glucose, Insulin etc.
             Observation units containing a value of 0 in the variables may represent the missing value. For example; a person's glucose or insulin value
             It will not be 0. Considering this situation, you can assign the zero values to the relevant values as NaN and then apply the operations to the missing values.
             Step 2: Create new variables.
             Step 3: Perform the encoding operations.
             Step 4: Standardize for numeric variables.
             Step 5: Build the model.


For Data Analysis and more content, I explain it on medium. You can follow me on medium. [Medium](https://medium.com/@haticeozbolat17)

## TR
**Problem :**  Özellikleri belirtildiğinde kişilerin diyabet hastası olup olmadıklarını tahmin edebilecek bir makine öğrenmesi modeli geliştirilmesi
istenmektedir. Modeli geliştirmeden önce gerekli olan veri analizi ve özellik mühendisliği adımlarını gerçekleştirmeniz beklenmektedir.

### Veri setinin hikatesi :
 Veri seti ABD'deki Ulusal Diyabet-Sindirim-Böbrek Hastalıkları Enstitüleri'nde tutulan büyük veri setinin parçasıdır. 
 ABD'deki Arizona Eyaleti'nin en büyük 5. şehri olan Phoenix şehrinde yaşayan 21 yaş ve üzerinde olan Pima Indian kadınları 
 üzerinde yapılan diyabet araştırması için kullanılan verilerdir. 768 gözlem ve 8 sayısal bağımsız değişkenden oluşmaktadır.
 
 Hedef değişken **"outcome"** olarak belirtilmiş olup; 1 diyabet test sonucunun pozitif oluşunu, 0 ise negatif oluşunu belirtmektedir.

### Veri setinde bulunan değişkenler 
- Pregnancies: Hamilelik sayısı
- Glucose: Glikoz
- BloodPressure: Kan basıncı (Diastolic(Küçük Tansiyon))
- SkinThickness: Cilt Kalınlığı
- Insulin: İnsülin.
- BMI: Beden kitle indeksi.
- DiabetesPedigreeFunction: Soyumuzdaki kişilere göre diyabet olma ihtimalimizi hesaplayan bir fonksiyon.
- Age: Yaş (yıl)
- Outcome: Kişinin diyabet olup olmadığı bilgisi. Hastalığa sahip (1) ya da değil (0)


### KEŞİFCİ VERİ ANALİZİ
            Adım 1: Genel resmi inceleyiniz.
            Adım 2: Numerik ve kategorik değişkenleri yakalayınız.
            Adım 3:  Numerik ve kategorik değişkenlerin analizini yapınız.
            Adım 4: Hedef değişken analizi yapınız. (Kategorik değişkenlere göre hedef değişkenin ortalaması, hedef değişkene göre numerik değişkenlerin ortalaması)
            Adım 5: Aykırı gözlem analizi yapınız.
            Adım 6: Eksik gözlem analizi yapınız.
            Adım 7: Korelasyon analizi yapınız.

### FEATURE ENGINEERING
            Adım 1:  Eksik ve aykırı değerler için gerekli işlemleri yapınız. Veri setinde eksik gözlem bulunmamakta ama Glikoz, Insulin vb.
            değişkenlerde 0 değeri içeren gözlem birimleri eksik değeri ifade ediyor olabilir. Örneğin; bir kişinin glikoz veya insulin değeri
            0 olamayacaktır. Bu durumu dikkate alarak sıfır değerlerini ilgili değerlerde NaN olarak atama yapıp sonrasında eksik değerlere işlemleri uygulayabilirsiniz.
            Adım 2: Yeni değişkenler oluşturunuz.
            Adım 3:  Encoding işlemlerini gerçekleştiriniz.
            Adım 4: Numerik değişkenler için standartlaştırma yapınız.
            Adım 5: Model oluşturunuz.


Veri Analizi ve daha fazla içeriği için medium üzerinden anlatıyorum. Beni mediumdan takip edebilirirsiniz. [Medium](https://medium.com/@haticeozbolat17)
