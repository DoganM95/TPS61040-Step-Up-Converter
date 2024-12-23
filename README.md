# Intro

Eagle designed PCB for the SOT-23 sized step-up converter IC TPS61040.

## Specs of the IC

- 1.8V - 6V input
- 1.8V - 28V adj. output Voltage
- 0.4A output current
- 28uA quiescent current

## Specs of the PCB (measured)

- 2.2V - 6V input
- 2.2V - 28V adj. output
- 0.4A output
- 60 uA quiescent current

## Power Consumption 

Power consumed by the board alone with no load (quiescent current)

- 61 uA @ 6.0V in (6V out)
- 59 uA @ 5.0V in (6V out)
- 60 uA @ 4.2V in (6V out)
- 63 uA @ 3.3V in (6V out)
- 65 uA @ 3.0V in (6V out)
- 73 uA @ 2.2V in (6V out)

## Power Output

output range 2.93V - 13.87V  
output power @ 3.0V in  
V out without load -> V out with load after @  

- 13.87V loadless -> 13.8V @ 100mA  
- 12.00V loadless -> 11.8V @ 100 mA  
- 9.00V loadless -> 8.8V @ 100 mA  
- 6.0V loadless -> 5.8V @ 100mA  
- 5.0V loadless -> 4.7V @ 100mA  
- 3.3V loadless -> 3.0V @ 100mA  

## BOM

- VR1: 3x3 trimpot 1MOhm
- R2: 0603 100kOhm
- C_FF: 0603 22pF
- L1: CD43 10uF
- C_O: 0603 1nF
- U1: SOT23-5 TPS61040
- D1: any Schottky between SS14 & SS54
- C_IN: 0603 4.7uF

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

## Schematic

![image](https://github.com/user-attachments/assets/ffd44ff2-4bca-4434-814a-d52b781be895)
