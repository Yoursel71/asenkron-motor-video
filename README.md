# Asenkron Motorlar

Animasyonlu anlatım videosu, 12 dk 7 sn, 1080p, Türkçe seslendirmeli.
Kaynak: MEB **Atölye 10 (Endüstriyel Otomasyon Teknolojileri)**, 1. Öğrenme Birimi, **1.1 Asenkron Motorlar** (s. 16–26).

Video dosyaları repoda değil, **Releases** bölümünde (GitHub tek dosya sınırı 100 MB):

- **v2.0** (güncel, kitaba göre yeniden yapıldı): `asenkron-motorlar-atolye10-1080p.mp4` ve yalnızca seslendirme `asenkron-motorlar-anlatim.mp3`
- v1.0: ilk sürüm (9:43)

## Bölümler (v2.0)

| Zaman | Bölüm | Kitap |
|---|---|---|
| 0:00 | Giriş | 1.1 |
| 0:31 | Motorun parçaları | 1.1.1 · Şekil 1.1 |
| 1:06 | Sincap kafesli rotor | 1.1.1 · Şekil 1.2 |
| 1:30 | Döner manyetik alan | 1.1.1 |
| 2:05 | Rotor neden döner? | 1.1.1 |
| 2:37 | Doğru akım verilirse? | 1.1.1 |
| 3:08 | Motor etiketi | 1.1.2 · Şekil 1.3 |
| 4:00 | Klemens kutusu | 1.1.2 |
| 4:25 | Sargı kontrolü | 1.1.2 · Görsel 1.1 |
| 5:01 | Senkron devir | 1.1.3 · Tablo 1.1 |
| 5:39 | Neden "asenkron"? | 1.1.3 |
| 6:08 | Kayma | 1.1.3 |
| 6:43 | Takometre | 1.1.3 · Görsel 1.2 |
| 7:16 | Yol alma akımı | 1.1.4 |
| 8:03 | Yıldız (Y) bağlantı | 1.1.4 · Şekil 1.4–1.5 |
| 8:34 | Üçgen (Δ) bağlantı | 1.1.4 · Şekil 1.6–1.7 |
| 9:03 | Yıldız üçgen yol verme | 1.1.4 |
| 9:47 | Devir yönü değiştirme | 1.1.5 · Tablo 1.2 |
| 10:15 | Frenleme | 1.1.6 · Grafik 1.1 |
| 10:53 | Bir fazlı asenkron motorlar | 1.1.7 |
| 11:34 | Özet | 1.1 |

## Nasıl üretildi

- **Senaryo:** kitabın 1.1 bölümünden; terimler ve sayısal örnekler kitaptakiyle aynı (ör. 1500 / 1450 → kayma %3,33; 7,5 kW 14,8 A → direkt 74 A, yıldızda 24,6 A).
- **Seslendirme:** Microsoft Türkçe neural ses (tr-TR-AhmetNeural), her cümle ayrı; kelime zaman damgaları kaydedilir.
- **Senkron:** animasyon olayları ve kurgu efektleri, ilgili kelimenin söylendiği ana bağlıdır; birleştirmede anlatım her sahnenin ilk karesine örnek düzeyinde hizalanır (ölçülen en büyük kayma 1,7 ms).
- **2D animasyonlar:** Manim; **3D sahneler:** Blender 5.2.2 (EEVEE), seslendirmeye göre yeniden zamanlandı.
- **Kurgu katmanı:** yakınlaştırma, spot (çevreyi bulanıklaştırma), ok, vurgu kutusu, parçayı takip eden etiketler.
