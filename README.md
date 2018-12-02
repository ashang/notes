# notes

3996

commit/7497a834527f54d1e7005bb854239261466711b5

https://snapcraft.io/microk8s

cd3d7b19fd9fbd54730216bcfe846793650a9084

cd9822006ec76225f21f7f3fb5bf506019c4a87c

75ca440042d0e91c36b5d4fe780a49f37b0778a6

fcaf35356bd8691ca30651e561db723b21bff054

8c2af954ff8538f4677c5f6052af6ca5b8b4e255


https://wiki.archlinux.org/index.php/Multiboot_USB_drive#Configuring_GRUB

https://github.com/ashang/vagrant-vbguest         

81269c0694fd32462357d3461f5ed01fd0b4e4ac

https://www.voyax.me/posts/95b9b99d/

http://www.cplusplus.com/reference/

http://www.cplusplus.com/articles/E3wTURfi/

http://www.cplusplus.com/articles/y807M4Gy/

http://www.cplusplus.com/articles/Lz86b7Xj/

http://www.cplusplus.com/articles/jLzyhbRD/

http://www.cplusplus.com/articles/z6vU7k9E/

http://www.cplusplus.com/articles/j3wTURfi/

http://www.cplusplus.com/articles/Gw6AC542/

https://www.youtube.com/watch?v=1PJix23IeF8

https://code.visualstudio.com/docs/setup/linux#_visual-studio-code-is-unable-to-watch-for-file-changes-in-this-large-workspace-error-enospc

https://gohugo.io/getting-started/directory-structure/

https://en.wikipedia.org/wiki/Buddy_(software)

https://gohugo.io/content-management/static-files/

https://gohugo.io/getting-started/usage/

https://support.mozilla.org/en-US/kb/refresh-firefox-reset-add-ons-and-settings?redirectlocale=en-US&redirectslug=reset-firefox-easily-fix-most-problems

https://gohugo.io/hugo-pipes/introduction/

https://gohugo.io/content-management/sections/

deploy:

     type: git

     repo: https://github.com/xx/zz
     branch: master


npm install hexo-deployer-git --save

https://go.kieran.top/post/45/

https://en.wikipedia.org/wiki/PMAC_(cryptography)

    在导航栏添加点东西
        例如我添加了一个更新日志的模块。
        在主题的配置文件中，menu添加一栏：Board: /board。
        然后在source中添加一个board，即对应上面的名字。然后再创建一个index.md，里面可以写你想写的内容。
        在主题的hueman/langulages/zh-CN.yml中的index适当的位置加：board: '更新日志'，位置和名字是你自己设定。
        重新部署，然后就OK了
    在侧边栏添加点东西
        回到你的主题的配置文件中，找到widgets一栏，在你要添加的位置处添加一条你自定义的名称。例如我的叫communiation且放在了第二行。
        在上面所提到的zh-CN.yml文件中找到sidebar一栏，添加communiation: '你要设的名称'。
        在hueman/layout/widget中添加一个communiation.ejs,填入模板

    <% if (site.posts.length) { %>
        <div class="widget-wrap widget-list">
            <h3 class="widget-title"><%= __('sidebar.communiation') %></h3>
            <div class="widget">
                <!--这里添加你要写的内容-->
            </div>
        </div>
    <% } %>

9. 添加RSS

    先安装rss相关插件：npm i hexo-generator-feed
    在你的项目的_config.yml配置文件下找到Extensions添加如下内容：
    # Extensions #插件和主题 ## Plugins: https://hexo.io/plugins/ ## Themes: https://hexo.io/themes/ #RSS订阅 plugin: - hexo-generator-feed #Feed Atom feed: type: atom path: atom.xml limit: 20
    进入到你的主题的配置文件下，找到你的放rss的位置，添加/atom.xml即可。
    
    http://lewis.suclub.cn/2018/08/08/improve-github-clone-speed/
    
    http://haojen.github.io/2016/07/30/%E4%B8%BA%E8%87%AA%E7%94%B1%E4%B9%8B%E5%9C%B0/
    
    https://www.voyax.me/posts/95b9b99d/
    https://jaredforsyth.com/hexo-admin/
    
    https://hexo.io/docs/setup
    
    https://help.github.com/articles/using-a-custom-domain-with-github-pages/
    
    https://help.github.com/articles/creating-a-custom-404-page-for-your-github-pages-site/
    
    https://github.com/ashang/atbb/blob/master/_config.yml
    
    https://console.cloud.tencent.com/domain/manage/thepro.xyz/basicinfo
    
    https://github.com/ashang/ashang.github.io/blob/master/404.html
    
    https://en.wikipedia.org/wiki/CBC-MAC
    
    https://en.wikipedia.org/wiki/One-key_MAC
    
    10.10.50.11/bugs/show_bug.cgi?id=9674
    https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Source_Code
    
