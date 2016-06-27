## Logs

**Note:** the number of bytes received per second in these 
logs are limited by the hardcoded delay in the proccessing 
loop of the Arduino microcontrollers. I set this delay to 
100 milliseconds (0.1 seconds) initially to allow time to properly 
send the CAN messages and flush any ouput streams. Without 
the delay, the Arduinos' buffers can overflow. I might also experiment 
with different delay values to see if they yield different results.  

---

### Control Group

Log |  Average Bytes Received Per Second
-----------------------------------------
01  |  79.8367
02  |  79.8361

**Total Average:** 79.8364

---

### Experimental Group

Log |  Average Bytes Received Per Second
-----------------------------------------
01  |  69.0612
02  |  67.9184

**Total Average:** 68.4898

---

### Percent Decrease in Average Bytes Received Per Second:

Log |  Percent Decrease 
-----------------------------------------
01  |  6.7484 %
02  |  7.4634 %

**Total Average:** 7.1059