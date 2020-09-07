|      | 故障描述                                                     | 处理方式                                                 |
| ---- | ------------------------------------------------------------ | -------------------------------------------------------- |
| 1    | 没有找到有效的物理网卡或您的网络电缆没有插好                 | 线路问题，检查线路连接                                   |
| 2    | 找不到内网认证负无穷                                         | 线路问题，一般为自加设备级联线问题                       |
| 3    | 网卡获取信息失败                                             | 认证客户端或操作系统问题，安装最新版客户端或重装网卡驱动 |
| 4    | 认证成功后，短时间（约5分钟）内提示“外网失效，无法维持连接，内网唯一可用 | 重新安装客户端                                           |
| 5    | 频繁提示“内网强制下线”，其他用户无问题                       | 重启接入交换机                                           |
| 6    | 用户超过使用限制（流量用完）                                 | 充值10分钟后再试                                         |
| 7    | 用户超过适用范围（在线列表问题）                             | 等10分钟重新认证                                         |
| 8    | 内网认证成功，外网无法认证                                   | 一般是网关设置错误或认证服务器IP设置错误                 |

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">

<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
<script>
    const gitalk = new Gitalk({
        clientID: "f997f0370566fec3278e",
        clientSecret: "9e3d0c4c8706ad459f8b15a41e489c4f76525b51",
        repo: "CampusNetworkForSTDU",
        owner: "Dreammer12138",
        admin: ['Dreammer12138'],
        id: location.pathname
    });
    gitalk.render('gitalk-container');
</script>

