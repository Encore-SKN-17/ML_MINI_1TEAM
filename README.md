<!-- 주제: 왼쪽 정렬, 두 번째 크기 -->
<div align="center">
  <h1>머신러닝을 활용 한 영화의 대중성 예측</h1>
</div>

<!-- 팀 소개: 왼쪽 정렬 -->
<div align="left">
  

  <h3>✅ 팀 명</h3>
  <p><strong>SKN17-EDA-Mini-1Team : 🌸 산하엽(Skeleton Flower) 🌸</strong></p>

  <h3>🧑‍💻 팀 멤버</h3>
  <!-- 팀 멤버 정보는 여기에 추가하세요 -->
</div>

| [김주서](https://github.com/kimjuseo71) | [홍문봉](https://github.com/Glowcloudy) | [양정민](https://github.com/Yangmin3) | [한 훈](https://github.com/Hoonieboogie) | [김주영](https://github.com/samkim7788) |
|:--------------------------------------:|:--------------------------------------:|:-------------------------------------:|:---------------------------------------:|:---------------------------------------:|
| <img src="https://cdn.discordapp.com/attachments/1390125153542869159/1397415348168294500/370391fd-2fe0-4a83-a79a-2e462210fb35.png?ex=6881a3f5&is=68805275&hm=07c0fcb9b46efe06fc254dc8afda222f6500183de06e7959a3b7749620a79c00" width="150" height="250"> | <img src="https://cdn.discordapp.com/attachments/1395586816832438434/1400378419052679258/resized_150x252.jpg?ex=688c6b88&is=688b1a08&hm=5bf0b83859037d36f9a104cec36f12661e1801e6e9a014e8f1dc599f576be489&" width="150" height="250">| <img src="https://cdn.discordapp.com/attachments/1390125153542869159/1397420134108499988/01f607c7-1561-4973-bf47-038a40ecd0f7.png?ex=6882f9ea&is=6881a86a&hm=ddbddf82df66befb38a0a710029e85c2784c04d990db359d23c21eb8240bad8d" width="150" height="250"> | <img src="https://cdn.discordapp.com/attachments/1390125153542869159/1397424014686818425/3f02d83d-8363-45c2-9a5e-fd488063d006.png?ex=6881ac07&is=68805a87&hm=9af426f52fed283f64867cc1f8f25d4a35f2aa08d5af1feb96ca1c78db59efda" width="150" height="250"> | <img src="https://cdn.discordapp.com/attachments/1395586816832438434/1397395933632659466/animal-6814871_1280.png?ex=688191e0&is=68804060&hm=b7d7143e4ededd4f2528517af364723d733b3cc496c77607c015f423d2ba7609" width="150" height="250"> |










---

## 🗓️ (Mini)프로젝트 기간
✔️ 2025.07.25 ~ 2025.08.01

## 📖 프로젝트 소개

- 영화에 대한 대중성 예측

## 📌 프로젝트 배경

- 많은 공개 영화 데이터셋에서는 관람객 수나 박스오피스 수익과 같은 직접적인 대중성 지표가 포함되어 있지 않다.
   대중성은 도달 범위(평가 참여 인원- Votes)와 만족도(평균 평점- Rating)의 곱으로 설명할 수 있다. 평가 수는 관심도, 평균 평점은 만족도를 나타내며, 많은 사람이 보고 긍정적으로 평가한 영화일수록 대중성이 높다.
   행동 과학 연구에서도 사람들이 콘텐츠 선택 시 이 두 요소를 함께 고려한다는 점이 확인되었다.




### 📊 Votes × Rating 지표 기반 예측 (두 가지 가정 비교)

| 영화 | Votes × Rating | 가정 1: 평점 고정 (8.0) → 예상 Votes | 가정 2: Votes 고정 (50,000) → 예상 평점 |
|:----:|:---------------:|:--------------------------:|:----------------------------:|
| 영화 B | 900,000 | 112,500 | 18.0 |
| 영화 D | 512,000 | 64,000 | 10.24 |
| 영화 A | 410,000 | 51,250 | 8.2 |
| 영화 C | 273,000 | 34,125 | 5.46 |

  ### Votes × Rating 그래프 (텍스트 바 차트)
 1. 영화 B: ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ 900,000
 2. 영화 D: ▓▓▓▓▓▓▓▓▓▓▓▓        512,000
 3. 영화 A: ▓▓▓▓▓▓▓▓            410,000
 4. 영화 C: ▓▓▓▓▓               273,000


- 이 지수는 단순한 직관을 넘어 실무 분석에서 널리 활용되며, 흥행 예측 모델에서 중요한 변수로 사용되고 있다.

## 출처
  
  (1): Arcelus, F. J., & Srinivasan, G. (2020). Predicting box-office revenues of motion pictures. Journal of the Operational Research Society, 71(3), 364–378.
  🔗 https://doi.org/10.1080/01605682.2019.1574199

  (2):  Analytis, P. P., Barkoczi, D., & Herzog, S. M. (2018). Social learning strategies for matters of taste. Nature Human Behaviour, 2(6), 415–424.
  🔗 https://doi.org/10.1038/s41562-018-0333-2

  (3):  Sharda, R., & Delen, D. (2006). Predicting box-office success of motion pictures with neural networks. Expert Systems with Applications, 30(2), 243–254.
  🔗 https://doi.org/10.1016/j.eswa.2005.07.019

</div>


## 🎯 프로젝트 필요성


# 기술 스택
<img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=Python&logoColor=white"> <img src="https://img.shields.io/badge/pandas-150458?style=plastic&logo=pandas&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=plastic&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=plastic&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/numpy-013243?style=plastic&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/matplotlib-11557c?style=plastic&logo=matplotlib&logoColor=white"> <img src="https://img.shields.io/badge/seaborn-0C5A5A?style=plastic&logoColor=white">


## 데이터 출처

https://www.kaggle.com/datasets/raedaddala/imdb-movies-from-1960-to-2023?utm_source=perplexity

## ✅ 1차 전처리: 기본 정제
### 1. 불필요 컬럼 제거
영화
- 상영국가 결측치는 'Unknown' 으로 대체
- 의미 없는 Feature: 줄거리, 링크, 포스터 등
- 상영등급(MPA Rating) 'Not Rated' 및 결측치 → 'Unrated' 로 통일
- 여러 연도에 분산된 데이터를 하나의 통합 DataFrame으로 구성
<img width="1345" height="606" alt="image" src="https://github.com/user-attachments/assets/a2689d21-c4bb-4180-b397-449817b203cc" />

음악
<img width="530" height="630" alt="image" src="https://github.com/user-attachments/assets/3834df7b-a2a4-4472-ac6b-414dbd4292f0" />



## ✅ 2차 전처리: 시각화 및 분석 목적 정제
### 6. 상영시간 이상치 제거
- 전체 및 10년 단위 상영시간을 Box Plot으로 시각화
- IQR 기준으로 연도별 이상치 제거
<img width="1070" height="566" alt="image" src="https://github.com/user-attachments/assets/d090106e-3348-47d9-a740-b9b003abeffd" />


### 7. 다중 국가/장르 처리
- 리스트 형태 다중 장르 → 행 단위 분해
<img width="594" height="167" alt="image" src="https://github.com/user-attachments/assets/f2718f43-cd98-4128-be02-573c1d253ff8" />
<img width="790" height="493" alt="image" src="https://github.com/user-attachments/assets/60551bb9-a870-46b7-a593-ae45e92b4980" />

예시:
<pre>
{"훈이의 모험", [액션, 로맨스]}  
→ {"훈이의 모험", 액션}  
→ {"훈이의 모험", 로맨스}
{'hard_rock', 'alternative_rock', 'metal_rock' }  
→ {'rock'}
{'electro','edm','house','dance','techno','electronic'}  
→ {'Electronic'}
</pre>

## EDA 결과
### 10년 단위별 영화 러닝타임 분포 (이상치 제거)
![EDA 결과 이미지](https://cdn.discordapp.com/attachments/1397927714987704332/1397929318688227489/boxplot_decades_runtime.png?ex=688382a1&is=68823121&hm=20e50791e789a218aed5d69a64ecd1292dc773b02905cb1cb823e4f6fe638d2d&)
### 주요 5개국 연도별 평균 영화 러닝타임 변화
![EDA 결과 이미지](https://cdn.discordapp.com/attachments/1397927714987704332/1397929833949822977/top5_country_avg_runtime.png?ex=6883831c&is=6882319c&hm=4031b6fef34b46ee7c015eeeeef84e382378d7fd5ec65b628f0a4c9e12d48543&)
### 음악 장르별 평균 곡 길이 비교
![EDA 결과 이미지](https://cdn.discordapp.com/attachments/1397927714987704332/1397927738853167247/image.png?ex=68838129&is=68822fa9&hm=4a3f3f8043334ed5caf1050cc6c0a6b3749352c11223d3951c067495414b2c1a&)
### 10년 단위별 음악 길이 분포 (이상치 제거)
![EDA 결과 이미지](https://cdn.discordapp.com/attachments/1397927714987704332/1397939090325897317/image.png?ex=68838bbb&is=68823a3b&hm=cb15910347c7af0ea5b30183f71fa137eb6ccb019e9e4db4c7861f2e8c1b7f0c&)
### **연도별 영화 vs 음악 러닝타임 추이 비교**
![EDA 결과 이미지](https://cdn.discordapp.com/attachments/1395586816832438434/1397882426943995986/image.png?ex=688356f5&is=68820575&hm=f07b9104fccbaa3a81bbfe2de191bb9e2872b8a13ae84042902ad55f8f72c583&)


## 결론
본 조의 가설은 영화의 러닝타임은 증가하고, 음악의 러닝타임은 감소하고 있다는 전제로 시작하며, 위의 시각화 자료들은 이 가설을 뒷받침하는 경향을 잘 보여주고 있습니다.

🎬 **영화 러닝타임 증가의 배경**
영화의 러닝타임이 길어지는 주요 원인 중 하나는 세계관 중심의 시리즈 영화의 등장입니다.
예를 들어, 마블 시네마틱 유니버스(MCU)나 아바타 시리즈처럼 확장된 세계관을 지닌 영화들은 각 인물과 배경 설정, 서사적 연결성 설명 등을 포함해야 하므로 자연스럽게 러닝타임이 늘어납니다.

또한, OTT 플랫폼의 발달도 큰 영향을 미쳤습니다. 시청자들은 영화나 드라마 시리즈를 시간 제약 없이 몰아보기(Binge-watching) 할 수 있게 되었고, 이에 따라 제작자들은 보다 긴 분량의 콘텐츠 제작이 가능하고 선호되는 환경을 갖추게 되었습니다.

🎵 **음악 러닝타임 감소의 배경**
음악의 경우, 과거와 달리 소비자들이 음악을 접하는 주요 경로가 TV나 라디오보다 SNS 플랫폼(예: 틱톡, 인스타그램 릴스, 유튜브 숏츠) 으로 옮겨가면서 변화가 나타났습니다.

이러한 플랫폼에서는 짧고 임팩트 있는 콘텐츠가 선호되며, 특히 배경음악(BGM)이나 챌린지 콘텐츠에 적합하도록 곡의 러닝타임이 점점 짧아지는 경향을 보이고 있습니다.
이는 음악의 소비 구조와 유통 방식 변화가 음악 길이에도 직접적인 영향을 주고 있음을 시사합니다.

## 회고
- 김주서:처음 데이터 그래프를 만들며 단위 설정과 해석의 중요성을 깨달았습니다. 변화 전달을 위해 범위를 세밀하게 조절하고, 효과적인 표현 방식에 대해 고민하게 되었습니다.
- 홍문봉: 처음에 주제를 정하는 과정에서 여러가지 주제들이 나왔지만 결국 제가 추천한 주제로 선택이 되어 큰 그림은 팀원들이 이해를 하고 있지만 세세한 부분에서는 조율해야 하는 부분과 각각의 팀원들에게 작업 할당량을 부여 및 결과 도출에서 굉장히 힘들었습니다. 또한 어떻게 하면 우리의 가설에 대해 타당성이 있고 남들이 봤을 때 바로 이해할 수 있는 그래프를 찾는데 시간이 많이 소요되었으며 처음 그려보는 트리맵의 경우 각가의 박스사이 빈 공간이 생기는 이슈 해결을 위해 pad=False를 활용하여 박스 사이 공백을 매꾸었으며 각각의 장르의 평균 러닝타임을 구하는 방식에서 for문을 이용하여 각 장르별 평균러닝타임을 구하여 트리 맵에 표현 할 수 있었습니다.
- 양정민: 방대한 음악 데이터셋을 시각화하여 패턴과 트렌드를 분석하는 데 집중하였으나 데이터 양이 많아서 오류가 난건지 오류가 자주 발생하고 그로 인해 실수가 잦아져서 팀원의 도움을 구해 문제를 해결하고     동시에 관련 논문들을 많이 읽으며 레퍼런스 정리에 많은 시간을 투자했다.이를 통해 데이터 이해도를 높이고 프로젝트의 기초를 탄탄히 다질 수 있었다.
