---
id: "aspose-cells-for-net-22-7-release-notes"
slug: "aspose-cells-for-net-22-7-release-notes"
linktitle: "Aspose.Cells for .NET 22.7 Примечания к выпуску"
title: "Aspose.Cells for .NET 22.7 Примечания к выпуску"
weight: 6
description: "Aspose.Cells for .NET 22.7 Примечания к выпуску – the latest updates and fixes."
type: "repository"
layout: "release"
family_listing_page_title: "Aspose.Cells for .NET 22.7 Примечания к выпуску"
---
{{% alert color="primary" %}}

 Эта страница содержит примечания к выпуску для[Aspose.Cells for .NET 22.7](https://www.nuget.org/packages/Aspose.Cells/22.7.0).

{{% /alert %}}

|**Ключ**|**Резюме**|**Категория**|
|:- |:- |:- |
|CELLSNET-51296| Gridweb продолжает возвращаться к началу при попытке скопировать и вставить|
|CELLSNET-51355|И Range.Top, Left, Width, Height в единицах точек|
|CELLSNET-51367|Преобразование всех листов в одну страницу при сохранении в формате html.|
|CELLSNET-51486|Текст отображается в виде маленьких квадратов|
|CELLSNET-51492|Шрифт по умолчанию не применяется при преобразовании XLSX в HTML|
|CELLSNET-51306|Стили сводных таблиц неправильно скопированы при использовании последней версии Aspose.Cells for .NET|
|CELLSNET-51268|Проблема с формулой COUNTIFS, неправильно обрабатывающей 0|
|CELLSNET-51297|Cell.GetPrecedents() не предоставляет все прецеденты, когда формула ссылается на определенное имя|
|CELLSNET-51399|Именованный диапазон Print_Titles и функция ПОИСКПОЗ возвращает ошибку #ИМЯ|
|CELLSNET-51456|ячейки прыгают, когда нажимают Ctrl+C Ctrl+V, когда высота GridWeb установлена на 100%|
|CELLSNET-51457|контекстное меню не отображается, когда высота установлена на 100% после некоторых строк|
|CELLSNET-51471|список проверки не отображается в пустой ячейке|
|CELLSNET-51469|Текст на изображении отсутствует после конвертации в pdf|
|CELLSNET-51476|Элемент стрелки искажается на изображении|
|CELLSNET-51001|Фигура объекта на графике расположена неправильно|
|CELLSNET-51156| Преобразование диаграммы в изображение — различное отображение диаграммы в выходном изображении|
|CELLSNET-51213|Трехмерная круговая диаграмма отображается неправильно — преобразование диаграммы в изображение|
|CELLSNET-51472|Метки диаграммы отсутствуют с SVG, когда установлено на внешний конец|
|CELLSNET-51491|Неправильные значения, используемые в сериях диаграмм при визуализации в изображение или HTML|
|CELLSNET-51525|Диаграмма водопада отличается при экспорте в HTML/PNG или PDF|
|CELLSNET-51353|Преобразование файла XLSB со ссылкой DDE в файл XLSM изменяет положение приложения DDE в ссылке|
|CELLSNET-51376|Размер страницы автоматически меняется с A4? Письмо для листа|
|CELLSNET-51379| Внешняя ссылка типа OLE в файле XLS читается как тип DDE|
|CELLSNET-51402|Содержимое перемещается из ячейки при сохранении html-файла|
|CELLSNET-51417|Ссылки с фигуры на лист в файле удаляются после обновления с 22.5 до 22.6.1.|
|CELLSNET-51418|Внешняя ссылка типа xlPathMissing изменяется на обычный тип externalLinkPath при преобразовании XLSB в XLSM.|
|CELLSNET-51420|Различия в свойствах документа в файле app.xml|
|CELLSNET-51427|Внешняя ссылка, содержащая специальный символ «#», который не экранируется кодом Aspose.Cells.|
|CELLSNET-51482|Объединение листов из разных книг приводит к повреждению файла, который может привести к сбою MS Excel.|
|CELLSNET-51507|Числовые значения из файла XLSX читаются как 0|
|CELLSNET-51280|Исключение при сохранении файла ODS (RB-60121)|
|CELLSNET-51483|Ошибка загрузки файла с исключением "Исходный массив недостаточно длинный..."|

## **Public API и обратно несовместимые изменения**

Ниже приведен список любых изменений, внесенных в общедоступный номер API, таких как добавленные, переименованные, удаленные или устаревшие члены, а также любые несовместимые с предыдущими изменениями, внесенные в номер Aspose.Cells for .NET. Если у вас есть сомнения по поводу каких-либо перечисленных изменений, сообщите об этом на форум поддержки Aspose.Cells.

### **Добавляет метод Cells.GetDependentsInCalculation(int,int,bool)**

Получает все ячейки, результат вычислений которых зависит от ячейки, заданной строкой и столбцом, в соответствии с текущей цепочкой вычислений. Для ячейки, которая пуста и не была создана в текущей модели ячеек, пользователь может использовать этот метод вместо Cell.GetDependentsInCalculation(bool), потому что более позднему необходимо сначала создать экземпляр объекта ячейки в текущей модели ячеек.

### **Изменяет левую/правую границу ячейки для Cell.GetStyle(), когда соседний столбец скрыт**

В старых версиях, если соседний столбец скрыт для одной ячейки, то левая/правая граница этой ячейки не будет сравниваться с соседней ячейкой, поэтому возвращаемая граница может отличаться от того, что отображается в диалоговом окне MS Excel при установке границы этой ячейки. Начиная с версии 22.7, мы делаем так, чтобы возвращаемая граница всегда была фактическим значением (которое должно совпадать с границей соседней ячейки) ячейки для Cell.GetStyle(). Если пользователю нужно то, что показано для ячейки в MS Excel (когда соседний столбец скрыт, отображаемая граница может быть границей следующего видимого столбца), пользователь может попробовать Cell.GetDisplayStyle().

### **Добавьте свойства Range.Top, Range.Left, Range.Height и Range.Width.**

Получает положение и размер диапазона в пунктах.

### **Удалите класс PowerQueryFormulaCollction и добавьте класс класса PowerQueryFormulaCollection.**

В старом классе опечатка.

### **Добавьте свойства HtmlSaveOptions.ExportPageFooters и HtmlSaveOptions.ExportPageHeaders.**

Указывает, экспортируются ли верхние и нижние колонтитулы при сохранении в виде одного HTML-файла.

### **Добавляет свойство HtmlSaveOptions.ShowAllSheets.**

Указывает, будут ли отображаться все листы при сохранении в виде одного HTML-файла.

### **Устарело свойство HtmlSaveOptions.ExportHeadings и добавлено свойство HtmlSaveOptions.ExportRowColumnHeadings.**

Вместо этого используйте HtmlSaveOptions.ExportRowColumnHeadings.

### **Устаревает Chart.ToImage(string, ImageFormat) и добавляется Chart.ToImage(string, ImageType)**

Вместо этого используйте Chart.ToImage(string, ImageType).

### **Устарело Chart.ToImage(Stream, ImageFormat) и добавить Chart.ToImage(Stream, ImageType)**

Вместо этого используйте Chart.ToImage(Stream, ImageType).

### **Устарело Shape.ToImage(Stream, ImageFormat) и добавлено Shape.ToImage(Stream, ImageType)**

Вместо этого используйте Shape.ToImage(Stream, ImageType).