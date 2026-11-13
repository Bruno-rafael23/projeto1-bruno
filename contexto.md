# Contexto do MVP

## 1. Objetivo do MVP

O objetivo do MVP é criar uma solução digital que ajude as pessoas a descobrir restaurantes, lanchonetes e pontos gastronômicos mais adequados ao seu perfil, com base em:

- gostos culinários pessoais;
- comidas típicas da região em que o usuário está;
- avaliações online de clientes;
- filtros simples e rápidos para facilitar a decisão.

A proposta é reduzir o tempo de pesquisa e entregar ao usuário uma shortlist com os principais pontos de interesse mais relevantes para o momento, em vez de exigir que ele pesquise restaurante por restaurante.

## 2. Problema que o MVP resolve

Muitas pessoas enfrentam dificuldades para escolher onde comer porque percorrem várias opções sem saber qual delas realmente combina com suas preferências. Esse processo costuma ser lento e frustrante, principalmente quando:

- o usuário está em uma cidade desconhecida;
- deseja experimentar pratos típicos da região;
- busca opções que atendam ao seu gosto pessoal;
- depende de avaliações para evitar escolhas ruins.

O aplicativo resolve esse problema central ao centralizar a busca em uma experiência orientada por perfil e contexto.

## 3. Proposta de valor

O MVP entrega uma experiência prática em que o usuário informa o que gosta e o sistema sugere pontos gastronômicos mais adequados, considerando:

- tipo de comida;
- localização/região;
- pratos típicos;
- avaliação geral;
- nível de compatibilidade com o perfil do consumidor.

Com isso, o usuário economiza tempo, toma decisões mais assertivas e encontra opções que se alinham melhor com suas preferências.

## 4. Público-alvo

O público principal é:

- pessoas que gostam de comer fora e buscam recomendações rápidas;
- viajantes ou moradores que desejam conhecer comida típica da região;
- usuários que preferem decisões baseadas em avaliações e gosto pessoal;
- pessoas que querem evitar pesquisa manual excessiva antes de escolher um restaurante.

### Personas principais

#### Pessoa 1: Usuário urbano ocupado
- quer encontrar uma boa opção perto de onde está;
- não quer gastar muito tempo escolhendo;
- valoriza praticidade e rapidez.

#### Pessoa 2: Viajante gastronômico
- quer experimentar comidas típicas da região;
- busca pontos autênticos e bem avaliados;
- gosta de descobrir sabores locais.

#### Pessoa 3: Usuário com preferências específicas
- prefere determinados tipos de comida;
- valoriza filtros por perfil, culinária e avaliações;
- busca recomendações mais personalizadas.

## 5. Funcionalidades do MVP

O MVP deve focar em um conjunto mínimo de recursos para validar a ideia com menor esforço e maior retorno.

### Funcionalidades essenciais

1. Cadastro/login simples do usuário
2. Preferências gastronômicas do usuário
   - tipos de comida preferidos;
   - nível de abertura para pratos típicos;
   - regiões ou bairros de interesse.
3. Busca por localidade/ região
4. Filtro por culinária e cultura local
5. Ranking de pontos de interesse com base em:
   - avaliações;
   - popularidade;
   - relevância para o usuário;
   - comida típica da região.
6. Exibição dos principais pontos de interesse recomendados
7. Detalhes simples do restaurante ou ponto gastronômico
   - nome;
   - categoria;
   - localização;
   - avaliação;
   - destaque do prato ou categoria.

## 6. Arquitetura do projeto

A arquitetura do projeto pode ser pensada em camadas simples para facilitar desenvolvimento, manutenção e validação do MVP.

### Arquitetura proposta

#### Frontend
- interface web ou mobile para o usuário interagir;
- telas para:
  - login;
  - cadastro de preferências;
  - busca por região;
  - resultados de recomendação;
  - detalhes do estabelecimento.

#### Backend
- responsável pela lógica da aplicação;
- processamento das preferências do usuário;
- filtros por região e culinária;
- lógica de recomendação;
- integração com dados de restaurantes e avaliações.

#### Banco de dados
- armazenamento de usuários;
- dados de restaurantes/pontos gastronômicos;
- categorias culinárias;
- avaliações;
- preferências do usuário.

#### Serviços externos (opcional no MVP)
- APIs de mapas;
- APIs de busca geográfica;
- APIs de avaliações ou dados públicos de restaurantes.

## 7. Fluxo do usuário

O fluxo principal do MVP pode ser:

1. O usuário acessa o aplicativo.
2. Realiza login ou cadastro.
3. Define suas preferências alimentares.
4. Informa a região ou localização atual.
5. O sistema filtra as opções com base em:
   - comida típica da região;
   - preferências pessoais;
   - avaliações.
6. O aplicativo apresenta os principais pontos de interesse mais relevantes.
7. O usuário escolhe uma opção com mais confiança e menos esforço.

## 8. Critérios de sucesso do MVP

O MVP será considerado útil se:

- a recomendação for percebida como relevante pelo usuário;
- a busca por restaurantes for mais rápida que a pesquisa manual;
- os resultados forem mais alinhados às preferências pessoais;
- o usuário conseguir descobrir opções locais e típicas sem muita fricção;
- a experiência gerar confiança e conveniência.

## 9. Escopo inicial recomendado

Para não expandir demais no começo, o MVP deve focar em:

- preferências do usuário;
- filtro por região;
- filtro por tipo de comida;
- avaliação/nota;
- recomendação simples de melhores opções.

Funcionalidades mais avançadas, como geolocalização detalhada, mapa interativo, chat, ou sistema de fidelidade, podem entrar em versões futuras.

## 10. Resumo executivo

O MVP é um aplicativo de recomendação gastronômica orientado por perfil do usuário, localização e avaliações. Sua principal missão é facilitar a escolha de restaurantes e pontos de interesse gastronômicos, entregando opções mais relevantes de forma rápida e intuitiva. O projeto tem valor para pessoas que querem comer bem sem perder tempo pesquisando diversas opções manualmente.
