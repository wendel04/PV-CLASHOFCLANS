# Template — Biblioteca de Exus e Pombagiras em Amigurumi

Landing low-ticket em português para produto digital artesanal/espiritual com forte apelo visual, oferta em 2 planos, mockups grandes, bônus e seções em padrão zebra. Use como base para ofertas de artesanato, crochê, amigurumi, espiritualidade, coleções digitais em PDF e produtos com biblioteca organizada por categorias.

## Sobre o produto original

- **Nicho**: amigurumi, crochê, artesanato espiritual e entidades de Umbanda/Quimbanda.
- **Produto**: Biblioteca de Exus e Pombagiras em Amigurumi com +100 modelos em PDF, fotos de referência e organização por entidade.
- **Plano Básico**: R$27,90 — biblioteca principal.
- **Plano Completo**: R$37,90 — biblioteca principal + 5 bônus exclusivos.
- **Bônus do Plano Completo**:
  1. Kit de Acabamento e Apresentação
  2. Lista de Materiais para Amigurumis Espirituais
  3. Guia de Organização da Coleção
  4. Ficha de Identidade Simbólica das Entidades
  5. Acesso ao Grupo de Artesãs no WhatsApp
- **Persona**: artesãs e pessoas que amam amigurumi, espiritualidade, peças feitas à mão, presentes simbólicos e venda de peças diferentes.
- **Checkout**: links ainda genéricos/placeholder nos botões dos planos.
- **Tracking**: Pixel UTMify + script de UTMs no `<head>`.

## Paleta de cores

| Token | HEX | Uso |
|-------|-----|-----|
| **Marrom escuro** | `#3b1a0b` | Bloco "Tudo que vai receber", oferta e footer |
| **Marrom mais escuro** | `#2a1208` | Bordas e fundo da seção de oferta |
| **Creme hero** | `#fff4dc` | Primeira dobra |
| **Dourado claro** | `#f8dfad` | Demonstração e bônus |
| **Bege neutro** | `#f3e8d8` | Benefícios |
| **Off-white rosado** | `#fff7f9` | Bloco "ideal para você" |
| **Coral urgência** | `#ef5b4d` | Barra superior e bloco de urgência |
| **Azul claro garantia** | `#eef8fb` | Garantia |
| **Verde limão CTA** | Tailwind `lime-400` | Todos os botões principais |
| **Azul destaque** | Tailwind `blue-600` | Destaques em texto e títulos de plano |

## Estrutura

1. **Faixa de topo** — aviso "ATENÇÃO OFERTA VALIDA APENAS HOJE".
2. **Hero** — headline com destaque azul, mockup principal grande, subheadline, bullets em tags e CTA.
3. **Demonstração** — dois carrosseis horizontais com imagens A4 dos modelos.
4. **Benefícios** — cards com ícones/emoji no estilo recurso rápido.
5. **Urgência** — fundo coral/vermelho, cronômetro minimalista, headline caixa alta e CTA verde.
6. **Ideal para você** — cards verdes com check customizado grande.
7. **Tudo que vai receber** — fundo marrom, mockup grande, card branco com lista em duas colunas e CTA.
8. **Bônus** — cards visuais com mockup, nome, descrição e badge "BÔNUS GRATUITO HOJE".
9. **Oferta** — cards de Pacote Básico e Pacote Completo, com completo em destaque.
10. **Garantia** — selo visual de 15 dias e CTA.
11. **Como vai ser seu acesso** — passo a passo com ícones e imagem estática do entregável.
12. **FAQ** — perguntas frequentes em accordion.
13. **Footer** — copyright, Lei 9.610/98, compra segura e garantia.

## Decisões importantes

- **Primeira dobra não fica toda em caixa alta**. Demais headlines da página usam caixa alta.
- **Mockups principais ficam grandes e sem efeito de card**. Não adicionar borda/card ao redor das imagens principais.
- **Carrosseis são divididos em duas linhas**. Manter 5 imagens em cima e 5 embaixo quando adaptar.
- **Botões continuam verde limão**. O usuário pediu explicitamente para manter esse padrão.
- **Bloco de urgência permanece vermelho/coral**.
- **Cards do bloco "ideal para você" usam check customizado** em imagem: `https://i.postimg.cc/Dz61JcCv/download.png`.
- **Pacote Completo deve ter mais peso visual** que o Básico.
- **Pixel UTMify e script de UTMs ficam no `<head>` em blocos separados**.
- **Fonte atual**: Montserrat com pesos leves para texto e forte para headlines. Se o usuário pedir Poppins, adaptar mantendo hierarquia visual.
- **Mobile é prioridade**: evitar fontes grandes demais e manter cards um abaixo do outro.

## Slots customizáveis

### Textos

- Headline do hero
- Subheadline do hero
- Bullets principais
- Lista de entidades/modelos
- Benefícios
- Itens dos bônus
- Preços dos planos
- Garantia
- FAQ
- Footer legal

### Imagens

- Mockup principal: usado no hero, no bloco "Tudo que vai receber" e no Pacote Completo.
- Mockup do Pacote Básico.
- Imagens dos carrosseis.
- Mockups dos 5 bônus.
- Selo de garantia.
- Imagem estática do passo a passo/acesso.

### Tracking

- Pixel UTMify:
  - `window.pixelId = "..."`
  - `https://cdn.utmify.com.br/scripts/pixel/pixel.js`
- UTMs:
  - `https://cdn.utmify.com.br/scripts/utms/latest.js`
  - `data-utmify-prevent-xcod-sck`
  - `data-utmify-prevent-subids`

### Checkout

- Substituir os `href="#"` dos botões:
  - `QUERO PACOTE BÁSICO`
  - `QUERO PACOTE COMPLETO`
  - CTAs gerais podem apontar para `#oferta` ou checkout, conforme estratégia.

## Melhor uso

Use este template quando a oferta tiver:

- Produto digital visual em PDF.
- Artesanato, amigurumi, crochê ou peças feitas à mão.
- Nicho espiritual, simbólico ou colecionável.
- 2 planos de preço.
- 4 a 6 bônus.
- Muitos mockups/imagens de referência.
- Necessidade de página mobile-first, direta e visual.
