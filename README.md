# Python으로 하는 인과추론 : 개념부터 실습까지

## Causal Inference for The Brave and True 책 번역 
[![DOI](https://zenodo.org/badge/255903310.svg)](https://zenodo.org/badge/latestdoi/255903310)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FCausalInferenceLab%2FCausal-Inference-with-Python&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

안녕하세요. [가짜연구소](https://pseudo-lab.com/) Causal Inference 팀입니다.   
<br> 
이 책은 Matheus Facure (Nubank Data Scientist)의 [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)을 한국어로 번역한 자료입니다. 이 책은 인과추론에 대한 기본 개념과 Python 실습, 나아가 최신 사례까지 모두 다루고 있습니다. 인과추론에 대한 이론과 실습자료가 많지 않은 상황에서 이 책은 인과추론 처음 접하거나 인과추론에 대한 이해를 바탕으로 사례를 접하고 싶은 분 모두를 만족시킬 수 있는 책이라고 생각합니다. 한국에서 인과추론을 공부하시는 분들께 많은 도움이 되었으면 좋겠습니다.   
<br>
가짜연구소 Causal Inference 팀은 전문 번역가가 아닌, 데이터분석가/과학자/연구자로 구성 되어 있습니다. 따라서, 한국어 번역 과정에서 이상하거나 어색한 부분이 발생할 수 있어요. 해당 부분에 대한 여러분의 피드백을 부탁드립니다. 또한, 한국어 표현이 익숙하지 않은 부분에 대해서는 영어로 그대로 표현했습니다. 해당 부분 이해부탁드려요. 

<br>
마지막으로, 이 책의 한국어 번역에 동의해 주신 Matheus Facure에게 감사의 말씀을 전합니다.<br>
그리고, 번역과 실습자료를 만들기 위해 같이 고생해준 Causal Inference 팀 멤버들에게도 진심으로 감사드립니다!   
<br>



이 책은 Joshua Angrist, Alberto Abadie, Christopher Walters, Miguel Hernan 및 Jamie Robins 등을 포함한 많은 연구자들의 계량 경제학 수업과 바탕으로 하고 있으며, 대부분의 아이디어는 전미경제학회(American Economic Association)의 수업에서 가져왔습니다. 이 책을 작성하기 위해 참고한 자료와 서적은 아래와 같습니다.   

* [Cross-Section Econometrics](https://www.aeaweb.org/conference/cont-ed/2017-webcasts)
* [Mastering Mostly Harmless Econometrics](https://www.aeaweb.org/conference/cont-ed/2020-webcasts)
* [Mostly Harmless Econometrics](https://www.mostlyharmlesseconometrics.com/)
* [Mastering 'Metrics](https://www.masteringmetrics.com/)
* [Causal Inference Book](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)

<br>

## 한국어 번역 일정 

Causal Inference for The Brave and True에 대한 한국어 번역은 아래와 같은 일정에 따라 진행되었습니다.
Part2의 경우, 저자의 부탁에 따라 추후 진행될 예정입니다.

| 순서 | 완료여부 | Chapter | 완료일 | 작성자 |
| ------ | -- |----------- |------|------|
| 1 | ☑️ | [1. Introduction To Causality](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/01-Introduction-To-Causality.ipynb) | 2022-08-20 | [신진수](https://github.com/jsshin2022)
| 2 | ☑️ | [2. Randomised Experiments](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/02-Randomised-Experiments.ipynb) | 2022-12-04 | [최은희](https://github.com/EunHuiChoi) |
| 3 | ☑️ | [3. Stats Review: The Most Dangerous Equation](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/03-Stats-Review-The-Most-Dangerous-Equation.ipynb) | 2022-11-10 | [김준영](https://github.com/CptAswadu) |
| 4 | ☑️ | [4. Graphical Causal Models](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/04-Graphical-Causal-Models.ipynb) | 2022-11-23 | [김소희](https://github.com/soheekim911) |
| 5 | ☑️ | [5. The Unreasonable Effectiveness of Linear Regression](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/05-The-Unreasonable-Effectiveness-of-Linear-Regression.ipynb) | 2022-11-23 | [남궁민상](https://github.com/wholmesian) |
| 6 | ☑️ | [6. Grouped and Dummy Regression](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/06-Grouped-and-Dummy-Regression.ipynb) | 2022-11-05 | [정호재](https://github.com/wjdghwo) |
| 7 | ☑️  | [7. Beyond Confounders](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/07-Beyond-Confounders.ipynb) | 2022-11-26 | [김상돈](https://github.com/SANGDONKIM) |
| 8 | ☑️ | [8. Instrumental Variables](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/08-Instrumental-variables.ipynb) | 2022-12-04 | [최은희](https://github.com/EunHuiChoi) |
| 9 | ☑️ | [9. Non Compliance and LATE](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/09-Non-Compliance-and-LATE.ipynb) | 2022-11-19 | [김성수](https://github.com/fenzhantw) |
| 10 | ☑️ | [10. Matching](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/10-Matching.ipynb) | 2022-11-04 | [김상돈](https://github.com/SANGDONKIM) 
| 11 | ☑️ | [11. Propensity Score](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/11-Propensity%20Score.ipynb) | 2022-11-11 | [김성수](https://github.com/fenzhantw) |
| 12 | ☑️ | [12. Doubly Robust Estimation](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/12-Doubly-Robust-Estimation.ipynb) | 2022-10-28 | [홍성철](https://github.com/chulhongsung) |
| 13 | ☑️ | [13. Difference-in-Differences](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/13-Difference-in-Differences.ipynb) | 2022-08-27 | [신진수](https://github.com/jsshin2022) |
| 14 | ☑️ | [14. Panel Data and Fixed Effects](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/14-Panel-Data-and-Fixed-Effects.ipynb) | 2022-11-26 | [신진수](https://github.com/jsshin2022) |
| 15 | ☑️ | [15. Synthetic Control](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/15-Synthetic-Control.ipynb) | 2022-09-03 | [정호재](https://github.com/wjdghwo)
| 16 | ☑️ | [16. Regression Discontinuity Design](https://github.com/CausalInferenceLab/Causal-Inference-with-Python/blob/main/causal-inference-for-the-brave-and-true/16-Regression-Discontinuity-Design.ipynb) | 2022-11-22 | [남궁민상](https://github.com/wholmesian) |

<br>
