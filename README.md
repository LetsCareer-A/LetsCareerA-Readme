![image](https://github.com/user-attachments/assets/61bf201a-6419-414b-8381-e94c790ebef6)


## 1. 서비스

### 1-1. 서비스 소개


**<렛츠커리어 지원 대시보드>**는 취업을 준비하는 모든 여정의 소중한 경험과 기록을 차곡차곡 담아가며 함께 성장할 수 있도록 돕는 서비스입니다.

기본적인 ***지원 일정***뿐만 아니라, 각 전형에서 어필할 나의 핵심 ***경험을 관리***하고, 전형이 완료된 후에는 빠른 시일 내에 ***회고 기록***을 남기도록 도와, 취업을 준비하는 모든 과정을 체계적으로 관리할 수 있도록 합니다.

---


### 1-2. 유저 플로우


![image (12)](https://github.com/user-attachments/assets/7cdebf47-2e89-422d-aaff-91d16aa45f4b)

![flow2](https://github.com/user-attachments/assets/36041eed-ca96-4c8e-91a2-e4eed94584dc)

---

### 1-3. IA (Information Ar**chitecture)**


![image (13)](https://github.com/user-attachments/assets/179bd270-3d16-440f-a77b-29fafe7a34fb)

---

## 2. 프로토타입


![image (19)](https://github.com/user-attachments/assets/31988c3a-9fbb-4328-9a9d-90d981cc2859)

![image (20)](https://github.com/user-attachments/assets/51efb448-77ea-45c5-b8f9-4778f8273d2d)

![image (21)](https://github.com/user-attachments/assets/1e000d14-b8cd-4bef-b54d-4f6c5908570b)

![image (22)](https://github.com/user-attachments/assets/4d8f4d40-e7a5-4d18-b63c-84ca0e10d8ac)

![image (23)](https://github.com/user-attachments/assets/5590ac7a-e98a-4e3a-a53f-052361c8e9b4)

![image (24)](https://github.com/user-attachments/assets/dfef1c5f-fe43-46ba-bebc-d21205bd944d)

![image (25)](https://github.com/user-attachments/assets/ecc1cdbb-9292-460a-9887-376915c65b89)

![image (26)](https://github.com/user-attachments/assets/483f26d6-d426-41d1-8212-5cd599e71c04)

![image (27)](https://github.com/user-attachments/assets/f254cecf-08cb-4c34-8128-1f2bbe23cf1f)

![image (28)](https://github.com/user-attachments/assets/32a39f50-5559-4450-a159-db031918c799)


### 3. ERD

---

![letscareer-dashboard](https://github.com/user-attachments/assets/42774186-cbac-4104-971c-ded88ff8b1f2)


### 4. System Architechture

---

![image](https://github.com/user-attachments/assets/52f27d5e-168c-4c80-b408-7a6a9cee6abc)

## **🖥️  기술 스택 설명**


> **Frontend 스택** 
> 

### **프레임워크**

- React `18.0.3`
- TypeScript - 코드의 안정성과 가독성을 높이고,  더 안전한 코드를 작성을 위해 사용합니다.

### **스타일링 도구**

- Tailwind CSS - 미리 정의된 클래스를 사용해 효율적으로 스타일링을 위해 사용합니다.

### **라우팅 도구**

- React Router - SPA에서 페이지 간 네비게이션을 관리하기 위해 사용합니다.

### **데이터 및 상태 관리**

- Axios - HTTP 요청을 쉽게 관리하기 위해 사용합니다.

### **빌드 및 배포**

- Vite - 빠른 HMR(Hot Module Replacement)과 효율적인 번들링을 위해 사용합니다.
- Vercel - 자동화된 배포 파이프라인과 글로벌 CDN을 제공하기 때문에 빠르고 안정적인 배포를 위해 사용합니다.

---

> **Server 스택**
> 

### 프레임워크

- Spring boot `3.2.5`
- Query Dsl `5.0.0`  - 타입 세이프하고 가독성이 높은 쿼리 작성을 위해 사용합니다.

### 데이터베이스

- mysql `8.x.x`
- redis - 어필할 커리어를 연결할 당시 좌측 커리어보드의 데이터를 Redis에 캐싱함으로써 데이터베이스 부하를 줄이고 응답 속도를 높이기 위해 사용합니다.

### 클라우드

- EC2 - 인스턴스 생성을 위해 사용합니다.
- RDS - 데이터베이스 생성을 위해 사용합니다.
- Elastic cache - api의 성능을 위해 redis 캐싱을 위해 사용합니다.
- nginx, docker, githubactions - cicd 배포를 위해 사용합니다.

