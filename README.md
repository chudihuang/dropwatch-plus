# dropwatch-plus
dropwatch-plus  is an interactive utility for monitoring and recording packets with specific ip/port that are dropped by the kernel. it is based on dropwatch

Prerequisites
systemtap kernel-debuginfo

Usage

stap -g -v --all-modules dropwatch-plus.stp ip

for example 
stap -g -v --all-modules dropwatch-plus.stp 10.14.83.89
