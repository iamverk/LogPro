# Реферат
## по курсу "Логическое программирование"

### студент: Макаренкова В.М.

## Логическое программирование при создании современных информационных систем

## Результат проверки

| Преподаватель     | Дата         |  Оценка       |
|-------------------|--------------|---------------|
| Сошников Д.В. |              |               |
| Левинская М.А.|              |               |

> *Комментарии проверяющих (обратите внимание, что более подробные комментарии возможны непосредственно в репозитории по тексту программы)*

### Введение
В век информационных технологий нам сложно представить свою жизнь без огромного количества информации, которая всюду окружает нас. С приходом в мир такого объема данных возникает вопрос: как обрабатывать и систематизировать огромную «кучу» информации? Для ответа на этот вопрос были созданы многочисленные информационные системы, они постоянно развиваются и совершенствуются. В то же время для современных информационных систем требуется мощная программная поддержка, которая позволит обрабатывать большие потоки данных и преобразовывать информацию в понятный и удобный для человека вид. Открытие логического программирования и языков логического программирования дало новый виток в развитии современных информационных систем, который значительно упростил жизнь людям во многих областях знаний.

### Немного о логическом программировании
Логическое программирование – парадигма программирования, основанная на теории и аппарате математической логики с использованием математических принципов и резолюций. 
Центральным понятием в логическом программировании является отношение. Программа представляет собой совокупность определений отношений между объектами (в терминах условий или ограничений) и цели (запроса). Процесс выполнения программы трактуется как процесс общей значимости логической формулы, построенной из программы по правилам, установленным семантикой используемого языка. Результат вычисления является побочным продуктом этого процесса. В реляционном программировании нужно только специфицировать факты, на которых алгоритм основывается, а не определять последовательность шагов, которые требуется выполнить. Это свидетельствует о декларативности языка логического программирования. Она метко выражена в формуле Р. Ковальского: «алгоритм = логика + управление».
Самым распространенным языком логического программирования, пожалуй, является Prolog, он насчитывает сотни тысяч пользователей. Также существуют такие языки, как Planner («первопроходец» логического программирования) и произошедшие от него QA-4, Popler, Conniver и QLISP. От языка Prolog также произошли Mercury, Visual Prolog, Oz и Fril.

### Сферы применения логического программирования.
Логические языки программирования способны решать не только задачи из повседневных областей применения, но и еще задачи интеллектуальных систем, таких как, например, искусственный интеллект. 

• реляционные базы данных

Информация становится ценностью для человека только в том случае, если она обработана, автоматизирована и представлена в нужном для него виде, для такого вида представления информации используются базы данных реляционного типа. Поскольку модель реляционной базы данных – хорошо разработанный логический формализм, то с представлением базы данных на, например, Prolog, не составит большого труда.

• естественный язык

Первоначально Пролог предназначался для анализа естественного языка и его обработки. Создатель Пролога разработал систему грамматического разбора естественного языка нисходящим методом. такой формализм впоследствии получил название грамматики определенных предложений.

• представление знаний

Все основные концепции, связанные с применение искусственного интеллекта или формализмом представления знаний, включая семантические сети, фреймы, правила продукций и объектно ориентированное программирование, можно выразить при помощи логики и, следовательно, средств логического программирования.

• экспертные системы

К так называемым "экспертным системам" относятся медицина, экономика, география и прочие разнообразные сферы деятельности человека
 

### Информационные системы
Информационные системы уже давно прочно связаны с нашей жизнью. Они представляют собой системы для хранения, поиска и обработки информации, требующие соответствующих ресурсов, как человеческих, так технических и финансовых, для обеспечения и распространения информации, нужной именно в это время именно этим людям. При этом потоки информации складываются из разных предметных областей, но на выходе человек получает информационный продукт как результат функционирования информационной системы (документы, базы данных, информационные услуги и так далее).

### Свойства информационных систем:
•	любая ИС может быть подвергнута анализу, построена и управляема на основе общих принципов построения сложных систем

•	при построении ИС необходимо использовать системный подход

•	ИС является динамичной и развивающейся системой

•	ИС следует воспринимать как систему обработки информации, состоящую из компьютерных и телекоммуникационных устройств, реализованную на базе современных технологий

•	выходной продукцией ИС является информация, на основе которой принимаются решения или производятся автоматическое выполнение рутинных операций

•	участие человека зависит от сложности системы, типов и наборов данных, степени формализации решаемых задач.

### Этапы развития информационных систем
•	Первые ИС появились в 50-х гг. В эти годы они были предназначены для обработки счетов и расчета зарплаты, а реализовывались на электромеханических бухгалтерских счетных машинах. Это приводило к некоторому сокращению затрат и времени на подготовку бумажных документов.

•	60-е гг. знаменуются изменением отношения к ИС. Информация, полученная из них, стала применяться для периодической отчетности по многим параметрам. Для этого организациям требовалось компьютерное оборудование широкого назначения, способное обслуживать множество функций, а не только обрабатывать счета и считать з/пл.

•	В 70-х - начале 80-х ИС начинают широко использоваться в качестве средства управленческого контроля, поддерживающего и ускоряющего процесс принятия решений.

•	К концу 80-х гг. концепция использования ИС вновь изменяется. Они становятся стратегическим источником информации и используются на всех уровнях организации любого профиля. ИС этого периода, предоставляя вовремя нужную информацию, помогают организации достичь успеха в своей деятельности, создавать новые товары и услуги, находить новые рынки сбыта, обеспечивать себе достойных партнеров, организовывать выпуск продукции по низкой цене и многое другое.

Новая волна и значительный эффект от применения технологии искусственного интеллекта получены в результате разработки и применения интеллектуальных информационных систем, явившихся синтезом экспертных и информационных систем. Создание ИИС стало естественным продолжением широкого применения информационных систем классического типа. Системы реинжиниринга бизнес процессов показали возможность упорядочения информационных потоков и совершенствования структуры предприятия при внедрении информационных технологий, помогли освоить методологию разработки информационной модели предприятия. Интегрированные ИС предприятия обеспечивают информационную поддержку всех производственных процессов и служб предприятия, включая проектирование, изготовление и сбыт продукции, финансово-экономический анализ, планирование, управление персоналом, маркетинг, сопровождение эксплуатации изделий, перспективное планирование. Внедрение информационных систем типа ЕRР (Еntеrрrisе Rеsоurcе Planing) увеличивает эффективность работы предприятия на 20-30%. В результате появились полностью компьютеризованные информационно-технологические связи
между корпорациями (системы В2В или бизнес-бизнес) и связи корпорации с клиентами (системы В2С или системы бизнес-клиент).
 


### Логическое программирование и проектирование современных информационных систем
С самого начала исследований в области моделирования процесса мышления (конец 40-х годов) выделились два до недавнего времени практически независимых направления:
*	логическое,
*	нейрокибернетическое.
Первое было основано на выявлении и применении в интеллектуальных системах различных логических и эмпирических приемов, которые применяет человек для решения каких-либо задач. В дальнейшем с появлением концепций «экспертных систем» (ЭС) (в начале 80-х годов) это направление вылилось в научно-технологическое направление информатики «инженерия знаний», занимающееся созданием т. н. «систем, основанных на знаниях» (Knowledge Based Systems). Именно с этим направлением обычно ассоциируется термин «искусственный интеллект» (ИИ)(Искусственный интеллект — свойство интеллектуальных систем выполнять творческие функции, которые традиционно считаются прерогативой человека; наука и технология создания интеллектуальных машин, особенно интеллектуальных компьютерных программ).
Так как информация была ценным ресурсом во все времена, не говоря уже о нашем постиндустриальном обществе, развитие информационных систем никогда не стояло на месте, поэтому было неизбежно появление такой парадигмы программирования, как Логическое программирование, позволяющее делать существующие информационные системы интеллектуальными.
Эти изменения стали возможными благодаря двум основным факторам: выделению в алгоритме программы некоторой универсальной части (логического вывода) и отделению ее от части, зависящей от предметной области (базы знаний); повышению уровня взаимодействия пользователя и компьютерной программы, т.е. появлению интеллектуального интерфейса в программах ИИ.
Основной особенностью Интеллектуальных систем является возможноть поиска информации в режиме продвинутого разговора на естественном языке. Для того чтобы пользователь мог эффективно взаимодействовать с системой, ее интерфейс должен выполнять две основные функции: давать советы и объяснения пользователю и управлять приобретением знаний.
Состоят ИИС, как правило, из механизма обеспечения связи между пользователем и другими компонентами системы, хранилища данных и средств их обработкиб хранилища знаний о проблемной области, таких как процедуры, эвристики, правила, средства обработки знаний и подсистемы обработки и решения задач.
ИИС предназначены для решения следующего ряда задач:

•	Интерпретация данных

•	Диагностика

•	Мониторинг

•	Проектирование

•	Прогнозирование

•	Обучение

Со всеми этими задачами языки Логического программирования справляются крайне удачно в силу своей специфики, позволяя получать необходимые результаты быстро и достаточно просто относительно других языков.
Особенности логического формализма высокого уровня могут привести к набору средств практической разработки программ, существенно более мощных, чем существующие в настоящее время. Примерами таких средств являются автоматический преобразователь программ, частично вычисляющая программа, программа типового вывода и алгоритмический отладчик.




### Заключение
Логические языки программирования играют очень важную роль сфере информационных технологий, они принимают активное участие в обработке данных, работе с базами данных, решении задач искуственного интеллекта и экспертных систем, и, хочется отметить, что очень хорошо справляются с поставленными задачами, помогая людям в таких разных сферах человеческой жизни. В наше время есть ещё большее пространство для развития в этой теме, поэтому, на мой взгляд, имеется несколько несовершенств применения логического программирования в ней: на сегодняшний день создано уже большое количество экспертных систем. С помощью них решается широкий круг задач, но исключительно в узкоспециализированных предметных областях. Как правило, эти области хорошо изучены и располагают более менее чёткими стратегиями принятия решений. Очень хотелось бы, чтобы логическое программирование все больше развивалось и прогрессировало, захватывая все новые и новые предметные области как мощный инструмент для решения большого числа задач, и одновременно с этим продолжало покорять новые вершины в уже существующих сферах.
Хочу отметить, что мне попалась очень интересная тема для эссе, в которой мне было любопытно разбираться, ибо она актуальна в наше время и вполне может быть связана с моей будущей работой, ведь логическое программирование - мощный инструмент или оружие(для кого как) для программиста, а знать, например, Пролог вместе с императивными языками - всегда большое преимущество.
### Литература
1. Малпас Дж. Реляционный язык Пролог и его применение
2. Википедия
3. https://habr.com/ru/

