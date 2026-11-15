# 중국 APT 작전 지도

중국 연계 APT 9개 그룹이 어디를, 무엇을 노리는지 세계 지도 한 장에 정리했다.

**지도 보기**: https://accompanywithjesus.github.io/china-APT/

## 무엇을 볼 수 있나

- APT1, APT3, APT10, APT27, APT30, APT40, APT41, Salt Typhoon, Volt Typhoon의 표적 지역
- 표적 마커를 누르면 그 작전의 MITRE ATT&CK 전술·기법
- 공격이 거쳐 가는 C2 경유지 노드

## 왜 만들었나

국가가 배후에 있는 APT는 돈이 아니라 정보를 노리고, 들키지 않은 채 오래 머문다.
개별 사건만 보면 보이지 않는 패턴을, 그룹별 표적을 한 지도에 겹쳐 놓고 읽기 위해 만들었다.

## 만든 방법

- Python folium으로 지도 생성
- GitHub Pages로 배포
- 공개 위협 보고서와 MITRE ATT&CK을 근거로 정리

## 참고

- 공개 자료 기준이며, 배후 판단은 확정이 아니라 가능성이다
- 지도는 초기 분석을 바탕으로 BPFDoor를 APT41 항목에 표시했다. 이후 분석(Trend Micro 2025, Rapid7 2026)을 반영해 SKT 사례 분석에서는 레드 멘션(Red Menshen)을 유력 후보로 본다

## 만든 사람

김주영 · 신라대학교 AI·컴퓨터공학 · 사이버 위협 인텔리전스(CTI)
