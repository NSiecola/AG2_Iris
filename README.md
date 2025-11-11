# 🌸 Iris Flower Classifier

## 📋 Sobre o Projeto

Este projeto implementa um classificador de Machine Learning para identificar espécies de flores Iris com base em suas características morfológicas. Desenvolvido como parte da AG002 (Avaliação Global 2) do curso de Engenharia de Computação/Software do Inatel.

### 🎯 Objetivo

Treinar, avaliar e disponibilizar um modelo de aprendizado de máquina capaz de classificar três espécies de íris:
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

---

## 🗂️ Dataset

O projeto utiliza o **Iris Dataset**, coletado pelo estatístico Ronald Fisher em 1936. É um dos datasets mais conhecidos e utilizados em Machine Learning.

### Características do Dataset:
- **150 amostras** (50 de cada espécie)
- **4 atributos numéricos:**
  - Comprimento da sépala (cm)
  - Largura da sépala (cm)
  - Comprimento da pétala (cm)
  - Largura da pétala (cm)
- **3 classes:** Setosa, Versicolor, Virginica

**Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

## 🛠️ Tecnologias Utilizadas

### Linguagem
- Python 3.8+

### Bibliotecas
```
pandas          # Manipulação de dados
scikit-learn    # Algoritmos de ML
matplotlib      # Visualizações
seaborn         # Gráficos estatísticos
jupyter         # Notebooks interativos
```

---

## 📦 Instalação

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/iris-classifier.git
cd iris-classifier
```

### 2. Crie um ambiente virtual
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

---

## 🚀 Como Usar

### Opção 1: Jupyter Notebook (Recomendado)
1. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

2. Abra o arquivo `iris_classifier.ipynb`

3. Execute as células sequencialmente (Shift + Enter)

### Opção 2: PyCharm
1. Abra o projeto no PyCharm
2. Configure o interpretador Python
3. Execute o notebook diretamente na IDE

---

## 🧪 Funcionalidades

### ✅ Pré-processamento de Dados
- Carregamento automático do dataset
- Conversão de labels categóricos para numéricos
- Divisão em conjuntos de treino (80%) e teste (20%)
- Embaralhamento dos dados (shuffle)

### ✅ Treinamento do Modelo
Modelos disponíveis:
- ✓ **Decision Tree** (padrão)
- k-Nearest Neighbors (KNN)
- Multilayer Perceptron (MLP)
- Naïve Bayes
- Perceptron

### ✅ Avaliação
- Cálculo de acurácia
- Relatório de classificação (Precision, Recall, F1-Score)
- Matriz de confusão
- Visualizações gráficas

### ✅ Classificação Interativa
- Menu interativo para classificar novas amostras
- Interface simples via terminal
- Resultados em tempo real

---

## 📊 Resultados

### Métricas de Desempenho

```
Modelo: Decision Tree
Acurácia: 100%

              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00        10
   virginica       1.00      1.00      1.00        10

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30
```

**Nota:** A acurácia de 100% é esperada para o dataset Iris, que é relativamente simples e possui características bem distintas entre as espécies.

---

## 💻 Exemplos de Uso

### Classificação Manual

```python
# Exemplo 1: Iris Setosa
classificar_amostra(5.1, 3.5, 1.4, 0.2)
# Resultado: 'setosa'

# Exemplo 2: Iris Versicolor
classificar_amostra(6.0, 2.7, 5.1, 1.6)
# Resultado: 'versicolor'

# Exemplo 3: Iris Virginica
classificar_amostra(6.5, 3.0, 5.8, 2.2)
# Resultado: 'virginica'
```

### Menu Interativo

```bash
Comprimento da sépala (cm): 5.1
Largura da sépala (cm): 3.5
Comprimento da pétala (cm): 1.4
Largura da pétala (cm): 0.2

✓ RESULTADO 1: A flor é da espécie Iris setosa
```

---

## 📁 Estrutura do Projeto

```
iris-classifier/
│
├── iris_classifier.ipynb    # Notebook principal
├── README.md                # Documentação
├── requirements.txt         # Dependências
├── .gitignore               # Arquivos ignorados
```

---

## 🎓 Desenvolvimento Acadêmico

### Disciplina
Gestão de Engenharia de Software / Gestão de Engenharia de Computação

### Instituição
Instituto Nacional de Telecomunicações - Inatel

### Professores
- Prof. Me. Marcelo Vinícius Cysneiros Aragão
- Prof. Me. Renzo Mesquita Paranaíba

---

## 📝 Etapas do Projeto

- [x] Carregamento e análise exploratória dos dados
- [x] Pré-processamento (conversão de labels)
- [x] Divisão treino/teste (80/20 com shuffle)
- [x] Seleção e treinamento do modelo
- [x] Avaliação com métricas detalhadas
- [x] Implementação de classificador interativo
- [x] Documentação completa
- [x] Apresentação em vídeo

---

## 🔍 Referências

1. Fisher, R. A. (1936). The use of multiple measurements in taxonomic problems. *Annals of Eugenics*, 7(2), 179-188.

2. UCI Machine Learning Repository. Iris Dataset. DOI: https://doi.org/10.24432/C56C76

3. Scikit-learn Documentation. https://scikit-learn.org/

---

## 👥 Autores

**Ana Luiza Martins** - Engenharia da Computação
- GitHub: [@AnaLuizaMartins29](https://github.com/AnaLuizaMartins29)
- Email: ana.al@gec.inatel.br

**Nicholas do Vale Siécola** - Engenharia da Computação
- GitHub: [@NSiecola](https://github.com/NSiecola)
- Email: n.siecola@gec.inatel.br
---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos como parte da avaliação AG002 do Inatel.

---

⭐ **Se este projeto foi útil para você, considere dar uma estrela no repositório!**

---

**Desenvolvido com 💙 por estudantes do Inatel**
