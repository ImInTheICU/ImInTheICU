<p align="center"> <img src="https://cdn.discordapp.com/avatars/1156701175547166850/03de70812c94e565e0c36559d0e56b2b.webp" alt="pingulovesu" /> </p>

<h1 align="center">Hi 👋, I'm Christopher</h1>
<p align="center">Hello, I'm Braiden or known online as PinguLovesYou. <br>My programming consists of game & anti-cheat development. <br>You'll find me on Discord, Twitter, Steam, Roblox and the beaches of Rust!</p>

<p align="center"> <img src="https://komarev.com/ghpvc/?username=imintheicu&label=Profile%20views&color=d400ff&style=flat" alt="imintheicu" /> </p>
<p align="center">&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=imintheicu&show_icons=true&theme=synthwave&locale=en" alt="imintheicu" /></p>


```py
import datetime

class Human:
    def __init__(self, name: str, birth_year: int, code_languages: list, code_interests: list) -> None:
        self.name = name
        self.age = datetime.datetime.now().year - birth_year
        self.code_languages = code_languages
        self.code_interests = code_interests
    
    def identify_self(self):
        interests_str = ', '.join(self.code_interests)
        languages_str = ', '.join(self.code_languages)

        print(f"""
Hello, I'm {self.name}! 
I'm {self.age} years old and interested in {interests_str}. 
I work with {languages_str}.
        """)

Pingu = Human(
    name="Braiden",
    birth_year=2008,
    code_languages=["Python", "Lua", "Java", "C#"],
    code_interests=["Game Hacking", "Encryption", "Decryption", "Obfuscation", "Reverse Engineering"]
)
Pingu.identify_self()
```
