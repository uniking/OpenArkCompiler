# OpenArkCompiler

华为方舟编译器部分源码

https://code.opensource.huaweicloud.com/HarmonyOS/OpenArkCompiler/home

pacman -S ninja

pacman -S gn

编译好的二进制已上传到release


用maple加载libjava-core.mplt

用jbc2mpl生成原始的ir文件(.mpl)

mpl2mpl&mplme编译.mpl文件生成优化后的ir文件

mplcg编译优化后的文件生成汇编文件

