# grafana

安装
https://grafana.com/grafana/download/7.2.0?platform=windows

插件安装
windows |

·在grafana的bin目录下执行： 

grafana-cli plugins install grafana-clock-panel(管理员运行cmd)

·重启grafanna，kill grafana-server进程，grafana自动重启进程

·添加数据源(postgreSQL)

  -Host localhost:5432
  
  -SSL Mode disable
  
  -version 12

·备份还原
  
  -在每个dashboard页的右上角有一个齿轮->json model->复制json
  
  -dashboard -> import -> 粘贴
  
·windows命令：

【进入C盘】 cd C://

【dir】 查看目录下文件

【cd 目录】进入目录，如 cd GrafanaLabs\grafana\bin

【Tab键】自动补全路径

【tasklist】查看进程

【tskill PID】终止进程
