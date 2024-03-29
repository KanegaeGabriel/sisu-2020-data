# Dados SiSU 2020

## Este repositório foi migrado para o repositório [sisu-data](https://github.com/kanegaegabriel/sisu-data), com melhorias nos scripts, dados e documentações.

## Arquivos .csv

**[Lista de Cursos](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/all_courses.csv)**

**Parciais: [22/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_22.csv) | [23/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_23.csv) | [24/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_24.csv) | [25/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_25.csv) | [26/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_26.csv)**

**Final: [27/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_27.csv) | [Lista de Aprovados](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/names.csv)**

**[Arquivos "baixar lista de selecionados da instituição"](get_csv)**

## Arquivos .txt

**Parciais: [22/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_22.txt) | [23/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_23.txt) | [24/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_24.txt) | [25/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_25.txt) | [26/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_26.txt)**

**Final: [27/01](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/grades_27.txt) | [Lista de Aprovados](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/names.txt) | [Ranking Geral de Aprovados](https://raw.githubusercontent.com/KanegaeGabriel/sisu-2020-data/master/data/names_ranking.txt)**

## Observações

Os arquivos .csv foram gerados pelos scripts [all_list_courses.py](/all_list_courses.py), [grades_request_data.py](/grades_request_data.py) e [names_request_data.py](/names_request_data.py), e a partir deles, foram gerados os .txt por [grades_parse_csv.py](/grades_parse_csv.py), [names_parse_csv.py](/names_parse_csv.py) e [names_generate_rank.py](names_generate_rank.py) a título de exemplo de uso.

Os arquivos parciais contêm apenas 6122 dos 6481 cursos oferecidos pelo SiSU, enquanto os arquivos finais contêm todos os 6481 cursos. Os arquivos com os alunos aprovados listam um total de 230322 nomes dentre todos os 6481 cursos.

Todos os dados neste repositório são públicos e estiveram disponíveis nos endereços [http://sisualuno.mec.gov.br/](http://sisualuno.mec.gov.br/) e [https://sisu.mec.gov.br/#/selecionados](https://sisu.mec.gov.br/#/selecionados). Embora coletados destas fontes oficiais, os dados aqui presentes não possuem caráter oficial, e devem ser usados apenas para consulta, estudo e pesquisa.