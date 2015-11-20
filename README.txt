* Prequisite
    1. python installed
    2. web.py installed, if it's not, it can be installed as below:
        sudo easy_install web.py

* Deploy and run
    1. run ./deploy.sh
    2. run ./start.sh to start the web service

* Unit Test
    1. run ./tests/testcase.py

* Usage:
    1. open a browser and input http://localhost:8080/fib to get usage help.
    2. on browser, input http://localhost:8080/fib/5 to get results of N=5.
    3. on browser, input http://localhost:8080/fib/-1 to get results of negative case.
    
* Config:
    1. In ./conf/user_conf.xml, you can set maxmium value of input boundary limit at 'value', default is 20 now.
