<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>도담 인테리어 | 무료 상담</title>
  <meta name="description" content="모던하고 따뜻한 우드 인테리어. 주거·상업공간 맞춤 설계부터 시공, A/S까지. 무료 상담 신청하세요." />

  <!-- Pretendard (옵션) -->
  <link rel="preconnect" href="https://cdn.jsdelivr.net" />
  <link rel="stylesheet" as="style" href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/variable/pretendardvariable.css" />

  <style>
    :root{
      --bg:#ffffff;
      --bg-soft:#F3F7F4;
      --ink:#0F1A13;
      --muted:#5C6B63;
      --green:#1F3D2B;
      --green-2:#2D5A40;
      --wood:#8B6F4E;
      --line:rgba(15,26,19,.10);
      --shadow: 0 10px 30px rgba(15,26,19,.08);
      --radius: 18px;
      --radius-lg: 26px;
      --max: 1120px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0}
    body{
      font-family: "Pretendard Variable", Pretendard, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans KR", Arial, sans-serif;
      background:var(--bg);
      color:var(--ink);
      line-height:1.5;
    }
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .container{max-width:var(--max);margin:0 auto;padding:0 20px}
    .pill{display:inline-flex;gap:8px;align-items:center;padding:8px 12px;border:1px solid var(--line);border-radius:999px;background:#fff}
    .dot{width:8px;height:8px;border-radius:50%;background:var(--green)}
    .topbar{
      position:sticky;top:0;z-index:50;
      background:rgba(255,255,255,.8);
      backdrop-filter: blur(10px);
      border-bottom:1px solid var(--line);
    }
    .nav{
      display:flex;align-items:center;justify-content:space-between;
      height:68px;
    }
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:40px;height:40px;border-radius:14px;
      background: linear-gradient(135deg, var(--green), var(--green-2));
      box-shadow: 0 8px 20px rgba(31,61,43,.18);
      position:relative;
    }
    .logo:after{
      content:"";
      position:absolute;inset:10px 9px 9px 10px;
      border-radius:12px;
      border:2px solid rgba(255,255,255,.75);
      transform: rotate(8deg);
    }
    .brand strong{font-size:16px;letter-spacing:-.2px}
    .brand span{display:block;font-size:12px;color:var(--muted)}
    .navlinks{display:flex;gap:18px;align-items:center}
    .navlinks a{font-size:14px;color:var(--muted)}
    .navlinks a:hover{color:var(--ink)}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;
      padding:12px 16px;border-radius:999px;border:1px solid transparent;
      font-weight:600;font-size:14px;cursor:pointer;
      transition: all .2s ease;
      white-space:nowrap;
    }
    .btn-primary{background:var(--green);color:#fff;box-shadow: 0 10px 24px rgba(31,61,43,.18)}
    .btn-primary:hover{background:var(--green-2);transform: translateY(-1px)}
    .btn-ghost{background:#fff;border-color:var(--line);color:var(--ink)}
    .btn-ghost:hover{border-color:rgba(15,26,19,.18);transform: translateY(-1px)}
    .hero{
      padding:42px 0 28px;
      background:
        radial-gradient(900px 260px at 20% 10%, rgba(31,61,43,.08), transparent 60%),
        radial-gradient(700px 220px at 80% 0%, rgba(139,111,78,.10), transparent 60%);
    }
    .hero-grid{
      display:grid;grid-template-columns: 1.15fr .85fr;
      gap:26px;align-items:stretch;
    }
    .hero-card{
      background:#fff;border:1px solid var(--line);
      border-radius: var(--radius-lg);
      box-shadow: var(--shadow);
      padding:26px;
    }
    .kicker{color:var(--green);font-weight:700;font-size:13px;letter-spacing:.2px}
    h1{margin:10px 0 12px;font-size:42px;line-height:1.12;letter-spacing:-1px}
    .sub{margin:0;color:var(--muted);font-size:16px}
    .hero-cta{display:flex;gap:10px;align-items:center;margin-top:18px;flex-wrap:wrap}
    .trustrow{display:flex;gap:14px;flex-wrap:wrap;margin-top:18px}
    .chip{
      display:inline-flex;gap:8px;align-items:center;
      padding:10px 12px;border-radius:999px;
      background:var(--bg-soft);border:1px solid rgba(31,61,43,.12);
      color:var(--muted);font-size:13px;
    }
    .chip b{color:var(--ink)}
    .hero-media{
      border-radius: var(--radius-lg);
      overflow:hidden;
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      position:relative;
      background:
        linear-gradient(135deg, rgba(31,61,43,.18), rgba(139,111,78,.18)),
        url("https://images.unsplash.com/photo-1505691938895-1758d7feb511?auto=format&fit=crop&w=1400&q=80");
      background-size: cover;
      background-position:center;
      min-height: 420px;
    }
    .hero-media:after{
      content:"";
      position:absolute;inset:0;
      background: linear-gradient(180deg, rgba(255,255,255,.0), rgba(255,255,255,.68));
    }
    .media-badge{
      position:absolute;left:18px;top:18px;z-index:2;
      background:rgba(255,255,255,.88);
      border:1px solid var(--line);
      border-radius:999px;
      padding:10px 12px;
      display:inline-flex;gap:10px;align-items:center;
      backdrop-filter: blur(8px);
    }
    .media-badge .mini{width:10px;height:10px;border-radius:50%;background:var(--wood)}
    .media-badge b{font-size:13px}
    .section{padding:48px 0}
    .section.soft{background:var(--bg-soft);border-top:1px solid rgba(15,26,19,.06);border-bottom:1px solid rgba(15,26,19,.06)}
    .section h2{margin:0 0 10px;font-size:28px;letter-spacing:-.6px}
    .section p.lead{margin:0 0 22px;color:var(--muted)}
    .grid-3{display:grid;grid-template-columns: repeat(3,1fr);gap:14px}
    .card{
      background:#fff;border:1px solid var(--line);
      border-radius: var(--radius);
      padding:18px;
      box-shadow: 0 12px 24px rgba(15,26,19,.05);
    }
    .icon{
      width:44px;height:44px;border-radius:14px;
      background: linear-gradient(135deg, rgba(31,61,43,.14), rgba(139,111,78,.14));
      border:1px solid rgba(15,26,19,.08);
      display:flex;align-items:center;justify-content:center;
      font-weight:900;color:var(--green);
    }
    .card h3{margin:12px 0 6px;font-size:16px}
    .card p{margin:0;color:var(--muted);font-size:14px}

    .gallery{
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap:14px;
    }
    .gal-big, .gal-small{
      border-radius: var(--radius-lg);
      overflow:hidden;
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      background-size:cover;background-position:center;
      min-height: 360px;
      position:relative;
    }
    .gal-small{min-height: 173px}
    .gal-col{display:grid;gap:14px}
    .label{
      position:absolute;left:14px;bottom:14px;
      background:rgba(255,255,255,.88);
      border:1px solid var(--line);
      border-radius:999px;
      padding:10px 12px;
      font-size:13px;color:var(--muted);
      backdrop-filter: blur(10px);
    }
    .label b{color:var(--ink)}
    .steps{display:grid;grid-template-columns: repeat(5,1fr);gap:10px}
    .step{
      background:#fff;border:1px solid var(--line);
      border-radius: var(--radius);
      padding:14px;
      position:relative;
    }
    .step .n{
      width:30px;height:30px;border-radius:999px;
      background:var(--green);color:#fff;
      display:flex;align-items:center;justify-content:center;
      font-weight:800;font-size:13px;
      box-shadow: 0 10px 18px rgba(31,61,43,.18);
    }
    .step h4{margin:10px 0 6px;font-size:14px}
    .step p{margin:0;color:var(--muted);font-size:13px}

    .cta-wrap{
      display:grid;grid-template-columns: .95fr 1.05fr;
      gap:16px;align-items:stretch;
    }
    .cta-side{
      border-radius: var(--radius-lg);
      padding:22px;
      background: linear-gradient(135deg, rgba(31,61,43,.10), rgba(139,111,78,.10));
      border:1px solid rgba(15,26,19,.10);
    }
    .cta-side h3{margin:0 0 8px;font-size:20px;letter-spacing:-.4px}
    .cta-side p{margin:0 0 14px;color:var(--muted)}
    .cta-points{display:grid;gap:10px;margin-top:12px}
    .point{display:flex;gap:10px;align-items:flex-start}
    .check{
      width:22px;height:22px;border-radius:8px;
      background:rgba(31,61,43,.12);
      border:1px solid rgba(31,61,43,.18);
      display:flex;align-items:center;justify-content:center;
      color:var(--green);font-weight:900;font-size:13px;
      flex:0 0 auto;
    }
    form{
      background:#fff;border:1px solid var(--line);
      border-radius: var(--radius-lg);
      box-shadow: var(--shadow);
      padding:22px;
    }
    .row{display:grid;grid-template-columns: 1fr 1fr;gap:12px}
    label{display:block;font-size:12px;color:var(--muted);margin:10px 0 6px}
    input, select, textarea{
      width:100%;
      padding:12px 12px;
      border-radius:14px;
      border:1px solid rgba(15,26,19,.14);
      outline:none;
      font-size:14px;
      background:#fff;
      transition: border .2s ease, box-shadow .2s ease;
    }
    input:focus, select:focus, textarea:focus{
      border-color: rgba(31,61,43,.45);
      box-shadow: 0 0 0 4px rgba(31,61,43,.10);
    }
    textarea{min-height:110px;resize:vertical}
    .form-actions{display:flex;gap:10px;align-items:center;margin-top:14px;flex-wrap:wrap}
    .note{color:var(--muted);font-size:12px;margin:8px 0 0}
    .sticky-mobile{
      position:fixed;left:0;right:0;bottom:0;z-index:60;
      background: rgba(255,255,255,.86);
      backdrop-filter: blur(10px);
      border-top:1px solid var(--line);
      padding:10px 14px;
      display:none;
    }
    .sticky-mobile .inner{display:flex;gap:10px;align-items:center;justify-content:space-between}
    .sticky-mobile .txt{font-size:13px;color:var(--muted)}
    footer{
      padding:26px 0;
      border-top:1px solid var(--line);
      color:var(--muted);
      font-size:13px;
    }

    /* Responsive */
    @media (max-width: 980px){
      .hero-grid{grid-template-columns:1fr}
      .hero-media{min-height: 320px}
      .grid-3{grid-template-columns:1fr}
      .gallery{grid-template-columns:1fr}
      .steps{grid-template-columns:1fr 1fr}
      .cta-wrap{grid-template-columns:1fr}
      h1{font-size:34px}
      .navlinks{display:none}
      .sticky-mobile{display:block}
      body{padding-bottom:68px}
    }
  </style>
</head>

<body>
  <!-- Topbar -->
  <div class="topbar">
    <div class="container">
      <div class="nav">
        <a class="brand" href="#top">
          <div class="logo" aria-hidden="true"></div>
          <div>
            <strong>도담 인테리어</strong>
            <span>모던 · 우드 · 책임 시공</span>
          </div>
        </a>

        <div class="navlinks">
          <a href="#why">특장점</a>
          <a href="#portfolio">시공사례</a>
          <a href="#process">진행절차</a>
          <a href="#contact">상담신청</a>
        </div>

        <a class="btn btn-primary" href="#contact" aria-label="무료 상담 신청">무료 상담</a>
      </div>
    </div>
  </div>

  <!-- Hero -->
  <section class="hero" id="top">
    <div class="container">
      <div class="hero-grid">
        <div class="hero-card">
          <div class="pill"><span class="dot"></span><span class="kicker">WHITE & GREEN · MODERN WOOD</span></div>
          <h1>공간의 가치를 완성하는<br/>모던 우드 인테리어</h1>
          <p class="sub">
            주거 · 상업공간 맞춤 설계부터 시공, A/S까지.<br/>
            복잡한 과정은 줄이고, 결과는 더 깔끔하게.
          </p>

          <div class="hero-cta">
            <a class="btn btn-primary" href="#contact">무료 상담 신청하기</a>
            <a class="btn btn-ghost" href="#portfolio">시공사례 보기</a>
          </div>

          <div class="trustrow">
            <div class="chip"><b>투명 견적</b> · 공정 안내</div>
            <div class="chip"><b>1:1 맞춤</b> · 디자인 제안</div>
            <div class="chip"><b>A/S</b> · 책임 시공</div>
          </div>

          <p class="note">* 상담은 무료이며, 무리한 영업 없이 필요한 범위만 제안합니다.</p>
        </div>

        <div class="hero-media" role="img" aria-label="우드 톤 모던 인테리어">
          <div class="media-badge">
            <span class="mini"></span>
            <b>따뜻한 우드 + 미니멀</b>
            <span style="font-size:12px;color:var(--muted)">시공 퀄리티 중심</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- WHY -->
  <section class="section" id="why">
    <div class="container">
      <h2>왜 도담 인테리어인가요</h2>
      <p class="lead">첫 상담부터 완공까지, 고객이 불안해하는 지점을 먼저 해결합니다.</p>

      <div class="grid-3">
        <div class="card">
          <div class="icon">01</div>
          <h3>1:1 맞춤 설계</h3>
          <p>라이프스타일/동선/수납까지 고려한 실사용 중심 제안.</p>
        </div>
        <div class="card">
          <div class="icon">02</div>
          <h3>투명한 견적 & 공정</h3>
          <p>자재·공정·기간을 명확히 안내하고, 변경사항은 사전 공유.</p>
        </div>
        <div class="card">
          <div class="icon">03</div>
          <h3>모던·우드 전문</h3>
          <p>화이트 베이스에 우드 포인트로 고급스럽고 편안한 무드 완성.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section class="section soft" id="portfolio">
    <div class="container">
      <h2>시공 사례</h2>
      <p class="lead">사진은 “밝은 톤 + 우드 포인트 + 정돈된 라인” 위주로 구성하세요.</p>

      <div class="gallery">
        <div class="gal-big" style="background-image:url('https://images.unsplash.com/photo-1502005097973-6a7082348e28?auto=format&fit=crop&w=1400&q=80');">
          <div class="label"><b>거실 리모델링</b> · 화이트 + 우드</div>
        </div>
        <div class="gal-col">
          <div class="gal-small" style="background-image:url('https://images.unsplash.com/photo-1524758631624-e2822e304c36?auto=format&fit=crop&w=1400&q=80');">
            <div class="label"><b>주방</b> · 동선 개선</div>
          </div>
          <div class="gal-small" style="background-image:url('https://images.unsplash.com/photo-1484154218962-a197022b5858?auto=format&fit=crop&w=1400&q=80');">
            <div class="label"><b>상업공간</b> · 브랜딩</div>
          </div>
        </div>
      </div>

      <p class="note">※ 실제 시공 사진으로 교체하면 전환율이 크게 올라갑니다. (Before/After 2세트 추천)</p>
    </div>
  </section>

  <!-- Process -->
  <section class="section" id="process">
    <div class="container">
      <h2>진행 절차</h2>
      <p class="lead">복잡하지 않게, 고객이 “안심”하도록 단계가 보이게 구성합니다.</p>

      <div class="steps">
        <div class="step">
          <div class="n">1</div>
          <h4>상담 신청</h4>
          <p>기본 정보·공간 유형 확인</p>
        </div>
        <div class="step">
          <div class="n">2</div>
          <h4>현장 확인</h4>
          <p>실측/요구사항 정리</p>
        </div>
        <div class="step">
          <div class="n">3</div>
          <h4>견적 & 제안</h4>
          <p>자재·공정·기간 안내</p>
        </div>
        <div class="step">
          <div class="n">4</div>
          <h4>시공 진행</h4>
          <p>일정 공유·품질 관리</p>
        </div>
        <div class="step">
          <div class="n">5</div>
          <h4>완공 & A/S</h4>
          <p>검수 후 사후관리</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="section soft" id="contact">
    <div class="container">
      <h2>무료 상담 신청</h2>
      <p class="lead">상담은 무료이며, 무리한 영업 없이 필요한 범위만 안내드립니다.</p>

      <div class="cta-wrap">
        <div class="cta-side">
          <h3>상담 신청하면 이런 걸 알려드려요</h3>
          <p>예산·공간·일정에 맞춘 현실적인 선택지를 제공합니다.</p>

          <div class="cta-points">
            <div class="point"><div class="check">✓</div><div><b>예상 견적 범위</b><div class="note">공정/자재 기준으로 설명</div></div></div>
            <div class="point"><div class="check">✓</div><div><b>기간 & 진행 방식</b><div class="note">리스크 줄이는 일정 구성</div></div></div>
            <div class="point"><div class="check">✓</div><div><b>모던·우드 스타일 제안</b><div class="note">사진 참고 + 방향성 정리</div></div></div>
          </div>
        </div>

        <!-- ✅ 상담 신청 폼 (Formspree 이메일 수신) -->
<form id="leadForm" method="POST" novalidate>
  <div class="row">
    <div>
      <label for="name">이름</label>
      <input id="name" name="name" placeholder="성함" required />
    </div>
    <div>
      <label for="phone">연락처</label>
      <input id="phone" name="phone" placeholder="010-0000-0000" required />
    </div>
  </div>

  <div class="row">
    <div>
      <label for="type">공간 유형</label>
      <select id="type" name="type" required>
        <option value="" selected disabled>선택</option>
        <option>아파트/주거</option>
        <option>주택</option>
        <option>상업공간(매장/사무실)</option>
        <option>부분 시공(주방/욕실/거실 등)</option>
      </select>
    </div>

    <div>
      <label for="budget">예산(선택)</label>
      <select id="budget" name="budget">
        <option value="" selected>선택</option>
        <option>300~800</option>
        <option>800~1500</option>
        <option>1500~3000</option>
        <option>3000 이상</option>
      </select>
    </div>
  </div>

  <label for="message">문의 내용</label>
  <textarea id="message" name="message" placeholder="원하는 스타일/범위/일정 등을 간단히 적어주세요." required></textarea>

  <!-- ✅ Formspree에서 Reply-to로 쓰기 좋은 이메일(선택) -->
  <label for="email">이메일(선택)</label>
  <input id="email" name="_replyto" type="email" placeholder="답장 받을 이메일 (선택)" />

  <!-- ✅ 제목/구분값(이건 숨김) -->
  <input type="hidden" name="_subject" value="[랜딩] 인테리어 상담신청 접수" />
  <input type="hidden" name="source" value="landingpage" />

  <div class="form-actions">
    <button class="btn btn-primary" type="submit">상담 신청하기</button>
    <a class="btn btn-ghost" href="tel:010-0000-0000">전화 상담</a>
  </div>

  <p class="note" id="formNote">* 제출 시 개인정보 수집·이용에 동의한 것으로 간주됩니다.</p>
</form>

<script>
  // ✅ 1) 여기만 네 Formspree Endpoint로 바꾸면 끝
  const FORM_ENDPOINT = "https://formspree.io/f/meeewyek"; // <-- 교체!

  const form = document.getElementById("leadForm");
  const note = document.getElementById("formNote");

  // 간단 유효성 검사
  function validate(payload){
    if(!payload.name || payload.name.trim().length < 2) return "이름을 2자 이상 입력해주세요.";
    if(!payload.phone || payload.phone.trim().length < 9) return "연락처를 정확히 입력해주세요.";
    if(!payload.type) return "공간 유형을 선택해주세요.";
    if(!payload.message || payload.message.trim().length < 5) return "문의 내용을 5자 이상 입력해주세요.";
    return "";
  }

  form.addEventListener("submit", async (e) => {
    e.preventDefault();

    const fd = new FormData(form);
    const payload = Object.fromEntries(fd.entries());

    const err = validate(payload);
    if (err) {
      note.textContent = "⚠️ " + err;
      return;
    }

    try {
      note.textContent = "전송 중입니다...";
      const res = await fetch(FORM_ENDPOINT, {
        method: "POST",
        headers: { "Accept": "application/json" },
        body: fd
      });

      if (res.ok) {
        note.textContent = "✅ 접수 완료! 곧 연락드리겠습니다.";
        form.reset();
      } else {
        // Formspree가 JSON 에러를 줄 때가 있어 파싱 시도
        let msg = "⚠️ 전송 실패. 잠시 후 다시 시도해주세요.";
        try {
          const data = await res.json();
          if (data && data.errors && data.errors.length) {
            msg = "⚠️ " + data.errors.map(e => e.message).join(" / ");
          }
        } catch(_) {}
        note.textContent = msg;
      }
    } catch (error) {
      note.textContent = "⚠️ 네트워크 오류입니다. 잠시 후 다시 시도해주세요.";
    }
  });
</script>


  <footer>
    <div class="container" style="display:flex;gap:14px;flex-wrap:wrap;justify-content:space-between;align-items:flex-start">
      <div>
        <b style="color:var(--ink)">도담 인테리어</b><br/>
        사업자 정보 : 인테리어 · 주소 : 대구 칠곡 지점 · 대표자 : 김진
      </div>
      <div style="text-align:right">
        <div>상담: 010-3547-6532</div>
        <div>운영시간: 평일 10:00 - 20:00 /문의 24시 가능</div>
      </div>
    </div>
  </footer>

  <!-- Mobile Sticky CTA -->
  <div class="sticky-mobile">
    <div class="inner">
      <div class="txt">빠른 상담이 필요하신가요?</div>
      <div style="display:flex;gap:10px">
        <a class="btn btn-ghost" href="tel:010-0000-0000" style="padding:10px 12px">전화</a>
        <a class="btn btn-primary" href="#contact" style="padding:10px 12px">상담신청</a>
      </div>
    </div>
  </div>
  
</body>
</html>
