# Tabby
# Redis
##  String
序号 | 命令 | 描述
----|------|----
1 | set key value | 设置指定key的值
2 |  get key  | 获取指定key的值
3 | getrange key start end  | 返回key中字符串值的子字符
4 | getset key value  | 将给定key的值设为value,并返回key的旧值
5 | getbit key offset | 对key所存储的字符串值，获取指定偏移量上的位
6 | mget key1[key2...]  | 获取所有（一个或多个）给定key的值
7 | setbit key offset value | 对key所存储的字符串值，设置或清除指定偏移量上的位
8 | setex key seconds value | 将值value关联到Key，并将key的过期时间设为seconds
9 | setnx key value | 只有在key不存在时设置为key的值
10  | setrange key offset value | 用value参数覆盖指定key所存储的字符串值，从偏移量offset开始
11  | strlen key | 返回Key所存储的字符串值的长度
12  | mset key value [key value]  | 同时设置一个或多个key-value对
13  | psetex key  value | 同时设置一个或多个key-value对，当且仅当所有指定的key都不存在
14  | psetex key millisconds value  | 同上，单位是毫秒
15  | incr key  | 将key中存储的数字增一
16  | incrby key increment  | 将key存储的值加上给定的增值量(increment)
17  | incrbyfloat key increment | 将key所存储的值加上给定的浮点增值量(increment)
18  | decr key  | 将key中存储的数字值减一
19  | decrby key decrement  | key存储的值减去给定的减量值
20  | append key value  | 如果key已经存在并且是一个字符串，append 命令将value追加到Key原来的值的末尾
