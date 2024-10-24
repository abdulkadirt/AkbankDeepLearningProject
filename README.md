# AkbankDeepLearningProject

Projenin kaggle notebook linki -> https://www.kaggle.com/code/akadir0223/large-scale-fish-classification-using-ann?scriptVersionId=202933645

Veri seti kullanılarak bir sınıflandırma modeli geliştirildi ve değerlendirildi. Veri setinde 9 farklı balık türüne ait görseller bulunuyor.

Veri setinde bulunan balık türleri :
* gilt head bream,
* red sea bream,
* sea bass,
* red mullet,
* horse mackerel,
* black sea sprat,
* striped red mullet,
* trout,
* shrimp

  Sınıflandırma problemi ANN mimarisi kullanılarak çözülmeye çalışıldı. Değerlendirme ise Confusion Matrix ve Classification Report ile yapıldı.  
Classification Report Aşağıda görülebilir :
                    precision    recall  f1-score   support

   Black Sea Sprat       0.88      0.98      0.92       211
   Gilt-Head Bream       0.90      0.88      0.89       204
   Hourse Mackerel       0.96      0.90      0.93       195
        Red Mullet       0.98      0.93      0.95       191
     Red Sea Bream       0.95      0.96      0.96       201
          Sea Bass       0.91      0.91      0.91       179
            Shrimp       0.97      0.95      0.96       209
Striped Red Mullet       0.85      0.93      0.89       207
             Trout       0.93      0.87      0.90       203
          accuracy                           0.92      1800
         macro avg       0.92      0.92      0.92      1800
      weighted avg       0.92      0.92      0.92      1800
