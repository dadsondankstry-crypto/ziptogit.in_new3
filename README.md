# Organizador HTML — PWA

Aplicativo instalável e offline baseado na V3 Mobile, com relatório HTML pesquisável após organizar arquivos.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie **o conteúdo desta pasta** para a raiz (incluindo `index.html`, `sw.js`, `manifest.webmanifest` e `icons/`).
2. No GitHub, vá em **Settings → Pages → Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/ (root)` e salve.
3. Abra a URL HTTPS publicada pelo GitHub Pages no Chrome/Edge e use **Instalar app** ou **Adicionar à tela inicial** (quando oferecido).

## Atenção

- O PWA instala e abre offline após o primeiro carregamento online.
- A seleção e a gravação de **pastas** dependem de `showDirectoryPicker` (File System Access API), que **não é compatível com todos os navegadores Android**. A instalação como PWA não remove essa restrição. Chrome/Edge desktop são os ambientes mais confiáveis para essa função.
- Não envie seus arquivos pessoais para o repositório: só os arquivos do aplicativo. Os HTMLs processados ficam no dispositivo.
- O relatório é habilitado **apenas após uma organização concluída**. Ele usa os caminhos relativos à pasta escolhida; o navegador não revela necessariamente o caminho absoluto.
- Nesta versão, as abas JSON, JavaScript, imagens e texto **não foram implementadas**.
