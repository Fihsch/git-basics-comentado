# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

Deleta o arquivo especificado do disco e do git.

**Quando usar / observação:**

Utilizar sempre que for necessário deletar algum arquivo permanentemente.

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

Remove o arquivo apenas do git, porém mantém ele no disco.

**Quando usar / observação:**

Utilizar quando o git não precisar mais seguir as alterações de um determinado arquivo, mas ainda assim mantê-lo localmente.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

Utilizado para renomear arquivos.

**Quando usar / observação:**

Utilizar sempre que for necessário renomear um arquivo e manter as alterações no git.

---

## Checklist deste arquivo

- [ x ] 1. `git rm [arquivo]`
- [ x ] 2. `git rm --cached [arquivo]`
- [ x ] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
