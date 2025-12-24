<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GBeauty｜開運眉眼唇 預約</title>

  <style>
    :root{
      --bg:#faf7f2;
      --card:#ffffff;
      --text:#1f2937;
      --muted:#6b7280;
      --line:#e5e7eb;
      --brand:#111827;     /* 黑 */
      --brand2:#b45309;    /* 暖金棕 */
      --btn:#111827;
      --btnText:#ffffff;
      --shadow: 0 12px 30px rgba(0,0,0,.08);
      --radius: 18px;
      --max: 980px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Noto Sans TC", "PingFang TC", "Microsoft JhengHei", Arial, sans-serif;
      background: radial-gradient(1200px 600px at 20% 0%, #fff 0%, var(--bg) 60%) , var(--bg);
      color:var(--text);
      line-height:1.6;
    }
    a{color:inherit; text-decoration:none}
    .wrap{
      max-width:var(--max);
      margin:0 auto;
      padding:28px 16px 56px;
    }
    .topbar{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:12px;
      margin-bottom:18px;
    }
    .logo{
      display:flex;
      align-items:center;
      gap:10px;
      font-weight:800;
      letter-spacing:.2px;
      color:var(--brand);
    }
    .badge{
      font-size:12px;
      padding:4px 10px;
      border:1px solid var(--line);
      border-radius:999px;
      color:var(--muted);
      background:rgba(255,255,255,.6);
    }
    .hero{
      background:linear-gradient(180deg, rgba(255,255,255,.92), rgba(255,255,255,.78));
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      border-radius:var(--radius);
      padding:22px 18px;
      margin-bottom:18px;
    }
    .title{
      font-size:26px;
      margin:0 0 6px;
      color:var(--brand);
      letter-spacing:.3px;
    }
    .subtitle{
      margin:0 0 14px;
      color:var(--muted);
      font-size:14px;
    }
    .quote{
      border-left:5px solid var(--brand2);
      padding:12px 14px;
      margin:14px 0 16px;
      background:#fff;
      border-radius:12px;
    }
    .quote p{margin:0}
    .quote p + p{margin-top:8px}
    .actions{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      margin-top:12px;
    }
    .btn{
      display:inline-flex;
      align-items:center;
      justify-content:center;
      padding:11px 14px;
      border-radius:12px;
      border:1px solid transparent;
      font-weight:700;
      cursor:pointer;
      transition:.15s ease;
      user-select:none;
    }
    .btn.primary{
      background:var(--btn);
      color:var(--btnText);
    }
    .btn.primary:hover{transform:translateY(-1px); filter:brightness(1.05)}
    .btn.ghost{
      background:transparent;
      border-color:var(--line);
      color:var(--brand);
    }
    .btn.ghost:hover{background:rgba(255,255,255,.7)}
    .section{
      margin-top:16px;
      background:var(--card);
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      border-radius:var(--radius);
      overflow:hidden;
    }
    .sectionHead{
      padding:16px 18px;
      border-bottom:1px solid var(--line);
      display:flex;
      align-items:flex-end;
      justify-content:space-between;
      gap:10px;
    }
    .sectionHead h2{
      margin:0;
      font-size:18px;
      color:var(--brand);
    }
    .sectionHead span{
      font-size:12px;
      color:var(--muted);
    }
    .iframeBox{
      padding:0;
      background:#fff;
    }
    iframe{
      width:100%;
      height:1450px; /* 可依表單長度調整 */
      border:0;
      display:block;
    }
    .footer{
      margin-top:16px;
      color:var(--muted);
      font-size:12px;
      text-align:center;
      padding:10px 0 0;
    }
    .smallNote{
      padding:12px 18px 18px;
      color:var(--muted);
      font-size:13px;
    }

    /* 手機微調 */
    @media (max-width:520px){
      .title{font-size:22px}
      iframe{height:1600px;}
    }
  </style>
</head>

<body>
  <div class="wrap">
    <div class="topbar">
      <div class="logo">
        <span style="font-size:20px;">GBeauty</span>
        <span class="badge">開運眉眼唇・預約</span>
      </div>

      <!-- 如果你有首頁 index.html，可改成 href="index.html" -->
      <a class="btn ghost" href="./">回到首頁</a>
    </div>

    <div class="hero">
      <h1 class="title">GBeauty｜開運眉眼唇 預約</h1>
      <p class="subtitle">✧ 遇見最美的自己｜我不做奇蹟，只做剛剛好的調整。</p>

      <div class="quote">
        <p>很多人不是運不好，只是狀態有點亂。</p>
        <p>當線條順了，人的選擇也會慢慢順起來。</p>
        <p>當狀態穩了，選擇自然比較順。</p>
      </div>

      <div class="actions">
        <a class="btn primary" href="#bookingForm">立即填寫預約</a>
        <!-- 若你想直接開新分頁填表（不嵌入），可用這個 -->
        <a class="btn ghost" target="_blank" rel="noopener"
           href="https://docs.google.com/forms/d/e/1FAIpQLSexG8VG9bjWXVa02-l4BEgf12KPSpTfLPB2JQHVYoFerM4uEw/viewform">
          直接開啟表單
        </a>
      </div>
    </div>

    <section id="bookingForm" class="section">
      <div class="sectionHead">
        <h2>預約表單</h2>
        <span>填寫完成後，我會以你留下的聯絡方式與你確認時段</span>
      </div>

      <div class="iframeBox">
        <iframe
          src="https://docs.google.com/forms/d/e/1FAIpQLSexG8VG9bjWXVa02-l4BEgf12KPSpTfLPB2JQHVYoFerM4uEw/viewform?embedded=true"
          marginheight="0"
          marginwidth="0">
          載入中…
        </iframe>
      </div>

      <div class="smallNote">
        小提醒：若你在 iPhone / LINE 內建瀏覽器看到表單顯示異常，請點上方「直接開啟表單」。
      </div>
    </section>

    <div class="footer">
      © <span id="y"></span> GBeauty｜開運眉眼唇｜預約系統
    </div>
  </div>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>

