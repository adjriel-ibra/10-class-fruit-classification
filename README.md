Fruit Classification CNN
Deskripsi
Proyek ini bertujuan untuk mengklasifikasikan 10 jenis buah menggunakan model CNN berbasis MobileNetV2.


Dataset
Dataset terdiri dari 10 kelas:
Apple, Banana, Avocado, Cherry, Kiwi, Mango, Orange, Pineapple, Strawberry, Watermelon.
Total data lebih dari 3000 gambar.


Model
Model menggunakan:
* MobileNetV2 (Transfer Learning)
* Conv2D + MaxPooling
* Dropout & BatchNormalization
Hasil
* Training Accuracy: ~85%
* Validation Accuracy: ~80%
* Test Accuracy: ~85%
Format Model
* SavedModel
* TensorFlow Lite (TFLite)
* TensorFlow.js (TFJS)