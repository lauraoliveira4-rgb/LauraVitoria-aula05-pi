### Configuração do Ambiente de Desenvolvimento com Django

**1. Criação da pasta do projeto**

Inicialmente, foi criada uma pasta para organização do projeto no terminal:

mkdir meu_projeto
cd meu_projeto
<img width="528" height="210" alt="image" src="https://github.com/user-attachments/assets/e4073ae2-a93f-4bbc-ad68-4be23309f6dd" />

**2. Criação do ambiente virtual**

Para isolar as dependências do projeto, foi criado um ambiente virtual:

python -m venv venv

Em seguida, o ambiente foi ativado:

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate

<img width="597" height="263" alt="image" src="https://github.com/user-attachments/assets/4998dd92-73c6-4f9d-9554-b704c40bbf2f" />


**3. Instalação do Django**

Com o ambiente virtual ativo, foi realizada a instalação do framework Django:

pip install django

<img width="827" height="288" alt="image" src="https://github.com/user-attachments/assets/83bed101-5afd-4725-956b-02c50fe1b1cf" />


**4. Criação do projeto Django**

Após a instalação, foi criado o projeto inicial com o seguinte comando:

django-admin startproject meu_site .

Esse comando gera a estrutura básica de um projeto Django.

**5. Execução do servidor de desenvolvimento**

Para iniciar o servidor local, foi utilizado o comando:

python manage.py runserver

Após a execução, a aplicação ficou disponível no navegador por meio do endereço:

http://127.0.0.1:8000/

<img width="1095" height="386" alt="image" src="https://github.com/user-attachments/assets/9e4f2ad3-bc21-42ce-a116-ef363096d0da" />

**2. Criação do ambiente virtual**

Para isolar as dependências do projeto, foi criado um ambiente virtual:

python -m venv venv

Em seguida, o ambiente foi ativado:

Windows:

venv\Scripts\activate

Linux/Mac:

source venv/bin/activate

<img width="1043" height="503" alt="image" src="https://github.com/user-attachments/assets/ad62ec34-fd1c-4ae4-adb0-ca2033bfbe8d" />


**3. Instalação do Django**

Com o ambiente virtual ativo, foi realizada a instalação do framework Django:

pip install django

**4. Criação do projeto Django**

Após a instalação, foi criado o projeto inicial com o seguinte comando:

django-admin startproject meu_site .

Esse comando gera a estrutura básica de um projeto Django.

Imagem ilustrativa:

**5. Execução do servidor de desenvolvimento**

Para iniciar o servidor local, foi utilizado o comando:

python manage.py runserver

Após a execução, a aplicação ficou disponível no navegador por meio do endereço:

http://127.0.0.1:8000/
Professora essas partes que estão sem imagem não rodaram no meu pc, infelizmente ;(

