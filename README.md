# Dashboard público de Telemetria e Fretamento

Dashboard estático responsivo preparado para publicação no GitHub Pages.

## Proteção dos dados

A versão pública contém somente indicadores consolidados. Não foram publicados:

- placas e registros individualizados;
- centros de custo e descrições internas;
- cidades e arquivos de origem;
- planilhas ou bases brutas.

## Publicação

O workflow `.github/workflows/pages.yml` publica automaticamente o arquivo `index.html` após alterações na branch `main`.

Caso seja a primeira publicação deste repositório, abra **Settings → Pages → Source** e selecione **GitHub Actions**.

## Execução

O dashboard não exige backend, banco de dados ou dependências externas.
