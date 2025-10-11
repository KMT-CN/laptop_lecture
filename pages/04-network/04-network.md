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
      <td>iSecSP</td>
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
layout: two-cols
---

<div class="p-8">
<h2 class="text-2xl font-bold mb-6 text-amber-700">4.3 图书馆资源访问</h2>

<div class="bg-gradient-to-br from-amber-50 to-orange-50 rounded-xl shadow-lg p-6">
<div class="flex items-center mb-6">
<div class="w-12 h-12 rounded-xl bg-gradient-to-br from-amber-500 to-orange-500 flex items-center justify-center text-white">
<svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
</svg>
</div>
<h3 class="text-xl font-semibold text-amber-800 ml-4">数据库使用指南</h3>
</div>

<div class="space-y-4">
<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-amber-400 mr-3"></div>
<span class="text-gray-700">CNKI配置说明</span>
</div>

<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-orange-400 mr-3"></div>
<span class="text-gray-700">Web of Science访问</span>
</div>

<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-yellow-400 mr-3"></div>
<span class="text-gray-700">IEEE文献下载</span>
</div>

<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-red-400 mr-3"></div>
<span class="text-gray-700">ScienceDirect设置</span>
</div>
</div>
</div>
</div>

::right::

<div class="p-8 flex items-center justify-center">
  <img src="/assets/images/wechat_2025-10-08_162022_817.png" class="rounded-xl shadow-lg max-w-full" />
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-amber-700">文献下载加速方案</h2>
  <div class="bg-white rounded-xl shadow-lg overflow-hidden">
    <table class="w-full">
      <thead class="bg-gradient-to-r from-amber-50 to-orange-50">
        <tr>
          <th class="px-6 py-4 text-left text-gray-700 font-semibold">方法</th>
          <th class="px-6 py-4 text-left text-gray-700 font-semibold">优点</th>
          <th class="px-6 py-4 text-left text-gray-700 font-semibold">注意事项</th>
        </tr>
      </thead>
      <tbody class="divide-y divide-gray-100">
        <tr>
          <td class="px-6 py-4 text-gray-800 font-medium">校园VPN</td>
          <td class="px-6 py-4 text-gray-600">官方权威支持</td>
          <td class="px-6 py-4 text-gray-600">需要提前申请</td>
        </tr>
        <tr>
          <td class="px-6 py-4 text-gray-800 font-medium">镜像站点</td>
          <td class="px-6 py-4 text-gray-600">访问速度快</td>
          <td class="px-6 py-4 text-gray-600">资源可能滞后</td>
        </tr>
        <tr>
          <td class="px-6 py-4 text-gray-800 font-medium">代理服务</td>
          <td class="px-6 py-4 text-gray-600">便捷易用</td>
          <td class="px-6 py-4 text-gray-600">需要配置设置</td>
        </tr>
      </tbody>
    </table>
  </div>
  
  <div class="mt-8 flex justify-center">
    <img src="/assets/images/download-acceleration.png" class="rounded-xl shadow-lg max-w-2xl" alt="下载加速示意图" />
  </div>
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-purple-700">4.4 远程控制解决方案</h2>
  
  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    <!-- ToDesk -->
    <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-purple-500 to-pink-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
          </svg>
        </div>
        <h3 class="text-lg font-semibold text-purple-800 ml-4">ToDesk</h3>
      </div>
      <div class="space-y-3">
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-purple-400 mr-3"></div>
          <span class="text-gray-700">远程桌面控制</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-pink-400 mr-3"></div>
          <span class="text-gray-700">文件传输功能</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-rose-400 mr-3"></div>
          <span class="text-gray-700">远程开机支持</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-fuchsia-400 mr-3"></div>
          <span class="text-gray-700">移动端支持</span>
        </div>
      </div>
    </div>
    <!-- RustDesk -->
    <div class="bg-gradient-to-br from-orange-50 to-red-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-orange-500 to-red-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
          </svg>
        </div>
        <h3 class="text-lg font-semibold text-orange-800 ml-4">RustDesk</h3>
      </div>
      <div class="space-y-3">
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-orange-400 mr-3"></div>
          <span class="text-gray-700">免费开源方案</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-red-400 mr-3"></div>
          <span class="text-gray-700">自建服务器</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-yellow-400 mr-3"></div>
          <span class="text-gray-700">端到端加密</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-amber-400 mr-3"></div>
          <span class="text-gray-700">跨平台支持</span>
        </div>
      </div>
    </div>
    <!-- Windows远程桌面 -->
    <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-blue-500 to-indigo-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10" />
          </svg>
        </div>
        <h3 class="text-lg font-semibold text-blue-800 ml-4">Windows RDP</h3>
      </div>
      <div class="space-y-3">
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-blue-400 mr-3"></div>
          <span class="text-gray-700">系统原生集成</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-indigo-400 mr-3"></div>
          <span class="text-gray-700">高性能显示</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-purple-400 mr-3"></div>
          <span class="text-gray-700">本地资源映射</span>
        </div>
        <div class="flex items-center bg-white/60 rounded-lg p-3 text-sm">
          <div class="w-2 h-2 rounded-full bg-violet-400 mr-3"></div>
          <span class="text-gray-700">多显示器支持</span>
        </div>
      </div>
    </div>
  </div>
  
  <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6">
    <div class="text-center">
      <img src="/assets/images/sunlogin-features.jpg" class="rounded-xl shadow-lg w-full mb-4" alt="ToDesk功能" />
      <p class="text-sm text-gray-600">ToDesk界面展示</p>
    </div>
    <div class="text-center">
      <img src="/assets/images/rustdesk-interface.png" class="rounded-xl shadow-lg w-full mb-4" alt="RustDesk界面" />
      <p class="text-sm text-gray-600">RustDesk开源方案</p>
    </div>
    <div class="text-center">
      <img src="/assets/images/rdp-settings.png" class="rounded-xl shadow-lg w-full mb-4" alt="RDP设置" />
      <p class="text-sm text-gray-600">Windows远程桌面设置</p>
    </div>
  </div>
</div>

---
layout: two-cols
---

<div class="p-8">
<h2 class="text-2xl font-bold mb-6 text-green-700">4.6 代码托管与版本控制</h2>

<div class="bg-gradient-to-br from-green-50 to-emerald-50 rounded-xl shadow-lg p-6">
<div class="flex items-center mb-6">
<div class="w-12 h-12 rounded-xl bg-gradient-to-br from-green-500 to-emerald-500 flex items-center justify-center text-white">
<svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
</svg>
</div>
<h3 class="text-xl font-semibold text-green-800 ml-4">GitHub入门</h3>
</div>

<div class="space-y-4">
<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-green-400 mr-3"></div>
<span class="text-gray-700">仓库创建管理</span>
</div>

<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-emerald-400 mr-3"></div>
<span class="text-gray-700">分支管理策略</span>
</div>

<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-teal-400 mr-3"></div>
<span class="text-gray-700">Pull Request流程</span>
</div>

<div class="flex items-center bg-white/60 rounded-lg p-4 shadow-sm">
<div class="w-2 h-2 rounded-full bg-cyan-400 mr-3"></div>
<span class="text-gray-700">Issue跟踪系统</span>
</div>
</div>
</div>
</div>

::right::

<div class="p-8 flex items-center justify-center">
  <img src="/assets/images/github-basics.png" class="rounded-xl shadow-lg max-w-full" />
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-green-700">Git基础操作命令</h2>
  
  <div class="bg-gradient-to-br from-gray-50 to-slate-50 rounded-xl shadow-lg p-6 mb-8">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="space-y-4">
        <div class="bg-white rounded-lg p-4 shadow-sm">
          <h4 class="font-semibold text-gray-800 mb-2">初始化与配置</h4>
          <div class="bg-gray-100 rounded p-3 font-mono text-sm">
            <p class="text-green-600"># 初始化仓库</p>
            <p>git init</p>
            <p class="text-green-600 mt-2"># 配置用户信息</p>
            <p>git config --global user.name "name"</p>
            <p>git config --global user.email "email"</p>
          </div>
        </div>
        <div class="bg-white rounded-lg p-4 shadow-sm">
          <h4 class="font-semibold text-gray-800 mb-2">基本操作</h4>
          <div class="bg-gray-100 rounded p-3 font-mono text-sm">
            <p class="text-green-600"># 暂存更改</p>
            <p>git add .</p>
            <p class="text-green-600 mt-2"># 提交更改</p>
            <p>git commit -m "msg"</p>
            <p class="text-green-600 mt-2"># 查看状态</p>
            <p>git status</p>
          </div>
        </div>
      </div>
      <div class="space-y-4">
        <div class="bg-white rounded-lg p-4 shadow-sm">
          <h4 class="font-semibold text-gray-800 mb-2">远程操作</h4>
          <div class="bg-gray-100 rounded p-3 font-mono text-sm">
            <p class="text-green-600"># 添加远程仓库</p>
            <p>git remote add origin &lt;url&gt;</p>
            <p class="text-green-600 mt-2"># 推送到远程</p>
            <p>git push origin main</p>
            <p class="text-green-600 mt-2"># 拉取更新</p>
            <p>git pull origin main</p>
          </div>
        </div>
        <div class="bg-white rounded-lg p-4 shadow-sm">
          <h4 class="font-semibold text-gray-800 mb-2">分支管理</h4>
          <div class="bg-gray-100 rounded p-3 font-mono text-sm">
            <p class="text-green-600"># 创建分支</p>
            <p>git branch feature</p>
            <p class="text-green-600 mt-2"># 切换分支</p>
            <p>git checkout feature</p>
            <p class="text-green-600 mt-2"># 合并分支</p>
            <p>git merge feature</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <div class="text-center">
    <img src="/assets/images/git-workflow.webp" class="rounded-xl shadow-lg mx-auto max-w-4xl" alt="Git工作流程图" />
    <p class="text-sm text-gray-600 mt-4">Git版本控制工作流程示意图</p>
  </div>
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-indigo-700">4.7 家用网络优化</h2>
  
  <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
    <!-- 基础设置 -->
    <div class="bg-gradient-to-br from-indigo-50 to-blue-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-indigo-500 to-blue-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.111 16.404a5.5 5.5 0 017.778 0M12 20h.01m-7.08-7.071c3.904-3.905 10.236-3.905 14.141 0M1.394 9.393c5.857-5.857 15.355-5.857 21.213 0" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-indigo-800 ml-4">路由器基础设置</h3>
      </div>
      <div class="space-y-4">
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2">WiFi网络配置</h4>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• WiFi名称（SSID）设置</li>
            <li>• 安全密码配置</li>
            <li>• 网络加密方式选择</li>
          </ul>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2">频段与信道优化</h4>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• 2.4GHz vs 5GHz选择</li>
            <li>• 信道自动选择</li>
            <li>• 信号强度调整</li>
          </ul>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/router-settings.png" class="rounded-lg shadow-md w-full" alt="路由器基础设置" />
      </div>
    </div>
    <!-- 高级功能 -->
    <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-purple-500 to-pink-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z" />
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-purple-800 ml-4">高级功能配置</h3>
      </div>
      <div class="space-y-4">
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2">流量管理</h4>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• QoS服务质量设置</li>
            <li>• 带宽限制配置</li>
            <li>• 设备优先级管理</li>
          </ul>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2">安全与控制</h4>
          <ul class="text-sm text-gray-600 space-y-1">
            <li>• 访客网络设置</li>
            <li>• 家长控制功能</li>
            <li>• 防火墙规则配置</li>
          </ul>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/advanced-settings.png" class="rounded-lg shadow-md w-full" alt="高级功能配置" />
      </div>
    </div>
  </div>
  <!-- IPv6配置指南 -->
  <div class="mt-8 bg-white rounded-xl shadow-lg overflow-hidden">
    <div class="bg-gradient-to-r from-indigo-50 to-purple-50 px-6 py-4">
      <h3 class="text-lg font-semibold text-gray-800">IPv6配置指南</h3>
    </div>
    <div class="p-6">
      <div class="overflow-x-auto">
        <table class="w-full">
          <thead class="bg-gray-50">
            <tr>
              <th class="px-6 py-3 text-left text-gray-700 font-semibold">步骤</th>
              <th class="px-6 py-3 text-left text-gray-700 font-semibold">操作</th>
              <th class="px-6 py-3 text-left text-gray-700 font-semibold">说明</th>
            </tr>
          </thead>
          <tbody class="divide-y divide-gray-100">
            <tr>
              <td class="px-6 py-4 text-gray-800 font-medium">检查支持</td>
              <td class="px-6 py-4 text-gray-600">运营商咨询</td>
              <td class="px-6 py-4 text-gray-600">确认是否支持（我校校园网已支持IPv6）</td>
            </tr>
            <tr>
              <td class="px-6 py-4 text-gray-800 font-medium">系统设置</td>
              <td class="px-6 py-4 text-gray-600">开启IPv6</td>
              <td class="px-6 py-4 text-gray-600">在系统网络设置中启用</td>
            </tr>
            <tr>
              <td class="px-6 py-4 text-gray-800 font-medium">路由器配置</td>
              <td class="px-6 py-4 text-gray-600">IPv6转发</td>
              <td class="px-6 py-4 text-gray-600">在路由器后台设置中配置</td>
            </tr>
            <tr>
              <td class="px-6 py-4 text-gray-800 font-medium">测试连接</td>
              <td class="px-6 py-4 text-gray-600">测试网站</td>
              <td class="px-6 py-4 text-gray-600">验证IPv6连接是否正常</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-teal-700">4.8 局域网应用</h2>
  
  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    <!-- Windows文件共享 -->
    <div class="bg-gradient-to-br from-teal-50 to-cyan-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-teal-500 to-cyan-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
          </svg>
        </div>
        <h3 class="text-lg font-semibold text-teal-800 ml-4">文件共享</h3>
      </div>
      <div class="space-y-3">
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">共享文件夹创建</div>
          <div class="text-gray-600">设置共享目录权限</div>
        </div>
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">权限设置</div>
          <div class="text-gray-600">用户访问控制</div>
        </div>
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">网络发现</div>
          <div class="text-gray-600">自动发现设备</div>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/u=3729409556,267898855&fm=30&app=106&f=JPEG.jpg" class="rounded-lg shadow-md w-full" alt="文件共享" />
      </div>
    </div>
    <!-- 网络打印机 -->
    <div class="bg-gradient-to-br from-blue-50 to-indigo-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-blue-500 to-indigo-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 17h2a2 2 0 002-2v-4a2 2 0 00-2-2H5a2 2 0 00-2 2v4a2 2 0 002 2h2m2 4h6a2 2 0 002-2v-4a2 2 0 00-2-2H9a2 2 0 00-2 2v4a2 2 0 002 2zm8-12V5a2 2 0 00-2-2H9a2 2 0 00-2 2v4h10z" />
          </svg>
        </div>
        <h3 class="text-lg font-semibold text-blue-800 ml-4">网络打印</h3>
      </div>
      <div class="space-y-3">
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">打印机共享</div>
          <div class="text-gray-600">设备共享配置</div>
        </div>
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">驱动安装</div>
          <div class="text-gray-600">网络驱动配置</div>
        </div>
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">打印队列</div>
          <div class="text-gray-600">任务管理监控</div>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/u=765800986,2897228034&fm=3074&app=3074&f=PNG.png" class="rounded-lg shadow-md w-full" alt="网络打印机" />
      </div>
    </div>
    <!-- NAS存储 -->
    <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-purple-500 to-pink-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2m-2-4h.01M17 16h.01" />
          </svg>
        </div>
        <h3 class="text-lg font-semibold text-purple-800 ml-4">NAS存储</h3>
      </div>
      <div class="space-y-3">
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">设备选择</div>
          <div class="text-gray-600">硬件配置方案</div>
        </div>
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">存储配置</div>
          <div class="text-gray-600">RAID阵列设置</div>
        </div>
        <div class="bg-white/60 rounded-lg p-3 text-sm">
          <div class="font-medium text-gray-800 mb-1">远程访问</div>
          <div class="text-gray-600">外网访问配置</div>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/u=3473075622,3790293538&fm=253&fmt=auto&app=138&f=JPEG.webp" class="rounded-lg shadow-md w-full" alt="NAS存储" />
      </div>
    </div>
  </div>
</div>

---
layout: default
---

<div class="p-8">
  <h2 class="text-2xl font-bold mb-6 text-red-700">4.9 网络安全防护</h2>
  
  <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
    <!-- 基础防护 -->
    <div class="bg-gradient-to-br from-red-50 to-orange-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-red-500 to-orange-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-red-800 ml-4">基础防护措施</h3>
      </div>
      <div class="space-y-4">
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-red-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-red-500"></div>
            </div>
            密码安全
          </h4>
          <p class="text-sm text-gray-600">修改默认密码，使用强密码策略</p>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-orange-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-orange-500"></div>
            </div>
            固件更新
          </h4>
          <p class="text-sm text-gray-600">定期更新设备固件，修复安全漏洞</p>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-yellow-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-yellow-500"></div>
            </div>
            防火墙启用
          </h4>
          <p class="text-sm text-gray-600">开启防火墙，阻止恶意访问</p>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-amber-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-amber-500"></div>
            </div>
            设备监控
          </h4>
          <p class="text-sm text-gray-600">监控连接设备，发现异常连接</p>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/part-00282-3434.jpg" class="rounded-lg shadow-md w-full" alt="基础防护" />
      </div>
    </div>
    <!-- 高级安全 -->
    <div class="bg-gradient-to-br from-slate-50 to-gray-50 rounded-xl shadow-lg p-6">
      <div class="flex items-center mb-6">
        <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-slate-500 to-gray-500 flex items-center justify-center text-white">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold text-slate-800 ml-4">高级安全功能</h3>
      </div>
      <div class="space-y-4">
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-slate-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-slate-500"></div>
            </div>
            VPN服务器
          </h4>
          <p class="text-sm text-gray-600">搭建私有VPN，安全远程访问</p>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-gray-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-gray-500"></div>
            </div>
            入侵检测
          </h4>
          <p class="text-sm text-gray-600">实时监控网络异常行为</p>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-zinc-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-zinc-500"></div>
            </div>
            访问控制
          </h4>
          <p class="text-sm text-gray-600">精细化权限管理，访问时段控制</p>
        </div>
        <div class="bg-white/60 rounded-lg p-4">
          <h4 class="font-medium text-gray-800 mb-2 flex items-center">
            <div class="w-6 h-6 rounded-full bg-neutral-100 flex items-center justify-center mr-2">
              <div class="w-2 h-2 rounded-full bg-neutral-500"></div>
            </div>
            日志审计
          </h4>
          <p class="text-sm text-gray-600">记录网络活动，安全事件追踪</p>
        </div>
      </div>
      <div class="mt-6">
        <img src="/assets/images/v2-16bbc19ca6b6885d086f60464cc687e3_1440w.png" class="rounded-lg shadow-md w-full" alt="高级安全功能" />
      </div>
    </div>
  </div>
</div>