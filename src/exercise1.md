## ТЕСТИРОВАНИЕ МЕТОДОМ СЕРОГО ЯЩИКА

### Проверка серого ящика (англ. grey box testing) – специальный метод тестирования программного обеспечения с неполным знанием его внутреннего устройства. Чтобы выполнить подобный вид тестов, не нужно иметь доступ к исходному коду ПО. ###

Все тесты создаются на базе простого знания алгоритмов, архитектуры и иных высокоуровневых характеристик поведения продукта.

### __Типы тестов серого ящика:__

- __Регрессионные проверки__ - это проверка ранее протестированной программы, позволяющая убедиться, что внесенные изменения не повлекли за собой появления дефектов в той части программы, которая не менялась.;
- __Матричные проверки__ -   устанавливают все используемые переменные в программе. Этот метод помогает идентифицировать и удалять переменные, которые не используются в программе, и, в свою очередь, помогает увеличить скорость работы программного обеспечения;;
- __Шаблонное тестирование__ - это форма тестирования, которая фокусируется на следовании определенному шаблону в каждом тесте, который выполняет организация.Команды тестирования разрабатывают эти тесты для каждой функции программного обеспечения, при этом каждый тест предоставляет компании последовательный уровень информации о том, как функционируют отдельные функции.При использовании тестирования по шаблону иногда приходится изменять шаблон со временем, чтобы убедиться, что вы оцениваете каждую из работающих систем, но как только у вас есть шаблон, который работает, избегайте отклонений, чтобы обеспечить большую последовательность в результатах.;
- __Проверка ПО с помощью ортогонального массива__ - это в первую очередь техника тестирования, ориентированная на «черный ящик», которая возникает, когда тестировщики используют значительное количество входных данных, которое слишком велико для исчерпывающего тестирования каждой отдельной системы в процессе.В этих случаях каждый отдельный фрагмент данных предоставляет свою собственную уникальную информацию из-за потенциального отсутствия корреляции между конкретными фрагментами информации. Это ортогональный аспект системы, когда уникальные фрагменты информации используются для получения максимального количества данных при минимальных затратах.


#### __Основные преимущества метода:__

Имеет некоторые особенности черного и белого ящика. Иными словами, тестировщик смотрит на объект проверки с позиции черного ящика, но проводит анализ системы с точным расчетом данных, которые ему предварительно известны (белый ящик).  
QA-специалист может создавать и применять более сложные тестовые сценарии.
Данная проверка позволяет программисту заручиться достаточным количеством времени для исправления багов.  
Программист взаимодействует с тестировщиком на начальном уровне, что позволяет сразу же убрать ненужные и избыточные тест-кейсы.  
  

#### Недостатки:

- Анализ программного кода ограничен, так как доступа к исходному коду у тестировщика нет.
- Нет времени тестировать все потоки ввода и вывода информации, так как это займет очень много времени.
- Возможна ситуация, когда тестировщики могут стать лишними (когда не только QA-специалист, но и программист проверяет свой код с помощью юнит-тестов).

### КРАТКИЕ ИТОГИ  
 Итак, тестирование методом серого ящика наиболее востребовано в ситуации, когда QA-инженеры могут получить полноценный доступ к проектной документации и у них есть достаточно времени на подготовку тест-кейсов со сценариями тестирования.

Максимальная польза от применения подобного вида тестирования наблюдается во время проверки веб-приложений, веб-сервисов, графического интерфейса пользователя, и при выполнении разнообразных функциональных тестов ПО, ориентированных на системную и клиентскую безопасность.
