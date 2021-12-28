Prerequisite:
Download the code folder from canvas
Unzip the code folder and store it on C Drive folder ONLY (otherwise update the path in code on line 405 and 424. Search for path variable.

You can use either python 3.9 or 3.10.
If you are using 3.9, use the files named as cp39 when installing the dependencies
If you are using 3.10, use the files named as cp310 when installing the dependencies

Steps to run on a windows machine 
1. Install Python version 3+
2. Install latest version of PIP package installer 
3. Install latest version of numpy using PIP (pip install numpy)
4. Install latest version of pandas using PIP (pip install pandas)
5. Install latest version of matplotlib using PIP(pip install matplotlib)
6. Install geopandas and its dependecies as follows 
a. Unzip dependencies folder from main code folder 
b. Go to the folder where the binaries are extracted.
c. Open cmd as administrator from the extracted folder
d. The following order of installation using pip install is necessary. Be careful with the filename. It should work if the filename is correct: (Tip: Type “pip install” followed by a space and type the first two letters of the binary and press Tab. (e.g. pip install gd(press Tab))
pip install GDAL-3.3.3-cp39-cp39-win_amd64.whl
pip install pyproj-3.3.0-cp39-cp39-win_amd64.whl
pip install Fiona-1.8.20-cp39-cp39-win_amd64.whl
pip install Shapely-1.8.0-cp39-cp39-win_amd64.whl
pip install geopandas-0.10.2-py2.py3-none-any
7. Open the command prompt where the python code file is stored
8. Run py mapcoloring.py


If you get any error please feel free to reach any of the group member.