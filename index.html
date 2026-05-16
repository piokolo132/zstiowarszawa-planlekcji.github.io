<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>Plan lekcji — ZSTIO nr 2 Im. Adama Mickiewicza w Warszawie (z Office)</title>
<meta name="viewport" content="width=device-width,initial-scale=1">
<style>
  * { box-sizing: border-box; }
  body { margin: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; background: #fafafa; color: #1f2937; }
  .topbar { display: none; position: sticky; top: 0; z-index: 60; background: #1e40af; color: #fff; padding: 10px 14px; align-items: center; gap: 12px; }
  .hamburger { background: transparent; border: 2px solid #fff; color: #fff; width: 40px; height: 40px; font-size: 20px; cursor: pointer; display: flex; align-items: center; justify-content: center; }
  .topbar-title { font-weight: 700; font-size: 15px; }
  .scrim { display: none; position: fixed; inset: 0; background: rgba(0,0,0,.5); z-index: 70; }
  .scrim.open { display: block; }
  .layout { display: flex; min-height: 100vh; }
  .sidebar { width: 260px; background: #ffffff; border-right: 1px solid #e5e7eb; padding: 16px; position: sticky; top: 0; height: 100vh; overflow-y: auto; }
  .sidebar-head { font-size: 14px; padding-bottom: 12px; border-bottom: 1px solid #e5e7eb; margin-bottom: 12px; color: #1e40af; }
  .cat { margin-bottom: 8px; }
  .cat-toggle { width: 100%; text-align: left; background: transparent; border: none; padding: 8px 4px; font-weight: 700; font-size: 14px; cursor: pointer; color: #111827; display: flex; justify-content: space-between; align-items: center; }
  .cat-toggle:hover { background: #f3f4f6; }
  .caret { transition: transform .2s; }
  .cat.collapsed .caret { transform: rotate(-90deg); }
  .cat.collapsed .cat-list { display: none; }
  .cat-list { list-style: none; padding: 0 0 0 12px; margin: 0 0 8px 0; }
  .cat-list li { padding: 4px 0; }
  .cat-list a { color: #2563eb; text-decoration: none; font-size: 13px; display: block; padding: 4px 8px; }
  .cat-list a:hover { background: #eff6ff; }
  .main { flex: 1; padding: 24px 32px; min-width: 0; }
  .plan-section { display: none; max-width: 1100px; margin: 0 auto 32px; }
  .plan-section.active { display: block; }
  .plan-title { font-size: 22px; margin: 0 0 16px; color: #1e40af; }
  .table-wrap { background: white; overflow: auto; box-shadow: 0 1px 3px rgba(0,0,0,.08); }
  .plan-table { width: 100%; border-collapse: collapse; }
  .plan-table th, .plan-table td { border: 1px solid #e5e7eb; padding: 6px; text-align: center; vertical-align: top; }
  .plan-table th { font-weight: 600; font-size: 13px; padding: 10px 6px; }
  .hour-col { width: 80px; }
  .hour { font-weight: 700; background: #f9fafb; color: #374151; width: 80px; min-width: 80px; line-height: 1.2; }
  .hour-num { font-size: 16px; font-weight: 800; color: #1e40af; }
  .hour-time { font-size: 11px; font-weight: 600; color: #6b7280; margin-top: 2px; }
  .cell { min-height: 60px; padding: 4px !important; }
  .cell.empty { background: #fafafa; }
  .lesson { padding: 6px 8px; margin: 2px 0; text-align: left; font-size: 12px; color: #ffffff; }
  .subj { font-weight: 700; font-size: 13px; color: #ffffff; margin-bottom: 2px; }
  .meta { color: #ffffff; font-size: 11px; opacity: .95; }
  .meta .sep { margin: 0 4px; color: #ffffff; opacity: .7; }
  .link { color: #ffffff; text-decoration: underline; padding: 1px 3px; cursor: pointer; }
  .link:hover { background: rgba(255,255,255,.2); color: #ffffff; }
  .below { display: flex; justify-content: space-between; align-items: flex-start; margin-top: 16px; padding: 0 4px; flex-wrap: wrap; gap: 8px; }
  .below .right { text-align: right; font-size: 13px; color: #374151; }
  .below .muted { color: #6b7280; font-size: 12px; margin-top: 2px; }
  .btn-print { background: #1e40af; color: white; border: none; padding: 8px 16px; font-size: 14px; cursor: pointer; }
  .btn-print:hover { background: #1e3a8a; }
  .footer-logo { text-align: center; padding: 24px; opacity: .7; }
  .empty-state { text-align: center; padding: 80px 20px; color: #6b7280; }
  .empty-state h2 { color: #1e40af; }

  @media (max-width: 900px) {
    .topbar { display: flex; }
    .layout { display: block; }
    .sidebar { position: fixed; top: 0; left: 0; height: 100vh; z-index: 80; transform: translateX(-100%); transition: transform .25s ease; box-shadow: 2px 0 12px rgba(0,0,0,.15); }
    .sidebar.open { transform: translateX(0); }
    .main { padding: 16px; }
    .plan-title { font-size: 18px; }
    .plan-table th, .plan-table td { padding: 4px; font-size: 11px; }
    .hour-col, .hour { width: 60px; min-width: 60px; }
    .hour-num { font-size: 14px; }
    .hour-time { font-size: 10px; }
    .subj { font-size: 12px; }
    .meta { font-size: 10px; }
  }

  @media print {
    .topbar, .scrim { display: none !important; }
    .sidebar { display: none; }
    .btn-print { display: none; }
    .below .left { display: none; }
    .footer-logo { display: none; }
    .main { padding: 0; }
    .plan-section { display: none !important; max-width: 100%; }
    .plan-section.active { display: block !important; page-break-after: auto; }
    .empty-state { display: none !important; }
    body { background: white; }
  }
</style>
</head>
<body>
<div class="topbar">
  <button class="hamburger" id="hamburger" aria-label="Menu">☰</button>
  <div class="topbar-title">ZSTIO nr 2 Im. Adama Mickiewicza w Warszawie (z Office)</div>
</div>
<div class="scrim" id="scrim"></div>
<div class="layout">
  
      <aside class="sidebar" id="sidebar">
        <div class="sidebar-head">
          <strong>ZSTIO nr 2 Im. Adama Mickiewicza w Warszawie (z Office)</strong>
        </div>
        <div class="cat">
          <button class="cat-toggle" data-toggle="cat-classes">Klasy <span class="caret">▾</span></button>
          <ul class="cat-list" id="cat-classes">
            <li><a href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" style="color:#84cc16;font-weight:600;">1A</a></li><li><a href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" style="color:#eab308;font-weight:600;">1TK</a></li><li><a href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" style="color:#ef4444;font-weight:600;">7A</a></li><li><a href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" style="color:#f97316;font-weight:600;">8A</a></li><li><a href="#class-bfea6675-2530-44ea-bf87-d089823ad228" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" style="color:#f59e0b;font-weight:600;">8B</a></li>
          </ul>
        </div>
        <div class="cat">
          <button class="cat-toggle" data-toggle="cat-teachers">Nauczyciele <span class="caret">▾</span></button>
          <ul class="cat-list" id="cat-teachers">
            <li><a href="#teacher-c28e1df2-4a01-4a2e-83ae-2631ea0c4faa" data-jump="teacher-c28e1df2-4a01-4a2e-83ae-2631ea0c4faa">Aleksandra  Fabiańczyk</a></li><li><a href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></li><li><a href="#teacher-7c17e2ca-37cc-40d0-9e48-3a04c1758b2e" data-jump="teacher-7c17e2ca-37cc-40d0-9e48-3a04c1758b2e">Jarosław Lewandowski</a></li><li><a href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></li><li><a href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></li><li><a href="#teacher-47b42dff-1661-4fc6-844b-72b3f769eb62" data-jump="teacher-47b42dff-1661-4fc6-844b-72b3f769eb62">Kacper Czarniecki</a></li><li><a href="#teacher-3ed40624-f4ad-46d2-a4a7-de558840fc3f" data-jump="teacher-3ed40624-f4ad-46d2-a4a7-de558840fc3f">Kacper Kos</a></li><li><a href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></li><li><a href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a></li><li><a href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></li><li><a href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></li><li><a href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></li><li><a href="#teacher-f8880558-8539-40b1-94a2-481b884b95a0" data-jump="teacher-f8880558-8539-40b1-94a2-481b884b95a0">Mariusz kowalczyk</a></li><li><a href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></li><li><a href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></li><li><a href="#teacher-78d68b1e-8a36-451e-8876-852bce0849eb" data-jump="teacher-78d68b1e-8a36-451e-8876-852bce0849eb">Piotr Gajewski</a></li><li><a href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></li><li><a href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a></li><li><a href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a></li>
          </ul>
        </div>
        <div class="cat">
          <button class="cat-toggle" data-toggle="cat-rooms">Sale <span class="caret">▾</span></button>
          <ul class="cat-list" id="cat-rooms">
            <li><a href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></li><li><a href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></li><li><a href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></li><li><a href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></li><li><a href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></li><li><a href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></li><li><a href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></li><li><a href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></li><li><a href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></li><li><a href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></li><li><a href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></li><li><a href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></li><li><a href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></li>
          </ul>
        </div>
      </aside>
    
  <main class="main" id="main">
    <div class="empty-state" id="empty-state">
      <h2>Wybierz plan z menu po lewej</h2>
      <p>Kliknij oddział, nauczyciela lub salę, aby wyświetlić plan.</p>
    </div>
    <section class="plan-section" id="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" data-section>
        <h2 class="plan-title">Plan oddziału — 1A</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#84cc16;color:white;">Lekcja</th>
          <th style="background:#84cc16;color:white;">Poniedziałek</th><th style="background:#84cc16;color:white;">Wtorek</th><th style="background:#84cc16;color:white;">Środa</th><th style="background:#84cc16;color:white;">Czwartek</th><th style="background:#84cc16;color:white;">Piątek</th><th style="background:#84cc16;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" data-section>
        <h2 class="plan-title">Plan oddziału — 1TK</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#eab308;color:white;">Lekcja</th>
          <th style="background:#eab308;color:white;">Poniedziałek</th><th style="background:#eab308;color:white;">Wtorek</th><th style="background:#eab308;color:white;">Środa</th><th style="background:#eab308;color:white;">Czwartek</th><th style="background:#eab308;color:white;">Piątek</th><th style="background:#eab308;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell"><div class="lesson" style="background:#fb7185;color:#ffffff;">
          <div class="subj">Bezpieczeństwo i higiena pracy</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f43f5e;color:#ffffff;">
          <div class="subj">Infrastruktura kolejowa</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#d946ef;color:#ffffff;">
          <div class="subj">Podstawy ruchu kolejowego</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell"><div class="lesson" style="background:#ec4899;color:#ffffff;">
          <div class="subj">Urządzenia sterowania ruchem kolejowym</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f43f5e;color:#ffffff;">
          <div class="subj">Infrastruktura kolejowa</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#d946ef;color:#ffffff;">
          <div class="subj">Podstawy ruchu kolejowego</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ec4899;color:#ffffff;">
          <div class="subj">Urządzenia sterowania ruchem kolejowym</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" data-section>
        <h2 class="plan-title">Plan oddziału — 7A</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#ef4444;color:white;">Lekcja</th>
          <th style="background:#ef4444;color:white;">Poniedziałek</th><th style="background:#ef4444;color:white;">Wtorek</th><th style="background:#ef4444;color:white;">Środa</th><th style="background:#ef4444;color:white;">Czwartek</th><th style="background:#ef4444;color:white;">Piątek</th><th style="background:#ef4444;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#06b6d4;color:#ffffff;">
          <div class="subj">Muzyka</div>
          <div class="meta"><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" data-section>
        <h2 class="plan-title">Plan oddziału — 8A</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#f97316;color:white;">Lekcja</th>
          <th style="background:#f97316;color:white;">Poniedziałek</th><th style="background:#f97316;color:white;">Wtorek</th><th style="background:#f97316;color:white;">Środa</th><th style="background:#f97316;color:white;">Czwartek</th><th style="background:#f97316;color:white;">Piątek</th><th style="background:#f97316;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - pol</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - mat</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#8b5cf6;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - ang</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="class-bfea6675-2530-44ea-bf87-d089823ad228" data-section>
        <h2 class="plan-title">Plan oddziału — 8B</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#f59e0b;color:white;">Lekcja</th>
          <th style="background:#f59e0b;color:white;">Poniedziałek</th><th style="background:#f59e0b;color:white;">Wtorek</th><th style="background:#f59e0b;color:white;">Środa</th><th style="background:#f59e0b;color:white;">Czwartek</th><th style="background:#f59e0b;color:white;">Piątek</th><th style="background:#f59e0b;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - mat</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - pol</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#8b5cf6;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - ang</div>
          <div class="meta"><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-c28e1df2-4a01-4a2e-83ae-2631ea0c4faa" data-section>
        <h2 class="plan-title">Plan nauczyciela — Aleksandra  Fabiańczyk</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" data-section>
        <h2 class="plan-title">Plan nauczyciela — Bartłomiej Downar</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-7c17e2ca-37cc-40d0-9e48-3a04c1758b2e" data-section>
        <h2 class="plan-title">Plan nauczyciela — Jarosław Lewandowski</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" data-section>
        <h2 class="plan-title">Plan nauczyciela — Jarosław Lewandowski</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#8b5cf6;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - ang</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#8b5cf6;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - ang</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" href="#room-5d68a9ad-5455-4a71-885c-ab722d9dacd7">101</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" data-section>
        <h2 class="plan-title">Plan nauczyciela — Kacper  Czarniecki</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" href="#room-b0e872ce-51dd-4942-a8fe-1f1252e7e381">102</a></div>
        </div></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-47b42dff-1661-4fc6-844b-72b3f769eb62" data-section>
        <h2 class="plan-title">Plan nauczyciela — Kacper Czarniecki</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-3ed40624-f4ad-46d2-a4a7-de558840fc3f" data-section>
        <h2 class="plan-title">Plan nauczyciela — Kacper Kos</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" data-section>
        <h2 class="plan-title">Plan nauczyciela — Kacper Kos</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - pol</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - pol</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" href="#room-37d573d4-1dfe-4a97-abe1-07a659f9763a">105</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" data-section>
        <h2 class="plan-title">Plan nauczyciela — Karol  Bielicki</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#06b6d4;color:#ffffff;">
          <div class="subj">Muzyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-bd1e9c3c-3706-4099-87aa-06b438a91338" href="#room-bd1e9c3c-3706-4099-87aa-06b438a91338">9</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" data-section>
        <h2 class="plan-title">Plan nauczyciela — Krzysztof  Balcerzak</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" href="#room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3">106</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" data-section>
        <h2 class="plan-title">Plan nauczyciela — Ksawery Bogusiewicz</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" href="#room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4">109</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" data-section>
        <h2 class="plan-title">Plan nauczyciela — Mariusz  Kowalczyk</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - mat</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - mat</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" href="#room-8483f1ca-b799-47a9-9f84-561385ff7cc6">108</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-f8880558-8539-40b1-94a2-481b884b95a0" data-section>
        <h2 class="plan-title">Plan nauczyciela — Mariusz kowalczyk</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" data-section>
        <h2 class="plan-title">Plan nauczyciela — Mateusz Grygiel</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" data-section>
        <h2 class="plan-title">Plan nauczyciela — Piotr  Gajewski</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell"><div class="lesson" style="background:#fb7185;color:#ffffff;">
          <div class="subj">Bezpieczeństwo i higiena pracy</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f43f5e;color:#ffffff;">
          <div class="subj">Infrastruktura kolejowa</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#d946ef;color:#ffffff;">
          <div class="subj">Podstawy ruchu kolejowego</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell"><div class="lesson" style="background:#ec4899;color:#ffffff;">
          <div class="subj">Urządzenia sterowania ruchem kolejowym</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f43f5e;color:#ffffff;">
          <div class="subj">Infrastruktura kolejowa</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#d946ef;color:#ffffff;">
          <div class="subj">Podstawy ruchu kolejowego</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ec4899;color:#ffffff;">
          <div class="subj">Urządzenia sterowania ruchem kolejowym</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" href="#room-b249f52c-f015-4c06-8e68-1a1e40442ccb">10</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" href="#room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd">11</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-78d68b1e-8a36-451e-8876-852bce0849eb" data-section>
        <h2 class="plan-title">Plan nauczyciela — Piotr Gajewski</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" data-section>
        <h2 class="plan-title">Plan nauczyciela — Wakat Niemiecki</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" href="#room-04b0e970-aeba-4ab9-951b-338998f4d4bc">110</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" data-section>
        <h2 class="plan-title">Plan nauczyciela — Wakat Zdrowotna</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" href="#room-124f66c8-b5dc-4691-adb9-ff66ee7a514a">104</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" href="#room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a">103</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" data-section>
        <h2 class="plan-title">Plan nauczyciela — Wojciech  Dąbrowski</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#0ea5e9;color:white;">Lekcja</th>
          <th style="background:#0ea5e9;color:white;">Poniedziałek</th><th style="background:#0ea5e9;color:white;">Wtorek</th><th style="background:#0ea5e9;color:white;">Środa</th><th style="background:#0ea5e9;color:white;">Czwartek</th><th style="background:#0ea5e9;color:white;">Piątek</th><th style="background:#0ea5e9;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" href="#room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a">107</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-b249f52c-f015-4c06-8e68-1a1e40442ccb" data-section>
        <h2 class="plan-title">Plan sali — 10</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-5d68a9ad-5455-4a71-885c-ab722d9dacd7" data-section>
        <h2 class="plan-title">Plan sali — 101</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#8b5cf6;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - ang</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#8b5cf6;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - ang</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f59e0b;color:#ffffff;">
          <div class="subj">Język angielski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0" href="#teacher-caadcac3-e9e0-4469-8a2f-8bff3977def0">Jarosław Lewandowski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-b0e872ce-51dd-4942-a8fe-1f1252e7e381" data-section>
        <h2 class="plan-title">Plan sali — 102</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#be185d;color:#ffffff;">
          <div class="subj">Chemia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c" href="#teacher-e475a04f-2a52-4eda-b2a7-4520b5b9b85c">Kacper  Czarniecki</a></div>
        </div></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-d428f5d5-7118-43d2-a1bd-cfae77a8ce2a" data-section>
        <h2 class="plan-title">Plan sali — 103</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-124f66c8-b5dc-4691-adb9-ff66ee7a514a" data-section>
        <h2 class="plan-title">Plan sali — 104</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja zdrowotna</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-cdfd4099-5358-4821-b834-766f2c564b8a" href="#teacher-cdfd4099-5358-4821-b834-766f2c564b8a">Wakat Zdrowotna</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Geografia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#84cc16;color:#ffffff;">
          <div class="subj">Biologia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#b91c1c;color:#ffffff;">
          <div class="subj">Edukacja dla bezpieczeństwa</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-37d573d4-1dfe-4a97-abe1-07a659f9763a" data-section>
        <h2 class="plan-title">Plan sali — 105</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - pol</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - pol</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f97316;color:#ffffff;">
          <div class="subj">Język polski</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-b0447c6a-c5a8-47b6-a80f-2aa15e0c74a3" data-section>
        <h2 class="plan-title">Plan sali — 106</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#c2410c;color:#ffffff;">
          <div class="subj">Religia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-347a6c9b-e52d-4259-b55b-c62e56228c19" href="#teacher-347a6c9b-e52d-4259-b55b-c62e56228c19">Kacper Kos</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#22c55e;color:#ffffff;">
          <div class="subj">Historia</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-59fe0792-aef7-46e2-8b03-2ffff0850088" href="#teacher-59fe0792-aef7-46e2-8b03-2ffff0850088">Krzysztof  Balcerzak</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-5a1a854f-3267-4e2d-8991-294ac5ed1e0a" data-section>
        <h2 class="plan-title">Plan sali — 107</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#b45309;color:#ffffff;">
          <div class="subj">Wiedza o społeczeństwie</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7" href="#teacher-87eca136-fc91-4101-b5ec-e67f4805e0c7">Wojciech  Dąbrowski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#3b82f6;color:#ffffff;">
          <div class="subj">Biznes i zarządzanie</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#9f1239;color:#ffffff;">
          <div class="subj">Fizyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507" href="#teacher-0a7c844e-d3a8-45ac-95f2-5cb3b9401507">Bartłomiej Downar</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-8483f1ca-b799-47a9-9f84-561385ff7cc6" data-section>
        <h2 class="plan-title">Plan sali — 108</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - mat</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#6366f1;color:#ffffff;">
          <div class="subj">Przygotowujące do E8 - mat</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#ef4444;color:#ffffff;">
          <div class="subj">Matematyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7" href="#teacher-11676ccf-9f40-45a8-81c7-e2c5b699c2e7">Mariusz  Kowalczyk</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-7fdaa4f3-89f2-4af5-b448-c0ed2c1823c4" data-section>
        <h2 class="plan-title">Plan sali — 109</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#10b981;color:#ffffff;">
          <div class="subj">Informatyka</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-84222ad6-4cf0-4415-87a9-e5004d992650" href="#teacher-84222ad6-4cf0-4415-87a9-e5004d992650">Ksawery Bogusiewicz</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-05703ae6-1bd6-4e78-b4bc-7956b974b4cd" data-section>
        <h2 class="plan-title">Plan sali — 11</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell"><div class="lesson" style="background:#fb7185;color:#ffffff;">
          <div class="subj">Bezpieczeństwo i higiena pracy</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#f43f5e;color:#ffffff;">
          <div class="subj">Infrastruktura kolejowa</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#d946ef;color:#ffffff;">
          <div class="subj">Podstawy ruchu kolejowego</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell"><div class="lesson" style="background:#ec4899;color:#ffffff;">
          <div class="subj">Urządzenia sterowania ruchem kolejowym</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#f43f5e;color:#ffffff;">
          <div class="subj">Infrastruktura kolejowa</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#d946ef;color:#ffffff;">
          <div class="subj">Podstawy ruchu kolejowego</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#ec4899;color:#ffffff;">
          <div class="subj">Urządzenia sterowania ruchem kolejowym</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a855f7;color:#ffffff;">
          <div class="subj">Organizacja przewozów kolejowych</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#0ea5e9;color:#ffffff;">
          <div class="subj">Zajęcia z wychowawcą</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-e899b3f8-f752-4efd-a0ed-762558328b10" href="#teacher-e899b3f8-f752-4efd-a0ed-762558328b10">Piotr  Gajewski</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-04b0e970-aeba-4ab9-951b-338998f4d4bc" data-section>
        <h2 class="plan-title">Plan sali — 110</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#a16207;color:#ffffff;">
          <div class="subj">Język rosyjski</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d" href="#teacher-7069c6a6-554c-4113-83dc-5aa8c824a27d">Mateusz Grygiel</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f" href="#class-eaa25f26-a7b6-41c9-a6cc-aa31d0db806f">8A</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-bfea6675-2530-44ea-bf87-d089823ad228" href="#class-bfea6675-2530-44ea-bf87-d089823ad228">8B</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#eab308;color:#ffffff;">
          <div class="subj">Język niemiecki</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-808f6a89-3d6b-4f1c-9f42-803584facbad" href="#teacher-808f6a89-3d6b-4f1c-9f42-803584facbad">Wakat Niemiecki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
<section class="plan-section" id="room-bd1e9c3c-3706-4099-87aa-06b438a91338" data-section>
        <h2 class="plan-title">Plan sali — 9</h2>
        <div class="table-wrap">
          <table class="plan-table"><thead>
        <tr>
          <th class="hour-col" style="background:#10b981;color:white;">Lekcja</th>
          <th style="background:#10b981;color:white;">Poniedziałek</th><th style="background:#10b981;color:white;">Wtorek</th><th style="background:#10b981;color:white;">Środa</th><th style="background:#10b981;color:white;">Czwartek</th><th style="background:#10b981;color:white;">Piątek</th><th style="background:#10b981;color:white;">Sobota</th>
        </tr>
      </thead><tbody>
        <tr>
            <td class="hour"><div class="hour-num">1</div><div class="hour-time">17:00<br>17:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">2</div><div class="hour-time">17:30<br>17:55</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">3</div><div class="hour-time">18:00<br>18:25</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">4</div><div class="hour-time">18:40<br>19:05</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">5</div><div class="hour-time">19:15<br>19:40</div></td>
            <td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="class-feeed740-6ca0-4989-ad2b-9f2eafaad257" href="#class-feeed740-6ca0-4989-ad2b-9f2eafaad257">1TK</a><span class="sep">·</span><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a></div>
        </div></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547" href="#class-87c90f0e-24b2-434d-9e7b-ecbe3fc15547">1A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a></div>
        </div></td><td class="cell"><div class="lesson" style="background:#14b8a6;color:#ffffff;">
          <div class="subj">Plastyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">6</div><div class="hour-time">19:50<br>20:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell"><div class="lesson" style="background:#06b6d4;color:#ffffff;">
          <div class="subj">Muzyka</div>
          <div class="meta"><a class="link" data-jump="class-3c863b0e-9764-4873-af41-db7d79a1f4c0" href="#class-3c863b0e-9764-4873-af41-db7d79a1f4c0">7A</a><span class="sep">·</span><a class="link" data-jump="teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822" href="#teacher-0a1c30e9-22a7-423a-a922-ef64a6b90822">Karol  Bielicki</a></div>
        </div></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">7</div><div class="hour-time">20:20<br>20:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">8</div><div class="hour-time">20:50<br>21:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">9</div><div class="hour-time">21:20<br>21:45</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">10</div><div class="hour-time">21:50<br>22:15</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr><tr>
            <td class="hour"><div class="hour-num">11</div><div class="hour-time">22:17<br>22:42</div></td>
            <td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td><td class="cell empty"></td>
          </tr>
      </tbody></table>
        </div>
        <div class="below">
          <div class="left">
            <button class="btn-print" onclick="window.print()">🖨️ Wydrukuj plan</button>
          </div>
          <div class="right">
            <div>Wygenerowano: <strong>16 maja 2026 o 18:15</strong></div>
            <div class="muted">za pomocą programu VENUS PLAN</div>
          </div>
        </div>
      </section>
  </main>
</div>
<script>
  // Toggle kategorii
  document.querySelectorAll('.cat-toggle').forEach(btn => {
    btn.addEventListener('click', () => {
      btn.parentElement.classList.toggle('collapsed');
    });
  });
  // Pokaż wybraną sekcję
  function showSection(id) {
    document.querySelectorAll('[data-section]').forEach(s => s.classList.remove('active'));
    var emp = document.getElementById('empty-state');
    var target = document.getElementById(id);
    if (target) {
      target.classList.add('active');
      if (emp) emp.style.display = 'none';
    } else if (emp) {
      emp.style.display = 'block';
    }
  }
  // Hamburger / sidebar mobilny
  var sidebarEl = document.getElementById('sidebar');
  var scrimEl = document.getElementById('scrim');
  var hamb = document.getElementById('hamburger');
  function closeSidebar() { if (sidebarEl) sidebarEl.classList.remove('open'); if (scrimEl) scrimEl.classList.remove('open'); }
  function openSidebar() { if (sidebarEl) sidebarEl.classList.add('open'); if (scrimEl) scrimEl.classList.add('open'); }
  if (hamb) hamb.addEventListener('click', openSidebar);
  if (scrimEl) scrimEl.addEventListener('click', closeSidebar);

  document.querySelectorAll('[data-jump]').forEach(a => {
    a.addEventListener('click', e => {
      e.preventDefault();
      const id = a.getAttribute('data-jump');
      showSection(id);
      closeSidebar();
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  });
  // Pokaż pierwszą klasę domyślnie jeśli jest
  var first = document.querySelector('[data-section]');
  if (first) {
    showSection(first.id);
    var emp = document.getElementById('empty-state');
    if (emp) emp.style.display = 'none';
  }
</script>
</body>
</html>
