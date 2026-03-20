# mt-hallucinations-analysis
Выявление триггеров галлюцинации при машинном переводе и ее устранение.
- Перевод осуществляется с помощью модели nllb-200-distilled-600M с итальянского на английский и русского на финский
- Близость источника и перевода считается по косинусному расстоянию между эмбеддингами, сгенерированными моделью bge-m3
## Использованные датасеты и корпуса:
- Taiga — Shavrina T., Shapovalova O. (2017) To the methodology of corpus construction for machine learning: «Taiga» syntax tree corpus and parser. in proc. of “CORPORA2017”, international conference, Saint-Petersbourg, 2017.
- PAISÀ — Lyding, V., Stemle, E., Borghetti, C., Brunello, M., Castagnoli, S., Dell’Orletta, F., Dittmann, H., Lenci, A., & Pirrelli, V. (2013). PAISÀ Corpus of Italian Web Text. http://hdl.handle.net/20.500.12124/3
- ITA-CASEHOLD — Licari, D., Bushipaka, P., Marino, G., Comandé, G., & Cucinotta, T. (2023). Legal Holding Extraction from Italian Case Documents using Italian-LEGAL-BERT Text Summarization. Proceedings of the Nineteenth International Conference on Artificial Intelligence and Law, 148–156. https://doi.org/10.1145/3594536.3595177
- ru-medical-texts-ophtalmology — Sapunov, G. (2024). Ophthalmology Russian/English Translations (Version 3) [Data set]. Kaggle. https://www.kaggle.com/datasets/cheshrcat/ru-medical-texts-ophtalmology
- sentence-level complexity in Russian — Vladimir Ivanov, Elbayoumi Mohamed Gamal (2023). A dataset for sentence-level complexity in Russian. https://doi.org/10.5281/zenodo.7937827
