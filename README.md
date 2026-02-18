

📊 Controle de Despesas Desktop — Python + Tkinter


Uma aplicação desktop desenvolvida em Python para gerenciamento de despesas pessoais, com persistência de dados em Excel e interface gráfica interativa.
Este projeto demonstra integração entre interface gráfica (GUI) e manipulação de dados estruturados, aplicando conceitos práticos de Engenharia de Software.

🎯 Objetivo do Projeto:

-Criar uma solução simples e funcional para controle financeiro pessoal, permitindo:
-Visualização estruturada das despesas
-Edição dinâmica dos dados
-Persistência automática em arquivo Excel
-Tratamento de exceções
-Interface amigável utilizando componentes nativos do Python

🛠️ Stack Tecnológica
Tecnologia	Finalidade:

🐍 Python 3	Linguagem principal
🖼️ Tkinter	Interface gráfica (GUI Desktop)
📊 Pandas	Manipulação e estruturação de dados
📁 OpenPyXL	Escrita e leitura de arquivos Excel
🧠 Arquitetura da Aplicação

A aplicação segue uma estrutura baseada em:
Separação de responsabilidades por funções
Persistência de dados desacoplada da interface
Atualização dinâmica da camada de visualização (Treeview)
Tratamento de exceções para criação automática de planilha
Fluxo de Execução
O sistema tenta carregar despesas.xlsx
Caso não exista, cria um DataFrame vazio
Os dados são renderizados no componente Treeview

O usuário pode:
-Selecionar uma linha
-Editar os campos
-Salvar alterações
-Ao fechar o sistema:
-Os dados são automaticamente persistidos no Excel

🖥️ Interface:

A interface foi construída com:
-ttk.Treeview para exibição tabular
-Campos Entry vinculados via StringVar
-Eventos do Tkinter (<<TreeviewSelect>>)
-Manipulação de estado da aplicação

Essa implementação demonstra domínio de:
-Eventos
-Bindings
-Manipulação dinâmica de componentes GUI
-Sincronização entre UI e dados


<img width="1919" height="1005" alt="controle de despesas" src="https://github.com/user-attachments/assets/e06f5660-c7c6-4160-af78-07dcf80b74de" />




