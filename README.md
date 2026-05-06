<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sound Engineer Portfolio</title>
    <style>
        body { background-color: #0e1111; color: #ffffff; font-family: sans-serif; line-height: 1.6; padding: 40px; }
        header { text-align: center; border-bottom: 2px solid #00ffcc; padding-bottom: 20px; margin-bottom: 40px; }
        h1 { color: #00ffcc; }
        section { background: #1a1a1a; padding: 20px; border-radius: 10px; margin-bottom: 20px; border-left: 5px solid #00ffcc; }
        h2 { color: #00ffcc; }
        .wave-box { display: flex; align-items: flex-end; height: 50px; gap: 3px; margin-top: 15px; }
        .bar { flex: 1; background: #00ffcc; height: 20%; animation: move 1s infinite alternate; }
        @keyframes move { from { height: 20%; } to { height: 100%; } }
        .bar:nth-child(2n) { animation-duration: 0.7s; }
        .bar:nth-child(3n) { animation-duration: 1.2s; }
    </style>
</head>
<body>
    <header>
        <h1>SOUND ENGINEER PORTFOLIO</h1>
        <p>물리학과 디지털 기술로 소리를 설계하다</p>
    </header>
    <section>
        <h2>01. 연구 주제: 주파수 응답 특성 분석</h2>
        <p>인간의 가청 주파수 대역 내에서 이퀄라이징(EQ)이 음색의 선명도에 미치는 영향을 탐구했습니다.</p>
        <div class="wave-box">
            <div class="bar"></div><div class="bar"></div><div class="bar"></div><div class="bar"></div>
            <div class="bar"></div><div class="bar"></div><div class="bar"></div><div class="bar"></div>
        </div>
    </section>
    <section>
        <h2>02. 디지털 오디오 원리 (ADC/DAC)</h2>
        <p>아날로그 파동이 어떻게 샘플링과 양자화 과정을 거쳐 디지털 신호로 변환되는지 학습했습니다.</p>
    </section>
    <section>
        <h2>03. 진로 목표 및 활동</h2>
        <p>단순한 음악 녹음을 넘어, 공간 음향과 물리적 잔향의 관계를 연구하는 엔지니어가 되고자 합니다.</p>
    </section>
    <div style="text-align:center; color:#666;">&copy; 2024 Sound Engineer Portfolio Project.</div>
</body>
</html>
