AX9000 openclash 专属固件
默认 IP: 10.10.10.10

密码: 没有密码，其他涉及默认密码的都是 password

特性
与 common 版相比，删除了 ssrp，追求极简。

DNS 流向

                          主要
AdGuardHome[53, no cache] ────⟶ openclash[7874] ────⟶ mosdns[5335, cache]
                          |                           ↑
                          └───────────────────────────┘
                                      备用
其他部分参考 lede-common-x86-amd64，基本一致。
