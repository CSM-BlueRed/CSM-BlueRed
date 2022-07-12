# Hey 👋

[![Discord Presence](https://lanyard.cnrad.dev/api/699359734427549736)](https://discord.com/users/699359734427549736)

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
