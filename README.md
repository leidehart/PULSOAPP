# PULSO 40+

App PWA de autoestima, confiança, língua portuguesa e inglês básico para mulheres 40+.

## O que foi alterado nesta versão

- Tudo foi organizado em formato clicável e de múltipla escolha.
- As áreas ficaram separadas em: **Terapia**, **Língua Portuguesa** e **Inglês**.
- Cada exercício mostra uma **nota final de 0 a 10**.
- A evolução diária é salva automaticamente no navegador/celular.
- A tela inicial mostra exercícios feitos hoje, nota média do dia, sequência de dias e evolução dos últimos 7 dias.
- O histórico mostra as últimas notas por data e categoria.

## Arquivos principais

- `index.html`: aplicativo completo.
- `manifest.webmanifest`: nome, cores e dados de instalação do app.
- `service-worker.js`: cache básico para funcionamento como PWA.
- `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-180.png`, `icon-32.png`, `favicon.png`: ícones do app.
- `.nojekyll`: evita processamento do GitHub Pages.

## Como publicar no GitHub Pages

1. Crie ou abra o repositório no GitHub.
2. Envie todos os arquivos deste pacote para a raiz do repositório, junto do `index.html`.
3. Abra **Settings** > **Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`.
6. Clique em **Save**.
7. Aguarde o GitHub gerar o link do site.

## Como atualizar um app já publicado

1. Substitua os arquivos antigos por estes novos arquivos.
2. Faça commit e push para o GitHub.
3. Aguarde o GitHub Pages atualizar.
4. No celular, feche e abra o app novamente. Se continuar aparecendo versão antiga, remova o app instalado e instale de novo pelo navegador.

## Observação importante

Os dados de evolução ficam salvos no aparelho/navegador em `localStorage`. Se limpar os dados do navegador ou trocar de aparelho, o histórico local não acompanha automaticamente.
