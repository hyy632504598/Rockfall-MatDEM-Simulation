# Rockfall-MatDEM-Simulation
# A secondary development rockfall movement simulation code based on MatDEM.
1.Please download MatDEM from matdem.com, this code should run under matlab runtime 2019.
\n 2.Then you should unzip "rockfall.zip" into the "MatDEM" folder.
3."R1.m" is for the establishment of model box, and sample L, sample W and sample H is the legth, width and height of model box. You should set these data bigger than the scale of slope because the rockfall movement space is needed.
4."R2.m" is for the establishment of  slope model and rock block model.Digit elevation data should be put in '.txt' file like 'S1.txt' and the parameters of rock and soil can be reset in 'Mats' folder.The initial position of rock block should be set in this sentence 'd.moveGroup('rock',0.25,0,63.2);' in 'R2', the first one is X coordinate, the sencond one is Y coordinate and the last one is Z coordinate.
5."RN3" is for rockfall movement simulation, results obtained by simulation will be saved in the excel file you preset.
6.Then you can run MatDEM.exe, click on the main program, enter the 'rockfall' folder on the right, click and run 'R1';  'R2'; 'RN3' in sequence. 
7.Simulation results will be saved in the excel file in 'rockfall' folder.
