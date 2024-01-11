---
marp: true
theme: default
header: ''
footer: ''
paginate: true
size: 16:9
style: |
    @import 'https://fonts.googleapis.com/css2?family=Droid+Sans&display=swap';

    body {
    font-family: 'Droid Sans', sans-serif;
    }

    section h1 {
    font-size: 64px;
    color: #70a0e0;
    }

    h2 {
    color: #70a0e0;
    border-bottom: 2px solid #70a0e0;
    padding-bottom: 5px;
    }

    p {
    font-size: 23px;
    }

    li {
    font-size: 23px;
    }

    table td, table th {
    font-size: 23px;
    }

    .item-container ul {
    list-style-type: none;
    }

    .item-container ul li::before {
    content: '';
    display: inline-block;
    width: 1em;
    height: 1em;
    background-color: #70a0e0;
    margin-right: 0.5em;
    vertical-align: middle;
    }

    .item-container ul ul li::before {
    content: '•';
    color: #70a0e0;
    margin-right: 0.5em;
    }

    .red {
    color: #e07070;
    }

    .blue {
    color: #70a0e0;
    }

    .green {
    color: #93c870;
    }

math: katex

---

# 雑誌会

石川健太郎
2024 年 1 月 15 日

## Formalizing and solving the problem of clustering in MCDA

Patrick Meyer, Alexandru-Liviu Olteanu
11 January 2013

---

## ABSTRACT

- 多基準意思決定では, データ分析で用いられるような類似度や距離などとは異なる比較方法が考えられる

- 多基準意思決定に特有の概念を用いて, 多基準意思決定問題におけるクラスタリングの問題を定式化し, そこから得られる構造について

---

## 1. Introduction

