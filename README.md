# Despesas

App web (PWA) para registar despesas.

## Publicar com GitHub Pages

1. No GitHub, abre **Settings → Pages**.
2. Em **Build and deployment**, escolhe **Deploy from a branch**.
3. Seleciona o branch onde estão os ficheiros (ex.: `main`) e a pasta `/ (root)`, e clica **Save**.
4. Após 1–2 minutos a app fica em `https://<utilizador>.github.io/<repositorio>/`.

## Adicionar ao telemóvel

- **iPhone (Safari):** abre o link → botão Partilhar → **Adicionar ao ecrã principal**.
- **Android (Chrome):** abre o link → menu ⋮ → **Adicionar ao ecrã principal** / **Instalar app**.

## Importar despesas

Botão **Importar despesas (CSV)**: aceita o ficheiro que a própria app exporta, ou uma folha do Excel guardada como CSV com as colunas `Data;Descrição;Valor`. As despesas são acrescentadas às que já existem, e as linhas repetidas são ignoradas.
