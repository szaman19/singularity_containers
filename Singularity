Bootstrap: docker
From: centos:7


%post 
	yum -y update
	yum -y install yum-utils
	yum -y groupinstall development
	yum -y install https://centos7.iuscommunity.org/ius-release.rpm
	yum -y install python36u
	yum -y install python36u-devel
	yum -y install python36u-pip	
	echo "Installed system dependencies"
	
	pip3.6 install --upgrade pip	
	pip3.6 install --no-cache-dir numpy
	
%environment 
	
%test 

