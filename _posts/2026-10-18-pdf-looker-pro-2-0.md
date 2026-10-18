---
layout: news
title: "PDF Looker Pro 2.0 — a PDF reader and annotator, written from scratch"
date: 2026-10-18
category: news
author: Chengxi Zhang
meta: Release
---

<figure class="post-figure">
  <a href="https://dongfangxy.github.io/pdf-looker-pro/">
    <img src="/pdf-looker-pro/assets/app.png" width="1200" height="750" loading="lazy"
         alt="The PDF Looker Pro window: thumbnails and an annotation list on the left, and a page carrying a typewriter note, a highlight, a standard stamp and a distance measurement.">
  </a>
  <figcaption>
    The application as it is: a typewriter note, a text highlight, a standard stamp and a
    distance measurement, beside the list of annotations on the page. They are written
    into the PDF itself, so Acrobat or Preview shows the same marks.
  </figcaption>
</figure>

I have released **PDF Looker Pro 2.0**, a desktop PDF reader and annotator for Windows
(MIT, portable, no installer). Rendering is pdf.js; two things that had no ready-made
component are implemented from the bytes up — a writer that puts annotations *into* the
PDF so other readers see them too, and a whole-document rewrite that makes page editing
possible at all.

Version 2.0 closes four areas of work. **Reading**: continuous scroll with page
virtualisation, four view modes, fit-to-visible-area, a magnifier, printing with a page
range. **Document editing**: rotate, delete, insert, extract, crop, reorder, merge
another file in, and build a document from images. **Annotating**: eleven markup and
shape types, six standard stamps, replies written as real `/IRT` threads, flattening, and
an annotation summary. **Search**: results grouped by page, folder search across
documents, and saved searches.

It also fixes a defect worth naming: an annotation written into a file could not
afterwards be removed. The writer appended to the page's `/Annots` without dropping what
it had written before, so a deletion was undone by the next save and every save added
another copy of every mark. That chain now has its own regression test.

[Project page and download](https://dongfangxy.github.io/pdf-looker-pro/) ·
[Source on GitHub](https://github.com/dongfangxy/pdf-looker-pro) ·
[Release notes](https://github.com/dongfangxy/pdf-looker-pro/releases/tag/v2.0.0)

已发布 **PDF Looker Pro 2.0**：一个从零写起的 Windows PDF 阅读与批注工具。批注直接写进 PDF
文件（增量更新，不改动原始字节），页面编辑走整份重写路径，因此旋转、删页、合并都能真正落到
文件里。2.0 同时修复了「存进去的批注删不掉」这一类缺陷——写入器过去只追加、不摘除上一次写入
的对象。项目页与下载见上方链接，源码为 MIT。
