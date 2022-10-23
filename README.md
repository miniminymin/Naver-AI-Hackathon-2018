# 원형 코드
https://github.com/miniminymin/Naver-AI-Hackathon-2018


# Model
Character Level Embedding + Bi-directional LSTM + multi-layer CNN + Fully connect layer

-><strong>Data is private but you can see details with [our paper](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07503227)</strong>

# Score
Mse : 2.67 **(2nd prize at final)**

# 사전 수행
$ pip install git+https://github.com/n-CLAIR/nsml-local # 대회 당시 nsml 환경 local 설치
$ pip install tf-slim # tensorflow ver 1.x에서만 지원하던 코드 변형을 위해 추가

# Authors
**Yongwoo Cho(조용우)**
- https://nomorecoke.github.io
- https://github.com/nomorecoke

**Gyusu Han(한규수)**
- https://gyusu.github.io
- https://github.com/gyusu

## License
```
Copyright 2018 NAVER Corp.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
