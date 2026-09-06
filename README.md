# Geri Dönüşüm AI

Bu proje, farklı atık türlerini görüntü üzerinden ayırt ederek atığın geri dönüştürülebilir olup olmadığı hakkında bilgi vermek amacıyla geliştirilmiştir.

## Projenin Amacı

Projenin temel amacı, kullanıcı tarafından gösterilen bir atık türünü yapay zekâ kullanarak sınıflandırmak ve sınıflandırılan atık hakkında bilgi vermektir.

Model aşağıdaki atık türlerini ayırt etmek için eğitilmiştir:

Karton

Plastik

Cam

Metal

Geri dönüştürülemeyen atık

## Nasıl Yapıldı?

Bu proje Google Teachable Machine kullanılarak geliştirilmiştir.

Eğitim verileri Hugging Face üzerinden alınmıştır. Bu veriler Google Teachable Machine'e aktarılmış ve görüntü sınıflandırma modeli bu veriler kullanılarak eğitilmiştir.

## Nasıl Çalışır?

1. Kullanıcı kamerayı veya bir görseli modele gösterir.
2. Yapay zekâ görseli analiz eder.
3. Atığın hangi kategoriye ait olduğunu tahmin eder.
4. Sonuç ekranda gösterilir.
5. Kullanıcıya atığın geri dönüşümü ve doğadaki durumu hakkında bilgi verilir.

## Kullanılan Teknolojiler

Google Teachable Machine

Hugging Face

Yapay zekâ

Görüntü sınıflandırma

## Veri Kaynağı

Eğitim verileri Hugging Face platformundan alınmıştır.

Modelin eğitimi ve görüntü sınıflandırma işlemi Google Teachable Machine kullanılarak gerçekleştirilmiştir.

## Not

Modelin tahminleri kullanılan eğitim verilerine bağlıdır ve her zaman yüzde 100 doğru sonuç vermeyebilir. Işık koşulları, kamera açısı, görüntü kalitesi ve farklı atık türleri modelin tahminlerini etkileyebilir.

## Sonuç

Geri Dönüşüm AI, yapay zekâ kullanarak atıkların türlerini ayırt etmeye ve insanların geri dönüşüm konusunda bilinçlenmesine yardımcı olmayı amaçlamaktadır.
