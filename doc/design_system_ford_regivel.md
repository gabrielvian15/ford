# Design System — Ford Regivel

**Versão 1.0 · Referência visual e técnica para o site**

Design System baseado na identidade visual existente da Ford Regivel, preservando azul institucional, azul elétrico, prata, branco, tipografia moderna e proposta automotiva. Objetivo: interface moderna, confiável, sofisticada e comercial, com foco na apresentação de veículos e conversão de visitantes em clientes.

## 1. Paleta de cores

| Nome | HEX | Uso |
|---|---|---|
| Azul institucional | `#102F78` | Marca, navegação, títulos e ações principais |
| Azul elétrico | `#0878E8` | Destaques, ações, links e estados ativos |
| Cinza azulado claro | `#F2F5FA` | Fundos de seções e áreas de conteúdo |
| Azul escuro | `#17243A` | Textos, rodapé e contraste |
| Branco | `#FFFFFF` | Cards, fundos e áreas limpas |
| Prata | `#C5CAD3` | Detalhes, divisores e elementos decorativos |
| Verde sucesso | `#16A34A` | Confirmações e sucesso |
| Vermelho erro | `#DC2626` | Erros e alertas |
| Amarelo aviso | `#F59E0B` | Avisos e pendências |
| Cinza borda | `#DCE2EC` | Bordas e divisores |
| Cinza texto | `#64748B` | Textos secundários |

## 2. Tipografia

- **Títulos:** Montserrat Bold.
- **Textos, menus, formulários e descrições:** Inter Regular.
- Evitar parágrafos longos e texto totalmente em caixa alta, exceto etiquetas e chamadas pequenas.
- Manter legibilidade e contraste em telas pequenas.


## 3. Hierarquia e tamanhos

| Elemento | Fonte | Tamanho | Peso |
|---|---|---:|---|
| H1 | Montserrat | 40 px | 700 |
| H2 | Montserrat | 32 px | 700 |
| H3 | Montserrat | 26 px | 700 |
| H4 | Montserrat | 22 px | 700 |
| H5 | Montserrat | 18 px | 700 |
| H6 | Montserrat | 16 px | 700 |
| Texto grande | Inter | 18 px | 400 |
| Texto padrão | Inter | 16 px | 400 |
| Texto pequeno | Inter | 14 px | 400 |
| Legenda | Inter | 12 px | 400 |

Espaçamento inferior sugerido: H1 24 px; H2 20 px; H3 16 px; parágrafo 16 px; legenda 8 px.

## 4. Botões

- Altura: 48 px; padding horizontal: 24 px; radius: 8 px.
- Fonte: Inter, 16 px, peso 600.
- Transição: 200 ms.
- **Primário:** fundo `#102F78`, texto branco.
- **Ação/destaque:** fundo `#0878E8`, texto branco.
- **Secundário:** fundo transparente, borda `#102F78`, texto azul institucional.
- **Neutro:** fundo `#F2F5FA`, texto `#17243A`.
- Hover: azul mais intenso e leve elevação; active: escurecimento; disabled: opacidade reduzida; focus: indicador visível para teclado.
- Botões previstos: Ver veículos, Ver detalhes, Tenho interesse, Falar com vendedor, Consultar financiamento, Simular financiamento, Comprar à vista, Enviar mensagem, Voltar e Saiba mais.

## 5. Formulários

Campos simples, intuitivos e sem excesso de entradas.

- Altura de campo: 48 px; fundo branco; borda `#DCE2EC`; radius 8 px; padding 12–16 px.
- Fonte Inter 16 px; placeholder `#94A3B8`.
- Normal: borda cinza claro; focus: borda azul `#0878E8`; erro: borda vermelha e explicação; sucesso: confirmação; disabled: fundo cinza claro.
- Campos possíveis: nome, telefone, e-mail, veículo de interesse, faixa de preço, forma de pagamento e mensagem.

## 6. Cards e componentes reutilizáveis

### Card de veículo
- Imagem; marca/modelo; ano; quilometragem; transmissão; preço; etiqueta de status; botão de detalhes.
- Imagens com proporção consistente; card equilibrado; preço em destaque; CTA no rodapé; hover com elevação discreta.

### Cards de benefícios
- Compra à vista; financiamento; parcelamento; atendimento.

### Outros componentes
| Componente | Aplicação |
|---|---|
| Header | Navegação principal |
| Footer | Contatos e informações institucionais |
| Vehicle Card | Catálogo de veículos |
| Search Bar | Pesquisa de veículos |
| Filter Panel | Filtros de busca |
| Breadcrumb | Localização dentro do site |
| Badge | Novo, seminovo, vendido |
| Modal | Avisos e confirmações |
| Alert | Erro, aviso e sucesso |
| WhatsApp Button | Atendimento rápido |
| Pagination | Navegação de resultados |
| Empty State | Nenhum veículo encontrado |
| Loading | Carregamento de conteúdo |

## 7. Bordas, sombras e espaçamentos

### Bordas
| Elemento | Radius |
|---|---:|
| Inputs | 8 px |
| Botões | 8 px |
| Cards | 12 px |
| Imagens | 12 px |
| Modais | 16 px |
| Badges | 20 px ou pill |

### Sombras
| Token | Valor |
|---|---|
| Shadow Small | `0 2px 6px rgba(16,47,120,0.08)` |
| Shadow Medium | `0 4px 16px rgba(16,47,120,0.12)` |
| Shadow Large | `0 12px 32px rgba(16,47,120,0.18)` |

### Espaçamento (base 4 px)
| Token | Valor |
|---|---:|
| XS | 4 px |
| SM | 8 px |
| MD | 12 px |
| BASE | 16 px |
| LG | 24 px |
| XL | 32 px |
| 2XL | 48 px |
| 3XL | 64 px |
| 4XL | 80 px |

Uso recomendado: padding interno de componentes 16–24 px; distância entre cards 24 px; entre seções 48–80 px; padding de página 24 px desktop e 16 px mobile.

## 8. Responsividade

| Dispositivo | Largura | Comportamento |
|---|---|---|
| Mobile | 320–767 px | Uma coluna |
| Tablet | 768–1023 px | Duas colunas |
| Desktop | 1024–1439 px | Layout completo |
| Large desktop | 1440 px+ | Conteúdo centralizado |

### Mobile
- Menu hambúrguer; cards em uma coluna ou carrossel; botões em largura adequada; filtros em modal/painel expansível; textos proporcionais; WhatsApp flutuante; imagens sem distorção.

### Tablet
- Catálogo em duas colunas; filtros compactos; menu adaptado; espaçamentos intermediários.

### Desktop
- Catálogo em três ou quatro colunas; filtros laterais ou superiores; navegação horizontal; conteúdo centralizado com largura máxima; banners amplos.

## 9. Componentes globais e uso por página

Componentes globais: Logo Ford Regivel; Header; menu principal; WhatsApp; botões; card de veículo; card de benefício; filtros; pesquisa; formulários; alertas; footer; breadcrumb; modal; paginação.

| Página | Componentes |
|---|---|
| Home | Header, banner, cards de veículos, benefícios, CTA, footer |
| Catálogo | Header, filtros, pesquisa, cards, paginação, footer |
| Detalhes do veículo | Header, galeria, dados, preço, CTA, footer |
| Financiamento | Header, cards, formulário, CTA, footer |
| Sobre | Header, conteúdo institucional, imagens, footer |
| Contato | Header, formulário, contato, mapa se aplicável, footer |
| Privacidade | Header, textos, footer |
| Painel administrativo | Header interno, formulários, tabela, modal, alertas |

Estrutura global: Header (logo/menu) → breadcrumb (quando necessário) → conteúdo da página → CTA “Fale com um vendedor” → Footer (contatos, redes sociais e links institucionais).

## 10. Tokens CSS

```css
:root {
  /* Cores */
  --color-primary: #102F78;
  --color-secondary: #0878E8;
  --color-background: #F2F5FA;
  --color-dark: #17243A;
  --color-white: #FFFFFF;
  --color-silver: #C5CAD3;
  --color-success: #16A34A;
  --color-error: #DC2626;
  --color-warning: #F59E0B;
  --color-border: #DCE2EC;
  --color-text-secondary: #64748B;

  /* Tipografia */
  --font-heading: "Montserrat", sans-serif;
  --font-body: "Inter", sans-serif;
  --font-size-xs: 12px;
  --font-size-sm: 14px;
  --font-size-base: 16px;
  --font-size-lg: 18px;
  --font-size-xl: 22px;
  --font-size-2xl: 26px;
  --font-size-3xl: 32px;
  --font-size-4xl: 40px;

  /* Bordas */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 16px;
  --radius-pill: 999px;

  /* Espaçamento */
  --spacing-1: 4px;
  --spacing-2: 8px;
  --spacing-3: 12px;
  --spacing-4: 16px;
  --spacing-6: 24px;
  --spacing-8: 32px;
  --spacing-12: 48px;
  --spacing-16: 64px;
  --spacing-20: 80px;

  /* Sombras */
  --shadow-sm: 0 2px 6px rgba(16,47,120,0.08);
  --shadow-md: 0 4px 16px rgba(16,47,120,0.12);
  --shadow-lg: 0 12px 32px rgba(16,47,120,0.18);

  /* Layout */
  --container-max: 1200px;
  --transition-default: 200ms ease;
}
```


## 11. Configuração de referência Tailwind CSS

```js
/** @type {import('tailwindcss').Config} */
export default {
  theme: {
    extend: {
      colors: {
        regivel: {
          primary: "#102F78",
          secondary: "#0878E8",
          background: "#F2F5FA",
          dark: "#17243A",
          white: "#FFFFFF",
          silver: "#C5CAD3",
        },
      },
      fontFamily: {
        heading: ["Montserrat", "sans-serif"],
        body: ["Inter", "sans-serif"],
      },
      borderRadius: {
        regivel: "8px",
        card: "12px",
        modal: "16px",
      },
      boxShadow: {
        regivel: "0 4px 16px rgba(16,47,120,0.12)",
      },
      maxWidth: {
        container: "1200px",
      },
    },
  },
};
```

## 12. Diretrizes da identidade visual

### Fazer
- Usar azuis institucionais em elementos de destaque.
- Manter consistência em botões, cards e menus.
- Utilizar fotos reais dos veículos disponíveis.
- Priorizar contraste e legibilidade.
- Aplicar Montserrat e Inter conforme a hierarquia.
- Manter layout limpo, moderno e profissional.

### Evitar
- Cores fora da identidade sem necessidade funcional.
- Sombras excessivamente fortes.
- Muitos estilos de botão diferentes.
- Misturar famílias tipográficas.
- Animações exageradas.
- Páginas sobrecarregadas.
- Alterar, distorcer ou recriar a logo sem autorização.

## 13. Resultado esperado

O site deve transmitir confiança, modernidade, presença automotiva e facilidade de uso. Todas as páginas devem parecer parte de um único sistema. Os visitantes devem reconhecer a marca, encontrar veículos, consultar preços e condições e entrar em contato com facilidade.

Este documento é a referência visual e técnica para criação dos wireframes, protótipos, componentes de interface e desenvolvimento do site Ford Regivel.
