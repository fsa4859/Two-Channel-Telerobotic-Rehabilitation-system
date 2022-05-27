# Two-Channel-Telerobotic-Rehabilitation-System
Simulation of two channel telerobotic rehabilitation system in the presence of constant and variable communication delay. Smith Predictor and Wava Variables were designed and implemented to ensure the stability of the system in the presence of constant time delay. Passivation by scaling was used to ensure the system stability in the presence of variable time delay.

# Tracking in the absence of wave variable and the presence of constant delay

## Force Tracking

![image](https://user-images.githubusercontent.com/69100847/170683608-4f394287-3a8d-4273-855b-01b160bc46af.png)

## Velocity Tracking

![image](https://user-images.githubusercontent.com/69100847/170683650-f2db170c-1af6-4849-bc8b-498e0ce61b0c.png)


it can be seen that based on Nyquist stability criteria, the system is not stable in the presence of the given time delay.


# Wava Varaible Simulink Model

![image](https://user-images.githubusercontent.com/69100847/170680700-ae72c764-e27e-4974-a4a4-094474144fe8.png)


## Force and velocity Tracking at b=0.1 (wave variable)

### Force Tracking

![image](https://user-images.githubusercontent.com/69100847/170680857-a74f78ae-5050-493d-ac4e-aae0338d1e5a.png)


### Velocity Tracking

![image](https://user-images.githubusercontent.com/69100847/170680908-9546e91e-305a-4b58-b545-b11b603d2008.png)


# Passivation by Scaling

## 
To ensure the passivity of the telerobotic system in the presence of the variable time delay, we utilize the approach of passivation by scaling which adds an extra layer of dampening to ensure the system passivity however the transparency of the system is affected. 

## Force Tracking

![image](https://user-images.githubusercontent.com/69100847/170684658-2e8500d1-8c1a-495a-9441-efb51ea13b23.png)


## Velocity Tracking

![image](https://user-images.githubusercontent.com/69100847/170684690-f5855683-29af-457b-ac51-96f880dd6282.png)





