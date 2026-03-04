# EXEMPLO1: FORNO DE SECAGEM DIDATICO
## Introdução
Exemplo simples didático de uma automação implementada na linguagem descritiva

## Descrição do Processo


Para um processo de secagem simples, um forno deve ser acionado até a temperatura interna ultrapassar 200 graus. Em sequência, deve ser resfriado naturalmente por 2 horas;
O processo deve ser iniciado quando um botão for pressionado;

## Pontos de E/S
SD1: Aciona o aquecimento do forno;

ED1: Botão de início;

EA1: Sensor de temperatura, onde $T[C] = \frac{EA1}{20000} * 500.0$

## Diagrama de Estados
<img width="218" height="502"
     style="background-color:white; padding:10px;"
     src="https://github.com/user-attachments/assets/467d49ac-032d-4a59-8808-2a9570791ccf" />
    
## Implementação
 <img width="402" height="446" alt="image" src="https://github.com/user-attachments/assets/43a8d323-63b5-4fa0-9010-272c80d67ebe" />
