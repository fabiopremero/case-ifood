# iFood Data Analysis Case

Este projeto contém um notebook (.ipynb) que realiza a análise dos dados do case técnico do iFood. Siga as instruções abaixo para configurar o ambiente e rodar o notebook, seja no VSCode ou no Google Colab.

---

## Pré-requisitos

- **Python** instalado (para VSCode).
- **Visual Studio Code (VSCode)** com a extensão **Jupyter** instalada, se optar por rodar localmente.

---

## VSCode

1. **Clonar o Repositório ou Abrir a Pasta do Projeto:**

   - Se o projeto estiver hospedado em um repositório Git, clone-o:
     ```bash
     git clone <URL-do-repositório>
     ```
   - Ou baixe e extraia os arquivos do projeto e abra a pasta no VSCode.

2. **Criar e Ativar um Ambiente Virtual (opcional, mas recomendado):**

   - Navegue até a pasta do projeto e crie um ambiente virtual:
     ```bash
     python -m venv venv
     ```
   - Ative o ambiente:
     ```bash
     source venv/bin/activate
     ```

3. **Instalar as Dependências:**

   - Execute:
     ```bash
     pip install -r requirements.txt
     ```

4. **Abrir e Executar o Notebook:**

   - No VSCode, abra o arquivo `.ipynb`.
   - Certifique-se de que o kernel aponta para o ambiente virtual correto (verifique no canto inferior direito).
   - Execute as células usando os botões "Run Cell" ou "Run All".

---

## Google Colab

1. **Acessar o Google Colab:**

   - Vá para [Google Colab](https://colab.research.google.com/).
   - Baixar todas os arquivos do repositório dentro do Google Colab

2. **Instalar Dependências (se necessário):**

   - Adicione uma célula no início do notebook com o comando:
     ```python
     !pip install -r requirements.txt
     ```
     > **Nota:** Certifique-se de ter carregado o arquivo `requirements.txt` junto com o notebook ou instale manualmente as bibliotecas necessárias.

3. **Executar o Notebook:**

   - Execute as células do notebook normalmente usando os botões do Colab.

---
