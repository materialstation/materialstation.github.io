---
title: "Liberty Gemileri: Çelik Gevrekleştiğinde"
date: 2026-10-07
description: "İkinci Dünya Savaşı'nın kaynaklı yük gemileri soğuk suda neden çatladı — hatta ikiye ayrıldı — ve bu olaylar mühendislere kırılma hakkında ne öğretti?"
tags: ["kırılma", "çelik", "hasar analizi", "kaynak"]
translationKey: "liberty"
math: true
---

<div class="callout"><p><strong>Örnek vaka analizi.</strong> Bunu şablon olarak kullanın: altı başlığı koruyup içeriği kendi analizinizle değiştirin ya da bu dosyayı silin.</p></div>

## 1. Arka plan

İkinci Dünya Savaşı sırasında ABD, rekor hızda üretilen basit yük gemileri olan yaklaşık 2.700 *Liberty gemisi* inşa etti. Önemli bir yenilik, perçinli gövdeler yerine **tamamen kaynaklı gövdeler** kullanılmasıydı; bu hem zaman hem çelik tasarrufu sağladı.

## 2. Problem

Bu gemilerin ve benzer T2 tankerlerinin birçoğunda ciddi çatlaklar oluştu. Bazıları tamamen ikiye ayrıldı — birkaçı limanda sakin şekilde beklerken. Hasarlar, kışın Kuzey Atlantik gibi **soğuk sularda** yoğunlaşıyordu.

## 3. Malzeme ve servis koşulları

| Etken | Koşul |
|---|---|
| Malzeme | Dönemin sade karbonlu gemi çeliği |
| Birleştirme | Kesintisiz kaynaklı gövde |
| Sıcaklık | Çoğunlukla 0 °C civarı veya altı |
| Geometri | Köşeli ambar ağızları, ani kesit değişimleri |

## 4. Analiz

Hacim merkezli kübik çelikler **sünek–gevrek geçişi** gösterir: Belirli bir sıcaklığın üzerinde kırılmadan önce şekil değiştirip enerji soğururlar; altında ise uyarı vermeden aniden kırılırlar. Gemi çeliğinin geçiş sıcaklığı, servis sıcaklığına çok yakındı.

Kırılma mekaniği bu tehlikeyi şöyle ifade eder: \(\sigma\) gerilmesi altındaki \(a\) uzunluğundaki bir çatlak

$$K_I = Y\,\sigma\sqrt{\pi a}$$

gerilme şiddeti oluşturur ve \(K_I\), malzemenin kırılma tokluğu \(K_{IC}\) değerine ulaştığında hızlı kırılma gerçekleşir. Soğukta \(K_{IC}\) keskin biçimde düştü; ılık suda zararsız olacak çatlaklar kritik hâle geldi.

## 5. Kök neden

Üç etkenin birleşimi:

1. **Düşük sıcaklık tokluğu zayıf çelik** (yüksek geçiş sıcaklığı).
2. **Gerilme yığılmaları** — köşeli ambar ağızları ve kaynak hataları çatlak başlangıç noktası oldu.
3. **Kaynaklı, kesintisiz yapı** — perçinli levhaların aksine kaynak, ilerleyen çatlağa gövde boyunca kesintisiz bir yol sundu.

Constance Tipper'ın Cambridge'deki çalışmaları, yalnızca kaynağın değil çeliğin kendisinin de kritik bir sıcaklığın altında gevrekleştiğini göstermede belirleyici oldu.

## 6. Çıkarılan dersler

- Tokluğu *servis* sıcaklığında belirleyin (ör. Charpy darbe deneyi).
- Gerilme yığılmalarını tasarımla giderin — köşeleri yuvarlatın.
- İlerleyen çatlağın tüm yapıyı geçmesini önlemek için **çatlak durdurucular** ekleyin.
- Bu dersler, modern kırılma mekaniğinin temellerini attı.
