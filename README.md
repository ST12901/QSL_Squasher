**Author:** Svetlin Tassev (Harvard-Smithsonian Center for Astrophysics, Braintree High School)

**Initial public release date:** Aug 28, 2016

QSL Squasher is an OpenCL code for calculating squashing factors of vector fields.

QSL Squasher is based on the following paper:

* QSL Squasher: A Fast Quasi-Separatrix Layer Map Calculator, S. Tassev and A. Savcheva, [arXiv:1609.00724](https://arxiv.org/abs/1609.00724)

If you use QSL Squasher or a derivative of it for scientific work, we 
kindly ask you to reference the paper above.

* QSL Squasher is free and open-source software, distributed under the GPLv3+ license.

* To build the code and learn how to run it, read the manual [here](https://bitbucket.org/tassev/qsl_squasher/downloads/QSLSquasher.pdf). Scripts that compile the code and its dependencies under CentOS and Debian are available from the author upon request.

* The example input files can be downloaded [here](https://bitbucket.org/tassev/qsl_squasher/downloads/cartesian_demo.tar.gz).

**Revision History:**

ver. 1.1 (June 27, 2017): Added support for global models (covering the Sun in longitude and latitude). Treat the poles as well as the periodicity in longitude correctly.