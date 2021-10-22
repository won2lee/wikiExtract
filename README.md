# wikiExtract

Extract sentences from wikipedia (from https://dumps.wikimedia.org/enwiki/latest/)

if wget module is not installed => pip3 install wget

### use cases
    python3 wikiExtract.py --lang='en' --opt=0 --num=2         
  ........ read 2(num=2) files selected randomly(opt=0) 

    python3 wikiExtract.py --lang='en' --opt=1 --articles 3 10 15         
  ........ read article index 3,10,15 (can be more than 3 files <= several files by one index) 

  Extracted sentences are stored in folder wikiE/


### 한국어 위키
한글 위키피디아로 부터 문장 추출 (from https://dumps.wikimedia.org/kowiki/latest/)

##### 사용례
    python3 wikiExtract.py --lang='ko' --opt=0 --num=2   
  ........ 임의로 선택된(opt=0) 2개(num=2)의 파일을 읽어 오는 경우  

    python3 wikiExtract.py --lang='ko' --opt=1 --articles 3 4  
  ........ 아티클 인덱스(3,4)를 지정하는 경우
 
  추출된 결과는 wikiK/ 폴더에 저장
