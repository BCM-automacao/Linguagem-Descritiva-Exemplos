# EXEMPLO3: FURADEIRA AUTOMÁTICA
## Introdução
Exemplo simples didático de uma automação implementada na linguagem descritiva

## Descrição do Processo

Ao ser pressionada a partida, o cabeçote deve avançar na velocidade rápida até acionar o sensor
VLT;

Após acionar o sensor VLT, o cabeçote deve avançar na velocidade lenta até acionar o sensor CAV;

Após acionar o sensor CAV, o cabeçote deve permanecer na posição por um tempo configurável
TEMPO_FURO;

Passado o TEMPO_FURO, o cabeçote deve recuar até atingir o sensor CAR e esperar por um novo
comando;

## Pontos de E/S

 - SD1: Bobina de acionamento da velocidade rápida
 - SD2: Bobina de acionamento da velocidade lenta
 - SD3: Bobina de acionamento de recuo

 - ED1: Botão de início
 - ED2: Sensor de posição de repouso
 - ED3: Sensor de posição de troca de velocidade
 - ED4: Sensor de posição de furação


## Diagrama de Estados
<img width="482" height="383" alt="image" src="https://github.com/user-attachments/assets/0cae2f68-c500-4de1-92ea-a9185527e2ed" />

