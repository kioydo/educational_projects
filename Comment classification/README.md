# Классификация комментарией
[ipynb](https://github.com/kioydo/educational_projects/blob/main/Comment%20classification/Классификация%20комментариев.ipynb)

## Описание проекта
Необходим инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Стэк
- python
- pandas
- seaborn
- nltk.stem.WordNetLemmatizer
- nltk.stem.wordnet
- nltk.stem.pos_tag
- nltk.stem.word_tokenize
- sklearn.feature_extraction.text.TfidfVectorizer
- sklearn.linear_model.LogisticRegression
- lightgbm.LGBMClassifier
- sklearn.ensemble.RandomForestClassifier
- sklearn.svm.SVC

## Вывод 
В ходе работы была проведена обработка текстовых данных, выявлен дисбаланс классов и приняты меры для его учета в обучении. По результатам метрики выбрана модель Логистичекой регрессии.
