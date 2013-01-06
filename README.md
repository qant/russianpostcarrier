Модуль Почта России (стандартная посылка и наложенный платеж) для Prestashop 1.5
================================================================================

За основу взят модуль Сергей Родовниченко версии 1.0.6, который рассчитывает стоимость посылки, и добавлен расчет наложенного платежа. Сергей, большое спасибо за модуль!

Описание оригинального модуля приведено на [сайте разработчика](http://www.handmadesite.net/2012/12/pochta-rossii-dlya-prestashop-1-5-pervaya-rabochaya-versiya/).
Код оригинального модуля [тут](http://code.google.com/p/russianpostcarrier/).

При установке модуля создаются 2 перевозчика: 
* Почта России;
* Почта России (наложенный платеж).

В настройках модуля "Russian Post", добавлены параметры для расчета стоимости пересылки денежного перевода: фиксированная сумма и процент от пересылаемой суммы.

Тарифы приведены на [сайте почты](http://www.russianpost.ru/rp/servise/ru/home/finuslug/cybermoney_russia).
Но для некоторых регионов устанавливается индивидуальный тариф, [см.](http://www.russianpost.ru/rp/servise/ru/home/finuslug/cybermoney_russia/cybermoney_russia_regions).
Исключения для этих регионов, пока не предусмотрены. Наложенный платеж будет считаться для всех направлений по одному тарифу.

Модуль находится в процессе разработки, поэтому, если кто захочет его установить, то нужно сделать резервную копию базы данных и файлов.
