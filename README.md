# Create the markdown file with the Cyberpunk-themed README content

markdown_content = """
<p align="center">
  <img src="https://i.imgur.com/Nq7oI2y.gif" alt="Cyberpunk Banner" width="90%">
</p>

<h1 align="center">⚡️ I'm <span style="color:#0ff;font-weight:bold;">Wahib Mohammed</span> ⚡️</h1>

---

### 💾 **Cyberpunk Profile**

I’m a passionate **Game Developer & Designer** navigating the digital frontier, crafting immersive and sleek gaming experiences with **Unity**.  

Obsessed with game feel, pixel perfection, and creating engaging, unforgettable worlds.

---

### 🔥 **Skills & Tech Stack**

**Game Engines & Design Tools:**

- Unity, Godot, Unreal Engine, Blender, Aseprite, Figma

**Programming Languages:**

- C#, C++, Python, Java, JavaScript, TypeScript, HTML5, CSS3

**Frameworks & Libraries:**

- Flutter, Spring Boot, React, Node.js

**Databases:**

- MySQL, SQLite

**DevOps & Creative Tools:**

- Git, GitHub, Postman, Photoshop, Audacity, FL Studio, DaVinci Resolve, Obsidian

---

### 📊 **GitHub Cyberstats**

<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=wahibpop&show_icons=true&hide_border=true&count_private=true&theme=radical"/>
  <img height="170em" src="https://github-readme-streak-stats.herokuapp.com/?user=wahibpop&theme=radical&hide_border=true"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wahibpop&langs_count=8&theme=radical&hide_border=true&layout=compact"/>
</p>

---

### 🌃 **My Cyber Projects**

| Repo | Description | Tech |
|------|-------------|------|
| [AstroBlaster](https://github.com/wahibpop/AstroBlaster) ⚡️ | Arcade space shooter, intense & vibrant gameplay | Unity, C# |
| [PixelPuzzle](https://github.com/wahibpop/PixelPuzzle) 🧩 | Relaxing pixel-art puzzle experience | Unity, C# |
| [DevTools](https://github.com/wahibpop/DevTools) 🛠️ | Unity editor enhancements & workflow boosters | Unity, C# |
| [GameTemplate](https://github.com/wahibpop/GameTemplate) 🚀 | Modular Unity template ready for rapid prototyping | Unity, C#, UI/UX |

---

### 🔗 **Connect With Me**

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wahibpop@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wahib-mohammed-b03324229/)
[![X](https://img.shields.io/badge/X-%231DA1F2.svg?style=for-the-badge&logo=X&logoColor=white)](https://x.com/yqwz_)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=wahibpop&style=flat-square&color=0ff" alt="Profile views" />
</p>
"""

# Save the content to a markdown file
file_path = '/mnt/data/cyberpunk_readme.md'
with open(file_path, 'w', encoding='utf-8') as f:
    f.write(markdown_content)

file_path
