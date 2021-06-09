# python-web-crawling
Chrome web crawling using python

## 설치 방법
1. [크롬 드라이버](https://chromedriver.chromium.org/downloads)를 자신의 크롬 버전과 일치하는지 확인한다.
2. 크롬 드라이버 해당 소스와 같은 위치에 복사한다.
3. 해당 파이썬 코드를 실행한다.

## 사용 방법
1. google_input_crawl: search_path에 폴더 위치 생성 후 코드 실행

    ``` python
    search_name = input("검색하고 싶은 키워드 : ")
    search_limit = int(input("원하는 이미지 수집 개수 : "))
    search_path = "d:/images/"
    ```
2. google_input_crawl: searchList 변수에 저장하고 싶은 명령어 삽입 후 실행

    ``` python
    searchList = ['사과', '나주배']
    ```


