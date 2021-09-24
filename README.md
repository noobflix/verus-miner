SISTEMA 64BITS


pkg install wget -y ; pkg install wget proot -y && wget https://raw.githubusercontent.com/MasterDevX/KaliTermux/master/InstallKali.sh && bash InstallKali.sh


INSTALAR MINERARDOR



apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential ; apt-get install git -y ; git clone https://github.com/monkins1010/ccminer.git ; cd ccminer ; chmod +x build.sh ; chmod +x configure.sh ; chmod +x autogen.sh ; ./build.sh

MINERAR

./ccminer -a verus -o stratum+tcp://ap.luckpool.net:3956 -u RJVg86NQgFj6efLBVmnoiw2T8fz19nD7r4.celular -p hybrid -t 8 
