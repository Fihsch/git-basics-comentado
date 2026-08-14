# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

Esse arquivo diz ao git quais arquivos ignorar no versionamento.

**Quando usar / observação:**

Utilizar quando temos arquivos que não precisam ser inclusos no repositório git, mas que contribuem ao projeto.

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

Lista todos os arquivos ignorados no versionamento do projeto.

**Quando usar / observação:**

Utilizar para consultar a lista de arquivos que não fazem parte do versionamento git.

---

## Checklist deste arquivo

- [ x ] 1. Arquivo `.gitignore`
- [ x ] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
