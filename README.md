# volatility-install-liunx

Stage 1:

 step 1>git clone https://github.com/volatilityfoundation/volatility.git
 step 2>sudo apt-get install pcregrep libpcre++-dev python-dev -y
 <span> if Error is given for python-dev not found then use python2-dev instand of python-dev </span>
 step 3>cd volatility
 step 4>sudo python setup.py install 
 <span> if Error is given for python not found then use python2 instand of python every where python is given</span>
 step 5>python setup.py build
 step 6>sudo python setup.py build install
 step 7>sudo apt-get install yara -y
 step 8>Copy the drive link>>https://drive.google.com/drive/folders/1S1Oo83VPGTK04mvLGhlIXmp20ak43R2K?usp=sharing
 
 Stage 2:
 
 step 9>unzip the folder that you have downloaded.Then enter into that folder.
 step 10>Then open a terminal here..
 step 11>cd distorm3
 step 12>sudo python setup.py build
 step 13>sudo python setup.py build install
 step 14>tar -xvzf pycrypto-2.6.1.tar.gz
 step 15>cd pycrypto-2.6.1
 <span>Use step 17 before 16 </span>
 <span> if Error is given for  include file: 'gmp.h': No such file or directory then use step 16 first other wise skip it</span>
 step 16>sudo apt install libmpc-dev
 step 17>sudo python setup.py build
 step 18>sudo python setup.py build install
 step 19>vol.py --h
