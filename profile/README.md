# VeriApi.Pro

**Türkiye verileri tek API'de:** namaz vakitleri, hava durumu, döviz ve altın kurları, son depremler, akaryakıt fiyatları, nöbetçi eczaneler, il/ilçe listesi ve daha fazlası.

Turkish public data in one REST API: prayer times, weather, exchange rates and gold prices, earthquakes, fuel prices, on-duty pharmacies, cities and districts.

- Ücretsiz anahtar, kart gerekmez: <https://veriapi.pro/?ref=github>
- Dokümantasyon: <https://veriapi.pro/dokumantasyon>
- OpenAPI: <https://api.veriapi.pro/v1/openapi.json>
- MCP sunucusu (Claude, ChatGPT, Cursor): `https://api.veriapi.pro/v1/mcp`

## Resmî SDK'lar

| Dil | Depo | Kurulum |
|---|---|---|
| PHP | [veriapi-php](https://github.com/veriapipro/veriapi-php) | `composer require veriapi/sdk` |
| Python | [veriapi-python](https://github.com/veriapipro/veriapi-python) | `pip install veriapi` |
| JavaScript / TypeScript | [veriapi-js](https://github.com/veriapipro/veriapi-js) | `npm install @veriapi/sdk` |
| Go | [veriapi-go](https://github.com/veriapipro/veriapi-go) | `go get github.com/veriapipro/veriapi-go` |

Hepsi bağımlılıksız ve MIT lisanslı.

## Hızlı deneme

```bash
curl -H "X-API-Key: va_ANAHTARINIZ" "https://api.veriapi.pro/v1/doviz?kod=USD,EUR"
```
