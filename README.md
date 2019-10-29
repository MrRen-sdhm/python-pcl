

#### ubuntu16.04

#### PCL1.8.1

#### VTK7.1.1

#### Python3.5



1、install ppython dependence

```
pip install --upgrade pip
pip install Cython==0.29.6
pip install numpy==1.15.1
```

２、install python-pcl

```
git clone https://github.com/strawlab/python-pcl.git
cd python-pcl

system enviroment：
sudo python setup.py build_ext -i
sudo python setup.py install

virtual enviroment：
python setup.py build_ext -i
python setup.py install
```


