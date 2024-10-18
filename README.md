# EBA- Aula 06 (Para Casa): Testes Não Paramétricos

Nesta aula vamos abordar os Testes Não Paramétricos que são utilizados quando não conseguimos garantir a normalidade na distribuição dos nossos dados.

O que você encontrará neste repositório:

- Na pasta `data`: os arquivos `csv's`ou `xlsx` utilizados em aula.
- Na pasta `notebooks`: o gabarito do desafio.
Recomendamos que você apenas olhe o gabarito depois de tentar fazer por você mesmo. Desta forma você irá desenvolver muito mais suas habilidades analíticas.

---
## INSTRUÇÕES PARA RESOLUÇÃO DO DESAFIO IFOOD (Continuação):

O conjunto de dados é composto por clientes da empresa Ifood com dados sobre:

- Perfis de clientes
- Preferências do produto
- Sucessos/fracassos da campanha
- Desempenho do canal

Queremos agora saber se o fato de uma pessoa reclamar na plataforma a torna detratora (detrator aqui seria não comprar mais em nossa plataforma).

Tomando como base a coluna `Complain`, veja que o grupo de pessoas que reclamam tem menos gastos (expense) do que pessoas que não reclamam.

Use um teste paramétrico e um não paramétrico. Discuta as diferenças

---

## INSTRUÇÕES PARA O USO DESTE REPOSITÓRIO:

### **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Abaixo estão as instruções simplificadas para configurar o ambiente com Pyenv e Poetry.

- **Passo a Passo para Configuração do Ambiente:**

1. **Clonar o Repositório:**

No terminal, clone este repositório:

```bash
git clone https://github.com/EbaPed/EBA-aula06-ParaCasa.git
cd EBA-aula06-ParaCasa
```

2. **Configurar a versão do Python com Pyenv**

Defina a versão do Python para o projeto. Para esta aula, vamos usar o Python 3.10.11 (ou outra versão compatível):

```bash
pyenv local 3.10.11
```

3. **Ativar o Ambiente Virtual Poetry**

Agora, ative o ambiente virtual:

```bash
poetry shell
```

4. **Instale as dependências do projeto usando Poetry:**

```bash
poetry install
```

Isso criará automaticamente um ambiente virtual isolado.


5. **Configurar o Kernel do Jupyter Notebook**

Se você for usar Jupyter Notebook, instale o ipykernel:

```bash
poetry add ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)
```

No Jupyter Notebook, escolha o kernel "Python (venv)" ao iniciar ou criar um novo notebook.


6. **Desativar o Ambiente Virtual**

Para sair do ambiente virtual, basta usar:

```bash
exit
```

7. **Executar o Código**

Agora que o ambiente está configurado, você pode executar os códigos Python fornecidos no repositório.

### **Comandos úteis**

- Ativar o ambiente virtual Poetry:

```bash
poetry shell
```

- Rodar um script com Poetry:

```bash
poetry run python script.py
```

- Adicionar bibliotecas:

 ```bash
poetry add nome_da_biblioteca
```

