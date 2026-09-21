# 🍷 Projeto: Vinheria Agnello
Animação gráfica da logo (tela de carregamento) utilizando o Blackboard Arduino Uno R3 com o Display LCD 16x2 I2C. Criada para o projeto Vinheria Agnello da FIAP.

## 🛠️ Materiais Utilizados
* **1x** Arduino Uno (Blackboard Arduino Uno R3)
* **1x** Display LCD 16x2 com adaptador I2C
* **4x** Fios Jumper (Macho-Fêmea)

## 🔌 Conexões (Pinagem I2C)
**GND** -> GND | **VCC** -> 5V | **SDA** -> A4 | **SCL** -> A5

## 📦 Bibliotecas Necessárias
Para que o código funcione, é preciso instalar a biblioteca no Arduino IDE:
1. Abra o programa Arduino IDE.
2. Clique no canto superior esquerdo **Sketch** > **Include Library** > **Manage Libraries... or Ctrl + Shift + I**.
3. Pesquise por **LiquidCrystal_I2C** by Martin Kubovčík, Frank de Brabander.
4. Clique em **Install**.

*(Opcional: Caso o seu display não acender ou mostrar caracteres estranhos, pode ser necessário rodar um script de I2C Scanner para descobrir o endereço hexadecimal do seu módulo, que geralmente é "0x27" ou "0x3F").*

## 🚀 Como Executar no Arduino IDE
1. Clone este repositório ou faça o download dos arquivos em formato ZIP.
2. Abra o arquivo ".ino" no Arduino IDE.
3. Conecte o seu Arduino Uno ao computador via cabo USB.
4. Clique em **Tools** > **Board** > **Arduino AVR Boards** e selecione o modelo correto do seu Arduino.
5. Clique em **Tools** > **Port** e selecione a porta COM correspondente.
6. Clique no botão **Upload** (ícone de seta para a direita) para compilar e carregar o código para o Arduino.

## 💻 Integrantes do Projeto
**Flávia Sirahata Hasegava**, **Eduardo Ambra Giordano de Castro**, **Gabriel Souza Bore de Carvalho**, **Lirity Ribeiro de Paiva** e **Nicolle Lima Nascimento**.

## 📄 Licença
Este projeto está licenciado sob a licença [MIT](LICENSE).
