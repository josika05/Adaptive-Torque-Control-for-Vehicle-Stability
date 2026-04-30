 ##Vehicle Torque Control System (Simulink)
This project implements a simple vehicle torque control system using Simulink to improve stability under different driving conditions.

- Uses slip ratio, yaw rate, and friction
- Reduces torque during unsafe conditions
- Maintains torque during stable driving

- High slip → Reduce torque  
- High yaw → Reduce torque  
- Wet road → Reduce torque  
- Else → Maintain torque  

##Scenarios

- Dry Condition (No Yaw)
- Dry + Yaw Condition
- Wet Condition

##Each scenario includes:
- Input values
- Output graph
- Explanation

![Model](images/model.png)

![Output](images/output.png)


- Simulink

