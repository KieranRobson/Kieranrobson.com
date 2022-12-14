<div align="center">

## My Site

A place for personal thoughts and documetation that you may find interesting!

<img src="https://img.shields.io/github/workflow/status/KieranRobson/Blog/ci?style=for-the-badge">
<img src="https://img.shields.io/badge/HUGO-0.102.0-blue?style=for-the-badge&logo=HUGO" />
<img src="https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge">
</div align="center">

---

## Installation
### Docker

```
docker run -d \
--name=Site \
-p 8083:80 \
kieranr27/blog:latest
```

Using a tool like [Ouroboros](https://github.com/pyouroboros/ouroboros), you can automatically update containers without the need for restarts.
### Manual
- Clone the repo
- Run `hugo server`
- Head to `localhost:1313`
- Make some changes and watch them change!

## Built With
- Theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- SSG: [Hugo](https://gohugo.io/)
