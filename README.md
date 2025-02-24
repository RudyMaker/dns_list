
# dns-outside
描述：CN地区以外的常见DNS列表,包含了常见的非中国地区 DNS 提供商的域名（如 Google、Cloudflare 等）和对应的 IP 地址。

用途：这个配置适用于OpenClash，用于自定义分流规则。

url: [https://raw.githubusercontent.com/RudyMaker/dns_outside/refs/heads/main/dns-outsite.yaml](https://raw.githubusercontent.com/RudyMaker/dns_outside/refs/heads/main/dns-outsite.yaml)


# dns-cn
描述：CN地区的常见DNS列表,包含了常见的中国地区 DNS 提供商的域名（包含阿里、腾讯 各地运营商 等）和对应的 IP 地址。

用途：这个配置适用于OpenClash，用于自定义分流规则。

url: [https://raw.githubusercontent.com/RudyMaker/dns_outside/refs/heads/main/dns-outsite.yaml](https://raw.githubusercontent.com/RudyMaker/dns_list/refs/heads/main/dns-cn.yaml)

# 分流
实际上一般只需要dns-outside.yaml将国外的DNS分流出去即可，国内的不设置，直接直连或者省事用wan口拨号的DNS（其实按道理wan口的DNS才是国内最快的）。

openclash的设置可以照这Aethersailor的教程来：[OpenClash-设置方案](https://github.com/Aethersailor/Custom_OpenClash_Rules/wiki/OpenClash-%E8%AE%BE%E7%BD%AE%E6%96%B9%E6%A1%88)


# 感谢 
[Aethersailor/Custom_OpenClash_Rules](https://github.com/Aethersailor/Custom_OpenClash_Rules?tab=readme-ov-file)
