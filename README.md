# GS1 Barcode & Digital Link Decoder (Sunrise 2027) — Python Client

[![PyPI version](https://img.shields.io/pypi/v/gs1-decoder-client.svg)](https://pypi.org/project/gs1-decoder-client/)
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/57865358-8bafe64c-1441-4fe3-ba7a-2d60bdeb7dc5)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![RapidAPI Listing](https://img.shields.io/badge/RapidAPI-Dedicated%20Listing-blueviolet)](https://rapidapi.com/noor-mkdad-apis-noor-mkdad-apis-default/api/gs1-barcode-digital-link-decoder-sunrise-2027)

Official zero-dependency Python client for **GS1 Barcode & Digital Link Decoder (Sunrise 2027)**.

> Decode GS1 DataMatrix, GS1-128, FNC1 Barcodes and GS1 Digital Link URIs into structured JSON in sub-5ms.

> 🔑 **Get your Dedicated API Key:** [Subscribe to GS1 Barcode & Digital Link Decoder (Sunrise 2027) on RapidAPI](https://rapidapi.com/noor-mkdad-apis-noor-mkdad-apis-default/api/gs1-barcode-digital-link-decoder-sunrise-2027)

---

## 🚀 Installation

```bash
pip install gs1-decoder-client
```

---

## ⚡ Quickstart

```python
from gs1_decoder_client import Gs1DecoderClient

# Zero config for sandbox testing, or pass your RapidAPI key for production
client = Gs1DecoderClient(api_key="YOUR_RAPIDAPI_KEY")

result = client.validate({
    # Enter validation payload
})

print(result)
```

---

## 📚 API Reference

### `Gs1DecoderClient(api_key=..., base_url=...)`
- `api_key` *(optional)*: RapidAPI Key (`x-rapidapi-key`).
- `base_url` *(optional)*: Direct edge worker override URL.

### `client.validate(payload)`
Dispatches standard validation / parse request with sub-5ms latency.

### `client.get_health()`
Checks edge isolate health and responsiveness.

---

## 🔗 Links
- 📖 [RapidAPI Documentation & Key](https://rapidapi.com/noor-mkdad-apis-noor-mkdad-apis-default/api/gs1-barcode-digital-link-decoder-sunrise-2027)

## 📄 License
MIT © Noor Mkdad
