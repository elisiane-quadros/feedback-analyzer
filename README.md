# Feedback Analyzer — Análise de Sentimentos com NLP

Projeto de análise de sentimentos em tweets com pipeline completo: EDA, pré-processamento, modelagem supervisionada e disponibilização via API. Desenvolvido para prática intensiva em NLP com Python e integração de modelos em ambientes de produção.


## Objetivos do Projeto

- Análise exploratória e visualização de sentimentos em dados reais;
- Limpeza e pré-processamento textual para tarefas de NLP;
- Classificação multiclasse (`positive`, `neutral`, `negative`) com modelos supervisionados;
- Exposição de modelo via API com FastAPI;
- Organização modular seguindo boas práticas para ambientes profissionais.


## Tecnologias Utilizadas

- **Python 3.11**
- **Pandas, NumPy** — manipulação de dados;
- **Seaborn, Matplotlib, WordCloud** — EDA visual;
- **Scikit-Learn** — modelagem supervisonada;
- **FastAPI** — API REST;
- **Jupyter Notebook** — experimentação e EDA interativa.


## Dataset

- **Fonte**: [Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- **Tamanho**: ~14.6k tweets rotulados como `positive`, `neutral`, `negative`.
- **Objetivo**: Predição automática do sentimento associado a textos curtos (tweets).


## Status

- ✅ EDA e limpeza concluída;
- ✅ Dataset limpo salvo para modelagem;
- 🔜 Próxima etapa: modelagem supervisionada;
- 🔜 API para inferência em tempo real.


## Execute o projeto

```bash
# Instalar dependências
pip install -r requirements.txt

# Executar EDA
jupyter notebook notebooks/eda_model_training.ipynb

```

Desenvolvido por **Elisiane Quadros**
[LinkedIn](https://www.linkedin.com/in/elisiane-quadros/) • © 2025  

Este projeto está licenciado sob a [MIT License](LICENSE).
