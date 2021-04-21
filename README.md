# ECE 562 - Final Project


Files changed from original:<br />
configs/common/CacheConfig.py<br />
configs/common/Options.py<br />
configs/common/Caches.py<br />
src/mem/XBar.py<br />

All changes made by kama commented with name.

running with:<br /><br />
build/ARM/gem5.opt --stats-file='FIRSTTRY.txt' --dump-config='config.ini' configs/example/se.py --caches --l1i_size=32kB --l1i_assoc=4 --l1d_size=32kB --l1d_assoc=4 --l2cache --victimcache --vic_assoc=1 --vic_size=512B --cacheline_size=64 --cpu-clock=1.6GHz -n 1 --maxinsts=100000000 --bench mcf


<br/>
Questions:<br/>
Should VictimXBar be point of unification? point of coherency?<br/>
Are all caches properly connected?<br/>
Is cache logic correct?<br/>
