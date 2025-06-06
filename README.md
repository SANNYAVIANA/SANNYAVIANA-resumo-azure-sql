# SANNYAVIANA-resumo-azure-sql
# 💾 Criando uma Instância de Banco de Dados no Microsoft Azure

# 🎯 Objetivos

- Criar uma instância de banco de dados SQL no Azure
- Entender os principais conceitos da solução PaaS para bancos de dados
- Documentar a experiência como material de apoio para estudos futuros
- Praticar o uso do GitHub para organização e publicação de conteúdo técnico

# 🛠️ Passo a Passo: Criando o Banco de Dados SQL no Azure

1. **Acessando o portal do Azure:**
   👉 [https://portal.azure.com](https://portal.azure.com)

2. **No menu lateral, clique em "SQL databases"**

3. **Clique em "Criar"**

4. **Preencha os campos principais:**
   - **Nome do banco:** `db-estudo-azure`
   - **Assinatura:** selecione a disponível
   - **Grupo de recursos:** crie um novo ou selecione um existente (ex: `grupo-sql`)
   - **Servidor:** clique em "Criar novo"
     - Nome do servidor: `sql-server-sannya`
     - Local: Brazil South
     - Autenticação: SQL Authentication
     - Usuário administrador e senha: crie com segurança

**Imagens:**

![1](https://github.com/user-attachments/assets/c9d8570c-65f5-482a-87e6-00843a4c87f5)
![criando servidor](https://github.com/user-attachments/assets/985918b0-6ae9-4e21-bd03-daa9d7041492)



5. **Configurar desempenho:**  
   - Utilize a camada gratuita (se disponível) ou a mais básica (ex: DTU: Basic)

6. **Avance com as opções padrão nas próximas abas e clique em "Revisar + Criar"**

7. **Aguarde a implantação e clique em “Ir para o recurso”**

**Imagens:** 
![3](https://github.com/user-attachments/assets/a6c5e66d-cafd-4f34-b29a-372482ecbcda)
![4](https://github.com/user-attachments/assets/3a473412-6044-483d-9784-55f9bfd7c4d2)


# 💡 Dicas Importantes

- Lembre-se de anotar o nome do servidor, usuário e senha para conexão.
- Configure corretamente as regras de firewall para conseguir se conectar.
- Ao finalizar o uso, **pause ou exclua o recurso** para evitar cobranças.


## 📝 Anotações Pessoais

- O SQL do Azure é uma solução ideal para quem deseja focar no desenvolvimento sem se preocupar com manutenção do servidor.
- Gostei da simplicidade da interface do Azure e da rapidez da criação.
- As aulas do laboratório ajudaram a reforçar conceitos práticos de banco de dados em nuvem.


# 🔗 Links úteis

- [Documentação oficial do Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- [GitHub para iniciantes](https://docs.github.com/pt/get-started/quickstart)


# ✨ Conclusão

Esse laboratório me ajudou a colocar em prática conceitos importantes sobre bancos de dados em nuvem e a entender os benefícios de uma solução PaaS como o Azure SQL Database. Estou confiante de que esse conhecimento será útil em projetos futuros.


📌 *Feito com 💙 por Sannya Viana*


