# 5GISN_sns3

[Original GitHub](https://github.com/sns3)

# Requirements

Linux OS

C++ 11

# Building SNS3

`cd 5GISN_sns3/contrib/satellite/`

`git clone https://github.com/sns3/sns3-data.git data`

`Go back to 5GISN_sns3`

`(./waf clean) Not needed first time`

`CXXFLAGS="-std=c++11" ./waf configure --enable-examples --enable-tests`

`./waf build -j 6`

# Document 

[ns3.29](https://www.nsnam.org/releases/ns-3-29/)

[satellite extension](https://www.sns3.org/content/home.php)

