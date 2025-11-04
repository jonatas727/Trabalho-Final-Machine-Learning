<div align="center">

![IMAGEM](imagens/cabeçalho.png)

</div>

A Doença de Crohn é uma condição inflamatória crônica do trato gastrointestinal, cuja origem envolve fatores genéticos, imunológicos e ambientais. Neste projeto, foram selecionados dados de expressão gênica — com aproximadamente 1.922 genes como atributos — para investigar padrões moleculares associados à doença e prever o diagnóstico de pacientes.

Foram aplicados seis modelos de aprendizado supervisionado para a tarefa de classificação: Dummy (baseline), Naive Bayes, Regressão Logística, SVM, Random Forest e XGBoost. Essa abordagem permitiu avaliar a robustez preditiva, a interpretabilidade e a complexidade de cada modelo, aspectos fundamentais em aplicações biomédicas.

A avaliação do desempenho foi conduzida por meio de métricas clássicas de classificação, com ênfase na AUC-ROC, que mede a capacidade do modelo em distinguir entre classes positivas e negativas, e no desvio padrão, que indica a estabilidade das previsões entre diferentes execuções. Técnicas de validação cruzada e otimização de hiperparâmetros com Optuna foram empregadas para garantir a generalização e a consistência dos resultados.

---

### __Instruções de configuração__
__1__. Acesse a pasta `Arquivos_projeto`.

- Baixe o arquivo `dataset.zip`.

- Extraia o conteúdo e mantenha os arquivos extraídos na mesma pasta onde ficará o notebook principal (`DataCrohn.ipynb`).

__2__. Baixe o arquivo principal.
- O arquivo se chama `DataCrohn.ipynb`.

- Coloque-o na mesma pasta onde os datasets foram extraídos.

__3__. Acesse a pasta `optunas_arquivos`.
- Baixe todos os arquivos `.db` contidos nessa pasta.

- Mova-os também para o mesmo diretório onde estão o notebook e os datasets.

---

### __Execução do Notebook__
__1__. Verifique se o Python (versão 3.10 ou superior) está instalado em seu sistema.

__2__. Instale as dependências necessárias com o comando:

```bash
pip install -r requirements.txt
```
Caso o arquivo `requirements.txt` não esteja disponível, instale manualmente as bibliotecas utilizadas, como `pandas`, `numpy`, `scikit-learn`, `optuna` e `matplotlib`.

Abra o notebook `DataCrohn.ipynb` no Jupyter Notebook, JupyterLab ou Visual Studio Code e execute as células na ordem apresentada.

---

### __Observações importantes__
Certifique-se de que todos os arquivos necessários (datasets e bancos de dados `.db`) estejam no mesmo diretório do notebook principal. Isso é essencial para que os caminhos de leitura definidos no código funcionem corretamente.

---

### __Autores__
Aline Silva dos Santos
Jônatas Rafael de Oliveira Melo
Letícia Nunes de Souza Andrade

Disciplina: Aprendizado de Máquina — Ilum Escola de Ciência
Professor: Dr. Daniel R. Cassar

---