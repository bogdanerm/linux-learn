ps f -g<PID>
ps -ejH                                                     # - process hierarchy using ps
pstree -aps $$                                               # - process hierarchy of current active process 
ps axjf
ls /dev/fd                                                   # - find fd directory
ls -l /proc/self/fd                                          # - list self process streams
ls -l /proc/<PID>/fd                                          # - list process streams
