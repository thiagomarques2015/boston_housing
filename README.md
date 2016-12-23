# Predicting Boston Housing Prices
O mercado imobiliário de Boston é altamente competitivo e você quer ser o melhor corretor de imóveis da região. Para competir contra seus colegas, você decidiu elencar alguns conceitos básicos de machine learning para ajudar você e seu cliente a achar o melhor preço de venda para a casa dele. Com sorte, você se deparou com o conjunto de dados de habitação de Boston que contém dados agregados de várias características para casas das comunidades da grande Boston, incluindo valores médios das casas para cada uma das regiões. Sua tarefa é construir um modelo ótimo baseado na análise das estatísticas com as ferramentas disponíveis. Esse modelo será então usado para estimar o melhor preço de venda para as casas do seus clientes.

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

### Code

Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 490 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-student ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
