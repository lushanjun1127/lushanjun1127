# 陆山君 🌸✨

<div align="center" style="padding:30px; border-radius:30px; backdrop-filter: blur(14px); background: linear-gradient(135deg, rgba(255,182,193,0.3), rgba(173,216,230,0.3)); animation: floatBG 20s ease infinite;">

🌸 二次元爱好者 & 稳定高效程序员  
⚡ 喜欢把创意变成可运行的代码  
🔧 热衷基础设施、生产级项目和自动化  
🌱 永远在学习新技术，优化流程和效率  

</div>

---

### 🛠 技能
<div style="display:flex; flex-wrap:wrap; gap:14px; justify-content:center; animation: fadeIn 1s forwards;">
  <img src="https://img.shields.io/badge/Python-FFD1DC?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-87CEFA?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-FFB6C1?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-9370DB?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-FF69B4?style=for-the-badge&logo=docker&logoColor=white" />
</div>

---

### 📊 GitHub 动态统计
<div align="center" style="display:flex; flex-wrap:wrap; gap:22px; justify-content:center;">
  <img src="https://github-readme-stats.vercel.app/api?username=lushanjun1127&show_icons=true&theme=dark&hide_border=true&bg_color=FFB6C1&text_color=fff" width="45%" style="border-radius:22px; backdrop-filter: blur(12px); animation: fadeIn 1s forwards;" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lushanjun1127&layout=compact&theme=dark&hide_border=true&bg_color=FFD1DC&text_color=000" width="45%" style="border-radius:22px; backdrop-filter: blur(12px); animation: fadeIn 1s forwards; animation-delay:0.2s;" />
</div>

---

### 🚀 项目精选
<div align="center" style="margin-top:20px;">
  <div style="margin-bottom:12px;">
    <button onclick="showCategory('all')">全部</button>
    <button onclick="showCategory('frontend')">前端</button>
    <button onclick="showCategory('backend')">后端</button>
    <button onclick="showCategory('automation')">自动化</button>
  </div>
  
  <div id="projects" style="display:flex; flex-wrap:wrap; gap:22px; justify-content:center;">

    <!-- 示例项目1 -->
    <a href="https://github.com/lushanjun1127/project1" target="_blank" class="project-card all backend" style="text-decoration:none;">
      <div style="width:260px; border-radius:22px; overflow:hidden; box-shadow: 0 8px 28px rgba(255,182,193,0.7); transition: transform 0.5s, opacity 0.5s; opacity:0; transform: translateY(20px); animation: fadeIn 1s forwards; animation-delay:0.1s; background: rgba(255,192,203,0.2); backdrop-filter: blur(14px);">
        <img src="https://via.placeholder.com/260x160?text=ACG+Project+1" alt="项目1" width="260" style="display:block; transition: transform 0.5s;" />
        <p align="center" style="color:#fff; padding:12px; margin:0;">ACG 自动化脚本</p>
      </div>
    </a>

    <!-- 示例项目2 -->
    <a href="https://github.com/lushanjun1127/project2" target="_blank" class="project-card all frontend" style="text-decoration:none;">
      <div style="width:260px; border-radius:22px; overflow:hidden; box-shadow: 0 8px 28px rgba(173,216,230,0.7); transition: transform 0.5s, opacity 0.5s; opacity:0; transform: translateY(20px); animation: fadeIn 1s forwards; animation-delay:0.2s; background: rgba(173,216,230,0.2); backdrop-filter: blur(14px);">
        <img src="https://via.placeholder.com/260x160?text=ACG+Project+2" alt="项目2" width="260" style="display:block; transition: transform 0.5s;" />
        <p align="center" style="color:#fff; padding:12px; margin:0;">萌系前端界面优化</p>
      </div>
    </a>

    <!-- 示例项目3 -->
    <a href="https://github.com/lushanjun1127/project3" target="_blank" class="project-card all automation" style="text-decoration:none;">
      <div style="width:260px; border-radius:22px; overflow:hidden; box-shadow: 0 8px 28px rgba(255,105,180,0.7); transition: transform 0.5s, opacity 0.5s; opacity:0; transform: translateY(20px); animation: fadeIn 1s forwards; animation-delay:0.3s; background: rgba(255,105,180,0.2); backdrop-filter: blur(14px);">
        <img src="https://via.placeholder.com/260x160?text=ACG+Project+3" alt="项目3" width="260" style="display:block; transition: transform 0.5s;" />
        <p align="center" style="color:#fff; padding:12px; margin:0;">ACG 基础设施级页面</p>
      </div>
    </a>

  </div>
</div>

<style>
@keyframes fadeIn { to { opacity:1; transform: translateY(0); } }
@keyframes floatBG { 0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%} }
a div:hover img { transform: scale(1.1) rotate(-1deg); }
a div:hover { transform: translateY(-10px) rotateX(3deg) rotateY(3deg); box-shadow: 0 12px 36px rgba(255,182,193,0.8); }
.project-card { display:inline-block; transition: all 0.5s; }
button { margin:4px; padding:6px 12px; border-radius:8px; border:none; cursor:pointer; background:#ff69b4; color:#fff; transition: all 0.3s; }
button:hover { background:#ff85c1; }
</style>

<script>
function showCategory(category) {
  const cards = document.querySelectorAll('.project-card');
  cards.forEach(card => {
    if(category === 'all' || card.classList.contains(category)) {
      card.style.display = 'inline-block';
      setTimeout(()=>{card.style.opacity=1; card.style.transform='translateY(0)';},50);
    } else {
      card.style.opacity=0;
      card.style.transform='translateY(20px)';
      setTimeout(()=>{card.style.display='none';},500);
    }
  });
}
</script>

---

### 📫 联系我
<div align="center" style="background: rgba(255,182,193,0.2); padding:20px; border-radius:22px; backdrop-filter: blur(14px); transition: all 0.5s; animation: fadeIn 1s forwards;">
📧 [lushanjun@hotmail.com](mailto:lushanjun@hotmail.com)  
🌐 [个人网站/博客](https://your-website.com)
</div>
