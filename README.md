# MicroDegree-MegaProject

---

###  Docker Commands

#### 1. Build Docker Image

```bash
docker build -t microdegree-app .
```

#### 2. Run Docker Container (pass AWS RDS details)

```bash
docker run -d -p 80:5000 \
  -e RDS_HOST="your-rds-endpoint" \
  -e RDS_USER="your-rds-username" \
  -e RDS_PASSWORD="your-rds-password" \
  kchithu/microdegree-app:1.0
```

Replace `your-rds-endpoint`, `your-rds-username`, and `your-rds-password` with actual values.

---

