## Description

PM2 module to send logs to elasticsearch

`Warning: Due to version upgrade of elasticsearch, both of [pm2-elasticlogs](https://github.com/infuse89/pm2-elasticlogs) and [pm2-elastic](https://github.com/danilaplee/pm2-elastic) are no longer work any more when the version of elasticsearch beyond V7.5, so try this repository to sync your pm2 logs into ELK.`

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
