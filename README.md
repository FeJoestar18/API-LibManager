# 📚 LibManager API

[![Laravel](https://img.shields.io/badge/Laravel-11.x-red?style=for-the-badge&logo=laravel)](https://laravel.com/)
[![PHP](https://img.shields.io/badge/PHP-8.2+-blue?style=for-the-badge&logo=php)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-8+-orange?style=for-the-badge&logo=mysql)](https://www.mysql.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

A **LibManager API** é uma solução desenvolvida em **Laravel** para o gerenciamento moderno de bibliotecas.  
Oferece endpoints REST seguros e escaláveis para **cadastro de livros, controle de usuários e gestão de empréstimos**.  

---

## 🚀 Funcionalidades
- 📚 **Livros** → cadastro, edição, listagem e exclusão  
- 👥 **Usuários** → autenticação, permissões e gerenciamento  
- 🔄 **Empréstimos** → registro de retirada e devolução de obras  
- 📊 **Relatórios** → estatísticas de uso e livros mais lidos  
- 🔐 **Segurança** → autenticação via **JWT**  

---

## 🛠️ Tecnologias
- [Laravel 11.x](https://laravel.com/)  
- [PHP 8.2+](https://www.php.net/)  
- [MySQL 8+](https://www.mysql.com/)  
- [Composer](https://getcomposer.org/)  
- JWT para autenticação  

---

## ⚙️ Instalação

Clone o repositório:
```bash
git clone https://github.com/FeJoestar18/API-LibManager.git
```

```bash
cd libmanager-api
```

Instale as dependências:
```bash
composer install
```

Configure o ambiente:
```bash
cp .env.example .env
php artisan key:generate
```

Configure o banco de dados no arquivo `.env` e rode as migrations:
```bash
php artisan migrate
```

Inicie o servidor:
```bash
php artisan serve
```

---

## 🔑 Autenticação
A API utiliza **JWT (JSON Web Token)** para autenticação.  
Após login, utilize o token retornado no **header Authorization** das requisições:

```http
Authorization: Bearer {seu_token_aqui}
```

---

## 📌 Endpoints principais (exemplo)

EM DESENVOLVIMENTO POR ENQUANTO

---

## 📅 Roadmap
- [ ] Sistema de reservas de livros  
- [ ] Notificações por e-mail/SMS  
- [ ] Integração com aplicações mobile  
- [ ] Dashboard administrativo  

---

## 🤝 Contribuição
Contribuições são sempre bem-vindas!  
Para contribuir:
1. Faça um fork do projeto  
2. Crie uma branch (`git checkout -b feature/nova-feature`)  
3. Commit suas alterações (`git commit -m 'Adicionando nova feature'`)  
4. Envie um push (`git push origin feature/nova-feature`)  
5. Abra um Pull Request 🎉  

---

## 📄 Licença
Este projeto está licenciado sob a **MIT License** – veja o arquivo [LICENSE](LICENSE) para mais detalhes.  

---
