# Criando um Crud em djangorestframework

1. criar uma pasta

- 1.2 HABILITAR SCRIPTS NO POWERSHELL
  `Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser`

2. criar um ambiente virtual
   `python -m venv venv`

3. ativar a venv
   `.\venv\Scripts\activate`

- comando para unix:`source venv/bin/activate`

4. instalar pacote django na venv
   `pip install djangorestframework`

5. django-admin startproject nome_do_projeto .

6. ir no setting.py e adicionar 'rest_framework' em INSTALLED_APPS

7. criar uma pasta de app
   `python manage.py startapp nome_do_app`

8. ir no setting.py e adicionar 'nome_do_app' em INSTALLED_APPS.

9. abrir o arquivo model na pasta nome_do_app
   criar uma classe de acordo com a interação que sera feita com o banco.

10. criar arquivo serializers.py
    e estabelescer o conteudo que sera convertido.

11. entar no arquivo views.py e criar uma classe com viewsets.
    as viewsets sao umas funcionalidades especificas do framework
    setam uma visualização.

12. ir na raiz do projeto e fazer um include no arquivo de url. (o include são das urls do app).

13. Criar um arquivo urls.py na pasta app e setar uma rota. (essa rota e da view que vou criar)

14. fazer migrações
    `python manage.py makemigrations nome_do_app`

15. executar as migrações
    `python manage.py migrate nome_do_app`

16. rodar o servidor.
    `python manage.py runserver`



**se der erro, [StackOverflow](https://stackoverflow.com/) lhe aguarda =)**
