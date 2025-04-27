# MTA SA HUD Builder

Uma ferramenta web robusta para criar HUDs personalizados para servidores MTA SA, inspirada nas funcionalidades do Paint do Windows, com interface de arrastar e soltar, suporte a camadas, e exportação para código Lua.

## Funcionalidades
- **Ferramentas de Desenho**: Lápis, retângulo, linha, texto, borracha, e preenchimento.
- **Edição Avançada**: Ajuste de posição, tamanho, rotação, opacidade, e cores (com suporte a transparência).
- **Camadas**: Adicione, remova, reordene, e alterne a visibilidade de camadas.
- **Desfazer/Refazer**: Histórico de ações para facilitar a edição.
- **Exportação Lua**: Gera scripts Lua compatíveis com MTA SA, incluindo suporte a camadas e transparência.
- **Visualização em Tempo Real**: Veja as alterações no HUD instantaneamente.

## Estrutura do Projeto
- `index.html`: Estrutura HTML com dependências via CDN.
- `index.js`: Lógica React com componentes para canvas, ferramentas, propriedades, e camadas.

## Como Usar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mta-sa-hud-builder.git
   ```
2. Abra `index.html` em um navegador para testar localmente.
3. Acesse a versão hospedada em [Cloudflare Pages](https://mta-sa-hud-builder.pages.dev).

## Hospedagem
Este projeto está hospedado no Cloudflare Pages. Para configurar:
1. Conecte o repositório ao Cloudflare Pages.
2. Configure o build para usar a raiz do projeto (sem comandos de build, apenas arquivos estáticos).

## Contribuições
Sinta-se à vontade para abrir issues ou pull requests para melhorias, como:
- Suporte a importação de scripts Lua existentes.
- Salvamento de projetos no navegador (localStorage).
- Mais ferramentas de desenho (círculos, polígonos, etc.).

## Licença
MIT
