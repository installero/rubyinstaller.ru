---
layout: post
title:  "Релиз RubyInstaller 2.6.0-1"
author: Lars Kanis
---
Вышел релиз RubyInstaller-2.6.0-1.
Больше деталей в [этом посте](https://www.ruby-lang.org/en/news/2018/12/25/ruby-2-6-0-released/) и в 
[CHANGELOG](https://github.com/oneclick/rubyinstaller2/blob/master/CHANGELOG-2.6.md).
Имейте в виду, что некоторые гемы пока что несовместимы с Ruby-2.6 на Windows. Поэтому оставайтесь на версии 2.5 
до тех пор, пока 2.6 не станет более стабильной (если вы, конечно, не собираетесь предложить решение одной из проблем).

Если у вас уже стоит одна из предыдущих версий RubyInstaller (2.4.x или 2.5.x), то <b>не нужно её обновлять</b> 
до версии 2.6.x (то есть не скачивайте в ту же директорию): некоторые гемы с расширением C несовместимы между Ruby-2.5 
и 2.6. Лучше создайте новую директорию для версии 2.6.x.

В релизе RubyInstaller-2.6.0-1 мы представили новый инструмент —  __ridk use__. Он может переключаться между версиями 
Ruby внутри консоли. Интерактивный режим можно запустить с помощью команды `ridk use`. По умолчанию эта команда 
сканирует реестр Windows, ищет все версии RubyInstaller и предлагает выбрать нужную. Более подробную инструкцию 
читайте в [вики](https://github.com/oneclick/rubyinstaller2/wiki/The-ridk-tool#ridk-use).

В Ruby-2.6 добавили фичу —  __JIT compiler__. Её можно использовать с RubyInstaller, но работать с ней приходится 
пока только вручную, да и она довольно медленная. В общем, для практического применения всё это ещё не приспособлено. 
Как обычно, подробности, на что JIT compile уже способен, ищите в [FAQ](https://github.com/oneclick/rubyinstaller2/wiki/FAQ#q-how-can-i-use-the-ruby-jit).

Все  бинарники можно [скачать тут]({{ "/downloads/" | relative_url }})!
