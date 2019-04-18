# zblog

## 项目介绍
zblog-hexo

#### zblog博客地址
    http://zuot.gitee.io/zblog

####
    hexo

#### 评论系统 - 来必力
    <!-- 来必力City版安装代码 -->
    <div id="lv-container" data-id="city" data-uid="MTAyMC80MTc2OC8xODMxNA==">
    	<script type="text/javascript">
       (function(d, s) {
           var j, e = d.getElementsByTagName(s)[0];

           if (typeof LivereTower === 'function') { return; }

           j = d.createElement(s);
           j.src = 'https://cdn-city.livere.com/js/embed.dist.js';
           j.async = true;

           e.parentNode.insertBefore(j, e);
       })(document, 'script');
    	</script>
    <noscript> 为正常使用来必力评论功能请激活JavaScript</noscript>
    </div>
    <!-- City版安装代码已完成 -->


#### 百度统计 satott/S6
##### https://tongji.baidu.com/web/homepage/index
    <script>
    var _hmt = _hmt || [];
    (function() {
      var hm = document.createElement("script");
      hm.src = "https://hm.baidu.com/hm.js?d2a4aaa23cf21744067bec574ea39e2a";
      var s = document.getElementsByTagName("script")[0];
      s.parentNode.insertBefore(hm, s);
    })();
    </script>


#### footer 显示 Hexo
文件路径：themes/next6/layout/_partials/footer.swig  

	{% if theme.footer.powered.enable %}
	  <div class="powered-by">{#
	  #}{{ __('footer.powered', next_url('https://hexo.io', 'Hexo', {class: 'theme-link'})) }}{#
	  #}{% if theme.footer.powered.version %} v{{ hexo_env('version') }}{% endif %}{#
	 #}</div>
	{% endif %}

	{% if theme.footer.powered.enable and theme.footer.theme.enable %}
	  <span class="post-meta-divider">|</span>
	{% endif %}

	{% if theme.footer.theme.enable %}
	  <div class="theme-info">{#
	  #}{{ __('footer.theme') }}  {{ next_url('https://theme-next.org', 'NexT.' + theme.scheme, {class: 'theme-link'}) }}{#
	  #}{% if theme.footer.theme.version %} v{{ version }}{% endif %}{#
	#}</div>
	{% endif %}
	

#### GitHub 域名解析

	zsatot
	/
	zlove.github.io
	zsatot
	/
	zwww.github.io

	satott
	/
	tozuo.github.io
	satott
	/
	tzuo.github.io


	tozuo
	/
	zlink.github.io
	tozuo
	/
	tblog.github.io

