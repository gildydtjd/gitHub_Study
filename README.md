일단 레파지토리를 한개를 만들고,


1. 레파지토리를 가진 폴더 

2. 레파지토리를 클론한 폴더



2폴더에서

git branch dragon2 를 생성하여 로컬 저장소를 만든다.

git checkout dragon2 로 dragon2 브랜치로 이동한다.

 

 ![1](https://user-images.githubusercontent.com/53888108/128548179-ab58b795-3b45-48d8-aec1-38987a6edf91.JPG)

.txt 파일을 만든다.
![2](https://user-images.githubusercontent.com/53888108/128548199-47f392b9-8aa3-48a5-be3f-fffd7b52a185.JPG)


git add . 을 사용하여 모든 파일을 더하고

커밋을 한다.

 ![3](https://user-images.githubusercontent.com/53888108/128548222-d9a30cc8-fbfe-4348-b7a0-557269844574.JPG)



그리고 git push origin dragon2

origin으로 dragon2 브렌치의 내용을 push 한다.

그러면 새로운 브랜치가 생겼다고 뜬다.

 

git log 를 쳐보면
![4](https://user-images.githubusercontent.com/53888108/128548242-405c1c11-f9ea-44f2-8d1f-0c564084fe86.JPG)


내가 커밋한 이력이 나온다.

 

그리고 github 사이트를 들어가보면
![5](https://user-images.githubusercontent.com/53888108/128548272-b54a42ef-3a42-498d-b6dd-a854a56bf8ad.JPG)


새로운 dragon2라는 놈이 생겨났다 풀리퀘할 권한을 줄거냐라고 뜬다.
![6](https://user-images.githubusercontent.com/53888108/128548288-e8af62ac-6f22-4491-a8c9-a669ad228d66.JPG)

여기서 머지할지 안할지 정할수있다. 머지를 하고

 

1폴더를 들어간다.

여기서 할일

1. 2폴더에서 main에 머지한 내용을 가져온다.

1폴더는 프로젝트를 만든 주인 영역이라 git pull 만 하면 데이터가 가져와진다.
![7](https://user-images.githubusercontent.com/53888108/128548340-64673691-bedf-48cd-8dcc-df7a60de672f.JPG)
![8](https://user-images.githubusercontent.com/53888108/128548344-3085ba4c-edef-417a-8e14-e52fe5278e59.JPG)



용성.txt 를 만들어서 푸쉬한다.

 

이제 해볼일!

폴더2에 똑같은 용성.txt 폴더를 만들고 안에 내용을 다르게 해봐서 오류를 확인한다.

![1212](https://user-images.githubusercontent.com/53888108/128548375-507a2a89-766e-4897-98e0-8fc449739a88.JPG)

변경된 내용을 스테이징하고 커밋한 뒤

![1313](https://user-images.githubusercontent.com/53888108/128548389-621b593a-0ab8-48d5-817b-4d3bb28505ff.JPG)

git push 하면 레파지토리에 잘 변경되어있다.

 

아직 손에 익지 않는 것 같다. 매번 연습해야겠다.
 
이상 github 조금정복 완료. 
