+++
template = 'home.html'

[extra]
lang = 'zh'

# Show footer in home page
footer = true

# If you don't want to display id/bio/avatar, simply comment out that line
name = "Zumpyx"
id = "zumpyx"
bio = "一蓑烟雨任平生"
avatar = "img/avatar.png"
links = [
    { name = "GitHub", icon = "github", url = "https://github.com/zumpyx" },
    { name = "Bilibili", icon = "bilibili", url = "https://twitter.com/" },
    { name = "Email", icon = "email", url = "mailto:admin@qq.com" },
]

# Show a few recent posts in home page
recent = false
recent_max = 15
recent_more_text = "more »"
date_format = "%Y-%m-%d"
+++

Hi, I'm ...


## 朋友们

{{ collection(file="../collections/blogroll.toml") }}