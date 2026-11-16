# Life Control — versão web instalável (PWA)

Esta é uma versão inicial para testar no iPhone sem Mac. Ela registra receitas, despesas e contas localmente no navegador.

## Publicação necessária
Para instalar pela tela inicial do iPhone, os arquivos precisam estar publicados em um endereço HTTPS. O ZIP sozinho não é instalável como app.

## Como usar
1. Publique os arquivos `index.html`, `manifest.json` e `sw.js` em um serviço de hospedagem estática HTTPS.
2. No iPhone, abra o endereço publicado no Safari.
3. Toque em Compartilhar > Adicionar à Tela de Início.
4. Confirme o nome Life Control e toque em Adicionar.

## Limitações desta versão
- Dados ficam no armazenamento local do navegador deste iPhone. Não há conta nem sincronização em nuvem.
- Voz depende do suporte de reconhecimento de fala do Safari/iOS. Se não funcionar, use o ditado do teclado do iPhone.
- Contas cadastradas não disparam notificações automáticas nesta versão.
- Não substitui aconselhamento financeiro.
