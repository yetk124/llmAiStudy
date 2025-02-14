# llmAiStudy


## project2.ipynb
### 미니포에 웹 크롤러 📦

- 미니포에 웹사이트에서 상품 정보를 크롤링하는 프로그램

### 기능
- 페이지 번호에 따라 상품 리스트 크롤링 🛍️
- 상품명, 정상 가격, 할인 가격, 할인율 추출 💰
- 데이터를 CSV 파일로 저장하여 쉽게 관리 가능 💾

### 사용 기술
- **BeautifulSoup**: HTML 파싱 🧑‍💻
- **Requests**: HTTP 요청 🌐

### 설치 및 실행 방법
1. 필요한 라이브러리 설치:
    ```bash
    pip install requests beautifulsoup4
    ```
2. 크롤링 스크립트 실행:
    ```bash
    python crawling_script.py
    ```


## project3.ipynb
### mongoDB 이미지 관리 📸

- MongoDB를 활용하여 이미지 파일을 저장하고 관리하는 프로그램

### 기능
  - 이미지를 MongoDB에 저장 🗄️
  - 저장된 이미지 목록 조회 📝
  - 이미지를 삭제하고 수정하는 기능 ✂️

### 사용 기술
 - **MongoDB** : 데이터베이스 관리  🛠️
 - **GridFs** :  대용량 파일 저장 시스템 📦
 - **pyomongo** : MongoDB와 python 간의 인터페이스 💻

### 설치 및 실행 방법
1. 필요한 라이브러리 설치:
        ```bash
        pip install pymongo gridfs
        ```
