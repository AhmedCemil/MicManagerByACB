[English](README.md) | [Türkçe](README.tr.md)

# MicManagerByACB

Sistem tepsisi entegrasyonlu hafif bir Windows mikrofon sessiz/açık aracı.

## Özellikler

- **Global Kısayol Tuşu**: Özelleştirilebilir kısayol tuşu ile mikrofonu sessiz/açık yapın (varsayılan: Menu tuşu)
- **Sistem Tepsisi**: Görsel sessiz durumu göstergesi ile sistem tepsisi simgesinden kolay erişim
- **Çoklu Mikrofon Desteği**: Mevcut mikrofonlar arasında seçim yapın ve geçiş yapın
- **Ekran Bildirimleri**: Sessiz durumu değiştiğinde görsel geri bildirim
- **Harici Değişiklik Algılama**: Diğer uygulamalar tarafından yapılan sessiz değişikliklerini algılar
- **Yerelleştirme**: İngilizce ve Türkçe dil desteği (sistem dilini otomatik algılar)
- **Başlangıçta Çalıştır**: Windows ile otomatik başlatma seçeneği
- **Pasif Mod**: Kısayol tuşunu yakalamadan sadece izleme modu
- **Kısayol Tuşu Engelleme**: İsteğe bağlı olarak kısayol tuşunun orijinal işlevini engeller

## Kurulum

1. [Releases](https://github.com/AhmedCemil/MicManagerByACB/releases) sayfasından son sürümü indirin
2. `MicManagerByACB.exe` dosyasını çalıştırın
3. Uygulama sistem tepsinizde görünecektir

## Kullanım

- Sessiz/açık durumunu değiştirmek için tepsi simgesine **çift tıklayın**
- İçerik menüsü için tepsi simgesine **sağ tıklayın**:
  - Mikrofonu Sessiz/Açık Yap
  - Mevcut cihazlardan mikrofon seçin
  - Kısayol tuşunu değiştir
  - Bildirimleri aç/kapat
  - Kısayol tuşu engellemeyi aç/kapat
  - Pasif modu aç/kapat
  - Başlangıçta çalıştır
  - Dil değiştir (İngilizce/Türkçe)

## Kaynaktan Derleme

### Gereksinimler
- MinGW-w64 (g++ derleyici)
- Windows SDK

### Derleme
```batch
build.bat
```

Çalıştırılabilir dosya `build/` klasöründe oluşturulacaktır.

## Yapılandırma

Ayarlar `%USERPROFILE%\.micmanager\config.json` dosyasında saklanır.

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.

## Geliştirici

Ahmed Cemil Bilgin tarafından geliştirilmiştir.

- GitHub: [AhmedCemil](https://github.com/AhmedCemil)
