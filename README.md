# 1c-fake_job_postings

Фичи:
1) все изначально числовые
2) категориальные с небольшим количеством категорий переводим в one-hot'ы
3) из текста каждой вакансии получим средний ветор из word2vec
4) из текста каждой вакансии получим tf-idf и сожмём его PCA

Произведём поиск подходящих классификаторов перебором. Лучше всего сработал SVC.