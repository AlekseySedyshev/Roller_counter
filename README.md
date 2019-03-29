# Roller_counter
Roller counter with stm8l101, cheap 24 steps per rotation encoder and i2c LCD (motorola T191 LCD)

This schematic has not power off switch because current in sleep mode below than 1uA, sleep mode activated utomaticaly when you not move wheel more than 30 sekonds.

You can adjust modes if press and hold first button or encoder "OK" middle button.
Hold on 1 sek: Reset counter
Hold on 2 sek: Count clockwise
Hold on 3 sek: Count conter-clockwise
Hold on 4 sec: Reset all parameters and put 1 rotation = 24 sM (1 step = 1sm)
Second button for set up quantity of impulses per 1 metr.
