# Guia Prático de Git no FSC Labs

## 1. Antes de Começar a Tarefa

### Atualize sua cópia local do projeto:

```bash
git pull origin main
```

### Crie uma branch para sua tarefa:

```bash
git checkout -b feat/add-delete-product-button
```

### Padrões de nomes de branch:

- **`feat/`** para novas funcionalidades.
- **`fix/`** para correções de bugs.
- **`chore/`** para configurações ou ajustes não relacionados ao código principal.

> **Nota:** Sempre trabalhe em uma branch separada. Nunca edite diretamente o branch `main`.

---

## 2. Durante o Desenvolvimento

### Adicione as mudanças ao controle de versão:

```bash
git add .
```

### Faça commits descritivos seguindo o padrão **Conventional Commits**:

```bash
git commit -m "feat: add delete product button"
```

---

## 3. Finalizando a Tarefa

### Sincronize sua branch com o branch principal:

```bash
git pull origin main
git merge main
```

### Envie sua branch para o repositório remoto:

```bash
git push origin feat/add-delete-product-button
```

### Abra um Pull Request (PR) e descreva:

- **O que foi feito.**
- **O motivo da mudança.**
- **Qualquer detalhe técnico relevante.**
