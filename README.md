# Aplicativo Web com Análise de Indicadores do PNAD-COVID-19 para o Planejamento de Ações de Combate ao Surto da Doença

Este projeto consiste em um aplicativo web para análise dos dados da PNAD-COVID-19 (IBGE), focada no planejamento de ações de combate à doença. O sistema utiliza dados de setembro a novembro de 2020 para identificar gargalos de infraestrutura, caracterizar sintomas clínicos e analisar aspectos socioeconômicos e geoespaciais da população brasileira.

### Pré-requisitos

Certifique-se de ter o Python 3.11 instalado em seu sistema.

Para sistemas baseados em Linux (Ubuntu/Debian), instale o suporte ao ambiente virtual:

```bash
sudo apt update && sudo apt install python3.11-venv
```

### Instalação

Siga os passos abaixo para configurar o ambiente e instalar as dependências:

```bash
#clonar o repositório
git clone https://github.com/jorgeplatero/postech-tech-challenge-fase3.git
cd postech-tech-challenge-fase3

#criar o ambiente virtual
python -m venv venv

#ativar o ambiente virtual
source venv/bin/activate

#instalar as dependências
pip install -r requirements.txt
```

### Como Rodar a Aplicação

Com o ambiente virtual ativado, execute o comando abaixo para iniciar o aplicativo localmente:

```bash
streamlit run app.py
```

### Tecnologias

| Componente | Tecnologia | Versão | Descrição |
| :--- | :--- | :--- | :--- |
| **Frontend/App** | **Streamlit** | `1.28.0` | Framework para desenvolvimento de aplicativo web |
| **Processamento Big Data** | **PySpark** | `3.5.0` | Framework para processamento distribuído, leitura e pré-processamento de grandes volumes de dados |
| **Análise de Dados** | **Pandas** | `2.0.3` | Biblioteca para manipulação de dados |
| **Visualização** | **Plotly** | `5.17.0` | Biblioteca para criação de gráficos dinâmicos e interativos |
| **ORM** | **SQLAlchemy** | `2.0.22` | Biblioteca para manipulação de banco de dados relacionais |
| **Drivers DB** | **PyMySQL** | `1.1.0 / 8.1.0` | Biblioteca para comunicação nativa com servidores MySQL |
| **Comunicação** | **Requests** | `2.31.0` | Biblioteca para requisições HTTP e consumo de API |
| **Linguagem** | **Python** | `>=3.11` | Linguagem para desenvolvimento de scripts |
| **Gerenciamento** | **Venv** | `-` | Gerenciador de ambientes virtuais para isolamento de dependências |

### Fontes de Dados

Os dados foram extraídos da pesquisa PNAD COVID-19 realizada pelo IBGE.

Link para a base de dados: https://covid19.ibge.gov.br/pnad-covid/

### Deploy

O aplicativo web está disponível via Streamlit Cloud.

Link para o aplicativo: https://postechtechchallengefase3-nvadkgperqxqkzu835k6er.streamlit.app/

### Colaboradores

[Mateus Albuquerque](https://github.com/mateus-albuquerque)

[Adrielly Silva](https://github.com/adriellytsilva)
