<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>물류관리론 퀴즈</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/react/18.2.0/umd/react.production.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/react-dom/18.2.0/umd/react-dom.production.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/babel-standalone/7.23.2/babel.min.js"></script>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: linear-gradient(135deg,#ffffff 100%); min-height: 100vh; font-family: 'Apple SD Gothic Neo', 'Noto Sans KR', sans-serif; }
  input::placeholder { color: #588acf; }
  input:focus { border-color: #144e96 !important; outline: none; }
  @keyframes shake { 0%,100%{transform:translateX(0)} 20%{transform:translateX(-8px)} 40%{transform:translateX(8px)} 60%{transform:translateX(-6px)} 80%{transform:translateX(6px)} }
  @keyframes bounceIn { 0%,100%{transform:scale(1)} 40%{transform:scale(1.03)} 70%{transform:scale(0.98)} }
  .shake { animation: shake 0.4s ease; }
  .bounce { animation: bounceIn 0.5s ease; }
  ::-webkit-scrollbar { width: 6px; }
  ::-webkit-scrollbar-track { background: transparent; }
  ::-webkit-scrollbar-thumb { background: rgba(255,255,255,0.2); border-radius: 99px; }
</style>
</head>
<body>
<div id="root"></div>
<script type="text/babel">

// ─── 문제 데이터 ────────────────────────────────────────────────────────────
// a  : 첫 번째 빈칸 정답. '/'로 구분 시 어느 쪽을 입력해도 정답
// a2 : 두 번째 빈칸 정답 (문제에 빈칸이 2개일 때만 사용)

const ALL_QUESTIONS = [
  // 1. 물류원론
  { category:"1. 물류원론", q:"물류는 생산과 소비 사이의 ①___적, ②___적 간격을 해소하여 효용을 창출한다.", a:"장소", a2:"시간" },
  { category:"1. 물류원론", q:"물류의 영역 중 원재료 조달부터 생산 공정 투입 전까지를 ___라고 한다.", a:"조달물류" },
  { category:"1. 물류원론", q:"물류의 5대 기능은 운송, 보관, 하역, ___, 물류정보이다.", a:"포장" },
  { category:"1. 물류원론", q:"물류이익 ___에 따르면 물류비 절감은 판매액 증대와 같은 효과를 준다.", a:"제3의 이원론" },
  { category:"1. 물류원론", q:"물류시스템의 하부 시스템 중 창고 내 물품의 이동을 담당하는 것은 ___이다.", a:"하역시스템" },
  { category:"1. 물류원론", q:"반품, 리콜 등을 포함하는 물류 영역을 ___라고 한다.", a:"회수물류" },
  { category:"1. 물류원론", q:"7R 중 '적절한 가격'을 의미하는 것은 ___이다.", a:"Right Price" },
  { category:"1. 물류원론", q:"물류의 기능 중 '장소적 효용'을 창출하는 핵심 기능은 ___이다.", a:"운송" },
  { category:"1. 물류원론", q:"___은 생산 공정 중의 물류를 의미한다.", a:"사내물류" },
  { category:"1. 물류원론", q:"기업의 물류 비전은 경영 방침과 ___을 반영하여 수립된다.", a:"물류 환경" },
  { category:"1. 물류원론", q:"___은 물류 활동의 결과를 수치로 나타낸 목표이다.", a:"KPI/물류 성과지표" },
  { category:"1. 물류원론", q:"물류 계획 수립 시 가장 먼저 고려해야 할 것은 ___이다.", a:"고객 서비스 수준" },
  { category:"1. 물류원론", q:"___ 물류는 다 쓴 제품을 회수하여 재활용하는 활동을 포함한다.", a:"폐기물" },
  { category:"1. 물류원론", q:"물류센터의 ___ 설계는 전술계획 수준의 의사결정이다.", a:"공간 활용" },
  { category:"1. 물류원론", q:"___ 서비스는 물류시스템의 출력(Output) 요소에 해당한다.", a:"고객" },

  // 2. 물류합리화 및 표준화
  { category:"2. 물류합리화 및 표준화", q:"물류표준화의 핵심은 시설, 장비 등의 ___을 통일하는 것이다.", a:"규격" },
  { category:"2. 물류합리화 및 표준화", q:"화물을 일정한 중량이나 크기로 단위화하는 시스템을 ___라고 한다.", a:"ULS/유닛 로드 시스템" },
  { category:"2. 물류합리화 및 표준화", q:"한국의 표준 파렛트 규격(T-11형)은 ___mm이다.", a:"1,100x1,100/1100X1100/1100*1000" },
  { category:"2. 물류합리화 및 표준화", q:"파렛트를 공동으로 이용하고 관리하는 시스템은 ___이다.", a:"PPS/파렛트 풀 시스템" },
  { category:"2. 물류합리화 및 표준화", q:"물류 모듈화의 평면 치수 기준은 ___의 규격에 따른다.", a:"파렛트" },
  { category:"2. 물류합리화 및 표준화", q:"여러 기업이 물류 시설을 공동으로 이용하는 것을 ___라고 한다.", a:"물류공동화" },
  { category:"2. 물류합리화 및 표준화", q:"___ 적재는 파렛트 층마다 방향을 90도씩 바꾸어 쌓는 방식이다.", a:"벽돌쌓기/블록" },
  { category:"2. 물류합리화 및 표준화", q:"물류 표준화의 대상 중 전표, 코드 등을 통일하는 것은 ___ 표준화이다.", a:"소프트웨어" },
  { category:"2. 물류합리화 및 표준화", q:"___ 모듈은 기본 모듈 치수를 정수로 나눈 치수이다.", a:"분할" },
  { category:"2. 물류합리화 및 표준화", q:"___ 모듈은 기본 모듈 치수를 정수로 곱한 치수이다.", a:"배수" },
  { category:"2. 물류합리화 및 표준화", q:"물류합리화의 3대 원칙은 저렴성, ___, 안전성이다.", a:"신속성" },
  { category:"2. 물류합리화 및 표준화", q:"___은 환경 부하를 줄이기 위한 물류 활동을 뜻한다.", a:"녹색물류" },
  { category:"2. 물류합리화 및 표준화", q:"자동창고(AS/RS) 도입을 위한 필수 전제조건은 ___이다.", a:"물류표준화" },
  { category:"2. 물류합리화 및 표준화", q:"___은 복수의 화주 화물을 모아 효율적으로 운송하는 방식이다.", a:"공동수,배송" },
  { category:"2. 물류합리화 및 표준화", q:"___ 시스템은 배송 차량의 적재 효율을 높여 공차 운행을 줄인다.", a:"라우팅" },
  { category:"2. 물류합리화 및 표준화", q:"ULS 구축을 위한 두 가지 핵심 도구는 파렛트와 ___이다.", a:"컨테이너" },
  { category:"2. 물류합리화 및 표준화", q:"___ 수송은 화물차의 적재함을 가득 채우지 못한 상태의 운송을 뜻한다.", a:"LTL/소량" },
  { category:"2. 물류합리화 및 표준화", q:"___ 서비스는 온라인 주문의 입고, 보관, 배송을 일괄 대행한다.", a:"풀필먼트" },
  { category:"2. 물류합리화 및 표준화", q:"___ 은 파렛트가 물류 현장에 부족하거나 편중되는 현상을 방지한다.", a:"파렛트 풀 시스템" },
  { category:"2. 물류합리화 및 표준화", q:"___ 수송은 동일 구간을 여러 차량이 중복 운행하는 비효율을 방지한다.", a:"교차" },
  { category:"2. 물류합리화 및 표준화", q:"___는 하역의 기계화를 가능하게 하는 물류 표준화의 기본 단위이다.", a:"파렛트" },

  // 3. 물류비용
  { category:"3. 물류비용", q:"물류비는 재화가 공급자로부터 수요자에게 전달될 때 소비된 ___이다.", a:"경제적 가치" },
  { category:"3. 물류비용", q:"___ 물류비는 제품 판매 과정에서 발생하는 비용을 말한다.", a:"판매" },
  { category:"3. 물류비용", q:"기업 내부 자산을 사용하여 발생하는 물류비는 ___ 물류비이다.", a:"자가" },
  { category:"3. 물류비용", q:"___는 기능별 물류비 중 통상 가장 큰 비중을 차지한다.", a:"운송비" },
  { category:"3. 물류비용", q:"물류비 산정 시 '활동 발생 시점'을 기준으로 하는 것은 ___ 원칙이다.", a:"발생기준" },
  { category:"3. 물류비용", q:"___ 물류비는 반품이나 폐기 과정에서 발생한다.", a:"리버스/역물류" },
  { category:"3. 물류비용", q:"조달, 사내, 판매로 구분하는 것은 ___별 구분이다.", a:"영역" },
  { category:"3. 물류비용", q:"운송, 보관, 하역으로 구분하는 것은 ___별 구분이다.", a:"기능" },
  { category:"3. 물류비용", q:"___ 물류비는 제품 생산을 위한 원재료 구매 시 발생한다.", a:"조달" },
  { category:"3. 물류비용", q:"___는 물류 시설의 임차료나 보험료를 포함하는 비용 항목이다.", a:"보관비" },
  { category:"3. 물류비용", q:"___은 물류 정보 시스템의 개발 및 유지보수에 드는 비용이다.", a:"물류정보비" },
  { category:"3. 물류비용", q:"물류비의 ___ 현상은 한 부문의 비용을 줄이면 다른 부문의 비용이 늘어남을 뜻한다.", a:"상충/Trade-off" },

  // 4. 고객서비스와 품질관리
  { category:"4. 고객서비스와 품질관리", q:"고객의 주문부터 인도까지 걸리는 시간을 ___이라고 한다.", a:"리드타임/주문주기" },
  { category:"4. 고객서비스와 품질관리", q:"주문받은 수량을 결품 없이 인도하는 비율을 ___이라고 한다.", a:"주문충족률/서비스율" },
  { category:"4. 고객서비스와 품질관리", q:"___은 유형성, 신뢰성, 응답성 등 5개 차원으로 서비스 품질을 측정한다.", a:"SERVQUAL" },
  { category:"4. 고객서비스와 품질관리", q:"___은 불량률을 100만 개당 3.4개 수준으로 관리하는 혁신 기법이다.", a:"6시그마" },
  { category:"4. 고객서비스와 품질관리", q:"비즈니스 프로세스를 근본적으로 재설계하는 기법을 ___라고 한다.", a:"BPR" },
  { category:"4. 고객서비스와 품질관리", q:"___은 도요타에서 시작된 재고를 최소화하는 적시 생산 방식이다.", a:"JIT" },
  { category:"4. 고객서비스와 품질관리", q:"___은 전사적 차원에서 품질 향상을 추구하는 경영 방식이다.", a:"TQM" },
  { category:"4. 고객서비스와 품질관리", q:"___은 고객 만족도 조사에서 도출된 핵심 품질 특성을 의미한다.", a:"CTQ/핵심품질특성" },
  { category:"4. 고객서비스와 품질관리", q:"물류 현장의 5S 중 도구의 위치를 정해두는 활동은 ___이다.", a:"정돈" },
  { category:"4. 고객서비스와 품질관리", q:"___은 시스템의 병목 구간을 찾아내어 최적화하는 이론이다.", a:"TOC/제약이론" },
  { category:"4. 고객서비스와 품질관리", q:"___은 고객이 원하는 시간과 장소에 제품이 도달하는 것을 뜻한다.", a:"가용성/적기성" },
  { category:"4. 고객서비스와 품질관리", q:"___은 물류 활동 전반에 걸쳐 오류를 방지하는 관리 활동이다.", a:"품질관리/QC" },
  { category:"4. 고객서비스와 품질관리", q:"6시그마의 ___ 단계는 개선된 결과가 유지되도록 표준화하는 과정이다.", a:"Control/관리" },
  { category:"4. 고객서비스와 품질관리", q:"___은 자재소요계획을 관리하는 초기 단계의 품질 시스템이다.", a:"MRP" },
{ category:"4. 고객서비스와 품질관리", q:"___서비스는 주문의 정확성과 배송 신속성을 핵심으로 한다.", a:"물류" },
  { category:"4. 고객서비스와 품질관리", q:"___은 물류 사고 발생 시 고객에게 제공되는 사후 보상 대책이다.", a:"서비스 회복" },
{ category:"4. 고객서비스와 품질관리", q:"물류 서비스 수준(SL)을 높이면___이 기하급수적으로 증가할 수 있다.", a:"물류비용" },
  { category:"4. 고객서비스와 품질관리", q:"___은 제품의 파손 없이 안전하게 전달되는 정도를 의미한다.", a:"안전성" },
  { category:"4. 고객서비스와 품질관리", q:"___은 고객의 문의에 신속하게 대응하는 서비스 품질 요소이다.", a:"응답성" },
  { category:"4. 고객서비스와 품질관리", q:"___ 관리는 고객과의 관계를 지속적으로 관리하여 가치를 창출한다.", a:"CRM/고객관계관리" },

  // 5. 유통과 마케팅
  { category:"5. 유통과 마케팅", q:"마케팅 4P 전략은 제품, 가격, 촉진, ___이다.", a:"유통/Place" },
  { category:"5. 유통과 마케팅", q:"___은 제조업체에서 소비자로 제품이 이동하는 경로를 의미한다.", a:"유통경로" },
  { category:"5. 유통과 마케팅", q:"___ 유통은 가능한 많은 판매점을 통해 제품을 공급하는 전략이다.", a:"집약적/집중적" },
  { category:"5. 유통과 마케팅", q:"___ 서비스는 온라인 주문 후 오프라인에서 상품을 수령하는 서비스이다.", a:"O2O" },
  { category:"5. 유통과 마케팅", q:"___ 갈등은 유통 경로 내 제조사와 도매상 사이의 갈등을 의미한다.", a:"수직적" },
  { category:"5. 유통과 마케팅", q:"___은 과거의 일정 기간 데이터 평균을 내어 다음 수요를 예측한다.", a:"이동평균법" },
  { category:"5. 유통과 마케팅", q:"___은 제품 수명 주기의 4단계 중 이익이 극대화되는 단계이다.", a:"성숙기" },
  { category:"5. 유통과 마케팅", q:"___은 소비자 간의 중고 거래나 직거래 플랫폼 비즈니스 모델이다.", a:"C2C" },
  { category:"5. 유통과 마케팅", q:"유통의 ___ 효용은 소유권을 이전시켜 줌으로써 발생한다.", a:"소유" },
  { category:"5. 유통과 마케팅", q:"___은 유통 구성원 간의 정보 불일치로 주문량이 증폭되는 현상이다.", a:"채찍효과/Bullwhip Effect" },
  { category:"5. 유통과 마케팅", q:"___ 전략은 제조업자가 유통업자에게 인센티브를 주어 판매를 독려하는 전략이다.", a:"푸시/Push" },
  { category:"5. 유통과 마케팅", q:"___ 전략은 소비자가 제품을 찾게 하여 유통 경로로 끌어들이는 전략이다.", a:"풀/Pull" },
  { category:"5. 유통과 마케팅", q:"___은 24시간 운영하며 접근성이 좋은 소형 소매 업태이다.", a:"편의점/CVS" },
  { category:"5. 유통과 마케팅", q:"___은 한 지붕 아래 다양한 카테고리의 상품을 판매하는 대형 매장이다.", a:"백화점" },
  { category:"5. 유통과 마케팅", q:"___은 가격 민감도가 높은 소비자를 공략하기 위해 상시 저가 판매를 지향한다.", a:"할인점/마트" },
  { category:"5. 유통과 마케팅", q:"___은 특정 전문 카테고리의 상품을 저렴하게 판매하는 대형 전문점이다.", a:"카테고리 킬러" },
  { category:"5. 유통과 마케팅", q:"___ 유통은 제품 특성에 맞는 일부 판매점만 선별하여 운영하는 방식이다.", a:"선택적" },
  { category:"5. 유통과 마케팅", q:"___ 상인은 상품의 소유권을 직접 가지지 않고 거래만 중개한다.", a:"대리인/중개" },
  { category:"5. 유통과 마케팅", q:"___은 온라인과 오프라인 경로를 유기적으로 통합하여 고객 경험을 강화하는 전략이다.", a:"옴니채널" },
  { category:"5. 유통과 마케팅", q:"___은 수요예측 기법 중 데이터에 가중치를 두어 계산하는 방식이다.", a:"지수평활법" },

  // 6. 물류정보시스템
  { category:"6. 물류정보시스템", q:"___은 기업 간 표준 양식의 데이터를 컴퓨터로 교환하는 시스템이다.", a:"EDI" },
  { category:"6. 물류정보시스템", q:"___은 무선 주파수를 이용해 비접촉식으로 정보를 인식하는 기술이다.", a:"RFID" },
  { category:"6. 물류정보시스템", q:"___은 창고의 입출고와 재고를 실시간 관리하는 시스템이다.", a:"WMS" },
  { category:"6. 물류정보시스템", q:"___은 운송 경로 최적화와 배차를 지원하는 시스템이다.", a:"TMS" },
  { category:"6. 물류정보시스템", q:"___은 기업의 인사, 재무, 물류 등 전사 자원을 통합 관리한다.", a:"ERP" },
  { category:"6. 물류정보시스템", q:"___ 바코드는 정보를 가로세로 두 방향으로 담아 저장 용량이 크다.", a:"2차원/QR" },
  { category:"6. 물류정보시스템", q:"___은 창고 내 피킹 작업자에게 빛으로 위치를 알려주는 장치이다.", a:"DPS" },
  { category:"6. 물류정보시스템", q:"___은 미국 세관이 주도하는 민관 협력 대테러 보안 프로그램이다.", a:"C-TPAT" },
  { category:"6. 물류정보시스템", q:"___은 실시간으로 화물의 위치를 파악하는 시스템이다.", a:"RTLS" },
  { category:"6. 물류정보시스템", q:"___은 디지털 표시기에 지시된 수량만큼 물건을 분배하는 시스템이다.", a:"DAS" },
  { category:"6. 물류정보시스템", q:"___은 선박 및 항만 시설의 보안을 위해 제정된 국제 규칙이다.", a:"ISPS Code" },
  { category:"6. 물류정보시스템", q:"___은 배송 완료 정보를 실시간으로 화주에게 알리는 기능이다.", a:"POD" },
  { category:"6. 물류정보시스템", q:"___은 물류 센터 내 물품 배치 최적화 기능을 의미한다.", a:"슬로팅/Slotting" },
  { category:"6. 물류정보시스템", q:"___ 기술은 화물차의 GPS 위치와 상태를 관제 센터에 전달한다.", a:"텔레매틱스" },
  { category:"6. 물류정보시스템", q:"___은 클라우드 기반으로 필요한 물류 소프트웨어를 구독하여 사용하는 방식이다.", a:"SaaS" },
  { category:"6. 물류정보시스템", q:"___은 방대한 물류 데이터를 분석하여 수요 예측이나 경로 최적화에 활용한다.", a:"빅데이터" },
  { category:"6. 물류정보시스템", q:"___은 물류 산업에 AI, 로봇 등 ICT 기술을 결합하는 흐름이다.", a:"DT/디지털 전환" },
  { category:"6. 물류정보시스템", q:"___은 물류 센터 내에서 사람 대신 화물을 운반하는 무인 반송차이다.", a:"AGV" },
  { category:"6. 물류정보시스템", q:"___은 가상 공간에 실제 물류 현장을 복제하여 시뮬레이션하는 기술이다.", a:"디지털 트윈" },
  { category:"6. 물류정보시스템", q:"___은 공급망 전체에서 화물의 흐름을 한눈에 파악하는 기능이다.", a:"가시성/Visibility" },
  { category:"6. 물류정보시스템", q:"___은 정보 시스템 간 데이터 연동을 위한 전제 조건이다.", a:"표준화" },

  // 7. 물류조직과 아웃소싱
  { category:"7. 물류조직과 아웃소싱", q:"___은 물류 업무를 외부 전문 업체에 위탁하는 방식이다.", a:"3PL/3자물류" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 3PL에 컨설팅과 IT 솔루션을 더해 공급망 전체를 관리한다.", a:"4PL/4자물류" },
  { category:"7. 물류조직과 아웃소싱", q:"___조직은 각 사업부 내에 물류 기능이 흩어져 있는 형태이다.", a:"분산형)" },
  { category:"7. 물류조직과 아웃소싱", q:"___조직은 전사 물류 업무를 한 부서에서 통합 관리한다.", a:"집중형)" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 기업이 물류 자회사를 설립하여 운영하는 형태이다.", a:"2자물류/2PL" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 기업이 직접 물류 시설과 인력을 갖추어 수행하는 방식이다.", a:"1자물류/자가물류" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 물류 기능이 통합되어 독립된 부서로 존재하는 단계이다.", a:"로지스틱스 조직" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 SCM 시대에 공급망 참여자들과 협력하는 조직 형태이다.", a:"네트워크 조직" },
  { category:"7. 물류조직과 아웃소싱", q:"___물류업체는 차량이나 창고 등 직접적인 물류 수단을 보유한 업체이다.", a:"자산형" },
  { category:"7. 물류조직과 아웃소싱", q:"___물류업체는 시설 보유보다는 정보와 네트워크로 물류를 중개한다.", a:"비자산형" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 여러 물류업체를 하나로 통합하여 최적의 서비스를 제공하는 4PL 유형이다.", a:"솔루션 통합자" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 아웃소싱을 통해 물류 운영의 위험을 외부와 나누는 목적이다.", a:"리스크 분산)" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 3PL 업체를 선정할 때 고려하는 가장 중요한 요소 중 하나이다.", a:"전문성" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 부서 간 물류 갈등을 조정하기 위해 구성하는 조직이다.", a:"물류위원회" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 4자물류 서비스의 핵심 경쟁력이다.", a:"정보기술/IT" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 전 세계에서 최적의 조달처를 찾는 활동으로 SCM 조직의 역할이다.", a:"글로벌 소싱" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 조달부터 판매까지 물류의 단절을 없애는 관리 방식이다.", a:"통합 물류 관리" },
  { category:"7. 물류조직과 아웃소싱", q:"___은 시장 변화에 신속하게 대응할 수 있는 조직의 능력이다.", a:"유연성" },
  { category:"7. 물류조직과 아웃소싱", q:"___ 조직은 생산, 영업, 물류 등 기능별로 나뉘어 있는 전통적 조직이다.", a:"직능형" },

  // 8. 공급망 관리
  { category:"8. 공급망 관리(SCM)", q:"___은 원재료 조달부터 최종 소비자까지의 전체 프로세스를 최적화한다.", a:"SCM" },
  { category:"8. 공급망 관리(SCM)", q:"___은 기업 내 부가가치 창출 활동을 연쇄적으로 파악하는 개념이다.", a:"가치사슬/Value Chain" },
  { category:"8. 공급망 관리(SCM)", q:"___은 공급망 상류로 갈수록 수요 정보의 왜곡이 커지는 현상이다.", a:"채찍효과" },
  { category:"8. 공급망 관리(SCM)", q:"___은 재고유지비용과 주문비용의 합이 최소가 되는 지점이다.", a:"EOQ/경제적주문량" },
  { category:"8. 공급망 관리(SCM)", q:"___은 불확실한 수요에 대비하여 추가로 보유하는 재고이다.", a:"안전재고" },
  { category:"8. 공급망 관리(SCM)", q:"___은 판매자가 구매자의 재고 수준을 직접 관리하는 방식이다.", a:"VMI/공급자관리재고" },
  { category:"8. 공급망 관리(SCM)", q:"___은 공급망 파트너끼리 공동으로 수요를 예측하고 계획을 수립하는 것이다.", a:"CPFR" },
  { category:"8. 공급망 관리(SCM)", q:"___은 창고 입고 후 보관 없이 즉시 분류하여 출고하는 방식이다.", a:"크로스도킹" },
  { category:"8. 공급망 관리(SCM)", q:"___은 SCM의 핵심 목표 중 하나로 재고를 줄이는 효과가 있다.", a:"리드타임 단축" },
  { category:"8. 공급망 관리(SCM)", q:"___은 최종 조립을 고객 주문 시점까지 미루어 재고 리스크를 줄이는 전략이다.", a:"포스트포먼트/지연전략" },
  { category:"8. 공급망 관리(SCM)", q:"___은 재고가 일정 수준 이하로 떨어졌을 때 주문을 내는 시점이다.", a:"재주문점/ROP" },
  { category:"8. 공급망 관리(SCM)", q:"___은 재주문점 계산 시 '단위당 평균수요'와 곱해지는 요소이다.", a:"리드타임" },
  { category:"8. 공급망 관리(SCM)", q:"___은 주문량이 클수록 정비례하여 증가하는 비용이다.", a:"재고유지비용" },
  { category:"8. 공급망 관리(SCM)", q:"___은 주문량이 클수록 반비례하여 감소하는 비용이다.", a:"주문비용" },
  { category:"8. 공급망 관리(SCM)", q:"___은 채찍효과를 방지하기 위한 가장 근본적인 해결책이다.", a:"정보 공유" },
  { category:"8. 공급망 관리(SCM)", q:"___은 공급망 내 재고와 이동 정보를 투명하게 파악하는 것이다.", a:"물류 가시성" },
  { category:"8. 공급망 관리(SCM)", q:"___은 기업의 비핵심 업무를 외부로 돌려 효율을 높이는 SCM 전략이다.", a:"아웃소싱" },
  { category:"8. 공급망 관리(SCM)", q:"___은 공급망 성과를 측정하기 위한 표준 프로세스 모델이다.", a:"SCOR 모델" },
  { category:"8. 공급망 관리(SCM)", q:"___ 비용은 수요 예측 실패로 재고가 남았을 때 발생하는 손실이다.", a:"할인/재고 처리" },
  { category:"8. 공급망 관리(SCM)", q:"___은 수요를 기반으로 유통 거점별 재고를 배분하는 시스템이다.", a:"유통 자원 계획/DRP" },
  { category:"8. 공급망 관리(SCM)", q:"___은 SCM의 성공을 위한 공급망 파트너 간의 필수적인 태도이다.", a:"협업" },
];

const CATEGORIES = ["전체", ...Array.from(new Set(ALL_QUESTIONS.map(q => q.category)))];

// ─── 핵심: 정답 판정 ────────────────────────────────────────────────────────
// 공백 제거 + 소문자 변환만. '/'는 제거하지 않고 분리자로 사용
function normalize(str) {
  return str.replace(/[\s\-·]/g, "").toLowerCase();
}

// "KPI/물류 성과지표" → ["kpi", "물류성과지표"] 중 하나라도 일치하면 정답
function checkAnswer(input, answerStr) {
  const inp = normalize(input.trim());
  const variants = answerStr.split("/").map(s => normalize(s));
  return variants.some(v => v === inp);
}

// 표시용: "KPI / 물류 성과지표"
function fmtAnswer(answerStr) {
  return answerStr.split("/").map(s => s.trim()).join(" / ");
}

const { useState, useEffect, useRef } = React;

function App() {
  const [selectedCat, setSelectedCat] = useState("전체");
  const [questions,   setQuestions]   = useState([]);
  const [current,     setCurrent]     = useState(0);
  const [input1,      setInput1]      = useState("");
  const [input2,      setInput2]      = useState("");
  const [result,      setResult]      = useState(null);
  const [score,       setScore]       = useState(0);
  const [mode,        setMode]        = useState("select");
  const [wrongList,   setWrongList]   = useState([]);
  const [animCls,     setAnimCls]     = useState("");
  const ref1 = useRef(null);
  const ref2 = useRef(null);

  function startQuiz(cat) {
    const pool = cat === "전체" ? ALL_QUESTIONS : ALL_QUESTIONS.filter(q => q.category === cat);
    setQuestions([...pool].sort(() => Math.random() - 0.5));
    setSelectedCat(cat); setCurrent(0); setInput1(""); setInput2("");
    setResult(null); setScore(0); setWrongList([]); setMode("quiz");
  }

  function handleSubmit() {
    if (result) {
      if (current + 1 >= questions.length) setMode("done");
      else { setCurrent(c => c+1); setInput1(""); setInput2(""); setResult(null); }
      return;
    }
    const q = questions[current];
    const dual = !!q.a2;
    if (!input1.trim()) return;
    if (dual && !input2.trim()) { ref2.current?.focus(); return; }

    const ok1 = checkAnswer(input1, q.a);
    const ok2 = dual ? checkAnswer(input2, q.a2) : true;
    const ok  = ok1 && ok2;

    setResult(ok ? "correct" : "wrong");
    if (ok) {
      setScore(s => s+1);
      setAnimCls("bounce"); setTimeout(() => setAnimCls(""), 600);
    } else {
      setWrongList(w => [...w, { q, given1: input1.trim(), given2: dual ? input2.trim() : null }]);
      setAnimCls("shake"); setTimeout(() => setAnimCls(""), 500);
    }
  }

  useEffect(() => { if (mode==="quiz") ref1.current?.focus(); }, [current, mode]);

  const pct = questions.length ? Math.round(score/questions.length*100) : 0;

  // ── 카테고리 선택 ──────────────────────────────────────────────────────────
  if (mode === "select") return (
    <div style={{minHeight:"100vh",display:"flex",flexDirection:"column",alignItems:"center",padding:"32px 16px"}}>
      <div style={{textAlign:"center",marginBottom:"32px"}}>
        <div style={{fontSize:"52px",marginBottom:"8px"}}>📦</div>
        <h1 style={{color:"#000000",fontSize:"26px",fontWeight:800,margin:0}}>물류관리론 퀴즈</h1>
        <p style={{color:"#000000",fontSize:"13px",marginTop:"6px"}}>중간고사 예상문제 — 단원을 선택하세요</p>
      </div>
      <div style={{display:"grid",gridTemplateColumns:"repeat(auto-fill,minmax(190px,1fr))",gap:"12px",width:"100%",maxWidth:"700px"}}>
        {CATEGORIES.map(cat => {
          const cnt = cat==="전체" ? ALL_QUESTIONS.length : ALL_QUESTIONS.filter(q=>q.category===cat).length;
          return (
            <button key={cat} onClick={()=>startQuiz(cat)} style={{
              background:"rgba(96,165,250,0.15)",   // 연한 하늘색
              border:"1px solid rgba(96,165,250,0.35)",
              borderRadius:"16px",
              padding:"20px 16px",
              cursor:"pointer",
              textAlign:"left",
              transition:"all 0.2s"
            }}
              onMouseEnter={e=>{
                e.currentTarget.style.transform="translateY(-3px)";
                e.currentTarget.style.background="rgba(96,165,250,0.25)"; // hover 시 조금 진하게
              }}
              onMouseLeave={e=>{
                e.currentTarget.style.transform="none";
                e.currentTarget.style.background="rgba(96,165,250,0.15)";
              }}>
              <div style={{color:"#000000",fontSize:"14px",fontWeight:600,marginBottom:"6px"}}>{cat}</div>
              <div style={{color:"#60a5fa",fontSize:"12px",fontWeight:500}}>{cnt}문제</div>
            </button>
          );
        })}
      </div>
    </div>
  );

  // ── 결과 화면 ──────────────────────────────────────────────────────────────
  if (mode === "done") {
    const grade = pct>=90?"🏆 우수":pct>=70?"👍 양호":pct>=50?"📚 보통":"💪 분발";
    return (
      <div style={{minHeight:"100vh",display:"flex",justifyContent:"center",padding:"32px 16px"}}>
        <div style={{background:"rgba(255,255,255,0.05)",border:"1px solid rgba(255,255,255,0.1)",borderRadius:"24px",
          padding:"36px 28px",width:"100%",maxWidth:"560px",display:"flex",flexDirection:"column",alignItems:"center",gap:"16px"}}>
          <div style={{fontSize:"52px"}}>{grade.split(" ")[0]}</div>
          <h2 style={{color:"#000000",fontSize:"22px",fontWeight:800,margin:0}}>퀴즈 완료!</h2>
          <div style={{width:"110px",height:"110px",borderRadius:"50%",background:"linear-gradient(135deg,#3b82f6,#8b5cf6)",
            display:"flex",flexDirection:"column",alignItems:"center",justifyContent:"center"}}>
            <span style={{color:"#fff",fontSize:"26px",fontWeight:900}}>{pct}%</span>
            <span style={{color:"rgba(255,255,255,0.7)",fontSize:"12px"}}>{score}/{questions.length}</span>
          </div>
          <p style={{color:"#000000",fontSize:"16px",fontWeight:600,margin:0}}>{grade.split(" ")[1]}</p>
          {wrongList.length > 0 && (
            <div style={{width:"100%",maxHeight:"360px",overflowY:"auto",display:"flex",flexDirection:"column",gap:"10px"}}>
              <h3 style={{color:"#000000",fontSize:"15px",fontWeight:700,margin:"0 0 4px"}}>❌ 틀린 문제 복습</h3>
              {wrongList.map((w,i) => (
                <div key={i} style={{background:"rgba(239,68,68,0.08)",border:"1px solid rgba(239,68,68,0.2)",borderRadius:"12px",padding:"12px 14px"}}>
                  <p style={{color:"#000000",fontSize:"13px",margin:"0 0 6px",lineHeight:1.6}}>
                    {w.q.q.replace("①___","【①】").replace("②___","【②】").replace("___","【　】")}
                  </p>
                  {w.q.a2 ? (
                    <>
                      <p style={{color:"#000000",fontSize:"12px",margin:"0 0 2px"}}>
                        내 답 ①: <span style={{color:"#ef4444"}}>{w.given1}</span>　②: <span style={{color:"#ef4444"}}>{w.given2}</span>
                      </p>
                      <p style={{color:"#000000",fontSize:"12px",margin:0}}>
                        정답 ①: <span style={{color:"#22c55e",fontWeight:700}}>{fmtAnswer(w.q.a)}</span>　②: <span style={{color:"#22c55e",fontWeight:700}}>{fmtAnswer(w.q.a2)}</span>
                      </p>
                    </>
                  ) : (
                    <>
                      <p style={{color:"#000000",fontSize:"12px",margin:"0 0 2px"}}>내 답: <span style={{color:"#ef4444"}}>{w.given1}</span></p>
                      <p style={{color:"#000000",fontSize:"12px",margin:0}}>정답: <span style={{color:"#22c55e",fontWeight:700}}>{fmtAnswer(w.q.a)}</span></p>
                    </>
                  )}
                </div>
              ))}
            </div>
          )}
          <div style={{display:"flex",gap:"10px",width:"100%"}}>
            <button onClick={()=>startQuiz(selectedCat)} style={{flex:1,background:"linear-gradient(135deg,#3b82f6,#2563eb)",border:"none",borderRadius:"12px",padding:"14px",color:"#fff",fontWeight:700,cursor:"pointer",fontSize:"14px",fontFamily:"inherit"}}>다시 풀기</button>
            <button onClick={()=>setMode("select")} style={{flex:1,background:"rgba(255,255,255,0.08)",border:"1px solid rgba(255,255,255,0.15)",borderRadius:"12px",padding:"14px",color:"#000000",fontWeight:700,cursor:"pointer",fontSize:"14px",fontFamily:"inherit"}}>카테고리 선택</button>
          </div>
        </div>
      </div>
    );
  }

  // ── 퀴즈 화면 ──────────────────────────────────────────────────────────────
  const q      = questions[current];
  const dual   = !!q.a2;
  const prog   = (current / questions.length) * 100;
  const border = result==="correct" ? "#22c55e" : result==="wrong" ? "#ef4444" : "rgba(255,255,255,0.12)";
  const displayQ = q.q.replace("①___","①【　　　】").replace("②___","②【　　　】").replace("___","【　　　　】");

  const inputStyle = {
    flex:1, background:"rgba(255,255,255,0.08)", border:"1.5px solid rgba(255,255,255,0.15)",
    borderRadius:"12px", padding:"13px 16px", color:"#000000", fontSize:"15px", fontFamily:"inherit"
  };
  const btnStyle = {
    background:"linear-gradient(135deg,#3b82f6,#2563eb)", border:"none", borderRadius:"12px",
    padding:"13px 20px", color:"#fff", fontSize:"14px", fontWeight:700, cursor:"pointer", fontFamily:"inherit", whiteSpace:"nowrap"
  };

  return (
    <div style={{minHeight:"100vh",display:"flex",justifyContent:"center",padding:"24px 16px"}}>
      <div style={{width:"100%",maxWidth:"640px",display:"flex",flexDirection:"column",gap:"12px"}}>

        <div style={{display:"flex",alignItems:"center",justifyContent:"space-between"}}>
          <button onClick={()=>setMode("select")} style={{background:"transparent",border:"none",color:"#94a3b8",cursor:"pointer",fontSize:"14px",padding:"4px 0"}}>← 뒤로</button>
          <span style={{background:"rgba(96,165,250,0.15)",color:"#60a5fa",borderRadius:"20px",padding:"4px 12px",fontSize:"12px",fontWeight:600}}>{selectedCat}</span>
          <span style={{color:"#94a3b8",fontSize:"13px",fontWeight:600}}>{current+1} / {questions.length}</span>
        </div>

        <div style={{height:"6px",background:"rgba(255,255,255,0.1)",borderRadius:"99px",overflow:"hidden"}}>
          <div style={{height:"100%",background:"linear-gradient(90deg,#3b82f6,#60a5fa)",borderRadius:"99px",width:`${prog}%`,transition:"width 0.4s ease"}}/>
        </div>

        <div style={{display:"flex",gap:"8px"}}>
          <span style={{background:"rgba(34,197,94,0.15)",color:"#4ade80",borderRadius:"20px",padding:"4px 12px",fontSize:"12px",fontWeight:700}}>✅ {score}점</span>
          {wrongList.length>0 && <span style={{background:"rgba(239,68,68,0.15)",color:"#f87171",borderRadius:"20px",padding:"4px 12px",fontSize:"12px",fontWeight:700}}>❌ {wrongList.length}개</span>}
        </div>

        {/* 문제 카드 */}
        <div className={animCls} style={{
          background:"rgba(255,255,255,0.05)",border:`2px solid ${border}`,borderRadius:"20px",
          padding:"28px 24px",backdropFilter:"blur(20px)",minHeight:"160px",
          display:"flex",flexDirection:"column",gap:"16px",justifyContent:"center",transition:"border-color 0.3s"
        }}>
          <p style={{color:"#000000",fontSize:"17px",lineHeight:1.8,margin:0,fontWeight:500}}>{displayQ}</p>

          {result && (
            <div style={{borderRadius:"12px",padding:"12px 16px",fontSize:"14px",lineHeight:1.8,
              background:result==="correct"?"#dcfce7":"#fee2e2"}}>
              {result==="correct" ? (
                <span style={{color:"#16a34a"}}>
                  ⭕ 정답!{dual ? ` ①${fmtAnswer(q.a)}  ②${fmtAnswer(q.a2)}` : ` ${fmtAnswer(q.a)}`}
                </span>
              ) : dual ? (
                <span style={{color:"#dc2626"}}>
                  ❌ 정답: ①<strong>{fmtAnswer(q.a)}</strong>　②<strong>{fmtAnswer(q.a2)}</strong><br/>
                  내 답: ①{input1}　②{input2}
                </span>
              ) : (
                <span style={{color:"#dc2626"}}>
                  ❌ 정답: <strong>{fmtAnswer(q.a)}</strong> (내 답: {input1})
                </span>
              )}
            </div>
          )}
        </div>

        {/* 입력창 */}
        {dual ? (
          <div style={{display:"flex",flexDirection:"column",gap:"8px"}}>
            <div style={{display:"flex",gap:"8px",alignItems:"center"}}>
              <span style={{color:"#94a3b8",fontWeight:700,fontSize:"14px",minWidth:"20px"}}>①</span>
              <input ref={ref1} value={input1} onChange={e=>setInput1(e.target.value)}
                onKeyDown={e=>{if(e.key==="Enter"){if(!input2.trim())ref2.current?.focus();else handleSubmit();}}}
                placeholder="첫 번째 빈칸" disabled={!!result} style={inputStyle}/>
            </div>
            <div style={{display:"flex",gap:"8px",alignItems:"center"}}>
              <span style={{color:"#94a3b8",fontWeight:700,fontSize:"14px",minWidth:"20px"}}>②</span>
              <input ref={ref2} value={input2} onChange={e=>setInput2(e.target.value)}
                onKeyDown={e=>e.key==="Enter"&&handleSubmit()}
                placeholder="두 번째 빈칸" disabled={!!result} style={inputStyle}/>
            </div>
            <button onClick={handleSubmit} style={{...btnStyle,padding:"13px"}}>
              {result?(current+1>=questions.length?"결과 보기 →":"다음 →"):"확인"}
            </button>
          </div>
        ) : (
          <div style={{display:"flex",gap:"8px"}}>
            <input ref={ref1} value={input1} onChange={e=>setInput1(e.target.value)}
              onKeyDown={e=>e.key==="Enter"&&handleSubmit()}
              placeholder="정답을 입력하세요..." disabled={!!result} style={inputStyle}/>
            <button onClick={handleSubmit} style={btnStyle}>
              {result?(current+1>=questions.length?"결과 보기 →":"다음 →"):"확인"}
            </button>
          </div>
        )}

        <p style={{color:"#64748b",fontSize:"11px",margin:0,textAlign:"center"}}>
          💡 복수 정답은 어느 쪽을 입력해도 정답으로 인정됩니다
        </p>
      </div>
    </div>
  );
}

ReactDOM.createRoot(document.getElementById("root")).render(<App/>);
</script>
</body>
</html>
