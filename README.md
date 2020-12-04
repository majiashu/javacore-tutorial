---
# 3. Java并发编程
**常见的Java线程的四种创建方法：**
- 继承Thread类
- 实现Runnable接口
- 通过ExecutorService和Callable<Class>实现有返回值的线程
- 基于线程池

**五种常见的线程池**

|名称|说明|
|:---:|:---:|
|newCachedThreadPool| 可缓存的线程池|
|newFixedThreadPool|固定大小的线程池|
|newScheduledThreadPool|可做任务调度的线程池|
|newSingleThreadPool|单个线程的线程池|
|newWorkStealingPool|足够大小的线程池|
  
