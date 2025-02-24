# Aula Web Server

Este é um projeto de servidor web simples desenvolvido para a disciplina de Programação Avançada para Web na Universidade Vila Velha.

## Descrição

Este projeto implementa um servidor HTTP básico em Python que responde a diferentes rotas com mensagens HTML. O servidor é configurado para rodar na porta especificada pela variável de ambiente `PORT` ou, se não especificada, na porta 3001.

## Estrutura do Projeto

- `index.html`: Página HTML que exibe a porta em que o servidor está rodando.
- `main.py`: Script principal que define as rotas e inicia o servidor.
- `my_webserver.py`: Implementação da classe `MyWebServer` que configura e inicia o servidor HTTP.

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório.
3. Navegue até o diretório do projeto.
4. Execute o comando `python main.py` para iniciar o servidor.

## Exemplo de Uso

- Acesse `http://localhost:3001/` para ver a mensagem "Olá Mundo!".
- Acesse `http://localhost:3001/pagina1` para ver a mensagem "Estou numa página nova!".
- Acesse `http://localhost:3001/index` para ver a página HTML `index.html` com a porta do servidor.

## Autor

- Gustavo Schade

## Professor

- Wanderson Muniz

## Universidade

- Universidade Vila Velha
