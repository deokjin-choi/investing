# 투자 연구 저널 — RTX Spark 발표(6/1)와 반도체 종목별 주가 괴리: QCOM 관점

- **작성일:** 2026-06-02
- **태그:** `QCOM` `NVDA` `ARM` `2454.TW` `INTC` `AMD` `MRVL` `RTX-Spark` `WoA` `Agent-PC` `narrative-repricing`
- **파일명:** `2026-06-02-nvda-rtx-spark-computex-qcom-cross-read.md`

---

## 오늘의 질문

2026-06-01 NVIDIA RTX Spark 발표 이후, 같은 뉴스인데 종목별 주가 반응이 갈린 이유는 무엇이며, 6/1 장 마감 시점에서 시장은 QCOM을 어떻게 해석했는가?

## 결론 한 줄

**6/1 QCOM −9%는 EPS가 아니라 "WoA Agent PC" 성장 옵션 할인이며, 같은 RTX Spark 발표를 ARM·MTK·NVDA는 수혜·파트너로, QCOM·INTC는 PC 위협으로 읽었다 — MTK는 NVDA 공동 설계 파트너(+5%), QCOM은 직접 대체 대상(−9%).**

---

## 6/1 종가 수익률

> **종가 기준** 확정치. AMD는 장중 −5% → 종가 보합. QCOM은 프리마켓 −10%대 → 종가 −9%.

```
  +16%  ████████████████  ARM
  +7%   ███████           MRVL
  +6%   ██████            NVDA
  +5%   █████             MediaTek (TW)
   0%   ───────────────── AMD (장중 −5% → 종가 ~flat)
  -5%   █████             INTC
  -9%   █████████         QCOM
```

| 종목 | 티커 | 6/1 수익률 | 거래 시장 |
|------|------|-----------|-----------|
| Arm Holdings | ARM | **+16%** | 미국 |
| Marvell | MRVL | **+7%** | 미국 |
| NVIDIA | NVDA | **+6%** | 미국 |
| MediaTek | 2454.TW | **+5%** | 대만 |
| AMD | AMD | **~0%** (장중 −5%) | 미국 |
| Intel | INTC | **−5%** | 미국 |
| Qualcomm | QCOM | **−9%** | 미국 |

**OEM·파트너 (참고):** Dell +11%, HP +8.5%, Microsoft +2.3%

**QCOM −9% — 시장 해석**

- **실적 miss가 아닌 밸류 재조정.** PC 매출은 전사 IoT에 묶여 있고 점유율 1% 미만이라 당기 EPS 영향은 미미. 2029 PC $40억 목표·6/24 Investor Day 기대가 붙어 있던 주가에서 **WoA Agent PC 프리미엄이 깎인 것**으로 읽힘.
- **당일 QCOM vs NVDA 대비 악화.** Computex에서 QCOM은 Dragonfly **브랜드만** 공개하고 세부는 6/24까지 미룸. NVDA는 RTX Spark로 Agent PC 비전을 선명히 제시 — 시장은 "PC는 NVDA·MTK" 쪽으로 기울었다고 판단.
- **PC 위협 단독이 아님.** ByteDance 급등(+27% 전후) 직후 차익, AMD 약한 가이던스(섹터 약세), Arm–QCOM 라이선스 보도가 겹침. 프리마켓 −10%대 → 종가 −9%로 일부 되돌림.
- **포지션:** thesis 반증 조건 미충족 — **매도 트리거 아님** ([`thesis.md`](./thesis.md) §8.7).

---

## 같은 이벤트, 다른 해석 (6/1 종가)

| 방향 | 종목 | 시장이 읽은 것 |
|------|------|----------------|
| 상승 | ARM (+16%) | WoA PC 칩 증가 → **ISA 로열티** — 승자 무관 구조적 수혜 |
| 상승 | MRVL (+7%) | PC SoC 직접 수혜 아님 — AI DC 네트워킹·Computex 모멘텀 |
| 상승 | NVDA (+6%) | PC **플랫폼 주도권** + Agent PC CUDA 생태계 |
| 상승 | MediaTek (+5%) | QCOM 경쟁자가 아니라 **NVDA RTX Spark 공동 설계** 파트너 |
| 보합 | AMD (~0%) | 장중 −5% 후 회복 — x86 방어·Strix Halo 서사 |
| 하락 | Intel (−5%) | x86 PC 독점에 대한 **Arm+CUDA** 공격 |
| 하락 | QCOM (−9%) | WoA **Snapdragon X 독점 서사 붕괴** — RTX Spark가 GPU·CUDA·Agent로 차별화 |

**QCOM만 −9%인 이유:** (1) RTX Spark vs Snapdragon X = WoA **직접 대체**, (2) MTK는 NVDA **공동**·QCOM은 **대체**, (3) ByteDance·DC 서사로 52주 고점 $259 부근까지 급등 직후 — 되돌릴 여지 없음, (4) PC 매출 미미 → EPS miss가 아닌 **성장 옵션 할인**.

---

## 근거

### 1. 이벤트 요약 (2026-05-31 ~ 2026-06-01)

| 항목 | 내용 | 출처 |
|------|------|------|
| 발표 | RTX Spark: Grace 20코어 + Blackwell RTX(6,144 CUDA), 최대 128GB 통합 메모리, MediaTek CPU·메모리·연결 기여, 가을 2026 OEM 출하 | [NVIDIA Newsroom, 2026-05-31](https://nvidianews.nvidia.com/news/nvidia-microsoft-windows-pcs-agents-rtx-spark) · [MediaTek, 2026-06-01](https://www.mediatek.com/press-room/mediatek-collaborates-with-nvidia-on-rtx-spark-to-power-the-next-wave-of-windows-pc-experiences) |
| 소프트웨어 | Microsoft Windows Agent 보안 primitive + NVIDIA OpenShell; Adobe·게임·llama.cpp 등 생태계 | [NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-microsoft-windows-pcs-agents-rtx-spark) |
| QCOM 당일 | Computex: "Dragonfly" DC 브랜드만 공개, **6/24 Investor Day**에서 세부 내용 공개 예정 | [Yahoo Finance, 2026-06-01](https://finance.yahoo.com/markets/stocks/articles/why-qualcomm-qcom-shares-trading-020051482.html) · [Tickeron, 2026-06-01](https://tickeron.com/blogs/why-is-qualcomm-incorporated-qcom-stock-down-8-today-13848/) |
| 겹친 요인 | AMD 약한 가이던스(섹터 약세), QCOM 전주 ByteDance 뉴스 급등 후 차익, Arm–QCOM 라이선스 이슈 보도 | [CoinCentral, 2026-06-01](https://coincentral.com/qualcomm-qcom-stock-sinks-after-nvidia-ceo-makes-a-bold-pc-move/) · [24/7 Wall St., 2026-06-01](https://247wallst.com/investing/2026/06/01/nvidia-rallies-4-on-rtx-spark-launch-as-qualcomm-falls-7-on-ai-pc-competition-fears/) |

---

### 2. 수익률 출처

| 종목 | 출처 |
|------|------|
| ARM | [Investopedia, 2026-06-01](https://www.investopedia.com/stock-market-today-dow-jones-s-and-p-500-06012026-11987627) · [China Daily Asia](https://www.chinadailyasia.com/article/634277) |
| MRVL | [CNBC MRVL quote](https://www.cnbc.com/quotes/MRVL) · [GuruFocus, 2026-06-01](https://www.gurufocus.com/news/8894543/is-marvell-technology-inc-mrvl-overvalued-after-70-rally-gf-value-says-overvalued) |
| NVDA | [Alain Guillot, 2026-06-01](https://www.alainguillot.com/stock-market-recep-monday-june-1-2026/) · [Dow 30 close](https://www.dow-jones-djia.com/2026/06/01/dow-jones-components-closing-prices-for-monday-june-1-2026/) |
| MediaTek | [China Daily Asia](https://www.chinadailyasia.com/article/634277) · [GuruFocus](https://www.gurufocus.com/news/8893305/nvidia-unveils-rtx-spark-as-arm-surges-14-on-pc-push) |
| AMD | [Alain Guillot](https://www.alainguillot.com/stock-market-recep-monday-june-1-2026/) · [TechTimes, 2026-06-01](https://www.techtimes.com/articles/317544/20260601/nvidia-enters-pc-chip-market-rtx-spark-intel-falls-6-amd-drops-5-open.htm) |
| INTC | [Alain Guillot](https://www.alainguillot.com/stock-market-recep-monday-june-1-2026/) · [Globe and Mail](https://www.theglobeandmail.com/business/technology/article-nvidia-launches-rtx-spark-chip-ai-personal-computers/) |
| QCOM | [Alain Guillot](https://www.alainguillot.com/stock-market-recep-monday-june-1-2026/) · [24/7 Wall St.](https://247wallst.com/investing/2026/06/01/nvidia-rallies-4-on-rtx-spark-launch-as-qualcomm-falls-7-on-ai-pc-competition-fears/) |
| OEM | [Investopedia, 2026-06-01](https://www.investopedia.com/stock-market-today-dow-jones-s-and-p-500-06012026-11987627) |

---

### 3. 같은 뉴스인데 반응이 갈린 이유 (QCOM 중심)

**① "PC 칩 경쟁"이 아니라 "역할 분담"으로 읽힌 종목**

- **ARM (+16%):** RTX Spark·Snapdragon·향후 Arm PC 칩이 늘수록 **ISA 로열티** 수취. 승자가 NVDA든 QCOM이든 Arm은 구조적 수혜 ([China Daily Asia](https://www.chinadailyasia.com/article/634277)).
- **MediaTek (+5%):** QCOM과 경쟁이 아니라 **NVDA RTX Spark 공동 설계**(CPU·메모리 컨트롤러·연결) 파트너 ([MediaTek press](https://www.mediatek.com/press-room/mediatek-collaborates-with-nvidia-on-rtx-spark-to-power-the-next-wave-of-windows-pc-experiences)). OpenAI 폰에서 MTK 단독 유력 보도와 맞물려 **"QCOM 점유율을 MTK가 가져간다"** 는 해석이 강화됨.
- **NVDA (+6%):** PC 프로세서 **플랫폼 주도권** + Agent PC CUDA 생태계 ([NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-microsoft-windows-pcs-agents-rtx-spark)).
- **MRVL (+7%):** PC SoC 직접 수혜가 아님. AI DC 네트워킹(Teralynx 등)·Computex 등장·DC 실적 모멘텀이 주도 ([TradingKey, 2026-06-01](https://www.tradingkey.com/news/market-movers/261939726-market-movers-mrvl-20260601)). 6/2 Huang "next trillion-dollar company" 발언은 **별도 촉매** ([CNBC, 2026-06-02](https://www.cnbc.com/2026/06/02/jensen-huang-nvidia-marvell-technology-trillion-dollar-ai.html)).

**② "PC 점유·마진" 위협으로 읽힌 종목**

- **QCOM (−9%):** Windows on Arm에서 **Snapdragon X 독점 서사 붕괴**. RTX Spark는 동일 OS·동일 Prism 에뮬레이션 스택 위에서 **GPU·CUDA·Agent**로 차별화 ([The Verge, 2026-05-31](https://www.theverge.com/tech/940589/nvidia-rtx-spark-n1-n1x-laptop-desktop-pc-cpu-gpu-ai-release-date)). Microsoft Copilot+ PC(NPU TOPS) 중심 스토리에서 **OpenShell Agent PC** 스토리로 이동하면 QCOM의 85 TOPS NPU 우위가 **마케팅 포인트에서 밀림**. 당일 QCOM 키노트가 빈약하다는 평가가 **NVDA 대비 "AI 인프라 2단 구조"** 인식을 강화 ([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/why-qualcomm-qcom-shares-trading-020051482.html)).
- **Intel (−5%):** x86 PC 40년 독점에 대한 **Arm+CUDA** 공격 ([Globe and Mail](https://www.theglobeandmail.com/business/technology/article-nvidia-launches-rtx-spark-chip-ai-personal-computers/)).
- **AMD (~0%, 장중 −5%):** 프리미엄 노트북·통합 GPU 위협으로 장중 −5%까지 밀렸으나, x86 방어·Strix Halo 서사로 **종가는 보합** ([TechTimes, 2026-06-01](https://www.techtimes.com/articles/317544/20260601/nvidia-enters-pc-chip-market-rtx-spark-intel-falls-6-amd-drops-5-open.htm)).

**③ QCOM만 −9%로 크게 빠진 구조적 이유**

1. **동일 제품군:** RTX Spark vs Snapdragon X — WoA **직접 대체** 관계 ([24/7 Wall St.](https://247wallst.com/investing/2026/06/01/nvidia-rallies-4-on-rtx-spark-launch-as-qualcomm-falls-7-on-ai-pc-competition-fears/)).
2. **파트너 vs 대체:** MTK는 NVDA와 **공동 설계**, QCOM은 **대체 대상** — 6/1 주가가 반대 방향.
3. **기대치·완충 여지:** QCOM은 ByteDance·DC 서사로 **52주 고점 $259 부근**까지 급등 직후 ([CoinCentral](https://coincentral.com/qualcomm-qcom-stock-sinks-after-nvidia-ceo-makes-a-bold-pc-move/)) — PC 악재에 **되돌릴 여지 없음**.
4. **실적 vs 서사:** PC 매출 미미 → **EPS miss가 아니라 성장 옵션 할인** ([Invezz, 2026-06-01](https://invezz.com/in/news/2026/06/01/what-does-nvidias-laptop-chip-mean-for-intel-amd-and-qualcomm/) · [Dolphin Research, 2026-05](https://dolphinresearch.substack.com/p/qcom-can-the-ai-boost-offset-handset)).

---

### 4. QCOM thesis 연결 ([`thesis.md`](./thesis.md) 기준)

| thesis 요소 | RTX Spark 이전 | 6/1 이후 변화 |
|-------------|----------------|---------------|
| **재평가 축 (Auto·IoT·비스마트폰)** | 진행 중 (Auto +38% YoY Q2 FY26) | **변화 없음** — 실적 축 유효 ([QCOM Q2 FY26 earnings](https://www.fool.com/earnings/call-transcripts/2026/04/29/qualcomm-qcom-q2-2026-earnings-transcript/)) |
| **엣지 AI PC (Snapdragon X2)** | WoA 주도 서사 | **Agent PC 주도권은 NVDA 쪽으로 이동** — "Copilot+ 물량" vs "CUDA Agent 프리미엄" 이원화 |
| **하이퍼스케일러 DC (4/29)** | 12월 초도 출하, ByteDance 추정 | **PC 충격과 독립** — 6/24에서 숫자 나오면 서사 일부 회복 가능 |
| **반증 (Apple 모뎀 등)** | 이미 thesis에 명시 | RTX Spark **직접 충족 아님** — 다만 "다각화 스토리" 설득력 **PC 축에서 약화** |

- **6/1 시점 해석:** 시장은 QCOM을 "모바일 + DC 옵션"이 아니라 **"모바일 + DC 옵션 − PC 옵션"** 으로 재평가하기 시작한 것으로 보임.

---

### 5. 시나리오 (현재 시점 추정 발생확률)

> 확률은 2026-06-02 시점 **주관적 prior**. Fall RTX Spark 실물·6/24 ID·ByteDance 출하 전, **낮은 확신** — 분기마다 갱신 전제.

| ID | 시나리오 | 발생확률 | QCOM 주가·thesis 함의 | 관측 포인트 |
|----|----------|----------|------------------------|-------------|
| **S1** | **일시적 서사 할인 (3~6개월 후 소멸)** | **40%** | 6/1 −9%의 ~½은 PC 위협, ~½은 Computex 실망·차익. 6/24 DC 구체화 + ByteDance 출하 일정 유지 시 **스마트폰+자동차+DC 중심** 낙관론으로 회복. PC $40억 목표는 하향 조정되도 **thesis 유효** 유지 | 6/24 ID; Q2/Q3 DC 코멘터리; QCOM X2 Plus OEM 물량 |
| **S2** | **구조적 PC 서사 할인 (6~18개월 부담 지속)** | **35%** | Fall RTX Spark 리뷰·OEM 물량 양호 → "Agent PC = NVDA" 고착. 애널리스트 PC TAM 점유율 하향. **P/E 1~2 turn** 하향 가능. EPS는 크지만 **멀티플 축** 손실 | RTX Spark 가격·벤치; Adobe/Agent 앱 네이티브 비율; MSFT taskbar Agent UX |
| **S3** | **RTX Spark 틈새 실패 → QCOM WoA 물량 회복** | **15%** | x86 Prism·가격·$1,500+ 틈새 한계 ([Invezz](https://invezz.com/in/news/2026/06/01/what-does-nvidias-laptop-chip-mean-for-intel-amd-and-qualcomm/)). QCOM **$600~900 Copilot+** 가격대 재부각. 6/1 하락 **과잉 반응** | Fall 2026 판매 실적; RTX Spark 16GB vs 128GB 플래그십 mix |
| **S4** | **복합 악화 (PC + DC 실망)** | **10%** | 6/24 ID 빈약 + Apple/China handset 악화 동시. **thesis 재검토** (§8.7 −20% 트리거 점검). PC는 촉매가 아니라 **신뢰 붕괴** | 6/24; China handset guide; Apple modem timeline |

**기대값 방향 (정성):** S1+S3(55%) vs S2+S4(45%) — **단기 추가 하락 vs 횡보**가 팽팽. **중장기 thesis 유효성**은 S1·S3에서 유지, S2에서 "PC 축 포기·DC+auto만"으로 재정의 필요.

---

### 6. [`thesis.md`](./thesis.md) / [`log.md`](./log.md) 후속 작업 (미반영)

- **thesis.md:** "RTX Spark / WoA Agent PC 서사 위협" 소절 추가 검토; **현재 상태** 날짜 2026-06-02 갱신.
- **log.md:** 6/1 −9% 관찰, **매도 없음** — 서사 충격, thesis 반증 미충족 (필요 시 한 줄).

---

*근거 URL은 작성일 접근 가능 기준. §6/1 수익률은 사용자 확정 종가 기준(2026-06-02 갱신).*
