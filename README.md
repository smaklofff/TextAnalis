# TextAnalis

Программа позволяет получить статистику по диалогу.  Параметры, которые программа учитывает:
* Количество сообщений  
* Наибольшее количество сообщений за 1 день  
* Количество вложений  
* Количество слов в диалоге

Подсчет воличества слов ведется по следующиму алгоритму:
1) Исходный текст сообщения разбивается на слова 
2) Каждое слово приводится к лемме 
3) Добавление слова в словарь 
4) Подсчет слов

Также в программе есть распределение задач на разные потоки, чтобы процесс получения статистики для нескольких человек не занимал много времени.
