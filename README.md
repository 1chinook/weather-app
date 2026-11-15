# Weather App

Şehre göre anlık sıcaklık, nem ve rüzgâr hızını gösteren bir tarayıcı uygulaması.

## Kurulum ve çalıştırma

`index.html` dosyasını açın. [Open-Meteo](https://open-meteo.com/) ve bölgesel arka planlar için [REST Countries](https://restcountries.com/) internet bağlantısı gerektirir.

## Kullanım

Bir şehir yazıp arayın. Sonuç ekranındayken **Enter** ile yeni aramaya geçebilirsiniz.

### Kontroller

Node.js 20 veya üzeriyle:

```sh
npm run check
npm test
```

## Proje yapısı

- `weather.js` — şehir araması, veri istekleri ve sonuç ekranı.
- `weather-utils.js` — hava kodları ve bölge eşlemeleri.
- `tests/` ve `images/` — testler ve görseller.
