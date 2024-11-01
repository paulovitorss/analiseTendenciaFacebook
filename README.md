## Pré-requisitos

- **Python** (versão recomendada: 3.12 ou superior)
- **pip** (gerenciador de pacotes do Python)

## Configuração do Ambiente

Para garantir que todas as dependências estejam isoladas e não causem conflitos com outras bibliotecas instaladas, crie um ambiente virtual.

### 1. Criação do Ambiente Virtual

No terminal ou prompt de comando, navegue até o diretório do projeto e execute o seguinte comando para criar o ambiente virtual:

```bash
python -m venv env
```

### 2. Ativação do Ambiente Virtual

Para ativar o ambiente virtual, execute o comando conforme o sistema operacional:

- Windows:

```bash
env\Scripts\activate
```

- Linux ou macOS:

```bash
source env/bin/activate
```

### 3. Instalação das Dependências

Com o ambiente virtual ativado, execute o comando abaixo para instalar as dependências do projeto:

```bash
pip install -r requirements.txt
```

## Execução do Projeto

Para executar o projeto, execute o arquivo Jupyter Notebook `analise_tendencia.ipynb`:

```bash
jupyter notebook analise_tendencia.ipynb
```