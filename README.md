# SPEC06

1. Compile
- cd /scratch/cluster/zshi17/spec/config
- run ../bin/runspec --config=akanksha_config_debug.cfg --action=build --tune=base soplex

2. Inspect binary
- cd /scratch/cluster/zshi17/spec/benchspec/CPU2006/450.soplex/exe/
- addr2line -e soplex_base.amd64-m64-gcc42-nn

irregular benchmarks: soplex, omnetpp, sphinx3, xalancbmk, astar
regular benchmarks: lbm, leslie3d？

3. 
