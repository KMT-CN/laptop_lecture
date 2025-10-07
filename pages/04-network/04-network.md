---
marp: true
theme: default
paginate: true
transition: fade
style: |
  section {
    background-color: #ffffff;
    padding: 20px;
  }
  img {
    display: block;
    margin: auto;
    max-width: 100%;
    max-height: 450px;
  }
  .small-text {
    font-size: 0.8em;
  }
  .half-size {
    transform: scale(0.5);
  }
---

# 第四章：网络与远程服务

## 校园网络服务概述

![网络服务概览](/assets/images/network-services.jpg){.half-size}

---

## 4.1 校园网基础设施

### 网络架构
- 有线网络
- 无线网络
- 统一认证
- 带宽分配

![网络架构图](/assets/images/network-architecture.jpg){.half-size}

---

### 网络认证方式

类型|使用场景|认证方式
---|---|---
有线网络|宿舍/教室|Web认证
无线网络|公共区域|Web认证
VPN服务|校外访问|L2TP/IPSec

---

## 4.2 校园VPN服务

### VPN配置教程

#### Windows系统配置
首次使用SSL VPN，请先安装插件。具体方法见：SSL VPN插件安装步骤

方法一 网页端（推荐使用）：输入网址 https://vpnmotion.buct.edu.cn，用户可自主选择一种方法登录。
登录方法一：企业微信扫码登录；   
登录方法二：统一身份认证账号密码+手机短信验证进行登录。   

登录后如下图，点击“启动连接”。在电脑的任务栏看到大红A的图标，表示VPN已经连接成功。
![](/assets/images/vpn-windows1.jpg)

方法二 客户端
第一步 配置已安装的VPN客户端（如下图）

第二步 双击保存的站点进行vpn连接，在任务栏能看到大红A，表示连接VPN成功。
![](/assets/images/vpn-windows2.jpg)

---

#### 移动设备配置
1. 安装VPN客户端iSecSP
2. 导入配置文件
3. 填写账号信息
4. 测试连接

![](/assets/images/vpn-mobile.jpg)

---

## 4.3 图书馆资源访问
<!-- 待更改 -->

### 数据库使用指南
- CNKI配置说明
- Web of Science访问
- IEEE文献下载
- ScienceDirect设置

![](/assets/images/library-resources.jpg)

---

### 文献下载加速

方法|优点|注意事项
---|---|---
校园VPN|官方支持|需要申请
镜像站点|速度快|资源可能滞后
代理服务|便捷使用|需要配置

![](/assets/images/download-acceleration.jpg)

---

## 4.4 远程控制解决方案

### Todesk
- 远程桌面控制
- 文件传输
- 远程开机
- 移动端支持

![](/assets/images/sunlogin-features.jpg)

---

### RustDesk开源方案
- 免费开源
- 自建服务器
- 端到端加密
- 跨平台支持

![](/assets/images/rustdesk-interface.png)

---

### Windows远程桌面
- 系统集成
- 高性能显示
- 本地资源映射
- 多显示器支持

![](/assets/images/rdp-settings.png)

---

## 4.6 代码托管与版本控制

### GitHub入门
- 仓库创建
- 分支管理
- Pull Request
- Issue跟踪

![](/assets/images/github-basics.jpg)

---

### Git基础操作

```bash
git init            # 初始化仓库
git add .           # 暂存更改
git commit -m "msg" # 提交更改
git push           # 推送到远程
```

![](/assets/images/git-workflow.jpg)

---

## 4.7 家用网络优化

### 路由器基础设置
- WiFi名称配置
- 密码设置
- 频段选择
- 信道优化

![](/assets/images/router-settings.jpg)

---

### 高级功能配置
- QoS设置
- 访客网络
- 家长控制
- 防火墙规则

![](/assets/images/advanced-settings.jpg)

---

### IPv6配置指南

<table>
  <thead>
    <tr>
      <th>步骤</th>
      <th>操作</th>
      <th>说明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>检查支持</td>
      <td>运营商咨询</td>
      <td>确认是否支持</td>
    </tr>
    <tr>
      <td>系统设置</td>
      <td>开启IPv6</td>
      <td>系统网络设置</td>
    </tr>
    <tr>
      <td>路由器配置</td>
      <td>IPv6转发</td>
      <td>路由器后台设置</td>
    </tr>
    <tr>
      <td>测试连接</td>
      <td>测试网站</td>
      <td>验证IPv6连接</td>
    </tr>
  </tbody>
</table>

---

## 4.8 局域网应用

### Windows文件共享
- 共享文件夹创建
- 权限设置
- 网络发现
- 访问控制

![](/assets/images/file-sharing.jpg)

---

### 网络打印机
- 打印机共享
- 驱动安装
- 权限管理
- 打印队列

![](/assets/images/printer-sharing.jpg)

---

### NAS存储方案
- 设备选择
- 存储配置
- 备份策略
- 远程访问

![](/assets/images/nas-system.jpg)

---

## 4.9 网络安全防护

### 基础防护措施
- 修改默认密码
- 更新固件
- 开启防火墙
- 监控连接设备

![](/assets/images/security-settings.jpg)

---

### 高级安全功能
- VPN服务器
- 入侵检测
- 访问控制
- 日志审计

![](/assets/images/advanced-security.jpg)