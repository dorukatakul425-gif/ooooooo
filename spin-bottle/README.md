# Spin Bottle — tam paket

Bu pakette oyunun son sürümü, tüm 45 ikon ve görsel fiziksel dosya olarak bulunur. Görseller public/game-assets içindedir; Lovable görsel bağlantısına ihtiyaç duymaz. İlk gönderdiğiniz ZIP de original-spin-bottle-game.zip adıyla eksiksiz eklenmiştir.

## Çalıştırma

Bun kurulduktan sonra klasörde:

```sh
bun install
bun run dev
```

## YouTube anahtarı

src/lib/youtube-config.server.ts dosyasında YOUTUBE_API_KEY_IN_FILE boş değerine kendi anahtarınızı ekleyin. Alternatif olarak YOUTUBE_API_KEY ortam değişkenini kullanın. Google Cloud üzerinde YouTube Data API v3 açık olmalıdır. Anahtar sadece sunucuda kullanılır. Gerçek arama için internet ve geçerli anahtar gerekir; YouTube bazı videoların gömülü oynatılmasını kısıtlayabilir.

Paket kaynak kodudur: bağımlılıklar ve derlenmiş çıktılar dahil değildir; ilk kurulum internet gerektirir.
