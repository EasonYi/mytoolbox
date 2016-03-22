Q：为什么需要禁止Mac休眠？
A：Mac为了省电和账号安全，会在用户连续不操作电脑一段时间后自动进入休眠状态。但是，如果你希望在你离开Mac的时候，Mac能够继续为你工作（比如：安装一堆软件，下载一个大片，启动一个服务等），那么就需要禁止Mac休眠。

搜索caffeine：
➜ brew search caffeine
Caskroom/cask/caffeine

查看caffeine：
➜ brew cask info caffeine
caffeine: 1.1.1
Caffeine
http://lightheadsw.com/caffeine/
Not installed
https://github.com/caskroom/homebrew-cask/blob/master/Casks/caffeine.rb
==> Contents
Caffeine.app (app)

安装caffeine：
➜ brew cask install caffeine
==> Downloading http://lightheadsw.com/files/releases/com.lightheadsw.Caffeine/Caffeine1.1.1.zip
######################################################################## 100.0%
==> Verifying checksum for Cask caffeine
==> Symlinking App 'Caffeine.app' to '/Users/eason/Applications/Caffeine.app'
🍺 caffeine staged at '/opt/homebrew-cask/Caskroom/caffeine/1.1.1' (13 files, 416K)

启动caffeine：
1. Mac OS X 常用软件 > image2016-3-22 16:1:7.png
