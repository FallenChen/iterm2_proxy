# iterm2_proxy


## 临时有效

* $ export http_proxy=socks5://127.0.0.1:1081 # 配置http 代理访问
* $ export https_proxy=socks5://127.0.0.1:1081 # 配置https 代理访问
* $ export all_proxy=socks5://127.0.0.1:1081 # 配置http和https访问

* $ unset http_proxy  # 取消http 代理访问
* $ unset https_proxy # 取消https 代理访问
* $ unset all_proxy # 取消所有代理访问


## git_proxy

* git config --global http.proxy 'socks5://127.0.0.1:1081' 
* git config --global https.proxy 'socks5://127.0.0.1:1081'

* git config --global --unset http.proxy
* git config --global --unset https.proxy

