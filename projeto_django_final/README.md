# Cadastro de Clientes

Este projeto é uma aplicação Django moderna para gerenciar o cadastro de clientes e usuários, com layout responsivo, visual agradável e experiência de uso aprimorada.

## Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Acesse a pasta do projeto e aplique as migrações:
   ```bash
   cd cadastro_clientes
   python manage.py migrate
   ```
4. Inicie o servidor:
   ```bash
   python manage.py runserver
   ```
5. Acesse `http://127.0.0.1:8000/` no navegador.

## Estrutura do Projeto

- `clientes/` — Funcionalidades de clientes (CRUD, busca, templates)
- `usuarios/` — Cadastro, login, perfil, gerenciamento e templates de usuários
- `static/style.css` — CSS global com paleta, responsividade e layout moderno
- `templates/` — HTMLs minimalistas, responsivos e com visual profissional

## Observações

- O projeto utiliza Django 5+
- Todas as rotas de clientes exigem autenticação
- O layout é totalmente responsivo e acessível
- O avatar do usuário é exibido no cabeçalho após login
- O menu é centralizado e adaptável a qualquer tela
- O modal "Sobre Mim" está disponível em todas as páginas, com leitura confortável
- Dependências atualizadas no requirements.txt

---


