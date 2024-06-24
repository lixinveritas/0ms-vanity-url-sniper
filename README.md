# Discord Vanity URL Sniper

Bu proje, belirli bir Discord Vanity URL'sini almayı hedefler. Saniyede 0-5ms aralığında 500 deneme yaparak API yasağı almadan çalışır. Proje, bir bot hesabı ve bir kişisel hesap ekleyerek çalışmaktadır.

## Özellikler

- **Hızlı Deneme:** Saniyede 500 deneme yaparak istenilen Vanity URL'yi almayı hedefler.
- **API Dostu:** API yasağı almadan denemeler yapar.
- **Çoklu Hesap Kullanımı:** Bir bot hesabı ve bir kişisel hesap ile çalışır.

## Gereksinimler

- Python 3.10 veya üstü
- Bir Discord bot hesabı
- Bir kişisel Discord hesabı

## Kurulum

### Adım 1: Depoyu Klonlayın

bash
git clone [https://github.com/kullaniciadi/discord-vanity-url-sniper.git](https://github.com/lixinveritas/0ms-vanity-url-sniper)
cd discord-vanity-url-sniper

### Adım 2: Bağımlılıkları Yükleyin

Yöntem 1: Tek Tek Yükleme
requirements.txt dosyasındaki bağımlılıkları tek tek yüklemek için:

pip install -r requirements.txt

Yöntem 2: Otomatik Yükleme
kurulum.bat dosyasını çalıştırarak tüm bağımlılıkları otomatik olarak yükleyin

### Adım 3: Yapılandırma
Proje dizininde veritas.txt dosyasının içini doldurun formatta yapılandırın:

# url:sunucuid:hesaptoken formatında bilgi girin
# url:sunucuid:bot_tokeni
# url:sunucuid:kullanici_tokeni

Herhangi bir sorunuz olursa, sormaktan çekinmeyin! 
[issues](https://github.com/lixinveritas/0ms-vanity-url-sniper/issues)

## [@lixinveritas](https://discordapp.com/users/718287701987688491)
