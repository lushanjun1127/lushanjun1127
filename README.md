# 陆山君

<div align="center" style="padding:30px; border-radius:30px; backdrop-filter: blur(12px); background: linear-gradient(135deg, rgba(0,0,0,0.7), rgba(20,20,30,0.7)); animation: gradientBG 15s ease infinite;">

💻 小白程序员，但追求高效与稳定  
⚡ 实用主义者，喜欢把想法落地成可运行的代码  
🔧 热衷基础设施、生产级项目和自动化  
🌱 永远在学习新技术，优化工作流程和效率  
📈 对性能、可维护性和可扩展性有执念  

</div>

---

### 🛠 技能
<div style="display:flex; flex-wrap:wrap; gap:14px; justify-content:center; animation: fadeIn 1s forwards;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</div>

---

### 📊 GitHub 动态统计
<div align="center" style="display:flex; flex-wrap:wrap; gap:22px; justify-content:center;">
  <img src="https://github-readme-stats.vercel.app/api?username=lushanjun1127&show_icons=true&theme=dark&hide_border=true" width="45%" style="border-radius:22px; backdrop-filter: blur(10px); animation: fadeIn 1s forwards;" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lushanjun1127&layout=compact&theme=dark&hide_border=true" width="45%" style="border-radius:22px; backdrop-filter: blur(10px); animation: fadeIn 1s forwards; animation-delay:0.2s;" />
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
      <div style="width:260px; border-radius:22px; overflow:hidden; box-shadow: 0 12px 36px rgba(0,0,0,0.65); transition: transform 0.5s, opacity 0.5s; opacity:0; transform: translateY(20px); animation: fadeIn 1s forwards; animation-delay:0.1s; background: rgba(255,255,255,0.05); backdrop-filter: blur(12px);">
        <img src="https://via.placeholder.com/260x160?text=Project+1" alt="项目1" width="260" style="display:block; transition: transform 0.5s;" />
        <p align="center" style="color:#fff; padding:12px; margin:0;">生产级自动化脚本工具</p>
      </div>
    </a>

    <!-- 示例项目2 -->
    <a href="https://github.com/lushanjun1127/project2" target="_blank" class="project-card all frontend" style="text-decoration:none;">
      <div style="width:260px; border-radius:22px; overflow:hidden; box-shadow: 0 12px 36px rgba(0,0,0,0.65); transition: transform 0.5s, opacity 0.5s; opacity:0; transform: translateY(20px); animation: fadeIn 1s forwards; animation-delay:0.2s; background: rgba(255,255,255,0.05); backdrop-filter: blur(12px);">
        <img src="https://via.placeholder.com/260x160?text=Project+2" alt="项目2" width="260" style="display:block; transition: transform 0.5s;" />
        <p align="center" style="color:#fff; padding:12px; margin:0;">高效前端界面和交互优化</p>
      </div>
    </a>

    <!-- 示例项目3 -->
    <a href="https://github.com/lushanjun1127/project3" target="_blank" class="project-card all automation" style="text-decoration:none;">
      <div style="width:260px; border-radius:22px; overflow:hidden; box-shadow: 0 12px 36px rgba(0,0,0,0.65); transition: transform 0.5s, opacity 0.5s; opacity:0; transform: translateY(20px); animation: fadeIn 1s forwards; animation-delay:0.3s; background: rgba(255,255,255,0.05); backdrop-filter: blur(12px);">
        <img src="https://via.placeholder.com/260x160?text=Project+3" alt="项目3" width="260" style="display:block; transition: transform 0.5s;" />
        <p align="center" style="color:#fff; padding:12px; margin:0;">完整基础设施级页面布局</p>
      </div>
    </a>

  </div>
</div>

<style>
@keyframes fadeIn { to { opacity:1; transform: translateY(0); } }
@keyframes gradientBG { 0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%} }
a div:hover img { transform: scale(1.08); }
a div:hover { transform: translateY(-12px) rotateX(2deg) rotateY(2deg); box-shadow: 0 16px 48px rgba(0,0,0,0.75); }
.project-card { display:inline-block; transition: all 0.5s; }
button { margin:4px; padding:6px 12px; border-radius:8px; border:none; cursor:pointer; background:#555; color:#fff; transition: all 0.3s; }
button:hover { background:#777; }
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
<div align="center" style="background: rgba(255,255,255,0.05); padding:20px; border-radius:22px; backdrop-filter: blur(12px); transition: all 0.5s; animation: fadeIn 1s forwards;">
📧 [lushanjun@hotmail.com](mailto:lushanjun@hotmail.com)  
🌐 [个人网站/博客](https://your-website.com)
</div>
