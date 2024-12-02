---
layout: base
title:
permalink: /index/
redirect_from: /index.html
---


<style>
    .image-container {
        position: relative; /* 使容器成为定位上下文 */
    }

    .image-container img {
        width: 100%;
        height: 100%;
        object-fit: cover; /* 保证图片填充整个容器并保持比例 */
        object-position: center;
        filter: blur(3px); /* 模糊背景图片 */
    }

    .text-overlay {
        position: absolute; /* 使文字浮动在图片上方 */
        color: white;
        font-size: 3.5rem;
        font-weight: bold;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7); /* 给文字添加阴影 */
        font-family: Arial, sans-serif;
        top: 50%;  /* 元素顶部放置在父元素的50% */
        left: 50%;  /* 元素左边放置在父元素的50% */
        transform: translate(-50%, -50%);
        text-align: center;
        width: 90%;
    }
</style>

<div class="image-container">
    <img src="{{ '/img/overview.png' | absolute_url }}" alt="Overview Image">
    <div class="text-overlay">
        Start to Explore<br>
        the Secret of Biochemistry<br>
        Today
    </div>
</div>



<!-- <table style="width:100%; height:100vh; border: 0;">
<tr>
    <td style="text-align: center; vertical-align: middle;">
        <h1 style="font-size: 50px;">Start to Explore</h1>
        <h1 style="font-size: 50px;">the Secret of Biochemistry</h1>
        <h1 style="font-size: 50px;">Today</h1>
    </td>
</tr>
</table> -->