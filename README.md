# 🚀 Cockpit Client Linux Management

![Cockpit Logo](https://cockpit-project.org/images/cockpit.png)

Bem-vindo ao meu projeto! Aqui demonstro como usar o **Cockpit Client** para gerenciar servidores Linux de forma segura através de uma **interface gráfica moderna**. 🎛️💻

---

## 📝 Sobre o Projeto

O objetivo deste projeto é:

- Configurar e conectar servidores Linux via **Cockpit Client**
- Monitorar recursos do sistema (CPU, memória, armazenamento) 📊
- Gerenciar usuários, serviços e logs de forma segura 🔐
- Facilitar operações administrativas sem usar apenas a linha de comando 🖱️

---

## ⚡ Funcionalidades

- ✅ Interface gráfica web intuitiva  
- ✅ Gerenciamento de múltiplos servidores simultaneamente  
- ✅ Monitoramento em tempo real  
- ✅ Controle de serviços, containers e contas de usuário  
- ✅ Suporte a conexões seguras (HTTPS/SSH) 🔒

---

## 🖥️ Instalação

Para instalar o Cockpit Client no seu servidor Linux:

```bash
# Em distribuições baseadas em Debian/Ubuntu
sudo apt update
sudo apt install cockpit

# Em distribuições baseadas em RedHat/CentOS/Fedora
sudo yum install cockpit
sudo systemctl enable --now cockpit.socket