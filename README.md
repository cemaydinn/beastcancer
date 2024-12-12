Checking The Overfitting
Breast Cancer Classification modeli adı verilen bir model geliştirilmiştir. İlgili mühendis bu modelin accuracy değerinin yüzde 98 olduğunu iddia etmektedir. Ancak modelin hastalarımız ile ilgili yaptığı yanlış tahminler hastanemizi sıkıntıya sokmaktadır :)

Bu modeli tekrar geliştiriniz ve sonuçları yorumlayınız.

Logistic regression bölümünde elde ettiğimiz model accuracy değeri yüzde 98 idi. Bu durum bize aşırı öğrenme problemine düşebileceğimizi düşündürmüştü. Mühendisimizin günahını da alıyor olabiliriz. Bilmiyoruz.

Bu sebeple aşırı öğrenme önlemleri alarak yeni bir model geliştirmemiz gerekiyor.

Bu veri setini tekrar modelleyiniz.

Dikkat edilmesi gerekenler:

sklearn içerisinde yer alan breast cancer veri setini kullanınız. (from sklearn.datasets import load_breast_cancer)

Veri ön işleme adımında amelasyon yapılabilir. Fonksiyon yazılmasına gerek yok.

Tensorflow dataset için tanımladığımız fonksiyonu kullanınız ve batch_size'ı 32 yapınız.

1 gizli katmanlı basit bir model oluşturunuz. Nöron sayısını istediğiniz gibi tercih edebilirsiniz.

Aşırı öğrenme problemine karşı uygun katman yapılarını ve callback'i kullanınız.

Model compile bölümünde SGD'yi direkt kullanınız yani compile içinde optimizer="SGD" şeklinde kullanınız.

Overfitting'den şüphelendiğimiz için early stopping'de küçük bir değer giriniz.

En iyi epoch sonucunu yorumlayınız.

Loss eğrisini yorumlayınız.

İfade edilmeyen konularda tercih size bırakılmıştır.

Notebook'ta genel yapılar ve gidiş yolu için yönlendirmeler bırakılmıştır.
