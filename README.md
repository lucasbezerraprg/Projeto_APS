Este projeto é um sistema de avaliação e catálogo de filmes, similar ao IMDB, onde os usuários podem se cadastrar, deixar avaliações, ler críticas e visualizar a avaliação geral de cada filme.

## Funcionalidades

- **Registro de Usuário**: Permite que novos usuários se registrem usando um email e uma senha.
- **Login e Autenticação**: Usuários registrados podem fazer login com suas credenciais.
- **Avaliação de Filmes**: Usuários podem avaliar filmes com uma nota de 1 a 10 estrelas.
- **Escrever Críticas**: Usuários podem escrever críticas detalhadas sobre os filmes.
- **Adição e Edição de Filmes**: Usuários podem adicionar novos filmes ao catálogo e editar informações de filmes existentes.
- **Visualização de Avaliações**: Os usuários podem ver as avaliações e críticas de outros usuários.

## Requisitos

- **XAMPP**: Inclui Apache e MySQL.
- **PHP**: Para o backend.
- **Navegador Web**: Para acessar a interface do site.

## Instalação

### Passo 1: Baixar e Instalar o XAMPP

1. **Download**: Baixe o XAMPP do site oficial: [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).
2. **Instalação**: Siga as instruções de instalação, selecionando os componentes Apache e MySQL.

### Passo 2: Configurar o Servidor Web (Apache)

1. **Localização dos Arquivos**: Coloque os arquivos do projeto na pasta `htdocs` do XAMPP, geralmente localizada em `C:\xampp\htdocs`.
2. **Configuração do Apache**:
- Abra o arquivo `httpd.conf` (geralmente encontrado em `C:\xampp\apache\conf`).
- Certifique-se de que as portas 80 (HTTP) e 443 (HTTPS) estão configuradas corretamente.
- Para habilitar HTTPS, você pode seguir um guia como [este](https://httpd.apache.org/docs/2.4/ssl/ssl_howto.html).

### Passo 3: Configurar o Banco de Dados (MySQL)

1. **Iniciar MySQL**: Abra o painel de controle do XAMPP e inicie o MySQL.
2. **phpMyAdmin**: Acesse o phpMyAdmin (geralmente em `http://localhost/phpmyadmin`).
3. **Criar Banco de Dados**:
- Crie um banco de dados chamado `projetofinal`.
- Importe o arquivo SQL fornecido (`projetofinal.sql`) para criar as tabelas necessárias (`users`, `movies`, `reviews`).

