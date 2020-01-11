# rdkit
rdkit_sup

This file is for who want to use RDkit with python3 in Windows OS without anaconda!

Since the document binary installation is not good, when you finish the guide you would find still not work.
The error is :
ImportError: No module named 'rdkit.rdBase'       or
ModuleNotFound:rdBase

you will find you actually lose the rdbase.pyd file because the release you download dont have it




If you try to use rdkit without anaconda in Windows10 ,you can try my way to fix this problem

First download rdkit_win10.zip in my github

Second unzip it ,copy the "rdbase.pyd" to the directory  "rdkit"   you download from offical release

Third copy the "bin" directory to anywhere you want like C:\bin, and add the path to variable PATH

Finally you can try aggain,it will work!
