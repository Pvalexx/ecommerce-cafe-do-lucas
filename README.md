# 🛒 E-commerce para o Café do Lucas ☕

Descrição: 
Este projeto é um e-commerce desenvolvido para o trabalho acadêmico chamado Projeto Integrador Transdisciplinar em Ciencia da Computação PIT II, com o objetivo de criar uma loja virtual funcional.
 Utilizamos WordPress como CMS, WooCommerce para o gerenciamento de produtos e pedidos,
 MySQL como banco de dados e o PagSeguro para integração de pagamentos. Hospedado na plataforma gratuita InfinityFree.

---

## 🚀 Tecnologias Utilizadas

- WordPress: Sistema de gerenciamento de conteúdo para criar o site.
- WooCommerce: Plugin para criar a loja virtual.
- PHP: Linguagem de programação usada no backend.
- HTML5/CSS3: Tecnologias para estrutura e estilização das páginas.
- JavaScript: Para interatividade no frontend.
- MySQL: Banco de dados para armazenar informações do site.
- PagSeguro: Integração de pagamentos.
- InfinityFree: Plataforma de hospedagem gratuita.

---

## 🛠️ Como Configurar o Projeto Localmente

### 1. Clone o Repositório
No terminal, execute:
(```bash)
git clone https://github.com/Pvalexx/ecommerce-cafe-do-lucas.git


### 2. Importe o Banco de Dados
Acesse o phpMyAdmin na sua hospedagem ou ambiente local.
Crie um banco de dados com o nome desejado (ex.: cafe_do_lucas).
Importe o arquivo banco-de-dados/banco-cafe-do-lucas.sql.

### 3. Configure o wp-config.php
Edite o arquivo wp-config.php no WordPress para apontar para o banco criado. Atualize:

define('DB_NAME', 'nome_do_banco');
define('DB_USER', 'usuario');
define('DB_PASSWORD', 'senha');
define('DB_HOST', 'localhost');

## 4. Faça Upload dos Arquivos do Tema
Vá para a pasta wp-content/themes/.
Copie a pasta do tema personalizado do repositório (tema-wordpress/) para essa localização.

## 5. Ative o Tema e Plugins no WordPress
No painel do WordPress, ative o tema que você adicionou.
Instale e configure o WooCommerce e o PayPal.
