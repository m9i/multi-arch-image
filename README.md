# multi-arch-image
This repo shares all you need to do to create a multi-arch image. The idea came that if I'm not able to find a suitable IMG compatible with my architecture in the docker hub, why not build one multi-arch image for myself and also others "Build once, deploy anywhere". 
If you want to use ARM targets to reduce your bills, such as Raspberry Pis and AWS A1 instances, or even keep using your old i386 servers, deploying everywhere can become a tricky problem as you need to build your software for these platforms. For me, while moving to Apple Silicon M1 chip mac book which is arm64 based, It took some time for me to figure out how I can create docker images and share on docker hub that would work across different platforms.

