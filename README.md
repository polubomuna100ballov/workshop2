Отчет по лабораторной работе #2 выполнил:

Шайдуров Савелий Сергеевич
АТ-05 Отметка о выполнении заданий :
Задание	Выполнение	Баллы
Задание 1	*	
Задание 2	*	
Задание 3	*	
Задание 4	*	
Задание 5	#	
##Структура отчета

#Данные о работе: Работа #2. Шайдуров Савелий Сергеевич, Выполнены задачи 1,2,3,4

#Научиться передавать в Unity данные из Google Sheets с помощью Python.

Задание 1. Настроить доступ к google-таблице по api
Ход работы:

Перейти в Google Cloud Console .
Создать новый проект, выбрав Выберите проект - Новый проект .
Дать имя проекта и нажмите кнопку «Создать» .
Перейти Панель управления созданного проекта.
Перейти в Google Drive API , используя текстовый поиск.
Нажать кнопку Включить API .
Перейти в раздел «Учетные данные» и создайте учетные данные для ключа API.
Сохранить файл с ключом в формате JSON на своем компьютере.
Скопировать адрес сервисного аккаунта.
создать Google-таблицу и доступ к ней для редактирования с созданного сервисного аккаунта.
image

Задание 2.Генерация данных с помощью Python и их передача в google таблицу
Ход работы:

Запустить Jupyter Notebook и создать новый .ipynbфайл.
В .ipynb файле реализовать передачу данных в созданную ранее Google-таблицу.
image

image

image

Задание 3.Создание ключа API для передачи данных из google-таблицы в Unity
Создать ключ API для получения данных из таблиц и их обработки в Unity.

image

Задание 4. 4 Новый проект на Unity
Создать новый 3D-проект на Unity.

Добавить в файлы проекта jsonPackage и soundPackage.

Создать на сцене Unity пустой GameObjectи подключите к ней .csскрипт, в котором подключение к Google-таблице по API и подать сигнал в игру в соответствии со считываемыми значениями:

image image

Выводы
В ходе выполнения лабораторной работы мы научились передавать данные из Google Sheets в Unity с использованием Python и настроенного API. Реализованы генерация данных на Python, их передача в Google Sheets, а также использование этих данных в игровом движке Unity для передачи звука в соответствии с экономической моделью динамики.