## opentsdb-tools

OpenTSDB - Import and Export script

## Use Hbase

hbase shell

## List table

list

## disable and drop tables

disable 'tsdb'
disable 'tsdb-meta'
disable 'tsdb-tree'
disable 'tsdb-uid'
drop 'tsdb'
drop 'tsdb-meta'
drop 'tsdb-tree'
drop 'tsdb-uid'

## create a simple tables run my script create_table

./create_table

## Export opentsdb run tsdb-export script default export path is /bigdata/opentsdb-backup/ file name tsdb-backup-<current-exportdate>.tar.gz

./tsdb-export

## Import opentsdb run tsdb-import script and specify option -d to destination path

./tsdb-import -d /path/to/db 
