# 🚀 Desafio DIO: Laboratório de Máquinas Virtuais na Azure

Este projeto tem como objetivo **consolidar os conhecimentos adquiridos sobre máquinas virtuais (VMs) na plataforma Microsoft Azure**, aplicando conceitos de infraestrutura em nuvem e registrando todo o processo técnico de forma clara, organizada e reprodutível.  

Ao longo da prática, foi possível compreender o funcionamento de uma VM, desde sua criação até a configuração final, explorando recursos fundamentais de **rede, armazenamento, autenticação e monitoramento**.

---

## 🧠 Objetivos de Aprendizagem

- 🖥️ **Provisionar** e configurar uma máquina virtual no Azure  
- ⚙️ Entender os principais componentes de uma VM: **rede, disco, sistema operacional e segurança**  
- 📝 **Documentar tecnicamente** o processo de criação, configuração e ajustes realizados  
- 🌐 Utilizar o **GitHub** como ferramenta de versionamento, registro de práticas e compartilhamento técnico  

---

## 🛠️ Tecnologias Utilizadas

- [**Microsoft Azure**](https://portal.azure.com) → Ambiente de provisionamento e gerenciamento em nuvem  
- **Ubuntu Pro 24.04 LTS** → Sistema operacional da VM utilizada no laboratório  
- **Git e GitHub** → Versionamento de código e documentação do projeto  
- **Markdown** → Criação de documentação clara, estruturada e multiplataforma  

---

## 📋 Etapas Realizadas

### 1. Criação da VM no Portal do Azure
- **Tipo**: Ubuntu Server 22.04 LTS  
- **Tamanho**: Standard_B1s (custo reduzido e ideal para testes)  
- **Rede**: Porta SSH habilitada para acesso remoto seguro  
- **Autenticação**: Chave pública/privada ou credenciais de usuário e senha  

### 2. Acesso Remoto à VM
- Estabelecida conexão via **SSH** com sucesso, validando o funcionamento da rede e das credenciais.  

### 3. Configurações Adicionais
- Atualização completa do sistema operacional  
- Instalação de pacotes essenciais para administração (**curl, git, htop, unzip, etc.**)  
- Validação da integridade do sistema após as configurações  

---

## 🧩 Desafios e Soluções

Durante o laboratório, alguns obstáculos surgiram e foram resolvidos:  

- 🔐 **Erro de conexão SSH** → solucionado por meio de ajustes nas regras de firewall e validação da chave pública configurada  
- 🧭 **Escolha do tamanho ideal da VM** → superado com consulta à documentação oficial da Azure e análise de custo-benefício para ambientes de laboratório  

---

## ✅ Conclusão

Este laboratório demonstrou, na prática, como a **Azure simplifica a criação e o gerenciamento de máquinas virtuais**, permitindo que qualquer profissional ou estudante configure um ambiente completo em poucos minutos.  

Além de consolidar conceitos de **infraestrutura em nuvem**, a atividade reforçou a importância de:  

- Planejar os recursos de forma eficiente  
- Aplicar boas práticas de segurança (como autenticação por chave pública)  
- Monitorar custos e consumo de recursos em tempo real  

👉 A experiência prática torna os conceitos muito mais claros, preparando o aluno para **cenários reais de uso corporativo da nuvem**.
