git&gitHub 순서
* 초기 디렉터리 생성 시 순서
1. git init 저장소 등록
2. git branch -M main
    master -> main으로 변경
3. git remote add origin HTTPS주소 붙여넣기
    origin == gitHub HTTPS 주소별칭
--------------------------------------------
* 초기 디렉터리 생성 후 작업 진행 시 순서
1. git add.
    .이란? == 현재 디렉터리 안 모든 파일과 폴더를 뜻함.
2. git commit -m 'message'
    현재 스테이징된 파일의 기록명을 작성(영어, 한글 모두 가능, 짧게 키워드 위주로 작성하기)
    ex) 쇼핑몰 상품 페이지를 만들었다면?
        git commit -m 'shp man-product end'
        git commit -m '쇼핑몰 남자복 완성'
3. git push origin main
    origin == gitHub 주소
    main == Local 내컴퓨터 위치
    해석 == gitHub에 Local작업물을 Push 하겠다.
----------------------------------------------------
위 add->commit->push 순서 중간 중간 작업 확인 리눅스 명령어
1. git status
    Local과 Staging상태에서 작업물의 등록 상태 체크
2. git log
    Commit과 Push 상태에서 작업물의 Commit기록과 업로드 정보 체크
    -----------------------------------------------------------
# H1~H6 Tag(block)
* 제목 태그는 검색 키워드 역할을 하며 페이지 내에서 대/중/소 제목 역할을 한다.
H1이 가장 중요한 제목이며 H1, H2, H3 위주로 많이 사용한다.
----------------------------------------------------
# p Tag(block)
* 단락(내용)태그로 제목 아래 내용을 구성할 때 사용한다.
--------------------------------------------
# em, strong Tag(inline)
* 강조의미를 가진 em, strong은 블록 내에서 강조처리를 할 때 사용한다.
* 제목 태그(h)안에는 em, strong을 사용하지 않는다.