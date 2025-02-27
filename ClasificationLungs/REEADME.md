# Membuat Project Deep Learning Dengan tujuan untuk Memprediksi Penyakit Paru-Paru 
    Menggunakan Libarary Tensorflow dan Keras untuk Training Model nya 
    Menggunakan split data 70 :20: 10 . Dengan hasil Training yang cukup tinggi :

    Epoch 1/5
    115/115 ━━━━━━━━━━━━━━━━━━━━ 61s 470ms/step - accuracy: 0.7376 - loss: 59.4772 - val_accuracy: 0.8763 - val_loss: 0.3464
    Epoch 2/5
    115/115 ━━━━━━━━━━━━━━━━━━━━ 40s 350ms/step - accuracy: 0.9173 - loss: 0.2404 - val_accuracy: 0.8802 - val_loss: 0.4206
    Epoch 3/5
    115/115 ━━━━━━━━━━━━━━━━━━━━ 47s 399ms/step - accuracy: 0.9446 - loss: 0.1915 - val_accuracy: 0.9041 - val_loss: 0.3263
    Epoch 4/5
    115/115 ━━━━━━━━━━━━━━━━━━━━ 48s 414ms/step - accuracy: 0.9739 - loss: 0.0751 - val_accuracy: 0.9386 - val_loss: 0.2469
    Epoch 5/5
    115/115 ━━━━━━━━━━━━━━━━━━━━ 46s 400ms/step - accuracy: 0.9802 - loss: 0.0685 - val_accuracy: 0.9377 - val_loss: 0.3553 

    Accuracy: 0.89272030651341


# Classification Report:
                precision    recall  f1-score   support

            0       0.99      0.58      0.73       132
            1       0.88      1.00      0.93       390

        accuracy                           0.89       522
    macro avg       0.93      0.79      0.83       522
    weighted avg       0.90      0.89      0.88       522

    Confusion Matrix:
    [[ 77  55]
    [  1 389]]
    
# Intall requirments.txt
    pip install -r requirements.txt

# Link data set dapat di uduh dari link berikut:
 https://www.kaggle.com/datasets/nabilfirdaus/parkison-xray

[Deskripsi Gambar](src/paru.png)
#