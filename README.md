# quangthangcoder

![Stars](https://img.shields.io/github/stars/quangthangcoder?style=for-the-badge&color=yellow)
![Followers](https://img.shields.io/github/followers/quangthangcoder?style=for-the-badge&color=blue)
![Profile Views](https://komarev.com/ghpvc/?username=quangthangcoder&style=for-the-badge&color=brightgreen)

## About Me

Im **quangthangcoder**, Real Name Is **Trương Quang Thắng**, Living In **Bắc Đông Quan, Hưng Yên, Việt Nam**.  
Passionate about **Software Protection, Obfuscation, Reverse Engineering, and Security Research**.

---

```js
class QuangThangCoder {
    constructor() {
        this.username = "quangthangcoder"
        this.realName = "Trương Quang Thắng"
        this.location = "Bắc Đông Quan, Hưng Yên, Việt Nam"
        this.focus = [
            "JavaScript Obfuscation",
            "Python Obfuscation",
            "Anti-Tamper",
            "Anti-Debug",
            "Reverse Engineering"
        ]
        this.tools = [
            "CryptaJS",
            "Tsunami",
            "PyHigh",
            "Custom Obfuscation Engine"
        ]
    }

    about() {
        return `
        Name: ${this.realName}
        Username: ${this.username}
        Location: ${this.location}
        Focus: ${this.focus.join(", ")}
        Tools: ${this.tools.join(", ")}
        `
    }
}

const me = new QuangThangCoder()
console.log(me.about())
