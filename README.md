# Digital Clock Design Manual

## Features

### Alarm:
- **(1)** Incrementing hours mark  
- **(2)** Incrementing 10s minute mark  
- **(3)** Incrementing 1s minute mark  
- **(4)** Incrementing 10s second mark  
- **(5)** Incrementing 1s second mark  

### Other:
- **(6)** Slider: Switches between Clock, Stopwatch, Timer, and Alarm Set mode  
- **(7)** Reset Button: Resets the time on the display to the default  
- **(8)** 12-hour / 24-hour Switch: Toggles between 12-hour and 24-hour formatting  
- **(9)** On/Off Button  

---

## How to Use

### Clock Mode
1. Toggle the **On** switch on the interface.  
2. Activate the clock using `CTRL + K`.  
3. The clock will increment second by second.  
4. Use the **12/24 hour switch** to change time format.  
5. Press the **Reset** button to reset the time.  
6. To pause the clock, either toggle the **On/Off** switch or press `CTRL + K` again.

---

### Stopwatch Mode
1. Ensure the **On** switch is toggled.  
2. Start the stopwatch using `CTRL + K`.  
3. It will count upward until stopped.  
4. Stop the stopwatch with the **On/Off** switch or `CTRL + K`.  
5. Reset it using the **Reset** button.

---

### Alarm Set Mode
1. Use the **slider** to switch to Alarm Set mode.  
2. Use the **incremental buttons** (1-5) to set your desired alarm time.  
3. Switch between **12-hour** and **24-hour** formats as needed.  
4. Once set, return to Clock mode using the slider.  
5. The buzzer will sound when the set time is reached.  
6. Reset to `00:00:00` with the **Reset** button.

---

### Timer Mode
1. Toggle the **On** switch.  
2. Start the timer using `CTRL + K`.  
3. The timer will count down from **1:59** to **0:00**.  
4. When it reaches zero, the **buzzer** will sound.  
5. Use the **Reset** button to return the timer to **1:59**.

---

## Notes
- `CTRL + K` is used to start/stop the internal clock signal.  
- The **Reset** button clears all current time settings for the selected mode.  
- Modes can be changed using the **slider** at any time.