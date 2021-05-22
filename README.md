# wikiExtract

Extract sentences from wikipedia (from https://dumps.wikimedia.org/enwiki/latest/)

### use cases
  python3 wikiEnExtract.py --opt=0 --num=2     
  ........ read 2(num=2) file selected randomly(opt=0) 

  python3 wikiEnExtract.py --opt=1 --indexes 3 10 15     
  ........ read index 3,10,15 file (can be more than 3 files <= several files in one index) 



### 한국어 위키
한글 위키피디아로 부터 문장 추출 (from https://dumps.wikimedia.org/kowiki/latest/)

##### 사용례
  python3 wikiKoExtract.py --opt=0 --num=2   
  ........ 임의로 선택된(opt=0) 2개(num=2)의 파일을 읽어 오는 경우  

  python3 wikiKoExtract.py --opt=1 --indexes 3 4  
  ........ 인덱스(3,4)를 지정하는 경우
