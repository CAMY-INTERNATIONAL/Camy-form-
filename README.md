# CAMY — Diagnóstico de Bem-Estar

Formulário de avaliação de saúde mental para a Better Care Moçambique.

## Configuração antes de publicar

No ficheiro `src/App.jsx`, preencher o bloco CONFIG no topo:

```js
const CONFIG = {
  KOBO_ASSET_UID:  "colar aqui o Asset UID do KoboToolbox",
  KOBO_API_TOKEN:  "colar aqui o API Token do KoboToolbox",
  ...
}
```

## Como obter os valores do KoboToolbox

### ASSET_UID
Após fazer deploy do formulário no KoboToolbox, o URL fica:
`https://kf.kobotoolbox.org/#/forms/ESTE_E_O_ASSET_UID/summary`

### API_TOKEN
KoboToolbox → Avatar (canto superior direito) → Account Settings → API → copiar token

## Desenvolvimento local

```bash
npm install
npm run dev
```

## Deploy automático

Qualquer push para a branch `main` activa o GitHub Actions e publica automaticamente.
