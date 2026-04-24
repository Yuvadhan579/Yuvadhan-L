# 👋 Hey, I'm Yuvadhan L

🚀 MCA Student | AI/ML Enthusiast | Aspiring Software Developer  
💡 Passionate about building real-world intelligent systems  

---

## 🧠 About Me
- 🎓 MCA Final Year Student (2027)
- 💻 Strong in Java, Python & Data Structures
- 🤖 Interested in AI, Machine Learning & Data Analytics
- 🌱 Currently learning Advanced ML & Full Stack Development
- 🎯 Goal: Become a skilled AI Engineer / Software Developer

---

## ⚡ Tech Stack

### 💻 Languages
![Java](https://img.shields.io/badge/Java-orange)
![Python](https://img.shields.io/badge/Python-blue)
![C](https://img.shields.io/badge/C-lightgrey)
![C++](https://img.shields.io/badge/C++-blue)
![SQL](https://img.shields.io/badge/SQL-green)

### 🤖 AI / ML
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-red)
![Pandas](https://img.shields.io/badge/Pandas-black)
![NumPy](https://img.shields.io/badge/NumPy-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-red)

### 🌐 Web Development
![HTML](https://img.shields.io/badge/HTML-orange)
![CSS](https://img.shields.io/badge/CSS-blue)
![React](https://img.shields.io/badge/React-blue)
![Bootstrap](https://img.shields.io/badge/Bootstrap-purple)

### 🛠 Tools
![Git](https://img.shields.io/badge/Git-orange)
![GitHub](https://img.shields.io/badge/GitHub-black)
![VS Code](https://img.shields.io/badge/VSCode-blue)
![Figma](https://img.shields.io/badge/Figma-purple)

---

## 🚀 Projects

### 🔹 Fuel Consumption Prediction (ML Project)
- Built ML models using **Decision Tree & Linear Regression**
- Predicted fuel consumption based on vehicle data
- Used **Python, Pandas, NumPy, Streamlit**
- Helps optimize fuel usage & reduce cost

### 🔹 Portfolio Website
- Built using **React + Bootstrap**
- Fully responsive & modern UI
- Deployed using Netlify
- Focused on performance & clean design

---

## 📊 GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=Yuvadhan579&show_icons=true&theme=tokyonight)

![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Yuvadhan579E&layout=compact&theme=tokyonight)

---

## 🔥 Streak Stats

![GitHub Streak](https://streak-stats.demolab.com?user=Yuvadhan579&theme=tokyonight)

---

## 🏆 GitHub Trophies

![trophy](https://github-profile-trophy.vercel.app/?username=Yuvadhan579&theme=tokyonight)

---

## 🧑‍💻 Me as Code

```python
struct Developer {
    name: &'static str,
    role: &'static str,
    education: &'static str,
    what_i_do: &'static [&'static str],
    skills: &'static [(&'static str, &'static [&'static str])],
    currently_learning: &'static [&'static str],
    connect_me: &'static [&'static str],
}

impl Developer {
    fn print_profile(&self) {
        println!("\n=============================");
        println!("👨‍💻  Developer: {}", self.name);
        println!("🎓  {}", self.education);
        println!("🚀  {}", self.role);
        println!("=============================\n");

        println!("🎯 What I Do:");
        self.what_i_do.iter().for_each(|area| println!("  • {}", area));

        println!("\n🛠️ Skills:");
        self.skills.iter().for_each(|(category, tools)| {
            println!("  {}:", category);
            tools.iter().for_each(|tool| println!("    - {}", tool));
        });

        println!("\n📚 Currently Learning:");
        self.currently_learning.iter().for_each(|item| println!("  • {}", item));

        println!("\n🔗 Connect with Me:");
        self.connect_me.iter().for_each(|link| println!("  {}", link));

        println!("\n🤝 Let's build something impactful together!\n");
    }
}

static WHAT_I_DO: &[&str] = &[
    "🚀 Building Machine Learning models for real-world problems",
    "📊 Working on Data Analysis & Prediction Systems",
    "🌐 Developing responsive Web Applications",
    "🧠 Solving problems using Data Structures & Algorithms",
    "⚡ Exploring AI & Full Stack Development",
];

static SKILLS: &[(&str, &[&str])] = &[
    ("🧑‍💻 Languages", &["Java ☕", "Python 🐍", "C", "C++", "SQL"]),
    ("🤖 AI/ML", &["Machine Learning", "Pandas", "NumPy", "Streamlit"]),
    ("🌐 Web Development", &["HTML", "CSS", "React ⚛️", "Bootstrap"]),
    ("🗄️ Databases", &["MySQL"]),
    ("⚙️ Tools", &["Git", "GitHub", "VS Code", "Figma"]),
];

static CURRENTLY_LEARNING: &[&str] = &[
    "📈 Advanced Machine Learning",
    "🧠 Deep Learning",
    "🌐 Full Stack Development",
];

static CONNECT_ME: &[&str] = &[
    "💼 LinkedIn: www.linkedin.com/in/yuvadhan-l-748a732a6",
    "💻 GitHub: https://github.com/Yuvadhan579",
    "✉️ Email: yuvadhanl09@gmail.com",
];

fn main() {
    let yuva = Developer {
        name: "Yuvadhan L",
        role: "AI/ML Enthusiast | Aspiring Software Developer",
        education: "MCA Final Year Student (2027)",
        what_i_do: WHAT_I_DO,
        skills: SKILLS,
        currently_learning: CURRENTLY_LEARNING,
        connect_me: CONNECT_ME,
    };

    yuva.print_profile();
}





