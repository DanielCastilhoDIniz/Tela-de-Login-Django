# Tela de Login com Django

Este projeto implementa uma **Tela de Login** segura e responsiva utilizando Django, com integração a um banco de dados PostgreSQL e funcionalidades modernas como autenticação por token, validação de formulários e proteção contra ataques comuns (CSRF, XSS, etc.).

---

## 🚀 Funcionalidades

- **Autenticação Segura:** Sistema de login com validação de credenciais e proteção contra ataques de força bruta.
- **Registro de Usuários:** Formulário de cadastro com validação de campos (e-mail, senha, confirmação de senha).
- **Recuperação de Senha:** Fluxo de recuperação de senha via e-mail.
- **Proteção CSRF:** Defesa contra ataques Cross-Site Request Forgery.
- **Responsividade:** Design adaptável para mobile e desktop.
- **API RESTful:** Endpoints para integração com frontends modernos (React, Vue.js, etc.).

---

## 🛠️ Tecnologias Utilizadas

- **Backend:**
  - Django (Python)
  - Django REST Framework (DRF)
  - PostgreSQL (Banco de dados)
  - Docker (Containerização)
- **Frontend:**
  - HTML5, CSS3, JavaScript
  - Bootstrap (Design responsivo)
- **Ferramentas:**
  - GitHub Actions (CI/CD)
  - Swagger/OpenAPI (Documentação da API)
  - WhiteNoise (Servir arquivos estáticos)

---


---

## 🎯 Endpoints da API

| Método | Endpoint            | Descrição                          |
|--------|---------------------|------------------------------------|
| POST   | `/api/login/`       | Autenticação de usuário            |
| POST   | `/api/register/`    | Cadastro de novo usuário           |
| POST   | `/api/reset-password/` | Solicitação de recuperação de senha |
| GET    | `/api/user/`        | Detalhes do usuário autenticado    |

---

## 🛡️ Segurança

- **Proteção CSRF:** Todos os formulários estão protegidos contra ataques CSRF.
- **Validação de Senha:** Senhas são armazenadas com hash (bcrypt) e validadas quanto à complexidade.
- **Rate Limiting:** Limitação de tentativas de login para prevenir ataques de força bruta.
- **Headers de Segurança:** Configurações robustas de headers HTTP (CSP, HSTS, etc.).

---

## 🧪 Testes

O projeto inclui testes automatizados para:
- Autenticação de usuários
- Validação de formulários
- Fluxo de recuperação de senha

Para executar os testes:
```bash
docker compose exec web python manage.py test
```

---

## 🤝 Como Contribuir

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas alterações (`git commit -m 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

---

## 📄 Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## ✉️ Contato

- **Autor:** [daneilcastilhodiniz@gmail.com]
- **E-mail:**
- **LinkedIn:** 

---

## 🌟 Agradecimentos

- Equipe Django por um framework incrível.
- Comunidade open-source por todas as bibliotecas utilizadas.
- Você, por usar e contribuir com este projeto! ❤️

---



