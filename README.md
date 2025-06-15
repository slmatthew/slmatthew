<h2 align="center">About Me</h2>

```python
from typing import Tuple, List, Dict

class Matthew:
    pass

class Attributes(Matthew):
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/slmatthew"
        channel  = "t.me/matu4ak"
        email    = "me@slmatthew.ru"
	    
        return telegram, channel, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Russian', 'English']
        age   = 19
		
        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['php'],
            'intermediate': ['js'],
            'learning'    : ['go', 'c#', 'swift']
        }
        specialities  = ['backend']
        ide           = ['vscode', 'phpstorm']
        pc            = {
            'MacOS': {
                'macbook air m1': {
                    'processor': 'm1 | 8 cores',
                    'ram'      : '8gb',
                    'gpu'      : 'm1 | 8 cores'
                }
            },
            'Windows': {
                'custom': {
                    'processor': 'Intel Core i5 12400 | 6 cores',
                    'ram'      : '32gb',
                    'gpu'      : 'nvidia 3060Ti | 4864 CUDA cores'
                }
            }
        }

	return langs, specialities, ide, pc
```

<h2 align="center">Skills</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=bots,nodejs,ts,git,php,cs,dotnet,html,css&perline=4" />
  </a>
</p>

<p align="center">
    <img alt="" src="https://github-readme-stats.vercel.app/api?username=slmatthew&theme=transparent&show_icons=true">
</p>
