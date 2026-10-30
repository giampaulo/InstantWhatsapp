# InstantWhatsApp 2.0

Aplicação web estática para iniciar conversas, guardar favoritos, visualizar recentes e mais acessados, organizar tags, usar modelos de mensagens e exportar dados. Layout mobile-first, temas claro/escuro e PWA.

## Prévia

Branch `v2`: `index.html` autocontido com estilos e JavaScript. Abra via servidor HTTPS/localhost; instale como PWA onde compatível.

## Privacidade e limitações

Os dados ficam no `localStorage` do navegador (sem sincronização). Faça backup JSON regularmente. O gerador de QR usa API externa. A importação CSV simples não suporta todos os casos de aspas/multilinhas. Não há integração com a API do WhatsApp. Falta validar migração do formato legado e testes de navegação antes de promover para `main`.

## Publicação

No GitHub Pages é possível selecionar a branch `v2` e diretório raiz, ou publicar via GitHub Actions. Os arquivos legados foram preservados.
