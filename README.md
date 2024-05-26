# Втора лабораториска вежба по Софтверско инженерство
## Ана Доказа 223056

### Control Flow Graph

<img width="701" alt="image" src="https://github.com/anadokaza/SI_2024_lab2_223056/assets/120387980/00920af5-9c5d-4d1a-b90c-5feb7d1b7c93">

### Цикломатска комплексност
Цикломатската комплексност на овој код е 10, истото го добив бидејќи има 9 предикатни јазли и + 1 од формулата.

### Тест случаи според критериумот Every statement: if (item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0')
-T && T && T : item.price = 5000; item.discount = 0.25; item.barcode = "0123" 
-T && T && F  : item.price = 5000; item.discount = 0.25; item.barcode = "1234" 
-T && F && X : item.price = 5000; item.discount = -1; item.barcode = "1234" 
-F && X && X : item.price = 100; item.discount = -1; item.barcode = "1234"

### Тест случаи според критериумот Every path
<img width="487" alt="image" src="https://github.com/anadokaza/SI_2024_lab2_223056/assets/120387980/99dd7a70-fd84-4347-aa5e-133abe6b60e0">


### Објаснување на напишаните unit tests
При имплеменетација и пишување на unit testing применував слични тестови како и во претходното барање за every path. Во главно, ги користев фунциите assert true & false.


