<h1>Hi there, I'm Aleksandar Ciric 👋</h1> 

![](https://komarev.com/ghpvc/?username=alexmeanpug)

```php
class AboutMe {
    private $name;
    private $country;
    private $experience;
    private $role;
    private $favoriteFood;

    public function __construct($name, $country, $experience, $role, $favoriteFood) {
        $this->name = $name;
        $this->country = $country;
        $this->experience = $experience;
        $this->role = $role;
        $this->favoriteFood = $favoriteFood;
    }

    public function introduce() {
        return "👋 Hello! I'm {$this->name} from {$this->country},
                a {$this->experience}+ years experienced {$this->role}
                and a burger lover 🍔.";
    }
}

$aleksandar = new AboutMe("Aleksandar Ciric", "Serbia", 6, "WordPress developer and frontend developer", "burger");

echo $aleksandar->introduce();
```

![GitHub stats](https://github-readme-stats-git-master-alexmeanpug.vercel.app/api?username=alexmeanpug&show=reviews,prs_merged,prs_merged_percentage&hide=stars,issues&theme=dark&show_icons=true&rank_icon=percentile)
![Top Langs](https://github-readme-stats-git-master-alexmeanpug.vercel.app/api/top-langs/?username=alexmeanpug&layout=compact&theme=dark&show_icons=true)
