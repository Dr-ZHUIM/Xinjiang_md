---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# 新疆订单可视化安装文档

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---

## 第一步：打开控制面板

<img src="/1.jpg" style="width:800px"/>


---

## 第二步：点击程序

<img src="/2.jpg" style="width:800px"/>

---

## 第三步：点击启动或者关闭windows功能
<img src="/3.jpg" style="width:800px"/>

---

## 第四步：初始化windows功能
看到这个界面一直点击下一步
<img src="/4.jpg" style="width:600px"/>
---

## 第五步：勾选以下内容

<img src="/5.png" style="width:300px"/>

---

## 第六步：找到IIS

点击在桌面左下角的搜索按钮，输入iis
<img src="/6.jpg" style="width:400px"/>

---

## 第七步：添加应用池
右击应用程序池，添加应用程序池
<img src="/7.jpg" style="width:900px"/>

---

## 第八步：添加网站-1
右击网站，添加网站
<img src="/8.jpg" style="width:700px"/>

---

## 第八步：添加网站-2

配置如下：  
**注意！应用程序池要选择上一步添加的那一个**  
**注意！物理路径是你放置xinjiangback文件夹的位置！**
<img src="/9.jpg" style="width:700px"/>

---
## 第九步：打开文件测试
