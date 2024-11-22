```py
from Github import Profile, Contributions, Projects


class merciful_lol(Profile):
    def __init__(self):
        super().__init()
        self.name = "merciful-lol"
        self.aliases = ["mercy", "bry"]
        self.primary_language = "Python"
        self.languages = ["Python", "Javascript", "Html+CSS"]
        self.bio = "I'm Bry, I like making things people can use for free 💯"
        self.projects = Projects.load(user=self.username)
        self.contributions = Contributions.load(user=self.username)

    def display_profile(self):
        print(f"👋 Hello, I'm {self.username} (aka {', '.join(self.aliases)})!")
        print(f"💻📌 Primary Language: {self.primary_language}")
        print(f"💻 Other Languages: {", ".join(self.languages)}")
        print(f"📜 Bio: {self.bio}")


if __name__ == "__main__":
    profile = merciful_lol()
    profile.display_profile()
```

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=merciful-lol&layout=donut-vertical&bg_color=00000000)
![GitHub stats](https://github-readme-stats.vercel.app/api?username=merciful-lol&show_icons=true&bg_color=00000000)
