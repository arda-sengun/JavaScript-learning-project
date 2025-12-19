# 🎲 Pig Game (Zar Oyunu)

JavaScript ile DOM manipülasyonu, event handling ve oyun mantığını öğrenmek amacıyla geliştirilmiş, iki oyunculu klasik **Pig Game** uygulaması.

## 🚀 Proje Hakkında

Pig Game, iki oyuncunun sırayla zar atarak puan toplamaya çalıştığı basit ama öğretici bir oyundur. Oyuncular zar attıkça geçici (current) skor kazanır, ancak **1 gelirse tüm tur puanı sıfırlanır** ve sıra diğer oyuncuya geçer. Oyuncu isterse zar atmadan mevcut skorunu tutabilir (**Hold**) ve ana skoruna ekleyebilir.

Oyunun amacı, **100 puana ulaşan ilk oyuncu olmak**tır.

### Özellikler

- **İki Oyunculu Oyun Mekaniği**
- **Zar Atma (Roll Dice):**
  - 🎲 1–6 arası rastgele zar üretimi
  - Zar 1 gelirse tur skoru sıfırlanır
- **Hold Mekaniği:**
  - Oyuncu mevcut skorunu ana skora ekleyebilir
  - Sıra otomatik olarak diğer oyuncuya geçer
- **Oyuncu Değişimi:**
  - Aktif oyuncu görsel olarak vurgulanır
- **Kazanan Durumu:**
  - 100 puana ulaşan oyuncu kazanır
  - Oyun sonlandığında kontroller devre dışı bırakılır
- **Yeni Oyun (New Game):**
  - Tüm skorlar ve oyun durumu sıfırlanır

## 🛠️ Kullanılan Teknolojiler

- **HTML5:** Oyun arayüzü ve yapısal elementler
- **CSS3:** Oyuncu panelleri, aktif oyuncu stilleri ve görsel geri bildirimler
- **JavaScript (ES6+):**
  - DOM seçimi ve güncelleme
  - Event listener’lar (click)
  - Oyun durumu (state) yönetimi
  - Koşullu yapılar ve fonksiyonlar

## 💻 Kurulum ve Çalıştırma

Bu projeyi bilgisayarınızda çalıştırmak için şu adımları izleyebilirsiniz:

1. **Projeyi klonlayın:**

   ```bash
   git clone https://github.com/arda-sengun/JavaScript-learning-project.git
   ```

2. **Klasöre Gidin:**

```bash
  cd JavaScript-learning-project/pig-game
```

3. **Projeyi Başlatın:**

```bash
index.html dosyasını çift tıklayarak tarayıcınızda açın.
```


## 🎓 Emeği Geçenler

Bu proje, **Jonas Schmedtmann** tarafından hazırlanan **The Complete JavaScript Course** eğitiminin bir parçası olarak geliştirilmiştir.
Eğitim amacıyla [Arda Şengün](https://github.com/arda-sengun) tarafından kodlanmıştır.
