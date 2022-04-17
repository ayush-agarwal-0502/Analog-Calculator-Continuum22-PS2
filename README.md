# Analog-Calculator-Continuum22-PS2
Analog electronic circuit for integrating , differentiating and squaring based on the frequency of the input . Solution to Continuum22 PS2 .

## Introduction 

Team name - Resonant Oscillators 

Our team secured 1st position in "Continuum" held in 2022 , an Analog Electronics competition held under "Udyam" , the electronics department fest of IIT BHU .
This was my winning entry .

![image](https://user-images.githubusercontent.com/86561124/163708056-5bc43afa-dd44-4274-bdef-5a0aa373d5de.png)

(Link to leaderboard : https://www.udyamfest.com/leaderboard (link may not work after 2022) ) 

## The PS :

![image](https://user-images.githubusercontent.com/86561124/163708180-5aa7e538-57bf-4b73-a558-55436b97d8b5.png)
![image](https://user-images.githubusercontent.com/86561124/163708186-6db7396d-d99b-429f-b8ec-152e2435bd65.png)
![image](https://user-images.githubusercontent.com/86561124/163708192-9fb8e814-70ed-4ea8-bd89-fdab87fd80bc.png)
![image](https://user-images.githubusercontent.com/86561124/163708195-b7f0d197-5b8c-4a46-9163-2f4075ca40de.png)
![image](https://user-images.githubusercontent.com/86561124/163708200-502b5463-bab2-41de-b54c-d3dbdb46f389.png)
![image](https://user-images.githubusercontent.com/86561124/163708204-8de88d8b-1543-44cc-b110-80832b44ac7f.png)

## The PS , but in short :

Design an analog electronic circuit which returns the integrated , differentiated or squared value of the signal depending on the frequency of the input signal .

## Solution :

I have designed the circuit in such a way that the circuit :

* Squares the signal : at 100Hz 
* Differentiates the signal : at 90Hz 
* Integrates the signal : at 80Hz 

Since the focus of the PS was more on cost efficiency than on accuracy , I have added the 3 results and connected the result to the output . Also , I have used 2nd order butterworth filters , and parameters have been set in such a way that the filter which has a center at 90Hz will only pass 10% of the signal at 80 and 100Hz respectively , and so on for the other filters as well . 

### Squaring part of the circuit (along with its filter) :

![image](https://user-images.githubusercontent.com/86561124/163708684-06cd5f66-dd72-4960-9eb6-9f3c1445321c.png)

### Differentiating part of the circuit (along with the filter ) :

![image](https://user-images.githubusercontent.com/86561124/163708727-71de1662-5c1a-4ac5-913e-0d16d3cb929d.png)

### Integrating part of the circuit ( along with the filter ) :

![image](https://user-images.githubusercontent.com/86561124/163708865-17df6de1-ff70-4b5d-b090-6d5e60c58e4c.png)

### Adder part of the circuit :

![image](https://user-images.githubusercontent.com/86561124/163708788-4f9c037c-945e-43d3-8650-cfbba30837b1.png)
