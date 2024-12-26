# Hello, World! 👋🌐
Welcome to my GitHub profile! I’m Thiago Roldan, a passionate **Data Scientist** and **Software Engineer**. Below, you'll find a mix of my coding journey, skills, and personal stats. Feel free to explore, connect, and collaborate!

# 🐍 About me in Python:
``` Python
class DataScientist:
    """
    ✨ Class: DataScientist ✨

    A class representing a brief introduction about me as a data scientist.
    """

    def __init__(self):
        self.name: str = "Thiago Roldan"
        self.languages: list[str] = [
            "Python", "R", "SQL"
        ]
        self.tools: list[str] = [
            "JetBrains Tools", "Jupyter Notebook", "Insomnia"
        ]
        self.specialties: list[str] = [
            "Data Science", "Machine Learning", "Software Engineering"
        ]
        self.technologies: dict[str, list[str]] = {
            "Back-End": [
                "Flask 🧪", "Django 🕊️", "FastAPI ⚡"
            ],
            "DevOps": [
                "AWS ☁️", "Docker 🐳", "Kubernetes ☸️"
            ],
            "Databases": [
                "MySQL 🐬", "PostgreSQL 🐘", "DynamoDB 🛠️", "MongoDB 🍃"
            ],
            "Machine Learning": [
                "scikit-learn 🤖", "TensorFlow 🔗", "PyTorch 🔥", "XGBoost 🌟", "Keras 🧠"
            ],
            "Data Viz": [
                "Pandas 🐼", "NumPy 🔢", "Matplotlib 📊", "Seaborn 🌊", "Plotly 📈"
            ],
        }

        self.current_focus: str = (
            "Improving my skills in Data Science "
            "and Machine Learning."
        )
        self.fun_fact: str = (
            "I love solving puzzles and creating challenges—"
            "that's how I keep learning! 💡"
        )

    def get_technologies_as_string(self) -> str:
        """
        Converts the technologies dictionary into a formatted string.
        """
        return "\n".join(
            f"  {category}: {', '.join(techs)}"
            for category, techs in self.technologies.items()
        )

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
        )

if __name__ == "__main__":
    me = DataScientist()
    print(me)
```

# 📈 My GitHub Stats:

## 🔥 GitHub Streak
<p align="center">
<img height="192px" alt="Thiago Roldan's Github Streak Stats" src="https://github-readme-streak-stats-omega-seven.vercel.app/?user=thiagoproldan&card_width=570&theme=default&hide_border=true" />
<img height="180px" alt="Custom animation GIF" src="https://i.imgur.com/KJUDvY2.gif"/>
</p>

## 📊 GitHub Stats and Languages
<p align="center">
<a href="https://github.com/thiagoproldan"><img alt="Thiago Roldan's Github Stats" src="https://github-readme-stats-nine-kappa-38.vercel.app/api/?username=thiagoproldan&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&" height="192px"/></a> 
<a href="https://github.com/thiagoproldan"><img alt="Thiago Roldan's Top Languages" src="https://github-readme-stats-nine-kappa-38.vercel.app/api/top-langs/?username=thiagoproldan&langs_count=8&layout=compact&hide_border=true" height="192px"/></a>
</p>

## 📉 Activity Graph 
<a href="https://github.com/thiagoproldan"><img alt="Thiago Roldan's Activity Graph" src="https://github-readme-activity-graph-ebon.vercel.app/graph/?username=thiagoproldan&theme=github-compact&hide_border=true" /></a>

# 🔗 Where I Break Code (and Fix It)
[![LeetCode badge](https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=LeetCode&logoColor=orange)](https://leetcode.com/u/thiagoproldan/)
[![HackerRank badge](https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=HackerRank&logoColor=black)](https://www.hackerrank.com/profile/thiagoproldan/)
[![CodeWars badge](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=codewars&logoColor=grey)](https://www.codewars.com/users/thiagoproldan/)

---
Thanks for visiting my profile! 🚀 Feel free to explore my repositories, connect on LinkedIn, or challenge me on LeetCode, HackerRank, and CodeWars! Let's grow and learn together. 🌟
