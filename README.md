# m—re.org

Kreatif stüdyo landing sayfası.

## Yapı
- `index.html` — tüm site tek dosyada (HTML + CSS + JS inline)
- `vercel.json` — Vercel konfigürasyonu (clean URLs + güvenlik header'ları)

## Yerel olarak çalıştırma
Hiçbir build adımı yok. Dosyayı tarayıcıda aç:
```
open index.html
```
Veya local sunucu:
```
npx serve .
```

## Vercel'e deploy
1. Tüm klasörü Vercel'e sürükle-bırak: https://vercel.com/new
2. Veya GitHub'a push edip Vercel'e bağla — otomatik deploy.

## Domain bağlama (m-re.org)
GoDaddy DNS panelinden:
- A kaydı: @ → `76.76.21.21`
- CNAME: www → `cname.vercel-dns.com`

DNS yayılması 5 dakika ile 24 saat arası.

## Form
Şu an form `console.log` ile çalışıyor. Gerçekten mail göndermek için:
- Formspree (formspree.io) hesabı aç
- Aldığın endpoint URL'ini `index.html` içindeki `TODO` yorumunun olduğu yere koy
- 
