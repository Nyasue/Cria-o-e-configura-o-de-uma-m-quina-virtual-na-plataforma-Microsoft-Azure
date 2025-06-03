## Como criar e configurar uma máquina virtual na plataforma Microsoft Azure
<sub> Prática do processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure.

---

## O que é o Modelo Cloud (Nuvem): 
- é uma infraestrutura baseada na internet, onde empresa ou usuário utiliza **recursos de TI** de um provedor externo, exemplo os fornecedores de nuvem, como **Amazon Web Services (AWS)**, **Microsoft Azure** ou **Google Cloud**. Ao invés de a empresa ou usuário precisar dispor de ter servidores, bancos de dados e outros sistemas dentro de suas intalações, as empresas alugam o serviço de cloud.
  - ***Ou seja, pode-se aumentar ou diminuir a capacidade dos serviços de acordo com a necessidade, sem precisar de investimento em infraestrutura própria, reduzindo assim os custos, melhora a agilidade e o acesso a serviços avançados que seriam difíceis de implementar localmente***

 ---
 
## O que são máquinas virtuais:
- Máquinas Virtuais (VMs) são computadores emulados *(reprodução do comportamento de um sistema computacional em outro, mesmo que seja incopatível de forma natural)* por software, que funcionam como se fossem máquinas físicas, mas são executadas em servidores hospedados na nuvem. Quando você usa o Azure, a criação de VMs faz parte do serviço Infrastructure as a Service (IaaS), no Azure, por exemplo, você pode criar uma VM com o sistema operacional de sua escolha (Windows, Linux, etc.) e configurar o hardware virtual (CPU, memória, disco, etc.), de acordo com suas necessidades.
## As VMs servem para:
- **Ambientes de Desenvolvimento e Testes:** Você pode criar VMs para desenvolver e testar aplicativos em ambientes isolados e controlados.
- **Hospedagem de Aplicações e Sites:** As VMs podem hospedar servidores web, bancos de dados e serviços de backend.
- **Execução de Softwares Legados:** Caso você tenha aplicativos que dependem de um sistema operacional ou ambiente específico, é possível migrá-los para uma VM na nuvem.
- **Laboratórios e Treinamentos:** Você pode criar múltiplas VMs para treinar equipes de TI ou estudantes em diferentes tecnologias.


## 🌐 Agora vamos aprender como criar e configurar uma VMs no ambiente Azure

### 1️⃣ Acesse o Portal do Azure
- Abra o navegador e vá para [https://portal.azure.com](https://portal.azure.com).
- Faça login com sua conta Microsoft.

---

### 2️⃣ Crie uma Máquina Virtual
- No painel esquerdo, clique em **Máquinas Virtuais** ou pesquise por **Virtual Machines**.
- Clique em **+ Criar** e selecione **Máquina virtual**.

---

### 3️⃣ Configure as Informações Básicas
- **Assinatura:** Escolha a assinatura de cobrança desejada.
- **Grupo de Recursos:** Crie um novo grupo ou selecione um já existente.
- **Nome da VM:** Escolha um nome (ex.: `vm-winserver2025`).
- **Região:** Escolha a região desejada (ex.: Brasil Sul).
- **Imagem:** Selecione **Windows Server 2025** (ou a versão mais recente disponível).

---

### 4️⃣ Selecione o Tamanho da VM
- Clique em **Selecionar tamanho**.
- Escolha o tamanho adequado para sua necessidade (ex.: `B2ms` para uso básico).
- Clique em **Selecionar**.

---

### 5️⃣ Configure Usuário e Senha
- **Nome de usuário:** Crie um nome de administrador (ex.: `adminuser`).
- **Senha:** Defina uma senha forte e confirme.
⚠️ Importante: Anote a senha para usar no acesso remoto à VM.

---

### 6️⃣ Configure a Rede
- Deixe a maioria das opções no padrão.
- Verifique se a **porta 3389 (RDP)** está habilitada para acesso remoto.

---

### 7️⃣ Revisar e Criar
- Clique em **Revisar + Criar**.
- Aguarde a validação das configurações.
- Clique em **Criar** para iniciar o provisionamento.

---

### 8️⃣ Acompanhe o Provisionamento
- Aguarde alguns minutos até a VM ser criada.

---

### 9️⃣ Conectar à VM
- Acesse a página da VM no Azure.
- Clique em **Conectar > RDP**.
- Baixe o arquivo `.rdp` e abra-o.
- Insira o nome de usuário e senha configurados.

---

### 1️⃣0️⃣ Aproveite!
- Agora você tem uma VM Windows Server 2025 rodando no Azure.
- Instale seus aplicativos, configure seus serviços e comece a usar!

---

## 📌 Observações
- Ao terminar de usar a VM, pare ou exclua para evitar cobranças.
- Monitore o uso e os custos através do painel do Azure.
- Lembre-se de manter sua senha em local seguro.

---

## Bons estudos e boas práticas!
