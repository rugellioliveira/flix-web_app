**Flix - Web App**
---

**Funcionalidades**
Cadastro e Gerenciamento de Dados: Permite a inserção e atualização de informações sobre filmes, atores, gêneros e avaliações diretamente através da interface do Streamlit.
Visualização de Dados: Exibe gráficos e outras representações visuais para facilitar a análise dos dados cadastrados.
Integração com API: Utiliza a API flix_api para interagir com o backend, garantindo que todas as operações de leitura e escrita de dados sejam feitas de forma eficiente e segura.

**Tecnologias Utilizadas**
Streamlit: Para criação de interfaces de usuário dinâmicas e interativas.
Django: Para o desenvolvimento da API backend.
Django Rest Framework (DRF): Para a construção e gerenciamento das endpoints da API.

**Requisitos**
---
Certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:

Python (versão recomendada: 3.7 ou superior)
Outras dependências listadas no arquivo requirements.txt

**Instalação das Dependências**
---
Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:

pip install -r requirements.txt

**API**
---
Este projeto utiliza a [API do Projeto flix_api](https://github.com/rugellioliveira/flix_api) para fazer requisições.

**Rodar o projeto**
---
Após instalar as dependências, execute o projeto com:

streamlit run app.py
Após isso, o sistema estará pronto para ser acessado em: http://localhost:8501
