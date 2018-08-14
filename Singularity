Bootstrap: docker
From: ubuntu:18.04

%post
    chmod 755 /root
    apt-get -y update
    apt-get -y install python3 python3-pip git build-essential wget tar openjdk-11-jdk vim gcc-multilib 
    pip3 install Cython numpy scipy
    git clone https://github.com/mlindauer/GenericWrapper4AC.git
    cd GenericWrapper4AC
    python3 setup.py install
    cd ..
    git clone https://mlindauer@bitbucket.org/mlindauer/aclib2.git
    cd aclib2
    pip3 install -r requirements.txt
    wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_QCP.tar.gz
    tar xvfz sat_QCP.tar.gz
    chmod -R 777 .
    sed "s#python#python3#g" /aclib2/scenarios/sat/satenstein_qcp/scenario.txt -i


