# Documentation for ISharp

### Russian documentation below!

## Create a working area.

### First you need to install Python.

Download the [Iden](https://github.com/Mops2008wer/Iden) and [PCP](https://github.com/Mops2008wer/Python-Computer-Progect) files.
Unzip the PCP files. Next, copy the Iden files from the archive, find the installer and open it, Iden will install itself.

Open the applications folder in the directory where you copied all the files using any code editor.

## Syntax and structure of applications.

## At the very beginning, create a .py file in the directory from and import iden_isharp

## First, let's create a variable structure

For example, our application will be called ExampleX89

At the very beginning, we will create 2 lists

app_files = []

app_libs = []

Let's start with the structure of the variables:

metadata_create()

Next, we introduce all the variables we need:

example_string = metadata_add("Hello world!")

example_button = metadata_add("Hello!")

Next, we finish the structure with the command:

metadata = metadata_build("example.metadata")
app_files.append("example.metadata")

(where example.metadata is the name of the file where the variables are stored)

## At the moment we have this code:

from iden_isharp import *

metadata_create()

example_string = metadata_add("Hello world!")

example_button = metadata_add("Hello!")

zagluska = metadata_add("zagluska")

metadata = metadata_build("example.metadata")

## Next, let's create a function!

def_create(metadata)

After we write the first command: i_print!

i_print(example_string, example_button, "false", "default", "false")

The first 2 parameters are responsible for the main text and button text, we will tell you about the rest of the parameters later!

We end the function with the command:

test = def_build("example.app", metadata)

app_files.append("example.app")

(where iden_test.app is the filename of the function)

## Our first application is almost ready, it remains to register the command for the build!

i_build("example", app_files, app_libs, build)

(where example is the name of the application)

## We have this code:

from iden_isharp import *

metadata_create()

example_string = metadata_add("Hello world!")

example_button = metadata_add("Hello!")

zagluska = metadata_add("zagluska")

metadata = metadata_build("example.metadata")

def_create(metadata)

i_print(example_string, example_button, "false", "default", "false")

test = def_build("example.app", metadata)

app_files.append("example.app")

i_build("example", app_files, app_libs, build)

## It remains only to run the file and the application and the installer will be ready!

Other commands can be found below:

## All commands and their syntax:

Text output: i_print(Text, Text for the button, False or text for the exit button, Application style: yae or default, File name for the yae-style image)

Output two texts: i_print2(Text, Second text, Text for button, False or text for exit button, Application style: yae or default, File name for yae-style image)

Getting text: i_print2(Text, Second text, Variable to save, False or text for exit button, Application style: yae or default, File name for yae-style image)

Run program: i_run(Function or application)

Operations with numbers: i_int(Type: +, -, //, *, 1 variable, 2 variable, the variable in which everything will be saved);

Conditions: i_ifelse(Type: md_md (comparison of two variables) or _md (comparison of a variable and text), variable, variable or text, function to be executed if they are equal, function to be executed if they are not equal, or "zagluska");

Working with files: i_file("_file" (if you need to take a value from a file) or "_md" (if you need to write a value from a variable to a file), file, variable);

## Russian documentation:

# Документация для ISharp

## Создание рабочей зоны.

### Для начала вам необходимо установить Python.

Загрузите файлы [Iden](https://github.com/Mops2008wer/Iden) и [PCP](https://github.com/Mops2008wer/Python-Computer-Progect).
Разархивируйте файлы PCP. Далее скопируйте файлы Iden из архива, найдите инсталятор и откройте его, Iden установится сам.

Откройте папку с приложениями в каталоге, куда вы скопировали все файлы, с помощью любого редактора кода.

## Синтаксис и структура приложений.

## В самом начале создаём .py файл в директории от и импортируем iden_isharp

## Для начала создадим струкруру переменных

Для примера наше приложение будет называться ExampleX89

В самом начале создадим 2 списка

app_files = []

app_libs = []

Для начала струкруры переменных введём:

metadata_create()

Далее вводим все нужные нам переменные:

example_string = metadata_add("Hello world!")

example_button = metadata_add("Hello!")

zagluska = metadata_add("zagluska")

Далее заканчиваем структуру командой: 

metadata = metadata_build("example.metadata")

app_files.append("example.metadata")

(где example.metadata это имя файла в котором хранятся переменные)

## На данный момент у нас получился данный код:

from iden_isharp import *

metadata_create()

example_string = metadata_add("Hello world!")

example_button = metadata_add("Hello!")

metadata = metadata_build("example.metadata")

## Далее создадим функцию!

def_create(metadata)

После пропишем первую команду: i_print!

i_print(example_string, example_button, "false", "default", "false")

Первые 2 параметра отвечают за основной текст и текст кнопки, про остальные параметры мы расскажем вам позднее!

Завершаем функцию командой:

test = def_build("example.app", metadata)

app_files.append("example.app")

(где iden_test.app это имя файла функции)

## Наше первое приложение уже почти готово, осталось прописать команду для билда!

i_build("example", app_files, app_libs, build)

(гдк example это название приложения)

## У нас получился данный код: 

from iden_isharp import *

metadata_create()

example_string = metadata_add("Hello world!")

example_button = metadata_add("Hello!")

zagluska = metadata_add("zagluska")

metadata = metadata_build("example.metadata")

def_create(metadata)

i_print(example_string, example_button, "false", "default", "false")

test = def_build("example.app", metadata)

app_files.append("example.app")

i_build("example", app_files, app_libs, build)

## Осталось толкьо запустить файл и приложение и инсталятором будут готовы!

О других командах можно изнать ниже:

## Все команды и их синтаксис:

Вывод текста: i_print(Текст, Текст для конопки, False или текст для кнопки выхода, Стиль приложения: yae или default, Название файла для картинки в yae стиле)

Вывод двух текстов: i_print2(Текст, Второй текст, Текст для конопки, False или текст для кнопки выхода, Стиль приложения: yae или default, Название файла для картинки в yae стиле)

Получение текста: i_print2(Текст, Второй текст, Переменная для сохранения, False или текст для кнопки выхода, Стиль приложения: yae или default, Название файла для картинки в yae стиле)

Запуск программы: i_run(Функция или приложение)

Операции с числами: i_int(Тип: +, -, //, *, 1 переменная, 2 переменная, переменная в которой всё сохраниться);

Условия: i_ifelse(Тип: md_md (сравнение двух переменных) или _md (сравнение переменной и текста), переменная, переменная или текст, выполняемая функция если они равны, выполняемая функция если они не равны или "zagluska");

Работа с файлами: i_file("_file" (если нужно взять значение из файла) или "_md" (если нужно значение из переменной записать в файл), файл, переменная);
