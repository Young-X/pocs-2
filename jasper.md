# pocs
pocs of libjasper

### 001-jasper-aborted-1
```
jasper -f $FILE -t jpc -F /tmp/out.pnm -T pnm
Aborted
```


### 002-jasper-aborted-2
jasper -f $FILE -t jpc -F /tmp/out.pnm -T pnm
```
jasper: /data/xqx/tests/libjasper-test/jasper/src/libjasper/jpc/jpc_t1cod.c:144: JPC_NOMINALGAIN: Assertion `qmfbid == 0x01' failed.
Aborted
```


### 003-jasper-aborted-3
jasper -f $FILE -t jpc -F /tmp/out.pnm -T pnm
```
warning: ignoring unknown marker segment (0xffff)
type = 0xffff (UNKNOWN); len = 19;40 40 48 48 50 48 48 50 48 48 50 48 48 45 48 48 50 jasper: /data/xqx/tests/libjasper-test/jasper/src/libjasper/jpc/jpc_t1cod.c:144: JPC_NOMINALGAIN: Assertio
n `qmfbid == 0x01' failed.
Aborted
```

### 004-jasper-aborted-4
jasper -f $FILE -t jpc -F /tmp/out.pnm -T pnm
```
warning: trailing garbage in marker segment (15 bytes)
jasper: /data/xqx/tests/libjasper-test/jasper/src/libjasper/jpc/jpc_t1cod.c:144: JPC_NOMINALGAIN: Assertion `qmfbid == 0x01' failed.
Aborted
```

### 005-jasper-aborted-5
jasper -f $FILE -t jpc -F /tmp/out.pnm -T pnm
```
warning: ignoring trailing garbage (1 bytes)
jasper: /data/xqx/tests/libjasper-test/jasper/src/libjasper/jpc/jpc_dec.c:1883: jpc_dequantize: Assertion `absstepsize >= 0' failed.
Aborted
```

### 006-jasper-aborted-6
jasper -f $FILE -t jpc -F /tmp/out.pnm -T pnm
```
warning: ignoring unknown marker segment (0xff7e)
type = 0xff7e (UNKNOWN); len = 20;01 40 40 ff ff 80 00 48 50 40 48 50 48 48 50 48 48 50 warning: trailing garbage in marker segment (1 bytes)
warning: ignoring unknown marker segment (0xff0d)
type = 0xff0d (UNKNOWN); len = 20;00 40 40 00 00 00 00 00 00 00 00 e9 00 ff 80 e9 00 00 jasper: /data/xqx/tests/libjasper-test/jasper/src/libjasper/jpc/jpc_dec.c:1883: jpc_dequantize: Assertion `absstepsize >= 0' failed.
Aborted
```







