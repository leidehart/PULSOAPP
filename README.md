# PULSO 40+ — versão robusta

PWA pessoal para mulheres 40+ que desejam acompanhar evolução emocional, praticar conteúdos terapêuticos, ampliar repertório de português e treinar inglês intermediário de forma contínua.

## O que esta versão entrega

- **Terapia como prática observável**: exercícios sobre crítica interna, limites, regulação emocional, apego, diário de terapia e identidade futura.
- **Termômetro terapêutico diário**: humor, ansiedade, clareza, autoestima, voz interna e foco do dia.
- **Leitura de evolução**: o app calcula um Índice Pulso e mostra sinais de tendência, como “ajudando”, “estável”, “observando” ou “atenção”.
- **Português mais sofisticado**: vocabulário, fala pública, argumentação, reescrita profissional e leitura crítica.
- **Inglês intermediário**: autoapresentação, terapia em inglês, reuniões, pitch de projeto, limites e conectores de escrita.
- **Laboratórios de escrita**: campos para praticar português e inglês, com histórico local.
- **Resumo para terapia**: botão para gerar um texto copiável com os últimos 14 dias.
- **PWA instalável**: funciona como app pelo navegador e salva dados no aparelho.

## Observação de segurança

Este app é um apoio de autoconhecimento, educação emocional e prática de linguagem. Ele não substitui psicoterapia, atendimento médico, avaliação psicológica, psiquiátrica ou atendimento de emergência. Os indicadores são baseados em autorrelato e servem como pistas para reflexão.

## Arquivos

- `index.html`: aplicativo completo.
- `manifest.webmanifest`: metadados de instalação PWA.
- `service-worker.js`: cache e funcionamento básico offline.
- `icon.svg`, `icon-192.png`, `icon-512.png`, `icon-180.png`, `icon-32.png`, `favicon.png`: ícones.
- `.nojekyll`: evita processamento do GitHub Pages.

## Como publicar no GitHub Pages

1. Envie todos os arquivos para a raiz do repositório.
2. Abra **Settings > Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/root`.
5. Clique em **Save**.
6. Aguarde o link ser gerado.

## Atualização importante

O `service-worker.js` usa cache. Quando trocar arquivos no GitHub, aguarde alguns minutos e recarregue o app. Se o celular continuar mostrando a versão antiga, remova o app instalado e instale novamente pelo navegador.

## Dados

Os dados ficam em `localStorage`, no próprio navegador/aparelho. Se limpar dados do navegador ou trocar de celular, o histórico não acompanha automaticamente.
