# tecweb-atividade-2022.1

Neste repositório você pode encontrar dois projetos.

Para realizar essa atividade, recomendo que dê um fork neste repositório.

1.  notes_backend

    O projeto 'notes_backend' possui um projeto Django REST com algumas funcionalidades já implementadas em sala de aula.

    Para executar o projeto é necessário seguir os passos a seguir.

    - Crie um ambinente virtual.

          python -m venv env

    - Ative o ambiente virtual.
    - Instale as dependências do projeto. Dentro da pasta notes_backend, rode o comando a seguir.

          pip install -r requirements.txt
    - Execute o comando:

          python manage.py migrate


2. notes_frontend

    O projeto notes_frontend possui um projeto React com algumas funcionalidades já implementadas em sala de aula.

    Para executar o projeto é necessário seguir os passos a seguir.

    - Instale as dependência. Para isso, dentro da pasta notes_frontend, rode o comando a seguir:

          npm i


# Atividade

No projeto notes_backend, já existe a funcionalidade de deletar uma nota.
Agora a sua tarefa é utilizar essa funcionalidade no notes_frontend.

1. Para isso, implemente um botão/link que utilize a funcionalidade de deletar a nota fazendo uma requisição para o notes_backend.
2. Adicione o estilo css feito no Desafio CSS no projeto notes_frontend
