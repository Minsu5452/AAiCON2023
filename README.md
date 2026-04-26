# AI Frenz 2023 Publication

> 2023년 제2차 실용 인공지능 학술대회(AAiCON 2023)에 수록된 논문 기록입니다. SNP 기반 품종 분류 모델링 과정을 연구 문서와 notebook 형태로 정리했습니다.

## Overview

| 항목 | 내용 |
| --- | --- |
| 학술대회 | 2023년 제2차 실용 인공지능 학술대회 (AAiCON 2023) |
| 기간 | 2023.02.09 ~ 2023.02.10 |
| 논문 유형 | 학술대회 수록 논문 |
| 논문 제목 | SNP 정보를 활용한 유전체 품종 분류 모델링에 대한 연구 |
| 저자 | 강민수, 이상우, 이상준 |
| 역할 | 공동 저자, 모델링 과정 정리 및 논문 작성 |
| 연구 배경 | 유전체 정보 품종 분류 AI 경진대회 우승작 발표 논문 |
| 연계 레포 | [Genomic_Data_Breed_Classification](https://github.com/Minsu5452/Genomic_Data_Breed_Classification) |

## Research Summary

이 연구는 SNP(Single Nucleotide Polymorphism) 정보를 활용해 가축 품종을 분류하는 문제를 다룹니다. 데이터 수가 제한적이고 클래스 불균형이 존재하는 조건에서 feature engineering, class imbalance handling, hard voting ensemble을 적용해 분류 성능을 개선하는 방향으로 접근했습니다.

최종 논문에서는 단일 모델 성능 비교와 ensemble 결과를 함께 정리했으며, VotingClassifier 기반 hard voting ensemble에서 가장 높은 Macro-F1 score를 확인했습니다.

## Repository Contents

- `aaicon_2023_proceedings.pdf`: AAiCON 2023 학술대회 논문집/목차 자료
- `snp_breed_classification_research_notebook.ipynb`: 제출용 연구 notebook

## Notes

- 원본 대회 데이터는 저장소에 포함하지 않았습니다.
- notebook은 공개 포트폴리오용으로 출력 결과와 실행 메타데이터를 제거했습니다.
- 실제 모델링 실험 코드는 별도 레포인 [Genomic_Data_Breed_Classification](https://github.com/Minsu5452/Genomic_Data_Breed_Classification)에 정리되어 있습니다.
- 이 저장소는 competition solution 자체보다, 학술대회 publication record에 초점을 둡니다.

## Related Links

- [Winning solution repository](https://github.com/Minsu5452/Genomic_Data_Breed_Classification)
- [DACON competition page](https://dacon.io/competitions/official/236035/overview/description)
- [AI Frenz](http://aifrenz.org)
