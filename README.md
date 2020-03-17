# cualize

* Cumulative Histogram Equalization using OpenCL
* forked from [ImageHistogram](https://github.com/shreyasbhatia09/ImageHistogram)
* MIT License (except the original work by [Shreyas](https://github.com/shreyasbhatia09))


## References

* [ImageHistogram](https://github.com/shreyasbhatia09/ImageHistogram), C++/OpenCL implementation of linear equalization algorithm
* [Get Started with Intel® SDK for OpenCL](https://software.intel.com/en-us/articles/sdk-for-opencl-2019-gsg-linux-os)
* [Histogram Equalization by Patricio Bulic](https://ucilnica.fri.uni-lj.si/pluginfile.php/133289/mod_resource/content/0/HistogramEquilization2019.pdf)


## Dev Env Preparation on Linux Mint 19

Download "Intel® CPU Runtime for OpenCL™ Applications for Linux* OS"

`l_opencl_p_18.1.0.015.tgz`

Unpack it.

    tar xvzf l_opencl_p_18.1.0.015.tgz
    cd l_opencl_p_18.1.0.015/

Install dependent packages, install runtime

    sudo apt-get install libnuma1 zlib1g libxml2 lsb-core
    sudo ./install_GUI.sh


Download "Intel System Studio" and install

`system_studio_2020_ultimate_edition_offline.tar.gz`
`license.lic`


## Compilation

    g++ main.cpp -lOpenCL -std=c++11 -o ocl_vector_addition.o
