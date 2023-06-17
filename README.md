<img align="center" src="https://cdn.discordapp.com/attachments/1106913875275812924/1119585479797522492/Frame_3_1.png">

<h1 align="center">Hello, I'm BlueRed 👋</h1>
<p align=center>
    Hello, I'm BlueRed, I am a young Fullstack developer, I am currently learning the C# programming language
    to lean reverse engineering. My principals languages are Python, TypeScript, and JavaScript. I made alot
    of projetcts, like PyStyle, Harmony, Impostor, TSA, Hyperion, ByteH, and more, but 90% of them are not on GitHub.
    If you want to contact me, You can via my socials. I made a programming language based on Bytecode-like syntax.
</p>

<img align="center" src="https://cdn.discordapp.com/attachments/1106913875275812924/1119596499580497981/Frame_5_2.png">


```ts
type UserInfo = {
    name: string,
    age: number
};

type UserSocials = {
    TikTok: string,
    Discord: string,
    GitHub: string
};
```

```py
import typing
from datetime import datetime

class BlueRed:

    @classmethod
    def get_info(cls) -> UserInfo:
        return {
            'name': cls.__name__,
            'age': datetime.now().year - 2009
        }

    @staticmethod
    def get_socials() -> UserSocials:
        return {
            'TikTok' : 'https://tiktok.com/@bluered.pyx',
            'Discord': 'https://discord.com/users/1093599815599935568',
            'GitHub' : 'https://github.com/CSM-BlueRed',
        }
```

```cs
UserInfo info = BlueRed.get_info();
UserSocials socials = BlueRed.get_socials();

Console.WriteLine(info);
Console.WriteLine("----- socials -----");
Console.WriteLine(socials);
```
