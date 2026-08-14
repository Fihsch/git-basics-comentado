# 02. Configure a ferramenta

> Configure informações de usuário para todos os repositórios locais.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)

---

## Comandos desta seção (2)

### 1. `git config --global user.name "[nome]"`

```bash
git config --global user.name "[nome]"
```

**O que faz:**

Esse comando é utilizado para atrelar um nome ao commit.

**Quando usar / observação:**

Usar sempre que em uma máquina nova para configurar o usuário.
O interessante é que pode ser utilizado como git config --local quando apenas para 1 repositório.

---

### 2. `git config --global user.email "[endereco-de-email]"`

```bash
git config --global user.email "[endereco-de-email]"
```

**O que faz:**

Esse comando é utilizado para atrelar um endereço de email ao commit.

**Quando usar / observação:**

Usar sempre que em uma máquina nova para configurar o email.

---

## Checklist deste arquivo

- [ x ] 1. `git config --global user.name "[nome]"`
- [ x ] 2. `git config --global user.email "[endereco-de-email]"`

---

[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)
