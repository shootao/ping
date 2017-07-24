##1.介绍
    主要通过ICMP实现ping包demo（主要过程还得看ICMP协议）

##2.ping命令格式

        --ip baidu.com --timeout 2 --t 10 --interval 600
        
        --ip +  ip或域名             需要ping的目标
        
        --timeout + 时间（单位：S）   允许超时时间
        
        --t + 次数                   需要ping的次数
        
        --interval + 时间 （单位：S）    ping 时间间隔（第一次ping无间隔）
