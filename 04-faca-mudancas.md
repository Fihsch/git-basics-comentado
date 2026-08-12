# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

O git staus nos mostra em qual branch estamos e como ela está em relação a branch remota.

**Quando usar / observação:**

Sempre antes de fazer uma operação git, para se certificar que estamos onde realmente precisamos e seguindo a branch remota corretamente.

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra as diferenças entre os arquivos locais e os arquivos inicialmente commitados na branch

**Quando usar / observação:**

Sempre antes de commitar para revisar as própias alterações antes de mandar para o servidor

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Ele faz um "stage" dos aruivos.
Os arquivos em "stage" são aqueles que serão commitados com o git commit

**Quando usar / observação:**

Sempre antes dos commits para mandar os arquivos alterados

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Mostra as diferenças entre os arquivos locais em "stage" e os arquivos inicialmente commitados na branch

**Quando usar / observação:**

Sempre antes de commitar para revisar as própias alterações antes de mandar para o servidor

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Serve para reverter as alterações locais não commitadas.

**Quando usar / observação:**

Deve ser utilizado sempre que queremos reverter uma alteração local

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Commita os arquivos que estão em stage.
o -m "[mensagemdescritiva]" adiciona uma mensagem ao commit.

**Quando usar / observação:**

Sempre que queremos oficializar as nossas alterações locais
é de extrema importancia colocar mensagens claras e padronizadas nos commits.

---

## Checklist deste arquivo

- [ x ] 1. `git status`
- [ x ] 2. `git diff`
- [ x ] 3. `git add [arquivo]`
- [ x ] 4. `git diff --staged`
- [ x ] 5. `git reset [arquivo]`
- [ x ] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
