<p align="left" style="font-size:28px;"><strong><em>Documentação do PI</em></strong></p>
<details>
  <summary><strong>📑 Sumário</strong></summary>

- [1. Introdução](#1-introdução)
  - [Objetivos](#-objetivos)
  - [Metodologia](#-metodologia)
- [2. Requisitos](#2-requisitos)
  - [Requisitos funcionais](#-requisitos-funcionais)
  - [Requisitos não funcionais](#-requisitos-não-funcionais)
- [3. Modelo de casos de uso](#3-modelo-de-casos-de-uso)
- [4. Modelo do banco de dados](#4-modelo-do-banco-de-dados)
- [5. Banco de dados](#5-banco-de-dados)
- [6. Diagrama de classes](#6-diagrama-de-classes)
- [7. Estudo de viabilidade](#7-estudo-de-viabilidade)
- [8. Regras de negócio (Modelo canvas)](#8-regras-de-negócio-modelo-canvas)
- [9. Design](#9-design)
- [10. Protótipo](#10-protótipo)
- [11. Aplicação](#11-aplicação)
- [12. Considerações finais](#12-considerações finais)
- [13. Referências](#13-referências)

</details>

Para cada semestre, do 1º ao 6º, iremos utilizar este template para documentar o PI - incrementalmente.

# 1. Introdução
(Contextualização, Justificativa (porquê?)

## • Objetivos

## • Metodologia
(Que métodos, tecnologias, modelos de processo, ferramentas irá utilizar?  
Responde à pergunta: Como? Com o que? Onde? Quando?)  

# 2. Requisitos

## • Requisitos funcionais

2.1.1	Grupo de RF 1 
Coleta Automática via API/Chave:
O sistema deve integrar-se com a fonte de alimentação de dados (plataforma Davis/nuvem) através de API/chave de autenticação para extrair medições periodicamente sem necessidade de download manual
contínuo.

2.1.2	Grupo de RF 2
Importação Manual de Arquivo (.csv / .xml): 
Como mecanismo de contingência caso a automação/API falhe ou para carregar períodos específicos, o sistema deve permitir upload manual de arquivos.

2.1.3	Grupo de RF 3  
Filtragem e Limpeza Automática de Colunas:
Ao importar o .csv, o sistema deve descartar automaticamente as colunas desnecessárias e persistir apenas as variáveis úteis pré-definidas da estação.

2.1.4	Grupo de RF 4  
Consolidação e Agregação Temporal: 
O sistema deve calcular e consolidar automaticamente as métricas por período:
Agrupamento diário, semanal, mensal e anual.
Cálculo automático de médias, valores máximos/mínimos e acumulados de precipitação, eliminando a criação manual de planilhas.

2.1.5	Grupo de RF 5  
Gestão de Parâmetros Climáticos:
•	Precipitação: Acumulado diário (mm), acumulado mensal (mm) e acumulado anual (mm).
•	Umidade Relativa do Ar (%): Média diária, valor máximo registrado (com respectivo horário) e valor mínimo registrado (com respectivo horário).
•	Temperatura do Ar (°C): Média diária, temperatura máxima (com respectivo horário) e temperatura mínima (com respectivo horário).
•	Sensação Térmica (°C): Máxima (índice de calor com respectivo horário) e mínima (resfriamento pelo vento com respectivo horário).
•	Pressão Atmosférica (hPa): Média, valor máximo e valor mínimo (corrigidos para o nível do mar).
•	Vento: Velocidade média (km/h), direção predominante (rosa dos ventos/pontos cardeais), velocidade máxima da rajada de vento (km/h com respectivo horário e direção da rajada).
•	Extremos Anuais: Registro histórico da temperatura máxima e mínima do ano corrente (com data e hora da ocorrência).

2.1.6	Grupo de RF 6 
Página Inicial (Dashboard / Visão Geral):
Exibição das condições atuais (dados em tempo real / última medição disponível).
Apresentação resumida em cards ou tabelas limpas (inspirado no padrão de estações de referência como a da USP).



## • Requisitos não funcionais
(Escreva os requisitos não funcionais da aplicação (qualidade))  
- Requisitos de produto  
- Requisitos de organização  
- Requisitos de confiabilidade  
- Requisito de implementação  
- Requisito de padrões  
- Requisitos de interoperabilidade  

# 3. Modelo de casos de uso

# 4. Modelo do banco de dados
(Modelo conceitual, Modelo lógico, Físico)

# 5. Banco de dados

# 6. Diagrama de classes

# 7. Estudo de viabilidade

# 8. Regras de negócio (Modelo canvas)

# 9. Design
(Paleta de cor, Tipografia, Logo, Wireframes, Modelo de navegação)

# 10. Protótipo
(Gere um protótipo funcional na ferramenta que se sentir mais confortável (Figma, por exemplo) e apresente aqui, indicando o link).

# 11. Aplicação

# 12. Considerações finais

# 11. Referências

