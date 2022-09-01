# RTOS_UDACITY_ADVANCED_TASKS
My Tasks For RtosFwd

 # The Course Contains of 4 Assignments 
 ------------------------------------------------------------------------------------------------------------------------------
 ## Assignment 1 
  ### Intro To FreeRtos
   ##### TASK 1
     -Write A program with one task to toggle a led every 1000ms
   ##### TASK 2
     -Write A program with That toggles 3 LEDs with 3 different tasks
      at the following rates respectivelty , 100ms , 500ms and 1000ms
   ##### TASK 3
     -Write A program Where is the user shall be able to control LED
      toggling rate by pressing a push button , And the action is taken
      after releasing the button, Press Longer than 2 seconds and less than
      4 seconds will toggle the LED with periodicity 400ms , Press Longer than 
      4 seconds will toggle Led with perdiodicity 100ms , press Shorter than 
      2 Seconds will turn the LED OFF.
 ## Assignment 2 
  ### Interprocess communication 
  ##### TASK 1
     -Use an Existing RTOS project to write Program with two Tasks , A Task to
     read a button State and a Task to Turn an LED ON/OFF , The LED shall toggle
     its state between ON/OFF with every press on the button , The action of toggling
     the LED shall take place after user presses the button once and release it
   ##### TASK 2
     -Use an existing RTOS project to write a program with 2 tasks , both are responsible
     for writting on UART any string 10 times each task cylce , The Task cycles are 
     respectivly , 100ms , and 500ms , the task with cycle 500ms shall have an empty loop
     that loops 100,000 times (to simulate heavy load) after every time a string is written
     on UART , Each Task writing to UART shall not be interrupt by the other Task
   ##### TASK 3
     -Use an Existing RTOS project to write a program with 4 tasks , two tasks will 
     detect rising and falling edge on two buttons , Every edge is an event that will be
     sent to a consumer task to write on UART , A task will sent periodic string every 100ms
     to consumer task to write on UART
 ## Assignment 3 
  ### Design a real time system
   ##### TASK
   ##### -Design a HealthCare System Using RTOS with the following requirements :
   ##### 1 : A touch LCD as input that can control the system and give commands , Every LCD command is represented in 4 bytes 
   ##### , LCD is connected to the micro-controller through UART with speed 9600bps [bit per second] (Reading 4 bytes and takes 2ms)
   ##### 2 : Blood Pressure Sensor with new Data every 25ms ( takes 3ms)
   ##### 3 : Heart Beat detector with new Data every 100ms (takes 1.5ms)
   ##### 4 : Temperature Sensor with new data every 10ms (takes 2.5ms)
   ##### 5 : Alert Siren ( takes 1 ms)
 ## Assignment 4 
  ### Scheduling and Types of schedulers
