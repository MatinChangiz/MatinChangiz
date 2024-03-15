[![Profile Views](https://komarev.com/ghpvc/?username=MatinChangiz)](https://github.com/MatinChangiz)
![Profile Status](https://img.shields.io/static/v1?label=GitHub%20Status&message=Active&color=brightgreen)
## Used Languages and Technologies

![HTML](https://img.shields.io/badge/HTML-HTML5-E34F26?logo=html5&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-Laravel-FF2D20?logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-CodeIgniter-F05032?logo=codeigniter&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-Bootstrap-7952B3?logo=bootstrap&logoColor=white)
![Python](https://img.shields.io/badge/Python-Python-3776AB?logo=python&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-WordPress-21759B?logo=wordpress&logoColor=white)
![Materialize](https://img.shields.io/badge/Materialize-Materialize-EE6E73?logo=materialize&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-jQuery-0769AD?logo=jquery&logoColor=white)
![AJAX](https://img.shields.io/badge/AJAX-AJAX-0096D6?logo=ajax&logoColor=white)
![RSS](https://img.shields.io/badge/RSS-RSS-FFA500?logo=rss&logoColor=white)
![API](https://img.shields.io/badge/API-API-FF7B00?logo=api&logoColor=white)


## GitHub Activity

- Total Contributions: <!--TOTAL_CONTRIBUTIONS-->
- Current Streak: <!--CURRENT_STREAK-->
- Longest Streak: <!--LONGEST_STREAK-->
const fetchGitHubData = async () => {
  const response = await fetch('https://api.github.com/users/YourGitHubUsername');
  const data = await response.json();

  const totalContributions = data.contributions;
  const currentStreak = data.streak.current;
  const longestStreak = data.streak.longest;

  document.querySelector('#README').innerHTML = document.querySelector('#README').innerHTML
    .replace('<!--TOTAL_CONTRIBUTIONS-->', totalContributions)
    .replace('<!--CURRENT_STREAK-->', currentStreak)
    .replace('<!--LONGEST_STREAK-->', longestStreak);
};

fetchGitHubData();



## Profile

```python
class Profile:
    def __init__(self):
        self.name = "Martin 马丁"
        self.company = "Development Seed"
        self.role = "Software Engineer"
        self.code = ["PHP", "Javascript", "Python"]
        self.tools = ["Laravel", "Codeigniter", "WordPress"]
        self.use = ["vscode", "pycharm", "NuSphere"]
        self.love = "Coding ..."
        self.dark_mode = False
me = Profile()
