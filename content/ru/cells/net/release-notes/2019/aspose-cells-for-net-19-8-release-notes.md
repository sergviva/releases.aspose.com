---
id: "aspose-cells-for-net-19-8-release-notes"
slug: "aspose-cells-for-net-19-8-release-notes"
linktitle: "Aspose.Cells for .NET 19.8 Примечания к выпуску"
title: "Aspose.Cells for .NET 19.8 Примечания к выпуску"
weight: 50
description: "Aspose.Cells for .NET 19.8 Примечания к выпуску – the latest updates and fixes."
type: "repository"
layout: "release"
family_listing_page_title: "Aspose.Cells for .NET 19.8 Примечания к выпуску"
---
{{% alert color="primary" %}} 

 Эта страница содержит примечания к выпуску для[Aspose.Cells for .NET 19.8](https://www.nuget.org/packages/Aspose.Cells/19.8.0).

{{% /alert %}} 

|**Ключ**|**Резюме**|**Категория**|
|:- |:- |:- |
|CELLSNET-46823|Поддержка алгоритма цифровой подписи на основе эллиптических кривых (ECDSA) для P-384 и P-521|Новая особенность|
|CELLSNET-46813|Поддержка извлечения файла OLE Embedded .MOL.|Новая особенность|
|CELLSNET-46822|Обнаружение разницы между внутренними и внешними гиперссылками|Новая особенность|
|CELLSNET-42334|Aspose.Cells.Совместимость GridWeb с MVC|Улучшение|
|CELLSNET-46804|Повышение производительности при вычислении большой матрицы с двойными значениями.|Спектакль|
|CELLSNET-46856|Документ не сохраняется при сохранении более 10 раз|Спектакль|
|CELLSNET-46827|Контент отсутствует при преобразовании XLSX в ODS|Ошибка|
|CELLSNET-46833|Формы искажены в преобразовании Excel в PDF|Ошибка|
|CELLSNET-46835|Фигуры чертежа не отображаются должным образом в Excel для рендеринга PDF|Ошибка|
|CELLSNET-46848|Проблема с арабским текстом в Excel для рендеринга PDF|Ошибка|
|CELLSNET-44973|Невозможно установить цвет заливки ячеек сводной таблицы|Ошибка|
|CELLSNET-46818|Не все стили экспортируются при сохранении в HTML|Ошибка|
|CELLSNET-46824|Сводная таблица повреждена после обновления исходных данных сводной таблицы|Ошибка|
|CELLSNET-46820|Проблемы с группировкой данных интеллектуальных маркеров|Ошибка|
|CELLSNET-46840|Проблема с методом Workbook.RemoveUnusedStyles|Ошибка|
|CELLSNET-46853|Некоторые столбцы отображаются красным цветом в Excel до рендеринга PDF.|Ошибка|
|CELLSNET-46829|Объект DBConnection не предоставляет значение для DBConnection.ConnectionInfo|Ошибка|
|CELLSNET-46830|Чтение и запись в запросы|Ошибка|
|CELLSNET-46841|Открытие определенного файла XLS с ошибками Aspose|Ошибка|
|CELLSNET-46845|Проблемы в поведении ImportTableOptions.InsertRows|Ошибка|
|CELLSNET-46846|Файл Excel поврежден после повторного сохранения|Ошибка|
|CELLSNET-46849|Проблема с подключением к внешним данным|Ошибка|
|CELLSNET-46850|Группировка данных не сохраняется при использовании Cells.DeleteRange()|Ошибка|
|CELLSNET-46855|InsertRows неправильно разбивает сгруппированные строки|Ошибка|
|CELLSNET-46858|Преобразование XLSX в ODS изменяет шрифт текста в учебнике|Ошибка|
|CELLSNET-46859|Предварительный просмотр печати не показывает текстовое поле в файле ODS, преобразованном из XLSX|Ошибка|
|CELLSNET-46723|Возникает исключение при получении изображения из SheetRender для зашифрованного файла ODS.|Исключение|
|CELLSNET-46842|Вычисление диаграмм в excel с числом > int.MaxValue приводит к ошибке|Исключение|
|CELLSNET-46828|«IndexOutOfRangeException» при использовании смарт-маркера со сводной таблицей и сохранении книги|Исключение|
|CELLSNET-46814|Исключение «Индекс был за пределами массива» при преобразовании XLSX в PDF|Исключение|
|CELLSNET-46831|Исключение при рендеринге файла Excel на PDF|Исключение|
|CELLSNET-46844|Workbook.CalculateFormula() вызывает NullReferenceException|Исключение|
|CELLSNET-46832|Исключение «Недопустимое строковое значение MsoLineDashStyle» при загрузке файла формата XLSX|Исключение|
### **Public API и обратно несовместимые изменения**
Ниже приведен список любых изменений, внесенных в общедоступный номер API, таких как добавленные, переименованные, удаленные или устаревшие члены, а также любые несовместимые с предыдущими изменениями, внесенные в номер Aspose.Cells for .NET. Если у вас есть сомнения по поводу каких-либо перечисленных изменений, сообщите об этом на форум поддержки Aspose.Cells.
#### **Добавляет класс SheetPrintingPreview**
Предварительный просмотр печати рабочего листа.
#### **Добавляет класс WorkbookPrintingPreview**
Предварительный просмотр печати рабочей книги.
#### **Добавляет свойство QueryTable.ExternalConnection.**
Получает соединение с таблицей запросов.
#### **Добавляет свойство Hyperlink.LinkType и перечисление TargetModeType.**
Представляет тип гиперссылки.