# storm-spr-local
storm整合springboot，local模式。

local就是单进程模式（运行在单一的JVM），local模式storm整合Springboot，这与我们平常的Springboot开发方式没有多大区别。storm-local又被叫做测试模式。

storm-local整合Springboot，程序启动时，组件的初始化顺序是这样的，先启动SpringBoot，然后再在SpringBoot中启动Storm。因此说，与我们平常的Springboot开发方式没有多大区别。

执行的入口是：com.banling.stormspr.Start
