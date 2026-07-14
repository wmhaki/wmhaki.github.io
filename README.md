# wmhaki.github.io

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Privacy Policy — SPMP Mark Keyin</title>
<style>
  :root{
    --ink:#132420; --muted:#5b6b66; --line:#e1e6e2; --bg:#f7f8f5;
    --pen:#0f766e; --pen-deep:#0b5852; --pen-soft:#e8f6f3; --paper:#ffffff;
    --hilite:#fde047;
  }
  *{box-sizing:border-box}
  body{
    margin:0; background:var(--bg); color:var(--ink);
    font:16px/1.65 -apple-system,"Segoe UI",Roboto,sans-serif;
  }
  .wrap{max-width:760px;margin:0 auto;padding:56px 24px 96px}
  header{margin-bottom:40px}
  .eyebrow{
    display:inline-flex; align-items:center; gap:8px;
    font:700 11.5px/1 -apple-system,sans-serif; letter-spacing:.09em; text-transform:uppercase;
    color:var(--pen-deep); background:var(--pen-soft); border:1px solid #cdeeea;
    padding:6px 12px; border-radius:999px; margin-bottom:20px;
  }
  h1{
    font-size:clamp(28px,4vw,38px); line-height:1.15; margin:0 0 10px; letter-spacing:-.01em;
  }
  h1 .hl{position:relative; z-index:0; padding:0 3px}
  h1 .hl::after{
    content:""; position:absolute; z-index:-1; left:-2px; right:-4px; bottom:2px; height:38%;
    background:linear-gradient(93deg,var(--hilite),#facc15); transform:skewX(-10deg);
  }
  .meta{color:var(--muted); font-size:14.5px}
  .meta b{color:var(--ink)}
  .summary{
    margin:32px 0 8px; padding:20px 22px; background:var(--paper); border:1px solid var(--line);
    border-left:4px solid var(--pen); border-radius:10px; font-size:15px;
  }
  .summary p{margin:0 0 10px}
  .summary p:last-child{margin-bottom:0}
  .summary ul{margin:8px 0 0; padding-left:20px}
  h2{
    font-size:19px; margin:44px 0 12px; padding-top:4px;
    border-top:1px solid var(--line); padding-top:20px;
  }
  h2 span.num{color:var(--pen); font-variant-numeric:tabular-nums; margin-right:8px}
  p, li{color:#2b3835; font-size:15.5px}
  ul{padding-left:22px}
  li{margin-bottom:6px}
  table{width:100%; border-collapse:collapse; margin:14px 0; font-size:14.5px; background:var(--paper); border:1px solid var(--line); border-radius:8px; overflow:hidden}
  th,td{padding:10px 14px; text-align:left; border-bottom:1px solid var(--line); vertical-align:top}
  th{background:#eef2ef; font-size:11.5px; text-transform:uppercase; letter-spacing:.06em; color:var(--muted)}
  tr:last-child td{border-bottom:none}
  .ok{color:var(--pen-deep); font-weight:700}
  .no{color:#b91c1c; font-weight:700}
  .contact{
    margin-top:20px; padding:18px 20px; background:var(--pen-soft); border:1px solid #cdeeea; border-radius:10px;
  }
  .contact b{color:var(--pen-deep)}
  code{background:#eef2ef; padding:1px 6px; border-radius:5px; font-size:.92em}
  footer{margin-top:56px; padding-top:20px; border-top:1px solid var(--line); color:var(--muted); font-size:13px}
  .placeholder{background:#fff7ed; border:1px dashed #fdba74; padding:2px 6px; border-radius:5px; color:#9a3412}
</style>
</head>
<body>
<div class="wrap">

  <header>
    <div class="eyebrow">Privacy Policy</div>
    <h1><span class="hl">SPMP</span> Mark Keyin</h1>
    <div class="meta">Chrome Extension &nbsp;·&nbsp; Version 1.3 &nbsp;·&nbsp; Last updated: <b>14 July 2026</b></div>
  </header>

  <div class="summary">
    <p><b>In short:</b> SPMP Mark Keyin reads student names and marks from a file you choose (or cells you copy) and writes them into a grade-entry web page you already have open. Everything happens inside your own browser.</p>
    <ul>
      <li>We do <b>not</b> operate any server. No data this extension handles is ever transmitted anywhere.</li>
      <li>We do <b>not</b> sell, rent, or share user data with any third party.</li>
      <li>We do <b>not</b> use analytics, tracking, or advertising services of any kind.</li>
      <li>Data is <b>not stored</b> after you close the extension popup or close the browser tab.</li>
    </ul>
  </div>

  <h2><span class="num">1.</span>Who this policy covers</h2>
  <p>This policy applies to the <b>SPMP Mark Keyin</b> Chrome extension ("the Extension"), developed by <b>Wan Mohd Hakimin Bin Wan Shafie</b>. It explains what data the Extension handles, how that data is used, and who it is shared with, in line with the Chrome Web Store User Data Policy.</p>

  <h2><span class="num">2.</span>What data the Extension handles</h2>
  <p>The Extension processes the following data, entirely on your own device:</p>
  <table>
    <tr><th>Data</th><th>Source</th><th>Why it's needed</th></tr>
    <tr>
      <td>Student names and mark values</td>
      <td>An Excel/CSV file you choose to open, or spreadsheet cells you copy and paste into the Extension</td>
      <td>To match each student's name against the names shown on your currently open grade‑entry page, and to fill in the matching mark field(s)</td>
    </tr>
    <tr>
      <td>Text content of the web page you are viewing</td>
      <td>The single browser tab you are actively using, read only after you click <em>"Preview Match"</em> or <em>"Fill Marks"</em></td>
      <td>To find the rows of student names on that page and place the correct mark values next to them</td>
    </tr>
    <tr>
      <td>Clipboard content</td>
      <td>Only when you choose the "Paste directly from Excel" option and press Ctrl+V or click "Paste from clipboard"</td>
      <td>To read the spreadsheet cells you copied, as an alternative to uploading a file</td>
    </tr>
  </table>
  <p>The Extension does <b>not</b> collect health information, financial information, authentication credentials, personal communications, web browsing history, location data, or any data from any page other than the single tab you are actively working on.</p>

  <h2><span class="num">3.</span>How the data is used</h2>
  <ul>
    <li>Student names and marks are read into the Extension's memory only while its popup window is open.</li>
    <li>They are used solely to compute a name-matching score and to write mark values into input fields on the page you are viewing.</li>
    <li>No copy of this data is written to disk, to <code>chrome.storage</code>, to a database, or to any remote server. The Extension contains no networking code and makes no outbound requests.</li>
    <li>All processing (reading the file, matching names, filling values) runs locally inside your browser, using only local JavaScript bundled with the Extension.</li>
  </ul>

  <h2><span class="num">4.</span>Data retention</h2>
  <p>The Extension keeps data only in memory, for the current popup session. Closing the extension popup, navigating away, or closing the browser tab clears all student names and marks the Extension was holding. Nothing persists between sessions.</p>

  <h2><span class="num">5.</span>Data sharing and third parties</h2>
  <table>
    <tr><th>Party</th><th>Data shared</th></tr>
    <tr><td>Developer of this Extension</td><td class="no">None — the developer has no server and receives no data from installations of this Extension</td></tr>
    <tr><td>Advertising or analytics providers</td><td class="no">None — no such services are integrated</td></tr>
    <tr><td>Any other third party</td><td class="no">None</td></tr>
  </table>

  <h2><span class="num">6.</span>Permissions used</h2>
  <table>
    <tr><th>Permission</th><th>Purpose</th></tr>
    <tr><td><code>activeTab</code></td><td>Read and modify the single tab you are viewing, only after you click a button inside the Extension</td></tr>
    <tr><td><code>scripting</code></td><td>Inject the script that reads student rows and fills mark fields on that same tab</td></tr>
    <tr><td><code>clipboardRead</code></td><td>Read spreadsheet cells you copy, only when you use the "Paste directly from Excel" feature</td></tr>
  </table>
  <p>The Extension does not request any host permissions or match patterns, and cannot access any website automatically or in the background.</p>

  <h2><span class="num">7.</span>Children's data</h2>
  <p>The names and marks processed by this Extension may relate to students, including minors. This data is supplied and controlled entirely by the lecturer or staff member using the Extension, is processed only locally on that person's device, and is never transmitted to the developer or any third party. Institutions should ensure use of the Extension complies with their own student‑data handling policies.</p>

  <h2><span class="num">8.</span>Security</h2>
  <p>Because no data ever leaves your device, there is no server-side storage to secure. Standard browser sandboxing applies to the Extension like any other Chrome extension. We recommend keeping Chrome updated and only installing the Extension from the official Chrome Web Store listing.</p>

  <h2><span class="num">9.</span>Changes to this policy</h2>
  <p>If this policy changes, the "Last updated" date above will be revised and the new version will be published at this same URL. Material changes will also be reflected in the extension's Chrome Web Store listing notes.</p>

  <h2><span class="num">10.</span>Contact</h2>
  <div class="contact">
    <p>Questions about this policy or how the Extension handles data can be sent to:</p>
    <p><b>Email:</b> <a href="mailto:wmhakimin@gmail.com">wmhakimin@gmail.com</a><br>
       <b>Developer:</b> Wan Mohd Hakimin Bin Wan Shafie</p>
  </div>

  <footer>
    SPMP Mark Keyin — Privacy Policy · WMHWS
  </footer>

</div>
</body>
</html>
