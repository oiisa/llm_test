# llm_test
Для того, чтобы извлечь город из сообщений была использована библиотека spacy c моделью для русского языка. При помощи entity recognizer были ивзлечены именованые сущности(города) и добавлены к исходному датасету. Модель не справилась с 12 сущностями из 120. Среди них: ЕКБ, СПб, екб, мск, екат. Если сделать предобработку данных - сделать все слова с большой буквы, модель сможет распознать еще 5 городов.
