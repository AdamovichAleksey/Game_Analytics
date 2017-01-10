### Полное описание тестового задания можно прочитать в файле [Task_Match-3_Game.pdf] (https://github.com/AdamovichAleksey/Game_Analytics/blob/master/match-3_Game/Task_Match-3_Game.pdf)
Коротко:
Dataset [test_fd2.csv.gz](https://drive.google.com/open?id=0ByG1MRsDxjxLalR1MU5sUm5keTQ) (разархивированый csv файл 7.7 Gb)

Задача: исследовать данные о прохождении игроками уровней match3-игры и выполнить следующие задания:

  1. Определить DAU (Daily active users).
  2. Определить распределение игроков по уровням.
  3. Предложить метрику, описывающую сложность уровней и рассчитать ее.
  4. Если в процессе исследования будут обнаружены любые интересные факты - будет плюсом, если они будут указаны и визуализированы

### Выполнение задания можно посмотреть сохранив [архив html файлов](https://github.com/AdamovichAleksey/Game_Analytics/blob/master/TownShip/Analysis.html) или через Juputer Notebook:
* **Playrix2_df_processing** - предобработка [датасета](https://drive.google.com/open?id=0ByG1MRsDxjxLalR1MU5sUm5keTQ), чтобы уменьшить размер и разбить на части.
* **Playrix_Test2**- анализ исходного датасета с выводами. Предворительный анализ выполнялся на части базы (в данном случае 20 млн строк) из-за ограничения памяти.
* **DAU - by_Combining** - решение задачи №1
* **LVL_Distribution - by_Combining** - решение задачи №2
* **LVL_Difficulty - by_Combining** - решение задачи №3 и №4
