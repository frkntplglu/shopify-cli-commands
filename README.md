## Shopify CLI Faydalı Bulduğum Komutlar

### Bu repoda Shopify tema geliştirme üzerine yaptığım çalışmalarda öğrendiğim CLI komutlarını veya faydalı bilgileri toparlayacağım. Bu komutların detaylarına ve daha birçok faydalı bilgiye ulaşmak için [Dökümantasyon](https://shopify.dev/) sayfasına gidebilirsiniz.

Dawn temasını kopyalayarak yeni bir tema oluşturur.

    shopify theme init

Tarayıcıda açık olan store hesabına bağlantı sağlar.

    shopify login --store https://your-store.myshopify.com/

5 adet örnek ürün oluşturur.

    shopify populate products                                

Hangi kullanıcı ile login olduğunuzun bilgisini verir.

    shopify whoami      

Geliştirdiğimiz temayı store hesabına pushlamamızı sağlar. --unpublished ve --publish gibi flagleri vardır.

    shopify theme push   

Temayı local ortamda ayağa kaldırır ve store adresi üzerinden preview ortamı oluşturur.

    shopify theme serve                    
