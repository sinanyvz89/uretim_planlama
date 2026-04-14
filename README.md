# Üretim Planlama Merkezi

Toz dolum, granül dolum ve elle dolum ürünleri için kapsamlı üretim planlama sistemi.

## Modüller

| Modül | Açıklama |
|-------|----------|
| Dashboard | Genel bakış, KPI özeti, uyarı listesi |
| Kapasite Analizi | Maksimum/optimum kapasite, senaryo karşılaştırma |
| MPS Planlayıcı | Haftalık üretim planı, Gantt çizelgesi, ROP |
| Darboğaz & OEE | TOC analizi, OEE hesaplama, çözüm senaryoları |
| MRP & Stok | BOM, net ihtiyaç hesabı, sipariş takvimi |

## Kullanım

1. **Ayarlar** menüsünden makine, ürün hızı ve stok parametrelerini gir
2. Tüm modüller otomatik güncellenir
3. Dashboard'dan günlük durumu takip et

## GitHub Pages

Bu repo GitHub Pages ile yayınlanmaktadır.  
`Settings → Pages → Branch: main → / (root)` seçilerek aktif edilir.

## Geliştirme Notları

- Tek dosya mimarisi (`index.html`)
- Harici bağımlılık yok
- Tüm veriler tarayıcı belleğinde tutulur
