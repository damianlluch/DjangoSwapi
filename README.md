python 3.6
Click en la imagen para ver un video interactuando con la web

$ git clone https://github.com/damianlluch/DjangoSwapi

$ pip install pipenv

$ cd Django-Swapi

$ pipenv shell

$ pipenv install

$ python manage.py migrate

$ python manage.py runserver

http://127.0.0.1:8000

*aunque pipenv sea el instalador de paquetes recomendado por Django, puede dar problemas, por eso
podemos contar con la alternativa de usar venv

----

Super User:
  name: damian password:1234

![Star Wars](https://i.ytimg.com/vi/usO_6-RuCrg/maxresdefault.jpg)


instalar python 3.6

si se rompe pip 

$ pip install --user --upgrade pip

dio algunos problemas el pipenv install con whitenoise asi que hice un pip install whitenoise
tambien instale las dependencias quitando el lock de versiones con 

pipenv install --skip-lock <whatever>
