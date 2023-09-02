# ReadWrite Insight

### Reasons Why I Chose the Web Site

- ReadWrite.com은 2003년에 시작된, IT News를 다루는 웹사이트. 기술, 비즈니스 및 혁신 관련 주제를 다루는 웹사이트로, 기술 뉴스, 기사, 리뷰 등을 제공.

<br>

- ReadWrite 주제별 분류
  - AI
  - Blockchain
  - Cyptocurrency
  - Devices
  - Fintech
  - Gambling
  - Industrial
  - Startups
  - Smart Cities
  - Lifestyle
  - Reviews
  - Sales
  - Marketing
  - Customer
  - Service
  - IoT
  - AR/VR
  - Code
  - Data and Security
  - Energy
  - Hack
  - Web
  - Productivity
  - Culture
  - Branding
  - Tech
  - Cloud
  - Connect
  - Deals
  - Fund
  - Health

<br>

- 이에 2003년부터 지금까지의 모든 기사들을 수집해, IT 기술과 관련하여 어떠한 Insight들을 얻을 수 있는 지 분석해보고자 함. 또한 __각 카테고리 별__ 어떤 기술이 당시에 영향력이 있었는 지를 확인해보고자 함

<br>
<br>

### Total Number of Web Articles Collected

- 27,211 건

<br>
<br>

### Data Time Range

- 2003-4-19 - 2023-8-19 (약 20년)

<br>
<br>

### Key Findings and Lessons

- 전반적으로 카테고리 별 해당 기술에 대한 키워드들이 적절하게 추출됨을 확인할 수 있었음

- AI: 2023년 7월 16일에 게시물 게재수 최대치를 찍었고, 해당 주간의 기사들을 살펴봤을 때 OpenAI의 ChatGPT가 화재였음을 확인할 수 있었음

- Web: 2012년 1월 18일에 미국에서 SOPA와 PIPA와 같은 인터넷 저작권 관련 법안에 대해 대규모 인터넷 시위가 발생했었는데, 해당 기간에 게시물 게재 수가 최대치를 찍었던 것을 확인할 수 있었음

- Smart Cities: 2016년에 게시물 게재수가 많았는데, nvidia가 GPU를 활용해 비디오 인식, 자율 주행 자동차 등 스마트시티 혁신을 촉진하기 위해 다양한 기술과 솔루션을 개발하고 있었음을 확인할 수 있었음

<br>
<br>

### Major Challenges

- 키워드 분석에 있어 stopword로 사전 정의하기 애매한 단어들이 다수 등장하여 유의미한 키워드들을 밝혀내는 작업을 어렵게 만들었음

- 전체 글들을 clustering 하는 과정에서, Web 카테고리에 대한 내용이 압도적으로 많은 양을 차지하였기 때문에, 이를 고르게 clustering하기가 쉽지 않았음

<br>
<br>

### Future Work

- 키워드를 분석하는 과정에서 주로 기사의 '본문'에서 키워드를 추출했는데, 기사의 '제목'을 기준으로 키워드를 추출한다면 조금 더 그 당시에 발생한 사건에 대해 눈에 띄는 결과를 확인할 수 있지 않을까 싶음

- N-grams를 이용해서 키워드 추출을 한다면, 기사에서의 연속된 단어 조합을 분석하여 더 의미있는 키워드를 도출할 수 있을 것으로 예상됨
