<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>VaultFlow — Finance & Creator Operations Demo</title>
<meta name="description" content="VaultFlow is a fictional finance operations dashboard demo inspired by modern exchange, payout, banking and analytics interfaces.">
<script src="https://cdn.tailwindcss.com"></script>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
<style>
:root{--ink:#101828;--muted:#667085;--line:#e5e7eb;--bg:#f7f8fa;--blue:#2563eb;--purple:#4f46e5;--green:#039855;--orange:#f79009}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:var(--bg);color:var(--ink);font-family:Inter,Arial,sans-serif}
button,input,select{font:inherit}.mono{font-family:"JetBrains Mono",monospace}.app{min-height:100vh}.sidebar{position:fixed;left:0;top:0;bottom:0;width:250px;background:#fff;border-right:1px solid var(--line);z-index:30}.main{margin-left:250px}.topbar{height:72px;background:#fff;border-bottom:1px solid var(--line);position:sticky;top:0;z-index:20}
.navitem{display:flex;align-items:center;gap:13px;padding:11px 15px;margin:3px 10px;border-radius:10px;color:#667085;font-size:14px;cursor:pointer}.navitem:hover,.navitem.active{background:#eef4ff;color:#2457d6;font-weight:600}.navitem i{width:18px;text-align:center}.card{background:#fff;border:1px solid var(--line);border-radius:12px}.soft{background:#f8fafc}.btn{transition:.18s}.btn:hover{transform:translateY(-1px)}.tab{border-bottom:2px solid transparent}.tab.active{color:#2457d6;border-color:#2457d6}.pill{border-radius:999px}.table-row{border-top:1px solid #edf0f3}.modal{display:none}.modal.show{display:flex}.toast{transform:translateY(20px);opacity:0;pointer-events:none;transition:.25s}.toast.show{transform:translateY(0);opacity:1;pointer-events:auto}
@media(max-width:950px){.sidebar{width:76px}.sidebar .brandtext,.sidebar .navlabel,.sidebar .accounttext{display:none}.navitem{justify-content:center}.main{margin-left:76px}}
@media(max-width:650px){.sidebar{display:none}.main{margin-left:0}.top-actions .hide-sm{display:none}.grid4{grid-template-columns:1fr 1fr!important}.grid2{grid-template-columns:1fr!important}.table-wrap{overflow:auto}.hero-number{font-size:34px!important}}
</style>
</head>
<body>
<div class="app">

<aside class="sidebar">
  <div class="h-[72px] border-b flex items-center px-5 gap-3">
    <div class="w-9 h-9 rounded-xl bg-gradient-to-br from-blue-600 to-indigo-600 text-white grid place-items-center"><i class="fa-solid fa-layer-group"></i></div>
    <div class="brandtext"><div class="font-extrabold tracking-tight">VaultFlow</div><div class="text-[10px] text-slate-400 mono">DEMO PLATFORM</div></div>
  </div>
  <div class="px-3 py-5">
    <div class="text-[10px] uppercase tracking-widest text-slate-400 px-4 mb-2">Workspace</div>
    <div class="navitem active" data-section="dashboard"><i class="fa-solid fa-grid-2"></i><span class="navlabel">Dashboard</span></div>
    <div class="navitem" data-section="payments"><i class="fa-solid fa-arrow-right-arrow-left"></i><span class="navlabel">Payments</span></div>
    <div class="navitem" data-section="proof"><i class="fa-solid fa-receipt"></i><span class="navlabel">Payment Proof</span></div>
    <div class="navitem" data-section="payouts"><i class="fa-solid fa-money-bill-transfer"></i><span class="navlabel">Payout Rates</span></div>
    <div class="navitem" data-section="banking"><i class="fa-solid fa-building-columns"></i><span class="navlabel">Banking</span></div>
    <div class="navitem" data-section="analytics"><i class="fa-solid fa-chart-line"></i><span class="navlabel">Analytics</span></div>
    <div class="navitem" data-section="customers"><i class="fa-solid fa-users"></i><span class="navlabel">Customers</span></div>
    <div class="navitem" data-section="settings"><i class="fa-solid fa-gear"></i><span class="navlabel">Settings</span></div>
    <div class="text-[10px] uppercase tracking-widest text-slate-400 px-4 mb-2 mt-7">Tools</div>
    <div class="navitem" data-section="reports"><i class="fa-solid fa-file-invoice"></i><span class="navlabel">Reports</span></div>
    <div class="navitem" data-section="api"><i class="fa-solid fa-code"></i><span class="navlabel">API Center</span></div>
  </div>
  <div class="absolute bottom-0 left-0 right-0 p-3 border-t">
    <div class="navitem"><div class="w-8 h-8 rounded-full bg-indigo-100 text-indigo-700 grid place-items-center text-xs font-bold">VF</div><div class="accounttext"><div class="text-xs font-semibold text-slate-800">Demo Workspace</div><div class="text-[10px] text-slate-400">demo@example.test</div></div></div>
  </div>
</aside>

<div class="main">
<header class="topbar flex items-center justify-between px-5 lg:px-8">
  <div class="flex items-center gap-3">
    <button id="sideToggle" class="w-9 h-9 rounded-lg border border-slate-200 hover:bg-slate-50"><i class="fa-solid fa-bars text-slate-500"></i></button>
    <div><div id="pageTitle" class="font-bold text-slate-800">Dashboard</div><div class="text-[11px] text-slate-400">Workspace / <span id="crumb">Overview</span></div></div>
  </div>
  <div class="top-actions flex items-center gap-2">
    <div class="hide-sm flex items-center gap-2 border rounded-lg px-3 py-2 text-sm text-slate-500 bg-slate-50"><i class="fa-solid fa-magnifying-glass"></i><input id="search" class="bg-transparent outline-none w-32" placeholder="Search"></div>
    <button class="w-9 h-9 rounded-lg border text-slate-500"><i class="fa-regular fa-bell"></i></button>
    <button id="demoLogin" class="hide-sm px-3 py-2 rounded-lg bg-slate-900 text-white text-sm font-semibold">Demo Login</button>
    <button class="w-9 h-9 rounded-full bg-indigo-100 text-indigo-700 font-bold text-xs">VF</button>
  </div>
</header>

<main class="p-5 lg:p-8 max-w-[1500px] mx-auto">

<!-- DASHBOARD -->
<section id="dashboard" class="page">
  <div class="flex flex-wrap items-end justify-between gap-4 mb-6">
    <div><div class="mono text-[10px] uppercase tracking-widest text-blue-600">08 August 2026 · Demo Data</div><h1 class="text-2xl lg:text-3xl font-extrabold mt-1">Good morning, Operator.</h1><p class="text-sm text-slate-500 mt-1">Your business finance control center is ready.</p></div>
    <div class="flex gap-2"><button class="btn px-4 py-2.5 rounded-lg border bg-white text-sm font-semibold" onclick="showToast('Export prepared — demo only')"><i class="fa-solid fa-download mr-2"></i>Export</button><button class="btn px-4 py-2.5 rounded-lg bg-blue-600 text-white text-sm font-semibold" onclick="openModal('paymentModal')"><i class="fa-solid fa-plus mr-2"></i>New Payment</button></div>
  </div>
  <div class="grid grid4 grid-cols-4 gap-4">
    <div class="card p-5"><div class="flex justify-between text-slate-400 text-xs"><span>Available balance</span><i class="fa-solid fa-wallet"></i></div><div class="text-3xl font-extrabold mt-4">$24,680.42</div><div class="text-xs text-emerald-600 mt-2">↑ 12.8% this month</div></div>
    <div class="card p-5"><div class="flex justify-between text-slate-400 text-xs"><span>Payments today</span><i class="fa-solid fa-arrow-right-arrow-left"></i></div><div class="text-3xl font-extrabold mt-4">1,284</div><div class="text-xs text-emerald-600 mt-2">↑ 8.4% vs yesterday</div></div>
    <div class="card p-5"><div class="flex justify-between text-slate-400 text-xs"><span>New customers</span><i class="fa-solid fa-user-plus"></i></div><div class="text-3xl font-extrabold mt-4">392</div><div class="text-xs text-blue-600 mt-2">+49 today</div></div>
    <div class="card p-5"><div class="flex justify-between text-slate-400 text-xs"><span>Net income</span><i class="fa-solid fa-chart-simple"></i></div><div class="text-3xl font-extrabold mt-4">$8,942.18</div><div class="text-xs text-emerald-600 mt-2">↑ 18.2% this month</div></div>
  </div>
  <div class="grid grid2 grid-cols-2 gap-5 mt-5">
    <div class="card p-5"><div class="flex justify-between items-center"><div><h2 class="font-bold">Revenue performance</h2><p class="text-xs text-slate-400 mt-1">Last 30 days</p></div><select class="border rounded-lg text-xs p-2"><option>30 days</option><option>90 days</option></select></div><div class="h-[290px] mt-3"><canvas id="revenueChart"></canvas></div></div>
    <div class="card p-5"><div class="flex justify-between"><div><h2 class="font-bold">Activity stream</h2><p class="text-xs text-slate-400 mt-1">Latest workspace events</p></div><button class="text-xs text-blue-600">View all</button></div><div class="mt-4 space-y-1" id="activity"></div></div>
  </div>
  <div class="grid grid2 grid-cols-2 gap-5 mt-5">
    <div class="card"><div class="p-5 flex justify-between"><h2 class="font-bold">Recent transactions</h2><button onclick="go('payments')" class="text-xs text-blue-600">View all</button></div><div class="table-wrap"><table class="w-full text-sm"><thead class="bg-slate-50 text-[11px] uppercase text-slate-400"><tr><th class="text-left p-4">Customer</th><th class="text-left p-4">Method</th><th class="text-right p-4">Amount</th></tr></thead><tbody id="recentRows"></tbody></table></div></div>
    <div class="card p-5"><div class="flex justify-between"><h2 class="font-bold">Quick actions</h2><span class="text-xs text-slate-400">Shortcuts</span></div><div class="grid grid-cols-2 gap-3 mt-5"><button class="p-4 rounded-xl border text-left hover:bg-slate-50" onclick="openModal('paymentModal')"><i class="fa-solid fa-paper-plane text-blue-600"></i><div class="font-semibold text-sm mt-3">Send payment</div><div class="text-xs text-slate-400 mt-1">Create a demo transfer</div></button><button class="p-4 rounded-xl border text-left hover:bg-slate-50" onclick="go('proof')"><i class="fa-solid fa-file-circle-check text-emerald-600"></i><div class="font-semibold text-sm mt-3">Proof center</div><div class="text-xs text-slate-400 mt-1">Review receipts</div></button><button class="p-4 rounded-xl border text-left hover:bg-slate-50" onclick="go('banking')"><i class="fa-solid fa-building-columns text-violet-600"></i><div class="font-semibold text-sm mt-3">Bank accounts</div><div class="text-xs text-slate-400 mt-1">Manage demo accounts</div></button><button class="p-4 rounded-xl border text-left hover:bg-slate-50" onclick="go('payouts')"><i class="fa-solid fa-earth-americas text-orange-600"></i><div class="font-semibold text-sm mt-3">Payout rates</div><div class="text-xs text-slate-400 mt-1">Compare regions</div></button></div></div>
  </div>
</section>

<!-- PAYMENTS -->
<section id="payments" class="page hidden">
<div class="flex justify-between items-end mb-6"><div><div class="mono text-[10px] text-blue-600">PAYMENTS / LEDGER</div><h1 class="text-3xl font-extrabold mt-1">Payments</h1><p class="text-sm text-slate-500 mt-1">Search and inspect fictional transaction records.</p></div><button onclick="openModal('paymentModal')" class="px-4 py-2.5 bg-blue-600 text-white rounded-lg text-sm font-semibold">+ New payment</button></div>
<div class="card p-4 mb-4 flex flex-wrap gap-3"><input id="paymentSearch" oninput="filterPayments()" class="border rounded-lg px-3 py-2 text-sm flex-1 min-w-[220px]" placeholder="Search username, method or amount"><select class="border rounded-lg px-3 py-2 text-sm"><option>All methods</option><option>Card</option><option>USDT Polygon</option><option>Bank</option></select><button class="border rounded-lg px-4 text-sm">Filter</button></div>
<div class="card overflow-hidden"><div class="table-wrap"><table class="w-full text-sm"><thead class="bg-slate-50"><tr><th class="p-4 text-left text-[11px] uppercase text-slate-400">Date</th><th class="p-4 text-left text-[11px] uppercase text-slate-400">Username</th><th class="p-4 text-left text-[11px] uppercase text-slate-400">Method</th><th class="p-4 text-right text-[11px] uppercase text-slate-400">Amount</th><th class="p-4 text-right text-[11px] uppercase text-slate-400">Status</th></tr></thead><tbody id="paymentRows"></tbody></table></div></div>
</section>

<!-- PROOF -->
<section id="proof" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-emerald-600">PAYMENT PROOF / DEMO RECORDS</div><h1 class="text-3xl font-extrabold mt-1">Payment Proof</h1><p class="text-sm text-slate-500 mt-1">Fictional sample receipts for UI demonstration. Not real payment verification.</p></div>
<div class="card overflow-hidden"><div class="p-4 border-b flex justify-between"><div class="font-bold">Recent receipts</div><span class="pill px-3 py-1 bg-emerald-50 text-emerald-700 text-xs">DEMO MODE</span></div><div class="table-wrap"><table class="w-full text-sm"><thead class="bg-slate-50"><tr><th class="p-4 text-left text-[11px] text-slate-400">DATE</th><th class="p-4 text-left text-[11px] text-slate-400">USERNAME</th><th class="p-4 text-left text-[11px] text-slate-400">METHOD</th><th class="p-4 text-right text-[11px] text-slate-400">AMOUNT</th><th class="p-4 text-right text-[11px] text-slate-400">RECEIPT</th></tr></thead><tbody id="proofRows"></tbody></table></div></div>
</section>

<!-- PAYOUT -->
<section id="payouts" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-indigo-600">PAYOUTS / REGIONS</div><h1 class="text-3xl font-extrabold mt-1">Payout Rates</h1><p class="text-sm text-slate-500 mt-1">Sample CPM rates inspired by the supplied reference layout.</p></div>
<div class="card overflow-hidden"><div class="p-4 border-b flex justify-between"><span class="pill bg-indigo-50 text-indigo-700 px-3 py-1 text-xs font-semibold">SHORTLINKS · DEMO</span><button class="w-9 h-9 border rounded-full"><i class="fa-solid fa-magnifying-glass text-slate-500"></i></button></div><table class="w-full text-sm"><thead><tr><th class="p-4 text-left text-[11px] uppercase text-slate-400">Country</th><th class="p-4 text-right text-[11px] uppercase text-slate-400">Desktop CPM</th><th class="p-4 text-right text-[11px] uppercase text-slate-400">Mobile/Tablet CPM</th></tr></thead><tbody id="rateRows"></tbody></table></div>
</section>

<!-- BANKING -->
<section id="banking" class="page hidden">
<div class="flex justify-between items-end mb-6"><div><div class="mono text-[10px] text-violet-600">BANKING / ACCOUNTS</div><h1 class="text-3xl font-extrabold mt-1">Banking</h1><p class="text-sm text-slate-500 mt-1">Fictional bank account UI — no real banking connection.</p></div><button class="px-4 py-2.5 bg-slate-900 text-white rounded-lg text-sm" onclick="showToast('Bank account linking is disabled in demo mode')">Link account</button></div>
<div class="grid grid2 grid-cols-2 gap-5">
<div class="card p-6 bg-gradient-to-br from-slate-950 to-slate-800 text-white"><div class="flex justify-between"><span class="font-bold">VaultFlow Business</span><i class="fa-solid fa-building-columns"></i></div><div class="mono text-xl mt-12">•••• 4821</div><div class="flex justify-between mt-5 text-xs text-slate-400"><span>Demo checking</span><span>Available $18,240.10</span></div></div>
<div class="card p-6"><div class="flex justify-between"><div><div class="font-bold">Reserve Account</div><div class="text-xs text-slate-400 mt-1">Savings · Demo</div></div><i class="fa-solid fa-piggy-bank text-violet-600"></i></div><div class="text-3xl font-extrabold mt-10">$6,440.32</div><div class="text-xs text-emerald-600 mt-2">+ $420.00 this month</div></div>
</div>
<div class="card mt-5"><div class="p-5 border-b font-bold">Banking activity</div><div id="bankActivity"></div></div>
</section>

<!-- ANALYTICS -->
<section id="analytics" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-blue-600">ANALYTICS / PERFORMANCE</div><h1 class="text-3xl font-extrabold mt-1">Analytics</h1><p class="text-sm text-slate-500 mt-1">Interactive demo charts and operational KPIs.</p></div>
<div class="grid grid4 grid-cols-4 gap-4"><div class="card p-5"><div class="text-xs text-slate-400">Conversion</div><div class="text-2xl font-bold mt-3">8.42%</div><div class="text-xs text-emerald-600 mt-2">+1.3%</div></div><div class="card p-5"><div class="text-xs text-slate-400">Avg. payment</div><div class="text-2xl font-bold mt-3">$42.18</div><div class="text-xs text-emerald-600 mt-2">+4.7%</div></div><div class="card p-5"><div class="text-xs text-slate-400">Refund rate</div><div class="text-2xl font-bold mt-3">0.42%</div><div class="text-xs text-emerald-600 mt-2">-0.08%</div></div><div class="card p-5"><div class="text-xs text-slate-400">Retention</div><div class="text-2xl font-bold mt-3">82.6%</div><div class="text-xs text-emerald-600 mt-2">+3.4%</div></div></div>
<div class="card p-5 mt-5"><div class="flex justify-between"><div><h2 class="font-bold">Traffic vs. revenue</h2><p class="text-xs text-slate-400">Demo dataset</p></div><span class="text-xs text-slate-400">Aug 02 — Aug 08</span></div><div class="h-[380px] mt-4"><canvas id="analyticsChart"></canvas></div></div>
</section>

<!-- CUSTOMERS -->
<section id="customers" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-blue-600">CUSTOMERS / DIRECTORY</div><h1 class="text-3xl font-extrabold mt-1">Customers</h1></div>
<div class="card overflow-hidden"><table class="w-full text-sm"><thead class="bg-slate-50"><tr><th class="p-4 text-left text-[11px] text-slate-400">Customer</th><th class="p-4 text-left text-[11px] text-slate-400">Region</th><th class="p-4 text-left text-[11px] text-slate-400">Plan</th><th class="p-4 text-right text-[11px] text-slate-400">Lifetime value</th></tr></thead><tbody id="customerRows"></tbody></table></div>
</section>

<!-- SETTINGS -->
<section id="settings" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-slate-500">WORKSPACE / SETTINGS</div><h1 class="text-3xl font-extrabold mt-1">Settings</h1></div>
<div class="grid grid2 grid-cols-2 gap-5"><div class="card p-6"><h2 class="font-bold">Workspace profile</h2><label class="block text-xs text-slate-500 mt-6 mb-2">Workspace name</label><input class="w-full border rounded-lg p-3" value="VaultFlow Demo"><label class="block text-xs text-slate-500 mt-4 mb-2">Contact email</label><input class="w-full border rounded-lg p-3" value="demo@example.test"><button class="mt-5 px-4 py-2 bg-blue-600 text-white rounded-lg text-sm" onclick="showToast('Settings saved locally for this demo')">Save changes</button></div><div class="card p-6"><h2 class="font-bold">Security</h2><div class="flex justify-between items-center py-4 border-b"><span class="text-sm">Two-factor authentication</span><span class="pill bg-emerald-50 text-emerald-700 px-3 py-1 text-xs">Enabled</span></div><div class="flex justify-between items-center py-4"><span class="text-sm">Session timeout</span><select class="border rounded p-2 text-sm"><option>30 minutes</option><option>1 hour</option></select></div></div></div>
</section>

<!-- REPORTS -->
<section id="reports" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-orange-600">REPORTS / EXPORTS</div><h1 class="text-3xl font-extrabold mt-1">Reports</h1></div>
<div class="grid grid2 grid-cols-2 gap-5"><div class="card p-6"><i class="fa-solid fa-file-csv text-2xl text-emerald-600"></i><h2 class="font-bold mt-4">Transaction report</h2><p class="text-sm text-slate-500 mt-2">CSV-style demo export of payment activity.</p><button onclick="showToast('Demo CSV generated')" class="mt-5 px-4 py-2 border rounded-lg text-sm">Generate</button></div><div class="card p-6"><i class="fa-solid fa-file-pdf text-2xl text-rose-600"></i><h2 class="font-bold mt-4">Monthly statement</h2><p class="text-sm text-slate-500 mt-2">Visual statement preview for August 2026.</p><button onclick="showToast('Demo statement generated')" class="mt-5 px-4 py-2 border rounded-lg text-sm">Generate</button></div></div>
</section>

<!-- API -->
<section id="api" class="page hidden">
<div class="mb-6"><div class="mono text-[10px] text-cyan-600">DEVELOPER / API CENTER</div><h1 class="text-3xl font-extrabold mt-1">API Center</h1></div>
<div class="card p-6"><div class="flex justify-between"><div><h2 class="font-bold">Demo API key</h2><p class="text-xs text-slate-400 mt-1">Never use this value for production.</p></div><span class="pill bg-amber-50 text-amber-700 px-3 py-1 text-xs">TEST MODE</span></div><div class="mono bg-slate-950 text-emerald-300 rounded-xl p-4 mt-5 text-sm">vf_demo_7d8a9c2f_••••••••••••</div><div class="grid grid-cols-3 gap-3 mt-5"><div class="soft p-4 rounded-xl"><div class="text-xs text-slate-400">Requests</div><b>18,402</b></div><div class="soft p-4 rounded-xl"><div class="text-xs text-slate-400">Success</div><b>99.98%</b></div><div class="soft p-4 rounded-xl"><div class="text-xs text-slate-400">Latency</div><b>142 ms</b></div></div></div>
</section>

</main>
</div>
</div>

<!-- Demo login modal: deliberately fictional and does not transmit/store credentials -->
<div id="loginModal" class="modal fixed inset-0 bg-slate-950/60 backdrop-blur-sm items-center justify-center z-[60] p-4">
<div class="bg-white w-full max-w-md rounded-2xl shadow-2xl p-8 relative">
<button onclick="closeModal('loginModal')" class="absolute top-4 right-4 w-8 h-8 rounded-full hover:bg-slate-100"><i class="fa-solid fa-xmark"></i></button>
<div class="w-11 h-11 rounded-xl bg-slate-900 text-white grid place-items-center mx-auto"><i class="fa-solid fa-shield-halved"></i></div>
<h2 class="text-2xl font-bold text-center mt-5">Sign in to VaultFlow</h2>
<p class="text-xs text-center text-slate-400 mt-2">Fictional demo login · no real credentials are accepted.</p>
<button onclick="showToast('Demo OAuth flow opened — no external account used');closeModal('loginModal')" class="w-full border rounded-lg py-3 mt-6 text-sm font-semibold hover:bg-slate-50"><i class="fa-brands fa-google mr-2"></i>Continue with Demo Account</button>
<div class="flex items-center gap-3 my-5"><div class="h-px bg-slate-200 flex-1"></div><span class="text-xs text-slate-400">or demo email</span><div class="h-px bg-slate-200 flex-1"></div></div>
<input class="w-full border rounded-lg p-3 text-sm" placeholder="demo@example.test">
<button onclick="showToast('Demo login successful');closeModal('loginModal')" class="w-full bg-blue-600 text-white rounded-lg py-3 mt-3 text-sm font-semibold">Enter Demo Workspace</button>
<div class="mt-5 p-3 rounded-lg bg-amber-50 text-amber-800 text-[11px]">This is a UI prototype. Do not enter Gmail, Google, PayPal, bank, or other real credentials.</div>
</div></div>

<!-- Payment modal -->
<div id="paymentModal" class="modal fixed inset-0 bg-slate-950/60 backdrop-blur-sm items-center justify-center z-[60] p-4">
<div class="bg-white w-full max-w-lg rounded-2xl shadow-2xl p-7 relative">
<button onclick="closeModal('paymentModal')" class="absolute top-4 right-4 w-8 h-8 rounded-full hover:bg-slate-100"><i class="fa-solid fa-xmark"></i></button>
<h2 class="text-xl font-bold">Create demo payment</h2><p class="text-xs text-slate-400 mt-1">No money moves. This only updates the UI.</p>
<label class="block text-xs text-slate-500 mt-6 mb-2">Recipient</label><input id="payRecipient" class="w-full border rounded-lg p-3" placeholder="customer@example.test">
<label class="block text-xs text-slate-500 mt-4 mb-2">Amount</label><input id="payAmount" type="number" class="w-full border rounded-lg p-3" placeholder="25.00">
<label class="block text-xs text-slate-500 mt-4 mb-2">Method</label><select id="payMethod" class="w-full border rounded-lg p-3"><option>Demo Card</option><option>Demo Bank</option><option>Demo USDT Polygon</option><option>Demo PayPal-style Wallet</option></select>
<button onclick="createPayment()" class="w-full bg-blue-600 text-white rounded-lg py-3 mt-6 font-semibold">Create Demo Record</button>
</div></div>

<div id="toast" class="toast fixed bottom-5 right-5 z-[80] bg-slate-900 text-white rounded-xl shadow-xl px-5 py-3 text-sm flex items-center gap-3"><i class="fa-solid fa-circle-check text-emerald-400"></i><span id="toastText">Done</span></div>

<script>
const payments=[
["08 Aug, 2026","ODI***","USDT POLYGON","$3.22","Completed"],["07 Aug, 2026","NIG***","USDT POLYGON","$4.80","Completed"],["07 Aug, 2026","LUK***","USDT POLYGON","$6.70","Completed"],["07 Aug, 2026","XDA***","USDT POLYGON","$92.58","Completed"],["07 Aug, 2026","PED***","USDT POLYGON","$3.00","Completed"],["07 Aug, 2026","JOR***","USDT POLYGON","$3.13","Completed"],["07 Aug, 2026","ANI***","REDOTPAY USDT BSC","$153.10","Pending"],["07 Aug, 2026","ODI***","USDT POLYGON","$5.48","Completed"],["06 Aug, 2026","KAI***","Demo Card","$41.90","Completed"],["06 Aug, 2026","MIA***","Demo Bank","$240.00","Completed"],["05 Aug, 2026","SAM***","Demo PayPal-style Wallet","$18.75","Completed"]];
const rates=[["Greenland","GL","$22.0000","$22.0000"],["United States","US","$12.0000","$12.0000"],["Canada","CA","$11.0000","$11.0000"],["United Kingdom","GB","$10.0000","$10.0000"],["Brunei Darussalam","BN","$8.0000","$8.0000"],["Germany","DE","$8.0000","$8.0000"],["France","FR","$8.0000","$8.0000"],["Brazil","BR","$7.0000","$7.0000"],["Australia","AU","$6.0000","$6.0000"],["Japan","JP","$6.0000","$6.0000"],["Singapore","SG","$5.5000","$5.5000"],["India","IN","$4.5000","$4.5000"],["Pakistan","PK","$3.8000","$3.8000"]];
const customers=[["Ava Morgan","United States","Pro","$2,840"],["Noah Khan","Pakistan","Starter","$840"],["Mia Chen","Singapore","Pro","$1,920"],["Liam Wilson","United Kingdom","Business","$4,420"],["Sara Patel","India","Starter","$620"],["Oliver Smith","Canada","Pro","$2,160"],["Emma Garcia","Brazil","Business","$3,280"]];
const $=s=>document.querySelector(s);
function rowPayment(p){return `<tr class="table-row hover:bg-slate-50"><td class="p-4 text-xs text-slate-500">${p[0]}</td><td class="p-4 font-medium">${p[1]}</td><td class="p-4"><span class="pill bg-emerald-50 text-emerald-700 px-2.5 py-1 text-[10px]">${p[2]}</span></td><td class="p-4 text-right font-semibold text-emerald-700">↑ ${p[3]}</td><td class="p-4 text-right"><span class="text-xs ${p[4]=='Completed'?'text-emerald-600':'text-amber-600'}">${p[4]}</span></td></tr>`}
function render(){
 $("#recentRows").innerHTML=payments.slice(0,6).map(p=>`<tr class="table-row"><td class="p-4"><div class="font-medium">${p[1]}</div><div class="text-[10px] text-slate-400">${p[0]}</div></td><td class="p-4 text-xs text-slate-500">${p[2]}</td><td class="p-4 text-right font-semibold">${p[3]}</td></tr>`).join("");
 $("#paymentRows").innerHTML=payments.map(rowPayment).join("");
 $("#proofRows").innerHTML=payments.map(p=>`<tr class="table-row"><td class="p-4 text-xs text-slate-500">${p[0]}</td><td class="p-4 font-medium">${p[1]}</td><td class="p-4"><span class="pill bg-emerald-50 text-emerald-700 px-2.5 py-1 text-[10px]">${p[2]}</span></td><td class="p-4 text-right font-semibold text-emerald-700">↑ ${p[3]}</td><td class="p-4 text-right"><button class="text-blue-600 text-xs" onclick="showToast('Demo receipt preview opened')">View</button></td></tr>`).join("");
 $("#rateRows").innerHTML=rates.map(r=>`<tr class="table-row hover:bg-slate-50"><td class="p-4"><span class="mr-2">${r[1]}</span>${r[0]} <span class="text-[10px] bg-slate-100 text-slate-500 px-2 py-1 rounded ml-2">${r[1]}</span></td><td class="p-4 text-right mono text-xs">${r[2]}</td><td class="p-4 text-right mono text-xs">${r[3]}</td></tr>`).join("");
 $("#customerRows").innerHTML=customers.map(c=>`<tr class="table-row"><td class="p-4 font-medium">${c[0]}</td><td class="p-4 text-slate-500">${c[1]}</td><td class="p-4"><span class="pill bg-blue-50 text-blue-700 px-2.5 py-1 text-xs">${c[2]}</span></td><td class="p-4 text-right font-semibold">${c[3]}</td></tr>`).join("");
 $("#activity").innerHTML=[
 ["fa-arrow-down-left","Payment received","ODI*** received $3.22 via Demo USDT","2 min ago","text-emerald-600"],
 ["fa-user-plus","New customer","NIG*** joined Pro workspace","12 min ago","text-blue-600"],
 ["fa-building-columns","Bank sync","Reserve Account refreshed","28 min ago","text-violet-600"],
 ["fa-file-circle-check","Receipt generated","Demo proof #VF-9281 created","41 min ago","text-orange-600"],
 ["fa-arrow-up-right-from-square","Payout queued","$420.00 scheduled for demo payout","1 hr ago","text-slate-600"]
].map(a=>`<div class="flex gap-3 p-3 rounded-lg hover:bg-slate-50"><div class="w-9 h-9 rounded-full bg-slate-100 grid place-items-center ${a[4]}"><i class="fa-solid ${a[0]}"></i></div><div class="flex-1"><div class="text-sm font-medium">${a[1]}</div><div class="text-xs text-slate-400 mt-1">${a[2]}</div></div><div class="text-[10px] text-slate-400">${a[3]}</div></div>`).join("");
 $("#bankActivity").innerHTML=payments.slice(0,5).map(p=>`<div class="table-row p-4 flex justify-between"><div><div class="font-medium text-sm">${p[1]}</div><div class="text-xs text-slate-400 mt-1">${p[2]} · ${p[0]}</div></div><div class="font-semibold">${p[3]}</div></div>`).join("");
}
function go(id){document.querySelectorAll(".page").forEach(x=>x.classList.add("hidden"));$("#"+id).classList.remove("hidden");document.querySelectorAll(".navitem").forEach(x=>x.classList.remove("active"));document.querySelector(`.navitem[data-section="${id}"]`)?.classList.add("active");const names={dashboard:"Dashboard",payments:"Payments",proof:"Payment Proof",payouts:"Payout Rates",banking:"Banking",analytics:"Analytics",customers:"Customers",settings:"Settings",reports:"Reports",api:"API Center"};$("#pageTitle").textContent=names[id]||id;$("#crumb").textContent=names[id]||id;window.scrollTo({top:0,behavior:"smooth"});if(id==="analytics")setTimeout(charts,50)}
document.querySelectorAll(".navitem[data-section]").forEach(n=>n.onclick=()=>go(n.dataset.section));
$("#sideToggle").onclick=()=>{document.querySelector(".sidebar").classList.toggle("!w-[76px]");document.querySelector(".main").classList.toggle("!ml-[76px]")};
function openModal(id){$("#"+id).classList.add("show")}
function closeModal(id){$("#"+id).classList.remove("show")}
$("#demoLogin").onclick=()=>openModal("loginModal");
function showToast(msg){$("#toastText").textContent=msg;$("#toast").classList.add("show");setTimeout(()=>$("#toast").classList.remove("show"),2600)}
function createPayment(){const name=$("#payRecipient").value||"NEW***";const amt=Number($("#payAmount").value||0).toFixed(2);const method=$("#payMethod").value;payments.unshift(["08 Aug, 2026",name.slice(0,3)+"***",method,"$"+amt,"Pending"]);render();closeModal("paymentModal");showToast("Demo payment record created")}
function filterPayments(){const q=$("#paymentSearch").value.toLowerCase();$("#paymentRows").innerHTML=payments.filter(p=>p.join(" ").toLowerCase().includes(q)).map(rowPayment).join("")}
let revenueChart,analyticsChart;
function charts(){
 const opts={responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false}},scales:{y:{grid:{color:"#eef1f5"},ticks:{color:"#98a2b3"}},x:{grid:{display:false},ticks:{color:"#98a2b3"}}}};
 const labels=["Aug 02","Aug 03","Aug 04","Aug 05","Aug 06","Aug 07","Aug 08"];
 if(!revenueChart){revenueChart=new Chart(document.getElementById("revenueChart"),{type:"line",data:{labels,datasets:[{data:[3200,4100,5400,4200,6800,7200,8942],borderColor:"#2563eb",backgroundColor:"rgba(37,99,235,.08)",fill:true,tension:.35,borderWidth:2,pointRadius:3}]},options:opts})}
 if(!analyticsChart){analyticsChart=new Chart(document.getElementById("analyticsChart"),{type:"bar",data:{labels,datasets:[{label:"Revenue",data:[32,48,62,44,72,80,94],backgroundColor:"#4f46e5",borderRadius:6},{label:"Traffic",data:[60,72,90,75,110,126,142],backgroundColor:"#c7d2fe",borderRadius:6}]},options:{...opts,plugins:{legend:{display:true,position:"top",align:"end"}}}})}
}
$("#search").addEventListener("input",e=>{if(e.target.value.trim())go("payments")});
render();charts();
</script>
</body>
</html>
