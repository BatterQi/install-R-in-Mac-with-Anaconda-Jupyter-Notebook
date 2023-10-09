# install-R-in-Mac-with-Anaconda-Jupyter-Notebook
Recently , The Mac version Anaconda doesn't support the Kernel of R, means we can not Use R in Jupyter Notebook easily. I searched google for more informations but no support. Thought three nights ,finally I fixed this problem, write here in order to help others want to coding with R in new Mac OS
Recently , The Mac version Anaconda  doesn't support the Kernel of R, means we can not Use R in Jupyter Notebook easily.

I searched google for more informations but no support. Thought three nights ,finally I fixed this problem, write here in order to help others want to coding with R in new Mac OS.

If you like please give me a fork, you also could share this help document to other website , but you need add this link, Thanks




Preparation : 

1 download Anaconda. [how to download Anaconda](url: https://subscription.packtpub.com/book/data/9781789530797/1/ch01lvl1sec10/installing-anaconda#:~:text=One%20can%20download%20Anaconda%20for%20free%20from%20the%20Continuum%20Analytics%20website.) 

2 download R language. #https://cran.r-project.org[R](https://cran.r-project.org).

type R in Terminal , if this info is appear. It is work.    


![Image](https://github.com/users/BatterQi/projects/1/assets/144684892/3e9056a0-1850-4dd9-bfd1-fd485ba39e09)

3 Enter the folder of R's location.


![Image](https://github.com/users/BatterQi/projects/1/assets/144684892/4dbaf8f8-617a-4aa0-85f1-a43ed09b3c0c)

 3.1 use command  R.home(),   check your R's location.

3.2 use Sudo open the R

sudo /Library/Frameworks/R.framework/Resources/bin/R


4 the important  Steps:


![Image](https://github.com/users/BatterQi/projects/1/assets/144684892/eb7663ed-7c27-4055-a555-81680d671cab)


4.1 type  install.packages('IRkernel', dependencies=TRUE)      ,in R's console

4.2 select a location nearly to you and the processing  will show like this:



![Image](https://github.com/users/BatterQi/projects/1/assets/144684892/7150feb8-24ad-400b-a941-53e258f81453)

4.3 type:

  IRkernel::installspec()
  q()


![Image](https://github.com/users/BatterQi/projects/1/assets/144684892/95455f73-4075-414d-b605-a6b34f54d35c)



4.4 Congratulations , now check your Jupyter Notebook.




![Image](https://github.com/users/BatterQi/projects/1/assets/144684892/6ee143e0-9858-489b-ad4f-2a09616b6d21)
