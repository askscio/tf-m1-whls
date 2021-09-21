### Tensorflow Whl libraries for M1
These are binaries of tensorflow compiled from source **without** AVX instructions so that they are compatible with M1 Macs.

Example installation:
```
pip install https://github.com/askscio/tf-m1-whls/raw/master/tensorflow-1.15.4-cp37-cp37m-macosx_11_0_x86_64.whl
```

Or add this line to a `requirements.txt` file:
```
https://github.com/askscio/tf-m1-whls/raw/master/tensorflow-1.15.4-cp37-cp37m-macosx_11_0_x86_64.whl; platform_system == "Darwin"
```
