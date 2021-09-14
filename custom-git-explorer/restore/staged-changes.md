---
layout: default
title: staged changes
parent: restore
grand_parent: Custom-Git Explorer
permalink: /explorer/restore/staged-changes
---

# `grestorestaged`
{: .no_toc }

Select the files to unstage.
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## <i class="fas fa-video"></i> Demo
<div class="container">
  <iframe class="responsive-iframe" src="https://www.youtube.com/embed/StaPAVXnAm0?start=166&end=186&controls=0&modestbranding=1&autohide=1&rel=0&fs=1&iv_load_policy=3&widget_referrer=https://custom-git.io" title="gadd demo" frameborder="0" allow="clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## <i class="fas fa-file-alt"></i> Internals
`git restore --staged <filepath>`
<br>restore the contents in the index, i.e. unstage the file <a href="https://git-scm.com/docs/git-restore#_description" target="_blank"><i class="fas fa-external-link-alt"></i></a>
{: .fs-5 .fw-300 }

## <i class="fas fa-code"></i> Implementation
<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fcustom-git%2Fcustom-git-bash%2Fblob%2Fmain%2Fcmd%2Fgrestorestaged&style=github&showBorder=on&showFileMeta=on&showCopy=on"></script>
