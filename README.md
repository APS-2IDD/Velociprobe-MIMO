### Velociprobe MIMO

LabVIEW code for Real-time and FPGA systems of NI cRIO 9039

## Build Specifications (Versions)

All builds are an extension of original RT and FPGA code built by Sheikh Tamjid Mashrafi

# Velociprobe-Base

Initial attempt at implementing choice of PID and H-infinity controllers.

# Velociprobe-Dual

Choose between H-infinity and PID controllers.

# Velociprobe-MultiScan

Has choice of controllers: H-infinity or PID; Choice of scan type: Fly or Step.

# Velociprobe-MultiTraj

Capable of: Step/Fly scans; Snake, grid spiral and Archimedean spiral trajectorios; Open loop/Closed loop control (for the latter: H-Infinity and PID controllers available)

# Velociprobe-ModTrans (Latest)

Has multi-trajectory capability (as in MultTraj) but uses modular transfer function on FPGA. Also includes post-scan zeroing; data-saving trigger control (separate from detector and trajectory triggering); and enforced duty-cycle limits.
