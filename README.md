# Sistema de Gerenciamento de Transações Financeiras

Este é um sistema de gerenciamento de transações financeiras desenvolvido em Python. Ele oferece uma interface gráfica simples e intuitiva para inserir, visualizar e excluir transações financeiras, além de fornecer uma visão geral dos custos e vendas totais.

## Funcionalidades

- **Inserir Transação:** Adicione novas transações, incluindo o código do produto, a data da transação e os valores de compra e venda.
- **Visualizar Transações:** As transações são exibidas em uma tabela interativa, permitindo que os usuários vejam os detalhes de cada transação.
- **Excluir Transação:** Remova transações selecionadas da tabela.
- **Limpar Lista:** Opção para limpar todas as transações armazenadas no banco de dados.

## Destaque de Produtos

O sistema apresenta uma lista de produtos disponíveis, onde os códigos de produtos específicos são destacados com uma cor de fundo vermelha para identificação visual rápida.

## Bibliotecas Utilizadas

- **Tkinter:** Utilizada para desenvolver a interface gráfica do usuário.
- **SQLite3:** Usada para interagir com o banco de dados SQLite e armazenar as transações.
- **tkcalendar:** Fornece um widget de calendário para seleção de datas na interface.
- **tkinter.ttk:** Utilizada para criar widgets temáticos para a interface, como a Treeview, uma tabela interativa para exibir as transações.

As bibliotecas estão listadas no arquivo `requirements.txt` para facilitar a instalação das dependências do projeto.

## Como Usar

1. Certifique-se de ter Python instalado em seu sistema.
2. Clone este repositório em seu computador.
3. Instale as dependências do projeto executando o seguinte comando:
   ```bash
    pip install -r requirements.txt
5. Execute o programa digitando o seguinte comando:
   ```bash
    python main.py


## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório, abrir uma issue ou enviar um pull request com melhorias ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
