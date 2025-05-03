## **Especificações de Hardware da FLSun V400**

A FLSun V400 é uma impressora 3D de alta velocidade que utiliza um sistema de movimento delta. Aqui estão as suas especificações de hardware detalhadas:

### **Geral**

* **Tecnologia de Impressão:** FDM (Modelagem por Deposição Fundida)  
  * A Modelagem por Deposição Fundida, ou FDM, é um processo de impressão 3D que constrói objetos camada por camada, depositando material fundido. Na FLSun V400, o filamento de plástico é alimentado através de um bico aquecido, onde é derretido e extrudado em caminhos precisos com base no modelo digital. Este processo é repetido camada por camada até que o objeto 3D esteja completo. A tecnologia FDM é conhecida por sua versatilidade, usando uma ampla gama de termoplásticos, incluindo PLA, ABS, PETG e TPU.  
* **Tipo de Impressora:** Delta  
  * A FLSun V400 emprega uma configuração de impressora delta, distinta das impressoras cartesianas mais comuns. Em uma impressora delta, o cabeçote de impressão é suspenso por três braços que se movem em conjunto para posicionar o bico. Este projeto permite movimentos rápidos e precisos do cabeçote de impressão, o que é crucial para atingir as altas velocidades de impressão pelas quais a V400 é conhecida. As impressoras delta também são frequentemente elogiadas por sua alta relação altura-largura, permitindo a impressão de objetos mais altos em uma área de base menor.  
* **Velocidade Máxima de Impressão:** 600mm/s  
  * Uma das características de destaque da FLSun V400 é sua impressionante velocidade máxima de impressão de 600mm/s. Esta velocidade supera em muito as capacidades das impressoras 3D FDM tradicionais, permitindo tempos de impressão significativamente mais curtos. A capacidade de imprimir em velocidades tão altas é resultado de vários fatores, incluindo o design leve e rígido do sistema de movimento delta, o poderoso sistema de controle e o firmware Klipper otimizado.  
* **Aceleração Máxima:** 20000mm/s²  
  * Além da alta velocidade de impressão, a FLSun V400 também possui uma notável aceleração máxima de 20000mm/s². A aceleração refere-se à rapidez com que o cabeçote de impressão pode alterar sua velocidade de movimento. Uma aceleração mais alta permite que a impressora faça movimentos mais rápidos e precisos, reduzindo o tempo necessário para imprimir objetos com formas e detalhes complexos. Esta alta aceleração contribui para a capacidade geral da impressora de imprimir rapidamente, mantendo a qualidade da impressão.  
* **Volume de Construção:** ø300 x 410 mm  
  * A FLSun V400 oferece um volume de construção cilíndrico considerável de ø300 x 410 mm. Este grande volume de construção permite a impressão de objetos grandes ou vários objetos menores em uma única impressão. O diâmetro de 300 mm refere-se à largura da área de impressão circular, enquanto a altura de 410 mm indica a altura máxima do objeto que pode ser impresso. Este generoso volume de construção torna a V400 adequada para uma ampla gama de aplicações de impressão 3D, desde prototipagem e modelagem até produção de peças funcionais.  
* **Firmware:** Klipper  
  * A FLSun V400 é alimentada pelo firmware Klipper, conhecido por seu alto desempenho e flexibilidade. O Klipper utiliza uma arquitetura de computação dupla, onde os cálculos de movimento de alta velocidade são executados em um microcontrolador, enquanto os comandos de nível superior são processados em um computador mais poderoso, como um Raspberry Pi. Esta arquitetura permite velocidades de impressão e acelerações mais altas do que o firmware tradicional, mantendo a precisão e a qualidade da impressão. O Klipper também oferece recursos avançados como modelagem de ressonância (input shaping), que ajuda a reduzir artefatos de toque (ringing) em impressões de alta velocidade.  
* **Interface:** Tela de toque de 7 polegadas  
  * A FLSun V400 possui uma tela de toque colorida de 7 polegadas que fornece uma interface amigável para controlar a impressora. A tela de toque permite fácil navegação pelos menus da impressora, ajuste de configurações e monitoramento do processo de impressão. A interface é intuitiva e responsiva, tornando mais fácil para os usuários interagir com a impressora e gerenciar seus trabalhos de impressão. Alguns modelos também podem incluir funcionalidade KlipperScreen, fornecendo uma interface gráfica diretamente na tela de toque para o poderoso firmware Klipper.

### **Estrutura Física**

* **Dimensões da Máquina:** 480 x 435 x 940 mm  
* **Peso da Máquina:** 16kg  
* **Diâmetro do Filamento:** 1.75 mm

### **Sistema de Movimento**

* **Sistema de Movimento:** Delta  
* **Guias Lineares:** Guias lineares duplas  
* **Extrusora:** Extrusora direct drive de dupla engrenagem  
* **Hotend:** Bico Volcano  
* **Temperatura Máxima do Bico:** 300°C  
* **Cama Aquecida:** Sim  
* **Temperatura Máxima da Cama Aquecida:** 110°C  
* **Material da Cama Aquecida:** Aço de mola PEI

### **Eletrônica**

* **Placa-mãe:** Placa-mãe de 32 bits STM32F\*\*\* MKS Nano 2.1  
* **Drivers de Motor de Passo:** Drivers de motor de passo silenciosos  
* **Nivelamento da Cama:** Nivelamento automático  
* **Conectividade:** Wi-Fi, USB, Ethernet  
  * Drivers de Motor de Passo: TMC 2226  
* **Tela de Toque:** LCD IPS de 7 polegadas  
* **Entrada de energia:** AC 115-230V  
* **Saída de energia:** DC 24V  
* **Consumo de energia:** 450W

### **Software**

* **Firmware:** Klipper  
* **Interface de Controle:** Mainsail/Fluidd  
* **Fatiadores Suportados:** Cura, Simplify3D, PrusaSlicer, Ideamaker  
* **Formatos de Arquivo Suportados:** STL, OBJ, AMF, 3DS, G-Code

### **Recursos Adicionais**

* **Sensor de Fim de Filamento:** Sim  
* **Recuperação de Impressão:** Sim  
* **Ventiladores Silenciosos:** Sim