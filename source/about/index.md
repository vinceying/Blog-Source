---
title: about
layout: about
date: 2020-04-04 21:45:58
---
## 关于本站

之前使用的是 Cloud Studio 的 Pages 服务，可以通过使用动态网站，使用WordPress来搭建我的博客，但是后来由于相关服务的升级， Cloud Studio 停止了相关服务，网站也没有写什么内容。

由于我之前所在的两个论坛都相继关闭，我的一些帖子都没有备份。这对我来说是一大损失，于是打算搭建本站。使用 Github Pages+Hexo 框架，目的就是存一些我的文章和帖子。

## 关于我&愿望

* 前技德 Remix 论坛超级版主 梦想赞助商
* 前智友论坛（安智）版主 撰稿
* 经历过几个小项目
* 伪果粉

还在路上，希望能够一直热爱一些我所热爱的东西，也希望可以更加自律。同时也在培养自己的版权意识。之前也说了，主要是记录一下自己的文章和一些内容，佛系青年的佛系网站，**没有追求什么访客量**，当然也不会有什么访客量，主要为了给自己留点回忆。

## 一言，用代码表达语言的魅力

<p id="hitokoto">:D 获取中...</p>
<script>
  fetch('https://v1.hitokoto.cn')
    .then(response => response.json())
    .then(data => {
      const hitokoto = document.getElementById('hitokoto')
      hitokoto.innerText = data.hitokoto
      })
      .catch(console.error)
</script>

## 最后更新与运行时间
最后更新于2020/5/24，更新内容为更新友链界面重新整合。 

<div>
  <span id="timeDate">载入天数...</span>
  <span id="times">载入时分秒...</span>
  <script>
  var now = new Date();
  function createtime(){
      var grt= new Date("04/05/2020 00:00:00");
      now.setTime(now.getTime()+250);
      days = (now - grt ) / 1000 / 60 / 60 / 24;
      dnum = Math.floor(days);
      hours = (now - grt ) / 1000 / 60 / 60 - (24 * dnum);
      hnum = Math.floor(hours);
      if(String(hnum).length ==1 ){
          hnum = "0" + hnum;
      }
      minutes = (now - grt ) / 1000 /60 - (24 * 60 * dnum) - (60 * hnum);
      mnum = Math.floor(minutes);
      if(String(mnum).length ==1 ){
                mnum = "0" + mnum;
      }
      seconds = (now - grt ) / 1000 - (24 * 60 * 60 * dnum) - (60 * 60 * hnum) - (60 * mnum);
      snum = Math.round(seconds);
      if(String(snum).length ==1 ){
                snum = "0" + snum;
      }
      document.getElementById("timeDate").innerHTML = "本站运行&nbsp"+dnum+"&nbsp天";
      document.getElementById("times").innerHTML = hnum + "&nbsp小时&nbsp" + mnum + "&nbsp分&nbsp" + snum + "&nbsp秒";
  }
  setInterval("createtime()",250);
  </script>
</div>

## 相关内容及信息