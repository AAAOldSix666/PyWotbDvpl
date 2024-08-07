Tips:
1. If you want to compile a Python code including PyWotbDvpl to a executable ,you need to add following code in .spec file
hiddenimports=['lz4.block','struct','zlib']


2.The following is usage:

#py code

from PyWotbDvpl.DVPL import encryptDvpl,decryptDvpl 

encryptData=encryptDvpl('')
#write a string data or a bytes data in ''

decryptData=decryptDvpl('')
#write a file name in ''
