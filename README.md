Autonomous UAV Mission Controller (C++20)

Designed and implemented a multithreaded UAV flight-control simulation 
featuring sensor fusion, mission planning, telemetry processing, state-machine 
flight modes, obstacle detection, and real-time navigation architecture.
                 
                    
                    Mission Planner
                           │
                           ▼
                ┌──────────────────┐
                │ Flight Controller│
                └─────────┬────────┘
                          │
        ┌─────────────────┼─────────────────┐
        ▼                 ▼                 ▼

   GPS Sensor       IMU Sensor        Altimeter

        │                │                │
        └────────────────┼────────────────┘
                         ▼

                  Navigation Engine

                         ▼

                  Flight Modes

                ┌─────────────┐
                │ MANUAL      │
                │ AUTO        │
                │ LOITER      │
                │ RTL         │
                │ LAND        │
                └─────────────┘

                         ▼

                     Telemetry

                         ▼

                      Ground
                     Station
