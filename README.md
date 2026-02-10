# Local Development Setup

## How to Run

### 1. Install Docker

- Windows / macOS
  - Docker Desktop 설치 : https://www.docker.com/products/docker-desktop
- Linux
  - Docker Engine & Docker Compose Plugin 설치 : https://docs.docker.com/engine/install/

---

### 2. Clone

```cmd
git clone https://github.com/forERP/Backend-Repo.git
git clone https://github.com/forERP/Frontend-Repo.git
git clone https://github.com/forERP/Infra-Repo.git
```

---

### 3. Configure

```cmd
cd Infra-Repo
copy .env.example .env
```
- .env에서 보안 관련 값 설정하기 (Secret key, 비밀번호 등)

---

### 4. Run

```cmd
docker compose pull
docker compose up -d
```

---

## Port

- 관리자 웹 : http://localhost:3100/
- POS : http://localhost:3200/
