# Snort

https://www.openfoundry.org/tw/tech-column/8265--snort-

# Snort (入侵偵測系統)

規則描述如下表：

alert【處理方式】	產生警示的 log

tcp【來源通訊協定】	偵測 TCP 的封包

any【來源 IP】	偵測任何的來源 IP

any【來源 port】	偵測任何的來源埠

any【目的 IP】	偵測任何的目的 IP

5432【目的 port】	僅偵測 5432 埠的封包
