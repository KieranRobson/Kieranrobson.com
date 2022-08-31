# Kieran's Blog

> A place for personal thoughts that you may find interesting!

## Installation

### Docker

```
docker run -d \
--name=KieransBlog \
-p 8082:80 \
kieranr27/blog:latest
```

Using a tool like [Ouroboros](https://github.com/pyouroboros/ouroboros), you can automatically update containers without the need for restarts.

## Built With
- Theme: [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- SSG: [Hugo](https://gohugo.io/)