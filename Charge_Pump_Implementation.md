# Glance at the CHARGE_PUMP_NMOS_Implementation

A charge pump circuit in VLSI (Very Large ScaleIntegration) is a type of DC-DC converter that efficiently generates higher or lower voltage levels from a given input voltage without the need for inductors. It operates by transferring charge between capacitors through switches, allowing for a compact and efficient design. Compared to traditional buck and boost converters, charge pumps offer advantages such as reduced size and cost since they do not require bulky inductors. They also have lower electromagnetic interference (EMI), making them suitable for integrated circuit designs where space and noise are critical considerations. Additionally, charge pumps can achieve high efficiency at low power levels, which is beneficial in battery operated devices.

BLOCK DIAGRAM OF A CHARGE_PUMP File name ---> Charge_pump_NMOS.cir

![Hackathon Circuit__Implementation_IP](https://github.com/user-attachments/assets/94af78ab-df3e-4d38-96d9-e95ac57d7de8)


**NMOS CIRCUIT OF THE CHARGE PUMP**   File Name ------> Hackathon_Charge_Pump.cir

![Hackathon Circuit__Implementation_MOS](https://github.com/user-attachments/assets/17510b1b-4b27-424a-b3ac-792eaed3af5f)

**CHARGE_PUMP_Performance Parameters**

![Parameter](https://github.com/user-attachments/assets/af5814f5-bf1f-4c7b-8617-1c7967e8c28a)



**PRE_LAYOUT_PERFORMANCE_CHARACTERISTICS**

**VC2(output_port) vs Time**

![Hackathon Circuit_Implementation_Result](https://github.com/user-attachments/assets/fecbbc9a-2895-4adf-8458-d309eca38226)


Issues Faced in designing with Sky 130 nm technology.

As we can see from the output waveform the voltage does fall for few ms and again rise up to the steady state . It might because of the 130nm techlogy gate length which is responsible for the slow switching of the NMOS and hence maybe the time of the switching of the NMOS is more that than the charging and discharging of the Caps .

If we design using Si7336ADP from Siliconix a model used in LTSPICE then there are better results or close results to what is desired in a Charge Pump.

For more detailed Waveform refer to # Charge_Pump_NMOS_Research

Design of a Charge pump with NMOS.
A charge pump circuit in VLSI (Very Large ScaleIntegration) is a type of DC-DC converter that efficiently generates higher or lower voltage levels from a given input voltage
without the need for inductors. It operates by transferring charge between capacitors through switches, allowing for a compact and efficient design. Compared to traditional buck and boost
converters, charge pumps offer advantages such as reduced size and cost since they do not require bulky inductors. They also have lower electromagnetic interference (EMI), making them
suitable for integrated circuit designs where space and noise are critical considerations. Additionally, charge pumps can achieve
high efficiency at low power levels, which is beneficial in battery operated devices. 

NMOS

An NMOS (N-type Metal-Oxide-Semiconductor) transistor is a type of field-effect transistor (FET) that uses electrons as the charge carriers. It consists of a source, drain, and gate terminal, with the current flowing between the source and drain when a voltage is applied to the gate

Charge Pump

A charge pump is a circuit that converts a low voltage toa higher voltage by transferring charge through capacitors.It works by alternately charging and discharging capacitors using switches, creating a step-up effect that boosts the output voltage. This technique is commonly used in devices requiring higher voltages than their power supply can provide.

Charge pumps are the best solutions if we want to avoid large inductors and shorten the space though it may have some trade offs.

![Hackathon Circuit](https://github.com/user-attachments/assets/79d7cb6c-635b-4a6a-a54e-08ca756a1835)


![Hackathon Circuit_Result](https://github.com/user-attachments/assets/c81c8b37-3e98-4b8c-882c-d427c2f8aaee)


**Glance at the CHARGE_PUMP_NMOS_Implementation

A charge pump circuit in VLSI (Very Large ScaleIntegration) is a type of DC-DC converter that efficiently generates higher or lower voltage levels from a given input voltage without the need for inductors. It operates by transferring charge between capacitors through switches, allowing for a compact and efficient design. Compared to traditional buck and boost converters, charge pumps offer advantages such as reduced size and cost since they do not require bulky inductors. They also have lower electromagnetic interference (EMI), making them suitable for integrated circuit designs where space and noise are critical considerations. Additionally, charge pumps can achieve high efficiency at low power levels, which is beneficial in battery operated devices.

BLOCK DIAGRAM OF A CHARGE_PUMP File name ---> Charge_pump_NMOS.cir

![Hackathon Circuit__Implementation_IP](https://github.com/user-attachments/assets/94af78ab-df3e-4d38-96d9-e95ac57d7de8)


**NMOS CIRCUIT OF THE CHARGE PUMP**   File Name ------> Hackathon_Charge_Pump.cir

![Hackathon Circuit__Implementation_MOS](https://github.com/user-attachments/assets/17510b1b-4b27-424a-b3ac-792eaed3af5f)

**CHARGE_PUMP_Performance Parameters**

![Parameter](https://github.com/user-attachments/assets/af5814f5-bf1f-4c7b-8617-1c7967e8c28a)



**PRE_LAYOUT_PERFORMANCE_CHARACTERISTICS**

**VC2(output_port) vs Time**

![Hackathon Circuit_Implementation_Result](https://github.com/user-attachments/assets/fecbbc9a-2895-4adf-8458-d309eca38226)


Issues Faced in designing with Sky 130 nm technology.

As we can see from the output waveform the voltage does fall for few ms and again rise up to the steady state . It might because of the 130nm techlogy gate length which is responsible for the slow switching of the NMOS and hence maybe the time of the switching of the NMOS is more that than the charging and discharging of the Caps .

If we design using Si7336ADP from Siliconix a model used in LTSPICE then there are better results or close results to what is desired in a Charge Pump.

Please refer to Charge_pump_Research.md readme file.
