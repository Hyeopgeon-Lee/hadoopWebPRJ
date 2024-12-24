# 🌱 hadoopPRJ

> **웹과 연동한 하둡 분산 파일 시스템 프로그래밍**  
> Hadoop Client와 Spring Boot를 활용하여 HDFS와 연동된 파일 업로드 및 다운로드 기능을 구현한 실습 코드입니다.  
> 공유되는 프로그래밍 코드는 한국폴리텍대학 서울강서캠퍼스 빅데이터과 수업에서 사용된 코드입니다.

---

### 📚 **작성자**
- **한국폴리텍대학 서울강서캠퍼스 빅데이터과**  
- **이협건 교수**  
- ✉️ [hglee67@kopo.ac.kr](mailto:hglee67@kopo.ac.kr)  
- 🔗 [빅데이터학과 입학 상담 오픈채팅방](https://open.kakao.com/o/gEd0JIad)

---

## 🚀 주요 실습 내용

1. **Hadoop Client + Spring Boot Frameworks, Spring Boot Web 연동**
2. **HTML로부터 업로드된 파일을 HDFS 업로드 및 업로드된 파일 정보를 DB 테이블에 저장하기**
3. **HDFS 업로드된 파일 다운로드하기**

---

## 🛠️ 주요 기술 스택

- **Spring Boot Frameworks**
- **Hadoop HDFS**
- **Gradle**

---

## 📩 문의 및 입학 상담

- 📧 **이메일**: [hglee67@kopo.ac.kr](mailto:hglee67@kopo.ac.kr)  
- 💬 **입학 상담 오픈채팅방**: [바로가기](https://open.kakao.com/o/gEd0JIad)

---

## 💡 **우리 학과 소개**
- 한국폴리텍대학 서울강서캠퍼스 빅데이터과는 **클라우드 컴퓨팅, 인공지능, 빅데이터 기술**을 활용하여 소프트웨어 개발자를 양성하는 학과입니다.  
- 학과에 대한 더 자세한 정보는 [학과 홈페이지](https://www.kopo.ac.kr/kangseo/content.do?menu=1547)를 참고하세요.

---

## 📦 **설치 및 실행 방법**

### 1. 레포지토리 클론
- 아래 명령어를 실행하여 레포지토리를 클론합니다.

```bash
git clone https://github.com/Hyeopgeon-Lee/hadoopWebPRJ.git
cd hadoopWebPRJ
```

### 2. Hadoop 설정
- Hadoop HDFS가 로컬 또는 클러스터 환경에서 실행 중이어야 합니다.
- HDFS와의 연결 정보를 application.yml 또는 application.properties에 업데이트합니다.

```yaml
hadoop:
  fs:
    uri: hdfs://localhost:9000
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/your_database
    username: your_username
    password: your_password
```

### 3. 의존성 설치 및 빌드
- Gradle을 사용하여 의존성을 설치하고 빌드합니다.

```bash
./gradlew build
```

### 4. 애플리케이션 실행
- 아래 명령어를 실행하여 애플리케이션을 시작합니다.

```bash
./gradlew bootRun
```

