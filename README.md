# Asenkron Motor Nasıl Çalışır?

Animasyonlu anlatım videosu, 9 dk 43 sn, 1080p, Türkçe seslendirmeli.

Video dosyaları repoda değil, **Releases** bölümünde (GitHub tek dosya sınırı 100 MB, video daha büyük):

- `asenkron-motor-nasil-calisir-1080p.mp4` — ana kopya (361 MB, en yüksek kalite)
- `asenkron-motor-anlatim.mp3` — yalnızca seslendirme (8:50)

## Bölümler

| Zaman | Bölüm |
|---|---|
| 0:00 | Giriş |
| 0:46 | İki temel kural |
| 1:57 | Motorun içine bakalım |
| 3:20 | Döner manyetik alan |
| 5:07 | Rotor neden döner? |
| 5:51 | Neden "asenkron"? |
| 7:12 | Yük binince ne olur? |
| 7:54 | İleri seviye: moment–hız eğrisi |
| 8:50 | Her yerde, kapanış |

## Nasıl üretildi

- 3D sahneler: Blender 5.2.2 (EEVEE). Motorun sökülmesi, rotor ve stator yakın planları kurgu sürelerine göre yeniden zamanlandı.
- 2D animasyonlar: Python + matplotlib, her sahnenin seslendirme süresine göre render edildi.
- Seslendirme: Microsoft Türkçe neural ses (tr-TR-AhmetNeural), metin `okuma_metni.txt`'den.
- Kurgu: ffmpeg.
