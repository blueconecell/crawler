# crawler
## chrome브라우저를 이용해 구글에서 이미지를 크롤링할 수 있습니다.
- 업로드된 크롬드라이버 버전 : ChromeDriver 103.0.5060.53
- [크롬드라이버 다운로드 링크](https://chromedriver.chromium.org/downloads)

## 구글에서 이미지 크롤링하기
 셀레니움 4.0.0 버전을 이용하여 만들었습니다.<br>
 [이 주소](https://www.google.co.kr/imghp)에서 이미지를 검색하여 다운로드 받습니다.<br>
 순서대로 실행시키고 **검색할 키워드**와 **저장할 이미지 이름**을 차례로 입력해주면 **검색할 키워드**를 검색하여 이미지를 크롤링합니다.<br>
- [코드](https://github.com/blueconecell/crawler/blob/main/crawling_google.ipynb)
- [사진 원본으로 받을 수 있는 코드](https://github.com/blueconecell/crawler/blob/main/crawling_raw_images_google.ipynb)
  - 원본사진으로 받게 되면 사진 한장당 2초이상 소요되며 1,000장에 약 33분이 소요됩니다.

## 네이버에서 이미지 크롤링하기
 구글에서 이미지 크롤링하는 코드와 마찬가지로 셀레니움 4.0.0 버전을 이용하였습니다.<br>
 [이 주소](https://search.naver.com/search.naver?sm=tab_hty.top&where=image&query=)에서 이미지를 검색하여 다운받습니다.<br>
 위에서 설명한 방식과 같은 과정을 통해 이미지를 크롤링 합니다.<br>
- [코드](https://github.com/blueconecell/crawler/blob/main/crawling_naver.ipynb)
- [사진 원본으로 받을 수 있는 코드](https://github.com/blueconecell/crawler/blob/main/crawling_raw_images_naver.ipynb)
  - 원본사진으로 받게 되면 사진 한장당 2초이상 소요되며 1,000장에 약 33분이 소요됩니다.
