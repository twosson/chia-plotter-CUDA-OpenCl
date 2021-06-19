[![code style: achow](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/achow1o1)
<p><cd><p><a href="https://github.com/achow1o1/ASIC-Bitcoin-privatekey-Miner" rel="nofollow"><img src="https://camo.githubusercontent.com/0a47442b4a3342164618c1838f886fbbf2db735b585a8ba985b320318f0132bc/68747470733a2f2f696d672e736869656c64732e696f2f636f6465636f762f632f6769746875622f6477796c2f686170692d617574682d6a7774322e7376673f6d61784167653d32353932303030" alt="codecov.io " data-canonical-src="https://img.shields.io/codecov/c/github/dwyl/hapi-auth-jwt2.svg?maxAge=2592000" style="max-width:100%;"></a></p>

# chia-plotter-CUDA-OpenCl


+ chia-plotter-CUDA.Exe
+ RTX 3070/ 1 Plots = 10sec

+ chia-plotter-OpenCl.Exe
+ AMD 5500 XT / 1 Plots = 35sec

+ Dowloads:
+ Tutorial PDF & SETTING UP Included in .ZIP file
+ Chia Ploting GPU RAM Drive Step by Step PDF File
+ chia-plotter-CUDA-OpenCl.Zip

https://satoshidisk.com/pay/CCiJTq

Usage: chia_plot [OPTION...]

-n, --count arg Number of plots to create (default = 1, -1 = infinite)

-r, --threads arg Number of threads (default = 4)

-u, --buckets arg Number of buckets (default = 256)

-v, --buckets3 arg Number of buckets for phase 3+4 (default = buckets)

-t, --tmpdir arg Temporary directory, needs ~220 GiB (default = $PWD)

-2, --tmpdir2 arg Temporary directory 2, needs ~110 GiB [RAM] (default = )

-d, --finaldir arg Final directory (default = )

-p, --poolkey arg Pool Public Key (48 bytes)

-f, --farmerkey arg Farmer Public Key (48 bytes)

-G, --tmptoggle Alternate tmpdir/tmpdir2 (default = false)

     --help Print help

Usage: chia_plot.GPU [OPTION...]

chia_plot.GPU [-check] 

[-v] [-gpu] [-gpuId gpuId1[,gpuId2,...]] 

[-g g1x,g1y,[,g2x,g2y,...]] 

[-t nbThread]

-V: Print version

-gpu: Enable gpu calculation

-gpu gpuId1,gpuId2,...: List of GPU(s) to use, default is 0

-g g1x,g1y,g2x,g2y, ...: Specify GPU(s) kernel gridsize, default is 8*(MP number),128

-T threadNumber: Specify number of CPU thread, default is number of core

-nosse: Disable SSE hash function

-l: List cuda enabled devices

-check: Check CPU and GPU kernel vs CPU
