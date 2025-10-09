---
theme: default
background: none
class: text-center
layout: intro
highlighter: shiki
lineNumbers: false
info: |
  ## 笔记本使用指南
  为新生准备的笔记本使用指南，包含基础知识、软件推荐、AI工具等内容。
drawings:
  persist: true
transition: slide-left
title: 笔记本使用指南
mdc: true
paginate: true
colorSchema: light
fonts:
  sans: 'Noto Sans SC'
  serif: 'Noto Serif SC'
  mono: 'Fira Code'
css: |
  .slidev-layout {
    background: linear-gradient(to bottom, #f0f9ff, #e0f2fe, #dbeafe);
    position: relative;
    overflow: hidden;
  }
  
  .slidev-layout::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: 
      radial-gradient(circle at 20% 20%, rgba(147, 197, 253, 0.1) 0%, transparent 50%),
      radial-gradient(circle at 80% 80%, rgba(147, 197, 253, 0.1) 0%, transparent 50%);
    z-index: 0;
  }
  
  .content-wrapper {
    position: relative;
    z-index: 1;
  }
  
  .feature-card {
    backdrop-filter: blur(8px);
    background: rgba(255, 255, 255, 0.7);
    border: 1px solid rgba(255, 255, 255, 0.3);
    transform: translateY(0);
    transition: all 0.3s ease;
  }
  
  .feature-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 20px rgba(0, 0, 0, 0.1);
    background: rgba(255, 255, 255, 0.9);
  }
  
  .nav-button {
    background: linear-gradient(135deg, #3b82f6 0%, #6366f1 100%);
    transition: all 0.3s ease;
  }
  
  .nav-button:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(59, 130, 246, 0.3);
  }
---

# 笔记本使用指南 🚀

<div class="content-wrapper">
  <div class="mb-12 text-center">
    <div class="text-2xl font-bold text-blue-600 mb-4">
      专为新生打造的数字化学习指南
    </div>
    <div class="text-gray-600 max-w-2xl mx-auto">
      从基础到进阶，全方位提升你的数字化学习能力
    </div>
  </div>

<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-12 px-4">
  <div v-click="1" class="feature-card p-6 rounded-xl">
    <div class="flex items-center mb-4">
      <div class="w-12 h-12 flex items-center justify-center rounded-full bg-blue-100 text-blue-600 text-2xl">
        💻
      </div>
      <div class="ml-4 text-xl font-semibold text-blue-700">笔记本基础与系统认知</div>
    </div>
    <div class="text-gray-600">了解你的设备，掌握基本操作，建立系统认知</div>
  </div>
  
  <div v-click="2" class="feature-card p-6 rounded-xl">
    <div class="flex items-center mb-4">
      <div class="w-12 h-12 flex items-center justify-center rounded-full bg-green-100 text-green-600 text-2xl">
        📥
      </div>
      <div class="ml-4 text-xl font-semibold text-green-700">软件与资源获取</div>
    </div>
    <div class="text-gray-600">精选必备软件推荐，安全可靠的下载渠道</div>
  </div>

  <div v-click="3" class="feature-card p-6 rounded-xl">
    <div class="flex items-center mb-4">
      <div class="w-12 h-12 flex items-center justify-center rounded-full bg-purple-100 text-purple-600 text-2xl">
        🤖
      </div>
      <div class="ml-4 text-xl font-semibold text-purple-700">AI与智能学习工具</div>
    </div>
    <div class="text-gray-600">掌握AI工具，提升学习效率与创造力</div>
  </div>

  <div v-click="4" class="feature-card p-6 rounded-xl">
    <div class="flex items-center mb-4">
      <div class="w-12 h-12 flex items-center justify-center rounded-full bg-orange-100 text-orange-600 text-2xl">
        🌐
      </div>
      <div class="ml-4 text-xl font-semibold text-orange-700">网络与通信基础</div>
    </div>
    <div class="text-gray-600">网络配置指南，保持顺畅的在线体验</div>
  </div>
</div>

  <div class="absolute bottom-12 left-0 right-0 text-center">
    <a href="./pages/01-basics/01-basics.md" 
       class="nav-button px-8 py-4 rounded-full text-white inline-flex items-center text-lg font-medium">
      开始探索 <carbon:arrow-right class="ml-2 text-xl"/>
    </a>
  </div>
</div>

<div class="absolute bottom-0 left-0 right-0 h-1/3 bg-gradient-to-t from-blue-50/50 to-transparent pointer-events-none"></div>

---
src: ./pages/01-basics/01-basics.md
---

---
src: ./pages/02-software/02-software.md
---

---
src: ./pages/03-ai/03-ai.md
---

---
src: ./pages/04-network/04-network.md
---

---
src: ./pages/05-entertainment/05-entertainment.md
---
