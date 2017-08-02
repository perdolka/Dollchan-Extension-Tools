---
layout: default
language: ru
title: Руководство по написанию обращений
---

## Руководство по написанию обращений

1. Откройте [форму для заполнения](https://github.com/SthephanShinkufag/Dollchan-Extension-Tools/issues/new).
2. Убедитесь, что обращения, подобного вашему не существует в [списке уже известных обращений](https://github.com/SthephanShinkufag/Dollchan-Extension-Tools/issues?direction=desc&sort=created&state=open).
3. Определите тип обращения и укажите его после названием задачи в формате:
    * **#Баг** &mdash; сообщения об ошибке в работе скрипта (Например, "Не работает кнопка скрытия #Баг";
    * **#Улучшение** &mdash; пожелания к улучшению;
    * **#Поддержка** &mdash; вопросы по поддержке или пожелания к изменению существуюшего функционала.

В случае, если вы хотите сообщить о баге:

1. Убедитесь, что Вы используете самую [последнюю версию скрипта](https://raw.github.com/SthephanShinkufag/Dollchan-Extension-Tools/master/Dollchan_Extension_Tools.user.js).
2. Укажите в своем сообщении:
    * браузер и его версию;
    * используемую версию скрипта;
    * имиджборд, на котором встретилась ошибка
    * пошаговые действия для воспроизведения ошибки.

Каким образом разработчик может воспроизвести ошибку на своем компьютере?

Шаги для воспроизведения являются наиболее важной частью любого сообщения об ошибке. Если разработчик в состоянии воспроизвести ошибку, то она, скорее всего, будет исправлена. Если же действия не ясны, то невозможно узнать, каким образом ошибку можно исправить​​.

Опишите способ взаимодействия со скриптом на каждом шаге. Точно опишите наблюдаемые результаты и ожидаемый результат.

Напишите, появляются ли какие-нибудь сообщения в [консоли ошибок](http://help.yandex.ru/mail/faq.xml#error-console) после каждого шага.

Проверьте, наблюдается ли ошибка после сброса всех настроек (окно `"Настройки"` > кнопка `"Сброс"`). Если нет, то постарайтесь определить, из-за какой настройки возникает ошибка.