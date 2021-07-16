# Chapter 5: Web Mining & Data Crawling
## Data-Driven Categorization of Objects in Tourism
***Roman Egger***, ***Markus Kroner*** & ***[Andreas Stöckl](https://github.com/astoeckl)***

![crawling.png](https://github.com/DataScience-in-Tourism/Chapter-5-Web-Mining-Data-Crawling/blob/main/crawling.png)

### Abstract

In this chapter, a number of tools for crawling websites are presented, and an example using hotel ratings has been adopted in order to specifically show how these can be extracted from a rating platform. For this purpose, Python with the library "BeautifulSoup" is used. Other program packages include Scrapy and Selenium, with which more complex applications can be realized. In addition to the technical aspects of web scraping, the legal framework of this process will also be discussed. 

Let´s assume that you want to analyze online hotel reviews and, since no API is provided,  the data needs to be crawled from an online rating platform. In this example, the user feedback should be extracted from www.TripAdvisor.com; 

### Environment Setup

The notebook was created using `Python 3.8.10`. You need the following packages: `pandas`, `numpy`, `sklearn`, `plotly`, `matplotlib`, and `xgboost`. Additionally, you need a properly configured IPython kernel.

If you are using [Anaconda](https://www.anaconda.com/), we recommend performing the following steps upon cloning the repository (replace environment name `DSIT` as you like):
```bash
## create a new Anaconda environment and activate it
conda create -n DSIT
conda activate DSIT

## install packages
conda install -n DSIT ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost

## build IPython kernel
python -m ipykernel install --user --name DSIT --display-name "Python (Data Science in Tourism)"

## now you can start a Jupyter session
jupyter notebook
```

On a Windows system with Python 3 without [Anaconda](https://www.anaconda.com/), we recommend performing the following steps upon cloning the repository:
```bash
## create a new Python environment and activate it
python -m venv .env
.env\Scripts\activate

## install packages
pip install ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost

## build IPython kernel
python -m ipykernel install --user --name .env --display-name "Python (Data Science in Tourism)"

## now you can start a Jupyter session
jupyter notebook
```

On a Linux/Mac OS system with Python 3 without [Anaconda](https://www.anaconda.com/), we recommend performing the following steps upon cloning the repository:
```bash
## create a new Python environment and activate it
python3 -m venv .env
source .env/bin/activate

## install packages
pip install ipykernel jupyter pandas numpy plotly sklearn matplotlib xgboost

## build IPython kernel
python -m ipykernel install --user --name .env --display-name "Python (Data Science in Tourism)"

## now you can start a Jupyter session
jupyter notebook
```

### Contact
Roman Egger - [Homepage](http://www.smartvisions.at/) - [LinkedIn](https://www.linkedin.com/in/prof-dr-roman-egger-b645601/)
Andreas Stöckl - [Homepage](http://www.stoeckl.ai/) - [LinkedIn](https://www.linkedin.com/in/andreas-st%C3%B6ckl-57682113a/) - [Twitter](https://twitter.com/stoecklai)
