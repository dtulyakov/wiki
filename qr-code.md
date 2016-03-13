QR код
=======

QR-код (Quick Response - быстрый отклик) - матричный код (двухмерный штрих код), разработанный и представленный японской компанией «Denso-Wave» в 1994 году.

**Рассмотрим варианты для Ubuntu**

zbar-tools консольная утилита для считывания
$zbarimg для файлов или url ссылок
$zbarcam для устройства видеозахвата (камеры)

qrencode консольная утилита для считывания и создания

    $ qrencode -o [filename.png] '[text/url/information to encode]'
    $ qrencode -o google.png 'http://www.google.com'
    $ qrencode -o ~/Desktop/google.png -s 6 'http://www.google.com'

qreator ГУИ утилита для создания

Варианты:

    URL - Генерация кода с ссылкой
    Text - Генерация кода с любым текстом
    Geolocation - Ваше местонахождение в QR-коде (только у меня почему-то не загрузилась карта)
    WiFi Network - Генерация кода с данными о Wi-Fi

