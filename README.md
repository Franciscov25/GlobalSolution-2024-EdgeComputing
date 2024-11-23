# Energia Verde - Global Solution🌍 - 1ESPA - Primeiro Semestre de 2024

## Professor: 
- Professor Fábio Cabrini
## 👤Membros do Grupo - **Code Nexus**:
- [**Francisco Vargas**](https://github.com/Franciscov25) - RM560322
- [**Matheus Irizawa**](https://github.com/Matheus-Eiki) - RM559483
- [**Kayque Carvalho**](https://github.com/Kat-Carv) - RM561189

## 💡Descrição do Projeto:
- **O problema que procuramos resolver com este projeto é o alto consumo de energia elétrica pela população na utilização de alguns elétrodomésticos. Para isso nosso projeto utiliza o sensor TMP para a medição da temperatura ambiente, dependendo da sua medida além de aparecer no LCD, o mesmo pode tanto acionar o motor para a direção programada conforme a temperatura ou apenas desligar o motor para a economia de energia elétrica.**

## 📚Componentes Utilizados:
- **Arduino Uno R3** ou **Arduino Nano**
- **Tela LCD 16x2**
- **Conversor Serial I2C**
- **Sensor TMP**
- **Bateria 9V**
- **Motor CC**
- **Acionador de motor**

## Linguagem:
- **Linguagem em C++** 
 
## 📍Pinagem:
- **Sensor de temperatura TMP pino - A0**
- **Acionamento do motor pino - 3**
- **Movimentação do motor pinos - 5 e 6**
- **LCD 16x2 I2C pinos - A4 e A5**

## 👨🏽‍💻Funcionamento:
- **Apertar em iniciar simulação**
- **O LCD I2C irá ser iniciado mostrando a logo e logo em seguida somente os dados de temperatura que são atualizados a cada 3 segundos**
- **Clicar no TMP para criar uma variação na temperatura, os intervalos a seguir mostram os efeitos de cada um:**
  - **Menor que 15ºC**
    - **O motor vai ser ativado e irá rodar na direção programada**
  - **Entre 15ºC e 25ºC**
    - **O motor será ou desligado ou continuará em repouso**
  - **Mais que 25ºC**
    - **O motor vai ser ativado e irá rodar na direção programada**
## ⚙️Exemplo de Montagem
![exmontagem](https://github.com/user-attachments/assets/a94e70a1-08ff-4138-983f-fd2a015ab414)


## ❓Como instalar e rodar o projeto?
1. Conecte os fios e componentes conforme o esquema elétrico providenciado com a placa desconectada.
2. Conecte a placa ao PC.
3. Usando uma IDE compatível com a linguagem C++ e as bibliotecas do Arduino (como o Arduino IDE), cole o código-fonte do projeto no IDE, compile e faça o *upload* para a placa.
4. A instalação está completa!
