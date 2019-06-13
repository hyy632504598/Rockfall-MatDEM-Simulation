# Rockfall-MatDEM-Simulation
A secondary development rockfall movement simulation code based on MatDEM.
1.Please download MatDEM from matdem.com.
2.Then you should unzip this file into the installation directory.
3.Digit elevation data should be put in '.txt' file like 'S1.txt' and the parameters of rock and soil can be reset in 'Mats' folder.
4.Then you can run MatDEM.exe, click on the main program, enter the 'rockfall' folder on the right, click 'R1'; then 'R2'; 'RN3' in sequence. 
5.The initial position of rock block should be set in this sentence 'd.moveGroup('rock',0.25,0,63.2);' in 'R2', the first one is X coordinate, the sencond one is Y coordinate and the last one is Z coordinate.
6.Finally you should confirm the results saved address in 'RN3', and then run 'R1'; 'R2'; 'RN3' in sequence.
7.Simulation results will be saved in the excel file in 'rockfall' folder.
