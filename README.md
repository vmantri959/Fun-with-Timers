The aim of this project is to demonstrate how one timer can act as a master and trigger the operation of another timer, in this case via a PWM. 
The user will get asked the desired duty cycle. If the user inputs a duty cycle of 100%, the LED will turn on all the time. If the user inputs 50%, for the first 5 seconds, the LED will be off and then for the next 5, on. 
The master timer is triggered every 10 seconds and the user can input a new duty cycle at any time. On an update event (UEV), the master timer will set the new duty cycle and trigger the PWM operation of the slave timer. 
