Настройка виртуального окружения
1. Установка virtualenv 
>pip install virtualenv
2. Создание виртуального окружения
> virtualenv PRG1
PRG1 в данном случае – это имя окружения.
3. Активация виртуального окружения
Для активации виртуального окружения воспользуйтесь командой (для Linux):

> source PRG1/bin/activate
для Windows команда будет выглядеть так:

> PRG1\Scripts\activate.bat


установить зависимости из requirements.txt
-pip install -r requirements.txt

Создать requirements.txt
pip freeze > requirements.txt
