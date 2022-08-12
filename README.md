# Kepler-stars
Este repositório hospeda as Tabelas Finais de Dados dos objetos da missão Kepler, caracterizados pelos modelos gerados através de um algoritmo de Aprendizagem de Máquina, construído durante o mestrado da autora.

O arquivo <kbd>01tabela-final.csv</kbd> se refere à tabela de dados do modelo mais restrito do algoritmo, um modelo baseado em magnitudes J-PLUS/WISE com erro menor que 0,1 mag. Analogamente, o arquivo <kbd>02tabela-final.csv</kbd> se refere à tabela de dados de um segundo modelo, com menos restrições, baseado em magnitudes J-PLUS/WISE com erro menor que 0,2 mag. Como se supõe, o modelo mais restrito apresenta os dados mais precisos. 

**Sugerimos o uso dos dados de <kbd>02tabela-final.csv</kbd>, apenas quando a estrela Kepler não tiver sido caracterizada pelo primeiro modelo.**

As tabelas contém as seguintes colunas:

| Coluna        | Descrição     |
| ------------- | ------------- |
| RA            | Ascensão reta (J200) |
| DEC           | Declinação  (J200)|
| kic_kepler_id | Número identificador do objeto no catálogo KIC |
| Tef           | Temperatura efetiva estelar (K) |
| logg          | Logaritmo da gravidade superficial estelar (dex) |
| [Fe/H]        | Metalicidade estelar (dex) |
| m_g           | Magnitude aparente, na banda G do GAIA (mag) |
| dist(pc)      | Distância da Terra (pc) |
| M_g           | Magnitude absoluta, na banda G do GAIA (mag) |
| BC            | Correção bolométrica, na banda G do GAIA (mag) |
| M_bol         | Magnitude bolométrica (mag) |
| L             | Luminosidade estelar (L☉) |
| e_L           | Erro da luminosidade estelar (L☉) |
| R             | Raio estelar (R☉) |
| e_R           | Erro do raio estelar (R☉) |
| M             | Massa estelar (M☉) |
| e_M           | Erro da massa estelar (M☉) |
