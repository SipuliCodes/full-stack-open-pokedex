In c++ the liting tool could be clang-tidy. It will fix typical programming errors and keep the style consistent in the code.

Testing in c++ could be done with gtest framework. Tests will help ensure that the code is working correctly and doing what it should do. And they let you make changes to your code without worrying they will break your old code, because you can just run the tests.

Building could be done with Cmake. Cmake will do all the steps that is needed to transform your code files to a executable program.

Another cloud-based CI service is Travis CI. And gitlab CI is another self-hosted CI. Both of these could be used for c++.

The question of which would be better would depend on many things. First of the most important is how much you need to control things. If you need to control the CI process then self hosted would be better. But if you just need simple and quick, you would choose cloud based. 
If you know you need a scalable solutions you should choose a cloud-based CI. If security is really important you should choose self hosted and hire the best security guys. Otherwise the security of cloud-based should be enough.