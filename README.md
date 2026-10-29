# Segmentação de Clientes via Implementação Manual do K-Means

> Projeto desenvolvido na disciplina de Algoritmos e Estruturas de Dados do Mestrado em Tecnologia da Informação (PPGTI/IFPB), focado na implementação do algoritmo de agrupamento K-Means a partir do zero em Python.

---

## 📌 Contexto e Objetivo
O objetivo principal deste projeto foi explorar os fundamentos matemáticos e algorítmicos do aprendizado não supervisionado, implementando a lógica do **K-Means sem o uso de bibliotecas de alto nível (como o Scikit-Learn)** para a etapa de clusterização. 

O algoritmo foi aplicado em uma base de dados de clientes para identificar padrões de comportamento de compra e segmentar perfis estratégicos.

---

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Computação Científica:** NumPy
* **Manipulação de Dados:** Pandas
* **Visualização:** Matplotlib / Seaborn
* **Ambiente:** Jupyter Notebook

---

## 🧠 Funcionamento do Algoritmo Manual
A implementação cobre as fases centrais do K-Means:
1. **Inicialização:** Definição aleatória dos centróides iniciais no espaço de atributos.
2. **Cálculo de Distância:** Implementação da distância Euclidiana vetorizada para atribuição de cada ponto ao centróide mais próximo.
3. **Atualização de Centróides:** Recálculo da média aritmética das coordenadas dos pontos atribuídos a cada grupo.
4. **Critério de Parada:** Interrupção após convergência (estabilização dos centróides) ou limite máximo de iterações atingido.
5. **Avaliação:** Cálculo da inércia (WCSS) e análise do Método do Cotovelo (*Elbow Method*) para escolha do número ideal de clusters ($k$).

---

## 📈 Resultados Obtidos
* Identificação de clusters distintos baseados nos atributos de consumo dos clientes.
* Comparação da convergência e do custo computacional da implementação manual em relação ao baseline tradicional.

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone [https://github.com/giovanayngrid-gk/segmentacao-clientes-kmeans-manual.git](https://github.com/giovanayngrid-gk/segmentacao-clientes-kmeans-manual.git)
cd segmentacao-clientes-kmeans-manual

2. Crie e ative o ambiente virtual:
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

3.Instale as dependências:
pip install numpy pandas matplotlib seaborn jupyter

4.Abra o notebook no navegador:
jupyter notebook kmeans_segmentacao_clientes.ipynb


👩‍💻 Autora
Giovana Yngrid Duarte Ribeiro / www.linkedin.com/in/giovana-yngrid
