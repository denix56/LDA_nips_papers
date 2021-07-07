## Dependencies
 * Python 3.6
 * Virtualenv
 
## Installation
To install virtualenv issue:
```
pip3 install virtualenv
```

To create the Python 3.6 environment:
```
virtualenv -p python3.6 .env
```

To install all packages:
```
source .env/bin/activate
pip3 install -U pip
pip3 install -r requirements.txt
```

## Folder structure
```
root/
|__|data/
|  |__|raw/
|  |__|processed/
|__|notebooks/
|  |__|modeling/                    Naming convention: <YYYMMDD>_authorInitials>_<description>
|  |__|processing/                  Naming convention: <YYYYMMDD>_<authorInitials>_<executionSequence>_<description>
|__|readme.md
|__|requirements.txt
```
