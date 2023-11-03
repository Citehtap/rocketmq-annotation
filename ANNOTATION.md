# Start up
## 模块编译参数
> java9模块化导致的异常
settings - Java compiler - Override compiler parameters per-module
store - `--add-exports java.base/sun.nio.ch=ALL-UNNAMED`
test - `--add-exports java.base/sun.util.locale=ALL-UNNAMED`

## demo
1. NamesrvStartup
2. BrokerStartup
3. producer: `-a testtag -c 10 -g testproducergroup -k testkey -t testtopic`
4. consumer: `-f false -g testproducergroup -t testtopic -s *`

