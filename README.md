# -SIMULATION-AND-IMPLEMENTATION-OF-VARIOUS-SPWM-TECHNIQUES-OF-MULTILEVEL-INVERTER-

### ABSTRACT

Large electric drives & utility applications necessitates modern power electronics converter like cascaded H-bridge multilevel inverter (CHB) with separated DC source. CHB is most practical for use as a power converter for medium & high power applications. The H-bridge inverter removes large no. of bulky transformers, clamping diodes & flying capacitors. Cascaded multilevel inverter (MLI) aims for medium & high power applications. There are many PWM techniques used for controlling MLI among these, SPWM is well-known for its simplicity in both hardware & software. But SVM becomes complex when level increases. In this project, SPWM  controlled cascaded H-bridge MLI is designed , analyzed & 
compared with conventional inverter by simulating in MATLAB simulink software.

### OBJECTIVE

The objective of this project is to compare the different modulation technique used for controlling the cascaded H-bridge multilevel inverter. These comparison is done with respect to analyse the switching pattern & THD for different modulation techniques. For these comparisons all of the inverters are simulated in MATLAB/SIMULINK. 

### NECESSITY

The elementary concept of a multilevel converter to achieve higher power is to use a series of power semiconductor switches with several lower voltage dc sources to perform the power conversion by synthesizing a staircase voltage waveform. Capacitors, batteries, and renewable energy voltage sources can be used as the multiple dc voltage sources. The commutation of the power switches aggregate these multiple dc sources in order to achieve high voltage at the output; however, the rated voltage of the power semiconductor switches depends only upon the rating of the dc voltage sources to which they are connected. A multilevel converter has several advantages over a conventional two-level converter that uses high switching frequency pulse width modulation (PWM). The attractive features of a multilevel converter can be briefly summarized as follows.            
1. Staircase waveform quality: Multilevel converters not only can generate the output      voltages with very low distortion, but also can reduce the dv/dt stresses; therefore electromagnetic compatibility (EMC) problems can be reduced.  
2. Common-mode (CM) voltage: Multilevel converters produce smaller CM voltage; therefore, the stress in the bearings of a motor connected to a multilevel motor drive can be reduced. Furthermore, CM voltage can be eliminated by using advanced modulation strategies such as that proposed in .  
3. Input current: Multilevel converters can draw input current with low distortion.  
4. Switching frequency: Multilevel converters can operate at both fundamental switching frequency and high switching frequency PWM. It should be noted that lower switching 
frequency usually means lower switching loss and higher efficiency. 
Multilevel converters do have some disadvantages. One particular disadvantage is the greater number of power semiconductor switches needed. Although lower voltage rated switches can be utilized in a multilevel converter, each switch requires a related gate drive circuit. This may cause the overall system to be more expensive and complex.

### OUTCOME

The outcome of this project is to compare the SPWM’s two technique & to analyse the output voltage waveforms & THD. Also to find the best modulation technique among these two main PWM techniques.

 ### INTRODUCTION :Cascaded Multilevel Inverter

![image](https://user-images.githubusercontent.com/85278130/121054836-5ce15000-c7da-11eb-958a-719d99774c1c.png)

         FIG1 :- Three phase five level CHB MLI

### CONTROL TECHNIQUES OF MULTILEVEL INVERTER(MLI)

![image](https://user-images.githubusercontent.com/85278130/121055244-b8abd900-c7da-11eb-8304-6c2aff18570c.png)
             
             FIG2 :- Classification of various control techniques of H-bridge MLI

### MATLAB SIMULATION & RESULT

#### 1. CIRCUIT DIAGRAM OF 1-PHASE 5-LEVEL INVERTER 


 ![image](https://user-images.githubusercontent.com/85278130/121055531-f6106680-c7da-11eb-9f00-e1b060988086.png)
             
             FIG3 :- Circuit Diagram Of 5-Level Inverter Controlled By Phase Shifted SPWM Technique


#### RESULTS


##### GATE PULSES


![image](https://user-images.githubusercontent.com/85278130/121055935-556e7680-c7db-11eb-9115-6597f630ba4c.png)

    FIG4 :- Waveform of Gating Signal To Various Switches Of 5-Level Inverter Controlled By Phase Shift Technique


#### OUTPUT VOLTAGE


![image](https://user-images.githubusercontent.com/85278130/121056264-a67e6a80-c7db-11eb-8c1e-d9710cc1141e.png)

     FIG5:-Output waveform of 1-Phase 5-Level Inverter Controlled By SPWM Phase shifted technique, Mf=20,Ma=0.8
  
#### FFT ANALYSIS

![image](https://user-images.githubusercontent.com/85278130/121056436-d299eb80-c7db-11eb-93a3-0fb4441a2d6d.png)

     FIG6 :-FFT analysis  Of 5-Level Inverter Controlled By SPWM Phase shift technique**THD=38.34%

 ### 2. 3-PHASE 5-LEVEL INVERTER  CONTROLLED BY SPWM PHASE SHIFTED TECHNIQUE

![image](https://user-images.githubusercontent.com/85278130/121056599-fbba7c00-c7db-11eb-9cba-501064287fb5.png)

     FIG7:- Circuit Diagram Of 3-Phase 5-Level Inverter  Controlled By SPWM Phase Shifted Technique

 ### RESULTS
   #### VOLTAGE WAVEFORMS 
   ##### PHASE VOLTAGES
 
 ![image](https://user-images.githubusercontent.com/85278130/121056748-27d5fd00-c7dc-11eb-8942-873d441894db.png)
 
    FIG8 :- Line To Ground Voltage

  ##### LINE VOLTAGE VOLTAGES

![image](https://user-images.githubusercontent.com/85278130/121056897-50f68d80-c7dc-11eb-84f5-cd8c09b2eeab.png)

    FIG9 :- Line To Line Voltage

 ### FFT ANALYSIS
 #### FFT ANALYSIS OF PHASE VOLTAGE
 
  ![image](https://user-images.githubusercontent.com/85278130/121057016-75eb0080-c7dc-11eb-885f-6826a9eb0dfd.png)
  
  
        FIG10:- FFT analysis of 3-Phase Phase voltage**THD=40.83
  
  
  #### FFT ANALYSIS OF LINE VOLTAGE
  
  ![image](https://user-images.githubusercontent.com/85278130/121057107-8e5b1b00-c7dc-11eb-8875-b55eb75cf9fd.png)
  
      FIG11:- FFT analysis of 3-Phase Line voltage **THD=31.75%**
  
 ### LEVEL SHIFTED SPWM TECHNIQUE
  
  #### IN PHASE DISPOSITION  TECHNIQUE(IPD)
  
  ##### CIRCUIT DIAGRAM OF 1-PHASE 5-LEVEL INVETER CONTROLLED BY IPD
  
  ![image](https://user-images.githubusercontent.com/85278130/121059644-543f4880-c7df-11eb-8a80-bcff26fabadc.png)

     FIG12:- Circuit Diagram Of 1-Phase  5-Level Inverter Controlled By IPD

#### RESULTS

##### GATING SIGNALS

![image](https://user-images.githubusercontent.com/85278130/121059783-7f299c80-c7df-11eb-95fb-b10615bd46d0.png)

    FIG13:-Waveform of Gating Signal To Various Switches Of 5-Level Inverter Controlled By IPD Level Shift Technique

##### OUTPUT VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121059910-9e282e80-c7df-11eb-974d-332cb991c335.png)

    FIG14:- Output waveform of 1-Phase 5-Level Inverter Controlled By IPD Level shifted technique ,Mf =20, Ma =0.8

##### FFT ANALYSIS

![image](https://user-images.githubusercontent.com/85278130/121060016-b9933980-c7df-11eb-801a-e13a7de62b8b.png)

     FIG15:-FFT analysis of Output Voltage of 1-Phase MLI using IPD**THD=38.88%**

### 3-PHASE 5-LEVEL INVETER CONTROLLED  BY IPD

![image](https://user-images.githubusercontent.com/85278130/121060139-dfb8d980-c7df-11eb-81b2-a1e8efb1c6c4.png)

      FIG16 :- Circuit Diagram Of 3-Phase 5-Level Inverter Controlled  BY IPD

### RESULTS

 #### OUTPUT VOLTAGE

 ##### PHASE VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121060249-05de7980-c7e0-11eb-97cc-3a3984295f9b.png)
 
      FIG17:- Waveform of Phase Voltage of 3-Phase MLI using IPD

##### LINE  VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121060372-2c041980-c7e0-11eb-832c-779ee81d592f.png)

    FIG18:- Waveform of Line Voltage of 3-Phase MLI using IPD

#### FFT ANALYSIS

##### FFT ANALYSIS OF PHASE VOLTAGE 

![image](https://user-images.githubusercontent.com/85278130/121060454-4807bb00-c7e0-11eb-9327-60e7b3a2bf21.png)

    FIG19:- FFT analysis of 3-Phase Line to Ground voltage **THD=38.88%**

##### FFT ANALYSIS OF LINE VOLTAGE 

![image](https://user-images.githubusercontent.com/85278130/121060531-68377a00-c7e0-11eb-9f62-51be4e4bcb6d.png)
 
     FIG20:- FFT analysis of 3-Phase Line voltage **THD=21.34%**
    
### PHASE OPPOSITE DISPOSITION TECHNIQUE(POD)

#### CIRCUIT DIAGRAM OF 1-PHASE 5-LEVEL INVETER CONTROLLED BY POD TECHNIQUE

![image](https://user-images.githubusercontent.com/85278130/121060705-a03ebd00-c7e0-11eb-8f57-17392d49d570.png)

     FIG21 :-Circuit Diagram Of 3-Phase 5-Level Inverter  Controlled By SPWM POD Level Shifted Technique

#### RESULTS

##### GATING SIGNALS

![image](https://user-images.githubusercontent.com/85278130/121060880-d1b78880-c7e0-11eb-9407-f3b39769c80d.png)

      FIG22:- Waveform of Gating Signal To Various Switches Of 5-Level Inverter Controlled By POD Level Shift Technique

##### OUTPUT VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121060981-e98f0c80-c7e0-11eb-9c5b-840b196cb0d5.png)

        FIG23:- Output waveform of 1-Phase 5-Level Inverter Controlled By POD Level shifted technique ,Mf=20,Ma=0.8

##### FFT ANALYSIS

![image](https://user-images.githubusercontent.com/85278130/121061049-03305400-c7e1-11eb-861f-706d56d08780.png)

       FIG24:- FFT analysis of Output Voltage of 1-Phase MLI using POD**THD=38.57%*

### CIRCUIT DIAGRAM OF 3-PHASE 5-LEVEL INVETER CONTROLLED BY POD TECHNIQUE

![image](https://user-images.githubusercontent.com/85278130/121061128-19d6ab00-c7e1-11eb-94f0-09b1c320948d.png)

      FIG25:- CIRCUIT DIAGRAM OF 3-PHASE 5-LEVEL INVETER CONTROLLED  BY POD

#### RESULTS

#### OUTPUT VOLTAGE

##### PHASE VOLTAGE      

![image](https://user-images.githubusercontent.com/85278130/121061382-67ebae80-c7e1-11eb-8844-1a0a8ae80d6c.png)

      FIG26:-Waveform of Line Voltage of 3-Phase Line To Ground Voltage MLI using POD

##### LINE  VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121061461-7df96f00-c7e1-11eb-9d9f-eb6b6cb19bce.png)


         FIG27- Waveform of Line Voltage of 3-Phase MLI using POD

#### FFT ANALYSIS

##### FFT ANALYSIS OF PHASE VOLTAGE 

![image](https://user-images.githubusercontent.com/85278130/121061557-9d909780-c7e1-11eb-83b5-8aed2fccf778.png)

             FIG28:- FFT analysis of 3-Phase Line To Ground voltage using POD **THD=38.57%**

##### FFT ANALYSIS OF LINE VOLTAGE 


![image](https://user-images.githubusercontent.com/85278130/121062058-40e1ac80-c7e2-11eb-8b7c-a5b74144a36a.png)


           FIG29:- FFT analysis of 3-Phase Line voltage using POD **THD=35.37%**

### ALTERNATE PHASE OPPOSITE DISPOSITION TECHNIQUE(APOD):-


#### CIRCUIT DIAGRAM OF 1-PHASE 5-LEVEL INVETER CONTROLLED BY APOD

![image](https://user-images.githubusercontent.com/85278130/121062203-6d95c400-c7e2-11eb-9571-3d64dd3203c8.png)

 
         FIG30:- Circuit Diagram Of 1-Phase 5-Level Inverter  Controlled By SPWM APOD Level Shifted Technique


#### RESULTS 

##### GATING SIGNALS

 ![image](https://user-images.githubusercontent.com/85278130/121062328-8f8f4680-c7e2-11eb-967d-6ca8d201474a.png)

         FIG31:-Waveform of Gating Signal To Various Switches Of 5-Level Inverter Controlled By APOD Level Shift Technique

##### OUTPUT VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121062391-a3d34380-c7e2-11eb-8f92-46de7aef8898.png)

        
       FIG32:- Output waveform of 1-Phase 5-Level Inverter Controlled By SPWM APOD Level Shifted  Technique ,Mf =20, Ma =0.8


##### FFT ANALYSIS

![image](https://user-images.githubusercontent.com/85278130/121062425-b0f03280-c7e2-11eb-9e96-7c3887bc29b1.png)

       FIG33:- FFT analysis of Output Voltage of 1-Phase MLI using APOD**THD=39.10%**

### 3-PHASE 5-LEVEL INVETER CONTROLLED  BY APOD

![image](https://user-images.githubusercontent.com/85278130/121062545-d3824b80-c7e2-11eb-8411-0a89e3efa3f2.png)


FIG34:- CIRCUIT DIAGRAM OF 3-PHASE 5-LEVEL INVETER CONTROLLED  BY APOD
         

 #### RESULTS

#### OUTPUT VOLTAGE

##### PHASE VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121062713-12b09c80-c7e3-11eb-8289-e9e09fa33766.png)

            FIG35:- Waveform of Voltage of 3-Phase Line To Ground Voltage MLI using APOD

##### LINE  VOLTAGE

![image](https://user-images.githubusercontent.com/85278130/121062830-307e0180-c7e3-11eb-9a40-7888e8132c39.png)

         FIG36:-Waveform of Line Voltage of 3-Phase MLI using APOD

#### FFT ANALYSIS

##### FFT ANALYSIS OF PHASE VOLTAGE 

![image](https://user-images.githubusercontent.com/85278130/121063001-67541780-c7e3-11eb-98dc-38b05f14b6de.png)

      FIG37:-FFT analysis of 3-Phase Line To Ground voltage using APOD **THD=39.10%**

##### FFT ANALYSIS OF LINE VOLTAGE 

![image](https://user-images.githubusercontent.com/85278130/121063084-82bf2280-c7e3-11eb-8b4c-b3254589f239.png)

 
       FIG38:- FFT analysis of 3-Phase Line voltage using APOD **THD=29.79%**


### SIMULATION RESULTS AT GLANCE:-
 
 ![image](https://user-images.githubusercontent.com/85278130/121066020-11816e80-c7e7-11eb-9a62-ed819d78d0d7.png)


### HARDWARE

![image](https://user-images.githubusercontent.com/85278130/121063468-f6612f80-c7e3-11eb-85fd-1af9a6d7c5fb.png)

          FIG39:-CIRCUIT DIAGRAM
          

### Hardware implementation

![image](https://user-images.githubusercontent.com/85278130/121063582-214b8380-c7e4-11eb-9c03-99384c3f3127.png)


### CONCLUSION

The cascaded multilevel inverters have evolved from a theoretical concept to real applications due to several remarkable features like a high degree of modularity, the possibility of connecting directly to medium voltage, low harmonic distortion, and the control of power flow in the regenerative version. The focus of this project is limited to basic concept of different MLI and comparative study of different PWM generation methods and its impact on inverter output.

### REFERENCE


[1]A. Kale, A. Tamhane and A. Kalage, "Comparative study of SPWM And SVPWM cascaded h-bridge multilevel inverter", 2017 International Conference on Intelligent Computing and Control (I2C2), 2017
 
 [2]N. Salgado-Herrera, A. Medina-Rios, A. Ramos-Paz and J. Rodriguez-Rodriguez, "Generation of a multilevel SPWM technique of 3, 9 and 21 levels with FPGAs", 2013 North American Power Symposium (NAPS), 2013.

[3] Mustafa S. Alkhazragi, Nabil K.AL-Shamaa “Cascaded H-Bridge Multilevel Inverter Using SPWM and MSPWM Strategies”, Int. Journal of Engineering Research and Application ISSN : 2248-9622, Vol. 7, Issue 6, (Part -2) June 2017, pp.14-20

[4] Vinayaka B.C, S. Nagendra Prasad, “Modeling and Design of Five Level Cascaded H-Bridge Multilevel Inverter with DC/DC Boost Converter”,Int. Journal of Engineering Research and Applications ISSN : 2248-9622, Vol. 4, Issue 6( Version 5), June 2014, pp.50-55

[5]B. Kumar and M. Lokhande, "An enhanced space vector PWM for nine-level inverter employing single voltage source", 2017 IEEE Transportation Electrification Conference (ITEC-India), 2017.

[6] P. Bhagwat and V. Stefanovic, "Generalized Structure of a Multilevel PWM Inverter", IEEE Transactions on Industry Applications, vol. -19, no. 6, pp. 1057-1069, 1983.
