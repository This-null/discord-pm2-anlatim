# Pm2 Basit anlatım




## Herkese selam dostlar
- PM2 sistemine yeni yeni geçmiş bulunmaktayım ve bunu müzik botlarında denemek istedim başlangıç olarak
- Sizin le paylaşmak ve sizinde öğrenmeniz açısından 
- Basitçe konuya geçelim PM2 nedir veya nasıl çalışır.
- PM2 sizin kullanmış olduğunuz pc niz veya vds inizi `Web host` gibi kullanmanıza olanak sağlıyan sistemdir.

# Kullanım

- Kullanmak istediğiniz botları node modüllerini `SHIFT + MAUSE RIGHT` kısayolunu yaparak modüllerini indiriniz.
- Sonra `ecosystem.confi.js` dosyası oluşturunuz kısaca şöyle 

![Screenshot_1](https://user-images.githubusercontent.com/60463845/197375920-e6eed0ae-6eea-4919-ab1b-ba8c280ccfb2.png)

- Sonra yapmanız gereken şey klasörlerin main dosyalarını `ecosystem.confi.js` dosyasında belirtmek oda şu şekilde.

```js
module.exports = {
    apps: [
      {
        name: "null-invite",
        namespace: "null Bots",
        script: 'null.js',
        watch: false,
        exec_mode: "cluster",
        max_memory_restart: "500M",
        cwd: "./null-invite"
      },
]
};
```

# Sistemi Çalıştırma

- Bütün config ve sistemleriniz hazır ise botların bulunduğu klasöre `SHIFT + MAUSE RIGHT` kısayolunu kullanarak `CMD` açınız ve 
- `npm init -y` komutu ile temiz bir package.json dosyası oluşturun.
- sonra `npm i pm2@latest -g` yazınız indirme işlemi bittikten sonra ise.
- `pm2 start` yazmanız yeterli olucaktır.

![Screenshot_2](https://user-images.githubusercontent.com/60463845/197376348-2c6f69f2-0ea8-42cc-97d6-17b455e80452.png)



# Sistemi kapatma

- Sikerim böyle sistemi falan derseniz ve kapatmak isterseniz
- `pm2 kill` komutunu yazmanız yeterli olucaktır.

# Loglar nerde amk

- PM2 de logları görüntülemek için masa üstünde `SHIFT + MAUSE RIGHT` kısayolunu kullanarak `CMD` açınız
- ve ardından `pm2 logs` komutunu yazınız.

![Screenshot_3](https://user-images.githubusercontent.com/60463845/197376482-11e77607-40ce-4cf4-b82b-5ebf1f97c01a.png)


# Sevigilerle kalın

- Buradan kısa süre önce tanışmış olduğum ramal dostuma selamlar <3
- Sorun hata veya yardım işlemleriniz için 

- `null#4000` veya 
- web sitemden discorda gelebilir ve satın alın işlemleri yapabilirsiniz.

- https://hornystime.com/discord
- https://hornystime.com/magaza



