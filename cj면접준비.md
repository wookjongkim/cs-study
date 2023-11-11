## PT 관련 질문

<details markdown = "1">
<summary>데이터 분석 어떻게 진행했냐</summary>
우선 전국의 모든 학교마다 고유한 코드가 있었습니다. 이것을 나이스라는 교육정보 포털에서 다운로드 한 뒤에 이 코드를 바탕으로 식단 정보를 다운로드 했습니다.<br>
이때 식단 정보가 한건에 최대 1000개의 데이터만 다운로드 할 수 있어서, 자바라는 언어를 사용해서 다운로드 자동화를 위한 코드를 설계했고, 이를 바탕으로 750만개의 데이터를 다운로드 했습니다.<br>
다운로드 한 식단 데이터는 데이터베이스에 저장되게 하였고, 분석시에는 mysql이라는 언어를 사용해서 분석하였습니다.<br>
</details>

<details markdown = "1">
<summary>분석했을때 국 메뉴가 몇개였나??</summary>
단순히 국의 이름을 기반으로 했을텐 총 2만 몇개 정도가 나왔었습니다. 하지만 너무 많이 나왔다고 생각해서 데이터를 분석해보니 같은 메뉴임에도(ex: 콩나물 국, 맑은 콩나물국) 이름이 좀 다른 경우가 있었습니다.<br>
따라서 같은 메뉴를 추리기 위한 처리 과정이 필요했고, 메뉴가 너무 많아서 마라탕의 순위에 영향을 끼칠수 있는 메뉴에 대해서만 데이터를 추렸습니다.<br>
</details>

<details markdown = "1">
<summary>마라탕 재료 뭐있냐</summary>
채소류 부터 보자면 청경채,알배추,숙주,콩나물,푸주나 건두부가 있고 이외에는 중국당면이나 분모자와 소고기 또는 양고기가 있다.<br>
향신료 에는 깨 소스나 식초의 일종인 흑초를 넣기도 하지만<br>
핵심 적인 매운맛을 내는 것은 크게 마유와 라유로 나뉨.<br>
라유 : 매운맛을 내는 고추 기름<br>
마유가 바로 독특한 매운맛을 만들어주는 비밀.(얼얼한 느낌을 내줌), 기름에 다양한 향신료 넣어 만듬.(초피, 후추, 정향, 팔각,회향,쯔란 등)<br>
</details>

<details markdown = "1">
<summary>니가 말하는 레시피가 뭐냐?</summary>
호불호의 가장 큰이유는 매운맛과 향인것 같습니다. 이때 라유의 양은 줄이고, 마유에서 산초의 양을 조금 더 늘여서 매운맛은 줄이돼 얼얼한 맛을 유지함으로서 차별화된 맛을 개발할 수 있을거같습니다.<br>
그리고 보통 사골 육수를 베이스로 하고 치킨 스톡을 사용하는 것으로 알고 있는데 닭 육수를 주 베이스로 하면 조금더 깔끔한 맛을 낼수 있을거라 생각합니다.<br>
</details>

<details markdown = "1">
<summary>레시피 분석 및 표준화 작업, 상품 소싱, 합포장, 유통 순</summary>
첫번째 단계는 밀키트에 사용될 레시피를 분석하고, 대량 생산을 위한 표준화 작업(각 재료의 양, 조리 순서 및 시간, 재료 처리 방법 등을 명확히 기록)<br>
상품 소싱은 필요한 식자재나 포장 재료를 공급하는 공급처를 찾고, 가격이나 품질 등을 고려해서 최적의 공급처를 선정하는 과정입니다.<br>
합포장은 선정된 재료들을 밀키트로 조합하여 포장하는 작업이고, 유통은 완성된 밀키트를 소비자에게 배송하는 과정입니다.<br>
</details>

<details markdown = "1">
<summary>1분 자기소개</summary>
안녕하십니까 cj프레시웨이 영업직군 지원자 김욱종입니다. 저는 차별화된 영업 전략을 세우기 위해 두가지 역량을 쌓아왔습니다.<br>
첫째 의사소통입니다. 학부 시절 다양한 프로젝트에서 팀장의 역할을 맡아 여러 팀원들의 참여 의지를 높이고 의견을 조율해본 경험이 있습니다.<br> 
단순히 업무 배분 뿐 아니라 팀원들의 어려움을 경청하여 그들의 상황을 파악하고, 도움을 주거나 해결방안을 제시하여 프로젝트를 성공적으로 마무리 하였습니다.<br>
두번째로 데이터 분석 능력입니다. 학부 연구생 시절 이산화질소 측정 연구 과제 수주를 위해 타 연구실에 비해 산출 오차가 적다는 점을 수치적으로 계산 및 비교하여 강조하였고, 
최종적으로 해당 연구과제를 수주하였습니다. 또한 데이터 분석 능력을 바탕으로 추가 예산을 수주한 경험이 있습니다. 
국립 환경 과학원에서 맡긴 장비의 관측 한계점을 증명하고, 장비 튜닝을 통해서만 산출 오차를 줄일수 있다는 점을 증명하여 
최종적으로 추가 예산을 따내었고 산출오차를 20%에서 70%까지 개선하는 성과를 거둘 수 있었습니다.<br>
이러한 의사소통 능력과 데이터 분석 능력을 바탕으로 차별화되고 합리적인 영업 전략을 세우는 영업사원이 되겠습니다. 감사합니다.<br>
</details>

<details markdown = "1">
<summary>cj 프레시웨이 지원 동기</summary>
cj프레시웨이의 경우 데이터를 활용하여 고객분들께서 보다 편하고, 합리적인 가격에 좋은 품질의 상품을 주문하고 재떄 사용할 수 있도록 디지털 전환을 계속해 나가고 있습니다.<br>
이러한 노력을 바탕으로 업계 최초 cloud 전환을 통해 고객분들에게 안정적이고 빠른 서비스를 제공하고 있으며, 고객분들의 사업에 필요한 모든 데이터를 다각적으로 분석하여 인사이트를 제공하고 있습니다.<br>
디지털 전환을 바탕으로 고객 중심적 솔루션을 제공하고 있는 귀사에서, 학부와 연구생 시절 키웠던 데이터 분석 능력과 이를 기반으로 한 설득 경험, 여러 프로젝트에서 팀장의 역할을 맡아 팀원들의 참여 의지를 높여준 저의 의사소통 능력이 영업직군에 적합하다고 생각하였습니다.<br>
저의 역량을 바탕으로 귀사에서 데이터 중심적이고, 차별화된 영업 전략을 바탕으로 고객과 상생하는 FRESH한 인재로 성장해 나가겠습니다.
</details>

<details markdown = "1">
<summary>디지털 전환 사례</summary>

</details>

<details markdown = "1">
<summary>근데 fishbone diagram을 활용한 root cause analysis가 뭐죠? </summary>
Fishbone diagram은 복잡한 문제의 근본 원인들을 찾아내고 시각화하기 위해 사용되는 도식입니다. 이 도식은 문제를 일으킨 다양한 원인을 '물고기 뼈' 모양으로 배열하여, 원인과 결과 간의 관계를 명확하게 보여줍니다. 특히, 문제가 서로 연관된 여러 요소들에 의해 발생했을 경우, 각각의 원인을 분류하고 연결점을 파악하는 데 매우 유용합니다.<br>
</details>



---

## 직무 및 인성 관련 질문
<details markdown = "1">
<summary>cj 프레시웨이를 어떻게 알게 되었냐</summary>
(이연복이 단체 급식 경험이 없음 -> 이걸 가르쳐줌), 갈비찜 닭구이 했음<br>
한국인의 식판이라는 예능 프로그램에서 급식 솔루션 담당 셰프 분께서 대량 급식시 조리를 하는 방법을 가르쳐주시는 장면을 보고 처음 알게 되었습니다.<br> 
</details>

<details markdown = "1">
<summary>cj프레시웨이에 pb브랜드에 대해 알고있는가? 각 브랜드는 어떤 일을 하는가?</summary>
아이누리는 아이들에게 좋은 먹거리와 올바른 식습관을 위한 건강한 식문화 프로그램을 제공하는 키즈 전문 식품 브랜드입니다.<br>
헬씨누리는 시니어 분들에게 특화된 맞춤형 식자재와 서비스 뿐 아니라, 더욱 건강하고 지속가능한 토탈 푸드 케어 솔루션을 제공하는 브랜드입니다.<br>
튼튼스쿨은 고품질의 식자재와 트렌디한 급식 솔루션을 제공하는 학교 급식 경로 특화 브랜드입니다.<br>
정품진 한우 한돈은 엄격한 사양 관리와 HACCP 인증이 된 첨단 시설에서 키운 한우의 깊은 풍미를 느끼게 해주는 고품질 브랜드입니다.<br>
dono는 뉴질랜드에서 건너온 정통 프리미엄 유제품 & 양식재 전문 브랜드입니다.<br>
마지막으로 freshone은 지역의 중소업체와 상생하는 안정적이고 체계화된 유통 구조를 통하여 우수의 품질의 상품을 최고의 가격 경쟁력으로 전달하는 식당 전문 식자재 브랜드입니다.<br>
</details>

<details markdown = "1">
<summary>cj프레시웨이에 자회사 뭐있냐?</summary>
지역 거점의 중소형 식자재 유통회사와 cj프레시웨이과 함께 투자해 만든 상생 비즈니스 모델인 프레시원과
B2B형 간편식 제조 및 밀 솔루션 전문 기업인 프레스 플러스가 있습니다.<br>
</details>

<details markdown = "1">
<summary>자회사, PB(Private Brand), NB(National Brand), OEM(Original Equipment Manufacturer), GP(Gross Profit), OP(Operating Profit)이 뭔지</summary>
pb : 유통업체에서 직접 만든 자체 브랜드 상품으로, 제조 설비를 갖추지 않은 업체가 독자적으로 상품을 기획한 후 생산만 제조 업체에 의뢰해서 판매하는 상품, nb에 비해 저렴<br>
nb : 제조업체가 기획하고 생산하는 브랜드<br>
oem : 주문자의 의뢰에 따라 상표를 부착하여 판매할 상품을 제작하는 업체를 뜻합니다.<br>
gp(매출 총이익) : 매출액에서 원가(제조나 구매비용)를 뺀 매출 총이익을 뜻합니다.<br>
op(영업 이익) : 매촐 총이익에서 판매 관리비를 뺀 영업이익을 뜻합니다.<br>
</details>



<details markdown = "1">
<summary>cj프레시웨이의 지속 성장을 위해 필요한 것</summary>

</details>



<details markdown = "1">
<summary>우리 회사에 대해 아는대로 설명해주세요.</summary>
(어느 부분을 중시하는지, 어느 부분에 관심을 가지는지)<br>

</details>

<details markdown = "1">
<summary>왜 우리회사에 지원했는지?, 우리회사 지원하기 위해 어떤 노력을 했는지</summary>

</details>

<details markdown = "1">
<summary>우리 회사 경쟁사가 어딘지와 회사의 장단점</summary>

</details>

<details markdown = "1">
<summary>우리 회사 영업직이 무엇을 하는건지 알고 있는대로 설명해봐라</summary>

</details>

<details markdown = "1">
<summary>왜 cj프레시웨이에서 영업을 하고 싶냐</summary>

</details>


<details markdown = "1">
<summary>프레시웨이에 대해 많이 공부해왔을텐데, 여기서 영업자로서 어떤 업무를 해보고 싶은 업무는 무엇인가요?</summary>

</details>

<details markdown = "1">
<summary>지원분야와 관련한 실무적인 학습을 받은 적이 있습니까?</summary>

</details>

<details markdown = "1">
<summary>지원 직무에 대해 아는 것을 모두 말해보세요.</summary>

</details>

<details markdown = "1">
<summary>마지막으로 하고 싶은 말이 있다면 말해보세요.</summary>

</details>

<details markdown = "1">
<summary>대외 활동 어떤걸 했는지?</summary>

</details>

<details markdown = "1">
<summary>졸업한 뒤에는 어떤 일을 했는지 말해보세요.</summary>

</details>

<details markdown = "1">
<summary>전공에서 뭘 배웠었는지?</summary>

</details>

<details markdown = "1">
<summary>타 회사 지원은 많이 하고 있는지? 하고 있는지?</summary>

</details>

<details markdown = "1">
<summary>지원 직무의 커리어를 지속하고 싶은지, 혹시 다른 직무는 생각하고 있지 않는지 말해 보세요.</summary>

</details>

<details markdown = "1">
<summary>CJ 사이트에 접속해 보았나요? 인재상을 알고 있다면 인재상에 대해 말해보세요.</summary>

</details>

<details markdown = "1">
<summary>가장 큰 성취감을 느꼈던 경험은 무엇인지?</summary>

</details>

<details markdown = "1">
<summary>갈등을 해결하는 본인만의 노하우가 있는지?</summary>

</details>

<details markdown = "1">
<summary>패키징 공정 중 부적합 받은 제품에 대해 상사가 그냥 넘어가자고 하면 어떻게 할건지?</summary>

</details>

<details markdown = "1">
<summary>입사 후 같은 팀이나 타 팀과 마찰이 생겼을 때 어떻게 해결하실 건가요?</summary>

</details>

<details markdown = "1">
<summary>조직에서 갈등을 겪고 극복한 경험이 있는지</summary>

</details>

<details markdown = "1">
<summary>직무에서 활용가능한 본인만의 장점</summary>

</details>

<details markdown = "1">
<summary>인생에 꿈이 무엇인지?</summary>

</details>

<details markdown = "1">
<summary>일하고 싶은 분야가 어디인지?</summary>

</details>

<details markdown = "1">
<summary>영업인에게 필요한 자세가 무엇이라 생각하는지?</summary>

</details>







