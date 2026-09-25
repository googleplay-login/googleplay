# ANA CAMILA — ARQUIVO 001

Site single-page editorial ultra premium, sem dependências externas além do Google Fonts.

## Quick start

```
index.html               ← abra no navegador
images/foto1.jpg         ← hero (a mais marcante)
images/foto2.jpg         ← editorial 01
images/foto3.jpg         ← editorial 02
images/foto4.jpg         ← editorial 03
music/king-for-a-day.mp3 ← música (loop, autoplay após clique)
```

1. Solte as 4 fotos em `images/` com os nomes acima.
2. Solte o mp3 em `music/king-for-a-day.mp3`.
3. Abra `index.html`.

Servidor local (se abrir direto der problema de áudio):
```bash
python3 -m http.server 8080
# acesse http://localhost:8080
```

## Sem editar código

Dentro do site, botão **+** no canto inferior direito → upload de fotos/música direto pelo navegador (elas aparecem na hora e ficam salvas no browser).

## Customizar textos

Abra `index.html` e procure por `<!-- TROQUE AQUI -->` — todas as fotos e textos-chave estão marcados.
