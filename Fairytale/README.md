# 📖  OwnStory 
영어 동화를 생성하여 부모님 목소리로 읽어주는 서비스

<br>

## 🙌 AI 수도권 3반 12조

😀 Members: 김은지, 김진상, 소정현, 원장희, 이형길, 장성현, 최재호, 최태양

<br>

## 📃 목차

1.[ 개발 배경 및 목적](#1-개발-배경-및-목적-)

2.[ 기능](#2-기능-)

3.[ 서비스 Flow](#3-서비스-flow-)

4.[ 3 Tier Architecture](#4-3-tier-architecture-)

5.[ DB 설계](#5-db-설계-)

6.[ 개발 환경](#6-개발-환경-%EF%B8%8F)

7.[ 유저 가이드](#7-유저-가이드-)

<br>

## 1. 개발 배경 및 목적 💡

>현대 사회에서는 많은 부모님들이 자녀의 언어 발달과 교육에 더 많은 관심을 가지고 있습니다. 특히 영어 유치원 진학 경쟁이 점점 치열해지고 있으며, 조기 영어 교육에 대한 관심도 크게 증가하고 있습니다. 영어 동화책을 선택하고 구매하는 과정은 가정에게 경제적인 부담과 시간적인 압박을 주는 요소로 작용하고 있습니다.
위와 같은 배경을 고려하여, 우리는 맞춤형 서비스를 통해 어린이들의 지적 및 언어적 능력, 정서 발달을 촉진하고 부모님과의 정서적 교감 경험을 증진시킬 수 있는 솔루션을 개발하고자 합니다. 이를 통해 동화책 선정 과정을 간소화하고 구매 비용을 절약함으로써 가정의 경제적, 시간적 부담을 줄일 수 있습니다.
또한, 이 서비스를 통해 어린이들은 동화 컨텐츠에 쉽게 접근할 수 있으며, 영어에 대한 흥미를 유발할 수 있습니다. 더 나아가, 추후에는 영어 이외의 다른 언어로도 서비스를 확장할 예정입니다.
위의 목표를 달성하기 위해 우리는 어린이들이 즐겁게 동화를 읽을 수 있는 다양한 기능과 컨텐츠를 제공할 계획입니다. 이를 통해 어린이들의 교육과 성장을 지원하고, 가정에서의 동화책 구매와 선정 과정에 대한 부담을 덜어주고자 합니다.

기존 상황

* 영어 유치원 진학 경쟁이 치열
* 조기 영어 교육에 대한 관심이 높아지는 추세
* 영어 능력 필요성 증가
* 동화책을 선택하고 구매하는 과정은 반복되어 시간과 비용의 부담을 초래
* 기존의 동화책은 어린이들의 상상력과 창의성을 제한하며, 언어 발달과 정서 발달에 있어서도 한계 발생


>이러한 상황에서 우리의 목적은 기존의 상황과 비교하여 혁신적인 솔루션을 제공하여 다음과 같은 효과를 이끌어내는 것입니다:


* **맞춤형 서비스 제공과 상상력 자극**: 어린이들에게 맞춤형 서비스를 제공하고, 상상력과 창의성을 자극하여 지적/언어적 능력과 정서 발달을 촉진
* **간소화된 동화책 선정 과정과 경제적인 부담 절감**: 동화책 선정 과정을 간소화하고 구매 비용을 절약함으로써 가정의 경제적, 시간적 부담 절감
* **동화 컨텐츠의 쉬운 접근성**: 온라인 플랫폼으로 동화 컨텐츠에 대한 접근성을 간편화
* **영어에 대한 흥미 유발**: 영어에 대한 흥미를 유발하여 어린이들이 영어 학습에 보다 적극적으로 참여하도록 독려
* **혁신적인 기술과 서비스 제공**: 최신의 인공지능 기술과 창의적인 콘텐츠 개발로 어린이들에게 동화책을 즐겁게 읽을 수 있는 다양한 기능을 제공
* **다국어 지원으로 확장 가능한 플랫폼**: 영어 이외의 다른 언어로도 서비스를 확장하여 전 세계 어린이들에게 다양한 언어 학습 기회를 제공
  
  
>이를 통해 우리는 기존의 동화책 제공 방식과 비교하여 👉<u>**어린이들에게 혁신적인 영어 학습 환경을 제공함으로써, 그들의 교육과 성장을 지원하는 동시에, 부모님들의 부담을 덜어주고, 정서적인 교감 경험을 증진시키는 플랫폼**</u>👈을 구축하고자 합니다.

<br>

## 2. 기능 🛠
* 키워드 기반 동화 생성
* 이미지 기반 동화 생성
* TTS 음성 인식
* 게시판 이용 - 사용자 평가 및 다운로드, 저장 기능 제공

<br>

## 3. 서비스 Flow 🔍
![image](https://github.com/AIVLE-School-Third-Big-Project/Fairytale/assets/122524846/2525c085-74a2-4c1a-a35f-cbf950d6b162)

<br>

## 4. 3 Tier Architecture 🏢
![image](https://github.com/AIVLE-School-Third-Big-Project/Fairytale/assets/122524846/6b30e54a-0206-46b1-af08-0664dd4c5574)

<br>

## 5. DB 설계 🧱
![image](https://github.com/AIVLE-School-Third-Big-Project/Fairytale/assets/122524846/c4a5f4b4-464f-45f0-ad76-691924baa782)

<br>

## 6. 개발 환경 ⚙️
- Front-End


| HTML | CSS | JS | React | Figma |
| --- | --- | --- | --- | --- |
| ![image](https://cdn.icon-icons.com/icons2/2790/PNG/512/html_filetype_icon_177535.png) | ![image](https://cdn.icon-icons.com/icons2/2790/PNG/512/css_filetype_icon_177544.png) | ![image](https://cdn.icon-icons.com/icons2/2699/PNG/512/javascript_vertical_logo_icon_168606.png) | ![image](https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png) | ![image](https://cdn.icon-icons.com/icons2/2699/PNG/512/figma_logo_icon_171159.png)


- Back-End and Cloud

| Python | Django | django REST framework | MySQL | AWS |
| --- | --- | --- | --- | --- |
| ![image](https://cdn.icon-icons.com/icons2/2699/PNG/512/python_vertical_logo_icon_168039.png) | ![image](https://cdn.icon-icons.com/icons2/2622/PNG/512/brand_django_icon_158932.png) | ![image](https://images.velog.io/images/poiuyy0420/post/c8d8fd01-0a25-4866-aa3a-11ccc70d66af/d_rest.png) | ![image](https://cdn.icon-icons.com/icons2/2415/PNG/512/mysql_original_wordmark_logo_icon_146417.png) |  ![image](https://cdn.iconscout.com/icon/free/png-256/free-aws-1869025-1583149.png)

- etc

| GitHub | VS Code | Microsoft Teams | Notion | Slack | Discord |
| --- | --- | --- | --- | --- | --- |
| ![image](https://cdn.icon-icons.com/icons2/2415/PNG/512/github_original_wordmark_logo_icon_146506.png) | ![image](https://cdn.icon-icons.com/icons2/3053/PNG/512/microsoft_visual_studio_code_alt_macos_bigsur_icon_189952.png) | ![image](https://cdn.icon-icons.com/icons2/2397/PNG/512/microsoft_office_teams_logo_icon_145726.png) | ![image](https://cdn.icon-icons.com/icons2/2389/PNG/512/notion_logo_icon_145025.png) | ![image](https://cdn.icon-icons.com/icons2/2699/PNG/512/slack_tile_logo_icon_168820.png) | ![image](https://cdn.icon-icons.com/icons2/1945/PNG/512/iconfinder-discord-4661587_122459.png) |

<br>

## 7. 유저 가이드 👀
requirements.txt 설치시 TTS 오류 관련 문제<br>
https://visualstudio.microsoft.com/visual-cpp-build-tools/<br>
C++ build tools 다운로드 후 C++ 를 사용한 데스크톱 개발 선택하여 설치

### 실행 방법
#### 1. 가상환경 설정
python -m venv 가상환경이름

cd 가상환경이름\Scripts

activate

#### 2. requirements 설치
pip install -r requirements.txt

#### 3. 실행
python manage.py runserver
<br>
