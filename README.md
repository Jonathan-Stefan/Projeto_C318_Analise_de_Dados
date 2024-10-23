## VENV
Para criação do projeto trabalhamos com um ambiente virtual, o qual pode ser criado a partir dos comandos abaixo (OBS: recomendado estar na pasta iws)

```
# Linux

# Criar venv
python3 -m venv env

# Ativar venv
source env/bin/activate

# Desativar
deactivate
```
```
# Windows

# Criar venv
python3 -m venv env

# Ativar venv
env\Scripts\activate

# Desativar
deactivate
```

## Instalando dependências 
```
pip install summarytools klib scikit-learn plotly streamlit matplotlib pandas_gbq pandas
```