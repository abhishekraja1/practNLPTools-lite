
## If there is an issue in stanford parser. 
If the stanford parser can not be copy into installing location. So for quick working on Dependence parser the one possible solution I am asking you to follow, until the issue is resolved.
1. Assigning the location like this `annotator=Annotator();annotator.stp_dir="location_pls"` with respect to your os environment or follow the below steps
1.  please use the this package without installing(as local package without installing) which have `stanford-parser.jar`  inside  
2. Placing the `stanford-parser.jar` explicitly inside the installing in linux on python 3.x usual location is 
`/usr/local/lib/python3.5/dist-packages/pntl`  
3.  if you are using Anaconda distribution python the possible location is `/home/<user_name>/anaconda3/lib/python3.5/site-packages/pntl/` (without `virtual environment`)
4.  For Windows if you have install python in `C:` the go to the path  
`c:\users\<user_name_here>\local\programs\python3<just_version_number_here>\lib\site-packages\pntl` 
or for Anaconda Python distribution `C:\anaconda3\Lib\site-packages\pntl`

 Eg:
`c:\users\jawahar\local\programs\python35\lib\site-packages\pntl`
this is an example path with Python 3.5 installed in Windows system with jawahar as its user name.

> Note:- In Anaconda distribution it has its own version number so please change if you have to and change the Python version according which is present in your system. For windows there is no need to `.`(dot) in between version number of Python.
