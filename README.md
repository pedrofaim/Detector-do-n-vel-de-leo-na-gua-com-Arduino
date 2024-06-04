Descrição

Este projeto visa simular a detecção de níveis de óleo na água utilizando um potenciômetro, uma placa Arduino Uno e o Tinkercad. A simulação demonstra como um sensor pode variar a resistência em função da presença de óleo e água, fornecendo diferentes leituras que são interpretadas pelo Arduino.

Materiais Necessários
Placa Arduino Uno
Potenciômetro
Protoboard
Fios de conexão
Computador com acesso ao Tinkercad

Requisitos
Conta no Tinkercad
Conhecimentos básicos em eletrônica e programação Arduino

Dependências
Software Arduino IDE (se estiver testando localmente)
Navegador da Web compatível para acessar o Tinkercad
Configuração do Circuito no Tinkercad

Adicionar Componentes:
Arraste e solte uma placa Arduino Uno para a área de trabalho do Tinkercad.
Adicione um potenciômetro e uma protoboard.

Conectar o Potenciômetro:
Conecte o pino central do potenciômetro ao pino A0 do Arduino.
Conecte um dos pinos laterais do potenciômetro ao VCC (5V) do Arduino.
Conecte o outro pino lateral do potenciômetro ao GND do Arduino.

Montar na Protoboard:
Coloque o potenciômetro na protoboard de forma que os três pinos fiquem em colunas diferentes.
Use fios para conectar um dos pinos laterais do potenciômetro ao pino 5V do Arduino.
Conecte o outro pino lateral do potenciômetro ao GND do Arduino.
Conecte o pino central do potenciômetro ao pino A0 do Arduino.

Simulação
Iniciar Simulação:
No Tinkercad, clique em "Iniciar Simulação".

Observar Valores:
Abra o monitor serial para visualizar os valores lidos pelo Arduino.
Ajuste o potenciômetro para simular a variação de níveis de óleo e água.
As mensagens "Presença de Água", "Mistura de Água e Óleo" e "Presença de Óleo" aparecerão conforme os valores lidos.
Explicação dos Intervalos
0 a 340: Representa a presença de água.
341 a 681: Representa uma mistura de água e óleo.
682 a 1023: Representa a presença de óleo.

Ajustes Futuros
Dependendo da precisão necessária e do comportamento real do sensor, você pode ajustar esses intervalos para representar melhor as condições reais de detecção de óleo e água. Para uma simulação mais detalhada, seria interessante testar com diferentes líquidos e ajustar os intervalos conforme necessário.

Conclusão
Este projeto básico demonstra como usar um potenciômetro para simular a detecção de diferentes níveis de líquido. É um ponto de partida para projetos mais complexos envolvendo sensores de nível de líquidos reais.

Equipe responsável
Gabriel Guerreiro Escobosa Vallejo e Pedro Henrique Faim dos Santos.
