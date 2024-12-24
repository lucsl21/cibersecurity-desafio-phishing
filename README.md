# Phishing para Captura de Senhas do Facebook

Este projeto demonstra como configurar um ataque de phishing básico usando o **Kali Linux** e o **Social-Engineer Toolkit (SET)** para fins educacionais e de conscientização sobre segurança. **Atenção:** Este projeto deve ser utilizado apenas para fins de aprendizado e em ambientes controlados, com permissão explícita.

---

## ⚙️ Ferramentas Necessárias

- **Kali Linux** (ou qualquer distribuição que suporte o SET)
- **setoolkit** (Social-Engineer Toolkit)

---

## 🛠️ Configurando o Phishing no Kali Linux

## Passo 1: Acessar o Root
Execute o comando abaixo para obter acesso root:

sudo su

## Passo 2: Iniciar o SET
Inicie o Social-Engineer Toolkit:
setoolkit

## Passo 3: Escolher o Tipo de Ataque
Selecione Social-Engineering Attacks no menu inicial;
Escolha Web Site Attack Vectors como o vetor de ataque.
![menu](https://github.com/user-attachments/assets/32d3b525-27de-4e91-a671-699b308e5136)


## Passo 4: Configurar o Método de Ataque
Escolha Credential Harvester Attack Method;
Selecione Site Cloner como o método de ataque.
![metodo](https://github.com/user-attachments/assets/6be46695-2106-46df-84da-43c69d643432)


## Passo 5: Configurar a URL para Clonagem
Insira o endereço do site que será clonado. Para este exemplo, utilizaremos o Facebook:
http://www.facebook.com
![login_facebook](https://github.com/user-attachments/assets/20fe6786-7a40-4af7-a9e6-cb5019ee57f7)


📊 Resultados
Quando a vítima acessar o site clonado e inserir suas credenciais, os dados serão registrados no terminal do Kali Linux. Verifique as informações capturadas no console do SET.
![image](https://github.com/user-attachments/assets/dfb929ec-1507-4c03-9090-16a8f62eadcf)



🚨 Aviso Legal
Este projeto foi desenvolvido apenas para fins educacionais e de conscientização sobre segurança. Qualquer uso indevido que viole leis ou regulamentos é de responsabilidade exclusiva do usuário. A prática de phishing é ilegal e antiética se feita sem permissão explícita.

