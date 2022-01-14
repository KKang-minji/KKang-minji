# minjikang
Config files for my GitHub profile.

![KKang-minji's github stats](https://github-readme-stats.vercel.app/api?username=KKang-minji&show_icons=true)
[![KKang-minji's github stats](https://github-readme-stats.vercel.app/api/top-langs/?username=KKang-minji&show_icons=true&hide_border=true&title_color=004386&icon_color=004386&layout=compact)](https://github.com/KKang-minji)

# Protfolio(Master Branch)

   #### [Master Branch](https://github.com/zojae031/Portfolio/tree/master)
   - AAC ViewModel
   - MVVM
   - LiveData
   - Koin
   - dataBinding
 
   
   #### [MVP Branch](https://github.com/zojae031/Portfolio/tree/mvp)
   - MVP 패턴을 적용
   - View와 Presenter의 1:1 대응
   
   # MVVM 구성도

   ![Architecture](https://user-images.githubusercontent.com/31091115/67158166-ac59da80-f36f-11e9-94c5-5e892f4b44ca.png)

   <hr>  

   ```
   자신의 포트폴리오로 사용하는 방법
   
   1. 자신의 Repository로 Fork
   2. Json Branch안의 데이터 변경
   3. 어플리케이션 좌측 상단 메뉴 클릭
   4. 왼쪽 하단 돋보기 클릭
   5. 자신의 깃허브 아이디 선택
   ```

   # 프로젝트 구조

   #### [Repository](https://github.com/zojae031/Portfolio/tree/master/app/src/main/java/zojae031/portfolio/data)

   - Network 상태를 확인 후 Remote / Local 선택
   - Flowable.concat을 이용하여 Local데이터를 보여준 이후 Remote데이터를 보여줌
   

### 1. [Main](https://github.com/zojae031/Portfolio/tree/master/app/src/main/java/zojae031/portfolio/main)

 - 기본적인 데이터를 가져옴
 
   1. 사용자 이미지 : userImage
   2. Drawable에 띄울 Notice정보 : notice

### 2. [Profile](https://github.com/zojae031/Portfolio/tree/master/app/src/main/java/zojae031/portfolio/profile)

- 사용자의 기본 정보를 보여주는 공간
  1. 이름 : name
  2. 나이 : age
  3. 학력 : university
  4. 전공 : major
  5. 병역 : military
  6. 취미 : hobby
  7. Addtional (빈 공간일시 보이지 않음) : additional

### 3. [Project](https://github.com/zojae031/Portfolio/tree/master/app/src/main/java/zojae031/portfolio/project)  

- 사용자의 프로젝트 연혁, 경력정보를 보여주는 공간
  1. 기본 이미지 : image
  2. 제목 : name
  3. 수상 : prize
  4. 내용 : text
  5. 대회 이름 : competition
  6. 시연 영상 주소 : video
  7. 기술 : skills
  8. 깃허브 주소 : git
  9. 기간 : date

### 4. [Tec](https://github.com/zojae031/Portfolio/tree/master/app/src/main/java/zojae031/portfolio/tec)

- 사용자가 사용한 기술을 보여주는 공간
  1. 기술 이름 : image
  2. 기본 이미지 : name
  3. 기술 소스 (빈 공간일시 보이지 않음) : source
     1. 좌측 소스 : data1
     2. 우측 소스 : data2
     3. 왼쪽 버튼 이름 : left
     4. 오른쪽 버튼 이름 : right

```
사용된 라이브러리
1. Gilde
2. rxjava2
3. jsoup
4. gson
5. room
6. constraintlayout
7. recyclerview
8. play-services-ads
9. rxandroid
10. koin

```
