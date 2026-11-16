# 🎵 ShowTrack Analyzer: Análise de Dados de Shows e Eventos

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white) 
![Data Science](https://img.shields.io/badge/Data_Science-Analysis-blueviolet?style=for-the-badge)

## 📝 Sobre o Projeto
Este projeto foi desenvolvido para analisar o desempenho comercial e operacional de grandes shows e eventos musicais. Através da manipulação de dados utilizando a biblioteca **Pandas**, conseguimos calcular a receita bruta gerada por artista e a eficiência de ocupação de cada local do evento, fornecendo insights valiosos sobre o mercado de entretenimento.

## 🚀 Funcionalidades e Métricas Calculadas
O pipeline de dados realiza as seguintes operações:

1. **Carga e Exploração de Dados:** Leitura e análise descritiva das principais variáveis (artistas, gêneros, cidades, ingressos vendidos e preços).
2. **Geração de Receita Bruta:** Cálculo financeiro multiplicando os `Ingressos_Vendidos` pelo `Preco_Medio_Ingresso` por evento.
3. **Taxa de Ocupação (%):** Avaliação da eficiência de vendas em relação à capacidade máxima do local (`Capacidade_Local`).
4. **Exportação dos Resultados:** Geração de um novo arquivo CSV refinado pronto para dashboards de B.I.

## 📊 Resumo dos Dados Analisados
* **Volume de Shows:** 20 eventos mapeados.
* **Capacidade Média:** ~43.600 pessoas por evento.
* **Ingressos Vendidos (Média):** ~40.100 por show (demonstrando alta taxa de engajamento).
* **Preço Médio do Ingresso:** R$ 302,50.
* **Cidades Destacadas:** Forte presença de shows em São Paulo (6 dos 20 eventos).

## 🛠️ Tecnologias Utilizadas
* **Python** (Linguagem base)
* **Pandas** (Tratamento e manipulação de dados)
* **Jupyter Notebook / Google Colab** (Ambiente de desenvolvimento)

## 📁 Estrutura do Repositório
```bash
├── shows_eventos.csv       # Base de dados bruta de entrada
├── analise_eventos.ipynb   # Notebook com todo o código de análise
├── shows_eventos_novo.csv  # Base tratada contendo as novas colunas de Receita e Ocupação
└── README.md               # Documentação do projeto
🔧 Como Executar
Clone o repositório:
git clone https://github.com/seu-usuario/nome-do-seu-repositorio.git
Instale o Pandas:
pip install pandas
Execute o script ou abra o notebook no Jupyter/Google Colab para rodar as análises linha por linha.
