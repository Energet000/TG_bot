# TG_bot
Умный чат-бот для Telegram с использованием методов машинного обучения. Файл BIG_BOT_CONFIG содержит типичные запросы и ответы на них, разбитые на разные намерения. На этом датасете обучался линейный классификатор, на вход подавались запросы, а выходом являлся один из возможных ответов. Если модель не может дать ответ на текущий запрос, то проводится поиск похожих запросов в файле dialogues.txt, которые включает в себя реплики и ответы из художественной литературы. Если и в этом датасете не получается найти ответ, то бот выдает ответ-заглушку по типу:"Извините, я еще учусь"
Ссылка на файл dialogues.txt:
https://drive.google.com/file/d/1eMXU_FDUOmyD00VLtGMdEiggOEY3R0t5/view?usp=sharing
