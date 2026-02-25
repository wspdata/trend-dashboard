# Análise de Tendências de Vídeos no YouTube

## Descrição do Projeto
Projeto de análise de dados aplicado ao contexto de uma agência de publicidade (Sterling & Draper), com foco em automatizar a análise semanal de vídeos em tendência no YouTube. O objetivo principal foi construir um dashboard interativo que respondesse às perguntas recorrentes dos gerentes de planejamento de anúncios: quais categorias estão em alta, como se distribuem entre as regiões e quais são especialmente populares nos Estados Unidos.

---

## Metodologia
1. **Elaboração de Requisitos Técnicos**
   - Definição do objetivo de negócio, público-alvo do dashboard, frequência de uso e fontes de dados em conjunto com gerentes e administradores de banco de dados.
2. **Construção do Dashboard**
   - Criação de gráficos interativos no Tableau Public a partir da tabela agregada `trending_by_time.csv`, com filtros por data/hora e país que modificam todos os painéis.
3. **Análise e Resposta às Perguntas de Negócio**
   - Interpretação dos gráficos para responder às questões dos stakeholders sobre categorias em alta, distribuição regional e destaques nos EUA.
4. **Apresentação dos Resultados**
   - Síntese das conclusões em relatório visual voltado a públicos não técnicos.

---

## Principais Insights

- **Categorias mais frequentes globalmente:**
  Entertainment, People & Blogs e Music lideram em frequência de aparições entre os vídeos em alta no YouTube.

- **Distribuição por região:**
  As categorias mais populares seguem uma distribuição relativamente uniforme entre os países, com variações pontuais — como a maior presença de News & Politics na Rússia e Índia, ou de Howto & Style nos EUA.

- **Destaques nos Estados Unidos:**
  Os EUA seguem o padrão global, com Entertainment (24.3%) e Music (15.9%) no topo, mas se diferenciam pela maior diversidade de categorias secundárias, com destaque para Howto & Style (10.2%) e Comedy (8.5%) — padrão não observado com a mesma intensidade em outros países.

---

## 📊 Apresentação dos Resultados

Além do dashboard interativo, este projeto conta com uma apresentação voltada à comunicação dos resultados para públicos não técnicos.

### 📄 Apresentação em PDF
Foi elaborada uma apresentação com o resumo do projeto, principais gráficos e conclusões sobre o comportamento de tendências no YouTube por categoria e região.

➡️ **Acesse a apresentação:**
[Apresentação — Análise de Tendências no YouTube (PDF)](./apresentacao.pdf)

> *O PDF apresenta os principais insights de forma objetiva, com foco em impacto para o negócio e apoio à tomada de decisão.*

---

### 📈 Dashboard Interativo (Tableau)
Foi desenvolvido um dashboard no Tableau para exploração visual dos dados, contendo:
- Histórico de tendências dividido por dia e categoria (valores absolutos e percentuais)
- Distribuição de vídeos em alta por país e categoria
- Filtros interativos por data/hora e país

➡️ **Visualizar dashboard no Tableau:**
[Dashboard Análise de Tendências — Tableau Public](https://public.tableau.com/views/DashboardProjeto/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

> *O dashboard permite análise interativa do comportamento de tendências ao longo do tempo e entre regiões, com atualização diária à meia-noite UTC.*

---

## 📂 Conteúdo do Repositório

- **trending_by_time.csv:** dados utilizados no dashboard
- **dashboard_link.txt:** link para visualização interativa no Tableau Public
- **Apresentação (.pdf):** síntese dos resultados e conclusões de negócio
- **README (.md)** — Este arquivo.

---

## Tecnologias e Bibliotecas
- Visualização interativa: **Tableau Public**
- Apresentação: **PowerPoint**
- Dados: **CSV (trending_by_time)**

---

## Contato

Willian De Souza Pereira — ws13292@gmail.com

LinkedIn: https://linkedin.com/in/willian-de-souza-pereira-b69109202

GitHub: https://github.com/willtrash

## Licença

Este repositório está disponível para estudo e demonstração. Sinta-se à vontade para clonar, adaptar e abrir *issues* com dúvidas ou sugestões.
