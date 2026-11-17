# Meu Financeiro | Creator

Aplicativo web progressivo (PWA) para controle de publis.

## O que inclui
- Cadastro, edição e exclusão de campanhas
- Valor, data, entrega, status de pagamento e observações
- Filtros por mês e ano e totais automáticos
- Indicadores gerais: contratado, recebido e pendente
- Backup/restauração JSON e exportação CSV
- IndexedDB para persistência local e service worker para cache/offline

## Publicar gratuitamente pelo celular com GitHub Pages
1. No iPhone, abra Safari e acesse https://github.com. Crie uma conta ou entre.
2. Toque no `+` e crie um repositório novo chamado `meu-financeiro-creator`. Marque `Public` e crie.
3. No repositório, use `Add file` > `Upload files`.
4. Descompacte este ZIP no app Arquivos do iPhone. Envie TODOS os arquivos que estão dentro da pasta `financeiro_creator` (index.html, manifest.webmanifest, sw.js e os dois PNGs). Não envie apenas o ZIP.
5. Toque em `Commit changes`.
6. No repositório, entre em `Settings` > `Pages`. Em `Build and deployment`, escolha `Deploy from a branch`; selecione `main` e `/ (root)` e toque em `Save`.
7. Aguarde o GitHub publicar. A URL esperada será `https://SEU-USUARIO.github.io/meu-financeiro-creator/`. Substitua SEU-USUARIO pelo seu nome de usuário GitHub.
8. Abra a URL no Safari. Confirme que a tela carrega e faça um cadastro de teste antes de usar com dados reais.

## Adicionar à Tela de Início do iPhone
1. Abra o endereço publicado no Safari (não dentro do navegador de outro aplicativo).
2. Toque no botão Compartilhar (quadrado com seta para cima).
3. Role e toque em `Adicionar à Tela de Início`.
4. Deixe o nome `Meu Financeiro` e toque em `Adicionar`.
5. Abra pelo novo ícone. Faça um cadastro de teste e confira se continua lá ao fechar e abrir novamente.

## Como os dados são guardados (leia)
Os dados ficam no IndexedDB do navegador, no próprio aparelho e na origem do site. Não há servidor, conta ou sincronização em nuvem nesta versão. Não limpe os dados do Safari/site sem antes exportar o backup JSON. Guarde o arquivo no iCloud Drive, Google Drive ou computador. Para trocar de aparelho: exporte o JSON no aparelho antigo e use `Restaurar backup` no novo.

A exportação CSV é útil para abrir os registros em Excel/Numbers; o JSON é o backup completo para restauração.

## Privacidade
Não há envio dos registros a um servidor externo nesta versão. Quem tiver acesso ao aparelho e ao navegador poderá acessar os dados locais. Proteja o aparelho e mantenha backups em local seguro.
