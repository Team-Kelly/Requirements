# Plant UML과 마크다운 엮기

1. `.puml` 파일을 repo에 생성 후 `push`
2. `remote repo`에서 원본 파일 링크 복사
3. http://www.plantuml.com/plantuml/ 접속
4. 아래와 같이 입력
   ```puml
   @startuml
   !include https://raw.githubusercontent.com/Team-Kelly/Requirements/main/uml/sequence/app-server-ready.puml
   @enduml
   ```
5. 생성된 이미지 주소를 `Markdown`파일에 추가