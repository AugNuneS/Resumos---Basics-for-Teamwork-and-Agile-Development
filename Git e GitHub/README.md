# Resumo - Git 🌐

## O que é Git?

Git é um sistema de controle de versão distribuído, essencial para gerenciar e rastrear alterações em arquivos de projetos ao longo do tempo.

---

## Tracking dos Arquivos

| Ação          | Comando                   | Descrição                                          |
|---------------|---------------------------|----------------------------------------------------|
| Rastrear      | `git status`             | Mostra o estado atual do repositório, arquivos modificados, etc. |
| Histórico     | `git log`                | Exibe o histórico de commits realizados no repositório. |

---

## Realizando Commit

Um commit é uma captura das alterações feitas nos arquivos. Para realizá-lo, se utiliza o comando `git commit -m "mensagem"`.

| Comando                      | Descrição                             |
|------------------------------|---------------------------------------|
| `git commit -m "fix: texto corrigido"` | Registra alterações com uma descrição. |

---

## Modificando um Arquivo

Para modificar um arquivo, basta editá-lo. Depois, salvar as alterações e fazer o commit para registrar essas mudanças.

---

## Pulando o Staging

Para pular o staging, é só usar o comando `git commit -a`, que faz o commit de todas as alterações automaticamente.

---

## Removendo Arquivos

| Ação            | Comando                       | Descrição                                           |
|-----------------|-------------------------------|-----------------------------------------------------|
| Remover arquivo  | `git rm nome_do_arquivo`      | Remove o arquivo do repositório.                   |

---

## Renomeando Arquivos

Para enomear arquivos, basta utilizar o comando `git mv nome_antigo nome_novo`, que atualiza o nome do arquivo e registra a mudança.

---

## Realizando um Amend nas Mensagens

Para corrigir a mensagem do último commit, é só usar o comando `git commit --amend -m "nova mensagem"`.

---

## Log Detalhado

Para visualizar o histórico de commits e acompanhar o projeto, é só usar o comando `git log`.

---

## Git Reset

| Ação                    | Comando                      | Descrição                                          |
|-------------------------|------------------------------|----------------------------------------------------|
| Desfazer último commit  | `git reset HEAD~1`          | Reverte o último commit, mantendo as alterações.   |
| Hard reset              | `git reset --hard <commit>` | Descarta todas as alterações não confirmadas.      |

---

## O que são Branches?

Branches são ramificações que permitem trabalhar em diferentes funcionalidades ou correções simultaneamente.

| Ação                      | Comando                       | Descrição                                         |
|---------------------------|-------------------------------|---------------------------------------------------|
| Criar nova branch         | `git branch nome_da_branch`   | Cria uma nova branch.                             |
| Alternar para branch      | `git switch nome_da_branch` | Muda para a branch especificada.                  |

---

## Conclusão 🔚

Git é uma ferramenta indispensável para controle de versão, permitindo que desenvolvedores gerenciem suas alterações de maneira organizada.