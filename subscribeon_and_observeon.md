# SubscribeOn and ObserveOn

我们学到了如何在一个调度器上运行一个任务。但是我们如何利用它来和Observables一起工作呢？RxJava提供了`subscribeOn()`方法来用于每个Observable对象。`subscribeOn()`方法用`Scheduler`来作为参数并在这个Scheduler上执行Observable调用。
