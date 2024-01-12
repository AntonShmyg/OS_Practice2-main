# Запуск
В __Visual Studio__ запускать решение без дебаггина (__Ctrl+F5__).  

## Задание
Найдите с помощью алгоритма полного перебора пятибуквенные пароли, соответствующие следующим хэш-значенияи SHA-256 и выведите их на экран:

1. 1115dd800feaacefdf481f1f9070374a2a81e27880f187396db67958b207cbad
2. 3a7bd3e2360a3d29eea436fcfb7e44c735d117c42d1c1835420b6b9942dd4f1b
3. 74e1bb62f8dabb8125a58852b63bdf6eaef667cb56ac7f7cdba6d7305c50a22f

Хэш значения могут считываться из файла или непосредственно с консоли (формы для ввода хэш-значения)

Ваша программа должна перебрать все возможные пароли, состоящие только из пяти строчных букв английского алфавита ASCII.

Программа должна иметь возможность запуска перебора в однопоточном режиме или в многопоточном режиме (Количество потоков может задаваться пользователем). Для кажого режима необходимо выводить затраченное время на подбор.

[Методичка](https://hackmd.io/@0x41/OS_Lab_2)