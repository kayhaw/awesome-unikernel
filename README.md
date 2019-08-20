# Awesome Unikernel [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
An awesome list about Unikernel. Inspired by [awesome](https://github.com/sindresorhus/awesome)
> **Unikernels are specialised, single-address-space machine images constructed by using library operating systems.**
## :books: Books
- _[Unikernels:Beyond Containers to the Next Generation of Cloud](http://www.oreilly.com/webops-perf/free/unikernels.csp)_ - A unikernel primer, best option to get started with unikernel
- _[The Design and Implementation of the Anykernel and Rump Kernels](http://www.fixup.fi/misc/rumpkernel-book/)_ - A book for those who want to know more details about Rumprun
- _[Optimizing Boot Times and Enhancing Binary Compatibility for Unikernels](https://vtechworks.lib.vt.edu/bitstream/handle/10919/88865/Chiba_DJ_T_2018.pdf?sequence=1&isAllowed=y)_ - From Hermitux Project
## :bulb: Projects
- ### Misc
  - _[UKL](https://www.bu.edu/rhcollab/projects/linux-unikernels/)_ :new:
  - _[HEXO](http://popcornlinux.org/index.php/hexo)_ :new:
  - _[MirageOS](https://mirage.io/)_
  - _[Rumprun](http://rumpkernel.org/)_
  - _[OSv](http://osv.io/)_
  - _[ClickOS](http://cnp.neclab.eu/projects/clickos/)_
  - _[Clive](http://lsub.org/ls/clive.html)_
  - _[Drawbridge](http://research.microsoft.com/en-us/projects/drawbridge/)_
  - _[HaLVM](http://galois.com/project/halvm/)_
  - _[IncludeOS](http://www.includeos.org/)_
  - _[LING](http://erlangonxen.org/)_
  - _[Runtime.js](http://runtimejs.org/)_
  - _[HermitCore](https://hermitcore.org/)_
  - _[Hermitux](https://ssrg-vt.github.io/hermitux/)_
  - _[Unikraft](https://xenproject.org/developers/teams/unikraft/)_
- ### Unikernel Hypervisor
  - _[Solo5](https://github.com/Solo5/solo5)_ - Traditional hypervisors like KVM/QEMU, Xen are mainly used in unikernel projects, but Solo5 project propose ukvm(now called hvt), a specialized hypervisor for unikernel
- ### Management
  - _[Unik](https://github.com/solo-io/unik)_ - Unik provides building, deploying solution for unikernels
## :page_with_curl: Papers
  - _[Olivier, Pierre, et al. "HEXO: Offloading HPC Compute-Intensive Workloads on Low-Cost, Low-Power Embedded Systems." Proceedings of the 28th International Symposium on High-Performance Parallel and Distributed Computing. ACM, 2019.](https://dl.acm.org/citation.cfm?id=3325408)_ - Paper of HEXO
  - _[Madhavapeddy A, Mortier R, Rotsos C, et al. Unikernels: Library operating systems for the cloud[J]. Acm Sigplan Notices, 2013, 48(4): 461-472.](https://dl.acm.org/citation.cfm?id=2451167)_ - Paper of MirageOS, seek the origin of unikernel
  - _[Antti Kantee, Justin Cormack. Rump Kernels: No OS? No Problem! ;login: 39 (2014): n. pag.](https://www.usenix.org/system/files/login/articles/login_1410_03_kantee.pdf)_
  - _[Antti Kantee. The Rise and Fall of the Operating System. ;login: 40 (2015): n. pag.](https://www.usenix.org/system/files/login/articles/login_oct15_02_kantee.pdf)_
  - _[Lankes S, Pickartz S, Breitbart J. HermitCore: a unikernel for extreme scale computing[C]//Proceedings of the 6th International Workshop on Runtime and Operating Systems for Supercomputers. ACM, 2016: 4.](https://dl.acm.org/citation.cfm?doid=2931088.2931093)_ - Paper of HermitCore
  - _[Olivier P, Chiba D, Lankes S, et al. A Binary-Compatible Unikernel[J]. 2019.](https://dl.acm.org/citation.cfm?id=3313817)_ - Paper of Hermitux
  - _[Williams D, Koller R. Unikernel monitors: extending minimalism outside of the box[C]//8th {USENIX} Workshop on Hot Topics in Cloud Computing (HotCloud 16). 2016.](https://www.usenix.org/node/196335)_ - Paper of `ukvm`
  - _[Williams D, Koller R, Lucina M, et al. Unikernels as Processes[C]//Proceedings of the ACM Symposium on Cloud Computing. ACM, 2018: 199-211.](https://dl.acm.org/citation.cfm?id=3267845)_ - Extented work of `ukvm`
  - _[Raza A, Sohal P, Cadden J, et al. Unikernels: The Next Stage of Linux’s Dominance[J]. 2019.](https://www.bu.edu/rhcollab/files/2019/04/unikernel.pdf)_ - Paper of UKL
## :speech_balloon: Talks
- _[Unikernels: Rise of the Virtual Library Operating System](https://queue.acm.org/detail.cfm?id=2566628)_
## :tv: Videos
- _[LISA18-Unikraft: Unikernels Made Easy](https://www.youtube.com/watch?v=9PRKBZHArhI)_
- _[Unik: A Platform for Automating Unikernel Compilation and Deployment](https://www.youtube.com/watch?v=qtknmR_XnUE)_
- _[UniLinux: Unikernelized Linux](https://www.youtube.com/watch?v=4XIThgGLUNY)_
- _[Debunking Unikernel Criticisms](https://www.youtube.com/watch?v=lZKWK6c0ND0)_
- _[Rumprun Video Series](https://www.youtube.com/channel/UCEBgvAfntqRGXfaJjXgrktA)_
## :office: Commercial Usage
- _[NanoVms](https://nanovms.com/)_ - The only production ready unikernel platform in the industry, however source code is not open
## :heavy_plus_sign: Others
- _[Unikernel and Immutable Infrastructures](https://github.com/cetic/unikernels)_