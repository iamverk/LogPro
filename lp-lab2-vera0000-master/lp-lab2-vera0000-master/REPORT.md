#№ Отчет по лабораторной работе №2
## по курсу "Логическое программирование"

## Решение логических задач

### студент: Макаренкова В.М.

## Результат проверки

| Преподаватель     | Дата         |  Оценка       |
|-------------------|--------------|---------------|
| Сошников Д.В. |              |               |
| Левинская М.А.|     23.12    |      3        |

> *Комментарии проверяющих (обратите внимание, что более подробные комментарии возможны непосредственно в репозитории по тексту программы)*


## Введение

Cуществует 2 основных подхода к решению логических задач: метод порождения и проверок и метод ветвей и границ. Суть первого метода состоит в том, что некоторый предикат генерирует множество исходных данных, которые затем проверяются другими предикатами на предмет соответствия условию задачи. В случае неуспеха происходит возврат и рассмотрение следующего решения, в случае успеха полученное решение возвращается пользователю или используется дальше. В методе ветвей и границ значительные части возможных решений отсекаются на раннем этапе выполнения или вообще не генерируются. 

Пролог удобен для решения логических задач, так как он дает возможность рассмотрения большого количества вариантов решения задачи и выбора из них подходящих.
## Задание

В педагогическом институте Аркадьева, Бабанова, Корсакова, Дашков, Ильин и Флеров преподают географию, английский язык, французский язык, немецкий язык, историю и математику. Преподаватель немецкого языка и преподаватель математики в студенческие годы занимались художественной гимнастикой. Ильин старше Флерова, но стаж работы у него меньше, чем у преподавателя географии. Будучи студентками, Аркадьева и Бабанова учились вместе в одном университете. Все остальные окончили педагогический институт. Флеров отец преподавателя французского языка. Преподаватель английского языка самый старший из всех и по возрасту и по стажу. Он работает в этом институте с тех пор, как окончил его. Преподаватели математики и истории его бывшие студенты. Аркадьева старше преподавателя немецкого языка. Кто какой предмет преподает?

## Принцип решения

С помощью встроенных предикатов member и not вводим исходные данные и работаем с высказываниями задачи, например, высказываение "Преподаватель немецкого языка и преподаватель математики в студенческие годы занимались художественной гимнастикой" будет записываться в виде предикатов так:
```prolog
 %немецкий и математика - женщины
    member(person(_, female, math, _), Result),
    member(person(_, female, deutsch, _), Result),
    ...
```
Все условия и выводы из высказываний помещены в предикат `tutors(Result)`, который и делает все вычисления, после чего выводит ответ задачи:
```prolog
?- tutors(Res).
Res = [person(korsakova, female, math, ped), person(flerov, man, geography, ped), person(arcadeva, female, french, inst), person(babanova, female, deutsch, inst), person(ilin, man, history, ped), person(dashkov, man, english, ped)] 
```

## Выводы

Работа над данным заданием показала одно из преимуществ пролога над императивными языками : можно просто ввести все условия задачи, а пролог за тебя все может просчитать и на на основе этого сделать выводы! В императивном языке понадобилось бы множество циклов и разветвлений, так же, как и если решать данную задачу в письменном виде. Prolog - очень удобное средство решения различных логических задач.




