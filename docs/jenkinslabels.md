# Schema for Jenkins Labels


## The Schema Tree

![Schema tree](schemaTree.jpg)

  
## Actual Labels and Consumers

If we work on the principle that we only add a label if the build and test automation scripts require it in order to differentiate a machine, then the list is fairly small.

Label | Consumer 
----------- | ----------- 
hw.arch.s390x | test, build 
hw.arch.ppc64 | test, build 
hw.arch.x86 | test, build
hw.endian.le | test, build
hw.bits.32 | test, build
ci.role.build | build
ci.role.test | test
ci.role.test.jck | [jck tests](https://ci.adoptopenjdk.net/view/JCK%20tests/)
sw.tool.docker | [external tests](https://ci.adoptopenjdk.net/view/External%20tests/)
sw.os.linux | test
sw.os.aix | test
sw.os.osx| test
sw.os.windows| test
 | 
sw.os.rhel.6 | tbd
sw.os.rhel.7 | tbd
sw.os.ubuntu.14 | tbd
sw.os.ubuntu.16 | tbd
sw.os.sles.11 | tbd
sw.os.sles.12 | tbd

