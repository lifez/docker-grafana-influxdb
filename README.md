curl -i -XPOST 'http://localhost:8086/write?db=influx' --data-binary 'measurement,action=export_count value=1'
