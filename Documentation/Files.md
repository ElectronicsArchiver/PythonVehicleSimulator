Root folder:
/src/python_vehicle_simulator/ 
    main.py                 - MAIN PROGRAM (terminal command >>python3 main.py)
    3D_animation.gif        - 3D animation file which can be opened in a web browser by right-clicking the file   
    
Library files:
/src/python_vehicle_simulator/lib/         
    control.py              - feedback control systems
    gnc.py                  - generic GNC functions
    guidance.py             - guidance functions        
    mainLoop.py             - main simulation loop
    plotTimeSeries.py       - plotting and animation functions

Vehicle classes/methods: 
/src/python_vehicle_simulator/vehicles/              
    DSRV.py                 - Deep submergence rescue vehicle (DSRV) controlled by a stern plane, L = 5.0 m
    frigate.py              - Frigate, rudder-controlled ship described by a nonlinear Nomoto model, L = 100.0 m
    otter.py                - Otter unmanned surface vehicle (USV) controlled by two propellers, L = 2.0 m
    ROVzefakkel.py          - ROV Zefakkel, rudder-controlled ship described by a nonlinear Nomoto model, L = 54.0 m
    semisub.py              - Semisubmersible controlled by tunnel thrusters and main propellers, L = 84.5 m
    shipClarke83.py         - Ship, linear maneuvering model specified by L, B and T using the Clarke (1983) formulas
    supply.py               - Offshore supply vessel controlled by tunnel thrusters and main propellers, L = 76.2 m
    tanker.py               - Tanker, rudder-controlled ship model including shallow water effects, L = 304.8 m
    remus100.py             - Cylinder-shaped AUV controlled by a rudder, stern planes and a propeller, L = 1.6 m        
    