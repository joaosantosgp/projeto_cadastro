# 🧾 Página de Cadastro Interativa com Streamlit

Uma **aplicação web simples e eficaz** desenvolvida com [Streamlit](https://streamlit.io/) para **coleta e gestão de dados**.  
Os usuários podem inserir informações por meio de **formulários interativos**, e os dados são manipulados e exibidos em **tabelas dinâmicas** utilizando o [Pandas](https://pypi.org/project/pandas/).

---

## 🚀 Funcionalidades

- ✅ Interface web intuitiva construída com **Streamlit**
- ✅ Formulário interativo para inserção de dados
- ✅ Armazenamento e manipulação dos dados com **Pandas DataFrame**
- ✅ Exibição automática dos dados em tabela
- ✅ Ideal para **projetos de cadastro**, **coleta de informações** e **prototipagem rápida**

---

## 🛠️ Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)

---

## 📦 Instalação e Configuração

Siga os passos abaixo para executar o projeto localmente:

```bash
# Clone este repositório
git clone https://github.com/joaosantosgp/projeto_cadastro.git

# Acesse o diretório do projeto - mkdir para Windows
cd nome-do-repositorio

# Cria o ambiente virtual
python -m venv venv

# Ativa o ambiente no Windows
venv\Scripts\activate

# Ou no Linux/Mac
source venv/bin/activate

# Instale as dependências do projeto, 
# o arquivo requirements.txt contém todos os pacotes necessários.
# Para instalá-los, execute:

pip install -r requirements.txt

# Após instalar as dependências, execute o comando:
streamlit run app.py

# O navegador será aberto automaticamente com o endereço:
http://localhost:8501