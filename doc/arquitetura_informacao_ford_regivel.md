# Arquitetura da Informação -- Site Institucional Ford Regivel

**Projeto:** Ford Regivel\
**Tipo:** Site institucional e comercial\
**Área:** Venda de veículos\
**Público-alvo:** Pessoas interessadas em comprar veículos novos ou
seminovos.\
**Objetivo principal:** Apresentar os veículos disponíveis, divulgar
condições comerciais e facilitar o contato entre clientes e vendedores.

A arquitetura abaixo foi desenvolvida com base no documento de
levantamento de requisitos enviado, priorizando uma navegação simples,
intuitiva, responsiva e direcionada à conversão de visitantes em
potenciais compradores.

------------------------------------------------------------------------

# 1. Identificação das páginas necessárias

O site será dividido em duas áreas principais:

-   **Área pública:** destinada aos clientes e visitantes.
-   **Área administrativa:** destinada aos responsáveis pelo
    gerenciamento dos veículos e do estoque.

## 1.1. Área pública

  -----------------------------------------------------------------------
  Página                              Finalidade
  ----------------------------------- -----------------------------------
  1\. Início                          Apresentar a empresa e destacar
                                      ofertas e veículos.

  2\. Veículos                        Exibir o catálogo de automóveis
                                      disponíveis.

  3\. Detalhes do veículo             Apresentar informações completas de
                                      cada automóvel.

  4\. Financiamento                   Explicar as possibilidades de
                                      financiamento.

  5\. Formas de pagamento             Apresentar opções de pagamento à
                                      vista e parcelamento.

  6\. Sobre nós                       Apresentar a Ford Regivel e sua
                                      atuação.

  7\. Contato                         Disponibilizar canais de
                                      atendimento e formulário.

  8\. Política de privacidade         Informar como os dados pessoais são
                                      utilizados.
  -----------------------------------------------------------------------

## 1.2. Área administrativa

  -----------------------------------------------------------------------
  Página                              Finalidade
  ----------------------------------- -----------------------------------
  9\. Login administrativo            Permitir o acesso dos
                                      administradores.

  10\. Painel administrativo          Apresentar as principais funções de
                                      gerenciamento.

  11\. Gerenciar veículos             Listar os veículos cadastrados.

  12\. Cadastrar veículo              Permitir adicionar novos
                                      automóveis.

  13\. Editar veículo                 Alterar informações dos automóveis.

  14\. Gerenciar estoque              Atualizar a disponibilidade dos
                                      veículos.
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 2. Hierarquia das páginas

A hierarquia organiza as informações de acordo com a importância e a
relação entre as páginas.

``` text
FORD REGIVEL
├── Área pública
│   ├── Início
│   ├── Veículos
│   │   ├── Catálogo de veículos
│   │   ├── Pesquisa e filtros
│   │   └── Detalhes do veículo
│   ├── Financiamento
│   ├── Formas de pagamento
│   ├── Sobre nós
│   ├── Contato
│   └── Política de privacidade
└── Área administrativa
    ├── Login administrativo
    └── Painel administrativo
        ├── Gerenciar veículos
        │   ├── Cadastrar veículo
        │   ├── Editar veículo
        │   └── Remover veículo
        └── Gerenciar estoque
            ├── Atualizar disponibilidade
            └── Marcar como vendido
```

------------------------------------------------------------------------

# 3. Definição dos menus e submenus

O menu principal deverá ser simples e permanecer visível no topo das
páginas.

## Menu principal

-   **Início:** página inicial.
-   **Veículos:** catálogo de veículos disponíveis.
-   **Financiamento:** informações e simulação por atendimento.
-   **Pagamento:** opções à vista e parcelamento.
-   **Sobre nós:** informações institucionais.
-   **Contato:** WhatsApp e formulário.

## Submenus

### Veículos

-   Todos os veículos.
-   Pesquisar por marca ou modelo.
-   Filtrar por preço, ano e categoria.
-   Acessar detalhes do veículo.

### Financiamento

-   Como funciona.
-   Solicitar simulação.
-   Falar com um vendedor.

### Pagamento

-   Compra à vista.
-   Parcelamento.
-   Consultar condições.

### Rodapé

-   Sobre a empresa.
-   Contato.
-   Redes sociais.
-   Política de privacidade.

O painel administrativo não deverá aparecer no menu público. Seu acesso
será restrito aos administradores.

------------------------------------------------------------------------

# 4. Descrição detalhada das páginas

## 4.1. Página inicial

**Objetivo:** Apresentar a Ford Regivel e direcionar os visitantes para
os veículos disponíveis.

**Conteúdo:** - Logomarca da Ford Regivel. - Menu de navegação. - Banner
principal com imagem de veículo. - Texto de apresentação da empresa. -
Veículos em destaque. - Ofertas e condições comerciais. - Atalho para
financiamento. - Informações de contato. - Rodapé com redes sociais.

**Principais CTAs:** - Ver veículos. - Conhecer ofertas. - Simular
financiamento. - Falar pelo WhatsApp.

## 4.2. Página de veículos

**Objetivo:** Permitir que os visitantes encontrem os automóveis
disponíveis.

**Conteúdo:** - Catálogo de veículos. - Fotografias dos automóveis. -
Marca e modelo. - Ano de fabricação. - Quilometragem. - Preço. - Campo
de pesquisa. - Filtros por preço, ano, modelo e categoria.

**Principais CTAs:** - Pesquisar veículo. - Aplicar filtros. - Ver
detalhes. - Consultar disponibilidade.

## 4.3. Página de detalhes do veículo

**Objetivo:** Apresentar todas as informações necessárias para que o
cliente avalie o automóvel.

**Conteúdo:** - Galeria de fotografias. - Marca e modelo. - Ano de
fabricação. - Quilometragem. - Cor. - Tipo de câmbio. - Descrição do
veículo. - Preço de venda. - Condições de pagamento. - Disponibilidade.

**Principais CTAs:** - Tenho interesse. - Consultar financiamento. -
Falar com vendedor pelo WhatsApp. - Voltar para os veículos.

## 4.4. Página de financiamento

**Objetivo:** Explicar as possibilidades de financiamento e incentivar o
contato comercial.

**Conteúdo:** - Explicação sobre financiamento. - Informações sobre
análise de crédito. - Possibilidades de entrada e parcelas, conforme
condições disponíveis. - Orientações para solicitar atendimento.

**Principais CTAs:** - Solicitar simulação. - Falar com um consultor. -
Ver veículos disponíveis.

> **Observação:** a aprovação do financiamento dependerá da instituição
> financeira responsável.

## 4.5. Página de formas de pagamento

**Objetivo:** Informar aos clientes as modalidades de pagamento
oferecidas pela empresa.

**Conteúdo:** - Compra à vista. - Possibilidades de parcelamento. -
Condições comerciais. - Orientações para consultar valores e
disponibilidade.

**Principais CTAs:** - Consultar condições. - Falar com vendedor. -
Escolher um veículo.

## 4.6. Página sobre nós

**Objetivo:** Apresentar a empresa e transmitir confiança aos
visitantes.

**Conteúdo:** - História da Ford Regivel, caso disponibilizada. -
Apresentação da empresa. - Área de atuação. - Serviços oferecidos. -
Fotografias institucionais. - Diferenciais comerciais.

**Principais CTAs:** - Conhecer veículos. - Entrar em contato.

## 4.7. Página de contato

**Objetivo:** Facilitar a comunicação entre clientes e vendedores.

**Conteúdo:** - Número de WhatsApp. - Endereço da empresa, quando
fornecido. - Localização. - Links das redes sociais. - Formulário de
contato com: - Nome. - E-mail. - Telefone. - Assunto. - Mensagem.

**Principais CTAs:** - Enviar mensagem. - Conversar pelo WhatsApp. - Ver
localização.

## 4.8. Política de privacidade

**Objetivo:** Informar como os dados pessoais dos visitantes serão
tratados.

**Conteúdo:** - Dados coletados. - Finalidade da coleta. - Utilização
das informações. - Proteção dos dados. - Direitos dos usuários. -
Informações sobre a LGPD.

**Principais CTAs:** - Voltar ao início. - Entrar em contato.

------------------------------------------------------------------------

# 5. Área administrativa

A área administrativa será utilizada exclusivamente pela equipe
responsável pela atualização do site.

## 5.1. Login administrativo

**Conteúdo:** - Campo de usuário ou e-mail. - Campo de senha. - Botão de
entrar.

**CTA:** Acessar painel.

## 5.2. Painel administrativo

**Conteúdo:** - Resumo de veículos cadastrados. - Veículos
disponíveis. - Veículos indisponíveis. - Atalhos de gerenciamento.

**CTAs:** - Cadastrar veículo. - Gerenciar veículos. - Atualizar
estoque.

## 5.3. Gerenciamento de veículos

**Conteúdo:** - Lista de veículos cadastrados. - Fotografias. - Nome e
modelo. - Preços. - Disponibilidade.

**CTAs:** - Adicionar veículo. - Editar. - Remover.

## 5.4. Cadastro e edição de veículos

**Conteúdo:** - Marca. - Modelo. - Ano. - Quilometragem. - Cor. -
Câmbio. - Descrição. - Preço. - Fotografias. - Condições de pagamento.

**CTAs:** - Salvar veículo. - Publicar veículo. - Cancelar alterações.

## 5.5. Gerenciamento de estoque

**Conteúdo:** - Veículos disponíveis. - Veículos vendidos. - Veículos
indisponíveis. - Atualização da situação de cada automóvel.

**CTAs:** - Marcar como disponível. - Marcar como vendido. - Atualizar
estoque.

------------------------------------------------------------------------

# 6. Fluxo de navegação do usuário

O fluxo principal deverá levar o visitante da página inicial até o
contato com um vendedor.

``` mermaid
flowchart TD
    A["Página inicial"] --> B["Página de veículos"]
    B --> C["Pesquisar e aplicar filtros"]
    C --> D["Detalhes do veículo"]
    D --> E["Consultar fotos, preço e características"]
    E --> F["Contato com vendedor"]
    F --> G["WhatsApp ou formulário de interesse"]
    G --> H["Atendimento comercial"]
```

O usuário também poderá acessar diretamente as páginas de financiamento,
pagamento, sobre nós e contato pelo menu principal.

------------------------------------------------------------------------

# 7. Principais botões e chamadas para ação (CTAs)

Os botões deverão utilizar textos objetivos, que deixem claro o que
acontecerá após o clique.

  -----------------------------------------------------------------------
  Localização             Botão ou CTA            Ação
  ----------------------- ----------------------- -----------------------
  Página inicial          Ver veículos            Abre o catálogo.

  Página inicial          Conhecer ofertas        Direciona aos veículos
                                                  em destaque.

  Catálogo                Pesquisar               Realiza a pesquisa.

  Catálogo                Aplicar filtros         Filtra os veículos.

  Catálogo                Ver detalhes            Abre a página
                                                  individual.

  Detalhes                Tenho interesse         Inicia contato
                                                  comercial.

  Detalhes                WhatsApp                Abre conversa com
                                                  vendedor.

  Financiamento           Solicitar simulação     Solicita atendimento.

  Pagamento               Consultar condições     Direciona ao
                                                  atendimento.

  Contato                 Enviar mensagem         Envia o formulário.

  Administrativo          Cadastrar veículo       Abre o cadastro.

  Administrativo          Salvar alterações       Salva os dados.
  -----------------------------------------------------------------------

**Recomendação de UX/UI:** utilizar azul como cor principal dos botões,
com textos brancos e bom contraste. O botão de WhatsApp poderá utilizar
a identidade visual própria do serviço para facilitar sua identificação.

------------------------------------------------------------------------

# 8. Mapa do site -- Sitemap em Mermaid

O diagrama abaixo apresenta a estrutura completa do site, incluindo a
área pública e a área administrativa.

``` mermaid
flowchart TD
    A["FORD REGIVEL"]

    A --> B["Área Pública"]
    A --> C["Área Administrativa"]

    B --> D["Início"]
    B --> E["Veículos"]
    B --> F["Financiamento"]
    B --> G["Formas de Pagamento"]
    B --> H["Sobre Nós"]
    B --> I["Contato"]
    B --> J["Política de Privacidade"]

    E --> E1["Catálogo de Veículos"]
    E1 --> E2["Pesquisa e Filtros"]
    E1 --> E3["Detalhes do Veículo"]
    E3 --> E4["Galeria de Fotos"]
    E3 --> E5["Informações e Preço"]
    E3 --> E6["Condições de Pagamento"]
    E3 --> E7["Interesse / WhatsApp"]

    F --> F1["Informações de Financiamento"]
    F --> F2["Solicitar Simulação"]
    G --> G1["Pagamento à Vista"]
    G --> G2["Parcelamento"]

    I --> I1["Formulário de Contato"]
    I --> I2["WhatsApp"]
    I --> I3["Endereço e Localização"]
    I --> I4["Redes Sociais"]

    C --> K["Login Administrativo"]
    K --> L["Painel Administrativo"]
    L --> M["Gerenciar Veículos"]
    L --> N["Gerenciar Estoque"]

    M --> M1["Cadastrar Veículo"]
    M --> M2["Editar Veículo"]
    M --> M3["Remover Veículo"]

    N --> N1["Atualizar Disponibilidade"]
    N --> N2["Marcar como Vendido"]
```

------------------------------------------------------------------------

# 9. Funcionalidades futuras

As funcionalidades abaixo não são essenciais para a primeira versão, mas
poderão melhorar a experiência do usuário em atualizações futuras.

  Funcionalidade               Benefício
  ---------------------------- ----------------------------------------
  Simulador de financiamento   Permitir estimativas de parcelas.
  Comparador de veículos       Facilitar a escolha entre automóveis.
  Favoritos                    Salvar veículos de interesse.
  Cadastro de clientes         Acompanhar solicitações.
  Avaliação de usados          Facilitar negociações de troca.
  Integração com CRM           Organizar oportunidades comerciais.
  Notificações                 Divulgar ofertas e novos veículos.
  Relatórios administrativos   Acompanhar resultados do site.
  Chat online                  Facilitar o atendimento em tempo real.

------------------------------------------------------------------------

# 10. Recomendações finais de UX/UI

Para garantir uma boa experiência de navegação, recomenda-se:

1.  **Menu simples:** manter as principais páginas acessíveis no topo.
2.  **Identidade visual:** utilizar azul e branco, respeitando a
    identidade da Ford Regivel.
3.  **Responsividade:** adaptar o site para celulares, tablets e
    computadores.
4.  **Imagens dos veículos:** utilizar fotografias reais dos automóveis
    cadastrados, evitando imagens geradas por IA que possam representar
    veículos diferentes dos anunciados.
5.  **Pesquisa eficiente:** permitir encontrar veículos rapidamente por
    marca, modelo, preço e ano.
6.  **Contato facilitado:** manter o botão de WhatsApp em local visível.
7.  **Informações organizadas:** apresentar preços, características e
    condições de pagamento de maneira clara.
8.  **Acessibilidade:** utilizar textos legíveis, contraste adequado e
    navegação acessível.
9.  **Segurança:** proteger os dados enviados pelos clientes e respeitar
    a LGPD.
10. **Atualização constante:** garantir que os veículos vendidos ou
    indisponíveis não sejam apresentados como disponíveis.

------------------------------------------------------------------------

# 11. Conclusão

A arquitetura da informação proposta para a Ford Regivel organiza o site
em duas áreas principais: pública e administrativa.

A área pública tem como prioridade apresentar os veículos, facilitar a
pesquisa e transformar visitantes em potenciais compradores. Já a área
administrativa permite que a empresa mantenha o catálogo e o estoque
atualizados.

A navegação foi planejada para que o cliente consiga realizar três ações
fundamentais:

-   Conhecer os veículos disponíveis.
-   Consultar preços e condições de pagamento.
-   Entrar em contato com um vendedor.

**Resultado esperado:** um site organizado, intuitivo, moderno e
funcional, que fortaleça a presença digital da Ford Regivel e contribua
para o aumento das oportunidades de venda.

------------------------------------------------------------------------

*Documento elaborado com base no levantamento de requisitos do projeto
Ford Regivel. As páginas de funcionalidades futuras foram mantidas como
possibilidades de evolução, não como requisitos obrigatórios da primeira
versão.*
