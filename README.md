# Network Science: Interactive Demos
**경상국립대학교 물리학과 네트워크 과학 교과목 보조자료**

Landing page for the interactive web demos that accompany *Network Science* (네트워크 과학) in the Department of Physics, Gyeongsang National University.

**Live page:** https://lshlj82.github.io/network-science/

Created by Claude Opus 5.5, based on the lecture slides by Prof. Sang Hoon Lee.
이상훈 교수의 강의 슬라이드를 바탕으로 Claude Opus 5.5가 만들었습니다.

## Demos · 데모 목록

| # | Demo | 데모 | Links |
|---|------|------|-------|
| 1 | Network elements | 네트워크의 기본 요소 | [demo](https://lshlj82.github.io/network-basics/) · [source](https://github.com/lshlj82/network-basics) |
| 2 | Diffusion on networks | 네트워크 위의 확산 | [demo](https://lshlj82.github.io/diffusion-on-networks/) · [source](https://github.com/lshlj82/diffusion-on-networks) |
| 3 | Network assortativity | 네트워크 동류성 | [demo](https://lshlj82.github.io/network-assortativity/) · [source](https://github.com/lshlj82/network-assortativity) |
| 4 | Percolation on networks | 네트워크 위의 스며들기 | [demo](https://lshlj82.github.io/percolation-on-networks/) · [source](https://github.com/lshlj82/percolation-on-networks) |
| 5 | Small-world effect | 좁은 세상 효과 | [demo](https://lshlj82.github.io/small-world/) · [source](https://github.com/lshlj82/small-world) |
| 6 | Network centrality | 네트워크 중심도 | [demo](https://lshlj82.github.io/network-centrality/) · [source](https://github.com/lshlj82/network-centrality) |
| 7 | Scale-free networks | 척도 없는 네트워크 | [demo](https://lshlj82.github.io/SFN/) · [source](https://github.com/lshlj82/SFN) |
| 8 | Friendship paradox | 친구 역설 | [demo](https://lshlj82.github.io/FP-netsci-course/) · [source](https://github.com/lshlj82/FP-netsci-course) |
| 9 | Network models | 네트워크 모형 | [demo](https://lshlj82.github.io/network-models/) · [source](https://github.com/lshlj82/network-models) |
| 10 | Network communities | 네트워크 커뮤니티 | [demo](https://lshlj82.github.io/network-community/) · [source](https://github.com/lshlj82/network-community) |
| 11 | Network dynamics | 네트워크 동역학 | [demo](https://lshlj82.github.io/network-dynamics/) · [source](https://github.com/lshlj82/network-dynamics) |

## About the page · 페이지 소개

The page is a single self-contained `index.html` with no build step. Its header runs a live version of the configuration model from demo 9: 150 nodes receive a number of stubs drawn from either a Poisson or a power-law distribution, and random pairs of stubs are joined one at a time. Pairs that would create a self-loop or a multi-edge are rejected and redrawn, so the result is a simple graph. A second panel tracks the degree distribution as links form, against the target sequence and the theoretical distribution. For the Poisson case a slider sets the mean degree ⟨*k*⟩ from 1 to 6; for the power law it sets the exponent γ from 2.1 to 3.5, with degrees between 2 and 40, and the plot switches to log–log axes.

The page supports light and dark mode, adapts to phone screens, and shows the finished network without animation for visitors who have reduced motion turned on.

페이지는 빌드 과정 없이 `index.html` 파일 하나로 이루어져 있습니다. 상단에서는 데모 9의 구성 모형을 실시간으로 실행합니다. 노드 150개가 푸아송 분포 또는 거듭제곱 분포에서 뽑은 개수의 미연결 링크를 받고, 무작위로 고른 미연결 링크 쌍이 하나씩 이어집니다. 자기 고리나 중복 링크를 만드는 쌍은 버리고 다시 고르므로 결과는 단순 그래프입니다.

## Running locally · 로컬에서 실행

Open `index.html` in any modern browser. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Deploying · 배포

1. Put `index.html` and this `README.md` at the root of the repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The page will be served at `https://lshlj82.github.io/<repository-name>/`.

## References · 참고문헌

- Filippo Menczer, Santo Fortunato, and Clayton A. Davis, [*A First Course in Network Science*](https://www.amazon.com/First-Course-Network-Science/dp/1108471137) (Cambridge University Press, 2020).<br>
  한국어판: [『네트워크 분석』](https://www.acornpub.co.kr/product/네트워크-분석/5797/category/25/display/1/) (에이콘출판사, 2022)
- Mark Newman, [*Networks*, 2nd Edition](https://www.amazon.com/Networks-Mark-Newman/dp/0198805098/) (Oxford University Press, 2018).<br>
  한국어판: [『네트워크 2/e』](https://www.acornpub.co.kr/product/네트워크-2e/5888/category/25/display/1/) (에이콘출판사, 2022)
- Albert-László Barabási, [*Network Science*](https://networksciencebook.com) (Cambridge University Press, 2016).<br>
  한국어판: [『네트워크 사이언스』](https://www.acornpub.co.kr/product/네트워크-사이언스/5911/category/25/display/1/) (에이콘출판사, 2023)
- Sergey N. Dorogovtsev and José F. F. Mendes, [*The Nature of Complex Networks*](https://global.oup.com/academic/product/the-nature-of-complex-networks-9780199695119) (Oxford University Press, 2022).<br>
  한국어판: [『복잡계 네트워크의 자연법칙』](https://www.acornpub.co.kr/product/복잡계-네트워크의-자연법칙/6086/category/24/display/1/) (에이콘출판사, 2026)
- Prof. Sang Hoon Lee, lecture slides for Network Science. (이상훈 교수, 네트워크 과학 강의 슬라이드)
