# Baymax-Patch-toOls
1. 一款劫持补丁制作工具，偏移补丁支持特征码搜索替换内存数据；中断补丁支持模拟调试器的异常中断功能，通过设置并触发中断后修改寄存器、内存等数据，以实现修改程序执行流程等目的。

工具说明：
1. Baymax Patch Tools 针对目标进程释放劫持DLL来加载功能模块PYG.DLL，实现对目标进程的动态补丁。
2. Baymax 不仅支持动态修改目标模块的指令和数据，还模拟了 OD 的下断功能，可以对目标模块下断后修改对应的寄存器、标志寄存器、寄存器指向内存的内存数据，在不修改目标文件的情况下实现对其破解。

功能介绍：
1. 支持劫持破解，不修改文件自身
2. 支持对动态基址(ASLR)的进程补丁
3. 支持补丁目标进程的多个DLL模块
4. 支持同一补丁补丁不同的EXE
5. 支持对进程指定地址的内存数据补丁
6. 支持对进程使用特征码匹配进行补丁
7. 支持对加壳程序设置API HOOK解码后再补丁数据
8. 支持对进程设置硬件断点中断后再进行补丁数据
9. 支持对进程设置异常断点中断后修改寄存器或寄存器指向的内存
10. 支持对进程设置条件断点根据中断次数、寄存器或内存数值来判断是否执行Patch
11. 支持对同一地址设置不同条件断点对符合条件的中断进行对应的Patch
12. 支持从指令中提取全局变量存储及修改
13. 支持进程执行中存储数据和使用存储的数据
14. 支持中断后对存储标号指向的内存进行补丁
15. 支持中断后对数据做基本运算操作
16. 支持从ini文件中读取补丁数据
17. 支持创建内存注册机
18. 支持创建调试补丁，可自行排查补丁问题

解压密码(Unpack password)：www.chinapyg.com

## Screenshots

<img width="531" height="508" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/11.png"/>
<img width="537" height="673" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/12.png"/>
<img width="537" height="583" src="https://github.com/sicaril/Baymax-Patch-toOls/blob/main/pic/13.png"/>

