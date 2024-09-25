# Analog-Electronics

**What is a TRANSISTOR**

  * Transistor is a semiconductor device which is used in electronic circuits to amplify or switch signals.
  * It is mainly used to CONTROL THE CUREENT FLOW.

  App: 
  * Amplification: Increasing the strength of an electrical signal.
  * Switching: Controlling the flow of current on and off.

Vdo transistor working: https://youtu.be/7ukDKVHnac4?si=0AgJhrte8LMvCEun

* Diode: A diode is formed when a silicon is doped with N type (Phosphrous) and P type (Boron)
* Phosphorous has 5 valence electron **(N)** and boron has 3 valence electron **(P)**, electrons from N travel to P forming depletion region.
* In FORWARD BIAS more electrons get diffused in N type, and as there are holes in p type... electrons are drifted towards P type, casuing current to flow.

## __BJT Transistor__(Both e and p contribue in flow of current):


![BJT AMP](https://github.com/user-attachments/assets/ceced6d5-81e8-41b2-a028-314053d96828)

![image](https://github.com/user-attachments/assets/bf5373d0-7706-4d3c-87b2-0af3c74df29c)

* Emitter (heavily doped), base, Collector.
*  one side is forward biased, another is reverse biased.
*  small amount of base current is amplified at collector current.
*  To make transistor work as **amplifier** CONTROL THE CURRENT IN TRANSISTOR
*  To make transistor work as **switch** CONTROL THE THRESHOLD VOLATGE 


__Modes of Operation__

* Active region: Current flows from E to C - Vc>Vb>Ve
   * emitter-base is FB
   * collector base is RB
     
* Cutoff region: No current flows - Ve>Vb
  * emitter-base is RB
  * collector base is RB
    
* saturation region: Vb>Ve & Vb>Vc
  * emitter-base is FB
  * collector base is FB
 
### __FET Transistor:__

semiconductor devices that control the flow of current between a source and a drain terminal using an Voltage.
 
*Junction Field-Effect Transistors (JFETs):*

* The gate terminal is a PN junction.
* The gate voltage controls the width of the channel between the source and drain.

*Metal-Oxide-Semiconductor Field-Effect Transistors (MOSFETs):*

* The gate terminal is insulated from the channel by a layer of oxide.
* The gate voltage controls the formation of a channel between the source and drain.

__MOSFET__

Vdo:https://youtu.be/stM8dgcY1CA?si=d5HHqySzxiSV1mjt

![image](https://github.com/user-attachments/assets/39f80ed4-5639-4d80-a7f9-ddf7a5272e73)

Capacitor: It consists of an insulator sandwiched between two metal plates.
* Electric field is induced between two metal plates.
* one metal plate is removed and another metal plate with insulator is placed on MOSFET as GATE terminal.

Working;
* when voltage is applied between GATE and SUBSTRATE, electrons from CAPACITOR are fed into P type substrate
* Number of electrons increases in p-type substrate
* Electric field from CAP is induced in substrate causing large number of electrons attract to the GATE terminal
* Electrons combine with the holes and break the deplition region
* This introduces channel between two N-wells
* On providing voltage between drain and source, current flows from Source to drain (MOSFET TURNS ON)
            
__Depletion Type of MOSFET__

![image](https://github.com/user-attachments/assets/88edf537-6e9f-40be-8361-e14b4f1f759a)

* Channel is already present
* MOSFET IS works even at Vgs=0 
* At Vgs>0, Drain current (Id) increases
* At Vgs<0, Drain current (Id) decreases
* On applying Vds (drain to source), current starts to flow from source to drain.
* After pinch off voltage (Too much of Vds) the current gets saturated.

*Drain and transfer Characteristics*

Transfer characteristics are Input vs Output

![image](https://github.com/user-attachments/assets/080bdfed-dd1b-48a6-ab11-195707ea715a)

* Depletion mode is device OFF
* Enhancement mode is device ON


__Enhancement Type of MOSFET__


![image](https://github.com/user-attachments/assets/8533641b-2b08-46fb-b7c4-b27483060b5f)

* Channel is formed
* When Vgs>0, minority carriers (electrons) from p substrate are attracted towards gate.
* As Vgs increases, drain current also increases.
* INVERSION: the p-type near gate is inverted to n-type, forming a channel
* When Vds is applied the current starts to flow from source to drain
   * Vgd (voltage between gate and drain ) = Vgs - Vds
   * IF Vds = 0V : Vgd=Vgs (Uniform depletion width)
   * If Vds > 0v : Vgd decreases (More e- are pulled by drain, hence channel width decreases) Non-Uniform
   * If Vds = Vgs - Vt : Vgd = Vt ( Channel will become very narrow near DRAIN, making the MOSFET OFF) : Pinch OFF voltage occurs
 
![image](https://github.com/user-attachments/assets/cedb1450-cf4c-404a-a1e7-af54201b20e7)


__OP AMP__

App : ADC, DAC, Oscillators,
* Slewrate: how fast the Op-Amp reaches its final value
* Common mode rejection ratio : The ability of Op-Amp to reject the input when same voltage is applied at both the terminals.(For better accuracy)
* Open Loop gain is generally between 10^5 - 10^6

![image](https://github.com/user-attachments/assets/eff14565-83c1-458f-a25c-df4bbad16d56)

* A differential op-amp is a type of operational amplifier (op-amp) that amplifies the difference between two input signals.
* The amplified signal is always in between V+ and V-











