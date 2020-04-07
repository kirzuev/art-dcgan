# art-dcgan
art-DCGAN for HSE master project

Файлы с кодом: DCGAN128.ipynb для генерации картин 128x128, DCGAN256.ipynb -- 256x256.

Помимо этого присутствует скрипт genre-scrapper.py для выгрузки датасетов с ресурса WikiArts по заданному стилю или жанру.

Примеры запуска:
```
./genre-scraper.py --style=impressionism --output_dir=<dataset_directory>
./genre-scraper.py --genre=abstract --output_dir=<dataset_directory>
```

Модель генерирует новый набор картин.