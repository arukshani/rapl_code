sudo apt-get update  
sudo apt-get -y install python3-pip  
pip3 install pandas  

sudo python3 rapl.py -l py_rapl.csv  

gcc -O2 -Wall -o objname rapl-plot.c -lm  
sudo ./objname  

0 (0), 1 (0), 2 (0), 3 (0), 4 (0), 5 (0), 6 (0), 7 (0)
        8 (0), 9 (0), 10 (1), 11 (1), 12 (1), 13 (1), 14 (1), 15 (1)
        16 (1), 17 (1), 18 (1), 19 (1), 20 (0), 21 (0), 22 (0), 23 (0)
        24 (0), 25 (0), 26 (0), 27 (0), 28 (0), 29 (0), 30 (1), 31 (1)
        32 (1), 33 (1), 34 (1), 35 (1), 36 (1), 37 (1), 38 (1), 39 (1)

Sample  
-------
Time (s)        Package0(W)     DRAM(W)         Package1(W)     DRAM(W)
0.500377        9.034828        0.870235        7.394072        1.383509
1.000783        7.244343        0.524180        6.432992        0.446855


References  
https://github.com/deater/uarch-configure/tree/master/rapl-read  
https://web.eece.maine.edu/~vweaver/projects/rapl/   