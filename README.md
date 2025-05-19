# azure-maquina-virtual
Desafio - Azure na Prática (DIO)

# 🚀 Laboratório Prático - Criação de Máquina Virtual na Microsoft Azure

Este repositório faz parte do desafio prático da plataforma [DIO](https://www.dio.me), com o objetivo de aplicar e documentar os conhecimentos adquiridos sobre o uso da plataforma de nuvem **Microsoft Azure**. Aqui você encontrará anotações, dicas e o passo a passo para a criação de uma Máquina Virtual (VM) no Azure, servindo como material de apoio para revisões e futuras implementações.

---

## 🎯 Objetivo do Desafio

- Criar e configurar uma máquina virtual na Azure.
- Documentar o processo de forma clara e organizada.
- Compartilhar a documentação utilizando um repositório público no GitHub.

---

## 🧠 Conhecimentos Aplicados

- Conceitos básicos de computação em nuvem
- Navegação e uso do portal Azure
- Criação e configuração de máquinas virtuais
- Segurança e boas práticas na nuvem
- Gerenciamento de recursos via portal

---

## ☁️ O que é a Azure?

A Microsoft Azure é uma plataforma de computação em nuvem que oferece mais de 200 produtos e serviços em nuvem, incluindo:
- Máquinas Virtuais (VMs)
- Armazenamento
- Bancos de dados
- Redes
- Inteligência Artificial

---

## 🛠️ Passo a Passo: Criando sua VM no Azure

### 1. Criar Conta Gratuita
Acesse [https://azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free) e crie sua conta com crédito gratuito.

### 2. Acesse o Portal Azure
Entre em: [https://portal.azure.com](https://portal.azure.com)

### 3. Criar a Máquina Virtual
1. No menu lateral, clique em **"Máquinas Virtuais"**
2. Clique em **"Criar" > "Máquina virtual"**
3. Preencha os dados da instância:
   - Grupo de Recursos: `grupo-laboratorio`
   - Nome da VM: `vm-desafio-dio`
   - Região: Ex: `Brazil South`
   - SO: Windows Server 2022 / Ubuntu LTS
   - Tamanho: B1s (grátis para conta free)
   - Usuário e Senha/Chave SSH
4. Configurar regras de porta (RDP para Windows ou SSH para Linux)
5. Revisar e criar

---

## 🔗 Acessando sua VM

- **Windows:** Use o cliente de área de trabalho remota (RDP)
- **Linux:** Use o terminal com o comando:
```bash
ssh usuario@ip_da_vm
```

## 🔐 Dicas de Segurança

- Desative VMs quando não estiver usando
- Use firewall e regras de IP
- Nunca exponha senhas diretamente

## 💡 Dicas Gerais

- Acompanhe os custos pelo painel da Azure
- Use imagens otimizadas (Ubuntu Server LTS, Windows Server Core)
- Teste o acesso remoto após criação
- Faça snapshots antes de grandes alterações

## ✍️ Autor

- João — Estudante de Engenharia de Software  
- LinkedIn: [https://www.linkedin.com/in/joão-carlos-oliveira-passos-352298175/](https://www.linkedin.com/in/joão-carlos-oliveira-passos-352298175/)

