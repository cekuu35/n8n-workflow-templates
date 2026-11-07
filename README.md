# n8n Otomasyon Şablonları — Satışa Hazır Paket

n8n içinde **İçe Aktar (Import)** ile 30 saniyede çalışan 3 satılabilir otomasyon.
Her şablon; sürükle-bırak kullanıma uygun, credential'ları sen bağlarsın.

## 📦 Paket İçeriği

| # | Şablon | Ne yapar | Müşteriye fiyat önerisi |
|---|---|---|---|
| 01 | **Müşteri Bulma + Otomatik E-posta** | OpenStreetMap'ten sektör+şehir bazlı işletme verisi (telefon/web/adres) çeker, Google Sheets'e yazar, müşteriye e-posta gönderir | ₺2.000-4.000 kurulum |
| 02 | **Rakip Site Takip + Anlık Bildirim** | Rakip sitelerini günlük izler, değişim olunca Telegram/e-posta ile anında uyarır | ₺1.500-3.000 kurulum |
| 03 | **İçerik Fabrikası (RSS → AI)** | RSS/haber kaynağını alır, Gemini AI ile sosyal medya içeriğine dönüştürür, Sheets arşiv + Telegram kanalına atar | ₺2.500-5.000 kurulum |

## 🚀 Nasıl Aktarılır?
1. n8n editörünü aç (http://localhost:5678)
2. Sağ üstteki **⋯ menü → Import from File**
3. İstediğin `.json` dosyasını seç → **Import**
4. Kırmızı yanan düğümleri kontrol et: Google/Gmail/Telegram/Gemini hesabını bir kez bağla
5. **Execute Workflow** ile test et → **Publish**

## 🔌 Gerekli bağlantılar (müşteriye anlatılacak)
- **01:** Google Sheets hesabı + Gmail (5 dk kurulum, ben yapıyorum)
- **02:** Telegram botu (@BotFather ücretsiz) veya sadece e-posta
- **03:** Gemini API anahtarı (ücretsiz: https://aistudio.google.com/apikey)

## 💡 Satış stratejisi
- **Başlangıç paketi:** 1 şablon + kurulum desteği
- **Büyüme paketi:** 3 şablon + 1 özel otomasyon (müşterinin sürecine göre)
- **Aylık bakım:** Güncelleme + rapor + yeni otomasyon talepleri (tekrarlayan gelir)

## ⚖️ Lisans
Kişisel/ticari kullanım serbest. Devredilirken LICENSE korunmalıdır.
