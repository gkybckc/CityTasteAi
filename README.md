Belirli bir şehirdeki restoranların yorumlarını, puanlarını ve trendlerini analiz eden AI destekli bir mobil uygulama + analiz platformu.

# 🍽️ CityTaste AI
**AI-Powered Restaurant Review Analytics Platform**

CityTaste AI, şehir bazlı restoran yorumlarını analiz ederek kullanıcı memnuniyetini, popüler temaları ve duygusal eğilimleri ortaya çıkaran yapay zeka destekli bir analiz platformudur.  
Kullanıcılar mobil uygulama üzerinden şehir seçip restoranları keşfederken, sistem her restoranın yorumlarını NLP modelleriyle analiz eder ve sezgisel görselleştirmeler sunar.

---

## 🚀 Özellikler

| Kategori | Açıklama |
|-----------|-----------|
| 🧠 **AI Analizi** | Türkçe BERT modeliyle yorumların duygu ve konu analizi |
| 🌆 **Şehir Bazlı İnceleme** | Harita üzerinde şehirdeki restoranların memnuniyet yoğunluğu |
| 📊 **İstatistikler & Trendler** | Pozitiflik oranı, kelime bulutu, zamana göre değişim grafikleri |
| 📱 **Mobil Uygulama (React Native)** | Restoran listesi, analiz sonuçları ve görseller |
| 🧾 **Backend (FastAPI)** | API üzerinden analiz sonuçlarını yönetir |
| ☁️ **Veritabanı (Supabase / PostgreSQL)** | Restoran, yorum ve skor kayıtları |
| 💬 **Çok Dilli Destek** | Türkçe & İngilizce yorum analizleri |

---

## 🏗️ Mimari

```mermaid
graph TD;
  A[📱 React Native App] -->|Fetches Data| B[🚀 FastAPI Backend]
  B --> C[(🗄️ Supabase DB)]
  B --> D[🧠 NLP Model (BERT)]
  B --> E[📊 Streamlit Dashboard]
