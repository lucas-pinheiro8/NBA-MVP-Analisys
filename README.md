# 🏀 Análise de MVPs da NBA (1981–2021) — Power BI

Dashboard interativo desenvolvido para analisar o histórico do prêmio **MVP (Most Valuable Player)** da NBA ao longo de 42 temporadas, explorando padrões de desempenho, impacto nos times e comparação entre os maiores jogadores da história da liga.

![Capa](Pag%201.png)

[![Download Power BI](https://img.shields.io/badge/Download%20Dashboard-.pbix-yellow?style=for-the-badge&logo=powerbi)](https://github.com/lucas-pinheiro8/NBA-MVP-Analisys/raw/main/An%C3%A1lise%20MVP%20NBA.pbix)

---

## 📊 Sobre o Projeto

O projeto responde perguntas reais sobre o que define um MVP na NBA: estatísticas individuais fazem diferença? A idade importa? O time precisa ser forte? Quem são os maiores da história?

Foram analisadas **42 temporadas** (1981–2021), com dados de **198 jogadores diferentes**, cruzando estatísticas individuais com desempenho coletivo dos times.

---

## 📄 Páginas do Dashboard

### Página 1 — Visão Geral dos MVPs
![Visão Geral](Pag%202.png)

Panorama completo do histórico de MVPs com os principais KPIs e tendências:

- **42** temporadas analisadas (1981–2021)
- **198** jogadores diferentes no histórico
- **26,9 pts** de pontuação média dos MVPs
- **15,5 pts** — menor média de um MVP (2005)
- Evolução da média de pontos dos MVPs ao longo das décadas
- Gráfico de pizza: 76% dos MVPs foram conquistados após os 26 anos
- Ranking dos times com mais MVPs: Chicago Bulls e LA Lakers lideram com 6 cada
- Top 14 jogadores com mais aparições no Top 5 de votação — **LeBron James** lidera com 14 aparições

---

### Página 2 — Impacto do MVP no Time
![Impacto no Time](Pag%203.png)

Análise sobre a relação entre ter um MVP e o desempenho coletivo da franquia:

- Comparação de vitórias entre times **com MVP** vs **sem MVP** por temporada (1980–2021)
- Scatter plot de produção ofensiva: MVPs consistentemente acima da média da liga em pontos e USG%
- Gráfico de impacto nas vitórias por nível do time (Elite, Bom, Médio, Fraco)
- **Insight destacado:** Não existem MVPs em times médios ou fracos — o prêmio está diretamente associado a equipes de alto desempenho
- Medidor comparativo: média dos MVPs (26,9 pts) vs média dos candidatos Top 15 (21,8 pts)

---

### Página 3 — Comparativo entre Lendas
![Comparativo Lendas](Pag%204.png)

Análise aprofundada comparando **Michael Jordan, LeBron James, Kobe Bryant e Stephen Curry**:

- Pontuação média na carreira por jogador:
  - Michael Jordan: **30,7 pts**
  - LeBron James: **26,9 pts**
  - Kobe Bryant: **27,7 pts**
  - Stephen Curry: **26,5 pts**
- Gráfico de linha com a evolução da pontuação média ao longo das temporadas
- Bubble chart: média por temporada vs total de pontos, com tamanho da bolha indicando temporadas MVP
- Quantidade de títulos MVP conquistados: Jordan lidera com **5**, seguido por LeBron com **4**

---

## 💡 Principais Insights

- **Idade:** 76% dos MVPs foram conquistados por jogadores com mais de 26 anos
- **Time forte é obrigatório:** Nenhum MVP da história foi de um time médio ou fraco
- **Produção ofensiva:** MVPs têm USG% e média de pontos consistentemente acima da liga
- **Maior vencedor:** Michael Jordan com 5 títulos e média de 30,7 pts
- **Maior presença:** LeBron James lidera em aparições no Top 5 com 14 vezes
- **Menor média:** O MVP de 2005 venceu com apenas 15,5 pts — uma anomalia histórica

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Uso |
|---|---|
| Power BI Desktop | Construção do dashboard e visualizações |
| Power Query | Tratamento e transformação dos dados |
| DAX | Criação de medidas e KPIs calculados |
| Kaggle | Fonte dos dados históricos da NBA |

---

## 🗂️ Fonte de Dados

- **Dataset:** [NBA MVP Voting — Kaggle](https://www.kaggle.com)
- **Cobertura:** Temporadas de 1981 a 2021
- **Dados incluídos:** Estatísticas individuais, votações para MVP, dados dos times por temporada

---

## 📁 Estrutura do Repositório
```
NBA-MVP-Analisys/
├── Análise_MVP_NBA.pbix     # Arquivo Power BI
├── README.md
├── Pag 1.png                # Capa do Dashboard
├── Pag 2.png                # Visão Geral dos MVPs
├── Pag 3.png                # Impacto do MVP no Time
└── Pag 4.png                # Comparativo entre Lendas
```

---


