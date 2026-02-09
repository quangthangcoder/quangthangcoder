# quangthangcoder

![Stars](https://img.shields.io/github/stars/quangthangcoder?style=for-the-badge&color=yellow)
![Followers](https://img.shields.io/github/followers/quangthangcoder?style=for-the-badge&color=blue)
![Profile Views](https://komarev.com/ghpvc/?username=quangthangcoder&style=for-the-badge&color=brightgreen)

---

## System Status

![GitHub Stats](https://github-readme-stats-sigma-five.vercel.app/api?username=quangthangcoder&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=quangthangcoder&layout=compact&theme=tokyonight&hide_border=true)

---

## About

Im **quangthangcoder**  
Real Name: **Trương Quang Thắng**  
Location: **Bắc Đông Quan, Hưng Yên, Việt Nam**

---

## Profile

```js
class QuangThangCoder {
    constructor() {
        this.username = "quangthangcoder"
        this.realName = "Trương Quang Thắng"
        this.location = "Bắc Đông Quan, Hưng Yên, Việt Nam"

        this.languages = {
            Python: "Advanced",
            JavaScript: "Advanced",
            NextJS: "Intermediate",
            HTML: "Advanced"
        }

        this.hobbies = [
            "Play Games",
            "Watch Movies",
            "Coding"
        ]
    }

    dump() {
        return {
            user: this.username,
            name: this.realName,
            location: this.location,
            languages: this.languages,
            hobbies: this.hobbies
        }
    }
}

const runtime = new QuangThangCoder()
console.log(runtime.dump())
