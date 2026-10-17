# ПатанV1

Сайт для подготовки к итоговому занятию № 1 (зачёт) по патологической анатомии.

**Открыть:** https://zsasq1.github.io/patanV1/

- **Микро / Макро** — 19 микро- и 21 макропрепарат: фото, описание по рабочей тетради, что обозначить на рисунке, блок «Запомни», мнемоники.
- **Вопросы** (`voprosy/`) — ответы на 72 вопроса к зачёту.
- **Самопроверка** — скрывает названия и ответы; есть режим «вперемешку».
- **Поиск** по номеру, названию и тексту, увеличение фото, светлая и тёмная тема.

## Источники

- Лекции проф. Н. С. Федоровской и рабочая тетрадь № 1 кафедры патологической анатомии (Киров, 2015).
- Фото препаратов — снимки студента с занятий.
- Всё, чего нет в лекциях и тетради, помечено ★: учебник Струкова–Серова «Патологическая анатомия», WebPath (Университет Юты; только ссылки — их фото нельзя копировать без разрешения).
- Фото, которых нет в папке кафедры (микро № 2, № 4; макро № 8), взяты с Wikimedia Commons под свободными лицензиями, авторы и лицензии указаны на карточках:
  - Yale Rosen — [Pulmonary tuberculosis, necrotizing granuloma](https://commons.wikimedia.org/wiki/File:Pulmonary_tuberculosis_-_Necrotizing_granuloma_(6545186957).jpg), CC BY-SA 2.0;
  - Mikael Häggström — [Histopathology of a lacunar cerebral infarct](https://commons.wikimedia.org/wiki/File:Histopathology_of_a_lacunar_cerebral_infarct.jpg), CC0;
  - Nephron — [Spleen hyaloserositis](https://commons.wikimedia.org/wiki/File:Spleen_hyaloserositis_-_low_mag.jpg), CC BY-SA 3.0.

## Как устроено

Статический сайт без сборки: `index.html`, `voprosy/index.html`, `assets/` (стиль и скрипт), `data/` (тексты препаратов и ответов), `img/`. Чтобы поправить текст, меняйте `data/preparaty.js` или `data/voprosy.js`.

Локально: `python3 -m http.server 8765` в этой папке и открыть http://localhost:8765.
