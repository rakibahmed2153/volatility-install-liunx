# volatility-install-liunx

Stage 1:
<ol>
 <li>step 1>git clone https://github.com/volatilityfoundation/volatility.git</li>
 <li>step 2>sudo apt-get install pcregrep libpcre++-dev python-dev -y</li>
 <span> if Error is given for python-dev not found then use python2-dev instand of python-dev </span>
 <li>step 3>cd volatility</li>
 <li>step 4>sudo python setup.py install</li> 
 <span> if Error is given for python not found then use python2 instand of python every where python is given</span>
 <li>step 5>python setup.py build</li>
 <li>step 6>sudo python setup.py build install</li>
 <li>step 7>sudo apt-get install yara -y</li>
 <li>step 8>Copy the drive link>>https://drive.google.com/drive/folders/1S1Oo83VPGTK04mvLGhlIXmp20ak43R2K?usp=sharing</li>
 </ol>
 Stage 2:
 
 <li>step 9>unzip the folder that you have downloaded.Then enter into that folder.</li>
 <li>step 10>Then open a terminal here..</li>
 <li>step 11>cd distorm3</li>
 <li>step 12>sudo python setup.py build</li>
 <li>step 13>sudo python setup.py build install</li>
 <li>step 14>tar -xvzf pycrypto-2.6.1.tar.gz</li>
 <li>step 15>cd pycrypto-2.6.1</li>
 <span>Use step 17 before 16 </span></li>
 <span> if Error is given for  include file: 'gmp.h': No such file or directory then use step 16 first other wise skip it</span>
 <li>step 16>sudo apt install libmpc-dev</li>
 <li>step 17>sudo python setup.py build</li>
 <li>step 18>sudo python setup.py build install</li>
 <li>step 19>vol.py --h</li>
