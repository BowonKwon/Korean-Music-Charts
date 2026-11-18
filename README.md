# 가요 차트 100년 · Korean Music Charts

누가, 무엇으로, 어떻게 한국 가요의 순위를 매겨 왔는지를 1906년 유성기 녹음부터 디지털 차트까지 한 연대표로 잇는 역사 사이트입니다.

A history site that traces, on one timeline from the first gramophone recordings of 1906 to digital charts, who ranked Korean popular songs, with what, and how.

- 사이트 · Site: https://bowonkwon.github.io/Korean-Music-Charts/

## 내용 · Contents

| 장 · Chapter | 시기 · Period |
|---|---|
| 0. 순위를 매기는 방법들 · Ways of ranking songs | 1906–2026 |
| 1. 목록의 시대 · The age of catalogs | 1906–1945 |
| 2. 시상식의 시대 · The age of awards | 1945–1980 |
| 3. 주간 순위 프로그램 · Weekly chart shows | 1981–1998 |
| 4. 판매 집계의 시대와 공백 · Sales tallies and gaps | 1998–2010 |
| 5. 공인 차트와 플랫폼 · Official charts and platforms | 2010– |

## 데이터 · Data

`data/` 의 CSV(UTF-8)는 곡명·가수명·순위·날짜·판매량 같은 사실만 담습니다. 행마다 1차 출처와 대조 상태를 적었습니다. 「가요톱10」 표는 백과사전 목록을 뼈대로 삼았고, 당대 신문으로 확인한 행에만 1차 출처가 있습니다.

The CSV files in `data/` (UTF-8) hold only facts such as titles, artists, ranks, dates, and sales, with a primary source and check status for each row. The *Gayo Top 10* table is framed on an encyclopedia list; only rows checked against newspapers of the time carry a primary source.

## 하지 않는 것 · Scope

가사·음원·음반 표지·방송 화면·지면 이미지는 싣지 않습니다. 특정 가수나 기획사의 순위 조작 의혹은 다루지 않으며, 가수의 인기를 비교하는 지표를 만들지 않습니다.

No lyrics, audio, album covers, broadcast images, or newspaper page images are published. The site does not discuss allegations of chart manipulation against any singer or agency and builds no measure comparing singers' popularity.

## 판 이력 · Version history

판 번호는 사이트 아래쪽 꼬리글에 있습니다. · The version number is in the footer of every page.

| 판 · Version | 날짜 · Date | 바뀐 것 · Changes |
|---|---|---|
| 0.1.5 | 2026-11-18 | 목차에서 장·절로 바로 가기(장 목록, 면 안 절 목록, 절 제목 바로가기, 처음 면의 전체 목차), 넓은 화면에서 위쪽 메뉴 고정. 본문·수치 변화 없음 · Straight from the contents to a chapter or section (chapter list, section list on each page, links on section headings, full contents on the home page); the top menu stays on wide screens. No text or numerical value changed |
| 0.1.4 | 2026-11-16 | 그래프 설명 보강(축 이름과 단위, 띠 그림의 두 줄 묶음 이름, 자료에서 계산한 읽는 법, 「가요톱10」 1위 연속 막대 두 묶음을 같은 눈금으로, 시상식 줄 이름에 KBS 구간 표시), 좁은 화면에서 그림 옆으로 넘기기, 공개 자료 허브 링크. 자료 값 변화 없음 · Chart explanations (axis names and units, the two row groups named on the band chart, readings computed from the data, both No. 1-run panels on one scale, award row renamed to show the KBS segment), sideways scrolling on narrow screens, hub link. No data value changed |
| 0.1.3 | 2026-11-06 | 동아방송 「이주일의 10대가요」 1972년 10월 28일 순위표 판독(1위와 지난주 1위)을 2장과 자료에 반영 · DBS weekly top 10 of 28 October 1972 read (No. 1 and the previous week's No. 1), added to Chapter 2 and the data |
| 0.1.2 | 2026-11-06 | 첫 공개. 동아일보 지면 대조 결과를 3장에 반영하고, 「삼천리」 지면으로 인쇄된 합계를 확인 · First public release. Results of checks against Dong-A Ilbo pages added to Chapter 3; the printed totals in *Samcheolli* confirmed from the page image |

## 라이선스 · License

[LICENSE.md](LICENSE.md)
