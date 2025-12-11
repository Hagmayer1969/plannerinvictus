# Agenda Estoica 2026 — Deploy

Este repositório contém um site estático (HTML/CSS/JS). O arquivo de workflow em `.github/workflows/deploy.yml` publica automaticamente o conteúdo para o GitHub Pages quando houver push na branch `main`.

Passos rápidos para ativar o deploy:

1. Confirme que a branch principal do repositório é `main`. Se for `master` ou outra, edite o arquivo `/.github/workflows/deploy.yml` e altere `branches: - main` para o nome correto.
2. Faça commit e push das mudanças para o repositório remoto:

```bash
git add .
git commit -m "Add GitHub Pages deploy workflow"
git push origin main
```

3. O GitHub Actions executará o workflow e publicará o site. Após o deploy, acesse o site em `https://<seu-usuario>.github.io/<seu-repositorio>/` (ou verifique as configurações de Pages no repositório para o URL exato).

Observações:
- Se preferir usar Netlify ou Vercel, posso adicionar configurações específicas para esses serviços.
- O workflow usa a ação oficial de Pages do GitHub e publica o conteúdo do repositório raiz. Se você tiver arquivos que não devem ser publicados, coloque o site numa subpasta e atualize `path` no workflow.
