# AirDnB : 개발 행사 및 대회 소식 알림봇
<div align="center">
<img src="https://github.com/khuda-4th/khuda_de_project/assets/64704608/30a4b397-cc10-4505-a46d-60fb7eb32219" width="400" height="400"/>
<p align="center">
   <img src="https://img.shields.io/badge/Apache_Airflow-E5426E?style=flat-square&logo=Apache Airflow&logoColor=white" alt="Apache Airflow badge">
    <img src="https://img.shields.io/badge/Amazon_S3-61DAFB?style=flat-square&logo=Amazon S3&logoColor=black" alt="Amazon S3 badge">
    <img src="https://img.shields.io/badge/Amazon_AWS-EE4C2C?style=flat-square&logo=Amazon AWS&logoColor=white" alt="Amazos AWS badge">
    <img src="https://img.shields.io/badge/Prometheus-0467DF?style=flat-square&logo=prometheus&logoColor=white" alt="prometheus badge">
    <img src="https://img.shields.io/badge/Grafana-ea4335?style=flat-square&logo=grafana&logoColor=white" alt="grafana badge">
    <img src="https://img.shields.io/badge/Python-5C3EE8?style=flat-square&logo=python&logoColor=white" alt="python badge">
  </p>
</div>

`AirDnB` 는 **Airflow를 이용한 개발 행사 및 대회 소식 알림봇**입니다.
<br>

>주기적으로 데이터를 크롤링하고 개발 뉴스 및 행사에 대한 정보를 간략하게 요약하는 알림봇입니다.

<br>

## 🔍 Preview
- **`kakaotalk`** - [카카오톡 채널 등록](http://pf.kakao.com/_TxiInG)

<img src="https://github.com/khuda-4th/khuda_de_project/assets/64704608/64da25b5-8ac0-40ec-b7be-bcdc72f200c2" width="400" height="600"/>

>1. 카카오톡에서 'AirDnB' 친구 추가
>2. 메시지 프롬프트 창에 velog 인기글, 공모전, 개발 행사 정보 질문 선택
>3. 알림봇이 질문에 따라 요약한 정보를 메시지로 제공
>4. 필요시 첨부된 링크를 통해 자세한 정보 확인 가능

<br>


- **`slack`**

<img src="https://github.com/khuda-4th/khuda_de_project/assets/64704608/474de51a-e07f-469d-9678-f105db4f8791" width="400" height="600"/>



<br>


## 🧑🏻‍💻 Members

>**팀 `에어디앤비(AirDnB)`입니다!**<br><br>*에어비앤비에서 처음 airflow를 시작했기에 유사한 느낌을 주었습니다. air는 airflow의 air, d는 data, b는 bot 입니다!*

<br>

| 김건형 | 김효준 | 노명은 | 유혜지 |
| :-: | :-: | :-: | :-: |
| <img src='https://avatars.githubusercontent.com/u/60197194?v=4' height=130 width=130></img> | <img src='https://avatars.githubusercontent.com/u/143721160?v=4' height=130 width=130></img> | <img src='https://avatars.githubusercontent.com/u/90135669?v=4' height=130 width=130></img> | <img src='https://avatars.githubusercontent.com/u/90139122?v=4' height=130 width=130></img> |
| <a href="https://github.com/GU-0" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/hyojun03" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/NoMyeongEun" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/HyejiYu" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> |

| 조민서 | 최용빈 | 한상진 | 허윤지 |
| :-: | :-: | :-: | :-: |
| <img src='https://avatars.githubusercontent.com/u/87311912?v=4' height=130 width=130></img> | <img src='https://avatars.githubusercontent.com/u/64704608?v=4' height=130 width=130></img> | <img src='https://avatars.githubusercontent.com/u/49024115?v=4' height=130 width=130></img> | <img src='https://avatars.githubusercontent.com/u/111333350?v=4' height=130 width=130></img> |
| <a href="https://github.com/Minseo-Jo" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/whybe-choi" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/eu2525" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> | <a href="https://github.com/myeunee" target="_blank"><img src="https://img.shields.io/badge/GitHub-black.svg?&style=round&logo=github"/></a> |

<br>

## ⌘ Project BackGround

<br>

* **`배경`** : 개발 행사나 소식을 모아놓은 사이트는 이미 존재하지만, 개발 행사나 세미나 등과 같은 소식이 뭐가 있나 매번 들어가기 번거롭다.

* **`목표`**:  개발 행사 및 소식을 쉽고 간단하게 접할 수 있는 서비스를 제공합니다.

<br>


## ⚙️ Service Architecture
<img width="1101" alt="스크린샷 2023-12-02 오후 2 53 00" src="https://github.com/khuda-4th/khuda_de_project/assets/64704608/bab84871-4e70-4df0-9dad-060ad79a3b8f">


**[ 단계별 수행 과정 ]**
![image](https://github.com/myeunee/hello-world/assets/111333350/31e4c765-caac-43d6-a289-3616f301483b)

![image](https://github.com/myeunee/hello-world/assets/111333350/0ff5e885-4a27-40ef-8d4f-37ead60627b4)

<br>

## 💿 Data


## 📚 Further Information
