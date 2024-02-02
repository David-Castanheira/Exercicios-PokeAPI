# Sobre o projeto
Projeto desenvolvido durante o 3° semestre do curso de ADS na Faculdade Impacta, referente à disciplina de API's e microsserviços que se trata da resolução de exercícios, por meio do consumo da API da PokeAPI. Ainda está em processo de melhora e inclusão de novas funcionalidades e finalização do restante dos exercícios.

## Objetivo 
Exercícios elaborados pelo próprio professor da disciplina referentes ao consumo da PokeAPI. 

### Ambiente virtual
Durante este, é recomendado a criação de um ambiente virtual, o que garante o desenvolvimento estável e consistente sem interferir em outros projetos ou no ambiente global, neste caso, do Python. **É importante que esse passo seja feito antes mesmo da instalação do Flask e das bibliotecas extras! Para que o mesmo seja usado no próprio ambiente** Para criá-lo e ativá-lo, execute os seguintes comandos:

```
$ python -m venv nome_ambiente

$ venv\Scripts\Activate
```

## Ferramentas 
A linguagem back-end responsável pelas regras de negócio e lógica da aplicação em questão é o **[Python](https://docs.python.org/pt-br/3/tutorial/)**:
* O framework web utilizado é **[Flask](https://flask.palletsprojects.com/en/3.0.x/)** que facilita o desenvolvimento de aplicações web de alto desempenho, escaláveis e seguras. Flask é baseado no padrão WSGI (Web Server Gateway Interface), que define uma interface comum entre servidores web e aplicações web. Esse framework também oferece diversos recursos prontos para uso, como autenticação, roteamento, ORM, formulários, testes unitários, entre outros;
* Requests é uma biblioteca Python que permite fazer requisições HTTP de forma simples e elegante. Com ela, é possível consumir API's de diversos serviços Web, enviando e recebendo dados em diferentes formatos, como JSON, XML, HTML, etc. Requests é considerada uma das melhores bibliotecas em Python para trabalhar com HTTP.
Para instalá-los, basta seguir os passos abaixo com o uso de um pacote de instalação chamado 'pip' no terminal do Windows:

Rode o comando de instalação do Flask no terminal:
```
$ pip install Flask 
```
Feito isso, execute o comando abaixo para a instalação da biblioteca 'requests':
```
$ pip install requests 
```

Rode sua aplicação na IDE utilizada para o desenvolvimento e, após isso, acesse "[http://localhost:5000]"

