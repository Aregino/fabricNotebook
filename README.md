---

# FabricNoteBook

Bem-vindo ao repositório **FabricNoteBook**, onde você encontrará orientações sobre a configuração do ambiente Spark no **Microsoft Fabric**, além de como instalar bibliotecas e utilizar notebooks para suas necessidades de Engenharia de Dados e Ciência de Dados.

## 📑 Índice
1. [Introdução](#introdução)
2. [Criando o Ambiente Spark](#criando-o-ambiente-spark)
3. [Iniciando o Notebook](#iniciando-o-notebook)
4. [Instalando Bibliotecas](#instalando-bibliotecas)
5. [📚 Documentação](#-documentação)

---

## Introdução

Neste guia, vamos explorar como configurar o Spark no **Fabric**, instalar bibliotecas adicionais e utilizar notebooks dentro desse ambiente. O objetivo é ajudar você a configurar um ambiente de dados robusto e eficiente.

---

## Criando o Ambiente Spark

Para criar o ambiente Spark no Microsoft Fabric, siga os passos abaixo:

1. Acesse o **Workspace** em **Engenharia de Dados** ou **Ciência de Dados**.
2. Configure as opções do **Apache Spark**.
3. No campo **Pool**, defina as configurações mínimas para o pool de Spark que você deseja usar.
   
   ![Configurações do Pool](https://github.com/user-attachments/assets/842cb16d-6309-4d0f-9fc3-13466fae1857)
   
4. Escolha a versão do Spark que será utilizada no ambiente.

   ![Versão do Spark](https://github.com/user-attachments/assets/1c19c96a-ab85-421c-81b6-ebb29d38e828)

---

## Iniciando o Notebook

1. No seu **Workspace**, selecione a opção **Novo Item**.
   
   ![Novo Notebook](https://github.com/user-attachments/assets/65c65dbc-7126-443b-8de8-8d394293dead)
   
2. O sistema abrirá o notebook, e você poderá selecionar o ambiente configurado ou usar o padrão.
   
   ![Selecionar Ambiente](https://github.com/user-attachments/assets/54185954-3848-43d6-a5bc-f8c5b0102e00)

---

## Instalando Bibliotecas

1. Ao clicar no ícone do ambiente, uma nova janela será aberta com as configurações do ambiente.
   
   ![Configurações do Ambiente](https://github.com/user-attachments/assets/d76e90fd-e5be-4d78-a588-87410e89119a)
   
2. Na seção **Bibliotecas Públicas**, você pode instalar as bibliotecas necessárias que não estão incluídas por padrão. Isso tornará as bibliotecas disponíveis para qualquer notebook que utilize esse ambiente.

   ![Instalando Bibliotecas](https://github.com/user-attachments/assets/20e177af-50e9-4877-98da-46e602dbb801)

   - **Nota**: Nem todas as bibliotecas estão disponíveis via Conda, então você pode precisar gerenciar as dependências manualmente, entretanto instalando via Conda ele verifica as dependências.
   
3. Em **Compute**, defina qual pool será aplicado ao ambiente criado. Também é possível ajustar a capacidade do pool conforme suas necessidades.

   ![Capacidade do Pool](https://github.com/user-attachments/assets/bd100b8f-db63-4aaf-af15-ecd570b1e96f)

---

## 📚 Documentação

- [Ambiente](https://learn.microsoft.com/pt-br/fabric/data-engineering/environment-manage-compute)
- [Notebooks](https://learn.microsoft.com/pt-br/fabric/data-engineering/how-to-use-notebook)
- [Workspace](https://learn.microsoft.com/pt-br/fabric/get-started/workspaces)

---
