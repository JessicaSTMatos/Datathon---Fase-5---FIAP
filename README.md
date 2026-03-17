📊 Análise de Sentimentos em Reclamações de Serviços Financeiros
🧠 Visão Geral

Este projeto realiza uma análise de sentimentos em reclamações de consumidores sobre serviços financeiros, utilizando técnicas de Processamento de Linguagem Natural (NLP) e Deep Learning.

O objetivo é transformar narrativas textuais de reclamações em informações úteis para entender padrões de insatisfação dos consumidores e identificar os principais problemas relatados pelos clientes.

🎯 Objetivos

Classificar automaticamente o sentimento das reclamações.

Identificar padrões linguísticos nas narrativas dos consumidores.

Detectar temas recorrentes relacionados a serviços financeiros.

Gerar insights a partir da análise de dados textuais.

📂 Base de Dados

Foi utilizada uma base pública de reclamações de consumidores sobre serviços financeiros, contendo aproximadamente 162 mil registros.

Cada registro possui:

product – categoria do produto financeiro

narrative – narrativa textual da reclamação

Principais categorias identificadas:

credit card

credit reporting

debt collection

mortgages and loans

retail banking

🔎 Análise Exploratória de Dados (EDA)

A análise exploratória foi realizada para compreender a estrutura da base e identificar padrões iniciais nos dados.

Foram analisados:

tamanho da base e tipos de dados

valores ausentes nas colunas

distribuição de reclamações por categoria de produto

tamanho das narrativas (número de palavras)

palavras mais frequentes nas reclamações

Os resultados indicam maior volume de reclamações relacionadas a serviços de crédito, cobranças de dívidas e gestão de contas.

🧹 Pré-processamento de Texto

Os textos passaram por etapas de preparação para modelagem:

remoção de pontuação

normalização de acentos

tokenização

limpeza textual

🔢 Vetorização de Texto

As narrativas foram transformadas em sequências numéricas utilizando tokenização e word embeddings.

Configuração utilizada:

vocabulário máximo: 20.000 palavras

tamanho máximo da sequência: 100 tokens

🤖 Modelo de Deep Learning

Foi implementado um modelo baseado em Rede Neural LSTM (Long Short-Term Memory) para classificação de sentimentos.

Divisão da base:

70% para treinamento

30% para teste

📈 Resultados

O modelo apresentou bom desempenho na classificação de sentimentos.

Acurácia Final:
91,69%

Os resultados indicam boa capacidade do modelo em classificar o sentimento das reclamações.

🛠 Tecnologias Utilizadas

Python

Pandas

NumPy

Scikit-learn

TensorFlow / Keras

NLTK

Matplotlib

Seaborn

📌 Conclusão

A utilização de técnicas de Processamento de Linguagem Natural e Deep Learning permitiu identificar padrões relevantes nas reclamações de consumidores do setor financeiro.

Os resultados demonstram que a análise de dados textuais pode auxiliar na identificação de problemas recorrentes e na geração de insights sobre a experiência dos clientes com serviços financeiros.
