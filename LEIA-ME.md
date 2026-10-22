# DriverEnglish

App de inglês para motorista (PWA). Funciona sem conta, sem servidor e sem internet depois da primeira abertura.

## Arquivos
- index.html: o app inteiro (telas, conteúdo e lógica)
- manifest.json: nome e ícones para instalar no iPhone
- sw.js: faz o app funcionar offline
- icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png: ícones

## Publicar no GitHub Pages
1. No GitHub, crie um repositório novo e público chamado `driverenglish`.
2. Clique em "Add file" > "Upload files" e envie TODOS os arquivos desta pasta (não a pasta, os arquivos de dentro).
3. Clique em "Commit changes".
4. Vá em Settings > Pages. Em "Branch", escolha `main` e a pasta `/ (root)`. Salve.
5. Espere 1 a 2 minutos. O endereço fica: https://SEU-USUARIO.github.io/driverenglish/

## Instalar no iPhone
1. Abra o endereço no Safari (tem que ser o Safari).
2. Toque em Compartilhar (quadrado com seta) > "Adicionar à Tela de Início" > Adicionar.
3. Abra o app pelo ícone novo uma vez com internet. Depois ele funciona offline.

## Vozes melhores
Ajustes > Acessibilidade > Conteúdo Falado > Vozes > Inglês. Baixe vozes "Melhoradas" (britânica, americana, australiana, irlandesa). Depois feche e reabra o app.

## Atualizar o app
1. Envie o index.html novo para o repositório (substituindo o antigo).
2. Abra o sw.js no GitHub, troque `driverenglish-v1` por `driverenglish-v2` (e assim por diante) e salve.
3. No iPhone, abra o app com internet, feche e abra de novo.

## Progresso
Fica guardado no próprio iPhone. Em Progresso > "Salvar cópia" você guarda um arquivo de segurança (por exemplo no iCloud Drive). "Restaurar" traz o progresso de volta.
