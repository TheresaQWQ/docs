---
id: intro
sidebar_label: 简介
title: ""
sidebar_position: 1
hide_title: true
slug: /
---

<p align="center">
    <a href="https://ikaros.run" target="_blank" rel="noopener noreferrer">
        <img width="100" src="https://ikaros.run/logo.png" alt="Ikaros logo" />
    </a>
</p>

<p align="center"><b>Ikaros</b> [Ίκαρος]，专注于ACGMN的个人内容管家(CMS)。</p>

<p align="center">ACGMN全拼是：Anime(动画) + Comic(漫画) + Game(游戏) + Music(音乐) + Novel(小说)</p>

<p align="center">
<a href="https://github.com/ikaros-dev/ikaros/releases"><img alt="Github Releases" src="https://img.shields.io/github/v/release/ikaros-dev/ikaros?include_prereleases&style=flat-square" /></a>
<a href="https://github.com/ikaros-dev/ikaros/stargazers"><img alt="GitHub Stargazers" src="https://img.shields.io/github/stars/ikaros-dev/ikaros.svg?style=flat-square&label=Stars&logo=github" /></a>
<a href="https://github.com/ikaros-dev/ikaros/issues"><img src="https://img.shields.io/github/issues/ikaros-dev/ikaros?color=blue&style=flat-square"/></a>
<a href="https://hub.docker.com/r/ikarosrun/ikaros"><img alt="Docker pulls" src="https://img.shields.io/docker/pulls/liguohaocn/ikaros?style=flat-square" /></a>
<a href="https://app.codecov.io/github/ikaros-dev/ikaros"><img alt="code coverage" src="https://img.shields.io/codecov/c/github/ikaros-dev/ikaros/master?style=flat-square" /></a>
<a href="https://github.com/ikaros-dev/ikaros/commits"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/ikaros-dev/ikaros.svg?style=flat-square" /></a>
<a href="https://github.com/ikaros-dev/ikaros/actions"><img alt="GitHub workflow build status" src="https://img.shields.io/github/actions/workflow/status/ikaros-dev/ikaros/ikaros-server-ci.yml?branch=master&style=flat-square" /></a>
<br />
</p>

---

## 快速开始

```bash
docker run \
  -it -d \
  --name ikaros \
  -p 9999:9999 \
  -v ~/.ikaros:/root/.ikaros \
  ikarosrun/ikaros:0.2.0 \
  --ikaros.security.initializer.superadminusername=tomoki \
  --ikaros.security.initializer.superadminpassword=tomoki
```

以上仅作为体验使用，详细部署文档请查阅：<https://docs.ikaros.run/getting-started/install/docker-compose>

## 许可证

[![license](https://img.shields.io/github/license/ikaros-dev/ikaros.svg?style=flat-square)](https://github.com/ikaros-dev/ikaros/blob/master/LICENSE)

ikaros 使用 GPL-v3.0 协议开源，请遵守开源协议。

## 贡献

参考 [CONTRIBUTING](https://github.com/ikaros-dev/ikaros/blob/master/CONTRIBUTING.MD)。

## 状态

![Repobeats analytics](https://repobeats.axiom.co/api/embed/f7285853048ff09f313f6483901e2af0e638f666.svg "Repobeats analytics image")