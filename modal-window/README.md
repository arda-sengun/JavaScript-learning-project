# 🪟 Modal Window (Açılır Pencere Uygulaması)

JavaScript ile DOM manipülasyonu ve CSS sınıf yönetimini (class manipulation) öğrenmek amacıyla geliştirilmiş, klavye ve fare olaylarını dinleyen modern bir arayüz projesi.

## 🚀 Proje Hakkında

Bu projede amaç, web sitelerinde sıkça kullanılan "Pop-up" veya "Modal" pencerelerin mantığını kavramaktır. Sayfada bulunan farklı butonlar aynı pencereyi tetikler. Pencere açıldığında arka plan bulanıklaşır (overlay) ve kullanıcı pencereye odaklanır.

### Özellikler

- **Çoklu Buton Yönetimi:** Sayfadaki 3 farklı butondan hangisine tıklanırsa tıklansın aynı modal penceresi açılır.
- **Dinamik Sınıf Yönetimi:** JavaScript `classList` metodu kullanılarak CSS sınıfları eklenip çıkarılır (görünür/gizli durumları).
- **Kapatma Seçenekleri:**
  - ❌ Pencere üzerindeki çarpı butonuna basarak.
  - 🌫️ Modal dışındaki boş alana (Overlay) tıklayarak.
  - ⌨️ Klavyedeki **ESC (Escape)** tuşuna basarak.
- **Klavye Dinleme:** Global olay dinleyicisi (Global Event Listener) ile klavye hareketleri takip edilir.

## 🛠️ Kullanılan Teknolojiler

- **HTML5:** Sayfa iskeleti ve yapısal elementler için.
- **CSS3:** Modal pencerenin ortalanması, z-index katmanları, görsel efektler ve gizleme/gösterme stilleri için.
- **JavaScript (ES6+):** DOM element seçimi, döngüler ve olay dinleyicileri (click, keydown) için.

## 💻 Kurulum ve Çalıştırma

Bu projeyi bilgisayarınızda çalıştırmak için şu adımları izleyebilirsiniz:

1. **Projeyi klonlayın:**

   ```bash
   git clone [https://github.com/arda-sengun/JavaScript-learning-project.git](https://github.com/arda-sengun/JavaScript-learning-project.git)
   ```

2. **Klasöre Gidin:**

```bash
  cd JavaScript-learning-project/modal-window
```

3. **Projeyi Başlatın:**

```bash
index.html dosyasını çift tıklayarak tarayıcınızda açın.
```


## 🎓 Emeği Geçenler

Bu proje, **Jonas Schmedtmann** tarafından hazırlanan **The Complete JavaScript Course** eğitiminin bir parçası olarak geliştirilmiştir.
Eğitim amacıyla [Arda Şengün](https://github.com/arda-sengun) tarafından kodlanmıştır.
