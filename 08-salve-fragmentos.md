# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

Cria um "backup" das alterações feitas.

**Quando usar / observação:**

Utilizar sempre que vamos trocar de branch ou quado temos alterações não commitadas que precisam ser salvas em algum lugar.

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

Retira o backup das nossas alterações do stash, tornando eles visíveis.

**Quando usar / observação:**

Utilizar sempre que queremos "resgatar" as nossas alterações do stash.

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

Lista todas as alterações dentro do stash.

**Quando usar / observação:**

Utilizar sempre que precisamos consultar o que tem no stash.

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

Descarta as alterações mais recentes do stash

**Quando usar / observação:**

Utilizar sempre que precisamos descartar algo do stash sem ter que usar o comando pop

---

## Checklist deste arquivo

- [ x ] 1. `git stash`
- [ x ] 2. `git stash pop`
- [ x ] 3. `git stash list`
- [ x ] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
