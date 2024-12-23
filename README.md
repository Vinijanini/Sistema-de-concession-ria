[![Pylint](https://github.com/92username/Sistema-de-concessionaria/actions/workflows/pylint.yml/badge.svg)](https://github.com/92username/Sistema-de-concessionaria/actions/workflows/pylint.yml)

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  ![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
# Sistema de Concessionária

Este é um sistema de gerenciamento para uma concessionária, que permite o cadastro de veículos, clientes, vendedores e a realização de vendas. O sistema foi desenvolvido em Python utilizando SQLAlchemy para a interação com o banco de dados SQLite.

## Funcionalidades

- **Cadastro de Veículos**
  - Inclui informações como marca, modelo, ano, cor, câmbio, categoria, valor, quilometragem e placa.

- **Cadastro de Clientes**
  - Registro de clientes com validação de CPF, nome e idade (somente maiores de 18 anos).

- **Cadastro de Vendedores**
  - Cadastro de vendedores, incluindo nome, idade, CPF, salário e cálculo de comissão.

- **Listagens**
  - **Veículos**: Exibe a lista completa dos veículos disponíveis.
  - **Vendedores**: Mostra detalhes como salário, comissão e total a receber.
  - **Clientes**: Apresenta todos os clientes cadastrados.
  - **Vendas**: Lista todas as transações realizadas.

- **Efetuar Venda**
  - Registra a venda de um veículo, calcula automaticamente a comissão do vendedor (5% do valor do veículo) e remove o veículo vendido do sistema.

- **Pesquisa e Filtragem**
  - Permite pesquisar clientes pelo nome ou CPF.

- **Exclusão de Vendedores**
  - Possibilidade de deletar um vendedor após confirmação.

## Como iniciar o projeto

1. **Clone o repositório**
    ```sh
    git clone https://github.com/Vinijanini/Sistema-de-concessionaria.git
    cd Sistema-de-concessionaria
    ```

2. **Instale as dependências**
    - Certifique-se de ter o Python instalado. As dependências estão listadas no código fonte e podem ser instaladas utilizando `pip`:
    ```sh
    pip install sqlalchemy
    ```

3. **Execute o sistema**
    - Inicie o sistema executando o arquivo `menu.py`:
    ```sh
    python menu.py
    ```

## Estrutura do Projeto

- `main.py`: Contém as definições das classes e métodos principais do sistema, como `Veiculo`, `Cliente`, `Vendedor`, `Venda` e `Concessionaria`.
- `menu.py`: Arquivo responsável pelo menu principal do sistema, onde o usuário pode interagir com as funcionalidades oferecidas.
- `__pycache__/`: Diretório que contém os arquivos compilados pelo Python.
- `Leia_me`: Arquivo que contém informações importantes sobre o projeto e suas funcionalidades.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorar este projeto.

**Nota**: Certifique-se de que o arquivo `menu.py` está configurado corretamente para a execução do sistema.

