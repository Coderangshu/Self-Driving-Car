# Self-Driving-Car
Lateral and longitudinal controller for vehicle using stanley model for lateral control
  -The pathway for the vehicle has to be provided to it(provided by default)
  -The code has to be run in Carla Simulation made by unity engine
  -To run the simulator:
    *In LINUX:
      ./CarlaUE4.sh /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30
    *In Windows:
      CarlaUE4.exe /Game/Maps/RaceTrack -windowed -carla-server -benchmark -fps=30
  -To run the controller:
    *In LINUX:
      python3 module_7.py
    *In Windows:
      python module_7.py
