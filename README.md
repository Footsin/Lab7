# Автор

Малюнкин Илья ФТ-210008

# Описание

Программа реализует шаблон проектирования MVC. Вся главная логика прописана в файле app.py.

- models.py — содержит класс figure и enum для названий фигур.
- controll.py — содержит всю бизнес логику работы с программой.
- views.py — обращается к файлу controllers.py, обрабатывает полученные данные и выводит их пользователю. 
- input.py — берет у пользователя данные из стандартного потока ввода с обработкой ошибок.

Программа выполняет три основные задачи:

- Сравнивает две клетки фигур на одинаковость цветов. 
- Выясняет, может ли одна фигура срубить другую за один ход.
- Если не может, то находит промежуточные клетки для сруба за два хода, если такие имеются.

# Требования к использованию

- **Python v3.10**, т.к. используется оператор match.
- Запуск должен происходить в **терминале** (не в cmd), для корректного отображения Unicode и цветного вывода.

Команда для запуска:

`python app.py`

# Примеры использования

- Тест 1
<img width="282" alt="1_1" src="https://user-images.githubusercontent.com/114622207/199430150-ab0231f1-f324-43aa-9ac1-319b70141e7a.png">
<img width="182" alt="1_2" src="https://user-images.githubusercontent.com/114622207/199430166-ccbdcbef-0696-44ba-8bc8-93b45e66c26d.png">
<img width="526" alt="1_3" src="https://user-images.githubusercontent.com/114622207/199430175-99120e61-2b5b-484b-a255-46c87085fe10.png">
- Тест 2
<img width="222" alt="2_1" src="https://user-images.githubusercontent.com/114622207/199430188-9c625201-193e-48f7-b304-9a02d7967f8f.png">
<img width="179" alt="2_2" src="https://user-images.githubusercontent.com/114622207/199430196-350ac3da-55da-487d-9f74-93a8dadfccb5.png">
<img width="590" alt="2_3" src="https://user-images.githubusercontent.com/114622207/199430204-82a09ef3-16ca-4b44-a448-1222b2b355e0.png">

- Тест 3
<img width="206" alt="3_1" src="https://user-images.githubusercontent.com/114622207/199430220-fe0dcb92-80cd-49dc-8b82-016f645e6d38.png">
<img width="180" alt="3_2" src="https://user-images.githubusercontent.com/114622207/199430241-2e6454b1-5232-4d3c-aee0-79ec77cd7d35.png">
<img width="435" alt="3_3" src="https://user-images.githubusercontent.com/114622207/199430252-c6431aac-76d4-4587-a569-c01a9172663f.png">
