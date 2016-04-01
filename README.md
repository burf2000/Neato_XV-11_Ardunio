# Neato_XV-11_Ardunio
Up to date help on getting the Neato XV-11 talking to the Arduino and displaying data on a computer.  
I found that the orginal code did not compile any more and there where too many extra files you just did not need.  This is the bare min to get the sensor displaying data on a screen

Code is from Nicolas "Xevel" Saugnier : https://github.com/Xevel/NXV11 and Cheng-Lung Lee https://github.com/bombilee/NXV11  

Wiring  
Wiring diragrams and pictures can be found in the Arduino directory.  
- 2 * 1k Resister
- 1 * IRLB8721PBF N-channel Power MOSFET 30V 62A TO-220 (eBay)
- 1 * General Purpose Diodes IN4004

Arduino  (tested in 1.6.7)  
- Run the code in the Arduino directory  

Python  
- install VPython  
- install PySerial  
- open XV-11_test.py in VIDLE (installed with VPython) 
- set your COM port number (Windows e.g 4, Mac '/dev/tty.usbmodem14131')  
- F5 to run. Maintain left+right mouse button + move the mouse up and down to zoom.  



Licensing

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
