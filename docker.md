clean up all docker objects older than 30 days
```
docker system prune -a -f --filter 'until=720h'
```
