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
    
    tar xvfzsat_SWGCP.tar.gz
	tar xvfzml_madelon.tar.gz
	tar xvfzsat_UNSAT-UNIF-K5-CSSC14.tar.gz
	tar xvfzml_shuttle.tar.gz
	tar xvfzml_iris.tar.gz
	tar xvfzsat_BMC08-CSSC14.tar.gz
	tar xvfzsat_5SAT500-SAT-CSSC14.tar.gz
	tar xvfzsat_IBM-CSSC14.tar.gz
	tar xvfzasp_weighted-sequence.tar.gz
	tar xvfzml_covertype.tar.gz
	tar xvfzml_car.tar.gz
	tar xvfzsat_3SAT1K-SAT-CSSC14.tar.gz
	tar xvfzsat_CIRCUITFUZZ-CSSC14.tar.gz
	tar xvfzmip_BCOL-CLS.tar.gz
	tar xvfzsat_SWV-Calysto.tar.gz
	tar xvfzsat_circuit_fuzz.tar.gz
	tar xvfzsat_instances_satenstein.tar.gz.tar.gz
	tar xvfzsat_FACTORING.tar.gz
	tar xvfzsat_7sat90.tar.gz
	tar xvfzsat_CBMC.tar.gz
	tar xvfzsat_K3-CSSC14.tar.gz
	tar xvfzsat_QUEENS-CSSC14.tar.gz
	tar xvfzml_abalone.tar.gz
	tar xvfzml_krvskp.tar.gz
	tar xvfzml_waveform.tar.gz
	tar xvfzml_yeast.tar.gz
	tar xvfzmip_COR-LAT.tar.gz
	tar xvfzsat_SWGCP_SAT.tar.gz
	tar xvfzml_mnist.tar.gz
	tar xvfzml_winequalitywhite.tar.gz
	tar xvfzsat_3CNF-V350-CSSC14.tar.gz
	tar xvfzmip_Regions200.tar.gz
	tar xvfzsat_QCP.tar.gz
	tar xvfzsat_hgen2-small.tar.gz
	tar xvfzsat_k3-r4_26-v600.tar.gz
	tar xvfzsat_7SAT90-SAT-CSSC14.tar.gz
	tar xvfzsat_LABS-CSSC14.tar.gz
	tar xvfzplanning_zenotravel.tar.gz
	tar xvfzml_germancredit.tar.gz
	tar xvfzsat_GI-CSSC14.tar.gz
	tar xvfzml_semeion.tar.gz
	tar xvfzmip_RCW2.tar.gz
	tar xvfzml_secom.tar.gz
    
    chmod -R 777 .


