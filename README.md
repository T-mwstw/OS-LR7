# OS-LR7

Разработать программу с тремя дополнительными нитями (threads)
относительно главной нити. Каждая из нитей должна использовать общие для
всех нитей данные, представленные массивом символов, в которых записаны
20 первых букв латинского алфавита. Каждая из этих нитей на своем k-м шаге
выводит со своей случайной задержкой на место «своего» столбца экрана k-ю
букву из указанного массива латинских букв, причем с числом повторений,
равному условному номеру нити, умноженному на два. Каждая из используемых нитей должен осуществлять вывод своим цветом, отличным от остальных
нитей. На 6-м шаге главная нить делает попытку отмены первой из дополнительных нитей, а на 11-м делает попытку отмены третьей из дополнительных
нитей. Первая и третья дополнительная нити в начале своей работы запрещают
свою отмену. Третья нить на 13 шаге разрешает отмену, но в отложенном режиме. Точку отмены эта нить устанавливает между 16 и 17-м шагом своей работы. Все управляющие указания должны отображаться сообщениями без прокрутки экрана (в фиксированные позиции экрана)
