Sistema de notificação emergencial

Este projeto consiste em um sistema de notificação de emergência simples usando um Arduino, um botão e uma buzina. Ele foi projetado com a intenção de fornecer uma solução para hospitais, permitindo que funcionários pressionem um botão para sinalizar um atendimento emergencial diretamente ao medico.

Requisitos de Hardware:
Arduino Uno (ou similar)
Botão de pressao
Buzzer ativo
Resistores (se necessário)
Fios de conexão
Configuração do Hardware:
Conecte um pino do botão ao pino digital no Arduino.
Conecte o outro pino do botão ao GND no Arduino.
Conecte um pino do buzzer a um pino digital no Arduino.
Conecte o outro pino do buzzer ao GND no Arduino.
Se estier usando um buzzer passivo, considere adicionar um resistor de pull-up entre o pino do buzzer e o 5V no Arduino.

Como Utilizar:
Carregue o código fornecido no Arduino usando a IDE do Arduino.
Pressione o botão quando for necessário sinalizar um atendimento emergencial.
O Arduino acionará a buzina por um curto período de tempo, alertando os médicos sobre a situação.
Impacto:
Este sistema simples visa melhorar a eficiência no ambiente hospitalar, fornecendo uma maneira rápida e direta de alertar os médicos sobre atendimentos emergenciais. Ao pressionar o botão, os médicos podem ser notificados imediatamente, permitindo uma resposta mais rápida e potencialmente salvando vidas.
