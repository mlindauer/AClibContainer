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
    wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_SWGCP.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_madelon.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_UNSAT-UNIF-K5-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_shuttle.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_iris.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_BMC08-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_5SAT500-SAT-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_IBM-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/asp_weighted-sequence.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_covertype.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_car.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_3SAT1K-SAT-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_CIRCUITFUZZ-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/mip_BCOL-CLS.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_SWV-Calysto.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_circuit_fuzz.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_instances_satenstein.tar.gz.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_FACTORING.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_7sat90.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_CBMC.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_K3-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_QUEENS-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_abalone.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_krvskp.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_waveform.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_yeast.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/mip_COR-LAT.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_SWGCP_SAT.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_mnist.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_winequalitywhite.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_3CNF-V350-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/mip_Regions200.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_QCP.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_hgen2-small.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_k3-r4_26-v600.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_7SAT90-SAT-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_LABS-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/planning_zenotravel.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_germancredit.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/sat_GI-CSSC14.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_semeion.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/mip_RCW2.tar.gz
	wget http://aad.informatik.uni-freiburg.de/~lindauer/aclib/ml_secom.tar.gz
    
    tar xfz sat_SWGCP.tar.gz
	tar xfz ml_madelon.tar.gz
	tar xfz sat_UNSAT-UNIF-K5-CSSC14.tar.gz
	tar xfz ml_shuttle.tar.gz
	tar xfz ml_iris.tar.gz
	tar xfz sat_BMC08-CSSC14.tar.gz
	tar xfz sat_5SAT500-SAT-CSSC14.tar.gz
	tar xfz sat_IBM-CSSC14.tar.gz
	tar xfz asp_weighted-sequence.tar.gz
	tar xfz ml_covertype.tar.gz
	tar xfz ml_car.tar.gz
	tar xfz sat_3SAT1K-SAT-CSSC14.tar.gz
	tar xfz sat_CIRCUITFUZZ-CSSC14.tar.gz
	tar xfz mip_BCOL-CLS.tar.gz
	tar xfz sat_SWV-Calysto.tar.gz
	tar xfz sat_circuit_fuzz.tar.gz
	tar xfz sat_instances_satenstein.tar.gz.tar.gz
	tar xfz sat_FACTORING.tar.gz
	tar xfz sat_7sat90.tar.gz
	tar xfz sat_CBMC.tar.gz
	tar xfz sat_K3-CSSC14.tar.gz
	tar xfz sat_QUEENS-CSSC14.tar.gz
	tar xfz ml_abalone.tar.gz
	tar xfz ml_krvskp.tar.gz
	tar xfz ml_waveform.tar.gz
	tar xfz ml_yeast.tar.gz
	tar xfz mip_COR-LAT.tar.gz
	tar xfz sat_SWGCP_SAT.tar.gz
	tar xfz ml_mnist.tar.gz
	tar xfz ml_winequalitywhite.tar.gz
	tar xfz sat_3CNF-V350-CSSC14.tar.gz
	tar xfz mip_Regions200.tar.gz
	tar xfz sat_QCP.tar.gz
	tar xfz sat_hgen2-small.tar.gz
	tar xfz sat_k3-r4_26-v600.tar.gz
	tar xfz sat_7SAT90-SAT-CSSC14.tar.gz
	tar xfz sat_LABS-CSSC14.tar.gz
	tar xfz planning_zenotravel.tar.gz
	tar xfz ml_germancredit.tar.gz
	tar xfz sat_GI-CSSC14.tar.gz
	tar xfz ml_semeion.tar.gz
	tar xfz mip_RCW2.tar.gz
	tar xfz ml_secom.tar.gz
    
    chmod -R 777 .


