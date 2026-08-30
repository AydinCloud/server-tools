# AydınCloud Server Tools

AydınCloud tarafından Linux sunucularının yönetimi, sistem kontrolü ve temel bakım işlemlerini kolaylaştırmak amacıyla geliştirilen açık kaynak yardımcı araçlar.

Bu proje; VDS, VPS ve fiziksel Linux sunucularında temel sistem bilgilerini görüntülemek, kaynak kullanımını kontrol etmek ve disk durumunu hızlı şekilde incelemek için hazırlanmıştır.

## Özellikler

- Sistem bilgilerini görüntüleme
- İşletim sistemi ve kernel bilgilerini görüntüleme
- CPU modelini ve çekirdek sayısını görüntüleme
- RAM kullanımını kontrol etme
- Disk kullanımını kontrol etme
- Disk ve dosya sistemi bilgilerini görüntüleme
- Sunucu uptime bilgisini görüntüleme
- CPU ve RAM tüketen işlemleri görüntüleme
- Linux sunucuları için hızlı sistem kontrolleri

## Gereksinimler

- Linux işletim sistemi
- Bash
- Temel Linux sistem komutları
- Bazı sistem kontrolleri için gerekli kullanıcı izinleri

## Proje Yapısı

server-tools/
├── scripts/
│   ├── system-info.sh
│   ├── resource-check.sh
│   └── disk-check.sh
├── .gitignore
├── LICENSE
└── README.md

## Kullanım

Repository'yi sunucunuza klonlayın:

    git clone https://github.com/AydinCloud/server-tools.git

Proje dizinine girin:

    cd server-tools

Scriptlere çalıştırma izni verin:

    chmod +x scripts/*.sh

Sistem bilgilerini görüntülemek için:

    ./scripts/system-info.sh

Kaynak kullanımını kontrol etmek için:

    ./scripts/resource-check.sh

Disk ve dosya sistemi bilgilerini görüntülemek için:

    ./scripts/disk-check.sh

## Scriptler

### system-info.sh

Sunucunun temel donanım ve işletim sistemi bilgilerini görüntüler.

Gösterilen bilgiler:

- Hostname
- İşletim sistemi
- Kernel sürümü
- Sistem mimarisi
- CPU modeli
- CPU çekirdek sayısı
- RAM
- Disk
- Uptime

### resource-check.sh

Sunucunun mevcut kaynak kullanımını hızlı şekilde kontrol etmek için kullanılır.

Kontrol edilen kaynaklar:

- CPU yükü
- RAM kullanımı
- Disk kullanımı
- CPU tüketen işlemler
- RAM tüketen işlemler

### disk-check.sh

Sunucudaki disklerin ve dosya sistemlerinin durumunu görüntüler.

Kontrol edilen bilgiler:

- Dosya sistemi kullanımı
- Inode kullanımı
- Bağlı dosya sistemleri
- Disk aygıtları
- Disk boyutları
- Mount noktaları

## AydınCloud

AydınCloud, Türkiye merkezli hosting, VDS ve dijital altyapı hizmetleri sağlayıcısıdır.

Web siteleri, uygulamalar, oyun sunucuları ve kurumsal projeler için hosting ve sunucu çözümleri sunuyoruz.

Website:

https://aydincloud.com

## VDS Sunucu

AydınCloud VDS sunucu hizmetleri hakkında detaylı bilgi:

https://aydincloud.com/vds-sunucu-satin-al/

## WordPress Hosting

WordPress siteleri için optimize edilmiş hosting çözümleri:

https://aydincloud.com/wordpress-hosting-satin-al/

## Blog

Hosting, VDS, WordPress, Linux, sunucu yönetimi ve web teknolojileri hakkında teknik içerikler:

https://aydincloud.com/blog/

## Katkıda Bulunma

Hata bildirimleri, geliştirme önerileri ve katkılar GitHub Issues ve Pull Requests üzerinden paylaşılabilir.

## Lisans

Bu proje MIT License altında yayınlanmaktadır.

## AydınCloud

Hosting • VDS • WordPress Hosting • Sunucu Çözümleri

https://github.com/AydinCloud

https://aydincloud.com
