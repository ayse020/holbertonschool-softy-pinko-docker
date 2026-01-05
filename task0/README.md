# Holberton School Softy Pinko Docker Layihəsi

## Tapşırıq 0: İlk Docker Görüntüsünün Yaradılması

### Məqsəd
Bu tapşırıqda ilk Docker görüntüsünü yaratmaq və onu konteynerdə işə salmaq öyrənilir.

### Tələblər
- Dockerfile yaratmaq
- Ubuntu əsaslı görüntü qurmaq
- APT paket menecerini yeniləmək
- Qurulu proqramları yeniləmək
- Konteyner işə salındıqda "Hello, World!" mesajını çap etmək

### Dockerfile Məzmunu
```dockerfile
FROM ubuntu:latest
RUN apt-get update
RUN apt-get upgrade -y
CMD ["echo", "Hello, World!"]
