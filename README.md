# Como-configurar-uma-Maquina-virtual
# Instalação e Configuração do Oracle VirtualBox

Tutorial completo de instalação e configuração do Oracle VirtualBox para criação de laboratórios virtuais.

---

## 📌 Sobre

Este projeto mostra como instalar e configurar o Oracle VirtualBox para criar máquinas virtuais utilizadas em estudos de TI, servidores, redes e segurança da informação.

---

## 🚀 O que é o VirtualBox?

O Oracle VirtualBox é um software de virtualização que permite executar vários sistemas operacionais dentro do mesmo computador.

Exemplos:
- Windows
- Linux
- Kali Linux
- Ubuntu Server

---

## 🖥️ Requisitos

### Requisitos mínimos
- 8GB RAM
- Processador com virtualização habilitada
- 50GB livres no SSD/HD

### Recomendado
- 16GB RAM
- SSD

---

## 📥 Download do VirtualBox

Site oficial:

https://www.virtualbox.org/

---

## 📥 Download do Extension Pack

https://www.virtualbox.org/wiki/Downloads

O Extension Pack habilita:
- USB 2.0/3.0
- Melhor suporte de dispositivos
- Área de transferência avançada

---

## ⚙️ Como Instalar

### 1. Baixe o instalador

Acesse o site oficial e escolha seu sistema operacional.

### 2. Execute o instalador

Clique em:
- Next
- Install
- Finish

---

## 🔧 Habilitar Virtualização na BIOS

Antes de usar:
- Reinicie o computador
- Entre na BIOS
- Ative:
  - Intel VT-x
  - AMD-V

---

## 🖥️ Criando uma Máquina Virtual

### Passo 1
Clique em "Novo".

### Passo 2
Escolha:
- Nome da VM
- Sistema operacional
- Versão

### Passo 3
Defina:
- Memória RAM
- Disco virtual

---

## 💿 Instalando um Sistema Operacional

Baixe uma ISO:

### Ubuntu
https://ubuntu.com/download

### Kali Linux
https://www.kali.org/get-kali/

Depois:
- Vá em Configurações
- Armazenamento
- Selecione a ISO

---

## 🌐 Configuração de Rede

### NAT
Usa internet automaticamente.

### Bridge
A VM aparece como outro computador na rede.

### Host-only
Rede isolada entre host e VM.

---

## 🔐 Laboratório de TI

Exemplos de laboratórios:
- Windows Server
- Active Directory
- Kali Linux
- Redes
- Docker
- Segurança ofensiva
- APIs Spring Boot

---

## 🛠️ Problemas Comuns

### Virtualização desabilitada
Erro:
``` id="z0t7qw"
VT-x is disabled in BIOS
```

Solução:
- Ativar virtualização na BIOS.

---

### Lentidão
Solução:
- Aumentar RAM da VM
- Usar SSD
- Fechar programas pesados

---

## 📚 Aprendizados

- Virtualização
- Redes
- Sistemas operacionais
- Administração de servidores
- Segurança da informação

---

## 👩‍💻 Autor

Emanuelly Queiroz

GitHub:
LinkedIn:

