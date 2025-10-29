# qq-docs

Repositório de documentação para o qqfrevo

## 🚀 Desenvolvimento Local

Para executar a documentação localmente:

1. Instale as dependências:
```bash
pip install -r requirements.txt
```

2. Inicie o servidor de desenvolvimento:
```bash
mkdocs serve
```

3. Acesse http://127.0.0.1:8000 no seu navegador

## 📦 Build

Para construir a documentação:

```bash
mkdocs build
```

## 🚢 Deploy

A documentação é automaticamente implantada no GitHub Pages quando há um push para a branch `main`.

O workflow do GitHub Actions está configurado em `.github/workflows/deploy-docs.yml` e realiza:
- Build do MkDocs
- Deploy automático para GitHub Pages

## 📝 Estrutura

- `docs/` - Arquivos de documentação em Markdown
- `mkdocs.yml` - Configuração do MkDocs
- `.github/workflows/` - Workflows do GitHub Actions

## 🛠️ Tecnologias

- [MkDocs](https://www.mkdocs.org/) - Gerador de sites de documentação
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) - Tema Material Design
