# 🛰️ Athena Educacional - Simulador C2 inspirado no Vault 7

Este projeto é um **simulador educacional** inspirado nas ferramentas **Athena/Hera** do Vault 7, com o objetivo de demonstrar conceitos de **Comando e Controle (C2)** e segurança ofensiva em um ambiente controlado.

⚠️ **Aviso:** Este projeto é **apenas para fins educacionais**. Não utilize em redes reais ou sistemas sem autorização explícita.

## 📂 Estrutura do Projeto

- implant/ - Cliente implantável com módulos
- lp_server/ - Servidor C2
- shared/ - Configurações compartilhadas
- README.md - Documentação

## 🚀 Requisitos

- Python 3.8+
- pip install flask requests pynput pillow

## ▶️ Como Usar

### Servidor
```
cd lp_server
```
```
python app.py
```
### Cliente
```
cd implant/client
```
```
python agent.py
```
