## Description

PM2 module to send logs to elasticsearch

```bash
$ npm install pm2 -g

$ pm2 install pm2-elk-sync
```

To modify the config values you can use the following commands:

```bash
pm2 set pm2-elk-sync:elasticsearch_host 'http://localhost:9200'
```

```bash
pm2 set pm2-elk-sync:elasticsearch_index logs
```

```bash
pm2 set pm2-elk-sync:app_name all
```

## Uninstall

```bash
$ pm2 uninstall pm2-elk-sync
```

# License

MIT
