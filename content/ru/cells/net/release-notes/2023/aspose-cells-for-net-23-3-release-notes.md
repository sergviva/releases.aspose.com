---
id: "aspose-cells-for-net-23-3-release-notes"
slug: "aspose-cells-for-net-23-3-release-notes"
linktitle: "Aspose.Cells for .NET 23.3 Примечания к выпуску"
title: "Aspose.Cells for .NET 23.3 Примечания к выпуску"
weight: 10
description: "Aspose.Cells for .NET 23.3 Примечания к выпуску – the latest updates and fixes."
type: "repository"
layout: "release"
family_listing_page_title: "Aspose.Cells for .NET 23.3 Примечания к выпуску"
---
{{% alert color="primary" %}}

 Эта страница содержит примечания к выпуску для[Aspose.Cells for .NET 23.3](https://www.nuget.org/packages/Aspose.Cells/23.3.0).

{{% /alert %}}

|**Ключ**|**Краткое содержание**|**Категория**|
| :- | :- | :- |
|CELLSNET-52857|Поддержка установки/чтения/сохранения функции ENCODEURL|
|CELLSNET-52921|Поддержка установки/чтения/сохранения функции LET|
|CELLSNET-52605|Поддержка зависимости System.Drawing.Common от 6.0.0 для net6 и net7.|
|CELLSNET-52840|Обновить формулу вычисляемого столбца при копировании|
|CELLSNET-52742|Эффект тени текста исчезает при сохранении файла в pdf|
|CELLSNET-52802|Цвет шрифта текста смарт-арта должен быть черным.|
|CELLSNET-52634| ПРОМЕЖУТОЧНЫЕ.ИТОГИ и другие агрегатные функции работают некорректно в формуле динамического массива|
|CELLSNET-52752|При вычислении оператора SWITCH возвращается неверное значение Формула массива|
|CELLSNET-52771|Проблема с вычислением формул массива с внешними ссылками, имеющими функции ДВССЫЛ|
|CELLSNET-52858| Ошибка формулы при преобразовании xlsx в xls|
|CELLSNET-52770|Отсутствуют метки осей при преобразовании диаграммы в изображение в проекте NetCore|
|CELLSNET-52888|Экспорт изображения из диаграммы отличается от отображения в Excel|
|CELLSNET-52565| Демонстрация Github: пример привязки источника данных не работает|
|CELLSNET-52861|Установка редактируемого диапазона не влияет на GridWeb|
|CELLSNET-52890|Демонстрация Github: сеансовые режимы GridWeb не работают|
|CELLSNET-44789|Неправильные поля для преобразования xlsx в pdf|
|CELLSNET-52340|Текстовое поле не отображается при преобразовании xlsx в pdf|
|CELLSNET-52759|В объединенной области отсутствует граница при сохранении файла в pdf|
|CELLSNET-52801|Zorder не учитывался при сохранении PDF, если объект занимает более одной страницы|
|CELLSNET-52897|От XLS до PDF: изображение диаграммы EMF не отображается|
|CELLSNET-49337|От HTML до XLSX: некоторые стили отображаются неправильно.|
|CELLSNET-52019| Преобразование Excel в HTML - некоторые столбцы данных смещены, а форматирование нарушено|
|CELLSNET-52501|Копирование диапазона из исходной в целевую книгу не копирует данные/объекты должным образом|
|CELLSNET-52730|PNG изображения внутри ячеек не преобразуются в выходные данные PDF|
|CELLSNET-52736|Содержимое потеряно после повторного сохранения файла Excel|
|CELLSNET-52749|Использование метода Resize приводит к повреждению выходного файла|
|CELLSNET-52788|Ширина скопированных комментариев неверна|
|CELLSNET-52792|Повреждение файла после указания типа изображения при сохранении excel в изображение|
|CELLSNET-52822|Настройки поля комментария меняются с «Автоматически» на «Фиксированное».|
|CELLSNET-52824|Начальная позиция, шрифт и интервал между символами строки символов текстового поля изменены.|
|CELLSNET-52834|Скопированная таблица повреждена при копировании диапазона с другого листа.|
|CELLSNET-52839|Файл Xls поврежден, если заголовок диаграммы является постоянной формулой|
|CELLSNET-52871| Разверните таблицы и переместите другие таблицы под нее|
|CELLSNET-52873|XLSB — HTML: стиль таблицы не сохраняется при преобразовании|
|CELLSNET-52896|Исключение должно быть выдано при смещении части таблицы.|
|CELLSNET-52917|Файл результата аварийно завершает работу при вставке диапазона над таблицей|
|CELLSNET-52922|Тип единицы измерения оси Y должен быть виден при преобразовании диаграммы в pdf.|
|CELLSNET-52901| Название диаграммы отсутствует для древовидной диаграммы|
|CELLSNET-52741|Shape to image Ошибка при сохранении файла в pdf после копирования книги|
|CELLSNET-52828|Исключение нулевой ссылки при копировании диапазона|
|CELLSNET-52829|Исключение возникает при рендеринге предварительного просмотра файла ODS с дополнительным OnePagePerSheet.|
|CELLSNET-52830|Исключение для сохранения и получения предварительного просмотра|

##  **Public API и обратно несовместимые изменения**

Ниже приведен список любых изменений, внесенных в общедоступный номер API, таких как добавленные, переименованные, удаленные или устаревшие члены, а также любые несовместимые с предыдущими изменениями, внесенные в номер Aspose.Cells for .NET. Если у вас есть сомнения по поводу каких-либо перечисленных изменений, сообщите об этом на форум поддержки Aspose.Cells.

###  **Добавляет свойство CalculationOptions.LinkedDataSources.**

Позволяет пользователю установить связанные источники данных для внешних ссылок, используемых в формуле для расчета.

###  **Устаревший класс SvgSaveOptions**

Вместо этого используйте класс ImageSaveOptions.

###  **Устаревший конструктор SvgSaveOptions()**

Вместо этого используйте ImageSaveOptions(SaveFormat.Svg) и задайте для ImageSaveOptions.ImageOrPrintOptions.OnePagePerSheet значение true.

###  **Устарело свойство SvgSaveOptions.SheetIndex.**

Вместо этого используйте ImageSaveOptions.ImageOrPrintOptions.SheetSet.

###  **Добавляет перечисление StyleModifyFlag.FontVerticalText**

Указывает, выровнен ли текст по вертикали.

###  **Добавляет перечисление WarningType.InvalidOperator**

Представляет недопустимый оператор предупреждения при работе с файлами Excel.

###  **Поддерживает настройку свойств Row.GroupLevel и Column.GroupLevel.**

Поддерживает настройку группового уровня строк и столбцов.

###  **Устаревает HtmlLoadOptions.ConvertFormulasData и добавляет свойства HtmlLoadOptions.HasFormula.**

Вместо этого используйте HtmlLoadOptions.HasFormula.

###  **Устареет PivotGlobalizationSettings.GetTextOfProtection() и добавлены методы PivotGlobalizationSettings.GetTextOfProtectedName(String)**

Вместо этого используйте PivotGlobalizationSettings.GetTextOfProtectedName(String).

###  **Добавляет метод Chart.IsReferedByChart(Int32,Int32)**

Указывает, ссылается ли диаграмма на эту ячейку.

###  **Добавляет свойство PasteOptions.IgnoreLinksToOriginalFile.**

Не ссылайтесь на исходный файл при копировании диапазона.

###  **Добавляет PivotArea, PivotTableSelectionType и PivotTable.Format(Pivot.PivotArea, Style)**

Выберите область и отформатируйте ее в сводной таблице.

###  **Добавляет свойство SheetSet.Active**

Получает набор с активным листом книги.
