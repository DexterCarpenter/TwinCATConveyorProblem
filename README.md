# TwinCATConveyorProblem
This was a 2-day project in which I learned Beckhoff’s TwinCAT 3 XAE and created a hypothetical solution to a problem for a job interview. I had no prior experience with Structured Text or Pascal prior to this!

### Objectives
- We have an conveyor with 4 buttons Start Stop AND E-Stop AND Reset.
- When system starts it shouldnt do anything until reset.
- Starting it should speed up to a RUN_SPEED, over ACCEL_TIME and maintain.
- If stop is Pressed speed should decrease to 0 over DECCEL_TIME.
- If E_Stop is Pressed speed should go immediately to 0.
- Before resuming operation after E-Stop, the system should require a reset.

[YouTube Video](https://youtu.be/GMHNJdMj_Cc?si=3ZSCfqIMml-DatSz)
