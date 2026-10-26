<div align="center">

<img src="assets/logo.png" alt="Esnaf Ses logosu" width="260" />

# Esnaf Ses

### Arayan müşteriniz, sizin adınıza randevu alır.

Esnaflar için Türkçe konuşan, cihazda çalışan **sesli randevu asistanı**.<br/>
Müşterileriniz randevusunu alsın, siz işinize odaklanın.

![Durum](https://img.shields.io/badge/durum-geliştirme-1a73e8?style=flat-square)
![Dil](https://img.shields.io/badge/dil-Türkçe-0b2a6f?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Android%20%7C%20Windows-1a73e8?style=flat-square)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

<br/>

<p align="center">
  <img src="assets/tanitim.png" alt="Esnaflar için otomatik randevu asistanı" width="720" />
</p>

---

## 📞 Esnaf Ses nedir?

Telefon çalar, siz müşterinizle ilgilenirken açamazsınız — randevu kaçar.
**Esnaf Ses** o aramayı sizin yerinize karşılar: müşteriyle doğal Türkçe konuşur, uygun gün ve saati bulur, özeti okur ve **müşteri onay verdikten sonra** randevuyu takviminize yazar.

| | |
|---|---|
| 🕒 **7/24 randevu alımı** | Mesai dışında ve yoğun saatlerde de çağrılar karşılanır. |
| ⚡ **Zaman tasarrufu** | Telefon trafiği yerine işinize odaklanırsınız. |
| 👥 **Daha fazla müşteri** | Cevapsız arama yüzünden kaçan randevu kalmaz. |
| 📈 **İşinizi büyütün** | Düzenli takvim, daha az boşluk, daha çok hizmet. |

## 🏪 Kimler için?

<table>
  <tr>
    <td align="center">✂️<br/><b>Kuaför</b></td>
    <td align="center">🔧<br/><b>Tamirci</b></td>
    <td align="center">🏋️<br/><b>Spor Salonu</b></td>
    <td align="center">🦷<br/><b>Diş Hekimi</b></td>
    <td align="center">🚗<br/><b>Oto Servis</b></td>
    <td align="center">➕<br/><b>Ve daha fazlası</b></td>
  </tr>
</table>

## 🔄 Nasıl çalışır?

```mermaid
flowchart LR
    A["📞 Arama"] --> B["🗣️ Konuşma"]
    B --> C["📅 Uygunluk"]
    C --> D["✅ Onay"]
    D --> E["🗓️ Kayıt"]
```

1. **Arama** — Müşteri işletmenizi arar, Esnaf Ses karşılar.
2. **Konuşma** — Gün, saat ve isim doğal Türkçe konuşmayla alınır.
3. **Uygunluk** — Takvimde boş saat kontrol edilir, gerekirse alternatif önerilir.
4. **Onay** — Randevu özeti okunur, müşteri onaylar.
5. **Kayıt** — Randevu takviminize yazılır.

## 🛡️ İlkelerimiz

- **Onaysız kayıt yok.** Randevu, yalnız müşterinin açık onayından sonra yazılır; düzeltme eski onayı geçersiz kılar.
- **Uydurma yok.** Takvim ve kayıt sonuçları modelden değil, uygulama kodundan gelir.
- **Cihazda çalışır.** Konuşma çekirdeği yerelde çalışır; müşteri verisi gereksiz yere dışarı çıkmaz.
- **Saygılı ve kısa.** Varsayılan hitap "siz"; sıcak, ölçülü ve net bir işletme dili.

## 🧩 Mimari

| Bileşen | Görev |
|---|---|
| **Konuşma çekirdeği** | Türkçe niyet/alan modeli, yapılandırılmış hafıza, açık onaylı SQLite randevu defteri |
| **Uygulama** | Flutter ile esnaf sürümü, telefon testi ve Windows masaüstü |
| **Sunucu** | Telefon hattı için relay kurulumu (Docker, Caddy, systemd) |

---

<div align="center">

**Esnaf Ses** — telefonunuz çalarken işiniz durmasın. 💙

<sub>Proje aktif geliştirme aşamasındadır.</sub>

</div>
