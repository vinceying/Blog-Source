---
 title: 常用内容
 date: 2020-04-05 01:25:08 
 banner_img: https://cdn.vince.pub/blog-file/photo/debug.png 
---
####  网站相关

<div class="row links">
  <div class="card col-lg-4 col-md-6 col-sm-12">
      <a href="https://www.vince.pub/" class="card-body hover-with-bg" target="_blank" rel="noopener">
        <div class="card-content">          
  <div class="link-text">
            <div class="link-title">主站</div>
            <div class="link-intro">个人主站</div>
          </div>
        </div>
      </a>
    </div>
  <div class="card col-lg-4 col-md-6 col-sm-12">
      <a href="https://cloud.vince.pub/" class="card-body hover-with-bg" target="_blank" rel="noopener">
        <div class="card-content">          
  <div class="link-text">
            <div class="link-title">私有云</div>
            <div class="link-intro">个人私有云</div>
          </div>
        </div>
      </a>
    </div>
  <div class="card col-lg-4 col-md-6 col-sm-12">
      <a href="https://file.vince.pub/" class="card-body hover-with-bg" target="_blank" rel="noopener">
        <div class="card-content">          
  <div class="link-text">
            <div class="link-title">文件</div>
            <div class="link-intro">个人文件镜像站</div>
          </div>
        </div>
      </a>
    </div>
  <div class="card col-lg-4 col-md-6 col-sm-12">
      <a href="https://tongji.baidu.com/web/10000019662/homepage/index" class="card-body hover-with-bg" target="_blank" rel="noopener">
        <div class="card-content">          
  <div class="link-text">
            <div class="link-title">百度统计</div>
            <div class="link-intro">网站统计服务</div>
          </div>
        </div>
      </a>
    </div>

<div class="card col-lg-4 col-md-6 col-sm-12">
      <a href="https://leancloud.cn/dashboard/applist.html#/apps" class="card-body hover-with-bg" target="_blank" rel="noopener">
        <div class="card-content">          
  <div class="link-text">
            <div class="link-title">Lean Cloud</div>
            <div class="link-intro">评论与说说管理</div>
          </div>
        </div>
      </a>
    </div>

<div class="card col-lg-4 col-md-6 col-sm-12">
      <a href="https://www.iconfont.cn/" class="card-body hover-with-bg" target="_blank" rel="noopener">
        <div class="card-content">          
  <div class="link-text">
            <div class="link-title">Iconfont</div>
            <div class="link-intro">图标项目管理</div>
          </div>
        </div>
      </a>
    </div>
</div>

****
</br>

#### 插件

<div class="content">
        <div class="ah-tab-wrapper">
            <div class="ah-tab">
                <a class="ah-tab-item" data-ah-tab-active="true" href="">icheck-material</a>
                <a class="ah-tab-item" href="">其它插件</a>
            </div>
        </div>
        <div class="ah-tab-content-wrapper">
            <div class="ah-tab-content" data-ah-tab-active="true">
            <iframe src="https://i.vince.pub/website/icheck-material.html" width="100%" height="400" name="topFrame" scrolling="yes"  noresize="noresize" frameborder="0" id="topFrame"></iframe>
            </div>
            <div class="ah-tab-content">
                <strong>以下为部分插件使用说明</strong>
                <h2> </h2>
                <li><strong><a href="https://github.com/killia15/ProgressCircle" target="_blank" rel="noopener">ProgressCircle</a></strong></li>
                <li><strong><a href="https://github.com/bantikyan/icheck-material/" target="_blank" rel="noopener">Icheck-material</a></strong></li>
                <li><strong><a href="https://github.com/mohammad-hammal/bootsrap4-buttons-extended" target="_blank" rel="noopener">bootsrap4-buttons-extended</a></strong></li>
            </div>
        </div>
    </div>
    <script src="https://cdn.staticfile.org/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://cdn.vince.pub/blog-file/js/horizontalmenu.js"></script>
    <script>
        $(function() {
            $('.ah-tab-wrapper').horizontalmenu({
                itemClick: function(item) {
                    $('.ah-tab-content-wrapper .ah-tab-content').removeAttr('data-ah-tab-active');
                    $('.ah-tab-content-wrapper .ah-tab-content:eq(' + $(item).index() + ')').attr('data-ah-tab-active', 'true');
                    return false; //if this finction return true then will be executed http request
                }
            });
        });
    </script>

