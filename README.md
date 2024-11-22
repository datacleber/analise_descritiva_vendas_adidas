# Introdução e Objetivo

## Uma Marca Global

---

A Adidas é uma das maiores e mais reconhecidas marcas globais no setor de vestuário e equipamentos esportivos. 

Fundada em 1949 por Adolf Dassler na Alemanha, a empresa é conhecida por suas inovações em produtos como tênis, roupas esportivas e acessórios. 

Seu logotipo, composto por três listras, é um dos símbolos mais icônicos no mundo do esporte e da moda. 

A marca patrocina atletas e equipes em várias modalidades, além de colaborar com designers e influenciadores para criar coleções que combinam performance e estilo. A líder de mercado busca constantemente integrar tecnologia e sustentabilidade em seus produtos.

## Analista de Dados Recém Contratado

---

O projeto a seguir simula o papel de um analista admitido em um dos departamentos de dados da empresa e que recebe uma demanda inicial que é analisar as vendas dos anos de 2020 e 2021 da marca nos Estados Unidos.

A realização de uma análise descritiva representa uma oportunidade valiosa para entender o desempenho da empresa no mercado, revelando tendências de consumo, padrões de compra e comportamentos dos consumidores. Esses insights são fundamentais para apoiar a tomada de decisões estratégicas, otimizar processos e identificar áreas de melhoria.

## Quais Foram as Análises Requisitadas ?

---

Este projeto analisou o desempenho das vendas nos seguintes aspectos:

- **Linhas de Produtos:** O objetivo dessa análise é compreender o desempenho de diferentes categorias de produtos no mercado, identificando as linhas que geram maior faturamento, lucro operacional e rentabilidade. Além disso, a avaliação busca destacar quais produtos estão impulsionando o crescimento da marca e identificar aqueles com menor desempenho, possibilitando ações corretivas ou estratégias para potencializar resultados.

- **Faturamento por Região e Estados:** Esta análise tem como objetivo avaliar o desempenho da Adidas em diversas regiões dos Estados Unidos, identificando mercados com maior potencial de crescimento e desafios específicos em cada localidade. A partir desses dados, é possível mapear oportunidades regionais, ajustar estratégias comerciais e fortalecer a presença da marca em estados com menor desempenho ou maior competitividade.

- **Desempenho dos Canais de vendas:** A análise dos canais de vendas tem como objetivo identificar o impacto de cada canal — como lojas físicas, e-commerce e outlet — no desempenho geral da marca.
    
    Para isso, foi avaliado o comportamento das vendas ao longo da semana, buscando entender        padrões específicos, como dias com maior volume de vendas e variações entre os canais.
    

## Ferramentas Utilizadas

---

Para realizar essa análise, utilizei o Databricks Community, uma plataforma de desenvolvimento que facilita o trabalho com grandes volumes de dados. Ela integra o uso do SQL, uma linguagem padrão para consultas de dados, e sua versão específica chamada SparkSQL.

Inicialmente, os dados foram fornecidos no formato CSV  mas foi necessário convertê-los para o formato Delta.

Essa conversão é uma etapa fundamental, especialmente quando se trata de limpar e corrigir os dados. Com o formato Delta, é possível realizar operações importantes, como atualizar ou excluir dados, de forma mais segura e precisa, ofercendo mais garantia e integridade.

O processo de conversão está detalhado no notebook ***01_criacao_banco_de_dados_e_tabela_delta*.**

## Recursos Visuais

---

O Databricks fornece uma interface integrada para a criação de gráficos interativos diretamente a partir de notebooks. Essa funcionalidade permite visualizar dados de forma prática e dinâmica, utilizando formatos como gráficos de barras, linhas e dispersão, gerados diretamente a partir dos resultados de consultas SQL.

Embora as opções de personalização sejam mais limitadas em comparação com grandes ferramentas de BI, esses recursos são altamente úteis para visualizar resultados de maneira rápida e eficaz, especialmente durante a análise e apresentação de insights.

## Metodolodia de Análise

---

Na seção **Análises de Negócio**, após o tratamento e a limpeza dos dados, serão apresentados os resultados relacionados aos objetivos do projeto.

A estrutura estabelecida segue a seguinte ordem:

1. **Explicação** : Descrição do processo de construção das queries, incluindo a lógica empregada e a apresentação do código utilizado.
2. **Visualização dos resultados**: Exibição dos dados por meio de uma tabela de resultado  e  gráficos para facilitar a interpretação.
3. **Sessão de insights**: Análise dos resultados obtidos, destacando os principais aprendizados e implicações para o negócio.

## Materiais para Download

---

Todos os notebooks estarão disponíveis para download na última sessão do projeto.

Também será disponibilizado o projeto completo em minha página do github.
