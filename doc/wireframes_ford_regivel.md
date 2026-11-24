# Planejamento de Wireframes – Site Institucional Ford Regivel

**Projeto:** Ford Regivel  
**Tipo:** Site institucional e comercial  
**Entrega:** Planejamento de wireframes de baixa fidelidade  
**Base:** Arquitetura da Informação – Site Institucional Ford Regivel

---

## Objetivo do planejamento

Este documento descreve a disposição dos elementos das páginas do site Ford Regivel. Os wireframes são esquemáticos e servem como referência para desenhar as telas no papel ou reproduzi-las em uma ferramenta de prototipação, como Figma.

Nesta etapa:

- Não são definidas cores, tipografias ou estilos visuais.
- Os retângulos representam imagens, cartões, campos ou áreas de conteúdo.
- Os textos entre colchetes são indicações do conteúdo que deverá ocupar cada espaço.
- A estrutura deve ser adaptada para desktop, tablet e celular.
- As fotografias dos veículos deverão ser reais e corresponder aos automóveis anunciados.

## Visão geral das telas

### Área pública
1. Início
2. Veículos – catálogo
3. Detalhes do veículo
4. Financiamento
5. Formas de pagamento
6. Sobre nós
7. Contato
8. Política de privacidade

### Área administrativa
9. Login administrativo
10. Painel administrativo
11. Gerenciar veículos
12. Cadastrar veículo
13. Editar veículo
14. Gerenciar estoque

---

# Parte 1 – Área pública

## 1. Página inicial

**Objetivo:** apresentar a Ford Regivel e encaminhar o visitante para o catálogo, ofertas ou atendimento.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│                                                                      │
│                    [BANNER / FOTO DE VEÍCULO]                        │
│              [Título de apresentação da empresa]                    │
│                    [Texto breve de apoio]                            │
│                     [BOTÃO: Ver veículos]                            │
│                                                                      │
├──────────────────────────────────────────────────────────────────────┤
│                    [BUSCA DE VEÍCULOS]                               │
│        [Marca ou modelo________] [BOTÃO: Pesquisar]                  │
├──────────────────────────────────────────────────────────────────────┤
│                       VEÍCULOS EM DESTAQUE                           │
│   ┌────────────────┐  ┌────────────────┐  ┌────────────────┐         │
│   │ [FOTO VEÍCULO] │  │ [FOTO VEÍCULO] │  │ [FOTO VEÍCULO] │         │
│   │ Modelo / ano   │  │ Modelo / ano   │  │ Modelo / ano   │         │
│   │ Preço          │  │ Preço          │  │ Preço          │         │
│   │ [Ver detalhes] │  │ [Ver detalhes] │  │ [Ver detalhes] │         │
│   └────────────────┘  └────────────────┘  └────────────────┘         │
│                       [BOTÃO: Ver todos]                             │
├──────────────────────────────────────────────────────────────────────┤
│                    CONDIÇÕES COMERCIAIS                              │
│       [Bloco: Financiamento]       [Bloco: Pagamento à vista]        │
│       [Texto breve]                [Texto breve]                     │
│       [Saiba mais]                 [Consultar condições]             │
├──────────────────────────────────────────────────────────────────────┤
│                  SOBRE A FORD REGIVEL                                │
│   [FOTO INSTITUCIONAL]       [Texto de apresentação]                 │
│                              [BOTÃO: Sobre nós]                      │
├──────────────────────────────────────────────────────────────────────┤
│             [CHAMADA PARA CONTATO / WHATSAPP]                        │
│                  [BOTÃO: Falar com vendedor]                         │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: logomarca | contato | redes sociais | links | privacidade    │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** logomarca à esquerda e menu principal em uma única linha. O acesso ao contato deve permanecer fácil de localizar.
2. **Conteúdo e seções:** banner principal; busca rápida; veículos em destaque; condições comerciais; apresentação institucional; chamada final para contato.
3. **Botões:** “Ver veículos” no banner; “Pesquisar” junto ao campo de busca; “Ver detalhes” em cada cartão; chamadas para financiamento e contato ao final das respectivas seções.
4. **Imagens:** uma imagem principal de veículo no banner; uma fotografia por cartão de veículo; uma imagem institucional na seção sobre a empresa.
5. **Rodapé:** logomarca, canais de contato, redes sociais e links institucionais, incluindo política de privacidade.
6. **Mobile:** menu recolhido em botão; banner em coluna; busca em largura total; cartões de veículos empilhados ou em carrossel horizontal; seções em coluna; botão de WhatsApp acessível sem encobrir conteúdo.

---

## 2. Página de veículos – catálogo

**Objetivo:** permitir que o visitante pesquise, filtre e compare visualmente as opções disponíveis.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│ INÍCIO > VEÍCULOS                                                    │
│                         VEÍCULOS DISPONÍVEIS                         │
│                                                                      │
│ ┌──────────────────────┐  ┌───────────────────────────────────────┐  │
│ │ FILTROS              │  │ [BUSCA: marca ou modelo____] [Buscar] │  │
│ │                      │  │                                       │  │
│ │ Preço                │  │ ┌──────────────┐  ┌──────────────┐     │  │
│ │ [mínimo] [máximo]    │  │ │ [FOTO]       │  │ │ [FOTO]      │     │  │
│ │                      │  │ │ Modelo / ano │  │ │ Modelo / ano│     │  │
│ │ Ano                  │  │ │ Km / câmbio  │  │ │ Km / câmbio │     │  │
│ │ [Selecionar]         │  │ │ Preço        │  │ │ Preço       │     │  │
│ │                      │  │ │ [Detalhes]   │  │ │ [Detalhes]  │     │  │
│ │ Modelo               │  │ └──────────────┘  └──────────────┘     │  │
│ │ [Selecionar]         │  │                                       │  │
│ │                      │  │ ┌──────────────┐  ┌──────────────┐     │  │
│ │ Categoria            │  │ │ [FOTO]       │  │ │ [FOTO]      │     │  │
│ │ [Selecionar]         │  │ │ Modelo / ano │  │ │ Modelo / ano│     │  │
│ │                      │  │ │ Km / câmbio  │  │ │ Km / câmbio │     │  │
│ │ [Aplicar filtros]    │  │ │ Preço        │  │ │ Preço       │     │  │
│ │ [Limpar filtros]     │  │ │ [Detalhes]   │  │ │ [Detalhes]  │     │  │
│ └──────────────────────┘  │ └──────────────┘  └──────────────┘     │  │
│                           │             [Paginação]                 │  │
│                           └───────────────────────────────────────┘  │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** mesmo cabeçalho público da página inicial, com acesso ao catálogo.
2. **Conteúdo e seções:** indicação de localização (breadcrumb), título, área de filtros e resultados em cartões.
3. **Botões:** “Pesquisar” junto à busca; “Aplicar filtros” e “Limpar filtros” no painel lateral; “Ver detalhes” em cada cartão; paginação abaixo dos resultados.
4. **Imagens:** cada cartão deve conter uma fotografia real do veículo, em proporção e tamanho consistentes.
5. **Rodapé:** padrão das páginas públicas.
6. **Mobile:** filtros devem abrir em painel ou seção expansível; busca ocupa a largura disponível; cartões aparecem em uma coluna; controles de paginação e botões devem ser fáceis de tocar.

---

## 3. Página de detalhes do veículo

**Objetivo:** apresentar as características do automóvel e incentivar o contato comercial.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│ INÍCIO > VEÍCULOS > [MODELO DO VEÍCULO]                              │
│                                                                      │
│ ┌─────────────────────────────────────┐  ┌────────────────────────┐ │
│ │                                     │  │ [Marca e modelo]       │ │
│ │       [FOTO PRINCIPAL DO CARRO]     │  │ Ano / versão           │ │
│ │                                     │  │ Preço                  │ │
│ │                                     │  │ Disponibilidade        │ │
│ ├──────────┬──────────┬──────────┬─────┤  │                        │ │
│ │ [Foto 2] │ [Foto 3] │ [Foto 4] │ ... │  │ [Tenho interesse]     │ │
│ └──────────┴──────────┴──────────┴─────┘  │ [WhatsApp]             │ │
│                                          │ [Consultar financiamento]│
│                                          └────────────────────────┘ │
├──────────────────────────────────────────────────────────────────────┤
│                         DESCRIÇÃO DO VEÍCULO                         │
│ [Texto descritivo do automóvel]                                      │
├──────────────────────────────────────────────────────────────────────┤
│                       INFORMAÇÕES DO VEÍCULO                         │
│ ┌──────────────────┐ ┌──────────────────┐ ┌──────────────────┐       │
│ │ Ano              │ │ Quilometragem    │ │ Cor              │       │
│ │ [Informação]     │ │ [Informação]     │ │ [Informação]     │       │
│ └──────────────────┘ └──────────────────┘ └──────────────────┘       │
│ ┌──────────────────┐ ┌──────────────────┐                            │
│ │ Câmbio           │ │ Condições        │                            │
│ │ [Informação]     │ │ [Pagamento]      │                            │
│ └──────────────────┘ └──────────────────┘                            │
├──────────────────────────────────────────────────────────────────────┤
│              [CHAMADA: Fale com um vendedor]                         │
│                       [BOTÃO: WhatsApp]                              │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho público padrão; breadcrumb abaixo para indicar o caminho de navegação.
2. **Conteúdo e seções:** galeria e resumo comercial lado a lado; descrição; características técnicas; condições de pagamento; chamada final para atendimento.
3. **Botões:** “Tenho interesse”, “WhatsApp” e “Consultar financiamento” próximos ao preço e à disponibilidade; botão de retorno ao catálogo pode ficar junto ao breadcrumb.
4. **Imagens:** foto principal em destaque, miniaturas abaixo ou ao lado; seleção de miniatura atualiza a foto principal.
5. **Rodapé:** padrão público.
6. **Mobile:** foto principal primeiro, miniaturas em faixa horizontal; nome, preço e CTAs logo abaixo; características em lista ou cartões empilhados; considerar botão de contato fixo na parte inferior sem cobrir informações.

---

## 4. Página de financiamento

**Objetivo:** explicar o processo de financiamento e levar o visitante a solicitar atendimento ou simulação.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│                    [TÍTULO: FINANCIAMENTO]                           │
│             [Texto introdutório sobre financiamento]                │
├──────────────────────────────────────────────────────────────────────┤
│ ┌──────────────────────────────┐  ┌────────────────────────────────┐ │
│ │ [IMAGEM ILUSTRATIVA /        │  │ COMO FUNCIONA                  │ │
│ │  FOTO DE VEÍCULO]            │  │ [Explicação em etapas ou texto]│ │
│ └──────────────────────────────┘  └────────────────────────────────┘ │
├──────────────────────────────────────────────────────────────────────┤
│                    INFORMAÇÕES IMPORTANTES                           │
│       [Análise de crédito] [Entrada e parcelas] [Aprovação]           │
│       [Texto explicativo em cada bloco]                               │
├──────────────────────────────────────────────────────────────────────┤
│                   SOLICITE UMA SIMULAÇÃO                             │
│          [Nome____________________________]                           │
│          [Telefone________________________]                           │
│          [Veículo de interesse____________]                           │
│                       [Solicitar simulação]                           │
│                    [Falar com consultor]                              │
│       [Aviso: sujeito à análise e aprovação financeira]               │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho público padrão.
2. **Conteúdo e seções:** título e introdução; explicação de como funciona; informações sobre análise, entrada e parcelas; área de solicitação de simulação.
3. **Botões:** “Solicitar simulação” após os campos; “Falar com consultor” como alternativa de contato; “Ver veículos” pode aparecer ao final.
4. **Imagens:** uma imagem de veículo ou atendimento, posicionada ao lado da explicação em desktop.
5. **Rodapé:** padrão público.
6. **Mobile:** imagem acima do texto; etapas em coluna; formulário com campos de largura total; botões empilhados; aviso de aprovação próximo ao formulário.

**Nota:** a página deve deixar claro que uma solicitação não garante aprovação de crédito.

---

## 5. Página de formas de pagamento

**Objetivo:** apresentar as modalidades de pagamento informadas pela empresa.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│                  [TÍTULO: FORMAS DE PAGAMENTO]                       │
│              [Texto breve de apresentação]                           │
├──────────────────────────────────────────────────────────────────────┤
│ ┌────────────────────────────┐  ┌──────────────────────────────────┐ │
│ │ PAGAMENTO À VISTA          │  │ PARCELAMENTO                     │ │
│ │ [Imagem/ícone ilustrativo] │  │ [Imagem/ícone ilustrativo]       │ │
│ │ [Texto explicativo]        │  │ [Texto explicativo]              │ │
│ │ [Consultar condições]      │  │ [Consultar condições]            │ │
│ └────────────────────────────┘  └──────────────────────────────────┘ │
├──────────────────────────────────────────────────────────────────────┤
│                    COMO CONSULTAR AS CONDIÇÕES                       │
│                  [Texto explicativo breve]                            │
│                  [BOTÃO: Falar com vendedor]                          │
├──────────────────────────────────────────────────────────────────────┤
│                    ENCONTRE SEU VEÍCULO                              │
│                  [BOTÃO: Ver veículos]                                │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho público padrão.
2. **Conteúdo e seções:** título; dois blocos principais para pagamento à vista e parcelamento; orientação para consultar condições; chamada para o catálogo.
3. **Botões:** “Consultar condições” em cada modalidade; “Falar com vendedor” após as explicações; “Ver veículos” ao final.
4. **Imagens:** imagens ou ícones ilustrativos discretos para cada modalidade, sem competir com as informações.
5. **Rodapé:** padrão público.
6. **Mobile:** os blocos de pagamento ficam empilhados; textos e botões ocupam a largura disponível; manter a chamada de contato próxima das condições.

---

## 6. Página sobre nós

**Objetivo:** apresentar a empresa, sua atuação e seus serviços para transmitir confiança.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│                         [TÍTULO: SOBRE NÓS]                          │
│                                                                      │
│ ┌────────────────────────────────┐  ┌──────────────────────────────┐ │
│ │                                │  │ APRESENTAÇÃO DA EMPRESA      │ │
│ │     [FOTO DA EMPRESA /         │  │ [Texto institucional]        │ │
│ │      CONCESSIONÁRIA]           │  │ [História, se fornecida]     │ │
│ │                                │  │                              │ │
│ └────────────────────────────────┘  └──────────────────────────────┘ │
├──────────────────────────────────────────────────────────────────────┤
│                         NOSSA ATUAÇÃO                                │
│             [Texto sobre venda e serviços oferecidos]                │
├──────────────────────────────────────────────────────────────────────┤
│                         DIFERENCIAIS                                 │
│       [Diferencial 1]       [Diferencial 2]       [Diferencial 3]     │
│       [Descrição]           [Descrição]           [Descrição]         │
├──────────────────────────────────────────────────────────────────────┤
│                 [FOTO INSTITUCIONAL SECUNDÁRIA, SE HOUVER]            │
│                   [BOTÃO: Conhecer veículos]                          │
│                   [BOTÃO: Entrar em contato]                          │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho público padrão.
2. **Conteúdo e seções:** título; apresentação com imagem e texto; área de atuação; serviços; diferenciais; chamadas para catálogo e contato.
3. **Botões:** “Conhecer veículos” e “Entrar em contato” na parte final da página.
4. **Imagens:** fotografia real da empresa, fachada, equipe ou showroom, caso fornecida; imagem secundária opcional.
5. **Rodapé:** padrão público.
6. **Mobile:** imagem antes do texto; diferenciais em coluna; CTAs empilhados; evitar blocos longos de texto sem subtítulos.

---

## 7. Página de contato

**Objetivo:** facilitar o contato entre visitantes e vendedores por formulário, WhatsApp ou canais informados pela empresa.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│                         [TÍTULO: CONTATO]                            │
│                 [Texto breve de orientação]                          │
├──────────────────────────────────────────────────────────────────────┤
│ ┌────────────────────────────────────┐ ┌────────────────────────────┐│
│ │ FORMULÁRIO DE CONTATO              │ │ FALE COM A FORD REGIVEL    ││
│ │                                    │ │                            ││
│ │ Nome [________________________]    │ │ WhatsApp                   ││
│ │ E-mail [______________________]    │ │ [Número / informação]      ││
│ │ Telefone [___________________]     │ │ [BOTÃO: Conversar]         ││
│ │ Assunto [____________________]     │ │                            ││
│ │ Mensagem [___________________]     │ │ Redes sociais              ││
│ │          [___________________]     │ │ [Links / identificações]   ││
│ │                                    │ │                            ││
│ │          [Enviar mensagem]         │ │ Endereço                   ││
│ └────────────────────────────────────┘ │ [Endereço, se fornecido]   ││
│                                        └────────────────────────────┘│
├──────────────────────────────────────────────────────────────────────┤
│                         LOCALIZAÇÃO                                  │
│                 [MAPA / ESPAÇO PARA MAPA]                            │
│                 [Endereço, se fornecido]                              │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho público padrão.
2. **Conteúdo e seções:** introdução; formulário em uma coluna; dados de contato em outra; localização em seção inferior.
3. **Botões:** “Enviar mensagem” abaixo do formulário; “Conversar” junto ao WhatsApp; link ou botão para abrir a localização, se houver endereço.
4. **Imagens:** não exige imagem promocional; reservar área para mapa quando a localização estiver disponível.
5. **Rodapé:** padrão público.
6. **Mobile:** formulário e informações de contato empilhados; campos de largura total; botão de envio após a mensagem; mapa em largura total e altura adequada.

---

## 8. Página de política de privacidade

**Objetivo:** apresentar as informações sobre coleta, uso e proteção dos dados pessoais.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA       Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
├──────────────────────────────────────────────────────────────────────┤
│                    [TÍTULO: POLÍTICA DE PRIVACIDADE]                 │
│                    [Data da última atualização]                      │
├──────────────────────────────────────────────────────────────────────┤
│ ┌──────────────────────┐  ┌───────────────────────────────────────┐  │
│ │ NESTA PÁGINA         │  │ 1. INTRODUÇÃO                         │  │
│ │ [Links de seção]     │  │ [Texto da política]                   │  │
│ │                      │  │                                       │  │
│ │ Dados coletados      │  │ 2. DADOS COLETADOS                    │  │
│ │ Finalidade            │  │ [Texto da política]                   │  │
│ │ Uso das informações  │  │                                       │  │
│ │ Proteção dos dados   │  │ 3. FINALIDADE E USO                   │  │
│ │ Direitos do usuário  │  │ [Texto da política]                   │  │
│ │ Contato              │  │                                       │  │
│ └──────────────────────┘  │ 4. PROTEÇÃO DOS DADOS                  │  │
│                           │ [Texto da política]                   │  │
│                           │                                       │  │
│                           │ 5. DIREITOS DOS USUÁRIOS               │  │
│                           │ [Texto da política]                   │  │
│                           │                                       │  │
│                           │ 6. CONTATO                             │  │
│                           │ [Canal de contato]                     │  │
│                           └───────────────────────────────────────┘  │
├──────────────────────────────────────────────────────────────────────┤
│ RODAPÉ: contato | redes sociais | links institucionais               │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho público padrão.
2. **Conteúdo e seções:** título, data de atualização, índice de tópicos opcional e texto dividido em seções com subtítulos.
3. **Botões:** links do índice levam à seção correspondente; link de contato ao final para dúvidas.
4. **Imagens:** não são necessárias imagens; priorizar leitura e organização textual.
5. **Rodapé:** padrão público.
6. **Mobile:** índice pode ser recolhível; texto em uma coluna; espaçamento confortável entre seções; links fáceis de tocar.

---

# Parte 2 – Área administrativa

A área administrativa é restrita à equipe autorizada. Não utiliza o menu público. As telas abaixo priorizam tarefas de cadastro, edição e atualização de estoque.

## 9. Login administrativo

**Objetivo:** permitir que somente administradores autorizados acessem o painel.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│                                                                      │
│                    [LOGOMARCA FORD REGIVEL]                          │
│                                                                      │
│                    ACESSO ADMINISTRATIVO                             │
│                                                                      │
│                 E-mail [____________________]                       │
│                 Senha  [____________________]                       │
│                                                                      │
│                      [BOTÃO: Entrar]                                 │
│                                                                      │
│                   [Mensagem de erro, se houver]                      │
│                                                                      │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** não utiliza o menu público; apresentar apenas a identificação da Ford Regivel e da área administrativa.
2. **Conteúdo e seções:** formulário de autenticação centralizado, com identificação, e-mail, senha e espaço para mensagens de validação.
3. **Botões:** “Entrar” abaixo dos campos; feedback de erro próximo ao formulário.
4. **Imagens:** apenas logomarca institucional, se disponível.
5. **Rodapé:** mínimo, com identificação institucional ou informação de suporte, se definida.
6. **Mobile:** formulário centralizado em coluna; campos e botão em largura total; teclado adequado ao tipo de campo.

---

## 10. Painel administrativo

**Objetivo:** oferecer uma visão geral e acesso rápido às funções administrativas.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA / ADMINISTRAÇÃO                       [Usuário] [Sair]     │
├───────────────────┬──────────────────────────────────────────────────┤
│ MENU LATERAL      │ PAINEL ADMINISTRATIVO                            │
│                   │                                                  │
│ [Visão geral]     │ ┌──────────────┐ ┌──────────────┐ ┌────────────┐│
│ [Veículos]        │ │ Cadastrados  │ │ Disponíveis  │ │Indisponíveis│
│ [Estoque]         │ │ [Número]     │ │ [Número]     │ │ [Número]   ││
│                   │ └──────────────┘ └──────────────┘ └────────────┘│
│                   │                                                  │
│                   │ AÇÕES RÁPIDAS                                    │
│                   │ [Cadastrar veículo] [Gerenciar veículos]        │
│                   │ [Gerenciar estoque]                              │
│                   │                                                  │
│                   │ ATIVIDADE / LISTA RESUMIDA                       │
│                   │ [Veículo] [Situação] [Última atualização]        │
│                   │ [Veículo] [Situação] [Última atualização]        │
│                   │                                                  │
└───────────────────┴──────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** identificação da área administrativa, usuário conectado e ação de sair.
2. **Conteúdo e seções:** menu lateral; título da página; indicadores de veículos cadastrados, disponíveis e indisponíveis; ações rápidas; resumo de atividade.
3. **Botões:** atalhos para cadastrar, gerenciar veículos e gerenciar estoque, posicionados após os indicadores.
4. **Imagens:** miniaturas de veículos podem aparecer na lista resumida, se ajudarem a identificar os registros.
5. **Rodapé:** não precisa repetir o rodapé público; manter apenas informações administrativas essenciais.
6. **Mobile:** menu lateral vira menu recolhível; indicadores empilhados ou em grade compacta; ações rápidas em botões de largura total; tabelas podem permitir rolagem horizontal ou virar cartões.

---

## 11. Gerenciar veículos

**Objetivo:** visualizar os veículos cadastrados e acessar as ações de cadastro, edição e remoção.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA / ADMINISTRAÇÃO                       [Usuário] [Sair]     │
├───────────────────┬──────────────────────────────────────────────────┤
│ MENU LATERAL      │ GERENCIAR VEÍCULOS                              │
│ [Visão geral]     │                                                  │
│ [Veículos]        │ [BOTÃO: Cadastrar veículo]                      │
│ [Estoque]         │                                                  │
│                   │ [Buscar por marca ou modelo________] [Pesquisar] │
│                   │                                                  │
│                   │ ┌───────┬─────────────┬────────┬────────┬───────┐│
│                   │ │ Foto  │ Veículo     │ Preço  │Status  │Ações  ││
│                   │ ├───────┼─────────────┼────────┼────────┼───────┤│
│                   │ │[Foto] │ Modelo / ano│ Valor  │Ativo   │Editar ││
│                   │ │[Foto] │ Modelo / ano│ Valor  │Vendido │Editar ││
│                   │ │[Foto] │ Modelo / ano│ Valor  │Inativo │Editar ││
│                   │ └───────┴─────────────┴────────┴────────┴───────┘│
│                   │             [Paginação]                          │
└───────────────────┴──────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho administrativo com usuário e opção de sair.
2. **Conteúdo e seções:** menu lateral; título; botão de cadastro; busca; tabela de veículos com foto, identificação, preço, status e ações.
3. **Botões:** “Cadastrar veículo” no topo; “Editar” e “Remover” em cada linha, com confirmação antes de remover.
4. **Imagens:** miniaturas pequenas na tabela para reconhecimento dos veículos.
5. **Rodapé:** mínimo ou inexistente, conforme padrão administrativo.
6. **Mobile:** busca em largura total; botão de cadastro em destaque; registros apresentados como cartões com dados e ações; evitar tabela espremida.

---

## 12. Cadastrar veículo

**Objetivo:** permitir que o administrador registre um novo automóvel no catálogo.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA / ADMINISTRAÇÃO                       [Usuário] [Sair]     │
├───────────────────┬──────────────────────────────────────────────────┤
│ MENU LATERAL      │ CADASTRAR VEÍCULO                               │
│ [Visão geral]     │                                                  │
│ [Veículos]        │ INFORMAÇÕES DO VEÍCULO                           │
│ [Estoque]         │ Marca [________________] Modelo [_____________]  │
│                   │ Ano [________] Quilometragem [_______________]   │
│                   │ Cor [________] Câmbio [______________________]   │
│                   │                                                  │
│                   │ DESCRIÇÃO                                        │
│                   │ [____________________________________________]  │
│                   │ [____________________________________________]  │
│                   │                                                  │
│                   │ PREÇO E PAGAMENTO                                │
│                   │ Preço [________________]                         │
│                   │ Condições [__________________________________]  │
│                   │                                                  │
│                   │ FOTOGRAFIAS                                      │
│                   │ [Adicionar imagens]                              │
│                   │ ┌──────────┐ ┌──────────┐ ┌──────────┐           │
│                   │ │[Prévia 1]│ │[Prévia 2]│ │[Prévia 3]│           │
│                   │ └──────────┘ └──────────┘ └──────────┘           │
│                   │                                                  │
│                   │ [Cancelar]                 [Salvar / Publicar]   │
└───────────────────┴──────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho administrativo padrão.
2. **Conteúdo e seções:** formulário dividido em informações do veículo, descrição, preço e pagamento, fotografias e disponibilidade.
3. **Botões:** “Salvar / Publicar” no final do formulário; “Cancelar” ao lado. Exibir validações junto aos campos obrigatórios.
4. **Imagens:** área de envio com pré-visualização das fotos adicionadas; permitir identificar e remover imagens antes de salvar.
5. **Rodapé:** mínimo ou inexistente.
6. **Mobile:** formulário em uma coluna; campos em largura total; envio de fotos adaptado ao celular; botões empilhados ou lado a lado quando houver espaço.

---

## 13. Editar veículo

**Objetivo:** permitir que o administrador atualize os dados de um veículo já cadastrado.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA / ADMINISTRAÇÃO                       [Usuário] [Sair]     │
├───────────────────┬──────────────────────────────────────────────────┤
│ MENU LATERAL      │ EDITAR VEÍCULO                                  │
│ [Visão geral]     │                                                  │
│ [Veículos]        │ [Identificação do veículo selecionado]           │
│ [Estoque]         │                                                  │
│                   │ INFORMAÇÕES DO VEÍCULO                           │
│                   │ Marca [valor atual] Modelo [valor atual]         │
│                   │ Ano [valor atual] Quilometragem [valor atual]    │
│                   │ Cor [valor atual] Câmbio [valor atual]           │
│                   │                                                  │
│                   │ DESCRIÇÃO                                        │
│                   │ [Texto atual editável_________________________]  │
│                   │                                                  │
│                   │ PREÇO E PAGAMENTO                                │
│                   │ Preço [valor atual]                              │
│                   │ Condições [valor atual_______________________]  │
│                   │                                                  │
│                   │ FOTOGRAFIAS ATUAIS                               │
│                   │ [Foto 1] [Foto 2] [Foto 3] [Adicionar fotos]     │
│                   │                                                  │
│                   │ DISPONIBILIDADE [Selecionar situação]            │
│                   │                                                  │
│                   │ [Cancelar]                  [Salvar alterações]  │
└───────────────────┴──────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho administrativo padrão.
2. **Conteúdo e seções:** identificação do veículo; campos preenchidos com dados atuais; descrição; preço; fotografias; situação de disponibilidade.
3. **Botões:** “Salvar alterações” no final; “Cancelar” ao lado; ação de remover foto junto a cada miniatura, se necessária.
4. **Imagens:** exibir as fotografias já cadastradas e permitir adicionar ou substituir imagens.
5. **Rodapé:** mínimo ou inexistente.
6. **Mobile:** formulário em coluna; miniaturas em faixa horizontal; seletor de disponibilidade acessível; botão de salvar visível ao final.

---

## 14. Gerenciar estoque

**Objetivo:** permitir que o administrador acompanhe e atualize a disponibilidade dos veículos.

### Wireframe – Desktop

```text
┌──────────────────────────────────────────────────────────────────────┐
│ LOGOMARCA / ADMINISTRAÇÃO                       [Usuário] [Sair]     │
├───────────────────┬──────────────────────────────────────────────────┤
│ MENU LATERAL      │ GERENCIAR ESTOQUE                               │
│ [Visão geral]     │                                                  │
│ [Veículos]        │ [Todos] [Disponíveis] [Vendidos] [Indisponíveis]│
│ [Estoque]         │                                                  │
│                   │ [Buscar veículo____________________] [Pesquisar] │
│                   │                                                  │
│                   │ ┌────────┬─────────────┬──────────┬────────────┐│
│                   │ │ Foto   │ Veículo     │ Situação │ Ação       ││
│                   │ ├────────┼─────────────┼──────────┼────────────┤│
│                   │ │[Foto]  │ Modelo / ano│Disponível│[Marcar vendido]│
│                   │ │[Foto]  │ Modelo / ano│Vendido   │[Atualizar] ││
│                   │ │[Foto]  │ Modelo / ano│Indisponível│[Disponibilizar]│
│                   │ └────────┴─────────────┴──────────┴────────────┘│
│                   │                                                  │
│                   │ [Paginação]                                     │
└───────────────────┴──────────────────────────────────────────────────┘
```

### Organização e comportamento

1. **Cabeçalho:** cabeçalho administrativo padrão.
2. **Conteúdo e seções:** título; filtros por situação; busca; listagem de veículos com foto, nome, situação e ação disponível.
3. **Botões:** filtros no topo; ação de atualizar situação em cada registro; solicitar confirmação para alterações importantes.
4. **Imagens:** miniaturas pequenas para identificação visual.
5. **Rodapé:** mínimo ou inexistente.
6. **Mobile:** filtros em seletor ou abas roláveis; busca em largura total; veículos em cartões; ação de disponibilidade claramente associada a cada cartão.

---

# 3. Padrões compartilhados entre as páginas

## 3.1. Cabeçalho público

Manter a mesma estrutura nas oito páginas públicas:

```text
┌───────────────────────────────────────────────────────────────────┐
│ [LOGOMARCA]  Início  Veículos  Financiamento  Pagamento  Sobre  Contato │
└───────────────────────────────────────────────────────────────────┘
```

No celular, substituir os links horizontais por um botão de menu que abre e fecha a navegação. A logomarca permanece visível.

## 3.2. Rodapé público

Repetir a estrutura básica em todas as páginas públicas:

```text
┌───────────────────────────────────────────────────────────────────┐
│ [LOGOMARCA]                                                        │
│                                                                    │
│ CONTATO             NAVEGAÇÃO             REDES SOCIAIS             │
│ [Telefone]          [Início]              [Links]                   │
│ [WhatsApp]          [Veículos]                                      │
│ [Endereço]          [Sobre nós]                                     │
│                     [Contato]                                      │
│                                                                    │
│ [Política de privacidade]       [Informações institucionais]       │
└───────────────────────────────────────────────────────────────────┘
```

No celular, organizar as colunas verticalmente, mantendo os links agrupados por assunto.

## 3.3. Estrutura administrativa

As páginas administrativas compartilham:

- Cabeçalho com identificação da administração e usuário conectado.
- Menu lateral com visão geral, veículos e estoque.
- Área central para conteúdo e tarefas.
- Ações de sair e retorno ao painel.
- Layout adaptado para telas menores.

## 3.4. Comportamentos gerais de responsividade

- Reorganizar colunas em uma única coluna em telas estreitas.
- Não reduzir campos e botões a ponto de dificultar o toque.
- Manter títulos e ações principais próximos do conteúdo a que se referem.
- Permitir rolagem vertical natural.
- Transformar menus laterais em menus recolhíveis no painel administrativo.
- Garantir que imagens mantenham proporção e não cortem informações importantes.
- Evitar que botões fixos cubram campos, textos ou controles.

---

# 4. Orientações para montar os wireframes no Figma ou no papel

1. Criar uma tela ou folha para cada uma das 14 páginas.
2. Desenhar primeiro a versão desktop, definindo cabeçalho, conteúdo e rodapé.
3. Repetir os componentes compartilhados para manter consistência entre as páginas.
4. Criar uma versão mobile para cada página, reorganizando os elementos em coluna.
5. Utilizar retângulos para imagens, campos, cartões e áreas de conteúdo.
6. Utilizar linhas para representar textos e títulos.
7. Identificar os botões com seus rótulos reais, como “Ver veículos”, “Tenho interesse” e “Salvar alterações”.
8. Revisar se cada tela permite identificar rapidamente o objetivo da página e a ação principal.

## Sugestão de organização dos arquivos no Figma

```text
FORD REGIVEL – WIREFRAMES
├── 00 – Referências e componentes
├── 01 – Área pública / Desktop
│   ├── Início
│   ├── Veículos
│   ├── Detalhes do veículo
│   ├── Financiamento
│   ├── Formas de pagamento
│   ├── Sobre nós
│   ├── Contato
│   └── Política de privacidade
├── 02 – Área pública / Mobile
│   └── Repetir as oito páginas
└── 03 – Área administrativa
    ├── Login
    ├── Painel
    ├── Gerenciar veículos
    ├── Cadastrar veículo
    ├── Editar veículo
    └── Gerenciar estoque
```

---

# 5. Checklist de validação

- [ ] As 8 páginas públicas foram representadas.
- [ ] As 6 telas administrativas foram representadas.
- [ ] Todas as páginas públicas possuem acesso à navegação principal.
- [ ] As páginas públicas possuem estrutura de rodapé consistente.
- [ ] Os CTAs estão próximos das informações relacionadas.
- [ ] O catálogo apresenta pesquisa e filtros.
- [ ] O detalhe do veículo destaca fotos, preço e contato.
- [ ] Os formulários apresentam campos e ação de envio.
- [ ] As telas administrativas permitem localizar as ações de cadastro, edição e estoque.
- [ ] Existe planejamento de comportamento mobile para todas as telas.
- [ ] Não foram definidas cores ou tipografias nesta etapa.

---

## Resultado esperado

Ao concluir os wireframes, a equipe terá um planejamento visual de baixa fidelidade das 14 telas do site Ford Regivel. Esse material servirá como base para a próxima etapa: criação do protótipo de alta fidelidade, aplicação da identidade visual e validação da experiência de navegação.
