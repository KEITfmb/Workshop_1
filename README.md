# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Кузнецов Игорь Иванович
- РИ-230910
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupyter Notebook.
Ход работы:
- Открыть приложение Anaconda.Navigator (шаг 1.) и из него запустить Jupyter Notebook нажав кнопу "Launch" под соответствующей иконкой (шаг 2).

![Снимок экрана 2024-10-01 022026](https://github.com/user-attachments/assets/24aa679a-82c1-473d-b103-7b2c7252a2e8)

- Создать папку UrFU/AD in GameDev (шаг 3.) и в этой папке создать файл под именем "Hello_World" с расширением ".ipynb", которое ещё называется "Notebook" (шаг 4.)

![Снимок экрана 2024-10-01 022253](https://github.com/user-attachments/assets/e0d2b979-3fe4-4622-b5b8-698c17d7a4db)

![Снимок экрана 2024-10-01 022510](https://github.com/user-attachments/assets/194dfdd5-32b3-4c58-858b-04557551a322)

- Открыть файл "Hello_World.ipynb" и вписать в него следующий код
```py

print("Hello World")

```

- Запустить код (шаг 5.) и проверить результат вывода (шаг 6.)

![Снимок экрана 2024-10-01 023112](https://github.com/user-attachments/assets/83deb8b2-e2e0-47df-99a2-a721854883cc)

## Задание 2
### Написать программу Hello World на C# с запуском на Unity.

- Зайти в приложение Unity Hub, нажать кнопку "New Project" (шаг 1.)

![Снимок экрана 2024-10-01 023806](https://github.com/user-attachments/assets/420957c8-7e89-429e-bf95-74eeb1791e01)

- Выбрать вариант с встроенным визуализатором "3D (Built-in Render Pipeline)" (шаг 2.), переименовать проект по своему выбору и нажать кнопку "Create Project" (шаг 3.)

![Снимок экрана 2024-10-01 023918](https://github.com/user-attachments/assets/3fcbc606-094c-4f10-909e-3a0aaf2ff88d)

- Открыть проект и внутри приложения в папке "Assets" создать папку "Scripts", а в ней создать файл "C# Script" с любым именем (шаг 4.)

![Снимок экрана 2024-10-01 024341](https://github.com/user-attachments/assets/137038c2-3f19-4bb7-99b6-0118acc35989)

- Открыть созданный файл и в коде изменить метод "Start":

```cs

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NewBehaviourScript : MonoBehaviour
{
    // В этот метод
    void Start()
    {
        print("Hello World!"); //Вписать команду "Print" со строкой "Hello World!"
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}

```
- Сохранив файл создать на сцене "SampleScene" 3D объект - куб (шаг 5.)

![Снимок экрана 2024-10-01 025847](https://github.com/user-attachments/assets/799483f4-b2d0-454a-a1ac-5b493f5ee056)

- Создав куб перетащить на него наш C# скрипт (шаг 6.) и запустить проект.

![Снимок экрана 2024-10-01 025801](https://github.com/user-attachments/assets/f619c7a5-4d8a-4e51-822b-7345b4adcc98)

- Убедиться, что в консоли Unity выдаёт нам желаемый результат.

![Снимок экрана 2024-10-01 025751](https://github.com/user-attachments/assets/4e263a2a-da01-46e6-8c5c-ddb68e3d3d78)


## Задание 3
### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.

- Перечисленные в этом туториале действия могут быть выполнены запуском на исполнение скрипт-файла, доступного [в репозитории](https://github.com/Den1sovDm1triy/hfss-scripting/blob/main/ScreatingSphereInAEDT.py).
- Для запуска скрипт-файла откройте Ansys Electronics Desktop. Перейдите во вкладку [Automation] - [Run Script] - [Выберите файл с именем ScreatingSphereInAEDT.py из репозитория].

```py

import ScriptEnv
ScriptEnv.Initialize("Ansoft.ElectronicsDesktop")
oDesktop.RestoreWindow()
oProject = oDesktop.NewProject()
oProject.Rename("C:/Users/denisov.dv/Documents/Ansoft/SphereDIffraction.aedt", True)
oProject.InsertDesign("HFSS", "HFSSDesign1", "HFSS Terminal Network", "")
oDesign = oProject.SetActiveDesign("HFSSDesign1")
oEditor = oDesign.SetActiveEditor("3D Modeler")
oEditor.CreateSphere(
	[
		"NAME:SphereParameters",
		"XCenter:="		, "0mm",
		"YCenter:="		, "0mm",
		"ZCenter:="		, "0mm",
		"Radius:="		, "1.0770329614269mm"
	], 
)

```

## Выводы

Абзац умных слов о том, что было сделано и что было узнано.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
