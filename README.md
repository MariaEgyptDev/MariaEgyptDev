<div align="center">

<img src="https://github.com/SP-XD/SP-XD/blob/main/images/hellocoders_rounded.gif?raw=true" width="60%" alt="Hello Coders"/>

<br>
<!-- GIF متحرك للبنت بعد الصورة الأولى -->
<img src="https://i.ibb.co/5hTZ6BmC/female-coding.gif" width="40%" alt="Coding Fun Girl"/>

# 👩‍💻 Mariam Adel | مريم عادل

**Student • Intermediate Programmer • Aspiring Developer**

I’m a 16-year-old student who loves learning programming and building small projects.  
This GitHub profile is where I share my learning journey and track my progress step by step.

I’m currently focusing on learning, practicing, and improving my skills.  
My dream is to travel, grow as a developer, and become someone I’m proud of.

</div>

---

## 🚀 Tools I Use
<p align="center">
<img src="https://img.shields.io/badge/Python-FFD43B?style=flat&logo=python&logoColor=darkgreen"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078D4?style=flat&logo=visual%20studio%20code&logoColor=white"/>
<img src="https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white"/>
<img src="https://img.shields.io/badge/Twine-8A2BE2?style=flat&logoColor=white"/>
</p>

---

## 📚 What I’m Doing Now
- Learning Python and web basics  
- Building small projects to practice programming  
- Improving my logic and problem-solving skills  
- Sharing my progress on GitHub  

---

## 🎯 Goals
- Improve programming skills step by step  
- Create clean and simple projects  
- Keep learning and building confidence  
- Grow into a strong and independent developer  

---

## ✨ Coding Feel ✨
<div align="center">
<img src="https://i.ibb.co/2s1fG3H/female-coding.gif" width="20%" alt="Coding Fun Girl"/>
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Face%20with%20Spiral%20Eyes.png" width="10%" alt="Broken system!"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Relieved%20Face.png" width="10%" alt="It's working!"/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Astonished%20Face.png" width="10%" alt="It's working but you don't know how!"/>
</div>


## 📫 Contact
- 📧 Email: **maria3del2023@gmail.com**  
- 📸 Instagram: **[@mar.iam3del](https://www.instagram.com/mar.iam3del/)**  
- 💻 GitHub: **[MariamEgyptDev](https://github.com/MariamEgyptDev)**


## ⚡ My Skills Level


import matplotlib.pyplot as plt
import numpy as np

# المهارات ومستواها
skills = {
    "Twine": 90,
    "Python": 85,
    "HTML": 60,
    "Unity": 54,
    "CSS": 54
}

# إعداد الشكل العام
fig, axes = plt.subplots(1, len(skills), figsize=(15, 3), subplot_kw={'projection': 'polar'})

if len(skills) == 1:
    axes = [axes]

for ax, (skill, level) in zip(axes, skills.items()):
    # نصف دائرة 0-180 درجة
    theta = np.linspace(0, np.pi, 100)
    radii = np.ones_like(theta)*1.5
    
    # خلفية الدائرة
    ax.plot(theta, radii, color="#ddd", linewidth=20, alpha=0.5)
    
    # السهم اللي يوضح المستوى
    theta_level = np.pi * level / 100
    ax.plot([0, theta_level], [0, 1.5], color="#ff5733", linewidth=4)  # السهم
    
    # عنوان المهارة والنسبة
    ax.set_title(f"{skill} ({level}%)", va='bottom', fontsize=12)
    
    # إزالة علامات المحور
    ax.set_yticklabels([])
    ax.set_xticklabels([])
    ax.set_ylim(0, 1.5)

plt.tight_layout()
plt.show()
rey)
