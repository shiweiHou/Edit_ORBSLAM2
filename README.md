#ORB_SLAM2

最初版本在这 https://github.com/raulmur/ORB_SLAM2

#修改：
1. 按照官方教程配置好其它环境后，直接在Ubuntu上运行提示“usleep（）”未定义，在“System.h"头文件加入 "#include <unistd.h>" 即可
2. 移除了pangolin
