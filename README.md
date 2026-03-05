# Linguagem-Descritiva-Exemplos
Exemplos de programas de automação usando o padrão LDA19 da Linguagem Descritiva no Solver.

## Linguagem Descritiva
Criada em 1982 pela BCM Automação, a linguagem descritiva foi projeta para ser a mais próxima possível da descrição de processos.
A linguagem é orientada à maquinas de estados. Uma rotina pode ter diversas máquinas operando simultaneamente, cada uma formada por diversos estados. Em cada estado, o CLP irá executas as intruções elencadas e testar as condições de transição até uma ser comprida.

### Instruções
 - FACA: Atribuição simples. Executada uma vez ao entrar no estado;
        FACA <VARIAVEL> := <EXPRESSÃO>;
 - FACA*: Atribuição simples. Executada continuamente enquanto dentro do estado;
          - FACA* <VARIAVEL> := <EXPRESSÃO>;
 - VA PARA: Transição para outro estado; VA PARA <ESTADO_DE_DESTINO>, onde ESTADO_DE_DESTINO pode ser uma constante ou variável
 - SE ENTAO: Transição condicional de estado; SE <EXPRESSAO> ENTAO <ESTADO_DE_DESTINO>; expressao pode ser de tempo: SE ATRASO=\<TEMPO\> ENTAO <ESTADO_DE_DESTINO>
 - LIGA/DESL: Alias para FACA var := 1 e FACA var := 0, usada para clareza em entradas e saídas digitais;
 - SET/RESET: Alias para FACA var := 1 e FACA var := 0, usada para clareza em flags;
 - INCREMENTA/DECREMENTA: Alias para FACA var := var+1 e FACA var := var-1, usada para clareza;
### Tipos de Dados:
São suportados todos tipos de dados da IEC61131-3
### Estrutura Geral:

<img width="1311" height="496" alt="image" src="https://github.com/user-attachments/assets/4ea6477a-5dbf-40e3-b1bd-8dd0cd406a3b" />

### Exemplos

<img width="1301" height="687" alt="image" src="https://github.com/user-attachments/assets/7dfab9b8-0c4c-4fdb-9b9d-69a7c006d116" />

<img width="1273" height="725" alt="image" src="https://github.com/user-attachments/assets/65a2a8b2-54a4-42ad-8556-24a1d7f6051e" />
