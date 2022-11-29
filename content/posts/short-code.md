---
author: "Hugo Authors"
title: "Short Code"
date: "2019-03-10"
description: "A brief description of Hugo Shortcodes"
tags: ["shortcodes", "privacy"]
ShowToc: true
---

Hugo ships with several [Built-in Shortcodes](https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes) for rich content, along with a [Privacy Config](https://gohugo.io/about/hugo-and-gdpr/) and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.
<!--more-->

---

## Video

### YouTube

{{< youtube ZJthWmvUzzc >}}

<br>

### Bilibili

{{< bilibili BV1MN4y177PB >}}


### Vimeo Simple Shortcode

{{< vimeo_simple 48912912 >}}

---

## Music

### NetEase

```bash
music server="netease" id="5250122"
```

{{< music server="netease" id="5250122" >}}

```bash
music server="netease" type="playlist" id="60198"
```

{{< music server="netease" type="playlist" id="60198" >}}

### QQ Music

```bash
music auto="https://y.qq.com/n/ryqq/song/004ENQPZ0dHaqy.html"
```

{{< music auto="https://y.qq.com/n/ryqq/song/004ENQPZ0dHaqy.html" >}}


## Code

### Gist

{{< gist spf13 7896402 >}}

### Github Code

{{< ghcode url="https://github.com/gohugoio/hugo/blob/77fc74a5b20f50298ac4a1cd88e436932fc2226f/markup/highlight/highlight.go#L60-L65" >}}

## Social Media

### Twitter

{{< twitter_simple 1085870671291310081 >}}

<br>


---

### Douban

{{< douban type="movie" id="35554292" >}}

{{< douban type="book" id="1084336" >}}


## Notice

{{< notice warning >}}
This is a warning notice. Be warned!
{{< /notice >}}

<br>

{{< notice tip >}}
This is a very good tip.
{{< /notice >}}

{{< notice note >}}
This is a note notice. Be warned!
{{< /notice >}}

{{< notice info >}}
This is a info notice. Be warned!
{{< /notice >}}