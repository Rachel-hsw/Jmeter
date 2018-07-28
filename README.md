# Jmeter
1、将jar放到Jmeter安装目录下的lib文件夹下

2、Jmeter新建测试计划，添加线程组，新建BeanShell Sampler
使用的时候导入
import com.hsw.getSha1;
String sign= getSha1.encode("拼接好的要加密的字符串");
