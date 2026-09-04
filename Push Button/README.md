# Push Button
Você sabe o que é Push Button?  Vem cá que eu te explico! 

Push button, botão de pressão ou ainda chave táctil, é um interruptor simples, o qual fará ações de permitir ou interromper a passagem de corrente elétrica ao pressionar ou soltar o botão. 
<div align="center">
<h3>Figura 1:Botão e seus terminais </h3> 
<img width="800" height="345" alt="Image" src="https://github.com/user-attachments/assets/3952e89b-443b-4bc9-bd27-22409dea0b7f" />
<h4>Fonte: ROBOCORE (Módulo Relé Serial - Acionamento por Botão) </h4>
</div>

# Como Funciona?
O botão possui 4 terminais divididos em dois pares interligados internamente A-C e B-D, pelos quais a corrente passa continuamente, independente do estado do botão.  Para utilizar o botão como chave, as conexões externas devem ser feitas entre pinos de pares diferentes, podendo operar em duas estruturas:

**Normalmente Fechados (NF):** O push button do tipo NF permite a passagem de corrente em seu estado de repouso (figura 2) até que o botão seja pressionado (figura 3), abrindo assim o circuito e impedindo a passagem de corrente.
<div align="center">
<table border="0">
  <tr>
    <td width="50%" align="center" valign="top">
      <h3>Figura 2 - Circuito NF (repouso)</h3>
    </td>
    <td width="50%" align="center" valign="top">
      <h3>Figura 3 - Circuito NF (pressionado)</h3>
    </td>
  </tr>
  <tr>
      <td align="center" valign="top">
        <img src="https://github.com/user-attachments/assets/647ff680-32a1-4099-b166-f976febe77db" /> 
      </td>
      <td align="center" valign="top">
        <img src="https://github.com/user-attachments/assets/6b938147-984c-48ab-9b74-6b2d72477616" />  
      </td>
    </tr>
</table>
  <h4>Fonte: autoria própria </h4>
</div>

**Normalmente Abertos (NA):** Para NA, o estado de repouso é diferente, pois fica desconectado (figura 4),  pois não há ligações entre os terminais até que o botão seja pressionado e a corrente consiga passar normalmente (figura 5).
<div align="center">
<table border="0">
  <tr>
    <td width="50%" align="center" valign="top">
      <h3>Figura 2 - Circuito NF (repouso)</h3>
    </td>
    <td width="50%" align="center" valign="top">
      <h3>Figura 3 - Circuito NF (pressionado)</h3>
    </td>
  </tr>
  <tr>
      <td align="center" valign="top">
        <img src="https://github.com/user-attachments/assets/5a966289-7985-4821-9eaa-e6568ebfa26e" />
      </td>
      <td align="center" valign="top">
        <img src="https://github.com/user-attachments/assets/5da48156-2e6d-430a-ad04-c1649c703bc7" />
      </td>
    </tr>
</table>
  <h4>Fonte: autoria própria </h4>
</div>

# Materiais Necessários:
- Arduino uno;
- 1 Botão;
- 1 LED;
- 1 Resistor 1 kΩ ;
- Cabo de alimentação do Arduino.

Normalmente, o Arduino utiliza pinos configurados como saída (OUTPUT) como no caso dos leds e entrada (INPUT) como no caso dos push buttons,  para enviar e receber sinais, respectivamente. Há três maneiras de se conectar o botão, sendo eles: 
