```py
from Github import Profile, Contributions, Projects


class eysxia(Profile):
    def __init__(self):
        super().__init()
        self.name = "eysxia"
        self.aliases = ["mercy", "leme", "bry"]
        self.primary_language = "Python"
        self.languages = ["Python", "Javascript", "Html+CSS"]
        self.bio = "I'm Bry, I like making things that people can use for free 💯"
        self.projects = Projects.load(user=self.username)
        self.contributions = Contributions.load(user=self.username)

    def display_profile(self):
        print(f"👋 Hello, I'm {self.username} (aka {', '.join(self.aliases)})!")
        print(f"💻📌 Primary Language: {self.primary_language}")
        print(f"💻 Other Languages: {", ".join(self.languages)}")
        print(f"📜 Bio: {self.bio}")


if __name__ == "__main__":
    profile = eysxia()
    profile.display_profile()
```
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=eysxia&style=flat-square&color=faa6ff" />
</p>

<details align="center">
    <summary><h2><b>⭐ Github Stats</b></h2></summary>
    <p>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=eysxia&layout=donut-vertical&bg_color=00000000"/>
    <br>
    <img src="https://github-readme-stats.vercel.app/api?username=eysxia&show_icons=true&bg_color=00000000"/>
    </p>
</details>
