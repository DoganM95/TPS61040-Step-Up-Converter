# Intro

Eagle designed PCB for the SOT-23 sized step-up converter IC TPS61040.

## Specs of the IC

- 1.8V - 6V input
- 1.8V - 28V adj. output Voltage
- 0.4A output current
- 28uA quiescent current

## Specs of the PCB (measured)

- 2.2V - 6V input
- 2.2V - 28V adj. output Voltage
- 0.4A output current
- 1.5 - 3.8mA quiescent current

## Power Consumption 

Power consumed by the board alone with no load (idle)

- 1.48mA @ 6.0V in
- 1.68mA @ 5.0V in
- 1.98mA @ 4.2V in
- 2.10mA @ 4.0V in
- 2.55mA @ 3.3V in
- 2.76mA @ 3.0V in
- 3.8mA @ 2.2V in

## PCB

<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/261a03f8-a712-4b88-8605-55cf0568de2d" alt="PCB Top View"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/73cf3478-eedc-4b59-91a0-4b0301820461" alt="PCB Bottom View"/>
    </td>
  </tr>
</table>


out range 2.93V - 13.87V

out power @ 3.0V in
13.87V loadless -> 13.8V (dropeed to) @ 100mA
12.00V loadless -> 11.8V @ 100 mA
9.00V loadless -> 8.8V @ 100 mA
6.0V loadless -> 5.8V @ 100mA
5.0V loadless -> 4.7V @ 100mA
3.3V lodless -> 3.0V @ 100mA


## Schematic

![image](https://github.com/user-attachments/assets/ffd44ff2-4bca-4434-814a-d52b781be895)

