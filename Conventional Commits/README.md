# Resumo - Conventional Commits 📜

## O que são Conventional Commits?

Conventional Commits é uma convenção para mensagens de commit que facilita a criação de um histórico simplificado. Essa convenção descreve funcionalidades, correções e mudanças significativas.

---

## Estrutura do Commit

As mensagens de commit devem ser estruturadas da seguinte forma:


### Tipos de Commit:

- **fix:** Corrige um bug no código.
- **feat:** Introduz uma nova funcionalidade.
- **BREAKING CHANGE:** Indica uma mudança significativa na API, podendo aparecer em qualquer tipo de commit.

---

## Exemplos de Mensagens de Commit

1. **feat:** adicionar a opção de personalizar a configuração.
   - **BREAKING CHANGE:** a chave `extends` agora serve para adicionar configurações de outros arquivos.

2. **fix:** evitar que requisições se misturem.
   - Adiciona um ID para cada requisição e referência à mais recente.

---

## Especificações

- Cada commit **PRECISA** começar com um tipo (como feat ou fix).
- O **escopo** é opcional e ajuda a dar mais contexto (por exemplo: feat(parser): adicionar suporte a arrays).
- A **descrição** deve vir logo depois do tipo/escopo e deve resumir rapidamente o que foi mudado.

---

## Vantagens dos Conventional Commits

- Geração automática de CHANGELOGs.
- Determinação automática de aumentos de versão semântica.
- Comunicação clara sobre mudanças com colegas e partes interessadas.
- Facilita a contribuição de novos desenvolvedores ao oferecer um histórico de commits estruturado.
