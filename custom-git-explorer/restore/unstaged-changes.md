---
layout: default
title: unstaged changes
parent: restore
grand_parent: Custom-Git Explorer
permalink: /explorer/restore/unstaged-changes
---

# `grestore`
{: .no_toc }

Select the unstaged (working tree) files to restore to HEAD.
<br>It provides a prompt before removing the changes.
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## <i class="fas fa-video"></i> Demo
<iframe width="600" height="337.5" src="https://www.youtube.com/embed/StaPAVXnAm0?start=166&end=186&controls=0&modestbranding=1&disablekb=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## <i class="fas fa-file-alt"></i> Internals
`git restore <filepath>`
<br>restore working tree files <a href="https://git-scm.com/docs/git-restore" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }

## <i class="fas fa-code"></i> Implementation
<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fcustom-git%2Fcustom-git-bash%2Fblob%2Fmain%2Fcmd%2Fgrestore&style=github&showBorder=on&showFileMeta=on&showCopy=on"></script>
