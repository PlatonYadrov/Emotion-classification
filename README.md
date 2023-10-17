# Классификация с помощью wav2vec2.0
Главный плюс библиотеки wav2vec2.0 это то, что для каждого вида задач (классификация, регрессия или обработка языка) есть предобученные на больших объемах данных. Это способствует лучшей предсказательной способности модели. Ограничения на wav2vec2.0 заключаются в том, предобученные модели обучались с sr=16000, поэтому приходится иметь это ввиду при загрузки в модель своих данных  
Ссылки: официальный сайт [wav2vec2.0](https://huggingface.co/docs/transformers/model_doc/wav2vec2)  
Метрики: подходит метрика accuracy так как количество элементов в классах примерно равное  
# Модель не дообучилась, поэтому это пробная версия
