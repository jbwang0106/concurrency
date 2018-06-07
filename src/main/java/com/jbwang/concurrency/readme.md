### synchronized
1. java语言层面提供的一个关键字，可以使线程同步进行
2. synchronized是独占锁
3. synchronized是不可中断的
4. synchronized是非公平锁，可重入的
5. synchronized在并发小的时候使用
6. synchronized可以实现原子性，可见性和重排序

### 有序性 happen-before
1. 程序次序规则
2. 锁定规则
3. volatile读写变量规则
4. 传递规则
5. 线程启动规则
6. 线程中断规则
7. 线程终止规则
8. 对象终止规则

### 发布对象
1. 发布对象：使一个对象能够被当前范围之外的代码使用
2. 对象逃逸：一种错误的发布，当一个对象还没有构造完成时，就使其他线程可见。