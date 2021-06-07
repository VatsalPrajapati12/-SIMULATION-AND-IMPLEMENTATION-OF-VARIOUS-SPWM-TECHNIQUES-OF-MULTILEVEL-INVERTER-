ABSTRACT

Large electric drives & utility applications necessitates modern power electronics converter like cascaded H-bridge multilevel inverter (CHB) with separated DC source. CHB is most practical for use as a power converter for medium & high power applications. The H-bridge inverter removes large no. of bulky transformers, clamping diodes & flying capacitors. Cascaded multilevel inverter (MLI) aims for medium & high power applications. There are many PWM techniques used for controlling MLI among these, SPWM is well-known for its simplicity in both hardware & software. But SVM becomes complex when level increases. In this project, SPWM  controlled cascaded H-bridge MLI is designed , analyzed & 
compared with conventional inverter by simulating in MATLAB simulink software.

OBJECTIVE

The objective of this project is to compare the different modulation technique used for controlling the cascaded H-bridge multilevel inverter. These comparison is done with respect to analyse the switching pattern & THD for different modulation techniques. For these comparisons all of the inverters are simulated in MATLAB/SIMULINK. 

NECESSITY

The elementary concept of a multilevel converter to achieve higher power is to use a series of power semiconductor switches with several lower voltage dc sources to perform the power conversion by synthesizing a staircase voltage waveform. Capacitors, batteries, and renewable energy voltage sources can be used as the multiple dc voltage sources. The commutation of the power switches aggregate these multiple dc sources in order to achieve high voltage at the output; however, the rated voltage of the power semiconductor switches depends only upon the rating of the dc voltage sources to which they are connected. A multilevel converter has several advantages over a conventional two-level converter that uses high switching frequency pulse width modulation (PWM). The attractive features of a multilevel converter can be briefly summarized as follows.            
1. Staircase waveform quality: Multilevel converters not only can generate the output      voltages with very low distortion, but also can reduce the dv/dt stresses; therefore electromagnetic compatibility (EMC) problems can be reduced.  
2. Common-mode (CM) voltage: Multilevel converters produce smaller CM voltage; therefore, the stress in the bearings of a motor connected to a multilevel motor drive can be reduced. Furthermore, CM voltage can be eliminated by using advanced modulation strategies such as that proposed in .  
3. Input current: Multilevel converters can draw input current with low distortion.  
4. Switching frequency: Multilevel converters can operate at both fundamental switching frequency and high switching frequency PWM. It should be noted that lower switching 
frequency usually means lower switching loss and higher efficiency. 
Multilevel converters do have some disadvantages. One particular disadvantage is the greater number of power semiconductor switches needed. Although lower voltage rated switches can be utilized in a multilevel converter, each switch requires a related gate drive circuit. This may cause the overall system to be more expensive and complex.

OUTCOME

The outcome of this project is to compare the SPWM’s two technique & to analyse the output voltage waveforms & THD. Also to find the best modulation technique among these two main PWM techniques.

 INTRODUCTION :Cascaded Multilevel Inverter

![image](https://user-images.githubusercontent.com/85278130/121054836-5ce15000-c7da-11eb-958a-719d99774c1c.png)

FIG1 :- Three phase five level CHB MLI

CONTROL TECHNIQUES OF MULTILEVEL INVERTER(MLI)

![image](https://user-images.githubusercontent.com/85278130/121055244-b8abd900-c7da-11eb-8304-6c2aff18570c.png)
             
             FIG2 :- Classification of various control techniques of H-bridge MLI

MATLAB SIMULATION & RESULT

1. CIRCUIT DIAGRAM OF 1-PHASE 5-LEVEL INVERTER 


 ![image](https://user-images.githubusercontent.com/85278130/121055531-f6106680-c7da-11eb-9f00-e1b060988086.png)
             
             FIG3 :- Circuit Diagram Of 5-Level Inverter Controlled By Phase Shifted SPWM Technique


RESULTS


GATE PULSES


![image](https://user-images.githubusercontent.com/85278130/121055935-556e7680-c7db-11eb-9115-6597f630ba4c.png)

    FIG4 :- Waveform of Gating Signal To Various Switches Of 5-Level Inverter Controlled By Phase Shift Technique


OUTPUT VOLTAGE


![image](https://user-images.githubusercontent.com/85278130/121056264-a67e6a80-c7db-11eb-8c1e-d9710cc1141e.png)

     FIG5:-Output waveform of 1-Phase 5-Level Inverter Controlled By SPWM Phase shifted technique, Mf=20,Ma=0.8
  
FFT ANALYSIS

![image](https://user-images.githubusercontent.com/85278130/121056436-d299eb80-c7db-11eb-93a3-0fb4441a2d6d.png)

     FIG6 :-FFT analysis  Of 5-Level Inverter Controlled By SPWM Phase shift technique**THD=38.34%

 2. 3-PHASE 5-LEVEL INVERTER  CONTROLLED BY SPWM PHASE SHIFTED TECHNIQUE

![image](https://user-images.githubusercontent.com/85278130/121056599-fbba7c00-c7db-11eb-9cba-501064287fb5.png)

     FIG7:- Circuit Diagram Of 3-Phase 5-Level Inverter  Controlled By SPWM Phase Shifted Technique

 RESULTS
    VOLTAGE WAVEFORMS 
           PHASE VOLTAGES
 
 ![image](https://user-images.githubusercontent.com/85278130/121056748-27d5fd00-c7dc-11eb-8942-873d441894db.png)
 
    FIG8 :- Line To Ground Voltage

  LINE VOLTAGE VOLTAGES

![image](https://user-images.githubusercontent.com/85278130/121056897-50f68d80-c7dc-11eb-84f5-cd8c09b2eeab.png)

    FIG9 :- Line To Line Voltage

 FFT ANALYSIS
 FFT ANALYSIS OF PHASE VOLTAGE
  ![image](https://user-images.githubusercontent.com/85278130/121057016-75eb0080-c7dc-11eb-885f-6826a9eb0dfd.png)
  
      FIG10:- FFT analysis of 3-Phase Phase voltage**THD=40.83
  
  
  FFT ANALYSIS OF LINE VOLTAGE
  
  ![image](https://user-images.githubusercontent.com/85278130/121057107-8e5b1b00-c7dc-11eb-8875-b55eb75cf9fd.png)
  
      FIG11:- FFT analysis of 3-Phase Line voltage **THD=31.75%**
  
  


