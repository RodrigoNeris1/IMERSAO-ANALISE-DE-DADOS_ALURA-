Passo a Passo para rodar o arquivo app.py

Abra um Novo Terminal no VsCode

Criar o ambiente virtual:

python3 -m venv .venv ou python -m venv .venv

Ativar o ambiente virtual em Windows:

.venv\Scripts\Activate

Ativar o ambiente virtual em MAC/LINUX:

source .venv/bin/activate

Criar um arquivo chamado requirements.txt e adicionar os pacotes necessários

pandas==2.2.3
streamlit==1.44.1
plotly==5.24.1

Instalar as bibliotecas necessárias
pip install -r requirements.txt
