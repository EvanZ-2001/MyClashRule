# MyClashRule
针对自己定制的Clash规则，主要分流规则来源于网络经典项目（如ACL4SSR），此外便于添加自定义的规则

## 使用方法

- 使用在线订阅转换工具 <[https://sub.v1.mk/](https://sub.v1.mk/)>，选择上传远程配置中填入本项目中my_config的raw链接
- ~~启动本地订阅转换后端程序subconverter~~
- ~~打开订阅转换前端网页（如<https://sub-web.netlify.app/>），在“远程配置”中填入项目中“my_config”文件的Raw链接（可能需要使用镜像链接，本地subconverter无法直连Github）~~

## 项目文件说明
根目录下my_config文件就是订阅链接中要用的配置文件，根目录下share_remote_config_example文件是配置文件的模板，目录Ruleset保存的是自己修改过的分流规则（主体部分来源于网络分享，但根据自己的需求进行了少许修改）
