
![GitHub](https://img.shields.io/github/license/DFGANDP/StyleGan2-Ada_Encoder_projector)

# Scrape and preprocess for PL GPT-2 Rap Generator

## Train Pipeline
```bash
1. Write Your Scraper like in examples:
* Scrape_website
* Scrape_other_website
2. Preprocess
- special chars
- Eng/other language than pl remove [uses Transformers]
- remove similar (e.g two songs which differs only one line)
[uses Transformers] and Sickit-Learn for threshold setting
- Write your preprocwessing
3. Train Model
```
