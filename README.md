# Meliça Brigadeiros — Hugo Site

Site estático em Hugo com tema custom **melica**, catálogo de produtos e botões de pedido via WhatsApp.

## Rodando localmente
1. Instale o Hugo Extended.
2. No terminal, dentro da pasta do projeto:
   ```bash
   hugo server -D
   ```
3. Abra o endereço local exibido.

## Editando o catálogo
- Cada produto é um arquivo em `content/produtos/*.md` contendo:
  - `title`, `description`, `price`, `image`
  - Um botão de WhatsApp já pronto no final do conteúdo
- As imagens estão em `static/images/brigadeiros/` (placeholders em SVG).

## Personalização
- Ajuste WhatsApp/Instagram/Email em `config.toml` (seção `[params]`).
- Cores e tipografia em `static/css/style.css`.
