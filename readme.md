Simple calibration programs
===========================

A collection of CRBasic datalogger programs for validating calibration of trace
gas analyzers. In general, the analyzers are not modified in any way -- their
performance is just recorded and summarized.

### Automatic programs

These programs are intended as single-shot routines. The user does initial
setup, triggers the program, and merely supervises operation.

#### `auto_EC150.cr1`

A calibration assessment routine for the EC150 using a CR1000. Supports up
to 3 gas cylinders plumbed into solenoid valves controled by ports C6-C8. 


### Manual programs 

These programs are fully user-controlled. Basically:

0. With the `Run mode` in *Off*...
1. Enter calibration gas concentration, tolerance and any relevant notes (we
   recommend listing the cylinder # or other traceability reference)
2. Switch `Run mode` to *Recording* for a sufficiently long duration
3. Revert `Run mode` back to *Off*

#### `manual_EC150.cr3`

For a Campbell Scientific EC150 open-path CO2/H2O gas analyzer. 

#### `manual_m205.cr6`

For assessment of a 2B Technologies model 205 dual beam ozone monitor using a CR6.

#### `manual_m405_42C.cr3`

For simultaneous assessment of a 2B Technologies model 405 nm and a Themo
Environmental Corp (TECO) model 42C.

#### `manual_UGGA.cr3`

For a Los Gatos Research ultraportable greenhouse gas analyzer.

