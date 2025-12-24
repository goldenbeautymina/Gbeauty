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

    /* LOGO 區塊 */
    .brandWrap{
      display:flex;
      align-items:center;
      gap:14px;
    }
    .brandLogo{
      width:84px;
      height:84px;
      border-radius:50%;
      object-fit:cover;
      background:#fff;
      box-shadow:0 8px 20px rgba(0,0,0,.12);
      border:1px solid rgba(0,0,0,.06);
    }
    .brandText{
      line-height:1.2;
    }
    .brandText strong{
      font-size:20px;
      letter-spacing:.4px;
      color:var(--brand);
    }
    .brandText span{
      font-size:12px;
      color:var(--muted);
    }

    /* 固定品牌語（LOGO 下方） */
    .brandSlogan{
      margin-top:6px;
      font-size:13px;
      color:#4b5563;
      letter-spacing:.6px;
      font-weight:500;
    }
    .brandSlogan::before{ content:"「"; }
    .brandSlogan::after{ content:"」"; }

    /* 右上角按鈕 */
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
      white-space:nowrap;
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

    /* 內容卡片 */
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
    .smallNote{
      padding:12px 18px 18px;
      color:var(--muted);
      font-size:13px;
    }
    .footer{
      margin-top:16px;
      color:var(--muted);
      font-size:12px;
      text-align:center;
      padding:10px 0 0;
    }

    /* 手機微調 */
    @media (max-width:520px){
      .title{font-size:22px}
      iframe{height:1600px;}
      .brandLogo{width:72px; height:72px;}
    }

    @media (max-width:420px){
      .topbar{flex-direction:column; align-items:flex-start}
    }
  </style>
</head>

<body>
  <div class="wrap">

    <div class="topbar">
      <!-- 左上：LOGO + 品牌語 -->
      <div class="brandWrap">
        <!-- 重要：請把 LOGO 放到 repo 的 images/gbeauty-logo.jpg -->
        <img src="images/gbeauty-logo.jpg" alt="GBeauty 開運眉眼唇" class="brandLogo">

        <div class="brandText">
          <strong>GBeauty</strong><br>
          <span>開運眉眼唇 · 預約</span>
          <div class="brandSlogan">當臉的線條順了，人的選擇也會跟著順。</div>
        </div>
      </div>

      <!-- 右上：回首頁 -->
      <a class="btn ghost" href="./">回到首頁</a>
    </div>

    <!-- 主視覺卡 -->
    <div class="hero">
      <h1 class="title">開運眉眼唇｜預約表單</h1>
      <p class="subtitle">✧ 遇見最美的自己｜我不做奇蹟，只做剛剛好的調整。</p>

      <div class="quote">
        <p>很多人不是運不好，只是狀態有點亂。</p>
        <p>當線條順了，人的選擇也會慢慢順起來。</p>
        <p>當狀態穩了，選擇自然比較順。</p>
      </div>

      <div class="actions">
        <a class="btn primary" href="booking.html" target="_blank" rel="noopener">立即填寫預約</a>

        <!-- 如果嵌入在 LINE / iPhone 內建瀏覽器有問題，可用這個開新分頁 -->
        <a class="btn ghost" target="_blank" rel="noopener"
           href="https://docs.google.com/forms/d/e/1FAIpQLSexG8VG9bjWXVa02-l4BEgf12KPSpTfLPB2JQHVYoFerM4uEw/viewform">
          直接開啟表單
        </a>
      </div>
    </div>

    <!-- 表單區 -->
    <section id="booking.html" class="section">
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
