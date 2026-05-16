# Testes de API com Postman e Newman

## Sobre o Projeto

Projeto desenvolvido para uma disciplina da faculdade com o objetivo de realizar testes automatizados em uma API utilizando Postman e Newman.

Foram realizados testes de:
- Requisições HTTP
- Validação de status code
- Verificação de respostas JSON
- Automação de testes via terminal

---

## Tecnologias

- Postman
- Newman

---

## Execução dos Testes

Instalar o Newman:

```bash
npm install -g newman
```

Executar collection:

```bash
newman run collection.json
```

Executar com environment:

```bash
newman run collection.json -e environment.json
```

---

## 📖 Aprendizados

- Uso de collections e environments
