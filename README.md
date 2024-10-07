Установка Flask
Установить Flask легко и просто. С менеджером пакетов pip  нужно сделать только:

pip install flask

Когда вы закончите установку Flask, создайте папку   FlaskApp. Перейдите в папку FlaskApp и создайте файл с именем app.py. Импортируйте модуль flask и создайте приложение с помощью Flask, как показано ниже:

from flask import Flask
app = Flask(__name__)

Теперь определим основной путь / и соответствующий ему обработчик запросов:

@app.route("/")
def main():
    return "Welcome!"

Затем проверьте, является ли исполняемый файл главной программой и запустите приложение:

if __name__ == "__main__":
    app.run()


Сохраните изменения и выполните app.py:

python app.py

Укажите браузеру на http://localhost:5000/ и у вас должно появиться приветственное сообщение.

Создание домашней страницы
Во-первых, при запуске приложения мы должны показать домашнюю страницу с последними элементами списка дел, добавленными пользователями. Итак, добавим нашу домашнюю страницу в папку приложения.

Flask ищет файлы шаблонов внутри папки templates. Перейдите в папку PythonApp и создайте папку под названием templates. Внутри templates создайте файл index.html. Откройте index.html и пропишите следующий HTML:

https://code.tutsplus.com/ru/creating-a-web-app-from-scratch-using-python-flask-and-mysql--cms-22972t

https://proglib.io/p/django-s-nulya-chast-1-pishem-mnogopolzovatelskiy-blog-dlya-kluba-lyubiteley-zadach-python-2022-06-06

front 
https://github.com/bedimcode/responsive-portfolio-website-Alexa.git
