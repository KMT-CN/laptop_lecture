---
layout: section
background: https://gradienta.io/web/assets/gradients/43.jpg
---

<div class="flex flex-col h-full">
  <div class="text-center my-auto p-8 bg-white bg-opacity-90 rounded-2xl shadow-xl mx-auto max-w-3xl">
    <div class="text-4xl font-bold mb-4 bg-clip-text text-transparent bg-gradient-to-r from-cyan-600 to-blue-600">
      第四章：网络与远程服务
    </div>
    <div class="text-2xl text-gray-600">
      校园网络服务概述
    </div>
  </div>
</div>

---
layout: image
image: /assets/images/network-services.jpg
---

<div class="absolute inset-0 bg-gradient-to-r from-black/50 to-transparent">
  <div class="p-12 text-white">
    <h1 class="text-4xl font-bold mb-4">网络服务概览</h1>
    <p class="text-xl opacity-90">全方位了解校园网络服务体系</p>
  </div>
</div>

---
layout: two-cols
---

<div class="p-8">
<h2 class="text-2xl font-bold mb-6 text-blue-700">4.1 校园网基础设施</h2>

<div class="bg-gradient-to-br from-blue-50 to-cyan-50 rounded-xl shadow-lg p-6">
  <h3 class="text-xl font-semibold text-blue-800 mb-4">网络架构</h3>

  <div class="grid grid-cols-1 gap-4">
    <div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
      <div class="w-10 h-10 rounded-full bg-blue-100 flex items-center justify-center text-blue-600 mr-4">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
        </svg>
      </div>
      <span class="text-gray-700">有线网络</span>
    </div>

  <div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
    <div class="w-10 h-10 rounded-full bg-cyan-100 flex items-center justify-center text-cyan-600 mr-4">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.111 16.404a5.5 5.5 0 017.778 0M12 20h.01m-7.08-7.071c3.904-3.905 10.236-3.905 14.14 0M1.394 9.393c5.857-5.857 15.355-5.857 21.213 0" />
      </svg>
    </div>
    <span class="text-gray-700">无线网络</span>
  </div>

  <div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
    <div class="w-10 h-10 rounded-full bg-indigo-100 flex items-center justify-center text-indigo-600 mr-4">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 7a2 2 0 012 2m4 0a6 6 0 01-7.743 5.743L11 17H9v2H7v2H4a1 1 0 01-1-1v-2.586a1 1 0 01.293-.707l5.964-5.964A6 6 0 1121 9z" />
      </svg>
    </div>
    <span class="text-gray-700">统一认证</span>
  </div>

  <div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
    <div class="w-10 h-10 rounded-full bg-blue-100 flex items-center justify-center text-blue-600 mr-4">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
      </svg>
    </div>
    <span class="text-gray-700">带宽分配</span>
  </div>
  
  </div>
</div>
</div>

::right::

<div class="p-8 flex items-center justify-center">
  <img src="/assets/images/network-architecture.jpg" class="rounded-xl shadow-lg max-w-full" />
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-blue-700">网络认证方式</h2>
  
  <div class="bg-white rounded-xl shadow-lg overflow-hidden">
    <table class="w-full">
      <thead class="bg-gradient-to-r from-blue-50 to-cyan-50">
        <tr>
          <th class="px-6 py-4 text-left text-gray-700 font-semibold">类型</th>
      <th>使用场景</th>
      <th>认证方式</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>有线网络</td>
      <td>宿舍/教室</td>
      <td>Web认证</td>
    </tr>
    <tr>
      <td>无线网络</td>
      <td>公共区域</td>
      <td>Web认证</td>
    </tr>
    <tr>
      <td>VPN服务</td>
      <td>校外访问</td>
      <td>L2TP/IPSec</td>
    </tr>
  </tbody>
</table>
  </div>
</div>
---

## 4.2 校园VPN服务

### VPN配置教程

#### Windows系统配置
首次使用SSL VPN，请先安装插件。具体方法见：SSL VPN插件安装步骤

###### 方法一 网页端（推荐使用）：输入网址 https://vpnmotion.buct.edu.cn，用户可自主选择一种方法登录。
###### 登录方法一：企业微信扫码登录；   
###### 登录方法二：统一身份认证账号密码+手机短信验证进行登录。   

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

![](/assets/images/wechat_2025-10-08_162022_817.png)

---

### 文献下载加速

<table>
  <thead>
    <tr>
      <th>方法</th>
      <th>优点</th>
      <th>注意事项</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>校园VPN</td>
      <td>官方支持</td>
      <td>需要申请</td>
    </tr>
    <tr>
      <td>镜像站点</td>
      <td>速度快</td>
      <td>资源可能滞后</td>
    </tr>
    <tr>
      <td>代理服务</td>
      <td>便捷使用</td>
      <td>需要配置</td>
    </tr>
  </tbody>
</table>

![](/assets/images/download-acceleration.png)

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

![](/assets/images/github-basics.png)

---

### Git基础操作

```bash
git init            # 初始化仓库
git add .           # 暂存更改
git commit -m "msg" # 提交更改
git push           # 推送到远程
```

![](/assets/images/git-workflow.webp)

---

## 4.7 家用网络优化

### 路由器基础设置
- WiFi名称配置
- 密码设置
- 频段选择
- 信道优化

![](/assets/images/router-settings.png)

---

### 高级功能配置
- QoS设置
- 访客网络
- 家长控制
- 防火墙规则

![](/assets/images/advanced-settings.png)

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

![](/assets/images/u=3729409556,267898855&fm=30&app=106&f=JPEG.jpg)

---

### 网络打印机
- 打印机共享
- 驱动安装
- 权限管理
- 打印队列

![](/assets/images/u=765800986,2897228034&fm=3074&app=3074&f=PNG.png)

---

### NAS存储方案
- 设备选择
- 存储配置
- 备份策略
- 远程访问

![](/assets/images/u=3473075622,3790293538&fm=253&fmt=auto&app=138&f=JPEG.webp)

---

## 4.9 网络安全防护

### 基础防护措施
- 修改默认密码
- 更新固件
- 开启防火墙
- 监控连接设备

![](/assets/images/part-00282-3434.jpg)

---

### 高级安全功能
- VPN服务器
- 入侵检测
- 访问控制
- 日志审计

![](/assets/images/v2-16bbc19ca6b6885d086f60464cc687e3_1440w.png)