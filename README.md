This device is based on the ESP8266 controller.
It is a fake access point on an open network and shows the client an authorization page
using a password, email address, and phone number. The entered authorization data is saved to the SD card
and displayed on the display.
************************************************************************************************************
Это устройство на основе контроллера ESP8266. Оно представляет собой фейковую точку доступа открытой сети 
и показывающую клиенту страницу авторизации с помощью пароля, адреса электронной почты и номера телефона. 
Введенные данные авторизации сохраняются на карту SD и отображаются на дисплее. 
************************************************************************************************************

ATTENTION!
This device has been developed and can only be used for educational purposes and information security research purposes. 
You must warn people that the device is fake and the data they enter must not be real!
You are responsible for the misuse of this project!
************************************************************************************************************
ВНИМАНИЕ! Данное устройство разработано и может быть использовано исключительно в образовательных целях и целях исследования
безопасности информации. Вы обязаны предупредить людей о том, что устройство является фейковым и вводимые ими данные
не должны быть реальными! Вы несете ответственность за неправомерное использование данного проекта!

_____________________________________________________________________________________________________________
pin connection

ESP         SD          OLED        BUZER
       
 D5         SCK
 D6         MISO
 D7         MOSI
 TX         CS
 D8                                    +
 D2                      SDA
 D1                      SCK
 _____________________________________________________________________________________________________________
