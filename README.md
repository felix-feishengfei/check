
# About

This project is inspired by [free](https://github.com/freefq/free) and [check](https://github.com/yeahwu/check) to filter free [v2](https://github.com/v2fly/v2ray-core) site periodically by [docker-v2](https://hub.docker.com/r/v2ray/official)

    
|    | id                   | addr                | ip             | chatgpt          | netflix          | tiktok           |
|---:|:---------------------|:--------------------|:---------------|:-----------------|:-----------------|:-----------------|
|  0 | [3](config/3.json)   | 156.225.67.147      | 154.84.1.178   | Yes (Region: NL) | Originals Only   | Yes (Region: NL) |
|  1 | [4](config/4.json)   | 156.225.67.40       | 154.84.1.16    | Yes (Region: NL) | Originals Only   | Yes (Region: NL) |
|  2 | [12](config/12.json) | 120.210.205.220     | 51.89.40.143   | IP is BLOCKED    | No               | Yes (Region: GB) |
|  3 | [21](config/21.json) | cf.noaries.de       | 107.189.28.253 | Yes (Region: LU) | Originals Only   | Yes (Region: LU) |
|  4 | [22](config/22.json) | 172.99.188.99       | 172.99.188.99  | Yes (Region: NL) | Originals Only   | Yes (Region: NL) |
|  5 | [24](config/24.json) | cfcdn.sanfencdn.net | 54.183.95.36   | Failed           | Yes (Region: US) | Yes (Region: US) |
|  6 | [28](config/28.json) | 172.99.188.99       | 172.99.188.99  | Yes (Region: NL) | Originals Only   | Yes (Region: NL) |

## Valid
```
vmess://eyJhZGQiOiAiMTU2LjIyNS42Ny4xNDciLCAidiI6ICIyIiwgInBzIjogImdpdGh1Yi5jb20vZnJlZWZxIC0gXHU1MzU3XHU5NzVlICAzIiwgInBvcnQiOiA1MTk0OCwgImlkIjogIjkzNTAzZGQ1LTI0NWEtNGViMS1hZTJhLTU3YWI5ZjJiM2MyOSIsICJhaWQiOiAiNjQiLCAibmV0IjogInRjcCIsICJ0eXBlIjogIiIsICJob3N0IjogIiIsICJwYXRoIjogIi8iLCAidGxzIjogIiJ9
vmess://eyJhZGQiOiAiMTU2LjIyNS42Ny40MCIsICJhaWQiOiA2NCwgImhvc3QiOiAiIiwgImlkIjogImRlNDkxODAyLTIzM2UtNDdmMi04YzZjLWQxOWJjZjViZDU2YiIsICJuZXQiOiAidGNwIiwgInBhdGgiOiAiIiwgInBvcnQiOiAzNTY4NSwgInBzIjogImdpdGh1Yi5jb20vZnJlZWZxIC0gXHU1MzU3XHU5NzVlICA0IiwgInRscyI6ICIiLCAidHlwZSI6ICJhdXRvIiwgInNlY3VyaXR5IjogImF1dG8iLCAic2tpcC1jZXJ0LXZlcmlmeSI6IHRydWUsICJzbmkiOiAiIn0=
vmess://eyJhZGQiOiAiMTIwLjIxMC4yMDUuMjIwIiwgImFpZCI6IDY0LCAiaG9zdCI6ICIiLCAiaWQiOiAiNDExZGFjZDYtMDMwYi00MWFkLWJmYjYtM2E4MjJlYzgzMDE0IiwgIm5ldCI6ICJ0Y3AiLCAicGF0aCI6ICIiLCAicG9ydCI6IDM2OTE4LCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTViODlcdTVmYmRcdTc3MDFcdTU0MDhcdTgwYTVcdTVlMDJcdTc5ZmJcdTUyYTggMTIiLCAidGxzIjogIiIsICJ0eXBlIjogImF1dG8iLCAic2VjdXJpdHkiOiAiYXV0byIsICJza2lwLWNlcnQtdmVyaWZ5IjogdHJ1ZSwgInNuaSI6ICIifQ==
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmRDbG91ZEZsYXJlXHU4MjgyXHU3MGI5IDIxIiwgImFkZCI6ICJjZi5ub2FyaWVzLmRlIiwgInBvcnQiOiAiODA4MCIsICJpZCI6ICI0ZjdkNWQ0My0yMjZlLTQ4ZDgtOWRmMC01ZThiZjlmNzcyODgiLCAiYWlkIjogIjAiLCAic2N5IjogImF1dG8iLCAibmV0IjogIndzIiwgInR5cGUiOiAibm9uZSIsICJob3N0IjogImJ1eXZtLmNsb3VkZmxhcmUucXVlc3QiLCAicGF0aCI6ICIvYXJpZXM_ZWQ9MjA0OCIsICJ0bHMiOiAiIiwgInNuaSI6ICIifQ==
ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@172.99.188.99:6379#github.com/freefq%20-%20%E7%BE%8E%E5%9B%BD%20%2022
vmess://eyJhZGQiOiAiY2ZjZG4uc2FuZmVuY2RuLm5ldCIsICJhaWQiOiAwLCAiaG9zdCI6ICJ1czIuc2FuZmVuY2RuLm5ldCIsICJpZCI6ICJkYTlkNWM3NC1hNTcyLTRjZjQtYTM3NS0xOWI4ODZmNWZmYzQiLCAibmV0IjogIndzIiwgInBhdGgiOiAiL3poLWNuIiwgInBvcnQiOiA0NDMsICJwcyI6ICJnaXRodWIuY29tL2ZyZWVmcSAtIFx1N2Y4ZVx1NTZmZENsb3VkRmxhcmVcdTgyODJcdTcwYjkgMjQiLCAic2VjdXJpdHkiOiAiYXV0byIsICJza2lwLWNlcnQtdmVyaWZ5IjogdHJ1ZSwgInNuaSI6ICIiLCAidGxzIjogInRscyIsICJ0eXBlIjogImF1dG8ifQ==
ss://YWVzLTI1Ni1nY206a0RXdlhZWm9UQmNHa0M0@172.99.188.99:8882#github.com/freefq%20-%20%E7%BE%8E%E5%9B%BD%20%2028
```

|    | id                           | addr                              |
|---:|:-----------------------------|:----------------------------------|
|  0 | [1](config_invalid/1.json)   | n1680936925.aqdisrv.cn            |
|  1 | [2](config_invalid/2.json)   | hk1.b.bd6b6c503c93.sanfen001.pics |
|  2 | [6](config_invalid/6.json)   | 212.110.134.10                    |
|  3 | [7](config_invalid/7.json)   | 103.160.204.13                    |
|  4 | [8](config_invalid/8.json)   | 23.224.110.183                    |
|  5 | [9](config_invalid/9.json)   | 185.162.228.1                     |
|  6 | [10](config_invalid/10.json) | 103.160.204.15                    |
|  7 | [11](config_invalid/11.json) | 188.114.99.2                      |
|  8 | [13](config_invalid/13.json) | 162.159.255.200                   |
|  9 | [14](config_invalid/14.json) | 185.143.220.25                    |
| 10 | [15](config_invalid/15.json) | 172.99.188.99                     |
| 11 | [16](config_invalid/16.json) | 170.187.206.48                    |
| 12 | [17](config_invalid/17.json) | 203.30.188.2                      |
| 13 | [18](config_invalid/18.json) | tw2.sanfen001.pics                |
| 14 | [19](config_invalid/19.json) | 188.114.96.1                      |
| 15 | [20](config_invalid/20.json) | 144.34.165.33                     |
| 16 | [23](config_invalid/23.json) | cf.515188.xyz                     |
| 17 | [25](config_invalid/25.json) | www.udemy.com                     |
| 18 | [26](config_invalid/26.json) | 185.162.228.229                   |
| 19 | [27](config_invalid/27.json) | 45.89.106.139                     |

## Invalid
```
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTRlMmRcdTU2ZmRcdTk2M2ZcdTkxY2NcdTRlOTEgMSIsICJhZGQiOiAibjE2ODA5MzY5MjUuYXFkaXNydi5jbiIsICJwb3J0IjogIjQ0MyIsICJpZCI6ICIyYjc0Y2RmMy04NWE3LTQ3MzgtYWVhMy05N2E4MmU5NWVkZTUiLCAiYWlkIjogIjAiLCAic2N5IjogImF1dG8iLCAibmV0IjogIndzIiwgInR5cGUiOiAibm9uZSIsICJob3N0IjogIm4xNjgwOTM2OTI1LmFxZGlzcnYuY24iLCAicGF0aCI6ICIvIiwgInRscyI6ICJ0bHMiLCAic25pIjogIm4xNjgwOTM2OTI1LmFxZGlzcnYuY24iLCAiYWxwbiI6ICIifQ==
vmess://eyJhZGQiOiAiaGsxLmIuYmQ2YjZjNTAzYzkzLnNhbmZlbjAwMS5waWNzIiwgInYiOiAiMiIsICJwcyI6ICJnaXRodWIuY29tL2ZyZWVmcSAtIFx1N2Y4ZVx1NTZmZFx1NjBlMFx1NjY2ZUhQIDIiLCAicG9ydCI6IDQ0MywgImlkIjogImRhOWQ1Yzc0LWE1NzItNGNmNC1hMzc1LTE5Yjg4NmY1ZmZjNCIsICJhaWQiOiAiMCIsICJuZXQiOiAid3MiLCAidHlwZSI6ICIiLCAiaG9zdCI6ICJ3d3cubWljcm9zb2Z0LmNvbSIsICJwYXRoIjogIi96aC1jbiIsICJ0bHMiOiAidGxzIn0=
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTRlNGNcdTUxNGJcdTUxNzAgIDYiLCAiYWRkIjogIjIxMi4xMTAuMTM0LjEwIiwgInBvcnQiOiAiNDQzIiwgImlkIjogIjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsICJhaWQiOiAiMCIsICJzY3kiOiAiYXV0byIsICJuZXQiOiAid3MiLCAidHlwZSI6ICJub25lIiwgImhvc3QiOiAiMTU0LnYycmF5My54eXoiLCAicGF0aCI6ICIvRUNUQ0owREYiLCAidGxzIjogInRscyIsICJzbmkiOiAiIiwgImFscG4iOiAiIn0=
vmess://eyJhZGQiOiAiMTAzLjE2MC4yMDQuMTMiLCAiYWlkIjogMCwgImhvc3QiOiAibGcyLnYycmF5Ni54eXoiLCAiaWQiOiAiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwgIm5ldCI6ICJ3cyIsICJwYXRoIjogIi81UU5ST1NSViIsICJwb3J0IjogNDQzLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTRlOWFcdTU5MmFcdTU3MzBcdTUzM2EgIDciLCAic2VjdXJpdHkiOiAiYXV0byIsICJza2lwLWNlcnQtdmVyaWZ5IjogdHJ1ZSwgInNuaSI6ICIiLCAidGxzIjogInRscyIsICJ0eXBlIjogImF1dG8ifQ==
vmess://eyJhZGQiOiAiMjMuMjI0LjExMC4xODMiLCAiYWlkIjogNjQsICJob3N0IjogIiIsICJpZCI6ICI0MTgwNDhhZi1hMjkzLTRiOTktOWIwYy05OGNhMzU4MGRkMjQiLCAibmV0IjogIndzIiwgInBhdGgiOiAiL3BhdGgvMDgwNzEyMzQyMzEwIiwgInBvcnQiOiA0NDMsICJwcyI6ICJnaXRodWIuY29tL2ZyZWVmcSAtIFx1N2Y4ZVx1NTZmZFx1NTJhMFx1NTIyOVx1Nzk4Zlx1NWMzY1x1NGU5YVx1NWRkZVx1NmQxYlx1Njc0OVx1NzdmNkNvcGVyYXRpb24gQ29sb2N0aW9uXHU2NTcwXHU2MzZlXHU0ZTJkXHU1ZmMzIDgiLCAic2VjdXJpdHkiOiAiYXV0byIsICJza2lwLWNlcnQtdmVyaWZ5IjogdHJ1ZSwgInNuaSI6ICIiLCAidGxzIjogInRscyIsICJ0eXBlIjogImF1dG8ifQ==
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTRlMzlcdTllYTYgIDkiLCAiYWRkIjogIjE4NS4xNjIuMjI4LjEiLCAicG9ydCI6IDQ0MywgImlkIjogIjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsICJhaWQiOiAwLCAic2N5IjogImF1dG8iLCAibmV0IjogIndzIiwgImhvc3QiOiAiMTU0LnYycmF5My54eXoiLCAicGF0aCI6ICIvRUNUQ0owREYiLCAidGxzIjogInRscyJ9
vmess://eyJhZGQiOiAiMTAzLjE2MC4yMDQuMTUiLCAiYWlkIjogMCwgImhvc3QiOiAibGcxLnYycmF5Ni54eXoiLCAiaWQiOiAiYzVhMmQ3YjgtYmY4NC00Zjk3LTg1NzctYjliODdmMmJhYWY3IiwgIm5ldCI6ICJ3cyIsICJwYXRoIjogIi9BVUlLTjhBVSIsICJwb3J0IjogNDQzLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTRlOWFcdTU5MmFcdTU3MzBcdTUzM2EgIDEwIiwgInRscyI6ICJ0bHMiLCAidHlwZSI6ICJhdXRvIiwgInNlY3VyaXR5IjogImF1dG8iLCAic2tpcC1jZXJ0LXZlcmlmeSI6IHRydWUsICJzbmkiOiAiIn0=
vmess://eyJhZGQiOiAiMTg4LjExNC45OS4yIiwgImFpZCI6IDAsICJob3N0IjogImZyLnYycmF5MS54eXoiLCAiaWQiOiAiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwgIm5ldCI6ICJ3cyIsICJwYXRoIjogIi8iLCAicG9ydCI6IDgwLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTVkZjRcdTg5N2ZcdTU3MjNcdTRmZGRcdTdmNTdDbG91ZEZsYXJlXHU4MjgyXHU3MGI5IDExIiwgInRscyI6ICIiLCAidHlwZSI6ICJhdXRvIiwgInNlY3VyaXR5IjogImF1dG8iLCAic2tpcC1jZXJ0LXZlcmlmeSI6IHRydWUsICJzbmkiOiAiIn0=
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmRDbG91ZEZsYXJlXHU4MjgyXHU3MGI5IDEzIiwgImFkZCI6ICIxNjIuMTU5LjI1NS4yMDAiLCAicG9ydCI6ICI4MCIsICJpZCI6ICI1MjQ2NmRjMi0zNTUwLTQzMTAtOTEwYy03NGI3YmY4YTAyMGUiLCAiYWlkIjogIjAiLCAic2N5IjogImF1dG8iLCAibmV0IjogIndzIiwgInR5cGUiOiAibm9uZSIsICJob3N0IjogInVzLTEuYWN5dW4uZXUub3JnIiwgInBhdGgiOiAiLyIsICJ0bHMiOiAiIiwgInNuaSI6ICIifQ==
vmess://eyJhZGQiOiAiMTg1LjE0My4yMjAuMjUiLCAiYWlkIjogMCwgImhvc3QiOiAiZGVuZ3hpbi5vbmUiLCAiaWQiOiAiZjI4ZTM1NGUtYzJkMS00OTgzLTliMDctNWFjYWYxYjNiM2U1IiwgIm5ldCI6ICJ3cyIsICJwYXRoIjogIi82ZTlFdFoyZEwiLCAicG9ydCI6IDQ0MywgInBzIjogImdpdGh1Yi5jb20vZnJlZWZxIC0gXHU0ZmM0XHU3ZjU3XHU2NWFmICAxNCIsICJ0bHMiOiAidGxzIiwgInR5cGUiOiAiYXV0byIsICJzZWN1cml0eSI6ICJhdXRvIiwgInNraXAtY2VydC12ZXJpZnkiOiB0cnVlLCAic25pIjogIiJ9
ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@172.99.188.99:5003#github.com/freefq%20-%20%E7%BE%8E%E5%9B%BD%20%2015
vmess://eyJhZGQiOiAiMTcwLjE4Ny4yMDYuNDgiLCAiYWlkIjogMCwgImhvc3QiOiAiIiwgImlkIjogIjkyNzA5NGQzLWQ2NzgtNDc2My04NTkxLWUyNDBkMGJjYWU4NyIsICJuZXQiOiAid3MiLCAicGF0aCI6ICIvY2hhdCIsICJwb3J0IjogNDQzLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmQgIDE2IiwgInRscyI6ICJ0bHMiLCAidHlwZSI6ICJhdXRvIiwgInNlY3VyaXR5IjogImF1dG8iLCAic2tpcC1jZXJ0LXZlcmlmeSI6IHRydWUsICJzbmkiOiAiIn0=
vmess://eyJhZGQiOiAiMjAzLjMwLjE4OC4yIiwgImFpZCI6IDAsICJob3N0IjogImZyLnYycmF5MS54eXoiLCAiaWQiOiAiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwgIm5ldCI6ICJ3cyIsICJwYXRoIjogIi8iLCAicG9ydCI6IDgwLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTZmYjNcdTU5MjdcdTUyMjlcdTRlOWFMeW5kaHVyc3QgU2Vjb25kYXJ5IENvbGxlZ2UgMTciLCAidGxzIjogIiIsICJ0eXBlIjogImF1dG8iLCAic2VjdXJpdHkiOiAiYXV0byIsICJza2lwLWNlcnQtdmVyaWZ5IjogdHJ1ZSwgInNuaSI6ICIifQ==
vmess://eyJhZGQiOiAidHcyLnNhbmZlbjAwMS5waWNzIiwgInYiOiAiMiIsICJwcyI6ICJnaXRodWIuY29tL2ZyZWVmcSAtIFx1NTNmMFx1NmU3ZVx1NzcwMVx1NTNmMFx1NTMxN1x1NWUwMlx1NGUyZFx1NTM0ZVx1NzUzNVx1NGZlMSAxOCIsICJwb3J0IjogNDQzLCAiaWQiOiAiZGE5ZDVjNzQtYTU3Mi00Y2Y0LWEzNzUtMTliODg2ZjVmZmM0IiwgImFpZCI6ICIwIiwgIm5ldCI6ICJ0Y3AiLCAidHlwZSI6ICIiLCAiaG9zdCI6ICIiLCAicGF0aCI6ICIvIiwgInRscyI6ICJ0bHMifQ==
vmess://eyJhZGQiOiAiMTg4LjExNC45Ni4xIiwgInYiOiAyLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTVkZjRcdTg5N2ZcdTU3MjNcdTRmZGRcdTdmNTdDbG91ZEZsYXJlXHU4MjgyXHU3MGI5IDE5IiwgInBvcnQiOiAiNDQzIiwgImlkIjogIjJlNDk2NzU4LTk1MGUtNDU0OS04ODQyLWQ1ZWVjOThkOWZkZSIsICJhaWQiOiAiMCIsICJzY3kiOiAiYXV0byIsICJuZXQiOiAid3MiLCAidHlwZSI6ICIiLCAiaG9zdCI6ICJsdjIuc2hhcmVjZW50cmVwcm8ub3JnIiwgInRscyI6ICJ0bHMiLCAicGF0aCI6ICIvc2hpcmtlciJ9
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmRcdTUyYTBcdTUyMjlcdTc5OGZcdTVjM2NcdTRlOWFcdTVkZGVcdTZkMWJcdTY3NDlcdTc3ZjZJVDdcdTdmNTFcdTdlZGMgMjAiLCAiYWRkIjogIjE0NC4zNC4xNjUuMzMiLCAicG9ydCI6ICIxMDUxMiIsICJ0eXBlIjogIm5vbmUiLCAiaWQiOiAiNTg3ODFlZWUtYmFiYS02NjY2LWJhYmEtMmNhMGFkYTY1NjhiIiwgImFpZCI6ICIwIiwgIm5ldCI6ICJ0Y3AiLCAicGF0aCI6ICIvIiwgImhvc3QiOiAiIiwgInRscyI6ICIifQ==
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmRDbG91ZEZsYXJlXHU1MTZjXHU1M2Y4Q0ROXHU4MjgyXHU3MGI5IDIzIiwgImFkZCI6ICJjZi41MTUxODgueHl6IiwgInBvcnQiOiAiODAiLCAiaWQiOiAiZjZhYTQ0NDAtZTdiZS00NGUxLTgwZTEtN2U0NWNjZDc5NmNjIiwgImFpZCI6ICIwIiwgInNjeSI6ICJhdXRvIiwgIm5ldCI6ICJ3cyIsICJ0eXBlIjogIm5vbmUiLCAiaG9zdCI6ICJzc3JzdWIudjAxLnNzcnN1Yi5jb20iLCAicGF0aCI6ICIvYXBpL3YzL2Rvd25sb2FkLmdldEZpbGUiLCAidGxzIjogIiIsICJzbmkiOiAiIn0=
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmRDbG91ZEZsYXJlXHU1MTZjXHU1M2Y4Q0ROXHU4MjgyXHU3MGI5IDI1IiwgImFkZCI6ICJ3d3cudWRlbXkuY29tIiwgInBvcnQiOiAiNDQzIiwgImlkIjogImU2NDQyOTAzLTQ3NTMtNDc4My04OTE2LWFjNDdjODA4MGU0ZiIsICJhaWQiOiAiMCIsICJzY3kiOiAiYXV0byIsICJuZXQiOiAid3MiLCAidHlwZSI6ICJub25lIiwgImhvc3QiOiAiZHluYW1pYy1zZzNiLm9iZnMueHl6IiwgInBhdGgiOiAiL3dvcnJ5ZnJlZSIsICJ0bHMiOiAidGxzIiwgInNuaSI6ICIiLCAiYWxwbiI6ICIifQ==
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTRlMzlcdTllYTYgIDI2IiwgImFkZCI6ICIxODUuMTYyLjIyOC4yMjkiLCAicG9ydCI6ICI4MCIsICJ0eXBlIjogIm5vbmUiLCAiaWQiOiAiNWY2NGZhNjUtN2IxNC00OWM1LTk1NGQtYWExNWM2YmZjYWNkIiwgImFpZCI6ICIwIiwgIm5ldCI6ICJ3cyIsICJwYXRoIjogIi8iLCAiaG9zdCI6ICJsZy52MnJheTgueHl6IiwgInRscyI6ICIifQ==
vmess://eyJ2IjogIjIiLCAicHMiOiAiZ2l0aHViLmNvbS9mcmVlZnEgLSBcdTdmOGVcdTU2ZmRcdTUyYTBcdTUyMjlcdTc5OGZcdTVjM2NcdTRlOWFcdTVkZGVcdTZkMWJcdTY3NDlcdTc3ZjZEZWRpcGF0aFx1NjU3MFx1NjM2ZVx1NGUyZFx1NWZjMyAyNyIsICJhZGQiOiAiNDUuODkuMTA2LjEzOSIsICJwb3J0IjogNDQzLCAiYWlkIjogMCwgInNjeSI6ICJhdXRvIiwgIm5ldCI6ICJ3cyIsICJ0eXBlIjogIm5vbmUiLCAidGxzIjogIiIsICJpZCI6ICI4MzY2ZjMwYy0xMjZiLTQ3MTEtZDZhZi03OWVkNjhhMTM4YjUiLCAiaG9zdCI6ICI0NS44OS4xMDYuMTM5IiwgInBhdGgiOiAiL3JheSJ9
```

## Todo
```
trojan://c89f1371-e52f-4e6d-85f4-a62df0c7416b@us226.ljydw.top:443#github.com/freefq%20-%20%E4%BA%9A%E5%A4%AA%E5%9C%B0%E5%8C%BA%20%205
```

