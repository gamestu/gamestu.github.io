---
layout: post
title: "常在terminal與finder之間切換，你需要這個Alfred workflow"
date: 2014-01-20 01:54:03 +0800
comments: true
categories:  工作流程 alfred
---

最近開始熟悉terminal的操作，沒辦法實在太多工具是command line tool了。於是發現常常為了在terminal打一個指令，光是在terminal找到資料夾就得花不少時間。或者是terminal已經在這個位置，想用finder打開又要再重新尋找一次。

上網找了一下方法，發現最棒的是這個Alfred的workflow──[Alfred terminalfinder][1]。

<!-- more -->

使用上非常簡單，只要叫出Alfred，輸入：

1. ft : 表示finder to terminal，將目前finder的資料夾在terminal打開
2. tf : 表示terminal to finder，將目前terminal的資料夾在finder打開
3. fi : 如果你是iTerm的愛用者，這是finder to iTerm
4. if : iterm to finder。

就這樣，非常簡單。

當然Alfred要用到workflow是要花錢的，如果真的不想花錢。

在finder中打開的指令是這樣：

```open -a Finder ./```

至於在finder資料夾上按右鍵->open in terminal，可以參考這篇教學：

[Open terminal here in Mac OS finder][2]

Enjoy it.

[1]:https://github.com/LeEnno/alfred-terminalfinder
[2]:http://stackoverflow.com/questions/420456/open-terminal-here-in-mac-os-finder


