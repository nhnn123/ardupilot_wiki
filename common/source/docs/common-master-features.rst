.. _common-master-features:

===========================
Items in Master Branch Only
===========================

This lists features or changes merged in master and build in the "latest" firmware, but not in a stable or beta release yet. They have passed all test suites and usually have already been flight tested. These items are considered in the broad flight testing stage and test users are encouraged. Eventually, they will released in a beta, then stable release.


.. toctree::
    :maxdepth: 1
[site wiki="plane"]
    Airmode <airmode>
[/site]
[site wiki="copter,plane,rover"]
    Compass-less Operation<common-compassless>
[/site]
[site wiki="copter,plane"]
    In-Flight FTT and filter control <common-imu-fft>
[/site]
[site wiki="copter,plane,rover"]
    Hott Telem (already in Plane release) <common-hott-telemetry>
    Lightware SF45/B (350 degree) <common-lightware-sf45b>
    MSP OSD <common-msp-osd-overview>
    MSP (MultiWii Serial Protocol) <common-msp-overview>
    OSD Parameter Editor <common-paramosd>
    RunCam Control <common-camera-runcam>
    Velocity ESCs <common-velocity-can-escs>
[/site]
    
    Other wiki changes <common-future-wiki-changes>
    
[site wiki="plane"]
- :ref:`Change to PID scaling in QuadPlane Tailsitters <4.1-gainscaling>`
[/site]
- :ref:`Camera Trigger MAV Command change <mav_cmd_do_set_cam_trigg_dist>`
   



[copywiki destination="plane,copter,rover,dev"]
