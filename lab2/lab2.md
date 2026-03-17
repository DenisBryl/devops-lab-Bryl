## Подготовка проекта

1. Скопировал файлы из первой лабораторной в новый репозиторий
![Alt text](images/image.png)

2. Вошел в аккаунт Docker Hub
![Alt text](images/image-1.png)

3. Создал новый репозиторий на Docker Hub для моего образа
![Alt text](images/image-2.png)

### Настройка GitHub Actions

4. Создал папку .github/workflows/ в корне проекта
![Alt text](images/image-3.png)

5. Создал файл docker-build.yml с пайплайном
![Alt text](images/image-4.png)

### Настройка секретов

6. Получил access-токен в Docker Hub
![Alt text](images/image-6.png)

7. В настройках GitHub репозитория добавил секреты
![Alt text](images/image-5.png)

### Тестирование пайплайна

8. Запушил в репозиторий для проверки работы пайплайна
![Alt text](images/image-8.png)

9. Созданный пайплайн в Github Actions:
![Alt text](images/image-7.png)

10. Все этапы пайплайна:
![Alt text](images/image-9.png)

11. Созданный образ в Docker Hub:
![Alt text](images/image-10.png)