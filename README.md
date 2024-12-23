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

- `C_FF`: 0603 22pF
- `C_IN`: 0603 4.7uF
- `C_O`: 0603 1nF
- `D1`: any Schottky between SS14 & SS54
- `EN_J`: join if board should be always on -> EN becomes redundant
- `L1`: CD43 10uF
- `R1`: 0603 up to 1MOhm, use if VR1 is unnecessary and needed resstance is known
- `R2`: 0603 100kOhm
- `U1`: SOT23-5 TPS61040
- `VR1`: 3x3 trimpot 1MOhm, sets output voltage by adjusting its resistance

## PCB

<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/31651223-e9b4-47c7-9ef5-5136ddd4020e" alt="PCB Top View"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/234b297c-94e8-4f43-a435-858336d23dcf" alt="PCB Bottom View"/>
    </td>
  </tr>
</table>

## Schematic

![image](https://github.com/user-attachments/assets/afcf28a0-c3f1-46bf-a150-96de484e08ad)
