
## Порядок запуска:

Все скрипты грузились на гугловский сервак и запускались с него. Эффективность кода не гарантируется, но википедию я для своего пользования более чем скачал и более чем кластеризовал.

* wiki_names.py скачивает все названия всех страниц по ссылке:  https://ru.wikipedia.org/w/index.php?title=Служебная:Все_страницы&from= 

* lemm_parser.py скачивает все статьи с википедии и лемматизирует их
* stemm_parser.py скачивает все статьи с википедии и делает их стемминг
* clea_paprser.py скачивает все статьи с википедии без предобработки

* data_prepare.py делает данные совместными с ARTM
* data_uniter.py объединяет разрозненные кусочки с данными

* В блокноте LDA+ARTM обучаем разные модели!
