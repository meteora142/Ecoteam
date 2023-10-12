# Ecoteam

## Название проекта: 
* Design of eco-solvents using machine learning
  
### Ментор: 
* Валерия Одегова
  
### Состав команды:
* Лобутова Виктория, Троценко Данил, Какуркина Дарья, Галиуллин Динар, Хайбуллина Зульфия
  
### Описание репозитория:
- **README.md** - описание проекта
- **files** - папка для хранения файлов
    - Density.csv - начальный датасет
    - Final.csv - готовый датасет для обучения
    - model_stack.pkl - веса StackingRegressor
    - model_xtra.pkl - веса ExtraTreesRegressor
    - requirements.txt - используемые библиотеки
- **images** - папка для изображений
- **scripts** - папка для скриптов
    - EcoteamProject.ipynb - скрипт проекта

## ___Description:___ 
* Глубокие эвтектические растворы (ГЭР) представляют собой новый класс двухкомпонентных или трехкомпонентных смесей,  имеющих сложное водородное связывание, что является корневой причиной снижения точек плавления и физико-химических свойств, по сравнению с чистыми составляющими компонентов. В большинстве случаев ГЭР состоят из натуральных компонентов, таких как органические кислоты, спирты, сахары и кватернические аммониевые соли, поэтому они биоразлагаемы, их производство доступно и легко осуществимо, и эффективность извлечения сравнима с известными органическими растворителями. Однако существует проблема выбора системы из двух или более соединений, способных образовать смесь с оптимальными свойствами для конкретной задачи. Ученые в основном решают эту проблему, проводя большое количество экспериментов, но эти свойства также могут быть предсказаны с использованием машинного обучения.  
Поскольку исследования в различных направлениях положительно продемонстрировали потенциал ГЭР, необходимо переключить внимание с разрозненных специализированных приложений на развитие фундаментального понимания с целью создания предсказательных моделей. Это можно достичь через проведение экспериментов, тщательного сбора и публикации всех возможных и практических физико-химических свойств ГЭР, особенно для широко изученных соединений и компонентов ДЭР, а также анализа данных и применения вычислительных методов для выявления новых взаимосвязей или эмпирических закономерностей. После создания более простых предсказательных моделей исследования могут расшириться, решая инженерные задачи, но делать это без подходящих моделей неэффективно из-за большого количества неизвестных.

* ___Где применимы ГЭР?___ 
1. Химическая промышленность: ГЭР могут использоваться для экстракции и разделения химических соединений, а также в синтезе органических соединений.
2. Экология: Они могут использоваться для очистки сточных вод и удаления загрязняющих веществ.
3. Фармацевтика: ГЭР могут служить растворителями для извлечения активных ингредиентов из растений и других природных источников для производства лекарств.
4. Пищевая промышленность: Они могут применяться для извлечения ароматизаторов и вкусовых добавок из природных продуктов.
5. Энергетика: ГЭР могут использоваться в электрохимических процессах и для хранения энергии.

## Исходные данные проекта:
* Количество компонентов (двух- трехкомпонентная система);
* Тип растворителя:
* Наименование первого и второго компонентов, название третьего компонента (при его наличии);
* Молярная доля компонентов, их температура, при которой проводилось исследование, показатели плотности;
* Источники исходных данных (DOI)
