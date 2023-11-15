# Laba_2_PKG


Приложение разработано с целью выполнения задания лабороторной работы №2.

Был использован язык программирования С++ и среда программирования Desktop Qt 5.15 MinGW 32-bit". Данное приложение поддерживает форматы:

png (PNG)

jpg

bpm (BPM)

gif

pcx

tiff

Основные объекты приложения:

Название приложения ( QLabel )

Строка отслеживания пути файла

Две кнопки

Левая кнопка для открытия папки с изображениями

при нажатии открывается окно проводника, где можно выбрать папку

в папке могут находиться изображения и другие файлы разных форматов, но выбраны будут только поддерживаемые этим приложением форматы

Правая кнопка для открытия отдельного изображения

при нажатии открывается окно проводника, где можно выбрать отдельное изображение, которое выбирается только если является поддерживаемым форматом

Окно отображения аналога проводника

Список свойств изображения (название, размер, разрешение, цветовая глубина, сжатие)

Таблица, где отображается необходимая информация об изображениях (название, размер, разрешение, цветовая глубина, сжатие)

Методы:

Открытие проводника и получение пути к отдельному изображению (void widget::OpenFile())

Открытие проводника и получение пути к папке (void widget::ProviderChoice())

Выбор изображения в аналоге проводника (void widget::Direction(const QModelIndex &index))

Добавление в таблицу (void widget::addToTable(const QString &fileName, const QString &size, const QString &resolution, const QString &colorDepth, const QString &compression))

Добавление в таблицу (void widget::addImageToTable(const QString &imagePath))

Библиотеки:
QImageWriter

QDir

QFileInfo

QImage

QHeaderView

QMainWindow

QFileSystemModel

QTableWidget

QFileDialog

QListView

QTableView

QGroupBox

QLable

QPushButton
