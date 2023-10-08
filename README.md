# 📺 MY_Media
Youtube API 를 활용하여 로그인 된 계정의 구독리스트와 카테고리별 인기동영상을 출력하고, 입력어에 해당하는 영상을 검색하고, 좋아요 한 항목이 마이페이지에 표시되는 어플을 구현하였습니다.


## ⚙ 프로젝트 구성
#### Architecture - MVVM
<img src="https://github.com/sinw212/My-Media/assets/53486320/c5b2af63-d463-458c-9c40-76a61548b600" width="550" height="400">

#### Stack
`ViewModel` `AAC` `LiveData` `Coroutine`

#### Data Storage
`SharedPreferences` `ContextProvider`

#### Image Loader
`Coil`

#### Network
`Retrofit`

---

## ⏰ 개발 기간 
2023.09.25 ~ 2023.10.06  


## 📒 팀 노션
https://www.notion.so/12-S-A-f79dc026055d4ec98d97ff1e3bffe057


## 👨‍👩‍👦‍👦 멤버 구성
<table>
  <tbody>
    <tr>
      <td align="center"><img src="https://github.com/boradorying.png" width="100px;" alt=""/><br /><sub><b>팀장 : 박세준</b></sub><br /></td>
      <td align="center"><img src="https://github.com/sinw212.png" width="100px;" alt=""/><br /><sub><b>팀원 : 김소현 </b></sub></a><br /></td>
      <td align="center"><img src="https://github.com/Odin5din.png" width="100px;" alt=""/><br /><sub><b>팀원 : 김지견</b></sub></a><br /></td>
      <td align="center"><img src="https://github.com/sooj36.png" width="100px;" alt=""/><br /><sub><b>팀원 : 이수진</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

:runner: 박세준
- [x]  VideoDetailFragment
- [x]  MyVideoFragment 

:runner: 김소현
- [x]  MainActivity
- [x]  HomeFragment (구독리스트)

:runner: 김지견
- [x]  searchFragment

:runner: 이수진
- [x]  HomeFragment (카테고리별 인기동영상)


## 📌 기능 설명
#### MainActivity
- BottomNavigationView
- OAuth 2.0 인증

#### HomeFragment
- 로그인 된 계정의 구독 계정 리스트 출력
- 카테고리별 인기동영상 출력 (전체, 동물, 음악, 게임, 유머)

#### SearchFragment
- 입력한 검색어에 해당하는 영상 출력

#### VideoDetailFragment
- 제목, 내용, 조회수, 좋아요 수 표시
- 해당 영상 썸네일 공유 기능
  
#### MyVideoFragment
- 디테일페이지 에서 '좋아요' 클릭한 영상 목록 출력
- 팀 깃헙, 팀 노션 페이지 이동 버튼

---

## 📱 구현 화면
<img src="https://github.com/sinw212/My-Media/assets/53486320/31809bfa-8320-4bae-8b12-1e0e5b9498a2" width="660" height="450">
<img src="https://github.com/sinw212/My-Media/assets/53486320/d38c999e-6aab-494c-9435-f36395ed2fa0" width="660" height="450">
