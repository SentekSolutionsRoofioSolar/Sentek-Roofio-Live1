> run: ![.!wget -c https://repo.continuum.io/archive/Anaconda3-5.1.0-Linux-x86_64.sh
!chmod +x Anaconda3-5.1.0-Linux-x86_64.sh
!bash ./Anaconda3-5.1.0-Linux-x86_64.sh -b -f -p /usr/local
!conda install -q -y --prefix /usr/local -c pytorch -c tensorcomp tensor_comprehensions

import sys
sys.path.append('/usr/local/lib/python3.6/site-packages/')]
