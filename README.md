# Phishing para Captura de Senhas do Facebook

Este projeto demonstra como configurar um ataque de phishing básico usando o **Kali Linux** e o **Social-Engineer Toolkit (SET)** para fins educacionais e de conscientização sobre segurança. **Atenção:** Este projeto deve ser utilizado apenas para fins de aprendizado e em ambientes controlados, com permissão explícita.

---

## ⚙️ Ferramentas Necessárias

- **Kali Linux** (ou qualquer distribuição que suporte o SET)
- **setoolkit** (Social-Engineer Toolkit)

---

## 🛠️ Configurando o Phishing no Kali Linux

### Passo 1: Acessar o Root
Execute o comando abaixo para obter acesso root:
```bash
sudo su
---


### Passo 2: Iniciar o SET
Inicie o Social-Engineer Toolkit:
setoolkit

---

### Passo 3: Escolher o Tipo de Ataque
Selecione Social-Engineering Attacks no menu inicial.
Escolha Web Site Attack Vectors como o vetor de ataque.

#### Passo 4: Configurar o Método de Ataque
Escolha Credential Harvester Attack Method.
Selecione Site Cloner como o método de ataque.

### Passo 5: Configurar a URL para Clonagem
Insira o endereço do site que será clonado. Para este exemplo, utilizaremos o Facebook:
http://www.facebook.com

📊 Resultados
Quando a vítima acessar o site clonado e inserir suas credenciais, os dados serão registrados no terminal do Kali Linux. Verifique as informações capturadas no console do SET.

🚨 Aviso Legal
Este projeto foi desenvolvido apenas para fins educacionais e de conscientização sobre segurança. Qualquer uso indevido que viole leis ou regulamentos é de responsabilidade exclusiva do usuário. A prática de phishing é ilegal e antiética se feita sem permissão explícita.

