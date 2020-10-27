# Self-Driving-Car
Lateral and longitudinal controller for vehicle using stanley controller for lateral control
  -The pathway for the vehicle has to be provided to it(provided by default)<br>
  -The code has to be run in Carla Simulation made by unity engine<br>
  -To run the simulator:<br>
  <pre>
    *In LINUX:<br>
      ./CarlaUE4.sh /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30<br>
    *In Windows:<br>
      CarlaUE4.exe /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30<br>
      </pre>
  -To run the controller:<br>
  <pre>
    *In LINUX:<br>
      python3 module_7.py<br>
    *In Windows:<br>
      python module_7.py<br>
</pre>
  -The trajectory followed here is:<br>
  <img src=controller_output/trajectory.png width=550 height=570>
