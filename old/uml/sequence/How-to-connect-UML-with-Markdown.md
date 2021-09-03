# Plant UML과 마크다운 엮기

> PlantUML 프록시 서버 활용 방법

1. `.puml` 파일을 repo에 생성 후 `push`
2. `remote repo`에서 `raw`파일 링크 복사
4. 아래와 같이 링크 생성
   ```
   http://www.plantuml.com/plantuml/proxy?cache=no&src=[RAW파일경로]
   ```
5. 생성된 이미지 주소를 `Markdown`파일에 추가

#### 참고
 - https://github.com/jonashackt/plantuml-markdown