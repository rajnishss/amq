Dockerfile to build a ActiveMQ container image.

## Version

Current Version: **5.9.0**


```bash
docker run --name='activemq' -it --rm \
	-e 'ACTIVEMQ_MIN_MEMORY=512' \
	-e 'ACTIVEMQ_MAX_MEMORY=2048'\
        -P
	webcenter/activemq:latest
```
