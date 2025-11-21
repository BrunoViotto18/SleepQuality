# Preparação do ambiente

Para instalar os pacotes necessários para a executação do notebook python, execute os seguintes passos:


## Crie um ambiente virtual

Crie um ambiente para a instalação dos pacotes relacionados ao projeto

`
python -m venv .venv
`

## Ative o ambiente

Ative o ambiente criado executando o script de ativação:

### Ativação Windows

`
.venv/bin/Activate.ps1
`

### Ativação Linux

`
.venv/bin/activate
`

## Instale as dependências

Instale as dependência através do seguinte comando:

`
pip install -r requirements.txt
`

## Execute o notebook python

Após instalar os pacotes necessários, você pode executar o notebook no ambiente virtual criado sem problemas

Caminho do notebook: `src/main.ipynb`
