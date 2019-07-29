#  Malware Analysis

A curated list of awesome malware analysis tools and resources
## Contents
- [Malware Collection](#)
    - [Virus Share](https://virusshare.com/)
    - [Virus Total](https://www.virustotal.com/gui/home/upload)
- [Static Analysis](https://github.com/mianarslan78/Malware-Analysis/tree/master/Static%20Analysis)
    - [Windows Portable Executable Format](https://docs.microsoft.com/en-us/windows/win32/debug/pe-format)
    - [Static Feature / Attribute Parser](https://github.com/mianarslan78/Malware-Analysis/blob/master/Static%20Analysis/Static_Feature_Parser.ipynb)

    - [Static Feature / Attribute List](https://github.com/mianarslan78/Malware-Analysis/blob/master/Static%20Analysis/Static_Feature_Vector.ipynb)
    
- [Dynamic Analysis](https://github.com/mianarslan78/Malware-Analysis/tree/master/Dynamic%20Analysis)
    - [How to make Sandbox](https://github.com/mianarslan78/Malware-Analysis/blob/master/Dynamic%20Analysis/Sandbox_Tutorial.ipynb)
    - [Dynamic Feature / Behavoir Parser](https://github.com/mianarslan78/Malware-Analysis/blob/master/Dynamic%20Analysis/Dynamic_Feature_Parser.ipynb)
    - [Dynamic Feature / Behavoir List](https://github.com/mianarslan78/Malware-Analysis/blob/master/Dynamic%20Analysis/Dynamic_Feature_Vector.ipynb)
    
    

## Static Analysis
  Static Analysis can be done by checking physical states of file. In our case , we used executable file as static samples and to check the physical states of windows executable file Windows provide Portable Executable Format (PE Format) which describes the structure of executable (image) files and object files under the Windows family of operating systems. These files are referred to as Portable Executable (PE) files.

## Dynamic Analysis
  Behaviour Analysis is similar to Dynamic Analysis therefore we created sandbox to find the behaviour of our malicious and good samples 
  and these behaviour includes Registry Operations , Files Operations , Api's Calls , Dll loaded , Mutex Information etc 
