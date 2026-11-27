# Rongcheer USA website

Mobile-first, swipe-through single-page site for Rongcheer USA (Rongcheer LLC).

- `index.html` — the whole site: 7 full-screen pages, inline CSS and a few lines of JS, no external fonts or libraries
- `assets/` — logo mark, favicon and one compressed machine image (WebP)
- `og.jpg` — preview image used when the link is shared on LinkedIn, WeChat, etc.

Total page weight is about 90 KB, so it loads quickly from any country.

## 网站管理员说明

- 整站就是 `index.html` 一个文件 + `assets` 文件夹，上传到任何网站主机的根目录即可上线。
- 不依赖外部字体或 CDN（Google 字体等在中国打不开），各国访问速度一致。
- 正式上线到 rongcheerusa.com 时，把 `index.html` 里 `og:image` 和 `og:url` 两处地址改成 `https://www.rongcheerusa.com/`。
- 联系按钮直接打开邮件发到 Sales@rongcheerusa.com 和 Recruit@rongcheerusa.com。
