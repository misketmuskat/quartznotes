Up: [[014_embedded-meaning]]
# Project Ideas
##### Dink Vakfı - Medyada Nefret Söylemi Çalışmaları
https://hrantdink.org/tr/asulis/faaliyetler/projeler/medyada-nefret-soylemi
https://hrantdink.org/attachments/article/829/Medyada%20Nefret%20S%C3%B6ylemi%20%C4%B0zleme%20Raporu%20Ocak-Nisan%202017.pdf

## Usable Datasets:
- [Turkey Earthquake Relief Tweets Dataset](https://www.kaggle.com/datasets/ulkutuncerkucuktas/turkey-earthquake-relief-tweets-dataset) — 464 unique values
- [Daily Public Opinion on Israel-Palestine War](https://www.kaggle.com/datasets/asaniczka/reddit-on-israel-palestine-daily-updated) — 2274536 unique values
- [History of Philosophy](https://www.kaggle.com/datasets/kouroshalizadeh/history-of-philosophy) — 360808 unique values
- [Grand National Assembly of Turkish Parliament Transcripts 1920-2015](https://tulap.cmpe.boun.edu.tr/entities/dataset/84b30ee2-c748-4a6d-8bde-bff2ae4f9f82/full)

### Turkish NLP Resources
- https://github.com/agmmnn/turkish-nlp-resources

# Proje
- **Hedef Kelimeler Belirlemek**
	- **Otoriterleşme ile İlişkili Kelimeler:** baskı, otorite, yasak, 
	- **Toplumsal Direnişle İlişkili Kelimeler:** özgürlük, demokrasi, adalet, hak, direniş, ifade,
	- **Diğer Öneriler:** beka, milli, yerli, terörist, terör, hain, 
- **Corpus’u Dönemlere Ayırma**
	- **2011-2013 (Gezi Parkı öncesi)**
	- **2013-2016 (Gezi Parkı sonrası)**
	- **2016-2017 (Darbe girişimi ve Anayasa referandumu dönemi)**
	- **2017-2022 (Cumhurbaşkanlığı seçiminden sonrası)**

- ### Size of the Data
	- 2011_H2 - 2016_H1 Corpus: 15.038.733 tokens, 1.501.323 sentences
	- 2016_H2 - 2022_H2 Corpus: 18.315.637 tokens, 1.785.529 sentences
### Technical Difficulties Encountered 
- Türkçe'nin sondan eklemeli bir dil oluşu ve kelime kökenlerine ihtiyaç duymamız. 
	- Talk about Turkish grammar: Yapım ekleri ve çekim ekleri: 
	- yumuşayan harfler: ağaç → ağac-ı (akkusativ), köpek → köpeğ-e (dativ)
	- passive voice: çekmek, çekilmek, çekiliş, çek
```
input:
print(model.most_similar("demokrasi"))

output:
[('laiklik', 0.8246017694473267), ('demokrasinin', 0.8242803812026978), ('demokratik', 0.8132491707801819), ('demokrasiye', 0.8128859996795654), ('özgürlük', 0.8012840747833252), ('“demokrasi', 0.798303484916687), ('özgürlükler', 0.792658805847168), ('demokrasisi', 0.7881730198860168), ("'eşitlik", 0.7821219563484192), ('10.günakhisar’da', 0.7809323072433472)]
```
- **Stemming - Lemmatization**
	- Zemberek vs Snowball:
		- https://github.com/ahmetaa/zemberek-nlp
		- Snowball: kalem → kale | kalem: pen, my castle, my |   
		- [Performance of Turkish Information Retrieval](https://www.researchgate.net/publication/263465256_Performance_of_Turkish_Information_Retrieval_Evaluating_the_Impact_of_Linguistic_Parameters_and_Compound_Nouns)







##### Tartışmalı Dönemlerde Söylem Analizi [[word2vec-project-2]]
- **Amaç:** 1960 ve 1980 darbeleri gibi kritik tarihsel dönemlerde TBMM’deki söylemin analizi.
- **Fokus:**
    - Dönem öncesi, sırası ve sonrasında “demokrasi,” “anayasa,” “ordu” gibi kelimelerin bağlamlarının nasıl değiştiği.
- **Metodoloji:**
    - Dönemlere ayrılmış bir korpus üzerinde Word2Vec modeli eğitmek.
    - Kritik kelimelerin zaman içindeki semantik değişimlerini analiz etmek.

