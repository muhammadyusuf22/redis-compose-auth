# redis-compose-auth
Docker Compose With Auth Configuration

### Menjalankan Docker Compose
1. Buka Terminal dan arahkan ke folder dimana docker-compose.yml berada
2. Jalankan Perintah Berikut
    ```bash 
    docker-compose -f docker-compose.yml up -d
    ```

### Koneksi Redis Menggunakan redis-cli
1. Masuk docker exec menggunakan perintah berikut
    ```bash
    docker exec -it redis /bin/sh
    ```
3. Setelah masuk redis-cli menggunakan perintah:
    ```bash
    redis-cli -h localhost
    ```
