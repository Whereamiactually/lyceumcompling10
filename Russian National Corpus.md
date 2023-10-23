# Инструкция по пользованию НКРЯ (Национальным корпусом русского языка)

1. [Основной корпус](https://ruscorpora.ru/)

В поисковое окошко нужно ввести требуемое слово или фразу, а затем нажать "Обзор возможностей".

Так вы попадете на страницу с информацией по запрашиваемому слову или фразе ([пример](https://ruscorpora.ru/explore?req=%D0%BB%D0%B8%D0%BD%D0%B3%D0%B2%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0)). 
Вы можете как искать по точно заданному слову (например, если вы введете "лингвистике" и нажмете на эту опцию, то он будет искать только "лингвистике", но не "лингвистику", "лингвистика" и пр.), так и сделать [лексико-грамматический поиск](https://ruscorpora.ru/search?search=CtQBEqcBCqQBChMKCWRpc2FtYm1vZBIGCgRtYWluChcKB2Rpc3Rtb2QSDAoKd2l0aF96ZXJvcxJ0Ch8KA2xleBIYChbQu9C40L3Qs9Cy0LjRgdGC0LjQutCwCgoKBGZvcm0SAgoACgsKBWdyYW1tEgIKAAoJCgNzZW0SAgoAChUKB3NlbS1tb2QSCgoIc2VtfHNlbXgKCQoDc3luEgIKAAoLCgVmbGFncxICCgAqIQoICAAQChgyIAoQBSAAKKThvO%2FonK4IQAVqBDAuOTV4ADICCAE6AQEwAQ%3D%3D) (в таком случае нужно ввести **лемму** требуемого слова и поиск найдет это слово во всех формах).
На странице лексико-грамматического поиска можно также задать, если надо, необходимые грамматические, семантические и синтаксические признаки (в принципе, весь интерфейс юзер-френдли, поэтому проблем возникнуть не должно).

На той же [странице](https://ruscorpora.ru/explore?req=%D0%BB%D0%B8%D0%BD%D0%B3%D0%B2%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0) можно увидеть график частотности употребления запрашиваемого слова или фразы.
Там можно выбрать интересующий вас период и сглаживание. Результаты представлены по панхроническому корпусу, но статистику можно посмотреть по другим корпусам.

Также на той же странице выводится случайное стихотворение с запрашиваемым словом или фразой. Оттуда же можно перейти на страницу с [портретом слова](https://ruscorpora.ru/word/main?req=%D0%BB%D0%B8%D0%BD%D0%B3%D0%B2%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0&gr=S). Там можно найти скетчи, морфемный разбор слова, его однокоренные слова, формы, слова, похожие на него, тексты, в которых он употребляется, и ещё всякую полезную информацию.
Помимо портрета слова, можно найти также [ссылку](https://academic.ru/searchall.php?SWord=%D0%BB%D0%B8%D0%BD%D0%B3%D0%B2%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0) на сайт academic.ru с толкованиями искомых слов.

2. [Страница с результатами](https://ruscorpora.ru/results?search=Ck8qIQoICAAQChgyIAoQBSAAKMbkrOeZ8f4IQAVqBDAuOTV4ADICCAE6AQFCIwohCh8KA3JlcRIYChbQu9C40L3Qs9Cy0LjRgdGC0LjQutCwMAE%3D)

На странице с результатами поиска представлены все тексты, в которых встретилось искомое слово или фраза. Выдачу можно скачать в формате .csv, чтобы потом с ней можно было работать в Python'e, например.
Рядом с каждым примером есть кнопочки, чтобы посмотреть его в более широком контексте, а также чтобы скопировать его в том числе со ссылкой на произведение, из которого он был взят.

Вкладка KWIC (Key Word In Context - ключевое слово в контексте) показывает тексты, выравненные по искомому слову.

На вкладке со статистикой можно посмотреть на статистику по авторам, сфере функционирования, типу текста и пр.

На вкладке с n-граммами можно смотреть словосочетания разной длины, в которых встретилось искомое слово.

3. [Лексико-грамматической поиск](https://ruscorpora.ru/results?search=Ct4BEroBCrcBChMKCWRpc2FtYm1vZBIGCgRtYWluChcKB2Rpc3Rtb2QSDAoKd2l0aF96ZXJvcxKGAQofCgNsZXgSGAoW0LvQuNC90LPQstC40YHRgtC40LrQsAoKCgRmb3JtEgIKAAodCgVncmFtbRIUChIoUykgJiAoYWNjKSAmIChzZykKCQoDc2VtEgIKAAoVCgdzZW0tbW9kEgoKCHNlbXxzZW14CgkKA3N5bhICCgAKCwoFZmxhZ3MSAgoAKhgKCAgAEAoYMiAKEAUgAEAFagQwLjk1eAAyAggBOgEBMAE=)

В лексико-грамматическом поиске необязательно искать по какому-то слову. Можно просто задать грамматические признаки требуемого слова/требуемых слов, и тогда поиск найдет словоформы любых лексем, подходящих под заданные признаки.
Вот [пример](https://ruscorpora.ru/results?search=CsgBEqQBCqEBChMKCWRpc2FtYm1vZBIGCgRtYWluChcKB2Rpc3Rtb2QSDAoKd2l0aF96ZXJvcxJxCgkKA2xleBICCgAKCgoEZm9ybRICCgAKKQoFZ3JhbW0SIAoeKFYpICYgKGluZGljKSAmICh0cmFuKSAmIChpcGYpCgkKA3NlbRICCgAKFQoHc2VtLW1vZBIKCghzZW18c2VteAoLCgVmbGFncxICCgAqGAoICAAQChgyIAoQBSAAQAVqBDAuOTV4ADICCAE6AQEwAQ==) выдачи по запросу "глагол + изъявительное наклонение + переходный + несовершенный вид".

Также с помощью лексико-грамматического поиска можно искать словосочетания.

4. [Частотный словарь](https://ruscorpora.ru/corpus/main/frequency-dictionary?pageSize=100&page=1&pos=) всех слов в корпусе (также на него можно перейти с основной страницы).

5. Другие корпуса (доступны с главной страницы)

Вот [пример](https://ruscorpora.ru/results?search=CokBEm4KbBJqChMKA2xleBIMCgrQstC10LTRgNC%2BCg0KB2xleF9yZWYSAgoACgoKBGZvcm0SAgoACg8KCW5vcm1fZm9ybRICCgAKCwoFZ3JhbW0SAgoACg0KB21lYW5pbmcSAgoACgsKBWZsYWdzEgIKACoQCggIABAKGDIgCiAAQAV4ADICCAg6AQEwAQ==) поиска в диалектологическом корпусе русского языка.
