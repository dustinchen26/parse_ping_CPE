# Parse_RSRP_SINR_PUSCH-power

online tool => https://dustinchen26.github.io/parse_ping_CPE

## Example
```
【How to use】
Please use the command below in MobaxTerm "Session->Shell" to generate the ping response time data: ex:
ping 10.205.164.18 -t | while read pong; do echo "$(date): $pong"; done

【Example input】
Tue Apr  2 15:27:12     2024: Reply from 10.205.164.18: bytes=32 time=24ms TTL=62
Tue Apr  2 15:27:13     2024: Reply from 10.205.164.18: bytes=32 time=24ms TTL=62
Tue Apr  2 15:27:14     2024: Reply from 10.205.164.18: bytes=32 time=23ms TTL=62

【Output】
Ping Delay 時間曲線圖
最小值: 23 ms, 平均值: 23.67 ms, 最大值: 24 ms

```
