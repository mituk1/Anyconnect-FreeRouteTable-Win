# Anyconnect-FreeRouteTable

解除 Anyconnect 对路由表操作的劫持。

## 使用

+ 安装 anyconnect-win-4.6.03049
+ 强制终止 VPN Agent Service 后台进程
+ 进入 <code>C:\Program Files (x86)\Cisco\Cisco AnyConnect Secure Mobility Client</code> 目录，替换 <code>vpnagentutilities.dll</code> 文件
+ 重启计算机，并连接 Anyconnect
+ 根据你的上网需求修改 <code>routeAdd.bat</code> ，以管理员身份执行
