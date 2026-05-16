[portier-vs-crown-castle.html](https://github.com/user-attachments/files/27862124/portier-vs-crown-castle.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portier v. Crown Castle — Telecom Easement Fraud Dispute</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Lora:ital,wght@0,400;0,500;1,400&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --ink:#1a1814;--ink-mid:#3d3a35;--ink-light:#7a756d;
  --paper:#faf8f4;--paper-dark:#f0ede6;--rule:#d4cfc6;
  --gold:#b8860b;--gold-light:#f5e9c8;
  --danger:#8b1a1a;--danger-light:#f9eded;
  --blue:#1e3a5a;--blue-light:#eef2f8;
  --green:#1a5c2e;--green-light:#eaf4ee;
}
html{scroll-behavior:smooth}
body{font-family:'Lora',Georgia,serif;background:var(--paper);color:var(--ink);font-size:16px;line-height:1.8}
a{color:var(--gold);text-decoration:none}
a:hover{text-decoration:underline}
p{margin-bottom:1.1rem}

/* NAV */
nav{background:var(--ink);padding:0 2rem;display:flex;align-items:center;justify-content:space-between;height:60px;position:sticky;top:0;z-index:100;border-bottom:2px solid var(--gold)}
.brand{font-family:'Cormorant Garamond',serif;font-size:19px;color:#fff;font-weight:600;letter-spacing:.02em}
.brand span{color:var(--gold)}
nav ul{display:flex;list-style:none;gap:1.5rem;flex-wrap:wrap}
nav ul a{color:#ccc;font-size:11px;letter-spacing:.06em;text-transform:uppercase;transition:color .2s}
nav ul a:hover{color:var(--gold)}

/* HERO */
.hero{background:var(--ink);padding:5rem 2rem 4rem;text-align:center;border-bottom:3px solid var(--gold)}
.eyebrow{font-size:11px;letter-spacing:.2em;text-transform:uppercase;color:var(--gold);margin-bottom:1rem}
.hero h1{font-family:'Cormorant Garamond',serif;font-size:clamp(2rem,4.5vw,3.4rem);color:#fff;font-weight:600;line-height:1.15;max-width:820px;margin:0 auto 1.5rem}
.hero h1 em{font-style:italic;color:var(--gold)}
.hero-intro{color:#b5ada4;max-width:680px;margin:0 auto 2.5rem;font-size:15px;line-height:1.9}
.stat-row{display:flex;justify-content:center;gap:2.5rem;flex-wrap:wrap;border-top:1px solid #333;padding-top:2rem;margin-top:2rem}
.stat{text-align:center}
.stat-val{font-family:'Cormorant Garamond',serif;font-size:2rem;color:#fff;font-weight:600;display:block}
.stat-lbl{font-size:10px;letter-spacing:.12em;text-transform:uppercase;color:var(--gold)}

/* LAYOUT */
.page-wrap{max-width:960px;margin:0 auto;padding:0 2rem}
section{padding:3.5rem 0;border-bottom:1px solid var(--rule)}
.section-label{font-size:10px;letter-spacing:.22em;text-transform:uppercase;color:var(--gold);margin-bottom:.7rem;display:block}
h2{font-family:'Cormorant Garamond',serif;font-size:2.1rem;font-weight:600;color:var(--ink);margin-bottom:1.5rem;line-height:1.2}
h3{font-family:'Cormorant Garamond',serif;font-size:1.4rem;font-weight:600;color:var(--ink);margin-bottom:.6rem;margin-top:1.5rem}
h4{font-family:'Lora',serif;font-size:1rem;font-weight:500;color:var(--ink);margin-bottom:.4rem;margin-top:1.2rem}

/* CALLOUT BOXES */
.box{padding:1.3rem 1.6rem;margin-bottom:1.5rem;border-radius:0 4px 4px 0}
.box-gold{background:var(--gold-light);border-left:4px solid var(--gold)}
.box-danger{background:var(--danger-light);border-left:4px solid var(--danger)}
.box-blue{background:var(--blue-light);border-left:4px solid var(--blue)}
.box-green{background:var(--green-light);border-left:4px solid var(--green)}
.box p{font-size:15px;margin-bottom:.5rem;color:var(--ink-mid)}
.box p:last-child{margin-bottom:0}
.box strong{color:var(--ink)}

/* TIMELINE */
.timeline{position:relative;padding-left:2.2rem;margin:1.5rem 0}
.timeline::before{content:'';position:absolute;left:4px;top:8px;bottom:8px;width:2px;background:var(--rule)}
.tl-item{position:relative;margin-bottom:2rem}
.tl-item::before{content:'';position:absolute;left:-2.05rem;top:7px;width:11px;height:11px;border-radius:50%;background:var(--gold);border:2px solid var(--paper);z-index:1}
.tl-item.red::before{background:var(--danger)}
.tl-item.blue::before{background:var(--blue)}
.tl-date{font-size:11px;letter-spacing:.1em;text-transform:uppercase;margin-bottom:.25rem}
.tl-item .tl-date{color:var(--gold)}
.tl-item.red .tl-date{color:var(--danger)}
.tl-item.blue .tl-date{color:var(--blue)}
.tl-item h4{margin-top:0;font-size:1rem}
.tl-item p{font-size:14px;color:var(--ink-mid);margin-bottom:0}

/* DOCUMENT CARDS */
.doc-card{background:#fff;border:1px solid var(--rule);border-top:4px solid var(--ink);padding:1.8rem;margin-bottom:1.8rem;position:relative}
.doc-card.disputed{border-top-color:var(--danger)}
.doc-card.corp{border-top-color:var(--blue)}
.doc-badge{position:absolute;top:1rem;right:1rem;font-size:9px;letter-spacing:.14em;text-transform:uppercase;padding:.3rem .8rem;font-weight:500}
.badge-orig{background:var(--ink);color:var(--gold)}
.badge-disp{background:var(--danger);color:#fff}
.badge-corp{background:var(--blue);color:#fff}
.badge-atc{background:#2c5f2e;color:#fff}
.doc-title{font-family:'Cormorant Garamond',serif;font-size:1.35rem;font-weight:600;margin-bottom:.25rem}
.doc-meta{font-size:11px;color:var(--ink-light);letter-spacing:.04em;margin-bottom:1rem}
.parties-grid{display:grid;grid-template-columns:1fr 1fr;gap:1rem;background:var(--paper-dark);padding:1rem;margin:.8rem 0;font-size:13px}
.party-lbl{font-size:9px;text-transform:uppercase;letter-spacing:.12em;color:var(--ink-light);margin-bottom:.2rem}
.party-name{font-weight:500}
.party-detail{font-size:11px;color:var(--ink-light);line-height:1.5}
.stamp-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:.5rem;background:var(--paper-dark);padding:.8rem 1rem;margin:.8rem 0;font-size:12px}
.stamp-item span{display:block;font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--ink-light);margin-bottom:.1rem}
.doc-quote{font-size:14px;color:var(--ink-mid);line-height:1.75;border-left:2px solid var(--rule);padding-left:1rem;margin:1rem 0;font-style:italic}
.terms-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(130px,1fr));gap:.7rem;margin:.8rem 0}
.term-box{background:var(--paper-dark);padding:.8rem;text-align:center}
.term-val{font-family:'Cormorant Garamond',serif;font-size:1.35rem;font-weight:600}
.term-lbl{font-size:10px;text-transform:uppercase;letter-spacing:.08em;color:var(--ink-light)}

/* CHAIN OF TITLE */
.chain{margin:1.5rem 0}
.chain-node{background:#fff;border:1px solid var(--rule);padding:1rem 1.3rem;margin-bottom:.25rem;display:flex;justify-content:space-between;align-items:flex-start;gap:1rem}
.chain-node.n-disputed{border-left:4px solid var(--danger)}
.chain-node.n-corp{border-left:4px solid var(--blue)}
.chain-node.n-current{border-left:4px solid var(--green);background:var(--green-light)}
.chain-name{font-family:'Cormorant Garamond',serif;font-size:1.1rem;font-weight:600}
.chain-detail{font-size:12px;color:var(--ink-light);margin-top:.2rem;line-height:1.5}
.chain-date{font-size:11px;text-align:right;color:var(--ink-light);white-space:nowrap;min-width:90px}
.chain-arrow{text-align:center;color:var(--gold);font-size:1rem;padding:.1rem 0}

/* FLAG LIST */
.flag-list{list-style:none;margin:1rem 0}
.flag-list li{display:flex;gap:.9rem;align-items:flex-start;padding:.9rem 0;border-bottom:1px solid var(--paper-dark);font-size:15px;color:var(--ink-mid)}
.flag-list li:last-child{border-bottom:none}
.flag-icon{width:22px;height:22px;min-width:22px;background:var(--danger);color:#fff;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:700;flex-shrink:0;margin-top:2px}

/* LEGAL / CITE SECTIONS */
.law-card{background:#fff;border:1px solid var(--rule);padding:1.3rem 1.5rem;margin-bottom:1rem}
.law-card .law-ref{font-size:11px;text-transform:uppercase;letter-spacing:.1em;color:var(--blue);margin-bottom:.4rem}
.law-card h4{margin-top:0;color:var(--blue)}
.law-card p{font-size:14px;color:var(--ink-mid);margin-bottom:.4rem}

.cite{font-size:12px;color:var(--ink-light);display:block;margin-top:.4rem;line-height:1.5}
.cite a{color:var(--gold);font-size:12px}

/* ASSESSMENT */
.assess-grid{display:grid;grid-template-columns:1fr 1fr;gap:1.5rem;margin:1.5rem 0}
.assess-col h3{font-size:1.2rem;margin-top:0}
.assess-col ul{list-style:none;padding:0;margin:0}
.assess-col ul li{font-size:14px;color:var(--ink-mid);padding:.6rem 0;border-bottom:1px solid var(--paper-dark);display:flex;gap:.7rem;align-items:flex-start}
.assess-col ul li:last-child{border:none}
.assess-col ul li::before{content:'';width:8px;height:8px;min-width:8px;border-radius:50%;margin-top:6px;flex-shrink:0}
.strengths li::before{background:var(--green)}
.challenges li::before{background:var(--danger)}

/* INDUSTRY SECTION */
.industry-card{background:#fff;border:1px solid var(--rule);padding:1.3rem 1.5rem;margin-bottom:1rem;border-left:3px solid var(--gold)}
.industry-card .source{font-size:11px;text-transform:uppercase;letter-spacing:.1em;color:var(--gold);margin-bottom:.4rem}
.industry-card p{font-size:14px;color:var(--ink-mid);margin-bottom:.3rem}

/* POSTS */
.post-card{background:#fff;border:1px solid var(--rule);padding:1.5rem 2rem;margin-bottom:1.3rem;transition:border-color .2s}
.post-card:hover{border-color:var(--gold)}
.post-date{font-size:11px;text-transform:uppercase;letter-spacing:.12em;color:var(--ink-light);margin-bottom:.5rem}
.post-card h3{font-size:1.25rem;margin:0 0 .7rem}
.post-card p{font-size:14px;color:var(--ink-mid);margin-bottom:.5rem}
.tag{display:inline-block;font-size:10px;letter-spacing:.1em;text-transform:uppercase;padding:.2rem .6rem;margin-right:.3rem;margin-top:.5rem}
.tag-red{background:var(--danger-light);color:var(--danger)}
.tag-blue{background:var(--blue-light);color:var(--blue)}
.tag-gold{background:var(--gold-light);color:#7a5c00}
.tag-gray{background:var(--paper-dark);color:var(--ink-light)}

/* VERDICT BOX */
.verdict{background:var(--ink);padding:2.5rem;margin:2rem 0;border-top:4px solid var(--gold)}
.verdict h3{font-family:'Cormorant Garamond',serif;font-size:1.6rem;color:#fff;margin-bottom:1rem;font-weight:600}
.verdict p{color:#b5ada4;font-size:15px;line-height:1.85;margin-bottom:.8rem}
.verdict p:last-child{margin-bottom:0}
.verdict strong{color:var(--gold)}

/* FOOTER */
footer{background:var(--ink);color:#888;padding:3rem 2rem;text-align:center}
footer p{font-size:13px;line-height:1.9;max-width:700px;margin:0 auto}
footer strong{color:#ccc}
.disclaimer{border-top:1px solid #333;margin-top:1.5rem;padding-top:1.5rem;font-size:12px;opacity:.6}

@media(max-width:680px){
  nav ul{display:none}
  .assess-grid{grid-template-columns:1fr}
  .parties-grid{grid-template-columns:1fr}
}
</style>
</head>
<body>

<nav>
  <div class="brand">Portier v. <span>Crown Castle</span></div>
  <ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#documents">Documents</a></li>
    <li><a href="#industry">Industry Context</a></li>
    <li><a href="#legal">Legal Framework</a></li>
    <li><a href="#assessment">Assessment</a></li>
    <li><a href="#updates">Updates</a></li>
  </ul>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="eyebrow">Telecom Easement Fraud Dispute &nbsp;·&nbsp; Wayne County, North Carolina</div>
  <h1>How Crown Castle Used a <em>Fraudulent Contract</em> to Seize a Landowner's Property Rights in Perpetuity</h1>
  <p class="hero-intro">Sidney Lawrence Portier II and his wife Janell Marie Portier of Goldsboro, North Carolina allege that Crown Castle Towers 09 LLC filed a fraudulent Grant of Easement against their property in 2012 — exploiting the absence of telecom legal counsel available to landowners — and that this fraudulent document has since been used to transfer their property rights to American Tower Corporation, without their knowledge or consent, in perpetuity.</p>
  <div class="stat-row">
    <div class="stat"><span class="stat-val">2003</span><span class="stat-lbl">Original Lease</span></div>
    <div class="stat"><span class="stat-val">Dec 2011</span><span class="stat-lbl">Agreement Signed</span></div>
    <div class="stat"><span class="stat-val">Apr 2012</span><span class="stat-lbl">Disputed Filing</span></div>
    <div class="stat"><span class="stat-val">2016–17</span><span class="stat-lbl">Portfolio Deal</span></div>
    <div class="stat"><span class="stat-val">Apr 2018</span><span class="stat-lbl">Assigned Away</span></div>
    <div class="stat"><span class="stat-val">2021</span><span class="stat-lbl">Am. Tower Letter</span></div>
  </div>
</div>

<div class="page-wrap">

<!-- =========================================
     SECTION 1: OVERVIEW
     ========================================= -->
<section id="overview">
  <span class="section-label">Overview</span>
  <h2>What Happened — and Why It Matters</h2>

  <div class="box box-gold">
    <p><strong>The core allegation:</strong> In December 2011, Sidney Portier II signed a letter agreement with Crown Castle Towers 09 LLC for the purchase of a perpetual easement over his Wayne County, North Carolina property for $75,000. The document that was actually filed with the Wayne County Register of Deeds on April 4, 2012, bears a different execution date — March 21, 2012 — and Mr. Portier alleges it contains material irregularities that do not reflect the terms he agreed to. His wife, Janell Marie Portier, was added as a co-Grantor on that recorded document without any corresponding signature or acknowledgment in the original agreement.</p>
  </div>

  <p>The property in question — located at 1720 S. Slocumb Street, Goldsboro, NC (Wayne County), designated as Facility #810076 and site Seymour Johnson NC G/203560 — has hosted cell tower communications infrastructure since at least 2003, when Mr. Portier entered his original PCS Site Agreement with ACW Leasing Company Inc.</p>

  <p>Over the following years, the easement rights changed hands without Mr. Portier's meaningful participation: Crown Castle assigned all rights to Global Tower Assets III, LLC (an American Tower subsidiary) in April 2018 as part of a bulk portfolio exchange involving multiple tower sites nationwide. American Tower's April 5, 2021 response letter to the Portiers' inquiries references only the disputed March 21, 2012 document — confirming that the original December 2011 agreement was never disclosed at any point in the chain of title.</p>

  <p>Mr. Portier contends that Crown Castle deliberately exploited a well-documented vulnerability: in the early 2000s, specialized telecommunications attorneys available to represent landowners in cell tower negotiations were virtually nonexistent. Tower companies, by contrast, deployed large real estate law firms and national title companies to execute these transactions. The result was a structural information and power imbalance that Crown Castle, Mr. Portier alleges, used to its advantage.</p>

  <h3>Timeline of Key Events</h3>
  <div class="timeline">
    <div class="tl-item">
      <div class="tl-date">August 20, 2003</div>
      <h4>Original PCS Site Lease</h4>
      <p>Mr. Portier enters a lease with ACW Leasing Company Inc. for a communications tower site at 1720 S. Slocumb Street. A memorandum is recorded January 13, 2004 in Wayne County Book 2162, Page 827, reflecting Southeast Towers, LLC as successor-in-interest to AGW Leasing Company, Inc.</p>
    </div>
    <div class="tl-item">
      <div class="tl-date">December 14, 2011</div>
      <h4>Original Letter Agreement Presented by Crown Castle</h4>
      <p>Crown Castle Towers 09 LLC presents a letter agreement for a $75,000 perpetual easement purchase, including a $30,000 down payment, 84 monthly installments of $535.71, and a 50% revenue share on any additional easement area. Mr. Portier signs December 16, 2011. Crown Castle's Land Acquisition Manager Douglas E. Bannon signs January 17, 2012.</p>
    </div>
    <div class="tl-item red">
      <div class="tl-date">March 21, 2012 — Disputed Execution Date</div>
      <h4>Disputed Grant of Easement</h4>
      <p>A "Grant of Easement and Assignment of Lease" bearing this execution date is prepared by Parker Poe Adams &amp; Bernstein LLP (Raleigh, NC), a major law firm. Mr. Portier alleges this document was not what he agreed to in December 2011.</p>
    </div>
    <div class="tl-item red">
      <div class="tl-date">April 4, 2012 — Recorded in Wayne County</div>
      <h4>Disputed Document Filed With Register of Deeds</h4>
      <p>Recorded at Book 2920, Page 288–314 by Lois J. Mooring, Register of Deeds. Doc ID: 010682780027. Excise tax of $150 (equivalent to $75,000 consideration under NC law). Title handled by Jamie Trevino, Stewart Title Guaranty – NTS, Houston, TX. Both Sidney Lawrence Portier II and wife Janell Marie Portier are named as Grantors — though Janell does not appear in the original December 2011 letter agreement.</p>
    </div>
    <div class="tl-item blue">
      <div class="tl-date">November 7, 2016 / March 6, 2017</div>
      <h4>Crown Castle and American Tower Enter Bulk Portfolio Exchange</h4>
      <p>Crown Castle Towers 09 LLC and Global Tower Assets III, LLC (American Tower subsidiary) enter a Site Exchange Agreement covering a large portfolio of tower sites. The Portier property at Facility #810076 is one of many assets bundled into this transaction. The Portiers are not notified.</p>
    </div>
    <div class="tl-item blue">
      <div class="tl-date">March 27 / Effective April 30, 2018 — Recorded May 23, 2018</div>
      <h4>Assignment and Assumption of Easement Agreement</h4>
      <p>Crown Castle formally assigns all easement rights to Global Tower Assets III, LLC. Prepared by Babst, Calland, Clements and Zomnir, P.C. (Pittsburgh, PA). Recorded in Wayne County Book 3373, Pages 537–548. The assignment explicitly references the disputed March 21, 2012 document as its legal foundation.</p>
    </div>
    <div class="tl-item">
      <div class="tl-date">April 5, 2021</div>
      <h4>American Tower Responds to Portiers' Inquiries</h4>
      <p>Attorney Christopher Satti (American Tower / US Tower division) responds via FedEx, referencing only the March 21, 2012 document — with no mention of the original December 2011 letter agreement. The letter asserts American Tower holds the easement in perpetuity and reserves all legal rights.</p>
    </div>
  </div>
</section>

<!-- =========================================
     SECTION 2: DOCUMENTS
     ========================================= -->
<section id="documents">
  <span class="section-label">Primary Evidence</span>
  <h2>The Documents — Released Publicly for the First Time</h2>
  <p>Mr. Portier is releasing these documents publicly for the first time. The dates are the key to understanding the sequence of events. Additional supporting documents will be released as this case develops.</p>

  <!-- ORIGINAL AGREEMENT -->
  <div class="doc-card">
    <span class="doc-badge badge-orig">Original Agreement</span>
    <div class="doc-title">Letter of Agreement — PCS Site Easement Purchase</div>
    <div class="doc-meta">December 14, 2011 &nbsp;·&nbsp; Wayne County, North Carolina &nbsp;·&nbsp; Version 12-13-11</div>
    <div class="parties-grid">
      <div>
        <div class="party-lbl">Grantor</div>
        <div class="party-name">Sidney Lawrence Portier II</div>
        <div class="party-detail">Seymour Johnson PCS, Goldsboro, NC 27530<br>Signed: December 16, 2011</div>
      </div>
      <div>
        <div class="party-lbl">Grantee</div>
        <div class="party-name">Crown Castle Towers 09 LLC</div>
        <div class="party-detail">Delaware Limited Liability Company<br>Signed by Douglas E. Bannon, Land Acquisition Mgr: January 17, 2012</div>
      </div>
    </div>
    <div class="terms-row">
      <div class="term-box"><div class="term-val">$75,000</div><div class="term-lbl">Purchase Price</div></div>
      <div class="term-box"><div class="term-val">$30,000</div><div class="term-lbl">Down Payment</div></div>
      <div class="term-box"><div class="term-val">$535.71/mo</div><div class="term-lbl">84 Installments</div></div>
      <div class="term-box"><div class="term-val">50%</div><div class="term-lbl">Revenue Share</div></div>
      <div class="term-box"><div class="term-val">2,000 sq ft</div><div class="term-lbl">Additional Option</div></div>
    </div>
    <div class="doc-quote">"Grantee and Grantor will enter into a Grant of Easement and Assignment of Lease which shall be perpetual and in substantially the form attached as Exhibit A… pursuant to which Grantee will acquire the property from Grantor for a purchase price of Seventy Five Thousand Dollars ($75,000.00)… Grantee shall make a down payment at closing in the amount of Thirty Thousand Dollars ($30,000.00)… Thereafter, Grantee shall pay the Purchase Price in Eighty Four (84) consecutive monthly installments of Five Hundred Thirty Five and 71/100 Dollars ($535.71)…"</div>
    <p style="font-size:13px;color:var(--ink-light)">Schedule 1 (Standard Terms &amp; Conditions) states: the Grant of Easement must be in "Grantee's standard form, <strong>modified to include the terms and conditions of this Agreement.</strong>" This clause is critical — it is the legal requirement that the recorded document reflect the agreed terms.</p>
  </div>

  <!-- DISPUTED FILED DOCUMENT -->
  <div class="doc-card disputed">
    <span class="doc-badge badge-disp">Disputed Filing</span>
    <div class="doc-title">Grant of Easement and Assignment of Lease — Recorded Document</div>
    <div class="doc-meta">Execution date: March 21, 2012 &nbsp;·&nbsp; Recorded: April 4, 2012 &nbsp;·&nbsp; Wayne County Register of Deeds</div>
    <div class="box box-danger" style="margin-top:1rem">
      <p>This is the document Mr. Portier disputes. It carries an execution date of <strong>March 21, 2012</strong> — more than 3 months after the Grantor signed the original letter agreement (December 16, 2011) and more than 2 months after Crown Castle's own representative signed (January 17, 2012). It was prepared by a major Raleigh law firm and processed by a Houston title company. Both Sidney Portier II and his wife Janell Marie Portier are listed as Grantors, though Janell's name does not appear in the original December 2011 agreement as a party.</p>
    </div>
    <div class="stamp-grid">
      <div class="stamp-item"><span>Doc ID</span>010682780027</div>
      <div class="stamp-item"><span>Book / Pages</span>BK 2920, PG 288–314</div>
      <div class="stamp-item"><span>Recorded</span>April 4, 2012 — 10:38 AM</div>
      <div class="stamp-item"><span>Excise Tax / Fee</span>$150.00 / $224.00</div>
      <div class="stamp-item"><span>Recorder</span>Lois J. Mooring, Register of Deeds</div>
      <div class="stamp-item"><span>Facility</span>#810076 · 1720 S. Slocumb St.</div>
      <div class="stamp-item"><span>Prepared by</span>Parker Poe Adams &amp; Bernstein LLP, Raleigh NC</div>
      <div class="stamp-item"><span>Title / Closing</span>Stewart Title Guaranty – NTS, Houston TX</div>
    </div>
    <div class="parties-grid">
      <div>
        <div class="party-lbl">Grantor (as named in disputed filing)</div>
        <div class="party-name">Sidney Lawrence Portier II</div>
        <div class="party-detail">AND wife, Janell Marie Portier<br>a/k/a Janelle Marie Portier<br><em style="color:var(--danger)">Note: Janell does not appear in the original December 2011 agreement</em></div>
      </div>
      <div>
        <div class="party-lbl">Grantee</div>
        <div class="party-name">Crown Castle Towers 09 LLC</div>
        <div class="party-detail">Delaware Limited Liability Company</div>
      </div>
    </div>
  </div>

  <!-- ASSIGNMENT DOCUMENT -->
  <div class="doc-card corp">
    <span class="doc-badge badge-corp">2018 Assignment</span>
    <div class="doc-title">Assignment and Assumption of Easement Agreement</div>
    <div class="doc-meta">Made March 27, 2018 · Effective April 30, 2018 · Recorded May 23, 2018 · Wayne County BK 3373, PG 537–548</div>
    <div class="box box-blue" style="margin-top:1rem">
      <p>This is the document by which Crown Castle transferred all easement rights to American Tower (via Global Tower Assets III, LLC) as part of a bulk corporate portfolio exchange. The assignment cites the disputed March 21, 2012 document as the entire legal basis for the transfer. The Portier property at Facility #810076 is identified only by a site number in the document's footer — one of many sites bundled in the exchange. No individual review of whether any underlying easement was legitimately obtained was performed.</p>
    </div>
    <div class="stamp-grid">
      <div class="stamp-item"><span>Book / Pages</span>BK 3373, PG 537–548</div>
      <div class="stamp-item"><span>Recorded</span>May 23, 2018 — 3:54 PM</div>
      <div class="stamp-item"><span>Pages / Fee</span>12 pages · $26.00</div>
      <div class="stamp-item"><span>Recorder</span>Judy Harrison, Register of Deeds</div>
      <div class="stamp-item"><span>Prepared by</span>Babst, Calland, Clements &amp; Zomnir P.C., Pittsburgh PA</div>
      <div class="stamp-item"><span>Submitted by</span>Solidifi Title and Closing LLC</div>
    </div>
    <div class="parties-grid">
      <div>
        <div class="party-lbl">Assignor</div>
        <div class="party-name">Crown Castle Towers 09 LLC</div>
        <div class="party-detail">c/o Crown Castle International Corp.<br>1220 Augusta Drive, Suite 600, Houston TX 77057</div>
      </div>
      <div>
        <div class="party-lbl">Assignee</div>
        <div class="party-name">Global Tower Assets III, LLC</div>
        <div class="party-detail">American Tower subsidiary<br>10 Presidential Way, Woburn MA 01801<br>Attn: Shawn Lanier, VP Legal</div>
      </div>
    </div>
    <div class="doc-quote">"WHEREAS, Assignor and Sidney Lawrence Portier, II and wife, Janell Marie Portier… entered into that certain Grant of Easement and Assignment of Lease dated March 21, 2012, and recorded on April 4, 2012, with the records of Wayne County, North Carolina in Book 2920, Page 288…"</div>
    <p style="font-size:13px;color:var(--ink-light)">The underlying exchange was governed by a Site Exchange Agreement dated November 7, 2016, amended March 6, 2017 — a large portfolio transaction affecting many tower sites. Governing law: State of New York.</p>
  </div>

  <!-- AMERICAN TOWER LETTER -->
  <div class="doc-card">
    <span class="doc-badge badge-atc">Am. Tower Letter</span>
    <div class="doc-title">Response Letter — American Tower Corporation</div>
    <div class="doc-meta">April 5, 2021 · Via FedEx · Site: Seymour Johnson NC G/203560 · Signed: Christopher Satti, Attorney, US Tower</div>
    <div class="parties-grid">
      <div>
        <div class="party-lbl">Addressed To</div>
        <div class="party-name">Sidney Lawrence Portier II &amp; Janell Marie Portier</div>
        <div class="party-detail">700 Isler St., Goldsboro, NC 27530</div>
      </div>
      <div>
        <div class="party-lbl">From</div>
        <div class="party-name">American Tower Corporation</div>
        <div class="party-detail">Christopher Satti, Attorney, US Tower<br>+1.781.926.4600 · Christopher.Satti@americantower.com</div>
      </div>
    </div>
    <div class="doc-quote">"Grantor granted Crown Castle the Easement on March 21, 2012… Per the Assignment Agreement, effective April 30, 2018, Crown Castle assigned, and American Tower assumed, all its rights, titles, and interests in the Easement to American Tower… The Easement is perpetual. The Easement was assigned to American Tower per the Assignment Agreement. Thus, American Tower enjoys the Easement and Easement Rights in perpetuity."</div>
    <div class="box box-gold" style="margin-top:.8rem;margin-bottom:0">
      <p><strong>Why this letter is critical evidence:</strong> The letter references the easement only as "dated March 21, 2012." There is no mention — anywhere in the letter — of the original December 2011 letter agreement between Mr. Portier and Crown Castle. This confirms that American Tower accepted the disputed 2012 filing as the complete and unqualified basis for its title, having never been informed of the original agreement's existence. The letter also includes a broad reservation of rights: "This letter is written without waiver of and/or prejudice to any of Grantee's rights, remedies, defenses."</p>
    </div>
  </div>

  <h3>Chain of Title — Site #810076</h3>
  <p style="font-size:14px;color:var(--ink-mid);margin-bottom:1rem">Every transfer of easement rights since 2012 is founded entirely on the disputed filing. The original December 2011 agreement does not appear anywhere in the recorded chain.</p>
  <div class="chain">
    <div class="chain-node"><div><div class="chain-name">ACW Leasing Company Inc. / Southeast Towers LLC</div><div class="chain-detail">Original tenant (2003) · Southeast Towers LLC recorded as successor Jan. 13, 2004 — BK 2162, PG 827</div></div><div class="chain-date">2003–2004<br>Original lease</div></div>
    <div class="chain-arrow">↓</div>
    <div class="chain-node n-disputed"><div><div class="chain-name">Crown Castle Towers 09 LLC</div><div class="chain-detail">Acquires easement via disputed Grant of Easement filed BK 2920, PG 288 — prepared by Parker Poe Adams &amp; Bernstein LLP (Raleigh)</div></div><div class="chain-date" style="color:var(--danger)">Recorded<br>April 4, 2012</div></div>
    <div class="chain-arrow">↓</div>
    <div class="chain-node n-corp"><div><div class="chain-name">Global Tower Assets III, LLC (American Tower)</div><div class="chain-detail">Receives assignment via bulk portfolio Site Exchange Agreement · Recorded BK 3373, PG 537 · Prepared by Babst Calland (Pittsburgh)</div></div><div class="chain-date" style="color:var(--blue)">Effective<br>April 30, 2018</div></div>
    <div class="chain-arrow">↓</div>
    <div class="chain-node n-current"><div><div class="chain-name">American Tower Corporation</div><div class="chain-detail">Current holder — asserts perpetual easement rights in April 2021 letter · Has no knowledge of the December 2011 original agreement</div></div><div class="chain-date" style="color:var(--green)">Current<br>Holder</div></div>
  </div>

  <h3>Documented Irregularities</h3>
  <ul class="flag-list">
    <li><span class="flag-icon">!</span><span>The disputed Grant of Easement bears an execution date of March 21, 2012 — more than 3 months after Mr. Portier signed the original letter agreement on December 16, 2011, and more than 2 months after Crown Castle's own representative signed on January 17, 2012.</span></li>
    <li><span class="flag-icon">!</span><span>The original letter agreement names only Sidney Lawrence Portier II as Grantor. The recorded deed names both Mr. Portier and his wife Janell Marie Portier as Grantors — with no corresponding document establishing when, how, or under what circumstances she was added.</span></li>
    <li><span class="flag-icon">!</span><span>The disputed document was prepared by Parker Poe Adams &amp; Bernstein LLP (a major Raleigh law firm) with title services by Stewart Title Guaranty (Houston, TX) — significant institutional legal resources that the Portiers had no counterpart to. No telecom attorney represented the Portiers at any stage.</span></li>
    <li><span class="flag-icon">!</span><span>The original letter agreement's Schedule 1 explicitly required the Grant of Easement to be "modified to include the terms and conditions of this Agreement." Whether that modification was actually made in the recorded document has not yet been publicly verified through a side-by-side comparison.</span></li>
    <li><span class="flag-icon">!</span><span>American Tower's April 2021 letter confirms they had no knowledge of the December 2011 agreement — meaning the disputed 2012 document was the sole basis of title through two major corporate transactions and the work of multiple law firms, none of whom identified or disclosed the original agreement.</span></li>
    <li><span class="flag-icon">!</span><span>The Portier property was transferred to American Tower as part of a bulk portfolio exchange (Site Exchange Agreement, 2016–2017) without individual due diligence on whether the underlying easement at this specific site was legitimately obtained. The Portiers were not notified of this transfer.</span></li>
    <li><span class="flag-icon">!</span><span>Additional specific irregularities within the text of the disputed contract have been identified by Mr. Portier and will be disclosed in subsequent document releases.</span></li>
  </ul>
</section>

<!-- =========================================
     SECTION 3: INDUSTRY CONTEXT
     ========================================= -->
<section id="industry">
  <span class="section-label">Industry Context</span>
  <h2>Tower Companies and Landowners: A Well-Documented Power Imbalance</h2>

  <p>The Portier dispute does not exist in a vacuum. It reflects a pattern of conduct that cell tower industry experts, attorneys, and advocates have documented extensively for decades. Understanding the industry context is essential to evaluating the plausibility of Mr. Portier's account.</p>

  <h3>Tower Companies Know Landowners Are Outmatched</h3>

  <div class="industry-card">
    <div class="source">Steel In The Air — Cell Tower Lease Consultants</div>
    <p>Industry consultant Steel in the Air warns landowners that tower companies structurally exploit the information gap: <em>"Tower companies know that landowners typically aren't sophisticated enough to be able to know the average lease rate in the area and then know how to equate it to the prepayment offer. If they contact enough property owners, it is more than likely that one of them will accept."</em></p>
    <p>The same source notes that perpetual easement offers — exactly the type obtained by Crown Castle here — are inherently and structurally disadvantageous to landowners: once signed, the easement runs with the land indefinitely, regardless of future property values, tenant additions, or changes in the telecommunications market.</p>
    <span class="cite">Source: Steel In The Air, "Prepaid Cell Tower Leases and Easements — What to Watch Out For" · <a href="https://www.steelintheair.com/blog/prepaid-cell-tower-lease/" target="_blank">steelintheair.com</a></span>
  </div>

  <div class="industry-card">
    <div class="source">Tower Genius — Cell Tower Lease Specialists</div>
    <p>Tower Genius, a firm that advises landowners in tower negotiations, describes the structural lopsidedness directly: <em>"Cell tower rental agreements are lopsided and heavily favor the wireless carrier or cell tower management company."</em> The firm further notes that tower companies regularly pressure landlords for rent reductions years after signing, "forgetting the lease agreement they just signed five or ten years earlier."</p>
    <span class="cite">Source: Tower Genius, "Cell Tower Lease Guide" · <a href="https://www.towergenius.com/cell-tower-lease-guide/" target="_blank">towergenius.com</a></span>
  </div>

  <div class="industry-card">
    <div class="source">Vertical Consultants — Cell Tower Lease Experts</div>
    <p>Vertical Consultants, which represents landowners in buyout negotiations, explains why tower companies push hard for perpetual easements: <em>"The reason cell tower tenants are pushing to buy out their own cell tower agreements is so the tenant can secure long-term rights to your property and enjoy the additional security that comes with it, as well as to create a means to prevent landowners from selling their rental streams to third-party acquisition companies."</em> Critically, the firm warns that initial buyout offers are always below actual site value and that a few phone calls could net additional tens of thousands of dollars — value most unrepresented landowners never capture.</p>
    <span class="cite">Source: Vertical Consultants, "Lease Buyouts and Easements: 3 Things to Consider" · <a href="https://www.celltowerleaseexperts.com/cell-tower-lease-news/lease-buyouts-and-easements-3-things-to-consider/" target="_blank">celltowerleaseexperts.com</a></span>
  </div>

  <div class="industry-card">
    <div class="source">Steel In The Air — Consent and Assignment Practices</div>
    <p>A separate advisory from Steel in the Air specifically warns landowners about Crown Castle's practice of seeking to remove consent provisions before making assignments: <em>"What Crown Castle has attempted to do… is basically remove the consent provision entirely."</em> The firm warns that tower companies routinely try to slip assignment-without-compensation provisions past landowners — and that "granting future consent defeats the entire purpose of having that language in the lease."</p>
    <span class="cite">Source: Steel In The Air, "Do Not Give Future Consent to Crown Castle (or Any Tower Company)" · <a href="https://www.steelintheair.com/blog/do-not-give-future-consent-to-crown-castle-or-any-tower-company/" target="_blank">steelintheair.com</a></span>
  </div>

  <div class="industry-card">
    <div class="source">Cell Tower Attorney — Landowner Property Rights</div>
    <p>A cell tower attorney's practice newsletter documents a pattern directly analogous to the Portier situation: <em>"Many unknowing landowners assume incorrectly that the cell phone company has the right to use their property… We suspect, however, that in many instances, the cell phone company does not have such rights and will only negotiate with a landowner when it is brought to their attention."</em> The attorney's firm notes this type of scenario is "happening frequently throughout the country."</p>
    <span class="cite">Source: Cell Tower Attorney, "Landowners' Property and Utility Company Easements" · <a href="http://www.celltowerattorney.com/news/2009/02/landowners-property-and-utility-company.html" target="_blank">celltowerattorney.com</a></span>
  </div>

  <div class="industry-card">
    <div class="source">Crown Castle in Litigation — A Pattern of Disputes</div>
    <p>Crown Castle has faced legal disputes over easement agreement terms in multiple jurisdictions. In a 2024 case before the Florida Supreme Court, a court ruled that Crown Castle was a party to and bound by an easement agreement as successor-in-interest to the original grantor — and that it had breached that agreement. The court explicitly rejected Crown Castle's argument that it was not bound as a non-signatory: <em>"It held, as a matter of law, that Crown Castle was a successor-in-interest to BellSouth and that it breached the Easement Agreement."</em></p>
    <span class="cite">Source: Florida Supreme Court, Case No. SC2024-0547, RJI v. Crown Castle (2024) · <a href="https://acis-api.flcourts.gov/courts/68f021c4-6a44-4735-9a76-5360b2e8af13/cms/case/0c6dc94b-07f5-44cc-8934-04c32945e870/docketentrydocuments/78c6a778-9961-4efe-a064-68caf5339d6e" target="_blank">Florida Courts</a></span>
  </div>

  <div class="box box-blue">
    <p><strong>Key takeaway:</strong> The pattern documented across the industry — uninformed landowners, lopsided agreements, perpetual easements, bulk corporate transfers — is not a theoretical concern. It is a well-documented business practice. Mr. Portier's account, supported by the documents released here, is consistent with what cell tower industry experts have described as common practice for decades.</p>
  </div>
</section>

<!-- =========================================
     SECTION 4: LEGAL FRAMEWORK
     ========================================= -->
<section id="legal">
  <span class="section-label">Legal Framework</span>
  <h2>Applicable North Carolina Law</h2>
  <p>The following legal framework applies to the Portier dispute under North Carolina law. This is informational only — not legal advice. Mr. Portier should consult a North Carolina real property attorney.</p>

  <div class="law-card">
    <div class="law-ref">N.C. Gen. Stat. § 1-52(9) — Fraud Statute of Limitations</div>
    <h4>The Clock Starts at Discovery, Not at Signing</h4>
    <p>Under North Carolina law, a fraud claim must be filed within three years — but critically, <em>"the cause of action shall not be deemed to have accrued until the discovery by the aggrieved party of the facts constituting the fraud or mistake."</em> This is known as the discovery rule. For constructive fraud, a 2013 amendment to the statute confirmed that "discovery" means <strong>actual discovery</strong> — not when the fraud theoretically could have been discovered.</p>
    <p>This means the three-year window for Mr. Portier's fraud claim begins from when he actually discovered the irregularities — not from when the deed was recorded in 2012. The question of when discovery occurred is a fact question for the jury, per NC Pattern Jury Instruction 800.00A, which cites <em>Hudson v. Game World, Inc.</em>, 126 N.C. App. 139 (1997).</p>
    <span class="cite">Sources: N.C. Gen. Stat. § 1-52(9) · <a href="https://codes.findlaw.com/nc/chapter-1-civil-procedure/nc-gen-st-sect-1-52.html" target="_blank">FindLaw</a> &nbsp;·&nbsp; NC Pattern Jury Instruction 800.00A · <a href="https://www.sog.unc.edu/sites/default/files/pji-master/c/c800.00A%20Fraud%E2%80%94Statute%20of%20Limitations%20%5B5-2016%5D.pdf" target="_blank">UNC School of Government</a> &nbsp;·&nbsp; Constructive Fraud Amendment, NC Legislative Reporting Service · <a href="https://lrs.sog.unc.edu/bill/constructive-fraudlimitations-period" target="_blank">lrs.sog.unc.edu</a></span>
  </div>

  <div class="law-card">
    <div class="law-ref">N.C. Gen. Stat. § 41-10 — Quiet Title Action</div>
    <h4>Removing the Cloud on Title</h4>
    <p>North Carolina law provides a mechanism to challenge a fraudulent or materially altered recorded instrument through a quiet title action filed in the Superior Court of the county where the land is located — in this case, Wayne County Superior Court. Under NC law: <em>"Forged or materially altered deeds are void and convey nothing; fraud‑induced deeds are voidable and can be cancelled by judgment."</em> If the deed was materially different from what Mr. Portier agreed to, a court could declare the easement void, cancel it in the Register of Deeds, and restore the Portiers' full property rights.</p>
    <p>A lis pendens (notice of pending litigation) can be recorded with the Register of Deeds to put all parties — including American Tower — on notice of the dispute and prevent further transfers.</p>
    <span class="cite">Sources: N.C. Gen. Stat. § 41-10 · Pierce Law Group, "Quiet Title Actions in NC" · <a href="https://piercelaw.com/news/real-estate-qa-series/how-can-i-prove-fraud-in-my-quiet-title-action-and-clear-the-property-title/" target="_blank">piercelaw.com</a> &nbsp;·&nbsp; Anderson Legal, "Guide to Quiet Title Actions in NC" · <a href="https://www.andersonlegalnc.com/a-guide-to-quiet-title-actions-in-north-carolina/" target="_blank">andersonlegalnc.com</a></span>
  </div>

  <div class="law-card">
    <div class="law-ref">N.C. Gen. Stat. § 75-1.1 — Unfair and Deceptive Trade Practices Act (UDTPA)</div>
    <h4>Treble Damages for Fraud in Commerce</h4>
    <p>North Carolina's UDTPA declares unlawful <em>"unfair methods of competition in or affecting commerce, and unfair or deceptive acts or practices in or affecting commerce."</em> The statute is powerful for several reasons: (1) <strong>fraud in the inducement qualifies as a UDTPA violation</strong>; (2) a violation results in <strong>automatic treble (triple) damages</strong>; and (3) the statute allows recovery of attorneys' fees. Under NC case law, <em>"fraud is sufficient evidence of an unfair or deceptive act, including fraud in the inducement."</em> The statute has been applied liberally by NC courts and is "one of the most important causes of action under North Carolina law."</p>
    <span class="cite">Sources: N.C. Gen. Stat. § 75-1.1 · Wikibooks, "UDTPA Under North Carolina Law" · <a href="https://en.wikibooks.org/wiki/N.C._Gen._Stat_%C2%A7_75-1.1:_Unfair_&_Deceptive_Trade_Practices_Under_North_Carolina_Law" target="_blank">wikibooks.org</a> &nbsp;·&nbsp; Ellis &amp; Winters, "Defining Unfairness in Unfair Trade Practices" · <a href="https://www.elliswinters.com/wp-content/uploads/2020/02/75-1-1_final_sept6.pdf" target="_blank">elliswinters.com</a></span>
  </div>

  <div class="law-card">
    <div class="law-ref">N.C. Gen. Stat. § 1-253 / § 1A-1, Rule 9(b) — Declaratory Judgment / Pleading Fraud</div>
    <h4>Declaring Rights and Pleading Requirements</h4>
    <p>A declaratory judgment action allows a court to formally declare the rights of the parties — in this case, declaring whether the perpetual easement recorded in 2012 is valid or void. North Carolina also requires that fraud be <strong>pleaded with particularity</strong>: the "who, what, when, where, and how" of the alleged fraud must be stated specifically in any complaint. This requirement underscores why Mr. Portier's document release strategy is significant — each document he releases builds the specific factual record that particularity pleading would require.</p>
    <span class="cite">Sources: N.C. Gen. Stat. § 1-253 (Declaratory Judgments) · Rule 9(b), N.C. Rules of Civil Procedure · Pierce Law Group · <a href="https://piercelaw.com/news/real-estate-qa-series/how-can-i-prove-fraud-in-my-quiet-title-action-and-clear-the-property-title/" target="_blank">piercelaw.com</a></span>
  </div>

  <div class="box box-gold">
    <p><strong>North Carolina's pure race recording rule (NCGS § 47-18)</strong> generally protects the first party to record — giving Crown Castle's 2012 filing a legal presumption of validity. However, this protection does not apply when fraud is proven. A court that finds the 2012 deed was fraudulently induced or materially altered can cancel the instrument and quiet title regardless of when it was recorded.</p>
    <span class="cite">Source: Pierce Law Group, "How Can I Prove Fraud in My Quiet Title Action?" · <a href="https://piercelaw.com/news/real-estate-qa-series/how-can-i-prove-fraud-in-my-quiet-title-action-and-clear-the-property-title/" target="_blank">piercelaw.com</a></span>
  </div>
</section>

<!-- =========================================
     SECTION 5: CASE ASSESSMENT
     ========================================= -->
<section id="assessment">
  <span class="section-label">Case Assessment</span>
  <h2>Analysis: Does the Evidence Support the Dispute?</h2>

  <p>The following assessment is based <strong>solely on the documents provided</strong> and publicly available legal research. It is not legal advice. For a definitive legal assessment, Mr. Portier should consult a North Carolina real property and telecommunications attorney.</p>

  <div class="assess-grid">
    <div class="assess-col">
      <div class="box box-green" style="padding:1rem 1.3rem;margin-bottom:1rem">
        <h3 style="font-size:1.2rem;margin-bottom:.5rem;color:var(--green)">Strengths of the Claim</h3>
      </div>
      <ul class="strengths">
        <li><span><strong>Two documents, two dates.</strong> A binding letter agreement was fully executed by January 17, 2012. A different document with a March 21, 2012 execution date was recorded months later. This gap is factual and documented — not merely alleged.</span></li>
        <li><span><strong>Janell Portier's addition is unexplained.</strong> She is not a party in the original December 2011 agreement. Her appearance as co-Grantor on the recorded deed — without any documented acknowledgment of the terms — is a genuine irregularity in the paper record.</span></li>
        <li><span><strong>The "modified to include" clause.</strong> Schedule 1 explicitly required the final Grant to incorporate the letter agreement's terms. Any material departure from those terms is a potential breach and grounds for fraud or reformation.</span></li>
        <li><span><strong>American Tower corroborates.</strong> Their April 5, 2021 letter confirms they received no disclosure of the original December 2011 agreement. This supports Mr. Portier's claim that the 2012 filing obscured the true terms from all subsequent parties.</span></li>
        <li><span><strong>Discovery rule applies.</strong> Under NCGS § 1-52(9), the fraud limitations period doesn't begin until actual discovery — a question for the jury, not the court. The timeline of Mr. Portier's inquiry and the 2021 response letter may be significant in establishing the discovery date.</span></li>
        <li><span><strong>UDTPA provides powerful remedies.</strong> If fraud in the inducement is established, North Carolina's UDTPA mandates automatic treble damages and attorney's fees — making this case potentially economically viable for a plaintiff's attorney to take on contingency.</span></li>
        <li><span><strong>Industry pattern supports plausibility.</strong> Multiple independent cell tower industry experts document that tower companies systematically exploit unrepresented landowners using exactly the structural advantages Crown Castle possessed here.</span></li>
      </ul>
    </div>
    <div class="assess-col">
      <div class="box box-danger" style="padding:1rem 1.3rem;margin-bottom:1rem">
        <h3 style="font-size:1.2rem;margin-bottom:.5rem;color:var(--danger)">Significant Challenges</h3>
      </div>
      <ul class="challenges">
        <li><span><strong>Statute of limitations is the most serious obstacle.</strong> The deed was recorded April 4, 2012 — over 13 years ago. Even under the discovery rule, Mr. Portier would need to establish a specific date of discovery within 3 years of filing any action. The 2021 American Tower letter may anchor that timeline, but its sufficiency is a legal question.</span></li>
        <li><span><strong>Signed, recorded deed carries a strong presumption of validity.</strong> Under North Carolina law, a notarized, signed, and recorded instrument is presumptively valid. Overcoming this requires clear and convincing evidence — a high standard.</span></li>
        <li><span><strong>Good-faith purchaser doctrine.</strong> American Tower acquired the easement through an assignment recorded in 2018 — years after the original 2012 filing. As a good-faith purchaser in the chain of title, American Tower may have additional legal protections even if the original easement is found defective. This complicates, though does not necessarily defeat, any quiet title action.</span></li>
        <li><span><strong>Specific irregularities not yet disclosed.</strong> Mr. Portier states the contract contains specific textual irregularities that have not been fully made public. Without a side-by-side comparison of the letter agreement and the recorded Grant, the core of the fraud claim cannot be fully evaluated from the available documents.</span></li>
        <li><span><strong>North Carolina's race recording statute.</strong> NCGS § 47-18 generally protects first-to-record parties. While fraud overrides this, establishing fraud in a 13-year-old transaction against a well-resourced corporate defendant will require a well-organized evidentiary record and experienced litigation counsel.</span></li>
      </ul>
    </div>
  </div>

  <div class="verdict">
    <h3>Overall Assessment</h3>
    <p>Based on the documents provided and applicable North Carolina law, <strong>the Portier dispute has a legitimate and documentable factual foundation.</strong> The two-document, two-date structure is real. The addition of Janell Marie Portier as co-Grantor without documentation in the original agreement is a genuine irregularity. The American Tower letter independently corroborates that the original 2011 terms were never disclosed in the chain of title. And the industry context makes the alleged mechanism of exploitation — a major law firm and title company on one side, an unrepresented landowner on the other — both plausible and consistent with documented patterns.</p>
    <p>This is <strong>not a frivolous claim.</strong> However, whether it rises to an actionable legal case today depends primarily on two factors the documents alone cannot fully resolve: (1) a line-by-line comparison of the letter agreement and the recorded Grant of Easement — which either will or will not confirm that the terms were materially altered; and (2) a statute of limitations analysis by experienced NC counsel, focused specifically on when discovery of the fraud actually occurred.</p>
    <p>The strongest immediate action is retaining a North Carolina real property attorney — ideally one with telecommunications law experience — to review all documents, conduct a title search, and evaluate whether a quiet title action with UDTPA claims should be filed in Wayne County Superior Court. A lis pendens filed with the Register of Deeds would immediately put all parties on notice and preserve the Portiers' rights pending litigation.</p>
    <p style="font-size:13px;color:#888;margin-top:1rem;border-top:1px solid #333;padding-top:1rem"><em>Note: This assessment is document-based and informational only. It does not constitute legal advice. Nothing here should be relied upon as a substitute for consultation with a licensed North Carolina attorney.</em></p>
  </div>
</section>

<!-- =========================================
     SECTION 6: UPDATES / POSTS
     ========================================= -->
<section id="updates">
  <span class="section-label">Updates</span>
  <h2>Posts &amp; New Developments</h2>
  <p style="font-size:14px;color:var(--ink-mid);margin-bottom:2rem">Follow this section for new document releases and case developments as Mr. Portier continues to make his records public.</p>

  <div class="post-card">
    <div class="post-date">May 16, 2026</div>
    <h3>Assignment Documents Released: How the Fraud Traveled Through the Corporate Chain</h3>
    <p>The Assignment and Assumption of Easement Agreement (BK 3373, PG 537–548) is released today, revealing that Crown Castle transferred easement rights to American Tower's subsidiary Global Tower Assets III, LLC on April 30, 2018 — as part of a bulk portfolio exchange covering many tower sites. The assignment was recorded May 23, 2018 and was prepared by Pittsburgh law firm Babst, Calland, Clements and Zomnir, P.C.</p>
    <p>Critically, the assignment document cites the disputed March 21, 2012 Grant of Easement as its entire legal foundation. The Portier property at Facility #810076 is identified only by a site number in the document footer — confirming it was one asset among many in a portfolio deal, with no individual due diligence performed on whether the underlying easement was legitimately obtained.</p>
    <span class="tag tag-blue">Assignment Documents</span><span class="tag tag-red">Key Evidence</span>
  </div>

  <div class="post-card">
    <div class="post-date">May 16, 2026</div>
    <h3>Original 2011 Agreement &amp; Disputed 2012 Deed Released for the First Time</h3>
    <p>Sidney Portier II makes public for the first time the original December 14, 2011 letter agreement he signed with Crown Castle, alongside the disputed Grant of Easement recorded April 4, 2012. The dates are the story: Mr. Portier signed in December 2011; what was ultimately filed carries a March 2012 execution date and was prepared by a major Raleigh law firm. Both documents are now in the public record for review.</p>
    <p>Mr. Portier notes that both he and his wife's signatures appear on the disputed contract, but states this was possible only because no telecom attorneys existed to represent landowners at the time — a vulnerability Crown Castle is alleged to have deliberately exploited.</p>
    <span class="tag tag-red">Document Release</span><span class="tag tag-gold">First Public Release</span>
  </div>

  <div class="post-card">
    <div class="post-date">April 5, 2021</div>
    <h3>American Tower Attorney's Letter: No Knowledge of the Original Agreement</h3>
    <p>A letter from Christopher Satti, Attorney at American Tower Corporation (US Tower division), responding to the Portiers' inquiries via FedEx, references the easement exclusively as "dated March 21, 2012" — with no mention of the December 2011 letter agreement. The letter asserts the easement is perpetual, that American Tower holds it in perpetuity, and closes with a full reservation of Grantee's rights. Attachments included the easement and the assignment agreement.</p>
    <p>This letter is significant because it confirms that the original agreement Mr. Portier signed was never disclosed to American Tower — the current holder — at any point in the chain of title.</p>
    <span class="tag tag-gold">American Tower</span><span class="tag tag-red">Corroborating Evidence</span>
  </div>

  <div class="post-card">
    <div class="post-date">Ongoing</div>
    <h3>Additional Documents and Evidence to Be Released</h3>
    <p>Mr. Portier has confirmed that many additional documents exist that further establish the fraudulence of the 2012 contract filing. Specific textual irregularities within the disputed Grant of Easement have not yet been disclosed publicly. These will be released in forthcoming posts as the public case is built out.</p>
    <span class="tag tag-gray">Upcoming</span>
  </div>
</section>

</div><!-- end page-wrap -->

<footer>
  <p><strong>Portier v. Crown Castle — Public Disclosure</strong><br>
  This site presents the documented account and supporting evidence of Sidney Lawrence Portier II and Janell Marie Portier regarding their dispute over a telecommunications easement on property located at 1720 S. Slocumb Street, Wayne County, North Carolina (Facility #810076 / Site Seymour Johnson NC G/203560).</p>
  <div class="disclaimer">
    All factual claims on this site are based on documents released by the property owners and publicly available records. Legal analysis references publicly available statutes and case law. Nothing on this site constitutes legal advice. External sources are cited for informational context only. Additional documentation will be published as the case develops.
  </div>
</footer>

</body>
</html>
