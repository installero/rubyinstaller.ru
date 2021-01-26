---
layout: post
title:  "Вышел установщик Ruby 3.0.0-1"
author: Lars Kanis
---
Вышел установщик Ruby 3.0.0-1!
Он добавляет в руби много классных фич и улучшений.
Читайте пост [про релиз ruby-3.0.0](https://www.ruby-lang.org/en/news/2020/12/25/ruby-3-0-0-released/), если хотите подробностей.

Ruby-3.0.0 завершает переход к кодировке UTF-8 как основной кодировке на Windows.
Теперь работает полная поддержка всех возможных Unicode-символов для файловой системы и переменных окружения и улучшена совместимость с другими инструментами операционной системы.

Обратите, однако, внимание, что некоторые гемы до сих пор не совместимы с Ruby-3.0 на ОС Windows.
Возможно, стоит пока использовать версию 2.7, пока версия 3.0 не будет поддерживаться.

<b>Не стоит</b> обновлять предыдущие версии установщика Ruby 2.6.x или 2.7.x, устанавливая новую версию установщика Ruby 3.0.x в ту же папку.
Причина — несовместимость гемов с расширениями на языке C для версий ruby-2.7 и 3.0.
Лучше всего использовать другую папку для установки Ruby 3.0.x, как и предложит установщик.

Все бинарники лежат в разделе [Скачать]({{ "/downloads/" | relative_url }})!