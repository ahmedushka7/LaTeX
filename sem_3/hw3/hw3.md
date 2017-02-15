## Задание 3

Не забывай, где находится [страничка курса](https://fulyankin.github.io/LaTeX/) с кучей шпаргалок!

**Внимание!** Всё, что вы не успели сделать на паре автоматически становится вашим домашним заданием! Оставшиеся задачи надо доделать. Вы можете получить то количество баллов, которое вам хочется получить. (Это правда, вы очень большой молодец, когда не ленитесь. Более того, вы ещё и очень красивы.)

Когда вы сделали ровно столько задач, сколько хотите, то вы должны:

1. Убедиться, что сейчас не 7 часов утра 22 февраля и дедлайн по домашке ещё не прошёл. (Сноска: я знаю, что сейчас уже почти 22 число! И ты сейчас это читаешь!)
2. Проверить точно ли файл без ошибок компилируется на вашем компьютере.
3. Удостовериться, что каждое новое задание начинается с новой страницы. Отработайте команду `\newpage` если это не так.
4. Заархивировать pdf-файл, tex-файл и все каринки которые были использованы.
5. Положить архив на	свой	Dropbox,	Github,	yandex-disk	или
другой	репозиторий.
6. Заполнить	[уютную	гугл-форму.](https://docs.google.com/forms/d/e/1FAIpQLSe11kxKVfv07iCL1E9yNX7ll9swKImiVwRr1H70lslGzInRSg/viewform)
7. Рано или поздно увидеть баллы за свою работу в [таблице.](https://docs.google.com/spreadsheets/d/1hXMpXN2sM4osNTvlvtVqH5_5WQMY2p4LHrDcEPZCioc/edit?usp=sharing)
8. Не стесняйтесь абсолютно в любое время дня и ночи просить о помощи, если она вам действительно необходима!
9. Обязательно мысленно пошутите на тему: "Ха-ха! Филипп не переделал шапку для семинарского листа!"

### Упражнение 1 (Свои собственные, кровные)

- [2] Написать команду, которая сама будет выводить

\[ x_1 \ldots x_n \]

- [2] Усовершенствовать предыдущую команду. Она должна быть от двух аргументов и при запросе \команда{a}{z}, \команда{1}{6} и \команда{(a,b)}{(c,d)} выдавать соответственно

\[ x_a \ldots x_z \]
\[ x_1 \ldots x_6 \]
\[ x_{(a,b)} \ldots x_{(c,d)} \]

- [2] Сделать так, чтобы чётные главы выводились римскими цифрами, а нечётные русскими буквами.
- [2] Сделать так, чтобы в itemize каждый новый пункт шёл после синей точки.

[! картинка]( )

- [2] Вспомнте проблемы с самой первой пары. Мы писали внутри теста \lim_{x \to 0} \frac{\sin{x}}{x} и получали $\lim_{x \to 0} \frac{\sin{x}}{x}$, хотя нам хотелось бы получить $\lim\limits_{x \to 0} \frac{\sin{x}}{x}$.

   Переопределите команду \lim так, чтобы внутри текста всегда получать желаемое.

- [2] Написать команду, которая будет переворачивать текст, написанный внутри неё вверх ногами. 
- **[2 за каждую]** Придумайте команду, которая здорово упростит жизнь всему человечеству!

### [10] Упражнение 2 (Cowsay)

Cowsay это настраиваемая говорящая и думающая корова! Эта [великая программа](http://citkit.ru/articles/679/) была когда-то написана на Perl и с тех пор не может покинуть многие великие умы.

Если вы используете Linux, то вы можете поставить cowsay, прописав `sudo apt-get install cowsay`. После попробуйте ввести `cowsay Hello, World!`. Не забудте вернуться назад в наш бренный мир после экстаза, который вы испытаете!

![Cowsay_Typical_Output](https://upload.wikimedia.org/wikipedia/commons/8/80/Cowsay_Typical_Output.png)

Создайте в LaTeX своё окружение, которое будет работать по аналогии с cowsay. Нарисуйте все необходимые для него кусочки в Tikz. Можете использовать для этого Geogebra или уже готовые заготовки, которые вы найдёте на просторах интернета. Оригинальные ходы будут щедро поощрены!

### [0-100] Упражнение 3 (Наклеечи)

Каждые полгода в Москве проходит [Датафест.](http://datafest.ru/) Одно из самых крупных собраний людей, которые занимаются анализом данных. На каждый датафест печатается партия отличных наклеек! Главная особенность этих наклеек состоит в том, что их хотят все.

![datafest]( )

Новый датафест уже был 11 февраля в небоскрёбе Mail на станции метро Аэропорт. Следующий будет осенью в здании Yandex на Парке Культуры. Непременно посетите его...

Нарисуйте свою наклейку, используя средства Tikz. Идеология наклеек следующая: на наклейке должен быть либо общеизвестный символ, либо тонкая профессиональная шутка. Например, если вы рисуете макроэкономическую наклеечку, то любой другой случайно увидивший её макроэкономист должен понять нарисованную шутку и захотеть такую наклейку себе. На рисование наклеек отводится три недели. По истечению этого срока все нарисованные наклейки будут выставлены на суд публики. Лучшие из них будут напечатаны и растиражированы! Вам же понравилась первая партия наклеек? Пришло время создавать вторую!

### [Бесценно] Упражнение n+1

На следующем семинаре мы будем изучать пакет minted. Этот пакет используется для красивого оформления кода. Он был написан на языке python. Поэтому для его корректной работы у вас на компьютере должен быть ... python. Ваша задача установить Python. Если у вас Windows, то установите [Анаконду](https://www.continuum.io/downloads). Если у вас Linux, то питон уже у вас на компе. На нём написана часть системы. Можете попробовать удалить его (Спойлер: это не приведёт ни к чему хорошему). Если у вас Mac, то спросите что делать у Саши Тишина.