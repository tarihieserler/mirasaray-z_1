# tarihieserler

## Miras — Türkiye’yi Keşfet

React, TypeScript, Vite ve Tailwind CSS ile hazırlanmış responsive arayüz.

```sh
npm ci
npm run dev
```

Üretim derlemesi: `npm run build`. Önizleme: `npm run preview`.

Şehir ve durak verileri `src/data.ts` içindedir. 81 benzersiz il, 104 durak ve duraklara özel konum soruları bulunur. Genel test 5 sorudur. Rekor tarayıcının localStorage alanında saklanır.

AI servisi bağlı değildir; panel bunu açıkça belirtir. Gerçek entegrasyonda sunucu tarafında bir sohbet uç noktası oluşturulmalı; API anahtarları istemciye konulmamalıdır. Tarihi içeriklerin kaynaklarla birebir editoryal doğrulaması yayından önce tamamlanmalıdır. Ana sayfa illüstrasyonu yerel SVG dosyasıdır; harici görsel servisine ihtiyaç yoktur.
