# ECE 562 - Final Project


Files changed:
configs/common/CacheConfig.py
configs/common/Options.py
configs/common/Caches.py
src/mem/XBar.py

All changes made by kama commented with name.

running with:
build/ARM/gem5.opt --stats-file='FIRSTTRY.txt' --dump-config='config.ini' configs/example/se.py --caches --l1i_size=32kB --l1i_assoc=4 --l1d_size=32kB --l1d_assoc=4 --l2cache --victimcache --vic_assoc=1 --vic_size=512B --cacheline_size=64 --cpu-clock=1.6GHz -n 1 --maxinsts=100000000 --bench mcf
