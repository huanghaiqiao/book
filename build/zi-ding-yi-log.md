# 自定义log

一、自定义log

```sh
LOG() {
    log=$@
    if [ "$1" == "ERROR" ]; then
        log="\033[0;31m$@\033[0m"
    fi
    echo -e "[$(date +"%Y-%m-%d %T.%3N")] $log"
}
LOG "ERROR" "错误原因"
```
