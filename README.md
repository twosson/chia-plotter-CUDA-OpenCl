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

Usage:
  chia_plot [OPTION...]

  -n, --count arg      Number of plots to create (default = 1, -1 = infinite)
  -r, --threads arg    Number of threads (default = 4)
  -u, --buckets arg    Number of buckets (default = 256)
  -v, --buckets3 arg   Number of buckets for phase 3+4 (default = buckets)
  -t, --tmpdir arg     Temporary directory, needs ~220 GiB (default = $PWD)
  -2, --tmpdir2 arg    Temporary directory 2, needs ~110 GiB [RAM] (default = <tmpdir>)
  -d, --finaldir arg   Final directory (default = <tmpdir>)
  -p, --poolkey arg    Pool Public Key (48 bytes)
  -f, --farmerkey arg  Farmer Public Key (48 bytes)
  -G, --tmptoggle      Alternate tmpdir/tmpdir2 (default = false)
      --help           Print help
   
  Usage:
  chia_plot.GPU [OPTION...]
      
  chia_plot.GPU [-check] [-v] [-gpu]
                [-gpuId gpuId1[,gpuId2,...]] 
                [-g g1x,g1y,[,g2x,g2y,...]] [-t nbThread]

+ -V: Print version
+ -gpu: Enable gpu calculation
+ -gpu gpuId1,gpuId2,...: List of GPU(s) to use, default is 0
+ -g g1x,g1y,g2x,g2y, ...: Specify GPU(s) kernel gridsize, default is 8*(MP number),128
+ -T threadNumber: Specify number of CPU thread, default is number of core
+ -nosse: Disable SSE hash function
+ -l: List cuda enabled devices
+ -check: Check CPU and GPU kernel vs CPU
