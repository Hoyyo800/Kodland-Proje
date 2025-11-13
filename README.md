# Kodland-Proje

# ♻️ Akıllı Atık Dedektörü Discord Botu

## 🌍 Proje Amacı
Bu proje, **iklim değişikliğine karşı farkındalık oluşturmak** ve **geri dönüşüm bilincini artırmak** amacıyla geliştirilmiş bir Discord botudur.  
Bot, **Google Teachable Machine** kullanılarak eğitilmiş bir **bilgisayarlı görü modeli** yardımıyla atık türlerini tanır ve kullanıcıya atığın doğaya etkisi hakkında bilgi verir.

---

## 🧠 Nasıl Çalışır
1. Kullanıcı Discord kanalına bir fotoğraf gönderir veya `/atık-tanımla` komutunu kullanarak resim yollar.  
2. Bot, Teachable Machine modelini kullanarak görüntüyü analiz eder.  
3. Atığın türünü belirler (örneğin: plastik, cam, kağıt, metal, organik, geri dönüştürülemez).  
4. Kullanıcıya şu bilgileri içeren bir mesaj döndürür:
   - Atığın türü  
   - Geri dönüştürülebilir olup olmadığı  
   - Doğada çözünme süresi  
   - Çevresel etkileri ve öneriler

---

## 🧩 Örnek Çıktı

> ♻️ **Bu atık plastik!**  
> Geri dönüştürülebilir, ancak doğada çözünmesi yaklaşık **450 yıl** sürer.  
> Lütfen **mavi kutuya** at!  
> 🔎 Plastik atıklar deniz canlılarının %60’ına zarar verir.

---

## ⚙️ Kullanılan Teknolojiler
- **Google Teachable Machine** → Görüntü sınıflandırma modeli  
- **TensorFlow.js** → Modelin Discord botu içinde çalışması  
- **Discord.js (Node.js)** → Botun ana altyapısı  
- **JavaScript** → İşlevsel ve basit entegrasyon

---

## 📁 Proje Yapısı
