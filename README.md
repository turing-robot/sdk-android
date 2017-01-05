##更新内容：
1. 去除请求userid方法，默认不再单独请求userid接口。
2. 用户不需要单独传userid，userid默认和设备IMEI号对应。如多台设备的IMEI号相同，会导致语义语境上下文出错，需特殊处理。
3. 如特殊情况必须传userid，可以参见TuringManager的setUniqueId方法。

###详细使用方法见文档。