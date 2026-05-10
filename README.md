<p align="center">
  <img src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/ff3d8db2-fc3d-4c1e-be65-beaf48536dcf.png" alt="SocialGPT Banner" width="600"/>
  
</p>

<h1 align="center">SocialGPT: 社会关系推理框架</h1>
<p align="center">通过视觉基础模型(VFMs)与大语言模型(LLMs)结合，实现零样本社会关系推理</p>

---

## 📌 核心问题
- 传统方法泛化性差，难以处理不同风格图像（卡通、素描等）  
- 端到端神经网络“黑箱”，缺乏可解释性  
- 手动提示设计低效，长提示难以优化  

---

## 💡 核心贡献
1. **模块化 SocialGPT 框架**  
   融合 VFMs + LLMs，实现“感知+推理”，提供强零样本基线  

2. **贪婪段提示优化(GSPO)**  
   - 段级优化代替令牌级优化  
   - 自动搜索提示，减少人工干预  
   - 输出格式固定，生成结构化标签  

3. **实验表现**  
   - 无需额外训练即可得到竞争力零样本结果  
   - 提供可解释推理过程  

---

## 🔍 技术流程示意
<p align="center">
  <img width="1120" height="493" alt="SocialGPT" src="https://github.com/user-attachments/assets/f061aac9-e239-469d-9e8b-33ecb8d14a9d" />

</p>

**流程说明：**  
1️⃣ 图像输入 → 2️⃣ SAM分割 + BLIP-2描述 → 3️⃣ SocialPrompt生成 → 4️⃣ LLM推理 → 5️⃣ 输出可解释社会关系  

---

## ⚡ 示例
> 家庭聚会场景  
> 白发老人 + 中年女性 + 年轻男子 + 小男孩 → 推理出祖孙、亲子关系  

---

<p align="center">
  <a href="[https://github.com/yhe8479-ship-it/myproject"><img src="https://img.shields.io/badge/GitHub-主页-181717?style=flat&logo=github" alt="GitHub Badge"/></a>
</p>

