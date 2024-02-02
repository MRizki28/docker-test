## Docker Setup
> <b>Perhatian: </b>
> Pastikan di komputer / server sudah diinstall docker dengan versi yang paling terbaru.
<ol>
    
```bash
docker-compose up -d
```
<p>Atau</p>
    
```bash
sudo docker build -t laravel/testing:1.0.0 .
```

<p>Run container</p>

```bash
sudo run --name rizki -p 8001:8001 laravel/testing:1.0.0
```

</ol>
