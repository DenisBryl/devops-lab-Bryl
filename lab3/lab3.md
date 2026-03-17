### Создание конфигурации Prometheus

1. Создал файл prometheus/prometheus.yml

![Alt text](image.png)

2. Создал тома и нетворк в докере

![Alt text](image-1.png)

### Запуск Node Exporter
3. Запустил контейнер Node Exporter для сбора системных метрик

![Alt text](image-3.png)

4. Проверил работу

![Alt text](image-4.png)
![Alt text](image-5.png)

### Запуск Prometheus

5. Вышел на папку выше в консоли, убедился, что нахожусь над уровнем папки prometheus. Запустил контейнер Prometheus

![Alt text](image-6.png)

6. Проверил работу

![Alt text](image-7.png)

### Запуск Grafana

7. Запустил контейнер Grafana

![Alt text](image-8.png)

### Настройка Grafana

8. Вошел в Grafana

![Alt text](image-9.png)

9. Добавил источник данных Prometheus

![Alt text](image-11.png)
![Alt text](image-10.png)

10. Создал дашборд

![Alt text](image-12.png)
![Alt text](image-13.png)

### Тестирование системы

11. Проверил все контейнеры системы

![Alt text](image-14.png)

12. Открыл Prometheus и убедился, что метрики собираются

![Alt text](image-17.png)

13. Открыл Grafana и проверил отображение графиков

![Alt text](image-16.png)

14. Создал несколько графиков для разных метрик

![Alt text](image-15.png)