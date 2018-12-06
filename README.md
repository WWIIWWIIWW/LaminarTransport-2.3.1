# LamianrTransport-2.3.1

This work is forked from [adhiraj-dasgupta/unsupportedContribOF23x](https://github.com/adhiraj-dasgupta/unsupportedContribOF23x). The origin work can be found [here](https://github.com/adhiraj-dasgupta/unsupportedContribOF23x).


Installation 

Preparation   
This code are based on OpenFOAM-2.3.1. You should install the OpenFOAM correctly before we start.
Also, you should install the gsl package with following command to compile the code with regard to fitting module.  

sudo apt-get install libgsl-dev

---
Step1: cd ~/OpenFOAM   
		git clone https://github.com/ZhengweiGao/LaminarTransport-2.3.1   

Step2: add  "export LIB_LaminarTransport_SRC=~/OpenFOAM/LaminarTransport-2.3.1/src/"  into your .bashrc.   

Step3:  cd src    
		wclean all   
		wmake all   

Step4: cd applications   
	   wclean all  
	   wmake all  

Now you can 