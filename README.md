# Hey 👋

Welcome to my Github profile, I'm BlueRed. I'm a Python developper and want to learn Java or C.<br>
If you want to code with me, contact me on Discord. I really like cybersecurity and programming.<br>
I do many projects, like [Pystyle](https://pepy.tech/project/pystyle) and [Hyperion](https://obf.plague.fun).
I currently learning C prgramming language (10%).<br>
Feel free to create something with me! I have also a [Discord server](https://discord.gg/j6n4599RXd) (⭐ Developing Community).<br>
In it, you can share your projects (must be about developpement), and find a lot of programmers.<br>
To support me, Star my projects, and subscrible to me! So i'll let you look at my profile and repos!

```python
class dev: ...

class BlueRed(dev):
    r"""
    # BlueRed
    Just a Python developper
    >>> BlueRed().sub()
    """
    def __init__(self) -> None:
        self.name = 'BlueRed'
        self.about = 'Python developper'
        self.age = 13
        self.infos = {
            key: value for key, value in [(key, value) for key, value in self.__dict__.items()] if key in ['name', 'about', 'age']
        } | {'devSkills': self.devSkills}
  
    @property
    def devSkills(self) -> str:
        languages = [
            'Python', 'Lua',
            'Javasript', tuple[str, ...]
        ]
        futureLanguages = ['c']
        return {'good': languages, 'currently-learning': futureLanguages}
        
    @devSkills.deleter
    def devSkills(self) -> None:
        print('You cant...')

    def __gt__(self, other) -> bool:
        return True
```

# 👒 SOCIAL MEDIAS
```js
/*
 * @tiktok BlueRed_ tiktok.com/@bluered_py
 * @youtube CSM BlueRed youtube.com/channel/UCWlvihS81r_wbysgg2J87Kw
 */
```

# 💪 GOOD REPOS

100% Python obfuscator: https://github.com/billythegoat356/hyperion *(by me and the author of the git)* <br>
Python compiler: https://github.com/Nuitka/Nuitka *(work on any Python versions)* <br>
Python tui/style lib: https://github.com/billythegoat356/pystyle *(by me, the author of the git and Lotus)* <br>
Python obfuscator: https://github.com/dashingsoft/pyarmor *(not working in all Python versions)* <br>
Python unless compiler: https://github.com/pyinstaller/pyinstaller *(can be decompiled)* <br>
