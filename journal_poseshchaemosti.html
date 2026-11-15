<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#f4f7fb">
<meta name="color-scheme" content="light">
<title>Журнал посещаемости — группа</title>
<style>
:root{
  --bg:#f4f7fb;--surface:#fff;--text:#182b46;--muted:#687990;--border:#e1e8f1;
  --primary:#2364d8;--primary-soft:#eaf1ff;--primary-dark:#154db0;
  --green:#157a53;--green-bg:#e6f6ed;--green-border:#b2dfc8;
  --orange:#9b5a16;--orange-bg:#fff3e5;--orange-border:#f1d2af;
  --purple:#6c45a1;--purple-bg:#f2edfb;--purple-border:#d7c4f1;
  --red:#a13b4a;--red-bg:#fff0f1;--red-border:#edc0c5;
  --shadow:0 6px 26px rgba(28,50,80,.045);
}
*{box-sizing:border-box}
html{-webkit-text-size-adjust:100%;scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--text);font:15px/1.45 system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif}
button,input,select{font:inherit}
button{-webkit-tap-highlight-color:transparent;cursor:pointer;touch-action:manipulation}
button:disabled{opacity:.55;cursor:not-allowed}
button:focus-visible,input:focus-visible,select:focus-visible{outline:3px solid #a8c7ff;outline-offset:2px}
[hidden]{display:none!important}
.container{max-width:1160px;margin:auto;padding:26px 24px 54px}
.topbar{display:flex;align-items:center;justify-content:space-between;gap:16px;margin-bottom:22px}
.topbar h1{font-size:clamp(25px,3vw,34px);line-height:1.12;letter-spacing:-.035em;margin:0 0 7px;font-weight:800}
.topbar p{color:var(--muted);margin:0;font-size:14px}
.pill{display:inline-flex;align-items:center;gap:7px;white-space:nowrap;background:var(--primary-soft);color:var(--primary-dark);border:1px solid #d8e5ff;border-radius:999px;padding:8px 13px;font-size:12px;font-weight:750}
.dot{display:inline-block;width:7px;height:7px;background:#1bbd79;border-radius:50%}
.panel{background:var(--surface);border:1px solid var(--border);border-radius:18px;box-shadow:var(--shadow)}
.control-panel{padding:20px}
.control-header{font-size:13px;font-weight:800;color:#354c6c;margin-bottom:13px}
.controls{display:grid;grid-template-columns:1.1fr 1.35fr .85fr auto;gap:13px;align-items:end}
.field{display:flex;flex-direction:column;gap:7px;min-width:0}
.field label{font-size:12px;font-weight:750;color:#5c6f87}
.field select,.field input{width:100%;height:48px;border:1px solid #cfd9e7;border-radius:11px;background:#fff;color:var(--text);padding:0 12px;min-width:0;font-size:16px;outline-offset:2px}
.btn{border:1px solid #d5e0ed;color:var(--text);border-radius:11px;background:#fff;padding:11px 14px;font-size:13px;font-weight:750;display:inline-flex;gap:8px;justify-content:center;align-items:center;min-height:46px;text-decoration:none;line-height:1.25}
.btn:hover{background:#f8fbff}
.btn.primary{background:var(--primary);border-color:var(--primary);color:white}
.btn.primary:hover{background:var(--primary-dark)}
.btn.danger{color:var(--red);border-color:#edcbd1}
.btn:active,.choice:active{transform:scale(.985)}
.summary{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:12px;margin:14px 0 21px}
.kpi{background:white;border:1px solid var(--border);border-radius:15px;padding:16px 18px;min-height:100px}
.kpi span{color:var(--muted);font-size:12px;font-weight:650;display:block;line-height:1.3}
.kpi strong{display:block;font-size:30px;line-height:1.1;margin-top:8px;font-variant-numeric:tabular-nums;letter-spacing:-.04em}
.kpi.total strong{color:var(--primary)}.kpi.sick strong{color:var(--orange)}.kpi.family strong{color:var(--purple)}.kpi.unknown strong{color:var(--red)}
.navigation{display:flex;gap:7px;margin-bottom:14px}
.nav-btn{border:1px solid var(--border);border-radius:12px;background:white;color:var(--muted);font-weight:750;padding:12px 18px;min-height:47px;display:inline-flex;align-items:center;gap:9px}
.nav-btn[aria-current="page"]{background:var(--primary);border-color:var(--primary);color:white}
.nav-icon{font-size:18px;line-height:1}
.view{display:none}.view.active{display:block}
.content-panel{padding:22px}
.section-head{display:flex;align-items:flex-start;justify-content:space-between;gap:14px;margin-bottom:17px}
.section-head h2{font-size:21px;letter-spacing:-.025em;line-height:1.25;margin:0 0 5px}
.subtle{font-size:13px;color:var(--muted);margin:0}
.state-chip{display:inline-flex;align-items:center;gap:5px;border-radius:9px;padding:7px 10px;border:1px solid #d7e8ff;background:#f0f6ff;color:#2459a4;font-weight:750;font-size:12px;white-space:nowrap}
.state-chip.unsaved{background:#fff8ec;color:#8e611e;border-color:#f4dfb6}
.filterbar{display:flex;align-items:center;gap:10px;margin-bottom:16px;flex-wrap:wrap}
.search{height:46px;flex:1 1 240px;min-width:0;border-radius:11px;padding:0 14px;border:1px solid #d5dfeb;background:#fff;font-size:16px}
.filter-switch{white-space:nowrap;display:inline-flex;align-items:center;gap:8px;color:#53677f;font-weight:700;font-size:13px;min-height:44px;cursor:pointer}
.filter-switch input{appearance:none;width:39px;height:23px;border-radius:999px;background:#ccd7e5;position:relative;margin:0;flex:none;transition:background .15s}
.filter-switch input:checked{background:var(--primary)}
.filter-switch input:before{content:"";position:absolute;left:3px;top:3px;width:17px;height:17px;border-radius:50%;background:white;box-shadow:0 1px 3px #0002;transition:transform .15s}
.filter-switch input:checked:before{transform:translateX(16px)}
.filter-switch input:focus-visible{outline:3px solid #a8c7ff;outline-offset:2px}
.countline{margin-bottom:12px;font-size:12px;color:#748399;font-weight:650}
.students{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px}
.student{border:1px solid var(--border);border-radius:14px;background:#fff;padding:15px;min-width:0;transition:border-color .15s,background .15s}
.student.is-absent{border-color:#eadadd;background:#fffdfd}
.student-top{display:flex;align-items:flex-start;gap:11px;margin-bottom:13px}
.number{display:flex;align-items:center;justify-content:center;border-radius:9px;color:#71849c;background:#f1f5fa;font-size:12px;font-weight:800;width:29px;height:29px;flex-shrink:0;font-variant-numeric:tabular-nums}
.name-wrap{min-width:0;flex:1}
.student-name{font-size:14px;line-height:1.35;font-weight:750;display:block;overflow-wrap:anywhere}
.student-status{font-size:11px;color:#7d8ca0;margin-top:4px;display:block;font-weight:650}
.student.is-absent .student-status{color:var(--red)}
.choice-set{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:6px}
.choice{border:1px solid #dbe4ee;border-radius:9px;min-width:0;min-height:44px;background:white;font-size:11px;padding:7px 3px;line-height:1.18;color:#53647c;font-weight:700;white-space:normal}
.choice[aria-pressed="true"]{font-weight:800;border-width:1.5px}
.choice.present[aria-pressed="true"]{background:var(--green-bg);border-color:var(--green-border);color:var(--green)}
.choice.sick[aria-pressed="true"]{background:var(--orange-bg);border-color:var(--orange-border);color:var(--orange)}
.choice.family[aria-pressed="true"]{background:var(--purple-bg);border-color:var(--purple-border);color:var(--purple)}
.choice.unknown[aria-pressed="true"]{background:var(--red-bg);border-color:var(--red-border);color:var(--red)}
.lesson-actions{display:flex;flex-wrap:wrap;gap:9px;margin-top:20px;padding-top:18px;border-top:1px solid var(--border)}
.save-line{color:var(--muted);font-size:12px;margin:14px 0 0;line-height:1.5}
.save-line.error{color:#b53543;font-weight:750}
.empty{padding:34px 16px;border-radius:12px;color:var(--muted);background:#f8faff;text-align:center;font-size:14px}
.report-overview{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:11px;margin-bottom:18px}
.overview-box{background:#f6f9fe;border:1px solid var(--border);padding:14px;border-radius:12px}
.overview-box small{display:block;color:var(--muted);font-size:12px}.overview-box strong{display:block;font-size:24px;font-variant-numeric:tabular-nums;margin-top:3px}
.report-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:11px}
.report-card{padding:13px 14px;border:1px solid var(--border);border-radius:12px;background:#fff}
.report-card-head{display:flex;gap:9px;align-items:center;justify-content:space-between;margin-bottom:11px}
.report-card .report-name{font-size:13px;font-weight:750;line-height:1.32}
.total-badge{display:inline-flex;align-items:center;justify-content:center;background:#edf3fe;color:#2553a8;font-size:14px;font-weight:800;border-radius:9px;padding:6px 9px;flex-shrink:0;min-width:31px}
.report-bits{display:grid;grid-template-columns:repeat(3,1fr);gap:6px}
.report-bit{background:#f8fafd;border-radius:7px;padding:8px 5px;text-align:center}
.report-bit small{display:block;font-size:10px;line-height:1.2;color:var(--muted)}
.report-bit b{font-size:16px;line-height:1.4;font-variant-numeric:tabular-nums}
.report-foot{font-size:11px;color:var(--muted);margin-top:9px}
.history-list{display:grid;gap:10px}
.history-item{display:flex;align-items:center;gap:12px;border:1px solid var(--border);border-radius:12px;padding:14px;text-align:left;background:white;width:100%;color:var(--text)}
.history-item:hover{background:#f8faff;border-color:#b7ceff}
.history-item .history-body{flex:1;min-width:0}
.history-item strong{font-size:14px;display:block;line-height:1.3}
.history-item small{display:block;font-size:12px;margin-top:3px;color:var(--muted)}
.history-count{background:#edf3ff;color:#235cba;border-radius:8px;font-weight:800;font-size:12px;padding:8px 9px;white-space:nowrap}
.info{background:#f2f7ff;border:1px solid #dce8fa;border-radius:12px;padding:15px 16px;color:#465f7f;font-size:13px;line-height:1.6}
.data-actions{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px;margin:16px 0}
.data-actions .btn{width:100%;min-height:55px}
hr{border:0;border-top:1px solid var(--border);margin:20px 0}
#fileImport{display:none}
.footer{text-align:center;font-size:12px;color:#92a0b0;margin-top:24px}
.toast{position:fixed;z-index:99;left:50%;bottom:28px;transform:translateX(-50%);min-width:180px;max-width:min(92vw,470px);padding:12px 18px;border-radius:12px;color:white;background:#22364f;box-shadow:0 10px 35px #15263c44;font-size:13px;font-weight:650;text-align:center;pointer-events:none;opacity:0;transition:opacity .2s}
.toast.show{opacity:1}
@media(min-width:850px){.student{padding:16px}.choice{font-size:12px}}
@media(max-width:840px){.controls{grid-template-columns:repeat(2,minmax(0,1fr))}.controls .today-btn{width:100%}.students{grid-template-columns:1fr 1fr}.choice-set{grid-template-columns:repeat(2,minmax(0,1fr))}.choice{font-size:12px}.report-grid{grid-template-columns:repeat(2,minmax(0,1fr))}}
@media(max-width:630px){
  .container{padding:18px 12px calc(100px + env(safe-area-inset-bottom))}
  .topbar{margin:2px 2px 16px;align-items:flex-start;gap:7px}
  .topbar h1{font-size:25px;margin-bottom:4px}
  .topbar p{font-size:12px}
  .topbar .pill{padding:6px 9px;font-size:10px;align-self:flex-start}
  .panel{border-radius:15px}
  .control-panel{padding:14px}
  .control-header{margin-bottom:10px}
  .controls{gap:10px}
  .field label{font-size:11px}
  .field select,.field input{height:48px}
  .controls .date-field{grid-column:1/3;grid-row:1}
  .controls .year-field{grid-column:1}
  .controls .lesson-field{grid-column:2}
  .controls .today-btn{grid-column:1/3}
  .summary{gap:8px;margin:11px 0 13px;grid-template-columns:repeat(2,minmax(0,1fr))}
  .kpi{min-height:82px;padding:12px 13px;border-radius:12px}
  .kpi span{font-size:11px}
  .kpi strong{font-size:27px;margin-top:5px}
  .navigation{position:fixed;z-index:60;bottom:0;left:0;right:0;margin:0;gap:0;background:#fff;border-top:1px solid var(--border);box-shadow:0 -8px 25px #273e6114;padding:6px 6px calc(7px + env(safe-area-inset-bottom));display:grid;grid-template-columns:repeat(4,minmax(0,1fr))}
  .nav-btn{border:0;border-radius:10px;background:none;min-width:0;min-height:57px;padding:7px 3px;display:flex;flex-direction:column;gap:3px;justify-content:center;font-size:10px;line-height:1.15}
  .nav-btn[aria-current="page"]{background:var(--primary-soft);color:var(--primary-dark);border:0}
  .nav-icon{font-size:21px}
  .content-panel{padding:15px}
  .section-head{margin-bottom:12px}
  .section-head h2{font-size:19px}
  .state-chip{font-size:10px;padding:6px 7px}
  .students{grid-template-columns:1fr;gap:8px}
  .student{padding:13px;border-radius:12px}
  .student-top{margin-bottom:10px}
  .choice-set{grid-template-columns:repeat(4,minmax(0,1fr))}
  .choice{font-size:11px}
  .lesson-actions{gap:8px}
  .lesson-actions .btn{flex:1 1 44%;padding:11px 7px}
  .report-grid{grid-template-columns:1fr}
  .report-overview{gap:7px}
  .overview-box{padding:10px}
  .overview-box small{font-size:10px}
  .overview-box strong{font-size:22px}
  .footer{margin-top:20px}
  .toast{bottom:calc(87px + env(safe-area-inset-bottom))}
}
@media(max-width:420px){
  .topbar{display:block}.topbar .pill{display:none}
  .choice-set{grid-template-columns:repeat(2,minmax(0,1fr))}
  .choice{font-size:12px;min-height:44px}
  .data-actions{grid-template-columns:1fr}
}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}*,*:before,*:after{transition:none!important}}
@media print{
  body{background:white}.container{max-width:none;padding:0}.topbar .pill,.control-panel,.summary,.navigation,.filterbar,.lesson-actions,.footer,.data-actions,.save-line,.toast{display:none!important}
  .panel{box-shadow:none;border:0}.content-panel{padding:0}.view:not(.active){display:none!important}.student,.report-card{break-inside:avoid}
  .students,.report-grid{grid-template-columns:repeat(2,1fr)}
}
</style>
</head>
<body>
<main class="container">
  <header class="topbar">
    <div><h1>Журнал посещаемости</h1><p>Учёт пропусков по парам · 24 студента</p></div>
    <span class="pill"><span class="dot"></span> Сохраняется на устройстве</span>
  </header>

  <section class="panel control-panel" aria-label="Выбор занятия">
    <div class="control-header">Выберите занятие</div>
    <div class="controls">
      <div class="field year-field"><label for="year">Учебный год</label><select id="year"></select></div>
      <div class="field date-field"><label for="date">Дата</label><input id="date" type="date" required></div>
      <div class="field lesson-field"><label for="lesson">Пара</label><select id="lesson"></select></div>
      <button class="btn today-btn" id="today" type="button">↪ Сегодня</button>
    </div>
  </section>

  <div class="summary" aria-label="Статистика текущей пары">
    <div class="kpi total"><span>Всего отсутствует</span><strong id="total">0</strong></div>
    <div class="kpi sick"><span>Болеет</span><strong id="sick">0</strong></div>
    <div class="kpi family"><span>По семейным</span><strong id="family">0</strong></div>
    <div class="kpi unknown"><span>Причина неизвестна</span><strong id="unknown">0</strong></div>
  </div>

  <nav class="navigation" aria-label="Разделы">
    <button type="button" class="nav-btn" data-view="journal" aria-current="page"><span class="nav-icon" aria-hidden="true">▦</span><span>Журнал</span></button>
    <button type="button" class="nav-btn" data-view="history"><span class="nav-icon" aria-hidden="true">◷</span><span>История</span></button>
    <button type="button" class="nav-btn" data-view="report"><span class="nav-icon" aria-hidden="true">▥</span><span>Статистика</span></button>
    <button type="button" class="nav-btn" data-view="data"><span class="nav-icon" aria-hidden="true">⇩</span><span>Данные</span></button>
  </nav>

  <section class="view active panel content-panel" id="journal" aria-label="Журнал на выбранной паре">
    <div class="section-head">
      <div><h2 id="lessonTitle">Отметки на паре</h2><p class="subtle" id="lessonSubtitle">Выберите причину для отсутствующих</p></div>
      <span id="recordState" class="state-chip unsaved">Не отмечена</span>
    </div>
    <div class="filterbar">
      <input id="studentSearch" type="search" class="search" aria-label="Поиск студента" placeholder="Поиск по фамилии или имени…" autocomplete="off">
      <label class="filter-switch"><input type="checkbox" id="absentOnly"><span>Только отсутствующие</span></label>
    </div>
    <div class="countline" id="studentCount">24 студента</div>
    <div id="students" class="students"></div>
    <div class="lesson-actions">
      <button id="allPresent" type="button" class="btn primary">✓ Все присутствуют</button>
      <button id="copy" type="button" class="btn">⧉ Скопировать отсутствующих</button>
      <button id="removeLesson" type="button" class="btn danger">Удалить запись о паре</button>
    </div>
    <p id="saveStatus" class="save-line" role="status">Изменения сохраняются автоматически. Если никто не отсутствует, нажмите «Все присутствуют».</p>
  </section>

  <section class="view panel content-panel" id="history" aria-label="История занятий">
    <div class="section-head"><div><h2>История занятий</h2><p id="historySubtitle" class="subtle">Все отмеченные пары выбранного учебного года</p></div></div>
    <div id="historyList" class="history-list"></div>
  </section>

  <section class="view panel content-panel" id="report" aria-label="Статистика за учебный год">
    <div class="section-head"><div><h2>Статистика за год</h2><p id="reportSubtitle" class="subtle">Пропущенные пары каждого студента</p></div></div>
    <div class="report-overview">
      <div class="overview-box"><small>Учтено пар</small><strong id="allLessons">0</strong></div>
      <div class="overview-box"><small>Пропусков всего</small><strong id="allAbsences">0</strong></div>
      <div class="overview-box"><small>Посещаемость</small><strong id="attendancePercent">—</strong></div>
    </div>
    <div id="reportRows" class="report-grid"></div>
    <p class="save-line">Если студент пропустил несколько пар в один день, каждая пара учитывается отдельно. Процент рассчитывается только по отмеченным парам.</p>
  </section>

  <section class="view panel content-panel" id="data" aria-label="Экспорт и резервное копирование">
    <div class="section-head"><div><h2>Экспорт и сохранение</h2><p class="subtle">Скачайте результаты или перенесите журнал на другое устройство</p></div></div>
    <div class="info"><strong>Важная информация.</strong> Журнал работает без интернета и сервера. Данные хранятся в браузере данного устройства. При очистке данных браузера они могут исчезнуть. Регулярно скачивайте резервную копию JSON.</div>
    <div class="data-actions">
      <button class="btn primary" id="csvSummary" type="button">↓ Статистика CSV для Excel</button>
      <button class="btn" id="csvDetailed" type="button">↓ Все отметки CSV</button>
      <button class="btn" id="backup" type="button">↓ Резервная копия JSON</button>
      <button class="btn" id="restore" type="button">↑ Восстановить из JSON</button>
    </div>
    <input id="fileImport" type="file" accept=".json,application/json">
    <hr>
    <p class="subtle">Восстановление заменяет все текущие записи журнала, поэтому перед импортом рекомендуется скачать резервную копию.</p>
  </section>
  <div class="footer">Журнал посещаемости · локальное хранение · без регистрации</div>
</main>
<div class="toast" id="toast" role="status" aria-live="polite"></div>
<script>
(()=>{'use strict';
  const NAMES=[
    'Бружев Рамиль Альбертович','Гиголов Владик Самвелович',
    'Готовцев Владимир Андреевич','Гричаниченко Арсений Дмитриевич',
    'Долманова Кристина Алексеевна','Запорожцев Виталий Владимирович',
    'Зарицкий Александр Сергеевич','Зыза Вячеслав Максимович',
    'Иванов Константин Витальевич','Кехян Артур Арегович',
    'Коротин Павел Сергеевич','Лисогорский Александр Александрович',
    'Меркулов Артем Денисович','Посулько Иван Павлович',
    'Прис Анастасия Олеговна','Равцова Татьяна Константиновна',
    'Расихина Анастасия Александровна','Рокотова София Ивановна',
    'Рудиков Андрей Сергеевич','Рыбалко Сергей Владимирович',
    'Тимов Аслан Чишмаевич','Филатов Владислав Алексеевич',
    'Хантимиров Ильдар Маратович','Чобанян Мери Галустовна'
  ];
  const KEY='group-attendance-2026-v1'; // Совместимость с предыдущей версией файла
  const OPTIONS={present:'Присутствует',sick:'Болеет',family:'По семейным',unknown:'Неизвестно'};
  const $=id=>document.getElementById(id);
  let records={},activeView='journal',savedOK=true,toastTimer;
  const pad=v=>String(v).padStart(2,'0');
  const dateISO=d=>`${d.getFullYear()}-${pad(d.getMonth()+1)}-${pad(d.getDate())}`;
  const academicYear=d=>d.getFullYear()-(d.getMonth()<8?1:0);
  function dateValid(s){if(!/^\d{4}-\d{2}-\d{2}$/.test(s))return false;const d=new Date(`${s}T12:00:00`);return !Number.isNaN(d.getTime())&&dateISO(d)===s;}
  const inYear=(s,y)=>s>=`${y}-09-01`&&s<=`${y+1}-08-31`;
  const year=()=>Number($('year').value);
  const entryKey=()=>`${$('date').value}|${$('lesson').value}`;
  const entry=()=>records[entryKey()]||{};
  const hasEntry=()=>Object.prototype.hasOwnProperty.call(records,entryKey());
  const formatDate=s=>new Date(`${s}T12:00:00`).toLocaleDateString('ru-RU',{day:'numeric',month:'long',weekday:'short'});
  const yearEntries=()=>Object.entries(records).filter(([key])=>inYear(key.slice(0,10),year())).sort(([a],[b])=>b.localeCompare(a));
  function normalize(obj){
    if(!obj||typeof obj!=='object'||Array.isArray(obj))throw Error('Некорректный формат записей');
    const result={};
    for(const [key,val] of Object.entries(obj)){
      const m=/^(\d{4}-\d{2}-\d{2})\|([1-8])$/.exec(key);
      if(!m||!dateValid(m[1])||!val||typeof val!=='object'||Array.isArray(val))continue;
      const clean={};
      for(const [id,reason] of Object.entries(val))if(/^(?:[0-9]|1[0-9]|2[0-3])$/.test(id)&&['sick','family','unknown'].includes(reason))clean[id]=reason;
      result[key]=clean; // Пустая запись = все присутствуют (пара учтена)
    }
    return result;
  }
  function showToast(message){
    $('toast').textContent=message;$('toast').classList.add('show');clearTimeout(toastTimer);
    toastTimer=setTimeout(()=>$('toast').classList.remove('show'),2100);
  }
  function load(){
    try{const raw=localStorage.getItem(KEY);if(raw)records=normalize(JSON.parse(raw));}
    catch(err){savedOK=false;$('saveStatus').textContent='Ошибка чтения сохранённых данных. Проверьте настройки браузера.';$('saveStatus').classList.add('error');}
  }
  function save(){
    try{localStorage.setItem(KEY,JSON.stringify(records));savedOK=true;$('saveStatus').textContent='✓ Отметки сохранены на этом устройстве';$('saveStatus').classList.remove('error');}
    catch(err){savedOK=false;$('saveStatus').textContent='Не удалось сохранить отметки! Скачайте резервную копию JSON.';$('saveStatus').classList.add('error');showToast('Ошибка хранения данных');}
  }
  function setYear(y){
    if(![...$('year').options].some(o=>o.value===String(y)))$('year').add(new Option(`${y}/${y+1}`,String(y)));
    $('year').value=String(y);$('date').min=`${y}-09-01`;$('date').max=`${y+1}-08-31`;
  }
  function renderSummary(){
    const counts={sick:0,family:0,unknown:0};
    Object.values(entry()).forEach(reason=>{if(reason in counts)counts[reason]++;});
    for(const r of Object.keys(counts))$(r).textContent=counts[r];
    $('total').textContent=counts.sick+counts.family+counts.unknown;
  }
  function node(tag,cls,text){const el=document.createElement(tag);if(cls)el.className=cls;if(text!==undefined)el.textContent=text;return el;}
  function renderStudents(){
    const row=entry();const phrase=$('studentSearch').value.trim().toLocaleLowerCase('ru');const only=$('absentOnly').checked;
    const list=NAMES.map((name,id)=>({name,id,status:row[id]||'present'}))
      .filter(p=>(!phrase||p.name.toLocaleLowerCase('ru').includes(phrase))&&(!only||p.status!=='present'));
    const area=$('students');area.replaceChildren();
    $('studentCount').textContent=`Показано: ${list.length} из ${NAMES.length} · присутствуют: ${NAMES.length-Object.keys(row).length}`;
    if(!list.length){area.append(node('div','empty',only?'На этой паре отсутствующих нет.':'Студенты не найдены.'));return;}
    const fragment=document.createDocumentFragment();
    list.forEach(({name,id,status})=>{
      const card=node('article','student'+(status==='present'?'':' is-absent'));
      const top=node('div','student-top');top.append(node('span','number',String(id+1)));
      const nameBox=node('div','name-wrap');nameBox.append(node('span','student-name',name),node('span','student-status',status==='present'?'На паре':OPTIONS[status]));top.append(nameBox);card.append(top);
      const choiceSet=node('div','choice-set');choiceSet.setAttribute('role','group');choiceSet.setAttribute('aria-label',`Посещаемость: ${name}`);
      for(const [reason,label] of Object.entries(OPTIONS)){
        const b=node('button','choice '+reason,label);b.type='button';b.dataset.id=String(id);b.dataset.reason=reason;b.setAttribute('aria-pressed',String(status===reason));choiceSet.append(b);
      }
      card.append(choiceSet);fragment.append(card);
    });
    area.append(fragment);
  }
  function renderJournal(){
    const date=$('date').value;const pair=$('lesson').value;
    $('lessonTitle').textContent=`${pair}-я пара · ${formatDate(date)}`;
    $('lessonSubtitle').textContent='Выберите причину отсутствия или отметьте «Присутствует»';
    $('recordState').textContent=hasEntry()?'✓ Пара отмечена':'Не отмечена';
    $('recordState').classList.toggle('unsaved',!hasEntry());
    $('removeLesson').disabled=!hasEntry();
    renderSummary();renderStudents();
  }
  function aggregation(){
    const lessons=yearEntries();
    const rows=NAMES.map((name,id)=>({name,id,sick:0,family:0,unknown:0,total:0}));
    for(const [,info] of lessons)for(const [id,reason] of Object.entries(info))if(rows[+id]&&['sick','family','unknown'].includes(reason)){rows[+id][reason]++;rows[+id].total++;}
    const total=rows.reduce((sum,r)=>sum+r.total,0);
    return {rows,total,lessonCount:lessons.length};
  }
  function renderReport(){
    const {rows,total,lessonCount}=aggregation();
    $('reportSubtitle').textContent=`Учебный год ${year()}/${year()+1} · учтены только сохранённые пары`;
    $('allLessons').textContent=lessonCount;$('allAbsences').textContent=total;
    $('attendancePercent').textContent=lessonCount?`${Math.round(100*(1-total/(lessonCount*NAMES.length)))}%`:'—';
    const area=$('reportRows');area.replaceChildren();const fragment=document.createDocumentFragment();
    rows.forEach(({name,id,sick,family,unknown,total})=>{
      const c=node('article','report-card'),head=node('div','report-card-head');
      head.append(node('span','report-name',`${id+1}. ${name}`),node('span','total-badge',String(total)));c.append(head);
      const bits=node('div','report-bits');
      for(const [caption,value] of [['Болеет',sick],['Семейные',family],['Неизвестно',unknown]]){
        const part=node('div','report-bit');part.append(node('small','',caption),node('b','',String(value)));bits.append(part);
      }
      c.append(bits);c.append(node('div','report-foot',`Присутствовал: ${Math.max(0,lessonCount-total)} из ${lessonCount} учтённых пар`));fragment.append(c);
    });area.append(fragment);
  }
  function renderHistory(){
    const entries=yearEntries();$('historySubtitle').textContent=`Учебный год ${year()}/${year()+1} · записей: ${entries.length}`;
    const area=$('historyList');area.replaceChildren();
    if(!entries.length){area.append(node('div','empty','Отметок за этот учебный год пока нет. Откройте «Журнал», чтобы начать.'));return;}
    for(const [key,absent] of entries){
      const [date,pair]=key.split('|');const count=Object.keys(absent).length;
      const b=node('button','history-item');b.type='button';b.dataset.date=date;b.dataset.pair=pair;
      const center=node('div','history-body');center.append(node('strong','',`${formatDate(date)} · ${pair}-я пара`),node('small','',count?'Нажмите, чтобы открыть и изменить':'Все присутствовали'));
      b.append(center,node('span','history-count',`${count} отсутств.`),node('span','', '›'));area.append(b);
    }
  }
  function switchView(view,scroll=true){
    activeView=view;document.querySelectorAll('.nav-btn').forEach(b=>{if(b.dataset.view===view)b.setAttribute('aria-current','page');else b.removeAttribute('aria-current');});
    document.querySelectorAll('.view').forEach(el=>el.classList.toggle('active',el.id===view));
    if(view==='journal')renderJournal();if(view==='history')renderHistory();if(view==='report')renderReport();
    if(scroll)window.scrollTo({top:0,behavior:'instant'});
  }
  function mark(id,reason){
    const key=entryKey();const current={...entry()};
    if(reason==='present')delete current[id];else current[id]=reason;
    records[key]=current;save();renderJournal();
  }
  function download(filename,body,type){
    const blob=new Blob([body],{type});const url=URL.createObjectURL(blob);const a=document.createElement('a');
    a.href=url;a.download=filename;document.body.append(a);a.click();a.remove();setTimeout(()=>URL.revokeObjectURL(url),5000);
  }
  const quote=s=>'"'+String(s).replace(/"/g,'""')+'"';
  function csv(rows){return '\ufeff'+rows.map(row=>row.map(quote).join(';')).join('\r\n');}
  function exportSummary(){
    const rows=[['№','ФИО','Болеет','По семейным','Неизвестно','Пропущено пар','Присутствовал пар']];const data=aggregation();
    data.rows.forEach((r,i)=>rows.push([i+1,r.name,r.sick,r.family,r.unknown,r.total,data.lessonCount-r.total]));
    download(`статистика_${year()}-${year()+1}.csv`,csv(rows),'text/csv;charset=utf-8');showToast('Статистика скачана');
  }
  function exportDetailed(){
    const rows=[['Дата','Пара','№','ФИО','Статус']];
    yearEntries().sort(([a],[b])=>a.localeCompare(b)).forEach(([key,val])=>{
      const [date,pair]=key.split('|');NAMES.forEach((name,id)=>rows.push([date,pair,id+1,name,OPTIONS[val[id]||'present']]));
    });
    download(`отметки_${year()}-${year()+1}.csv`,csv(rows),'text/csv;charset=utf-8');showToast('Отметки скачаны');
  }
  async function copyAbsent(){
    const absent=Object.entries(entry()).map(([id,status])=>`${NAMES[+id]} — ${OPTIONS[status]}`);
    const text=`Отсутствующие · ${$('date').value} · ${$('lesson').value}-я пара\n${absent.join('\n')||'Отсутствующих нет'}`;
    try{await navigator.clipboard.writeText(text);showToast('Список скопирован');}
    catch(err){const t=document.createElement('textarea');t.value=text;t.style.position='fixed';t.style.opacity='0';document.body.append(t);t.select();let ok=false;try{ok=document.execCommand('copy');}catch(e){}t.remove();if(ok)showToast('Список скопирован');else prompt('Скопируйте список:',text);}
  }
  function init(){
    load();const today=new Date(),currentYear=academicYear(today);
    for(let y=Math.min(2024,currentYear-3);y<=Math.max(2030,currentYear+3);y++)$('year').add(new Option(`${y}/${y+1}`,String(y)));
    for(let p=1;p<=8;p++)$('lesson').add(new Option(`${p}-я пара`,String(p)));
    setYear(currentYear);$('date').value=dateISO(today);$('lesson').value='1';
    $('year').addEventListener('change',()=>{const y=year();setYear(y);if(!inYear($('date').value,y))$('date').value=`${y}-09-01`;refresh();});
    $('date').addEventListener('change',()=>{if(!dateValid($('date').value)||!inYear($('date').value,year())){$('date').value=`${year()}-09-01`;showToast('Выберите дату внутри учебного года');}refresh();});
    $('lesson').addEventListener('change',refresh);
    $('today').addEventListener('click',()=>{const d=new Date();setYear(academicYear(d));$('date').value=dateISO(d);switchView('journal');});
    $('studentSearch').addEventListener('input',renderStudents);
    $('absentOnly').addEventListener('change',renderStudents);
    $('students').addEventListener('click',e=>{const b=e.target.closest('button[data-id]');if(b)mark(b.dataset.id,b.dataset.reason);});
    document.querySelectorAll('.nav-btn').forEach(b=>b.addEventListener('click',()=>switchView(b.dataset.view)));
    $('allPresent').addEventListener('click',()=>{
      if(Object.keys(entry()).length&&!confirm('Отметить всех присутствующими? Текущие причины отсутствия будут удалены.'))return;
      records[entryKey()]={};save();renderJournal();showToast('Все присутствуют · пара сохранена');
    });
    $('removeLesson').addEventListener('click',()=>{
      if(!hasEntry())return;
      if(confirm('Удалить запись выбранной пары полностью? Это действие нельзя отменить.')){delete records[entryKey()];save();renderJournal();showToast('Запись удалена');}
    });
    $('copy').addEventListener('click',copyAbsent);
    $('historyList').addEventListener('click',e=>{const b=e.target.closest('button[data-date]');if(!b)return;$('date').value=b.dataset.date;$('lesson').value=b.dataset.pair;switchView('journal');});
    $('csvSummary').addEventListener('click',exportSummary);
    $('csvDetailed').addEventListener('click',exportDetailed);
    $('backup').addEventListener('click',()=>{
      download(`копия_журнала_${dateISO(new Date())}.json`,JSON.stringify({type:'attendance-backup',version:1,exportedAt:new Date().toISOString(),records},null,2),'application/json;charset=utf-8');showToast('Резервная копия скачана');
    });
    $('restore').addEventListener('click',()=>$('fileImport').click());
    $('fileImport').addEventListener('change',async e=>{
      const file=e.target.files?.[0];if(!file)return;
      try{
        if(file.size>5*1024*1024)throw Error('Файл слишком большой (максимум 5 МБ).');
        const obj=JSON.parse(await file.text());if(obj.type!=='attendance-backup'||obj.version!==1||!obj.records)throw Error('Файл не является резервной копией журнала.');
        const imported=normalize(obj.records);
        if(!confirm(`Заменить все текущие отметки? В копии ${Object.keys(imported).length} занятий. Действие нельзя отменить.`))return;
        records=imported;save();refresh();showToast('Копия восстановлена');
      }catch(err){alert('Ошибка загрузки: '+err.message);}finally{e.target.value='';}
    });
    refresh();if(!savedOK){$('saveStatus').textContent='Не удалось прочитать локальное хранилище. Проверьте настройки браузера.';$('saveStatus').classList.add('error');}
  }
  function refresh(){renderSummary();if(activeView==='journal')renderJournal();else if(activeView==='history')renderHistory();else if(activeView==='report')renderReport();}
  init();
})();
</script>
</body>
</html>
