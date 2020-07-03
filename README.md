# redirect-timer-script
Встраиваемый скрипт, скрывающий один блок и открывающий второй (если он есть), по истечении срока бесплатного доступа

Встраивается в любое место страницы, для этого необходимо скопировать содержимое файла index.html и вставить его в html код страницы.

Для указания времени бесплатного доступа необходимо заменить первый параметр в конце скрипта. 
Указывается в часах (по умолчанию 24), или указывается точная дата в формате "DD.MM.YYYY hh:mm".

Для указания блока, который открыт изначально и блока, который изначально скрыт, во второй и третий аргумент соответственно подаются id этих блоков в формате "#id". При этом второй блок может отсутствовать (в этом случае его id не указывается.

При заходе на страницу со скриптом будет записано время бесплатного доступа, по его истечении, автоматически скрывается первый блок и открывается второй. Следует понимать, что при очистке cookie или смене устройства, отсчет начнется заново, поэтому использование скрипта не гарантирует защиты контента от доступа по истечению указанного времени.
