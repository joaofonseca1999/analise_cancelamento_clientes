# 📊 Análise de Cancelamento de Clientes com Python

## 📌 Descrição do Projeto
Este projeto faz parte da **Jornada Python** e tem como objetivo realizar uma **análise de dados de cancelamento de clientes** em uma empresa fictícia.  
Através da manipulação e tratamento de dados com **Pandas** e da criação de gráficos com **Plotly**, buscamos identificar padrões de cancelamento e propor soluções para reduzir a taxa de churn.

---

## 🚀 Funcionalidades
- Importação e visualização da base de dados `cancelamentos.csv`  
- Tratamento de dados (remoção de valores nulos e colunas irrelevantes)  
- Cálculo da taxa de cancelamento geral  
- Análise de cancelamento por tipo de contrato (Mensal, Trimestral e Anual)  
- Identificação de fatores que influenciam o cancelamento (idade, frequência de uso, ligações ao call center, etc.)  
- Criação de gráficos interativos para melhor visualização dos resultados  

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**  
- **Pandas** → manipulação e análise de dados  
- **Plotly** → criação de gráficos interativos  
- **Jupyter Notebook (VSCode)** → ambiente de desenvolvimento e execução dos blocos de código  

---

## ⚙️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-analise-cancelamentos.git
   cd projeto-analise-cancelamentos
2. Instale as dependências:
   pip install pandas plotly nbformat
3. Abra o arquivo  no VSCode com suporte ao Jupyter Notebook.
4. Execute o arquivo main.ipynb por blocos para visualizar as análises e gráficos.

---

📊 Exemplos de Análises
- Taxa de cancelamento geral: 56,7% dos clientes cancelaram o serviço.
- Cancelamento por tipo de contrato:
- Mensal → taxa de cancelamento próxima de 100%
- Trimestral → taxa de cancelamento ~46%
- Anual → taxa de cancelamento ~46%
Esses resultados mostram que contratos mensais são os mais problemáticos, indicando que a empresa deve repensar sua estratégia para este tipo de plano.

⚠️ Observações Importantes
- A base de dados possui mais de 880 mil registros, portanto o processamento pode ser pesado em máquinas com poucos recursos.
- Recomenda-se testar com subconjuntos menores da base para validar o código antes de rodar a análise completa.
- O tratamento de dados é essencial para evitar erros durante a análise.


