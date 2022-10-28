# Documentation for ISharp

## Create a working area.

### First you need to install Python.

Download the [Raiden89](https://github.com/Mops2008wer/RaidenSystem89) and [PCP](https://github.com/Mops2008wer/Python-Computer-Progect) files.
Unzip the PCP files. Next, copy the Raiden89 installation file and open it, Raiden89 will install itself.

Open the applications folder in the directory where you copied all the files using any code editor.

##Syntax and structure of applications.

All programs must be in the "apps" folder

There are 3 types of files:

".app" - application code file
".metadata" - the file is currently stored in these variables
".def" - called file with application code

each line of code is written with a semicolon
each variable in the metadata is written with a dash
each argument in a line is written through equals

In code, the first line should always be a metadata file.

Abbreviations and abbreviations that will be met below:
md_md = compare two metadata
_md = argument indicating that the value will be taken from the metadata, if you do not write it, then the metadatanumber argument does not need to be written.
metadatanumber = enter metadata number
text = enter any text
metadatasave = number of the metadata where the value will be saved
_file = argument indicating that the value will be taken from a file

## All commands and their syntax:

Text output: print=(_md or text)=(metatatanumber);
Getting text: input=(text)=(metadatasave);
Text output with interface: print_ui=(_md or text)=(metadatanumber)=(falseOR metadatanumber);
Getting text: input_ui=(text)=(metadatasave);
Working with metadata: metadata=(text)=(metadatasave);
Working with metadata: metadata=(_md or _file)=(filename)=(metadatanumber);
Run the program: run=(_md or _file)=(metatatanumber or filename);
Run the program: run=(text);
Operations with numbers: intopr=(+, -, //, *)=(metadatanumber1)=(metadatanumber2)=(metadatasave);
Conditions: true_false=(md_md)=(metadatanumber1)=(metadatanumber2)=(1func)=(2func);
Conditions: true_false=(_md)=(metadatanumber1)=(text)=(1func)=(2func);

Russian version of the documentation!

# Документация для ISharp

## Создание рабочей зоны.

### Для начала вам необходимо установить Python.

Загрузите файлы [Raiden89](https://github.com/Mops2008wer/RaidenSystem89) и [PCP](https://github.com/Mops2008wer/Python-Computer-Progect).
Разархивируйте файлы PCP. Далее скопируйте установочный файл Raiden89 и откройте его, Raiden89 установится сам.

Откройте папку с приложениями в каталоге, куда вы скопировали все файлы, с помощью любого редактора кода.

##Синтаксис и структура приложений.

Все программы должны быть в папке "apps"

Есть 3 типа файлов:

".app" - файл с кодом приложения
".metadata" - файл в токотом хранятся вте переменные
".def" - вызываемый файл с кодом приложения

каждая сторчка кода пишеться через точку с запятой
каждая переменная в метадате пишется через тире
каждый аргумент в строчке пишеться через равно

В коде первая строчка всегда должна быть файлом с метадатой.

Сокращения и бааревиатуры которые будут встречены далее:
md_md = сравнение двух метадат
_md = аргумент обозначающий что значение будет взято из метадаты, если не писать его, то аргумент metadatanumber писать не нужно.
metadatanumber  = впишите номер метадаты
text = впишите люьой текст
metadatasave = номер метадаты в которую будет сохранено значение
_file = ргумент обозначающий что значение будет взято из файла

## Все команды и их синтаксис:

Вывод текста: print=(_md или text)=(metadatanumber);
Получение текста: input=(text)=(metadatasave);
Вывод текста с интерфейсом: print_ui=(_md или text)=(metadatanumber)=(falseИЛИ metadatanumber);
Получение текста: input_ui=(text)=(metadatasave);
Работа с метадатой: metadata=(text)=(metadatasave);
Работа с метадатой: metadata=(_md или _file)=(filename)=(metadatanumber);
Запуск программы: run=(_md или _file)=(metadatanumber или filename);
Запуск программы: run=(text);
Операции с числами: intopr=(+, -, //, *)=(metadatanumber1)=(metadatanumber2)=(metadatasave);
Условия: true_false=(md_md)=(metadatanumber1)=(metadatanumber2)=(1func)=(2func);
Условия: true_false=(_md)=(metadatanumber1)=(text)=(1func)=(2func);
