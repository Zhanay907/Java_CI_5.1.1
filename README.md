# Cчётчик INSTRUCTION

Наименьшая единица отсчета JaCoCo - это инструкции с одним байтовым кодом Java. 
Покрытие инструкций предоставляет информацию об объеме кода, который был выполнен или пропущен. 
Эта метрика полностью независима от исходного форматирования и всегда доступна, 
даже при отсутствии отладочной информации в файлах классов.


# Счетчик BRANCH

JaCoCo также вычисляет охват веток для всех if и switch отчетности.
Эта метрика подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных ветвей. 
Покрытие веток всегда доступно, даже при отсутствии отладочной информации в файлах классов. 

# Счетчик LINE

ля всех файлов классов, которые были скомпилированы с отладочной информацией, 
можно рассчитать информацию о покрытии для отдельных строк. 
Исходная строка считается выполненной, если была выполнена хотя бы одна инструкция, назначенная этой строке.
В связи с тем, что одна строка обычно компилируется в инструкции с несколькими байтами, 
выделение исходного кода показывает три разных состояния для каждой строки, содержащей исходный код:

- Нет покрытия: ни одна инструкция в строке не была выполнена (красный фон)
- Частичное покрытие: выполнена только часть инструкции в строке (желтый фон)
- Полное покрытие: все инструкции в строке выполнены (зеленый фон)