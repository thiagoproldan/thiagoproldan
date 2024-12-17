# Hello, World! 👋🌐
Welcome to my GitHub profile! I’m Thiago Roldan, a passionate **Data Scientist** and **Software Engineer**. Below, you'll find a mix of my coding journey, skills, and personal stats. Feel free to explore, connect, and collaborate!

# 🐍 About me in Python:
``` Python
from datetime import datetime

class DataScientist:
    """
    ✨ Class: DataScientist ✨
    A class representing a brief introduction about me as a data scientist.
    """

    def __init__(self):
        self.name: str = "Thiago Roldan"
        self.languages: list[str] = ["Python", "R", "SQL"]
        self.tools: list[str] = ["Vim/Neovim", "VS Code", "JetBrains Tools", "Jupyter Notebook", "Insomnia"]
        self.specialties: list[str] = ["Data Science", "Machine Learning", "Software Engineering"]
        self.current_focus: str = "Improving my skills in Data Science and Machine Learning."
        self.fun_fact: str = "I love solving puzzles and creating challenges—that's how I keep learning! 💡"
        self.technologies: dict[str, list[str]] = {
            "Back-End": ["Flask 🧪", "Django 🕊️", "FastAPI ⚡"],
            "DevOps": ["AWS ☁️", "Docker 🐳", "Kubernetes ☸️"],
            "Databases": ["MySQL 🐬", "PostgreSQL 🐘", "DynamoDB 🛠️"],
            "Machine Learning": ["scikit-learn 🤖", "TensorFlow 🔗", "PyTorch 🔥", "XGBoost 🌟"],
            "Data Viz": ["Pandas 🐼", "NumPy 🔢", "Matplotlib 📊", "Seaborn 🌊", "Plotly 📈"]
        }

    def get_technologies_as_string(self) -> str:
        """
        Converts the technologies dictionary into a formatted string.
        """
        return "\n".join(f"  {category}: {', '.join(techs)}" for category, techs in self.technologies.items())

    def recommend_tool(self) -> str:
        """
        Recommends a tool or technology based on the user's name and current time.
        """
        all_techs = [tech for tech_list in self.technologies.values() for tech in tech_list]
        current_time = datetime.now().strftime("%Y%m%d%H%M%S")
        index = (sum(ord(char) for char in self.name + current_time)) % len(all_techs)
        return f"🤖 Today, why not try: {all_techs[index]}?"

    def __str__(self) -> str:
        """
        Returns a string representation of the DataScientist instance.
        """
        tech_lines = self.get_technologies_as_string()
        return (
            f"👋 Hi, I'm {self.name}!\n"
            f"🌟 Current Focus: {self.current_focus}\n"
            f"🎯 Specialties: {', '.join(self.specialties)}\n\n"
            f"💻 Programming Languages: {', '.join(self.languages)}\n"
            f"🛠️ Tools: {', '.join(self.tools)}\n\n"
            f"🔧 Technologies I work with:\n{tech_lines}\n\n"
            f"🎉 Fun Fact: {self.fun_fact}\n\n"
            f"🔗 Check out my GitHub: https://github.com/thiagoproldan\n"
            f"🔗 Connect with me on LinkedIn: https://linkedin.com/in/thiagoproldan"
        )

# Display profile information when this script is run directly
if __name__ == "__main__":
    me = DataScientist()
    print(me)
    print("\n" + me.recommend_tool())
```

# 📈 My GitHub Stats:

## 🔥 GitHub Streak
<p align="center">
<img height="192px" alt="Thiago Roldan's Github Streak Stats" src="https://github-readme-streak-stats-tau-woad.vercel.app/?user=thiagoproldan&card_width=570&theme=default&hide_border=true" />
<img height="180px" alt="Custom animation GIF" src="https://i.imgur.com/KJUDvY2.gif"/>
</p>

## 📊 GitHub Stats and Languages
<p align="center">
<a href="https://github.com/thiagoproldan"><img alt="Thiago Roldan's Github Stats" src="https://github-readme-stats-pi-mauve-92.vercel.app/api/?username=thiagoproldan&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&" height="192px"/></a>
<a href="https://github.com/thiagoproldan"><img alt="Thiago Roldan's Top Languages" src="https://github-readme-stats-pi-mauve-92.vercel.app/api/top-langs/?username=thiagoproldan&langs_count=8&layout=compact&hide_border=true" height="192px"/></a>
</p>

## 📉 Activity Graph
<a href="https://github.com/thiagoproldan"><img alt="Thiago Roldan's Activity Graph" src="https://github-readme-activity-graph-nu-eight.vercel.app/graph/?username=thiagoproldan&theme=github-compact&hide_border=true" /></a>

# 🔗 Where I Break Code (and Fix It)
[![LeetCode badge](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=LeetCode&logoColor=orange)](https://leetcode.com/u/thiagoproldan/)
[![HackerRank badge](https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=HackerRank&logoColor=black)](https://www.hackerrank.com/profile/thiagoproldan/)
[![CodeWars badge](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=codewars&logoColor=grey)](https://www.codewars.com/users/thiagoproldan/)

---
Thanks for visiting my profile! 🚀 Feel free to explore my repositories, connect on LinkedIn, or challenge me on LeetCode, HackerRank, and CodeWars! Let's grow and learn together. 🌟
