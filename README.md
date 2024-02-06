# Desafio Cientista de Dados

O repositório inclui análises exploratórias e modelos de previsão para uma plataforma de aluguéis temporários na cidade de Nova York.

Para a análise dos dados é necessário seguir os passos abaixo.

### Clonar o projeto:
No repositório, é possível encontrar o link projeto via SSH ou HTTPS e juntamente com o comando `git clone` é possível clonar o projeto.
- `https://github.com/AdrielyZBoller/DesafioDS.git`

### Ambiente Virtual:
Para realização do projeto foi criado um ambiente virtual. Para criar um ambiente virtual na pasta do projeto, siga estes passos:
- `python  -m venv venv`

### Ativar o ambiente virtual:
Após criar o ambiente virtual, é necessário ativá-lo.

- `.\venv\Scripts\Active.ps1` no Windows PowerShell ou VsCode;
- `source venv/bin/activate` no Linux;
- `source venv/Scripts/activate` em bash no Windows.

Quando ativado irá aparecer uma flag como o nome do ambiente virtual na frente do nome do usuário. Para desativar:
- `deactivate`

Obs: No caso do VsCode pode aparecer um erro de ativação, para solucionar abra o Windows PowerShell e digite o comando:
- `Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned`

Em seguida digite 'S'. Depois feche o PowerShell e execute novamente a ativação

### Instalar bibliotecas:
Execute o comando:

- `pip install -r requirements.txt` 

no terminal de comando.

### Executar o projeto:

- Abra o arquivo *Analise_exploratoria.ipynb* que se encontra dentro da pasta Notebooks e rodo por completo clicando no `run all`. Este arquivo contém a análise exploratória.

- Depois abra o arquivo *modelo_machine_learning.ipynb* e também rode por completo. Este arquivo contém o modelo de machine learning. Ao final ele irá gerar um arquivo .pkl.

### Ferramentas:
- Python 3.10.0;

- Jupyter Notebook.