<p align="center"><a href="https://emojipedia.org/"><img src="https://cdn.discordapp.com/attachments/312993895887929355/791621818032848896/AUEPA.png" width=675></a></p> 

<p align="center"><a href="https://www.python.org/downloads/release/python-375/"><img src="https://img.shields.io/badge/Python-3.7.5-brightgreen?style=for-the-badge&logoColor=white&link=https://www.python.org/&https://www.python.org/downloads/&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAPCAMAAAAMCGV4AAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAABVlBMVEUAAAA5e7Q3ebA3eK43dak3dKY2dKI5gLg4ebA1eq83d6s3caI8aaU5e7M3eK42eKs4cJsAgIA4eK85d7A2dqs2dKk2dKc3cqR2koD/10v/20k2ebU4ebDRvlz/1UX/00Q4erDbxFf/0UA2eK42aZb/1ET/zz83d6s3cqQ6c6GZpXuprXCpq2y8s2P900X/00M3cKL/3lH/zDs2dKZVg5L/yjk3c6U3caJihoz/yTn/xzg7dp03bpuqqnH/0kP/0kD/0D7/zjz/yzz/wzz//wD/2E7/zj7/yDf/41X/1Ub/zj3/zTz/yjn/yDf/1Ub/00L/0ED/zj3/zDv/yTr/xzg3d6s3dak3dKc3cqQ3caI3cJ82bp03eK42bZr/10c2a5j/1UX/00P/0UE3dKb/zz//zT3/3U7/20z/2Ur/10j/1Ub/zj3/zDv/00T/0D//0kL/1ET///8twZG5AAAAVXRSTlMAVcbw67tCEuhD9/YRG/ukKQIgLYiIiL44MxUm3HX1QKxwwuqzlfj6/oVudnZvhf2fq/aydbYz7njbKQ0zLb13d3ciEQEaoSoJ7vxN4Rw3suj27MNWkzfuJAAAAAFiS0dEca8HXOIAAAAHdElNRQfkBQcLNhpsHcMTAAAAuklEQVQI12NgAAJGJuZQFlY2Bihg5+DkCguP4OaB8nn5+IHcyCgBME9QSFhEVEw8MipaQlKKgUFaJiYULBsdKxsnJ8+gAOfGKyYkKjEow7kqqolJagzqYckamlraOjq6evpJKakMLMkRBoZp6RmZWYlArhGDcUSkCYybnWPKYGYeZQHi5iblZedYWjEwWNvYArl29g6OTs4uYBe5AmXz89yM3KHu9fAsyM/z8vbxhXnIzz8gMCg4BMQEAKy7MbtksegJAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDIwLTA1LTA3VDExOjU0OjI2KzAwOjAw1j8VsQAAACV0RVh0ZGF0ZTptb2RpZnkAMjAyMC0wNS0wN1QxMTo1NDoyNiswMDowMKdirQ0AAAAASUVORK5CYII="></a></p>

<p align="center"><a href="https://github.com/kubinka0505/auepa/releases/"><img src="https://img.shields.io/github/v/release/kubinka0505/auepa?style=for-the-badge"></a>　<a href="https://github.com/kubinka0505/auepa/commit/"><img src="https://img.shields.io/github/last-commit/kubinka0505/auepa?style=for-the-badge"></a></p>

<p align="center"><a href="https://github.com/kubinka0505/auepa/issues/"><img src="https://img.shields.io/github/issues/kubinka0505/auepa?style=for-the-badge"></a>　<a href="https://www.gnu.org/licenses/gpl-3.0.txt"><img src="https://img.shields.io/badge/license-GPL%20V3-red?style=for-the-badge"></a></p>

<p align="center"><img src="https://img.shields.io/codeclimate/maintainability/kubinka0505/auepa?logo=code-climate&style=for-the-badge"></a></p>

## Description 📝
I'm into Image Processing and I saw that there are no unoficcial EmojiPedia APIs that support many emoji image styles, so I've programmed one.

---
## Completed & Planned Features 🧑‍💻
- ✔️ Completed
- ❌ In Development
---
- ✔️ Basic emoji information scraping
- ✔️ **Multiple emoji images support**
- ❌ Optimized `Category` class support
- ❌ `Style` class

## Requirements 📥
- `Python >= 3.6`
- `PIL >= 5.1` (optional)
- `requests >= 2.12.5`
- `emoji`
---
## Installation 🖥️

1. `GitHub` Method **(recommended)**
	1. Clone the repository.
		```bash
		git clone https://github.com/kubinka0505/auepa
		cd auepa
		```
	2. Go to `Files` directory and install.
		```bash
		cd Files
		python setup.py install
		```
2. `pip` Method
	1. Type into CMD: `python -m pip install auepa`

## Usage 📝

```python
>>> import auepa
>>>
>>> # Get an emoji character & its description from EmojiPedia.
>>> Emote = auepa.Emoji(":snake:").unicode
>>> Description = auepa.Meta.Emoji(Emote).description
>>>
>>> # Print the emoji aliases
>>> print(auepa.Meta.Emoji(Emote).aliases)
['Serpent', 'Snake']
>>>
>>> # Print the emoji description.
>>> print(Description)
A snake, a slithering reptile without limbs. Generally depic...
>>>
>>> # Get an emoji image from Windows 10.
>>> auepa.Utils.get_image(
...     Emote,
...     {"windows": "10"} #1
...     )
'https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/...
```

¹ - Styles list are available [here](https://github.com/kubinka0505/auepa/wiki/Image-Styles).

## Meta Info ℹ️
### Disclaimer ⚠️
**All versions of this project have been made on:**
- `Windows 7 (64-bit)`
- `Python 3.7.5`

**[In case of problems create issue](https://github.com/kubinka0505/auepa/issues/new/choose)**.