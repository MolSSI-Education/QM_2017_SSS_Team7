[![codecov](https://codecov.io/gh/MolSSI-SSS/QM_2017_SSS_Team7/branch/master/graph/badge.svg)](https://codecov.io/gh/MolSSI-SSS/QM_2017_SSS_Team7)
[![Build Status](https://travis-ci.org/MolSSI-SSS/QM_2017_SSS_Team7.svg?branch=master)](https://travis-ci.org/MolSSI-SSS/QM_2017_SSS_Team7)

# QM_2017_SSS_Team7

![alt_text](https://lh3.googleusercontent.com/0F34szQp5v-7LxWpRP_htZeeP4p691p8FZjimGmqMgdzI5hWIX3ZFH_f6cczy6iAJ_4z-Zi1JX_WyZ_oLvJr906hgxdyHwfBif1Zg74Lmk3pFOYmNm-pcI_Nnv6zYJklxg2igPQfbNaJjRQ536ewoiuW5KDV_S2PX6qZWry40ZQEyxOjYvpbld3vX5wJuSHOxBtupON0hPjNhKQaqIuaccDW87dyfVD9cQM0oX-IHLrDH_G4F096fsKTizOBbHQrQtsAMFDR1WvthrgYBPtr1J9cQ8ONCPz7mWFS1TR16fMut1TeksprSnzMJf1p8hm9zl1g1GVk2qQ3SfFTh01N3REvScLWHyYIK0jzpoFOeWn6yR4Di_ndSCtOqN-nYuXLFqWenzyFp9crLumOWwZmFwukgbV6SGpdBJ3NchIXcg4fFDHfwlFSTzgQDASLSS_ujylAtJPa-5dbLluEc8F1NUSvbHZOovck-abwWeOhRGV80yBDqQbcqHnK9NFMjoIEhfm6llzoKrxSm7yxBWX-fSfZ_TIwU6eXzZMM2pjIpO0yR6eOu9C1h-mj6U2XwMKgeLIt-dtPpWeavDF7vAPrH3xfPzXMIB6lGFCWEOEU7NMqCbeMHP4TfBuy=w1580-h418-no)

## Installation
Download the repository and run `setup.py` as follows:
```
git clone https://github.com/MolSSI-SSS/QM_2017_SSS_Team7
cd QM_2017_SSS_Team7
python setup.py install
```
Alternatively you can set up the environment by following the instructions [here](https://molssi-sss.github.io/Logistics_SSS_2017/Setup.html). After the environment is configures make sure to activate your python environment:

```python
source activate sss
```

## Usage
Run following to see options:
```
python scf.py --help
```

### Compiling the JK algorithm
Go to `JKbinding` folder and run:
```
mkdir build
cd build
cmake ../ -DCMAKE_CXX_FLAGS="-Ofast"
make
```
Then copy the Python code to `build` directory and run it:
```
cp ../JKbinding.py .
python JKbinding.py
```

## Team Members
- Srinivas Mushnoori
- Sangeeta Sur
- Zhiwei Ding
- Kutay B. Sezginel
