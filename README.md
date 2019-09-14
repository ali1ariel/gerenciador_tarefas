# Gerenciador de tarefas

    Um gerenciador de tarefas que foi a base de um minicurso ofertado pela 'TreinaWeb' como 'Semana Python&Django'. É um sistema onde o usuário logado pode colocar tarefas ou qualquer anotação que quiser.

    a mesma aplicação se encontra online em: 

    https://semana-python-djangoali1ariel.herokuapp.com/

## Iniciando...

### Pré-requisitos
```
 Python 3.7.4
 MySQL
```
Requisitos do aplicativo:
Na pasta principal digite o comando a seguir para instalar os requisitos da aplicação.
```
pip install -r requirements.txt
```
### Instalando
 Para utilizar o banco de dados é necessário colocar as credenciais **settings.py**, na sessão **databases** colocar o user e a senha conforme confirado no seu MYSQL.

 Em seguida, no terminal, utilize o comando:
 ``` 
    python manage.py makemigrations
 ```
 E depois:
 ``` 
    python manage.py migrate
 ```

 Estando as configurações corretas, a aplicação estará pronta para ser levantada. O comando é:

 ```
    python manage.py runserver
 ```
 E pronto, sua aplicação já estará em pé localmente. 


## Deployment

 O projeto está pré-moldado para ser implantado pelo heroku.


## Built With

* [Python](https://www.python.org/) - A linguagem
* [DJango](https://www.djangoproject.com/) - O site do framework
* [MYSQL](https://www.mysql.com/) - O Banco de dados local


## Agradecimentos

Um agradecimento especial ao professor Fagner Pinheiro da TreinaWeb por ter planejado e ensinado com maestria a desenvolver toda essa base da aplicação. O projeto principal pode ser encontrado em [TreinaWeb - Semana Python&DJango](https://github.com/treinaweb/treinaweb-semana-python-django).
