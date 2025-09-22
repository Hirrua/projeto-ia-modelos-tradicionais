# Modelos Tradicionais de IA - RandomForest

Este repositório contém um notebook no **Google Colab** para experimentação com modelos de machine learning e um arquivo de **dataset** utilizado no projeto.

---

## 📂 Estrutura
- **Notebook Colab** → contém a implementação e execução dos modelos.  
- **Dataset** → arquivo `.csv` que deve ser carregado no Google Drive para uso no notebook.  

---

## ⚙️ Como usar
1. Salve o dataset em uma pasta no seu Google Drive.
2. Altere o caminho do dataset no notebook neste trecho:

```python
   # Altere para a pasta que você salvou (drive)
   survey_path = "/content/drive/{MyDrive/Colab Notebooks}/archive/survey.csv"

   df = pd.read_csv(survey_path)
```
# 🧠 Modelos

O notebook realiza um comparativo entre:

- **DummyClassifier** → modelo simples usado como baseline (*"modelo burro"*).  
- **RandomForest** → com aplicação de **engenharia de atributos** e **tratamento de outliers**, entre outras melhorias.  

---

# 🚀 Objetivo

O projeto tem como objetivo demonstrar a diferença de desempenho entre um modelo baseline e um modelo mais robusto (**RandomForest**), destacando a importância de técnicas de **pré-processamento** e **engenharia de atributos**.
