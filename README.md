# ANA CAMILA — ARQUIVO 001

Site single-page, sem dependências externas além do Google Fonts.

## Como usar

1. **Música**: coloque o arquivo mp3 em `music/king-for-a-day.mp3` (o player já aponta pra esse caminho).
2. **Fotos**: abra `index.html` e procure pelos comentários `<!-- TROQUE AQUI -->`. São 4 fotos (hero + 3 linhas editoriais). Basta substituir o `src` das `<img>` por caminhos locais, ex: `images/foto1.jpg`, `images/foto2.jpg`, etc.
3. **Textos**: tudo está no próprio HTML; é só editar.
4. Abra `index.html` direto no navegador, ou rode um servidor local (`python3 -m http.server`).

## Estrutura
- `index.html` — site completo (HTML + CSS + JS inline)
- `images/` — coloque aqui as fotos da Ana Camila
- `music/` — coloque aqui `king-for-a-day.mp3`

## Preview local
```bash
python3 -m http.server 8080
```
Depois acesse `http://localhost:8080`.

Clique em "● CLIQUE PARA ENTRAR" para destravar o áudio (autoplay com som exige interação do usuário em todos os navegadores).
