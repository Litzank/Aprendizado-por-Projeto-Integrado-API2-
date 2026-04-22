# Projeto segundo semestre - Logistica - Cargas Perigosas

Projeto baseado na metodologia ágil SCRUM, procurando desenvolver a Proatividade, Autonomia, Colaboração e Entrega de Resultados dos estudantes envolvidos

# Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Equipe](#Equipe)
* [Backlog do produto](#Product-Backlog)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Registro das Sprints](#Registro-das-Sprints)


# Projeto (API) 
Projeto pedagógico alicerçado na Metodologia API para ensino-aprendizado focado no desenvolvimento de competências e fundamentada nos pilares de aprendizado com problemas reais (RPBL), validação externa e mentalidade ágil. 
Uso de estratégias para entender o problema, conceber uma solução viável ao desenvolver e implementar o MVP seguido de sua operação (CDIO).

Desenvolver uma ferramenta de Business Intelligence que apresente o tratamento de dados do IBAMA para cargas especiais para analisar os indicadores de movimentação de cargas. O sistema deve apresentar métricas por estado e nacionalmente, como: quais cargas movimentadas, principais modais de transporte, matriz OD, entre outros.

Os resultados dos projetos devem obedecer ao Aviso Legal disponível no site da Fatec SJC com definição das datas do kickoff e das sprint

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Augusto Adriano Silva de Oliveira   |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/augustoprofile) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Litzank)              |
|  Scrum Master  | Matheus Luiz da Silva Santos   |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-luiz-a1aa632ab/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/KillBotSamonela)
| Team Member  | João Ricardo Rodrigues Araújo  |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-ricardo-rodrigues-ara%C3%BAjo-705560149?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/trabalhofatec2025)     |
| Team Member   | Rodrigo Luiz Ramos dos Santos  |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-luiz-santos-430081269?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/DigdinLogistico)        |
|  Team Member  | Edlaine Aparecida Marcos |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/edlaine-aparecida-marcos-3898341a7/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Dihmarcos85)        |    


# Objetivo do Projeto
Este projeto tem como objetivo ajudar e facilitar na utilização da plataforma GitHub, visando:
* Centralizar os trabalhos e projetos;
* Organizar e estruturar as informações;
* Versionar e controlar as alterações;
* Facilitar o compartilhamento e feedback;
* Desenvolver habilidades técnicas.


## Tecnologias Utilizadas

* Power BI
* Microsoft Excel (Office)
* Python (Colab)
* GitHub

## Questões para Análise

Para aprofundar a compreensão sobre o comércio exterior dos municípios paulistas, se deve investigar as seguintes questões (se possível):
*	Quais as principais cargas movimentadas?
*	Quais os principais modais utilizados?
*	Quais os principais origens e destinos?
*	Como foi a evolução da movimentação ao longo do tempo?
*	Quais as principais empresas movimentadoras de cargas perigosas com declaração realizada?

## Funcionalidades da Plataforma

A plataforma deverá conter os seguintes módulos:
*	Visualização segmentada por região
*	Dados referentes às movimentações de carga registradas pelo período de 2013 a 2025
*	Mapas e gráficos de tendência



# Product Backlog

| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
| 1    | Alta       | Como cliente, quero mesclar dos documentos de cargas perigosas do periodo de 2013 a 2025, para conseguir fazer o porte dessas informações para futuros graficos | 4          | 1      |
| 2    | Alta       | Como cliente, quero estruturar os dados mesclados de maneira a deixar clara as informações presente, para conseguir entender quais informações estão contidas nos dados mesclados| 8          | 1      |
| 3    | Alta       | Como cliente, quero filtrar estados fora são paulo, para que tenha foco no estado de são paulo somente                                                                                          | 2          | 1      |
| 4    | Alta       | Como cliente, quero filtrar a coluna UF de informações de municipios de destino, para que sejam removidas do banco                                   | 2          | 1      |
| 5    | Alta       | Como cliente, quero filtrar a coluna UF de informações de municipios de origem, para que sejam removidas do banco                                   | 2          | 1      |
| 6    | Alta       | Como cliente, quero destacar UF de destino e origem dos estados, para que seja possivel ser tratado posteriormente nos graficos                                                                             | 4          | 1      |
| 7    | Media       | Como cliente, quero padronizar a coluna “regional” no banco do DENATRAN para conter apenas o estado de São Paulo.                                                                            | 4          | 1      |
| 8    | Media       | Como cliente, quero remover colunas adicionais do DENATRAN, como data, dia da semana e feridos leves ou ilesos, para simplificar a base.v                                                                            | 4          | 1      |
| 9    | Media       | Como cliente, quero aplicar as mesmas transformações de limpeza em todas as bases do DENATRAN, para garantir consistência nos dados                                                                            | 4          | 1      |
| 10    | Baixa      | Como cliente, quero mesclar as informações da PRF sobre acidentes no periodo de 2013 e 2025, para que seja possivel conseguir fazer o porte dessas informações para futuros graficos | 10          | 1      |
| 11    | Baixa      | Como cliente, quero estruturar os dados mesclados da PRF, para posteriormente entender suas informações e filtrar suas informações                        | 10          | 1      |



  
# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| Video do Problema | 01/04/2026 | Entregue | [Video](https://www.youtube.com/watch?v=p4WN1IQ7SHc)|
| 01                | 29/04/2026 | a fazer  | [MVP](MVP/sp1.md)  |
| 02                | 20/05/2026 | a fazer  | [MVP](MVP/sp2.md)  |
| 03                | 10/06/2026 | a fazer  | [MVP](MVP/sp3.md)  |
| Feira de Soluções | 18/06/2026 | a fazer  | [MVP](#)  |

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa | Sprint |
|-----|-----------------------------------------------------------------------------|------------|------------|------------|
| US1 | Como cliente Marcos, quero um grafico de destino dos produtos, para possibilidade de visualização das informações de destino dos produtos.         | Alta       | 8 pontos   | Sprint 1  |
| US2 | Como cliente Marcos, quero um grafico de origem dos produtos, para possibilidade de visualização das informações de origem dos produtos.         | Alta       | 8 pontos   | Sprint 1  |
| US3 | Como cliente Marcos, quero um grafico dos produtos e suas quantidades, para possibilidade de visualização das informações dos produtos e suas quantidades.         | Alta       | 8 pontos   | Sprint 1  |
| US4 | Como cliente Marcos, quero um grafico dos tipos de transporte, para possibilidade de visualização das quantidades transportadas.         | Alta       | 8 pontos   | Sprint 1  |
| US5 | Como cliente Marcos, quero um grafico do anual dos produtos, para possibilidade de visualização da crescente anual dos produtos.         | Alta       | 8 pontos   | Sprint 1  |
| US6 | Como cliente Marcos, quero um filtro de destinos dos produtos, para possibilidade de visualização e seleção dos destinos.         | Media       | 4 pontos   | Sprint 1  |
| US7 | Como cliente Marcos, quero um filtro de origem dos produtos, para possibilidade de visualização e seleção das origens.         | Media       | 4 pontos   | Sprint 1  |
| US8 | Como cliente Marcos, quero um filtro dos tipos de produtos, para possibilidade de visualização e seleção de quais tipos de produtos queremos verificar. | Media       | 4 pontos   | Sprint 1  |
| US9 | Como cliente Marcos, quero um filtro dos tipos de transporte, para possibilidade de visualização e seleção dos tipos de transporte utilizados. | Media       | 4 pontos   | Sprint 1  |
| US10 | Como cliente Marcos, quero um filtro de anos, para possibilidade de visualização e seleção dos anos de maneira individual. | Media       | 4 pontos   | Sprint 1  |
| US11 | Como cliente Marcos, quero visualizar os gráficos com títulos claros, para melhor entendimento das informações apresentadas         | Baixa       | 2 pontos   | Sprint 1  |
| US12 | Como cliente Marcos, quero visualizar os gráficos com cores padronizadas, para facilitar a leitura dos dados.         | Baixa       | 2 pontos   | Sprint 2  |
| US13 | Como cliente Marcos, quero visualizar legendas nos gráficos, para melhor identificação das informações exibidas.         | Baixa       | 2 pontos   | Sprint 2  |
| US14 | Como cliente Marcos, quero aplicar múltiplos filtros simultaneamente, para analisar cenários mais específicos.        | Media       | 2 pontos   | Sprint 2  |
| US15 | Como cliente Marcos, quero passar o mouse sobre os gráficos e visualizar detalhes (tooltip), para obter informações mais específicas.       | Media       | 2 pontos   | Sprint 2  |
