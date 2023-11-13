---
id: "aspose-cells-for-java-8-0-0-release-notes"
slug: "aspose-cells-for-java-8-0-0-release-notes"
linktitle: "Aspose.Cells for Java Примечания к выпуску 8.0.0"
title: "Aspose.Cells for Java Примечания к выпуску 8.0.0"
weight: 70
description: "Aspose.Cells for Java Примечания к выпуску 8.0.0 – the latest updates and fixes."
type: "repository"
layout: "release"
family_listing_page_title: "Aspose.Cells for Java Примечания к выпуску 8.0.0"
---
{{% alert color="primary" %}}

 Эта страница содержит примечания к выпуску для[Aspose.Cells for Java 8.0.0](https://releases.aspose.com/cells/java/new-releases/aspose.cells-for-java-8.0.0/)

{{% /alert %}}

Aspose.Cells for Java был обновлен до версии 8.0.0, и мы рады сообщить, что в этом выпуске добавлено более 30 новых полезных улучшений.
Используя Aspose.Cells for Java, вы можете работать с XLS, SpreadsheetML, OOXML, XLSB, CSV, HTML, ODS, PDF, XPS и другими форматами в ваших приложениях. Вы также можете создавать, изменять, преобразовывать, визуализировать и печатать рабочие книги, не используя Microsoft Excel.
Посетите документацию, чтобы узнать, как начать работу с Aspose.Cells for Java.
Обратите внимание, что этот загружаемый файл содержит полностью рабочую версию продукта, однако без набора лицензий он будет работать в ознакомительном режиме с некоторыми ограничениями. Чтобы протестировать Aspose.Cells без этих ознакомительных ограничений, вы можете запросить бесплатную 30-дневную временную лицензию.
Ниже приведен список изменений в этой версии Aspose.Cells for Java.

Основные характеристики

Параметр использования памяти можно использовать для оценки производительности.
При создании книги с большим набором данных ячеек параметр MemorySetting.MEMORY_PREFERENCE может оптимизировать использование памяти для данных ячеек, чтобы снизить затраты памяти.

Другие улучшения и изменения

Новые особенности

(CELLSJAVA-40749) - Получить индексы начальной строки/столбца и конечной строки/столбца для страницы рабочего листа
(CELLSJAVA-40744) - Поддержка функции «Показать формулы» в MS Excel.
(CELLSJAVA-40423) - зависимости Aspose.Cells и Maven
(CELLSJAVA-40770) - Установить время создания в сгенерированном PDF

Улучшения

(CELLSJAVA-40751) - Опечатка в имени метода - SeriesCollection.setSecondCategoryData
(CELLSJAVA-40753) - Разделитель меток данных специальной серии
(CELLSJAVA-40764) - Cell.DisplayStringValue не вычислял точно пробелы, определяемые шириной столбца и '*' в пользовательском стиле.

Ошибки

(CELLSJAVA-40738) - setExportActiveWorksheetOnly изменить выравнивание таблицы в HTML
(CELLSJAVA-40747) — фоновое изображение не копируется в целевую книгу при вызове Workbook.copy.
(CELLSJAVA-40276) — Текст внутри изображения выглядит зеркально при сохранении книги Excel как PDF.
(CELLSJAVA-40573) - Некоторые слова разделяются при сохранении в PDF
(CELLSJAVA-40743) - Автофильтр таблицы не работает в формате xls, но нормально работает в формате xlsx.
(CELLSJAVA-40750) — при экспорте в HTML ячейки, покрытые изображением, теряют цвет фона.
(CELLSJAVA-40748) - Неверный путь к фоновому изображению
(CELLSJAVA-40731) - Проблема с вертикальным текстом
(CELLSJAVA-40737) — Проблема с форматированием фигур/элементов управления в Excel для преобразования PDF.
(CELLSJAVA-40742) — Неправильный перенос меток осей при преобразовании XLSX в PDF.
(CELLSJAVA-40757) — Столбцы DateTime неправильно читаются из CSV с европейской локалью.
(CELLSJAVA-40282) — вывод изображения зеркально отображается при преобразовании рабочего листа Excel в PDF.
(CELLSJAVA-40585) — Aspose.Cells: встроенная сигма-диаграмма неправильно отображается в PDF/images.
(CELLSJAVA-40742) — Неправильный перенос меток осей при преобразовании XLSX в PDF.
(CELLSJAVA-40758) - Данные в выходном PDF-файле неверны.
(CELLSJAVA-40762) - Cell.getDependents(true) issue - Cells из других листов, которых не должно быть в списке
(CELLSJAVA-40756) - CellsException: null в Workbook.calculateFormula(false)
(CELLSJAVA-40748) - Неверный путь к фоновому изображению
(CELLSJAVA-40754) - Экспорт фигур в html с ошибкой цвета фона
(CELLSJAVA-40766) — с XLSX по HTML: проблема с hideColumn, создающим нулевые значения в HTML.
(CELLSJAVA-40769) - Формула пересчета ячейки

(CELLSJAVA-40771) - Проблема со скрытой строкой и высотой строки


Исключения

(CELLSJAVA-40736) - com.aspose.cells.CellsException: недопустимое имя ячейки
(CELLSJAVA-40767) — NullpointerException при сохранении книги.
(CELLSJAVA-40755) — CellsException: переполнение в преобразовании String в int. Строковое значение: #Н/Д.
(CELLSJAVA-40761) - CellsException: ошибка преобразования формы в изображение!

Public API и обратно несовместимые изменения

Ниже приведен список любых изменений, внесенных в общедоступный номер API, таких как добавленные, переименованные, удаленные или устаревшие члены, а также любые несовместимые с предыдущими изменениями, внесенные в номер Aspose.Cells for Java. Если у вас есть сомнения по поводу каких-либо перечисленных изменений, сообщите об этом на форум поддержки Aspose.Cells.

Устарело свойство AutoFilter.FilterColumnCollection
Вместо этого использует AutoFilter.FilterColumns.

Добавляет свойство Worksheet.ShowFormulas
Указывает, отображаются ли формулы или значения формул.

Добавляет свойство PdfSaveOptions.CreatedTime.
Получает и задает время создания pdf-документа.

Добавляет перечисление FileFormatType.Ooxml
Представляет зашифрованный офисный открытый XML-файл (например, XLSX, DOCX, PPTX и т. д.).

Добавляет свойство LoadOptions.MemorySetting и свойство WorkbookSettings.MemorySetting.
Начиная с этой версии мы предоставляем пользователю возможность использования памяти для оценки производительности. Параметр по умолчанию MemorySetting.NORMAL применяется для всех версий. В некоторых ситуациях, таких как создание рабочей книги с большим набором данных для ячеек, параметр MemorySetting.MEMORY_PREFERENCE может оптимизировать использование памяти и снизить затраты памяти для пользовательского приложения. Однако этот параметр может снизить производительность в некоторых особых случаях, таких как случайный и многократный доступ к ячейкам.

Устарело свойство SeriesCollection.SecondCategoryData и добавлено свойство SeriesCollection.SecondCategoryData.
Использует SeriesCollection.SecondCategoryData для замены SeriesCollection.SecondCategoryData.

Реализации Row/Cell/RowCollection изменены
В старых версиях объекты Row и Cell хранятся в памяти для представления соответствующей строки и ячейки на листе. Один и тот же экземпляр будет возвращаться всякий раз, когда пользователь вызывает такие методы, как RowCollection[int index], Cells[int, int] и т. д. Из соображений производительности памяти, начиная с этой версии, в памяти будут храниться только свойства и данные Row и Cell. Объект Row/Cell станет оболочкой этих свойств и данных для удобства пользователя для управления моделью ячеек и будет заново создан при вызове пользователя. эти методы. Итак, теперь пользователь будет получать разные объекты при вызове одного и того же метода для получения Row/Cell много раз, даже если все эти разные объекты ссылаются на одну и ту же строку/ячейку на листе. Это изменение может повлиять на приложение пользователя в следующих ситуациях: 1. Если пользователь использовал код вроде if(row1==row2)...if(cell1==cell2)... для проверки той же строки/Cell, в новых версиях эти проверки могут завершиться ошибкой. Вместо этого используйте row1.equals(row2) и cell1.equals(cell2).2. Поскольку объекты Row/Cell заново создаются в соответствии с вызовом пользователя, они не будут храниться и управляться в памяти компонентом ячеек. После некоторых операций вставки/удаления их положение (индекс строки/столбца) может не обновляться или даже хуже, эти объекты становятся недействительными. Например, для следующего кода: Cell ячейка = ячейки.get("A2");System.out.println(cell.getName() + ":" + cell.getValue());cells.insertRange(CellArea.createCellArea( "A1", "A1"), ShiftType.DOWN); System.out.println(cell.getName() + ":" + cell.getValue()); в старых версиях после вставки ячейка будет ссылаться на A3 операция и ее значение такое же, как и перед вставкой. Однако в новой версии объект ячейки станет недействительным или по-прежнему будет ссылаться на A2 с другим значением. В такой ситуации пользователю необходимо снова получить объект Row/Cell из коллекции ячеек, чтобы получить правильный результат: " + cell.getValue());cells.insertRange(CellArea.createCellArea("A1", "A1"), ShiftType.DOWN);cell = Cells.get("A3");System.out.println(cell. getName() + ":" + cell.getValue());3. RowCollection теперь не наследует CollectionBase, потому что в его внутреннем списке больше нет объекта Row.

Cell.StringValue изменено для специального шаблона форматирования с '*' и '_'
В старых версиях специальный шаблон '* будет игнорироваться при форматировании значения ячейки для Cell.StringValue и '** всегда производит один символ в отформатированном результате. С этой версии мы меняем логику работы с '* и '**', чтобы отформатированный результат был таким же, как тот, который вы можете получить из MS Excel при копировании ячейки как текста (например, копирование ячейки в текстовый редактор или экспорт ячейки в csv). Например, используйте пользовательское «*($* #,##0.00*)» для форматирования значения ячейки 123, в старых версиях Cell. StringValue даст результат «123,00 $». Теперь с новыми версиями Cell.StringValue даст результат как «$123,00», что совпадает с тем, что вы можете получить из MS Excel, скопировав эту ячейку в текст.

Запись
Поскольку кодовая база Aspose.Cells for Java соответствует коду соответствующей версии .NET, большинство изменений, улучшений и исправлений, включенных в Aspose.Cells for .NET v8.0.0, также включены в этот Aspose.Cells for Java v8.0.0.