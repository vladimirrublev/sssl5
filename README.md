# Практическая работа №5 - Threat Hunting
## Rublev Vladimir Sergeevich
**Выполнил студент группы ББМО-02-23**

Вся информация по установке и отладке была взята из практической работы №3

**В работе были использованы 2 Виртуальнае машины на базе операционной системы Ubuntu v22.04.4 под сервер и агент XDR Wazuh**

Демонстрация подключения агента к серверу:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/1.jpeg)

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/2.jpg)

Разворначиваем IDS Суриката:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/3.jpg)

Внесение изменений для дальнейшего сбора логов suricata в конфиг xdr wazuh:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/4%201.png)

 Apache:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/5%201.png)

# Сканер уязвимостей NIKTO

Установка сканер уязвимостей Nikto:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/5.jpg)

Устанавливает интерпретатор Perl:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/6.png)

Запуск Nikto:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/7.png)

События от сурикаты в SIEM:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/8.png)

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/9.png)

Полная установка Yara:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/10.png)

Конфигурационный файл активного реагирования под утилиту yara:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/11.png)

Просмотр сработавших правил в истории логов:

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/12.png)

![image](https://github.com/vladimirrublev/sssl5/blob/main/screenshot/12%201.png)
