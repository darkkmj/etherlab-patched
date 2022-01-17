# **etherlab-patched**
Forked from official source of the etherlab and applied with additional improvement

## **Version History**
### **[Patch-0006]**
#### Added
- r8169, 8139too drivers for kernel 5.10 from official reposition of the etherlab (https://gitlab.com/etherlab.org/ethercat.git, branch: realtek-5.10)
#### Fixed
- fixed build problem by add some missing files 
### **[Patch-0005]**
#### Added
- igb drivers for kernel 5.10
- complete to test in raspberry pi 4 cm with PCI-E igb card
### **[Patch-0004]**
#### Added
- add the rtdmnet driver (https://www.mail-archive.com/etherlab-dev@etherlab.org/msg00537.html)
- solved some compile problems when use rtdmnet driver in kernel 5.10
### **[Patch-0003]**
#### Added
- add new generation of the i219 device information to the e1000e driver 
### **[Patch-0002]**
#### Fixed
- fixed a freezing problem in the e1000e (https://etherlab-users.etherlab.narkive.com/zesmsJIx/e1000e-driver-freeze-on-kernel-4-9-80-rtai-5-1#post7)
- fixed a memory leak problem in the igb (https://www.mail-archive.com/etherlab-users@etherlab.org/msg03479.html)
### **[Patch-0001]**
#### Added
- r8169 drivers for kernel 4.19 
### **[Initial]**
#### Added
- forked from official source of the etherlab (http://hg.code.sf.net/p/etherlabmaster/code)
- applied several patches (from patchsets of Gavin Lambert) 
