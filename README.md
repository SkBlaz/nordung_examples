# Set of example job inputs for the nordung cluster..

'''
&
(executable="pozeni.sh")
(jobname="g222")
(stdout = "mojLog.log")
(join = yes)
(walltime = "3 days")
(gmlog = "log")
(memory = "4500")
(count="1")
(countpernode="1")
(inputfiles = ("data_train.arff" "path to train")
              ("data_test.arff" "path to test")
              ("clus.jar" "local .jar path")
(outputfiles = ("results.tar.gz" ""))
(queue != "gridgpu")
'''

