# SmartRegener – Rejeneratif Frenleme Destekli DC Motor Sürücüsü

SmartRegener, TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destek Programı kapsamında geliştirilen, rejeneratif frenleme özellikli STM32G474 tabanlı bir fırçalı DC motor sürücü sistemidir.

Proje, hafif elektrikli araçlar, eğitim platformları ve enerji geri kazanım uygulamaları için düşük maliyetli ve yüksek verimli bir motor kontrol mimarisi geliştirmeyi amaçlamaktadır. Sistem; motor sürme, akım ölçümü, koruma mekanizmaları ve haberleşme altyapılarını tek bir donanım üzerinde birleştirmektedir.

## Temel Özellikler

* STM32G474 yüksek performanslı mikrodenetleyici
* DRV8701 tabanlı H-Köprü motor sürücü mimarisi
* Rejeneratif frenleme ve enerji geri kazanımı
* INA240 ile hassas akım ölçümü
* Ters polarite koruması
* Aşırı akım koruması
* ESP32 tabanlı kablosuz haberleşme altyapısı
* Hall sensör ve gaz kolu desteği
* UART, SWD ve genişletilebilir sensör arayüzleri
* Çok katmanlı PCB mimarisi

## Donanım Özellikleri

| Parametre         | Değer           |
| ----------------- | --------------- |
| Besleme Gerilimi  | 12 V            |
| Motor Gücü        | 120 W           |
| Mikrodenetleyici  | STM32G474RET6   |
| Gate Driver       | DRV8701         |
| Haberleşme        | ESP32           |
| Akım Ölçümü       | INA240          |
| PCB Yapısı        | 6 Katman        |
| PCB Tasarım Aracı | Altium Designer |

## PCB Tasarımı

Projenin Rev2 sürümünde 6 katmanlı PCB mimarisi kullanılmıştır. Tasarım sürecinde aşağıdaki mühendislik konularına odaklanılmıştır:

* Yüksek akım taşıyan güç yollarının optimizasyonu
* Düşük empedanslı topraklama yapısı
* Güç ve sinyal katmanlarının ayrıştırılması
* EMI ve gürültü azaltma stratejileri
* Isıl yönetim ve bakır dağılımı optimizasyonu
* Via stitching ve güç düzlemleri kullanımı

## 3D PCB Görselleştirmeleri

Bu depoda SmartRegener Rev2 tasarımına ait:

* Üst görünüş PCB renderları
* İzometrik 3D görseller
* Alt katman görünüşleri
* PCB yerleşim çalışmaları

paylaşılmaktadır.

## Proje Durumu

**Durum:** Geliştirme Aşamasında

**Mevcut Revizyon:** Rev2.0

**Yıl:** 2026

## Kullanılan Araçlar

* Altium Designer
* STM32CubeIDE
* STM32CubeMX
* KiCad Viewer
* GitHub

## Geliştirici

**Mehmet Emre Cebeci**

Yıldız Teknik Üniversitesi
Elektrik Mühendisliği

TÜBİTAK 2209-A Araştırma Projesi
