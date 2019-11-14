+++
title = "homebrew 설치하기"
author = ["Yong-Beom Gwon"]
date = 2014-12-28T00:00:00+09:00
tags = ["linuxbrew"]
draft = false
+++

<style>
  .ox-hugo-toc ul {
    list-style: none;
  }
</style>
<div class="ox-hugo-toc toc">
<div></div>

<div class="heading">Table of Contents</div>

- <span class="section-num">1</span> [관련 링크](#관련-링크)

</div>
<!--endtoc-->

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-13 수 21:18&gt;</span></span>  

1.  아래 스크립트 실행  
    
    ```text
    $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install.sh)"
    ```
2.  환경설정 추가  
    
    ```text
    echo 'eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)' >> ~/.profile
    ```
    
    .profile에 환경설정이 추가된다. PATH 등 brew 관련 환경 변수가셋팅된다


## <span class="section-num">1</span> 관련 링크 {#관련-링크}

<https://docs.brew.sh/Homebrew-on-Linux>
