# EMAGREÇA RÁPIDO 
💪 Emagreça Agora — seu guia prático para perder peso com saúde! Conte com contador de calorias, treinos rápidos, receitas fit e dicas exclusivas, tudo por apenas R$6 a cada 2 semanas. Comece hoje e transforme-se! 

<meta name="description" content="Emagreça Agora — transforme seu corpo e sua vida com treinos rápidos, receitas fit e contador de calorias. Acesse tudo por apenas R$6 a cada 2 semanas!">

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Emagreça Agora — Comece já</title>
  <meta name="description" content="Emagreça Agora — treinos curtos, receitas práticas, blog e contador de calorias. Plano: R$6 a cada 2 semanas.">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --pink:#ff2d7a; --orange:#ff914d; --muted:#6b7280; --card:#ffffff; --glass: rgba(255,255,255,0.12);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,"Helvetica Neue",Arial;color:#111;background:linear-gradient(180deg,#fff 0%, #f7f7fb 100%)}
    .container{max-width:1100px;margin:0 auto;padding:18px}
    header{background:linear-gradient(90deg,var(--pink),var(--orange)); color:#fff;padding:18px;border-bottom-left-radius:14px;border-bottom-right-radius:14px}
    .top{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{font-weight:800;font-size:18px}
    .tag{font-size:13px;color:rgba(255,255,255,0.9)}
    .nav{display:flex;gap:8px;align-items:center}
    .btn{display:inline-block;padding:10px 14px;border-radius:999px;font-weight:700;cursor:pointer;border:0}
    .btn-primary{background:#fff;color:var(--pink);box-shadow:0 10px 30px rgba(16,24,40,0.08)}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.18);color:#fff}
    .hero{display:flex;flex-direction:column;gap:14px;align-items:center;text-align:center;padding:28px 12px}
    .hero h1{font-size:32px;margin:0;line-height:1.02}
    .hero p{margin:0;color:rgba(255,255,255,0.95);max-width:820px}
    .hero-cta{background:rgba(255,255,255,0.12);padding:18px;border-radius:12px}
    .grid{display:grid;gap:14px}
    .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
    .card{background:var(--card);padding:14px;border-radius:12px;box-shadow:0 8px 24px rgba(16,24,40,0.06)}
    .section{padding:26px 12px}
    h2{margin:0 0 10px 0;font-size:20px;color:#111}
    p.lead{color:var(--muted);margin:0}
    footer{padding:20px 0;text-align:center;color:var(--muted);font-size:13px}
    input,textarea,select{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9ef;font-size:14px}
    .row{display:flex;gap:10px}
    .row > *{flex:1}
    .muted{color:var(--muted);font-size:13px}
    .kpi{display:flex;gap:10px;align-items:center}
    .badge{background:linear-gradient(90deg,var(--pink),var(--orange));color:#fff;padding:6px 10px;border-radius:999px;font-weight:800}
    .center{text-align:center}
    .progress-wrap{background:#f1f5f9;border-radius:999px;overflow:hidden;height:14px}
    .progress-bar{height:14px;background:linear-gradient(90deg,#34d399,#06b6d4);width:0%;transition:width .4s ease}
    .small{font-size:13px}
    .muted-weak{color:#94a3b8}
    .hidden{display:none}
    .pill{padding:6px 10px;border-radius:999px;border:1px solid #eef2ff;font-weight:700}
    /* responsive */
    @media(min-width:900px){
      .hero{flex-direction:row;text-align:left;justify-content:space-between;padding:36px 12px}
      .hero-left{max-width:60%}
      .hero-cta{max-width:36%}
    }
    /* subtle */
    .glow{box-shadow:0 8px 30px rgba(255,45,122,0.16)}
    .muted-2{color:#4b5563}
    .mt-6{margin-top:18px}
    .mb-6{margin-bottom:18px}
    .blog-item{padding:12px;border-radius:10px;background:#fff;box-shadow:0 6px 18px rgba(10,10,10,0.03)}
    .link{color:var(--pink);cursor:pointer;font-weight:700}
    .cta-large{padding:14px 20px;font-size:16px}
  </style>
</head>
<body>

<header>
  <div class="container top">
    <div style="display:flex;gap:12px;align-items:center">
      <div class="brand">Emagreça Agora</div>
      <div class="tag">R$6 · 2 semanas</div>
    </div>
    <div id="navArea" class="nav">
      <!-- nav injected -->
    </div>
  </div>

  <div class="container hero" role="banner" aria-label="Hero">
    <div class="hero-left">
      <h1>🔥 Emagreça Agora — Comece hoje, veja o resultado</h1>
      <p style="margin-top:10px">Plano prático, receitas gostosas e treinos curtos. Transforme seu corpo e sua confiança — por apenas <strong>R$6 a cada 2 semanas</strong>.</p>
      <div style="margin-top:14px;display:flex;gap:10px;flex-wrap:wrap">
        <button class="btn btn-primary cta-large" id="btnStart">QUERO EMAGRECER AGORA</button>
        <button class="btn btn-ghost" id="btnExplore">EXPLORAR</button>
      </div>
    </div>

    <div class="hero-cta center glow" aria-hidden="true">
      <div class="badge">Plano Rápido</div>
      <div style="font-size:20px;font-weight:800;margin-top:8px">R$6 <span class="small muted">/ 2 semanas</span></div>
      <div class="muted small" style="margin-top:8px">Receitas • Treinos • Blog exclusivo</div>
      <div style="margin-top:12px"><button class="btn btn-primary" id="btnSubscribeHero">Assinar por R$6</button></div>
    </div>
  </div>
</header>

<main class="container">

  <!-- HOME - features -->
  <section class="section" id="homeSection">
    <h2>O que você recebe</h2>
    <p class="lead">Três pilares: movimento fácil, alimentação prática e motivação diária — tudo para gerar resultado rápido e sustentável.</p>

    <div class="cards mt-6">
      <div class="card"><div class="kpi"><div style="font-size:26px">💃</div><div><strong>Treinos Rápidos</strong><div class="muted small">15 minutos, em casa</div></div></div></div>
      <div class="card"><div class="kpi"><div style="font-size:26px">🥗</div><div><strong>Receitas Saborosas</strong><div class="muted small">Fáceis e econômicas</div></div></div></div>
      <div class="card"><div class="kpi"><div style="font-size:26px">🔥</div><div><strong>Motivação Diária</strong><div class="muted small">Metas de 2 semanas</div></div></div></div>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="section">
    <h2>Depoimentos</h2>
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin-top:12px">
      <div class="card">“Perdi 5kg em 1 mês com esse plano.” — Ana</div>
      <div class="card">“Prático, barato e eficiente!” — João</div>
      <div class="card">“Recomendo para qualquer pessoa ocupada.” — Carla</div>
    </div>
  </section>

  <!-- Blog -->
  <section class="section" id="blogSection" style="display:none">
    <h2>Blog — Dicas & Histórias</h2>

    <div id="newPostArea" class="card mt-6" style="display:none">
      <div style="font-weight:700;margin-bottom:8px">Criar novo post</div>
      <input id="postTitle" placeholder="Título (ex: 5 passos para começar)" />
      <textarea id="postContent" placeholder="Conteúdo" style="margin-top:8px"></textarea>
      <div style="text-align:right;margin-top:8px"><button class="btn" id="postAddBtn" style="background:var(--pink);color:#fff">Publicar</button></div>
    </div>

    <div id="blogList" class="mt-6">
      <!-- posts inserted here -->
    </div>
  </section>

  <!-- Recipes -->
  <section class="section" id="recipesSection" style="display:none">
    <h2>Receitas Fit</h2>
    <div class="cards mt-6">
      <div class="card"><strong>Panqueca Fit de Banana</strong><div class="muted small">2 ovos + 1 banana. Misture e frite sem óleo.</div></div>
      <div class="card"><strong>Salada Turbo</strong><div class="muted small">Folhas, frango grelhado e azeite.</div></div>
      <div class="card"><strong>Shake de Aveia</strong><div class="muted small">Leite, aveia, cacau e mel.</div></div>
      <div class="card"><strong>Omelete Proteico</strong><div class="muted small">2 ovos + claras + espinafre.</div></div>
    </div>
  </section>

  <!-- Workouts -->
  <section class="section" id="workoutsSection" style="display:none">
    <h2>Treinos Rápidos</h2>
    <div class="cards mt-6">
      <div class="card"><strong>Treino 15 min</strong><div class="muted small">Circuito: agachamento, prancha, polichinelo.</div></div>
      <div class="card"><strong>Queima Rápida</strong><div class="muted small">30s: corrida no lugar, burpee, descanso.</div></div>
      <div class="card"><strong>Alongamento</strong><div class="muted small">Rotina de 5 minutos para recuperar.</div></div>
    </div>
  </section>

  <!-- Calorie Counter -->
  <section class="section" id="caloriesSection" style="display:none">
    <h2>Contador de Calorias</h2>
    <div class="card mt-6" style="max-width:760px;margin:auto">
      <div style="display:flex;gap:8px;flex-wrap:wrap">
        <input id="goalInput" type="number" placeholder="Meta diária (kcal)" value="2000" style="max-width:160px" />
        <input id="foodName" placeholder="Alimento (ex: Arroz 1 concha)" />
        <input id="foodCal" type="number" placeholder="kcal" style="max-width:120px" />
        <button class="btn" id="addFoodBtn" style="background:var(--pink);color:#fff">Adicionar</button>
      </div>

      <div id="foodList" style="margin-top:12px"></div>

      <div style="margin-top:12px">
        <div class="progress-wrap"><div id="progBar" class="progress-bar" style="width:0%"></div></div>
        <div style="display:flex;justify-content:space-between;margin-top:8px">
          <div class="muted small">Total consumido</div>
          <div id="totalText" style="font-weight:800"></div>
        </div>
        <div id="alertOver" style="color:#dc2626;font-weight:800;margin-top:8px;display:none">⚠️ Você atingiu ou ultrapassou sua meta!</div>
        <div style="margin-top:10px" class="muted small">Dica: use porções reais e acompanhe diariamente para melhores resultados.</div>
      </div>
    </div>
  </section>

  <!-- Dashboard -->
  <section class="section" id="dashboardSection" style="display:none">
    <h2>Seu Painel</h2>
    <div id="dashboardCard" class="card mt-6"></div>
  </section>

  <!-- Auth area -->
  <section class="section" id="authSection" style="display:none">
    <div style="max-width:640px;margin:auto">
      <div class="card">
        <div id="authTabs" style="display:flex;gap:8px;justify-content:center;margin-bottom:12px">
          <button class="btn small" id="tabSignup" style="background:var(--pink);color:#fff">Cadastre-se</button>
          <button class="btn small" id="tabLogin">Entrar</button>
        </div>
        <div id="signupForm">
          <input id="nameIn" placeholder="Nome" />
          <input id="emailIn" placeholder="Email" style="margin-top:8px" />
          <input id="passIn" placeholder="Senha" type="password" style="margin-top:8px" />
          <div style="text-align:right;margin-top:8px"><button class="btn" id="signupBtn" style="background:var(--pink);color:#fff">Criar conta</button></div>
        </div>
        <div id="loginForm" style="display:none;margin-top:8px">
          <input id="emailL" placeholder="Email" />
          <input id="passL" placeholder="Senha" type="password" style="margin-top:8px" />
          <div style="text-align:right;margin-top:8px"><button class="btn" id="loginBtn" style="background:#10b981;color:#fff">Entrar</button></div>
        </div>
        <div style="margin-top:12px" class="muted-2 small">Obs: esta é uma demo — dados salvos no navegador (localStorage).</div>
      </div>
    </div>
  </section>

</main>

<footer>
  <div class="container">
    © <span id="year"></span> Emagreça Agora — Simulação educativa • Preço demonstrativo: R$6 / 2 semanas
  </div>
</footer>

<script>
/* ------------------------------
  Emagreça Agora — single-file app
  localStorage keys: ea_user, ea_blog, ea_foods, ea_goal
  ------------------------------ */

/* Elements */
const navArea = document.getElementById('navArea');
const btnStart = document.getElementById('btnStart');
const btnExplore = document.getElementById('btnExplore');
const btnSubscribeHero = document.getElementById('btnSubscribeHero');
const yearEl = document.getElementById('year'); yearEl.textContent = new Date().getFullYear();

/* Sections map */
const sections = {
  home: document.getElementById('homeSection'),
  blog: document.getElementById('blogSection'),
  recipes: document.getElementById('recipesSection'),
  workouts: document.getElementById('workoutsSection'),
  calories: document.getElementById('caloriesSection'),
  dashboard: document.getElementById('dashboardSection'),
  auth: document.getElementById('authSection')
};

/* State load */
let user = JSON.parse(localStorage.getItem('ea_user') || 'null');
let blogPosts = JSON.parse(localStorage.getItem('ea_blog') || '[]');
let foods = JSON.parse(localStorage.getItem('ea_foods') || '[]');

function saveUser(){ localStorage.setItem('ea_user', JSON.stringify(user)); }
function saveBlog(){ localStorage.setItem('ea_blog', JSON.stringify(blogPosts)); }
function saveFoods(){ localStorage.setItem('ea_foods', JSON.stringify(foods)); }

/* Initialize demo posts if empty */
if(blogPosts.length === 0){
  blogPosts = [
    {id:1,title:'Guia rápido: comece hoje',content:'Pequenos passos: água, sono e treino diário de 15 minutos.'},
    {id:2,title:'Treinos de 20 minutos',content:'Circuito simples para queimar calorias sem sair de casa.'}
  ];
  saveBlog();
}

/* Render navigation */
function renderNav(){
  navArea.innerHTML = '';
  const addBtn = (label, cb, style='')=>{
    const b = document.createElement('button'); b.className='btn small'; b.textContent = label; if(style) b.style.background=style;
    b.onclick = cb; navArea.appendChild(b);
  };
  addBtn('Home', ()=>show('home'));
  addBtn('Blog', ()=>show('blog'));
  addBtn('Receitas', ()=>show('recipes'));
  addBtn('Treinos', ()=>show('workouts'));
  addBtn('Contador', ()=>show('calories'));

  if(user){
    const span = document.createElement('div'); span.className='muted small'; span.style.margin='0 8px'; span.textContent = 'Olá, ' + (user.name || 'Amigo');
    navArea.appendChild(span);
    addBtn('Painel', ()=>show('dashboard'));
    addBtn('Sair', ()=>{ logout(); }, '#f87171');
  } else {
    addBtn('Entrar', ()=>{ show('auth'); openAuthTab('login'); }, '#fff');
    addBtn('Cadastre-se', ()=>{ show('auth'); openAuthTab('signup'); }, '#fff');
  }
}
renderNav();

/* Show helper */
function show(name){
  Object.values(sections).forEach(s => s.style.display = 'none');
  if(sections[name]) sections[name].style.display = 'block';
  if(name === 'blog') renderBlog();
  if(name === 'dashboard') renderDashboard();
  if(name === 'calories') renderCalories();
}
show('home');

/* CTA actions */
btnStart.onclick = ()=>{ if(user) show('dashboard'); else { show('auth'); openAuthTab('signup'); } };
btnExplore.onclick = ()=> show('blog');
btnSubscribeHero.onclick = ()=>{ if(!user){ show('auth'); openAuthTab('signup'); } else subscribe(); };

/* AUTH handlers */
function openAuthTab(tab){
  document.getElementById('signupForm').style.display = (tab==='signup') ? 'block' : 'none';
  document.getElementById('loginForm').style.display = (tab==='login') ? 'block' : 'none';
}
document.getElementById('tabSignup').onclick = ()=> openAuthTab('signup');
document.getElementById('tabLogin').onclick = ()=> openAuthTab('login');

document.getElementById('signupBtn').onclick = ()=>{
  const name = document.getElementById('nameIn').value.trim() || 'Visitante';
  const email = document.getElementById('emailIn').value.trim();
  const pass = document.getElementById('passIn').value.trim();
  if(!email || !pass){ alert('Preencha email e senha.'); return; }
  user = { id: Date.now(), name, email, password: pass, subscription:null };
  saveUser(); renderNav(); alert('Conta criada! Bem-vindo(a) ' + name); show('dashboard'); renderDashboard();
};
document.getElementById('loginBtn').onclick = ()=>{
  const email = document.getElementById('emailL').value.trim();
  const pass = document.getElementById('passL').value.trim();
  const saved = JSON.parse(localStorage.getItem('ea_user') || 'null');
  if(saved && saved.email === email && saved.password === pass){
    user = saved; saveUser(); renderNav(); alert('Entrou como ' + (user.name || 'Usuário')); show('dashboard'); renderDashboard();
  } else { alert('Usuário não encontrado ou senha inválida.'); }
};

function logout(){ user = null; localStorage.removeItem('ea_user'); renderNav(); show('home'); alert('Você saiu.'); }

/* Subscription (simulado) */
function subscribe(){
  if(!user){ alert('Faça login para assinar.'); show('auth'); openAuthTab('signup'); return; }
  const next = new Date(); next.setDate(next.getDate() + 14);
  user.subscription = { active:true, priceBRL:6, nextBilling: next.toISOString(), started: new Date().toISOString() };
  saveUser();
  renderNav(); renderDashboard();
  alert('Assinatura ativa: R$6 a cada 2 semanas');
}

/* Blog render & create */
const blogListEl = document.getElementById('blogList');
function renderBlog(){
  blogListEl.innerHTML = '';
  // new post area visibility
  document.getElementById('newPostArea').style.display = (user && user.subscription && user.subscription.active) ? 'block' : 'none';
  if(blogPosts.length === 0){ blogListEl.innerHTML = '<div class="muted">Nenhum post ainda.</div>'; return; }
  blogPosts.slice().reverse().forEach(p=>{
    const div = document.createElement('div'); div.className = 'blog-item'; div.style.marginBottom='8px';
    const t = document.createElement('div'); t.style.fontWeight = 800; t.style.marginBottom = '6px'; t.textContent = p.title;
    const c = document.createElement('div'); c.className='muted'; c.textContent = p.content;
    div.appendChild(t); div.appendChild(c);
    blogListEl.appendChild(div);
  });
}
renderBlog();

document.getElementById('postAddBtn').onclick = ()=>{
  if(!user || !user.subscription || !user.subscription.active){ alert('Somente assinantes podem criar posts.'); return; }
  const title = document.getElementById('postTitle').value.trim();
  const content = document.getElementById('postContent').value.trim();
  if(!title || !content){ alert('Preencha título e conteúdo.'); return; }
  blogPosts.push({ id: Date.now(), title, content });
  saveBlog(); document.getElementById('postTitle').value=''; document.getElementById('postContent').value='';
  alert('Post criado!'); renderBlog();
};

/* Dashboard */
function renderDashboard(){
  const dash = document.getElementById('dashboardCard'); dash.innerHTML = '';
  if(!user){ dash.innerHTML = '<div>Faça login ou cadastre-se para acessar seu painel.</div>'; return; }
  const wrapper = document.createElement('div');
  wrapper.innerHTML = `
    <div style="display:flex;justify-content:space-between;align-items:center">
      <div><strong>Olá, ${user.name || 'Amigo'}</strong><div class="muted small">Painel do usuário</div></div>
      <div><button class="btn small" id="btnLogout" style="background:#ef4444;color:#fff">Sair</button></div>
    </div>
  `;
  if(user.subscription && user.subscription.active){
    const next = new Date(user.subscription.nextBilling).toLocaleDateString();
    const subDiv = document.createElement('div'); subDiv.style.marginTop='12px';
    subDiv.innerHTML = `<div class="card" style="padding:12px;background:#f8fafc"><strong>Assinatura ativa</strong><div class="muted small">Próxima cobrança: ${next}</div></div>`;
    wrapper.appendChild(subDiv);

    const actions = document.createElement('div'); actions.style.marginTop='12px';
    actions.innerHTML = `
      <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px">
        <button class="btn" id="goBlog" style="background:var(--pink);color:#fff">Blog</button>
        <button class="btn" id="goRecipes" style="background:#fb923c;color:#fff">Receitas</button>
        <button class="btn" id="goWorkouts" style="background:#34d399;color:#fff">Treinos</button>
        <button class="btn" id="goCalories" style="background:#60a5fa;color:#fff">Contador</button>
        <button class="btn" id="cancelSub" style="background:#ef4444;color:#fff">Cancelar assinatura</button>
      </div>
    `;
    wrapper.appendChild(actions);
  } else {
    const promo = document.createElement('div'); promo.style.marginTop='12px';
    promo.innerHTML = `<div class="card" style="padding:12px;background:#fff2f2"><strong>Sem assinatura ativa</strong><div class="muted small">Ative por R$6 / 2 semanas e libere todo o conteúdo.</div><div style="margin-top:10px"><button class="btn" id="activateSub" style="background:var(--pink);color:#fff">Ativar agora</button></div></div>`;
    wrapper.appendChild(promo);
  }
  dash.appendChild(wrapper);

  // handlers
  document.getElementById('btnLogout').onclick = ()=>{ logout(); show('home'); };
  if(document.getElementById('goBlog')) document.getElementById('goBlog').onclick = ()=>{ show('blog'); };
  if(document.getElementById('goRecipes')) document.getElementById('goRecipes').onclick = ()=>{ show('recipes'); };
  if(document.getElementById('goWorkouts')) document.getElementById('goWorkouts').onclick = ()=>{ show('workouts'); };
  if(document.getElementById('goCalories')) document.getElementById('goCalories').onclick = ()=>{ show('calories'); };
  if(document.getElementById('activateSub')) document.getElementById('activateSub').onclick = ()=>{ subscribe(); };
  if(document.getElementById('cancelSub')) document.getElementById('cancelSub').onclick = ()=>{
    if(!confirm('Deseja cancelar a assinatura?')) return;
    user.subscription = null; saveUser(); renderNav(); renderDashboard(); alert('Assinatura cancelada.');
  };
}

/* Calories logic */
function renderCalories(){
  const goalInput = document.getElementById('goalInput');
  const foodList = document.getElementById('foodList');
  const totalText = document.getElementById('totalText');
  const progBar = document.getElementById('progBar');
  const alertOver = document.getElementById('alertOver');

  goalInput.value = localStorage.getItem('ea_goal') || 2000;

  document.getElementById('addFoodBtn').onclick = ()=>{
    const name = document.getElementById('foodName').value.trim();
    const kcal = parseInt(document.getElementById('foodCal').value || 0);
    if(!name || !kcal){ alert('Informe alimento e calorias.'); return; }
    foods.push({ id: Date.now(), name, calories: kcal });
    saveFoods(); document.getElementById('foodName').value=''; document.getElementById('foodCal').value='';
    update();
  };

  goalInput.onchange = ()=>{ localStorage.setItem('ea_goal', goalInput.value); update(); };

  function update(){
    const goal = parseInt(goalInput.value || 2000);
    let total = foods.reduce((s,f)=>s + (parseInt(f.calories)||0), 0);
    foodList.innerHTML = '';
    foods.forEach((f, idx)=>{
      const row = document.createElement('div'); row.style.display='flex'; row.style.justifyContent='space-between'; row.style.padding='6px 0';
      row.innerHTML = `<div>${f.name}</div><div style="display:flex;gap:10px;align-items:center"><div>${f.calories} kcal</div><button data-i="${idx}" style="background:transparent;border:none;color:#ef4444;cursor:pointer">x</button></div>`;
      foodList.appendChild(row);
    });
    totalText.textContent = `${total} / ${goal} kcal`;
    const prog = Math.min(100, Math.round((total/goal)*100));
    progBar.style.width = prog + '%';
    alertOver.style.display = (total >= goal) ? 'block' : 'none';

    // delete handlers
    foodList.querySelectorAll('button').forEach(b=>b.onclick = (e)=>{
      const idx = parseInt(e.currentTarget.getAttribute('data-i'));
      foods.splice(idx,1); saveFoods(); update();
    });
  }
  update();
}

/* Initial render */
renderBlog();
renderNav();

/* Sync UI when user exists already */
if(user){ renderNav(); renderDashboard(); }

/* Small helpers for navigation/UI */
document.querySelectorAll('.btn-ghost').forEach(b => b.addEventListener('click', ()=>show('blog')));
document.getElementById('btnStart').addEventListener('click', ()=>{ if(user) show('dashboard'); else { show('auth'); openAuthTab('signup'); } });
document.getElementById('btnExplore').addEventListener('click', ()=> show('blog'));

/* Keep newPostArea visibility up-to-date when login/status changes */
function updateCreateAreaVisibility(){ document.getElementById('newPostArea').style.display = (user && user.subscription && user.subscription.active) ? 'block' : 'none'; }
setInterval(updateCreateAreaVisibility, 1000);

/* Make sure nav updates after signup/login */
document.getElementById('signupBtn').addEventListener('click', ()=> setTimeout(()=>{ renderNav(); updateCreateAreaVisibility(); renderDashboard(); }, 300));
document.getElementById('loginBtn').addEventListener('click', ()=> setTimeout(()=>{ renderNav(); updateCreateAreaVisibility(); renderDashboard(); }, 300));

/* Small UX: show blog if click blog link in nav (event delegation) */
document.addEventListener('click', (e)=>{
  if(e.target && e.target.matches('.link-go-blog')) show('blog');
});
</script>

</body>
</html>
