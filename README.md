# HP Smart Array to InfluxDB

Plugin to convert ssacli (successor of hpacucli) output to influxdb line protocol.

Example output:
```
ssa_controller,slot=0 health_ok=1i,type="P220i"
ssa_array,slot=0,array=A used=1i,type="SAS"
ssa_phsicaldrive,slot=0,array=A,port=1I,box=1,bay=1,drive=1I:1:1 health_ok=1i,health_str="OK",size=1.8E+12,type="SAS"
ssa_phsicaldrive,slot=0,array=A,port=1I,box=1,bay=2,drive=1I:1:2 health_ok=1i,health_str="OK",size=1.8E+12,type="SAS"
```

