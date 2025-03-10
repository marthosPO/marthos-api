# 📌 MARTHOS API 문서

## ✅ 1. 유저 인증 API

### 🔹 `POST /auth/login`
- **설명**: 사용자 로그인 API
- **요청 예시**
```json
{
  "email": "user@example.com",
  "password": "password123"
}

- **응답 예시**
```json
{
  "token": "eyJhbGciOi..."
}
```
