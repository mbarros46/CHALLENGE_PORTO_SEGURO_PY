# 🔷 Porto Seguro - Sistema de Gerenciamento de Usuários e Serviços

## 📌 Descrição do Projeto
O **Sistema de Gerenciamento de Usuários e Serviços** foi desenvolvido como parte de um projeto acadêmico em parceria com a **Porto Seguro**. Seu objetivo é facilitar o gerenciamento de usuários e serviços oferecidos pela seguradora, permitindo:
- Cadastro, consulta, atualização e exclusão de usuários
- Agendamento de serviços
- Simulação de cotações de seguro

Este sistema aprimora a organização e eficiência na administração das informações.

---

## 🚀 Funcionalidades
✅ **Cadastro de Usuários**: Permite o registro de novos usuários com validação de dados.  
✅ **Consulta de Usuários**: Pesquisa usuários cadastrados pelo CPF.  
✅ **Atualização de Dados**: Atualiza os dados cadastrais dos usuários.  
✅ **Exclusão de Usuários**: Remove usuários cadastrados pelo CPF.  
✅ **Agendamento de Serviços**: Agenda serviços como revisão, troca de óleo, reparo de sinistro e higienização.  
✅ **Simulação de Cotação de Seguro**: Simula cotações de seguro com base no modelo e ano do veículo.  
✅ **Suporte ao Cliente**: Fornece informações de contato para suporte.  
✅ **Histórico de Agendamentos**: Exibe os serviços já agendados.  
✅ **Exportação de Dados**: Salva os dados dos usuários em um arquivo **JSON** e no **Oracle Database**.  

---

## 🛠️ Tecnologias Utilizadas
- **Python** 🐍 - Linguagem principal do projeto  
- **Oracle Database** 🛢️ - Banco de dados para armazenamento  
- **Pandas** 📊 - Manipulação e exportação de dados  
- **JSON** 📄 - Formato de exportação de dados  
- **Requests** 🔗 - Biblioteca para requisições HTTP à API **ViaCEP**  

---

## ▶️ Como Executar

1️⃣ **Instale as dependências**:
```bash
pip install oracledb pandas requests
```

2️⃣ **Configure a conexão com o banco de dados**:
- Atualize as credenciais de conexão no método `gerar_conexao`.

3️⃣ **Execute o script**:
```bash
python porto_seguro.py
```

---

📢 Projeto acadêmico desenvolvido para aprimorar a gestão de usuários e serviços na Porto Seguro! 🚗🔧

