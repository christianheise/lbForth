[AppHarbor](https://appharbor.com/)  
[(no badge)](https://appharbor.com/applications/lbforth)  
Files: [`appharbor.sln`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/appharbor.sln),
[`packages.config`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/packages.config), and
[`build.vcxproj`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/build.vcxproj)

[AppVeyor](http://appveyor.com/)  
[![AppVeyor](https://ci.appveyor.com/api/projects/status/r8wuvf0n0obp3n14)]
(https://ci.appveyor.com/project/larsbrinkhoff/lbforth/history)  
File: [`appveyor.yml`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/appveyor.yml)

[Bitrise](http://bitrise.io/)  
[![Bitrise](https://www.bitrise.io/app/663938c8cb3bee14.svg?token=34FFBj3CLaI1yWXqou5JEg&branch=master)]
(https://www.bitrise.io/app/663938c8cb3bee14)  
Install: `install-deps.sh install_osx`  
Build: `gnumake M32=`  
Test: `gnumake check M32=`

[BuildHive](http://buildhive.cloudbees.com/)  
[![BuildHive](https://buildhive.cloudbees.com/job/larsbrinkhoff/job/lbForth/badge/icon)]
(https://buildhive.cloudbees.com/job/larsbrinkhoff/job/lbForth/)  
File: [`gradlew`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/gradlew)

[CircleCI](http://circleci.com/)  
[![CircleCI](https://circleci.com/gh/larsbrinkhoff/lbForth.svg?style=svg)]
(https://circleci.com/gh/larsbrinkhoff/lbForth)  
File: [`circle.yml`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/circle.yml)

[Codeship](http://codeship.io/)  
[![Codeship](https://www.codeship.io/projects/625b1e20-3cdd-0132-2ca6-12c33aebd1cb/status?branch=master)]
(https://codeship.com/projects/43094)  
Install: `install-deps.sh download_sbcl`  
Build:

    export SBCL_HOME=$PWD/sbcl/lib/sbcl
    export PATH=$PATH:$PWD/sbcl/bin
    make all M32=
    make check

[Drone.io](http://drone.io/)  
[![Drone.io](https://drone.io/github.com/larsbrinkhoff/lbForth/status.png)]
(https://drone.io/github.com/larsbrinkhoff/lbForth)  
Build:

    install-deps.sh install_linux
    make check M32=$M32

[Magnum CI](http://magnum-ci.com/)  
[![Magnum CI](https://magnum-ci.com/status/96ffb83fa700f069024921b0702e76ff.png)]
(https://magnum-ci.com/projects/1810/history)  
Install: `install-deps.sh install_linux`  
Build: `make check M32=`

[Semaphore](http://semaphoreci.com/)  
[![Semaphore](https://semaphoreci.com/api/v1/projects/726d1f9e-ae3a-4ef6-b109-39b2eeef14b1/531496/badge.svg)]
(https://semaphoreci.com/larsbrinkhoff/lbforth)  
Build:

    install-deps.sh install_linux
    make check M32=



[Ship.io](http://ship.io/)  
[![Ship.io](https://app.ship.io/jobs/7oIHDz28rgdvceSO/build_status.png)]
(https://app.ship.io/dashboard#/jobs/2822/history)  
File: [`gradlew`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/gradlew)

[Shippable](http://shippable.com/)  
[![Shippable](https://api.shippable.com/projects/5444c5ecb904a4b21567b0ff/badge?branchName=master)]
(https://app.shippable.com/projects/5444c5ecb904a4b21567b0ff)  
File: [`.travis.yml`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/.travis.yml)

[Snap CI](http://snap-ci.com/)  
[![Snap CI](https://snap-ci.com/larsbrinkhoff/lbForth/branch/master/build_image)]
(https://snap-ci.com/larsbrinkhoff/lbForth/branch/master)  
Install: `install-deps.sh install_yum`  
Build: `make all M32=$M32`  
Test: `make check`

[Travis CI](http://travis-ci.org/)  
[![Travis CI](https://travis-ci.org/larsbrinkhoff/lbForth.svg?branch=master)]
(https://travis-ci.org/larsbrinkhoff/lbForth)  
File: [`.travis.yml`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/.travis.yml)

[Visual Studio Online](http://visualstudio.com/)  
[![Visual Studio Online](https://larsbrinkhoff.visualstudio.com/DefaultCollection/_apis/public/build/definitions/953a34b9-5966-4923-a48a-c41874cfb5f5/1/badge)]
(https://larsbrinkhoff.visualstudio.com/DefaultCollection/lbForth/_build)  
Files: [`appharbor.sln`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/appharbor.sln),
[`packages.config`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/packages.config), and
[`build.vcxproj`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/build.vcxproj)

[Wercker](http://wercker.com/)  
[![Wercker](https://app.wercker.com/status/aedf010f682b5b530075e24d9446da26)]
(https://app.wercker.com/#applications/544dfb8aea87f6374f000ad9)  
File: [`wercker.yml`]
(https://github.com/larsbrinkhoff/lbForth/blob/master/wercker.yml)
