# Aydınlatma Hesaplama Modülü

E-ticaret siteniz için Gemini yapay zeka destekli profesyonel aydınlatma hesaplama ve ürün önerme modülü.

## Özellikler

-Ampul ve LED panel hesaplamaları
-Oda tipine göre lümen hesaplama
-Akıllı ürün önerileri
-Responsive tasarım
-AI destekli ürün tavsiyeleri

## Kurulum

1. Bu repository'yi klonlayın veya indirin
2. `config.example.js` dosyasını `config.js` olarak kopyalayın
3. API bilgilerinizi `config.js` dosyasına ekleyin
4. `index.html` dosyasını web sunucunuzda çalıştırın

## API Yapılandırması

Modülün tam çalışması için backend API'niz olmalı. (API bilgilerinizi kullandığınız e-ticaret sitesi alt yapınızdan isteyebilirsiniz)

```javascript
const API_CONFIG = {
    BASE_URL: 'https://your-domain.com/api',
    CALCULATE_ENDPOINT: '/calculate-lumen',
    AI_ADVICE_ENDPOINT: '/get-ai-response',
    API_KEY: 'your_api_key_here'
};
