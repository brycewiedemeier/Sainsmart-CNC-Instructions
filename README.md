# sainsmart-CNC-instructions
> This is a walkthrough on how to use the Sainsmart CNC Mill in Mr. Yip's classroom. This will include all of the necessary files and instructions to operate the mill and start generating your own GCode.
*There are two ways of operating the CNC and both are covered below
## Table of Contents
* [Operating with Computer](#operating-with-computer)
* [Offline Controller](#offline-controller)
* [](#)
* [](#)
* [](#)
* [](#)
* [](#)
* [](#)

# Operating with Computer
> This will walk you throught the setup on a computer to start CNC milling!
## Downloads
1. Download the [Sainsmart Original Documentation & Files](https://docs.sainsmart.com/article/7c20d7zaw3-how-to-install-candle-grblcontrol-for-windows)
2. Extract the CD.zip file with an extraction tool such as [WinZip](https://www.winzip.com/win/en/) or [7-Zip](https://www.7-zip.org/)
3. Open the extracted CD folder and navigate to `CD > 3018-PROVer Tutorial_Software_Driver > Driver` and run the *Driver_CH340SER.EXE* to install the drivers:
4. Navigate to `CD > 3018-PROVer Tutorial_Software_Driver > Grblcontrol(Candle_1.1.7)` and run the *Grblcontrol (Candle).exe* file
5. Boom you now have everything you need to start the CNC mill!

## Starting the CNC Mill
1. Plug in the computer that will be running the GCode with the attatched USB cable and power on the CNC
2. On your computer, press the `Windows Key`, search "Computer Management", and select the first option: 
3. Under Device Manager, you will see a `Ports (COM & LPT)` dropdown; here you will see the COM number of the CNC... remember this
4. In the `Candle` program, navigate to `Service > Settings` in the top left
5. Input the COM number that you memorized earlier and press "OK"
6. Your computer is now connected! (in the console, you should see something like [CTRL + X] which indicates a connection)

## Milling
1. To import GCode, press `File > Open` in the top left and select the GCode that you want to run
*There is some test GCode in `CD > 3018-PROVer Tutorial_Software_Driver > Gcode` that you can try*
2. Now insert a drill bit into the chuck of the mill making sure that it is tightly secured with the included wrenches
3. You will now want to line up the bit to where you would like the GCode to start using the on screen buttons
