# sandbox
Various test and public examples

```console
console
B017122@C1730113 /cygdrive/c/Bytemarc/.releases/04.11
$ ls js/jquery/3.4.1/jquery.min.js
js/jquery/3.4.1/jquery.min.js

B017122@C1730113 /cygdrive/c/Bytemarc/.releases/04.11
$
```

```json
[
  "json": true,
  "json2": true
]
```
```bash
#!/usr/bin/sh
#bash
check_return()
{
  RETURNCODE=$1
  #PASSWORD=$2
  #shift; shift;
  ## Having shifted twice, the rest is now comments ...
  #COMMENTS=$@
    if [ 0 -eq $RETURNCODE ]
    then 
        echo OK
    else
        echo ERROR $RETURNCODE
        sleep 3
    fi
}
compile()
{
    CMD=$1
    MSG=$2
    printf  '. %-60s' "$MSG"
    php $CMD >/dev/null
    check_return $?
} 
```

```shell
#!/usr/bin/sh
check_return()
{
  RETURNCODE=$1
  #PASSWORD=$2
  #shift; shift;
  ## Having shifted twice, the rest is now comments ...
  #COMMENTS=$@
    if [ 0 -eq $RETURNCODE ]
    then 
        echo OK
    else
        echo ERROR $RETURNCODE
        sleep 3
    fi
}
compile()
{
    CMD=$1
    MSG=$2
    printf  '. %-60s' "$MSG"
    php $CMD >/dev/null
    check_return $?
} 
```
