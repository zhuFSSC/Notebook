# paython：多线程/Pool

***

form multiprocessing.dummy import Pool #导入

pool = Pool(4) #4的数值为计算机内核数，按实际情况调整

results = pool.map(爬取函数，网址列表) #实现爬虫多进程

pool.close()

pool.join()

***
