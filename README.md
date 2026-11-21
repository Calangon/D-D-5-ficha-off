# Ficha D&D 5e — PWA

Aplicação web responsiva em português, inspirada na organização visual das fichas tradicionais mostradas como referência pelo usuário. O site possui três páginas principais: Personagem; História & Equipamento; Magias. Também inclui a aba opcional Atributos e modificadores.

## Recursos
- múltiplas fichas, troca, renomear, excluir e resetar com confirmação;
- salvamento automático em localStorage;
- exportação/importação JSON;
- imagem do personagem em cada ficha;
- campos extensos sem limite artificial de texto;
- página dedicada a magias, níveis 0–9, preparados e espaços de magia;
- impressão / salvar como PDF;
- PWA com cache para uso offline após a primeira visita.

## GitHub Pages
1. Crie um repositório público.
2. Envie o conteúdo desta pasta para a raiz do repositório (o `index.html` deve ficar na raiz).
3. Em Settings > Pages, selecione Deploy from a branch, branch `main` e pasta `/root`.
4. Salve e abra o endereço fornecido pelo GitHub.

## Offline
Abra a aplicação uma vez com internet e instale/adicionar à tela inicial pelo navegador. O service worker mantém os arquivos da aplicação disponíveis offline. Os dados das fichas continuam no armazenamento local do navegador/aparelho.

## Transferência
Use Exportar para gerar JSON e Importar no outro dispositivo. Para segurança, mantenha cópias dos JSON importantes.
