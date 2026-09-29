<!DOCTYPE html>
<html lang="vi"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>SWAPDROBE – Trao đổi đồ sinh viên</title>
<link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;800&display=swap" rel="stylesheet">
<style>
:root{--bg:#fff;--fg:#1a1a1a;--mut:#6b6b6b;--line:#e7e2e4;--soft:#f6f2f4;--pri:#CD5782;--pri2:#b3436b;--tint:#fbeaf1;--ok:#1f8f5f;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#151214;--fg:#f4eff2;--mut:#a99fa5;--line:#352f33;--soft:#1f1b1d;--tint:#33202a}}
:root[data-theme="dark"]{--bg:#151214;--fg:#f4eff2;--mut:#a99fa5;--line:#352f33;--soft:#1f1b1d;--tint:#33202a}
*,*:before,*:after{box-sizing:inherit}html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--fg);font:400 15px/1.5 "Be Vietnam Pro",system-ui,-apple-system,"Segoe UI",sans-serif}
button,input,select,textarea{font:inherit;color:inherit}
h1,h2,h3,p{margin:0}a{color:inherit}
:focus-visible{outline:2px solid var(--pri);outline-offset:2px}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:20;background:var(--bg);border-bottom:1px solid var(--line)}
.hd{max-width:1240px;margin:auto;display:flex;align-items:center;gap:20px;padding:10px 20px}
.logo{display:flex;align-items:center;gap:10px;background:none;border:0;cursor:pointer;padding:0}
.logo b{background:var(--pri);color:#fff;width:44px;height:44px;display:grid;place-items:center;font-weight:800;font-size:11px;line-height:1;letter-spacing:.02em;text-align:center}
.logo span{font-weight:800;font-size:19px;letter-spacing:-.01em}
nav{display:flex;gap:4px;flex:1}
nav button{background:none;border:0;padding:8px 12px;cursor:pointer;font-weight:500;border-bottom:2px solid transparent;position:relative}
nav button.on{border-color:var(--pri);color:var(--pri)}
nav i{font-style:normal;background:var(--pri);color:#fff;border-radius:9px;font-size:11px;padding:0 6px;margin-left:4px}
.me{display:flex;align-items:center;gap:8px;background:none;border:1px solid var(--line);border-radius:22px;padding:4px 12px 4px 4px;cursor:pointer}
.av{width:30px;height:30px;border-radius:50%;background:var(--pri);color:#fff;display:grid;place-items:center;font-weight:600}
.tick{display:inline-grid;place-items:center;width:15px;height:15px;border-radius:50%;background:#1d9bf0;color:#fff;font-size:10px;vertical-align:1px}
.strip{background:var(--tint);text-align:center;padding:8px 16px;font-size:14px}
.strip button{background:none;border:0;color:var(--pri2);font-weight:600;text-decoration:underline;cursor:pointer}
main{max-width:1240px;margin:auto;padding:0 20px 60px}
.btn{background:var(--pri);color:#fff;border:0;padding:10px 18px;font-weight:600;cursor:pointer;border-radius:2px}
.btn:hover{background:var(--pri2)}.btn.ghost{background:none;color:var(--fg);border:1px solid var(--fg)}.btn.ghost:hover{background:var(--soft)}
.btn.sm{padding:6px 12px;font-size:13px}.btn[disabled]{opacity:.5;cursor:not-allowed}
.hero{display:grid;grid-template-columns:1.1fr .9fr;gap:30px;align-items:center;background:var(--soft);margin:20px 0 0;padding:48px}
.hero h1{font-size:clamp(34px,5.4vw,66px);line-height:1.04;font-weight:800;letter-spacing:-.03em}
.hero p{margin:16px 0 24px;max-width:46ch;color:var(--mut);font-size:17px}
.hero .cta{display:flex;gap:10px;flex-wrap:wrap}
.stack{position:relative;height:300px}
.stack div{position:absolute;width:190px;height:240px;border-radius:4px;display:grid;place-items:center;font-size:76px;box-shadow:0 8px 22px rgba(0,0,0,.14);border:6px solid #fff}
.stack div:nth-child(1){left:6%;top:30px;transform:rotate(-9deg);background:#f5d5e2}
.stack div:nth-child(2){left:32%;top:0;transform:rotate(4deg);background:#d9e8f5}
.stack div:nth-child(3){left:54%;top:40px;transform:rotate(12deg);background:#dff0dd}
.how{display:grid;grid-template-columns:repeat(4,1fr);gap:0;margin:0;border-bottom:1px solid var(--line)}
.how div{padding:20px;border-right:1px solid var(--line)}.how div:last-child{border:0}
.how b{display:block;margin-bottom:2px}.how span{color:var(--mut);font-size:14px}
.tabs{display:flex;gap:6px;overflow-x:auto;padding:22px 0 0;border-bottom:1px solid var(--line)}
.tab{background:none;border:0;padding:8px 14px;cursor:pointer;white-space:nowrap;border-bottom:3px solid transparent;font-weight:500}
.tab.on{border-color:var(--pri);color:var(--pri);font-weight:600}
.tools{display:flex;flex-wrap:wrap;gap:10px;align-items:center;padding:16px 0}
.tools input,.tools select,.f input,.f select,.f textarea{border:1px solid var(--line);background:var(--bg);padding:9px 12px;border-radius:2px;min-width:0}
.tools input{flex:1;min-width:180px}
.seg{display:flex;border:1px solid var(--line)}.seg button{background:none;border:0;padding:8px 14px;cursor:pointer}.seg .on{background:var(--fg);color:var(--bg)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:22px 16px}
.card .art{position:relative;aspect-ratio:4/5;display:grid;place-items:center;font-size:72px;cursor:pointer;overflow:hidden}
.card .art img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.cond{position:absolute;left:0;bottom:0;background:var(--fg);color:var(--bg);font-style:normal;font-size:12px;font-weight:600;padding:3px 9px}
.cb{padding-top:10px}.cb h3{font-size:15px;font-weight:600;line-height:1.3}
.who,.loc{font-size:13px;color:var(--mut)}
.bar{display:flex;gap:6px;margin-top:10px;align-items:center}.bar .btn{flex:1;padding:8px 6px;font-size:13px}
.ic{width:36px;height:36px;border:1px solid var(--line);background:var(--bg);cursor:pointer;border-radius:2px}
.deck{max-width:400px;margin:0 auto}.deck .card .art{font-size:110px}.deck .bar .btn{font-size:14px}
.deckn{text-align:center;color:var(--mut);font-size:13px;margin-top:10px}
.empty{padding:50px 10px;text-align:center;color:var(--mut)}.empty .btn{margin-top:12px}
h2.t{font-size:26px;font-weight:800;letter-spacing:-.02em;margin:30px 0 6px}
.sub{color:var(--mut);margin-bottom:18px}
.f{display:grid;gap:14px;max-width:640px}.f label{display:grid;gap:5px;font-weight:500;font-size:14px}.f small{color:var(--mut);font-weight:400}
.r2{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.ph{display:flex;gap:8px;flex-wrap:wrap}.ph .p{width:86px;height:86px;border:1px dashed var(--mut);display:grid;place-items:center;background:var(--soft);cursor:pointer;overflow:hidden;font-size:24px;color:var(--mut)}.ph img{width:100%;height:100%;object-fit:cover}
.ol{display:grid;gap:12px;max-width:820px}
.o{border:1px solid var(--line);padding:16px;display:grid;gap:10px}
.o .row{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
.mini{display:flex;align-items:center;gap:8px;background:var(--soft);padding:6px 10px;font-size:13px;border-radius:2px}.mini s{text-decoration:none;font-size:22px}
.st{font-size:12px;font-weight:600;padding:2px 9px;border-radius:10px;background:var(--soft)}.st.a{background:var(--tint);color:var(--pri2)}.st.d{background:#dff3e8;color:var(--ok)}
.arrow{font-size:20px;color:var(--pri)}
.ov{position:fixed;inset:0;background:rgba(0,0,0,.5);z-index:50;display:grid;place-items:center;padding:16px}
.sheet{background:var(--bg);width:min(640px,100%);max-height:calc(100vh - 32px);overflow:auto;padding:24px;position:relative;border-radius:4px}
.sheet h3{font-size:21px;font-weight:800;margin-bottom:4px;padding-right:30px}
.x{position:absolute;right:10px;top:8px;background:none;border:0;font-size:26px;cursor:pointer}
.pick{display:flex;gap:10px;align-items:center;border:1px solid var(--line);padding:8px 10px;cursor:pointer;margin:6px 0}.pick:has(input:checked){border-color:var(--pri);background:var(--tint)}
.spots{display:flex;flex-wrap:wrap;gap:8px;margin:8px 0}.spots label{border:1px solid var(--line);padding:6px 12px;cursor:pointer;border-radius:18px;font-size:14px}.spots label:has(input:checked){background:var(--pri);color:#fff;border-color:var(--pri)}.spots input{display:none}
.chat{border:1px solid var(--line);height:190px;overflow:auto;padding:10px;display:flex;flex-direction:column;gap:6px;margin:8px 0}
.msg{max-width:80%;padding:6px 11px;background:var(--soft);border-radius:12px;font-size:14px}.msg.me{align-self:flex-end;background:var(--pri);color:#fff}
.cs{display:flex;gap:6px}.cs input{flex:1;border:1px solid var(--line);background:var(--bg);padding:8px 10px}
.stars button{background:none;border:0;font-size:32px;cursor:pointer;color:var(--line)}.stars .on{color:#f5a623}
.chk{display:grid;gap:8px;margin:14px 0}.chk div{display:flex;gap:10px;align-items:center;padding:10px;background:var(--soft)}
.toast{position:fixed;left:50%;bottom:calc(24px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);background:var(--fg);color:var(--bg);padding:10px 18px;z-index:80;border-radius:3px;max-width:90vw}
.prof{display:flex;gap:18px;align-items:center;flex-wrap:wrap;margin:26px 0}.prof .av{width:72px;height:72px;font-size:30px}
.stats{display:flex;gap:26px;margin:6px 0 0}.stats b{font-size:22px;display:block}.stats span{font-size:13px;color:var(--mut)}
footer{border-top:1px solid var(--line);padding:26px 20px;text-align:center;color:var(--mut);font-size:13px}
@media(max-width:820px){.hero{grid-template-columns:1fr;padding:28px 20px}.stack{height:240px}.stack div{width:140px;height:180px;font-size:54px}.how{grid-template-columns:1fr 1fr}.how div{border-bottom:1px solid var(--line)}.hd{gap:8px;padding:8px 12px}.logo span{display:none}nav button{padding:8px 7px;font-size:13px}.me span:last-child{display:none}.me{padding:3px}.r2{grid-template-columns:1fr}}
@media(prefers-reduced-motion:reduce){*{transition:none!important;animation:none!important}}
</style></head><body>
<header><div class="hd" id="hd"></div><div id="bn"></div></header>
<main id="app"></main>
<footer>SWAPDROBE · Nền tảng trao đổi đồ dành riêng cho sinh viên · Cũ người mới ta.</footer>
<div id="mo"></div><div id="ts"></div>
<script>
const CATS=['Sách vở/Giáo trình','Đồ điện tử','Quần áo/Phụ kiện','Đồ dùng KTX','Khác'];
const CE={'Sách vở/Giáo trình':'📚','Đồ điện tử':'🎧','Quần áo/Phụ kiện':'👕','Đồ dùng KTX':'🌀','Khác':'🎁'};
const CC={'Sách vở/Giáo trình':'#f5d5e2','Đồ điện tử':'#d9e8f5','Quần áo/Phụ kiện':'#fbe8c8','Đồ dùng KTX':'#dff0dd','Khác':'#e6ddf3'};
const SCH=['ĐH Ngoại Thương','ĐH Bách Khoa','ĐH Quốc Gia','ĐH Kinh tế Quốc dân','ĐH Sư phạm','ĐH Y Hà Nội','ĐH FPT'];
const CONDS=['Mới 100%','Mới 95%','Mới 90%','Mới 85%','Mới 80%','Cũ 70%'];
const SPOTS=['Cổng trường','Thư viện','KTX','Quán cafe gần trường','Căng tin'];
const mk=(id,t,cat,cond,who,school,loc,desc,want)=>({id,t,cat,cond,who,school,loc,desc,want});
const SEED=[
mk(1,'Giáo trình Kinh tế vi mô','Sách vở/Giáo trình','Mới 90%','Linh Trần','ĐH Bách Khoa','KTX Khu B','Bản mới nhất, có highlight nhẹ ở chương 3–5.','Quạt mini hoặc tai nghe'),
mk(2,'Quạt tích điện để bàn','Đồ dùng KTX','Mới 95%','Minh Anh','ĐH Ngoại Thương','Cổng trường','Pin dùng được khoảng 6 tiếng, 3 tốc độ gió.','Sách tiếng Anh'),
mk(3,'Áo khoác denim oversize','Quần áo/Phụ kiện','Mới 90%','Hà My','ĐH Kinh tế Quốc dân','Thư viện','Size M, form rộng, mặc 3–4 lần.','Hoodie hoặc túi tote'),
mk(4,'Tai nghe Sony có dây','Đồ điện tử','Mới 85%','Đức Long','ĐH Quốc Gia','Cơ sở 1','Âm thanh tốt, jack 3.5mm, đệm tai còn mềm.','Sách IELTS'),
mk(5,'Máy tính Casio fx-580VN X','Đồ điện tử','Mới 95%','Bảo Ngọc','ĐH Quốc Gia','Thư viện','Đã dùng 1 kỳ, còn hộp và nắp.','Đèn học'),
mk(6,'Đèn học LED kẹp bàn','Đồ dùng KTX','Mới 90%','Quang Huy','ĐH Bách Khoa','KTX Khu A','3 mức sáng, kẹp chắc, dây dài 1.5m.','Nồi cơm mini'),
mk(7,'Túi tote canvas in hình','Quần áo/Phụ kiện','Mới 95%','Thu Trang','ĐH Sư phạm','Cổng trường','Vải dày, có khoá kéo và túi phụ.','Áo thun basic'),
mk(8,'Cambridge IELTS 16 + đáp án','Sách vở/Giáo trình','Mới 90%','Phương Vy','ĐH Ngoại Thương','Căng tin','Chưa viết vào sách, kèm file audio.','Bàn phím hoặc chuột'),
mk(9,'Bàn phím cơ 87 phím','Đồ điện tử','Mới 90%','Tuấn Kiệt','ĐH FPT','Cơ sở 2','Switch đỏ, có keycap thay thế.','Loa mini'),
mk(10,'Nồi cơm điện mini 0.6L','Đồ dùng KTX','Mới 85%','Ngọc Bích','ĐH Y Hà Nội','KTX Khu C','Nấu 1–2 người, có xửng hấp.','Đèn học'),
mk(11,'Hoodie basic màu xám','Quần áo/Phụ kiện','Mới 95%','Gia Hân','ĐH Kinh tế Quốc dân','Thư viện','Size L, nỉ dày, không xù lông.','Áo khoác nhẹ'),
mk(12,'Bộ dụng cụ vẽ kỹ thuật','Khác','Mới 90%','Hoàng Nam','ĐH Bách Khoa','KTX Khu A','Thước, compa, bút kim đủ bộ.','Sách chuyên ngành')];
let S={user:null,items:SEED,saved:[],offers:[],chats:{},reviews:[],n:100};
try{const r=localStorage.getItem('swapdrobe');if(r)S=Object.assign(S,JSON.parse(r))}catch(_){}
const save=()=>{try{localStorage.setItem('swapdrobe',JSON.stringify(S,(k,v)=>k==='imgs'?undefined:v))}catch(_){}};
const $=s=>document.querySelector(s),e=s=>String(s??'').replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const ver=()=>S.user&&S.user.st==='v',isMe=n=>S.user&&n===S.user.name,item=id=>S.items.find(i=>i.id==id),TK='<span class="tick" title="Sinh viên đã xác thực">✓</span>';
let view='home',F={cat:'',school:'',q:'',mode:'grid'},D=0,W={};
function toast(m){$('#ts').innerHTML=`<div class="toast" role="status">${e(m)}</div>`;clearTimeout(toast.t);toast.t=setTimeout(()=>$('#ts').innerHTML='',2600)}
function modal(h){$('#mo').innerHTML=`<div class="ov" data-a="bg"><div class="sheet" role="dialog" aria-modal="true"><button class="x" data-a="close" aria-label="Đóng">×</button>${h}</div></div>`}
const closeM=()=>$('#mo').innerHTML='';
document.addEventListener('keydown',ev=>{if(ev.key==='Escape')closeM()});
function go(v){view=v;render();scrollTo(0,0)}
function gate(){if(!S.user){authM();return 0}if(!ver()){verifyM();toast('Cần xác thực thẻ sinh viên để tiếp tục');return 0}return 1}
const pending=()=>S.offers.filter(o=>o.to===S.user?.name&&o.status==='pending').length;
/* ---------- header ---------- */
function head(){
const n=(v,t,x='')=>`<button class="${view===v?'on':''}" data-a="go" data-id="${v}">${t}${x}</button>`;
$('#hd').innerHTML=`<button class="logo" data-a="go" data-id="home" aria-label="SWAPDROBE trang chủ"><b>SWAP<br>DROBE</b><span>SWAPDROBE</span></button>
<nav>${n('home','Khám phá')}${n('up','Đăng đồ')}${n('swaps','Swap của tôi',pending()?`<i>${pending()}</i>`:'')}${n('saved','Đã lưu')}</nav>
${S.user?`<button class="me" data-a="go" data-id="prof"><span class="av">${e(S.user.name[0])}</span><span>${e(S.user.name.split(' ').pop())}</span>${ver()?TK:''}</button>`:`<button class="btn" data-a="auth">Đăng nhập / Đăng ký</button>`}`;
$('#bn').innerHTML=S.user&&!ver()?`<div class="strip">Tài khoản chưa xác thực: bạn chỉ có thể xem đồ. <button data-a="verify">Xác thực thẻ sinh viên</button></div>`:''}
/* ---------- cards ---------- */
function card(i){const mine=isMe(i.who);
return `<article class="card"><div class="art" data-a="open" data-id="${i.id}" style="background:${CC[i.cat]}" role="button" tabindex="0" aria-label="Xem ${e(i.t)}">${i.imgs&&i.imgs[0]?`<img src="${i.imgs[0]}" alt="">`:CE[i.cat]}<em class="cond">${i.cond}</em></div>
<div class="cb"><h3>${e(i.t)}</h3><p class="who">${e(i.who)} ${TK} · ${e(i.school)}</p><p class="loc">📍 ${e(i.loc)}</p>
<div class="bar"><button class="ic" data-a="fav" data-id="${i.id}" aria-label="Lưu">${S.saved.includes(i.id)?'❤️':'🤍'}</button>${mine?'<span class="who">Đồ của bạn</span>':`<button class="ic" data-a="chat" data-id="${i.id}" aria-label="Hỏi nhanh">💬</button><button class="btn" data-a="offer" data-id="${i.id}">🔄 Offer Swap</button>`}</div></div></article>`}
function list(){return S.items.filter(i=>(!F.cat||i.cat===F.cat)&&(!F.school||i.school===F.school)&&(!F.q||(i.t+' '+i.desc+' '+i.who).toLowerCase().includes(F.q.toLowerCase())))}
function grid(){const l=list(),g=$('#grid');if(!g)return;
if(!l.length){g.className='';g.innerHTML=`<div class="empty"><p>Chưa có món đồ nào khớp bộ lọc.</p><button class="btn ghost" data-a="reset">Xoá bộ lọc</button></div>`;return}
if(F.mode==='deck'){D=Math.min(D,l.length-1);g.className='deck';g.innerHTML=card(l[D])+`<div class="bar" style="margin-top:14px"><button class="btn ghost" data-a="prev">‹ Trước</button><button class="btn ghost" data-a="next">Bỏ qua ›</button></div><p class="deckn">${D+1} / ${l.length}</p>`}
else{g.className='grid';g.innerHTML=l.map(card).join('')}}
const V={};
V.home=()=>`<section class="hero"><div><h1>Cũ người mới ta.</h1><p>Đổi đồ trực tiếp giữa sinh viên với nhau, không cần tiền. Đồ 0đ với bạn có thể là báu vật với người khác.</p><div class="cta"><button class="btn" data-a="scroll">Bắt đầu lướt</button><button class="btn ghost" data-a="go" data-id="up">Đăng món đồ đầu tiên</button></div></div><div class="stack" aria-hidden="true"><div>📚</div><div>🎧</div><div>👕</div></div></section>
<section class="how"><div><b>1. Xác thực</b><span>Email .edu.vn và thẻ sinh viên</span></div><div><b>2. Gửi offer</b><span>Chọn 1–3 món của bạn để đổi</span></div><div><b>3. Hẹn gặp</b><span>Địa điểm an toàn gần trường</span></div><div><b>4. Đánh giá</b><span>Chấm sao sau khi đổi xong</span></div></section>
<div class="tabs" id="tabs"><button class="tab on" data-a="cat" data-id="">Tất cả</button>${CATS.map(c=>`<button class="tab" data-a="cat" data-id="${c}">${CE[c]} ${c}</button>`).join('')}</div>
<div class="tools"><input id="q" type="search" placeholder="Tìm giáo trình, quạt, áo khoác…" aria-label="Tìm kiếm"><select id="sc" aria-label="Lọc theo trường"><option value="">Tất cả trường / khu vực</option>${SCH.map(s=>`<option>${s}</option>`).join('')}</select><div class="seg"><button class="on" data-a="mode" data-id="grid">Lưới</button><button data-a="mode" data-id="deck">Lướt card</button></div></div><div id="grid"></div>`;
V.saved=()=>{const l=S.items.filter(i=>S.saved.includes(i.id));return `<h2 class="t">Đã lưu</h2><p class="sub">Những món bạn muốn quay lại xem.</p>${l.length?`<div class="grid">${l.map(card).join('')}</div>`:`<div class="empty"><p>Bạn chưa lưu món nào. Bấm 🤍 trên một món đồ để lưu.</p><button class="btn" data-a="go" data-id="home">Đi khám phá</button></div>`}`};
V.up=()=>`<h2 class="t">Đăng đồ</h2><p class="sub">Một trang, vài phút là xong. Chỉ tài khoản đã xác thực mới đăng được.</p>
<form class="f" id="uf" onsubmit="return false"><div style="display:grid;gap:5px;font-weight:500;font-size:14px">Ảnh (tối đa 5)<div class="ph" id="ph"></div><input id="pf" type="file" accept="image/*" multiple hidden></div>
<label>Tên sản phẩm<input id="u1" maxlength="70" placeholder="VD: Giáo trình Giải tích 1"></label>
<div class="r2"><label>Danh mục<select id="u2">${CATS.map(c=>`<option>${c}</option>`).join('')}</select></label><label>Tình trạng<select id="u3">${CONDS.map(c=>`<option>${c}</option>`).join('')}</select></label></div>
<label>Mô tả ngắn<textarea id="u4" rows="3" maxlength="200" placeholder="Đã dùng bao lâu, có lỗi gì không?"></textarea></label>
<label>Món đồ mong muốn đổi lại <small>(không bắt buộc, chỉ để gợi ý)</small><input id="u5" placeholder="VD: Quạt mini, sách tiếng Anh"></label>
<label>Vị trí tiện giao dịch<input id="u6" placeholder="VD: KTX Khu A, Cơ sở 1"></label>
<button class="btn" data-a="publish">Đăng món đồ</button></form>`;
V.prof=()=>{if(!S.user)return `<div class="empty"><p>Đăng nhập để xem hồ sơ.</p><button class="btn" data-a="auth">Đăng nhập / Đăng ký</button></div>`;const u=S.user,my=S.items.filter(i=>isMe(i.who)),done=S.offers.filter(o=>o.status==='done').length;
return `<div class="prof"><span class="av">${e(u.name[0])}</span><div><h2 class="t" style="margin:0">${e(u.name)} ${ver()?TK:''}</h2><p class="who">${e(u.school)} · ${e(u.email)}</p><p>${ver()?`<span class="st d">Verified Student · MSSV ${e(u.sid)}</span>`:`<span class="st">Unverified</span> <button class="btn sm" data-a="verify">Xác thực ngay</button>`}</p>
<div class="stats"><div><b>${my.length}</b><span>Món đang đăng</span></div><div><b>${done}</b><span>Swap hoàn thành</span></div><div><b>${S.reviews.length?(S.reviews.reduce((a,r)=>a+r.s,0)/S.reviews.length).toFixed(1):'–'}</b><span>Sao trung bình</span></div></div></div></div>
<h3>Đồ của tôi</h3>${my.length?`<div class="grid" style="margin:12px 0 26px">${my.map(card).join('')}</div>`:`<p class="sub">Chưa có món nào. <a href="#" data-a="go" data-id="up">Đăng món đầu tiên</a></p>`}
<h3>Đánh giá đã gửi</h3>${S.reviews.length?S.reviews.map(r=>`<p style="margin:8px 0"><span style="color:#f5a623">${'★'.repeat(r.s)}</span> cho <b>${e(r.about)}</b> ${r.t?'· '+e(r.t):''}</p>`).join(''):'<p class="sub">Chưa có đánh giá nào.</p>'}
<p style="margin-top:30px"><button class="btn ghost sm" data-a="logout">Đăng xuất & xoá dữ liệu demo</button></p>`};
V.swaps=()=>{if(!S.user)return `<div class="empty"><p>Đăng nhập để quản lý các offer swap.</p><button class="btn" data-a="auth">Đăng nhập / Đăng ký</button></div>`;
const me=S.user.name,l=[...S.offers].reverse();
const mini=i=>i?`<span class="mini"><s>${CE[i.cat]}</s>${e(i.t)}</span>`:'';
return `<h2 class="t">Swap của tôi</h2><p class="sub">Offer bạn nhận, offer bạn gửi và các buổi hẹn.</p><div class="ol">${l.length?l.map(o=>{const inn=o.to===me,other=inn?o.by:o.to,stt={pending:['Chờ phản hồi',''],acc:['Đã chấp nhận','a'],done:['Hoàn thành','d'],no:['Đã từ chối','']}[o.status];
return `<div class="o"><div class="row"><b>${inn?'Offer nhận từ':'Offer gửi tới'} ${e(other)}</b><span class="st ${stt[1]}">${stt[0]}</span></div>
<div class="row">${o.give.map(id=>mini(item(id))).join('')}<span class="arrow">⇄</span>${mini(item(o.target))}</div>
${o.note?`<p class="who">“${e(o.note)}”</p>`:''}${o.when?`<p>📍 ${e(o.where)} · 🕒 ${e(o.when)}</p>`:''}
<div class="row">${o.status==='pending'&&inn?`<button class="btn sm" data-a="accept" data-id="${o.id}">Accept Offer</button><button class="btn ghost sm" data-a="decline" data-id="${o.id}">Từ chối</button>`:''}
${o.status==='pending'&&!inn?`<button class="btn ghost sm" data-a="cancel" data-id="${o.id}">Huỷ offer</button><button class="btn ghost sm" data-a="fake" data-id="${o.id}" title="Chỉ có trong bản demo">Demo: đối phương chấp nhận</button>`:''}
${o.status==='acc'?`<button class="btn sm" data-a="meet" data-id="${o.id}">Hẹn địa điểm & Chat</button>${o.doneMe?'<span class="who">Đang chờ bên kia xác nhận…</span>':`<button class="btn ghost sm" data-a="complete" data-id="${o.id}">Complete Swap</button>`}`:''}
${o.status==='done'&&!o.rated?`<button class="btn sm" data-a="rate" data-id="${o.id}">Đánh giá ${e(other)}</button>`:''}</div></div>`}).join(''):`<div class="empty"><p>Chưa có offer nào. Vào Khám phá và bấm “Offer Swap” trên món bạn thích.</p><button class="btn" data-a="go" data-id="home">Đi khám phá</button></div>`}</div>`};
function render(){head();$('#app').innerHTML=V[view]();if(view==='home')grid();if(view==='up')photos()}
/* ---------- auth & verification ---------- */
function authM(){W={};modal(`<h3>Tạo tài khoản sinh viên</h3><p class="sub">Cần email .edu.vn để nhận mã OTP.</p><div class="f" id="af">
<label>Họ và tên<input id="a1" autocomplete="name"></label><label>Trường Đại học / Cao đẳng<select id="a2">${SCH.map(s=>`<option>${s}</option>`).join('')}</select></label>
<label>Email sinh viên<input id="a3" type="email" placeholder="ten.sv@truong.edu.vn" autocomplete="email"></label><p id="ae" class="who" style="color:var(--pri2)"></p><button class="btn" data-a="otp">Gửi mã OTP</button></div>`)}
function otpStep(){modal(`<h3>Nhập mã OTP</h3><p class="sub">Mã 6 số đã gửi tới ${e(W.email)}. <b>Bản demo: mã là ${W.code}</b></p><div class="f"><label>Mã OTP<input id="a4" inputmode="numeric" maxlength="6"></label><p id="ae" class="who" style="color:var(--pri2)"></p><button class="btn" data-a="otpok">Xác nhận</button></div>`)}
function verifyM(){modal(`<h3>Xác thực thẻ sinh viên</h3><p class="sub">Tải ảnh 2 mặt thẻ (hoặc mã QR ứng dụng của trường). Hệ thống kiểm tra Mã SV, Họ tên và Trường.</p><div class="f" id="vf"><div class="r2"><label>Mặt trước<input id="v1" type="file" accept="image/*"></label><label>Mặt sau / QR<input id="v2" type="file" accept="image/*"></label></div>
<label>Mã sinh viên<input id="v3" placeholder="VD: 2211110045"></label><p class="who">Họ tên: ${e(S.user.name)} · Trường: ${e(S.user.school)}</p><p id="ae" class="who" style="color:var(--pri2)"></p><button class="btn" data-a="scan">Gửi xác thực</button></div>`)}
function scan(){const sid=$('#v3').value.trim();if(!$('#v1').files[0]||!$('#v2').files[0])return $('#ae').textContent='Hãy tải đủ ảnh 2 mặt thẻ.';if(sid.length<6)return $('#ae').textContent='Mã sinh viên cần ít nhất 6 ký tự.';
const rows=[['Mã sinh viên',sid],['Họ và tên',S.user.name],['Trường',S.user.school]];
$('#vf').innerHTML=`<div class="chk">${rows.map((r,k)=>`<div id="c${k}">⏳ Đang đọc ${r[0]}…</div>`).join('')}</div>`;
rows.forEach((r,k)=>setTimeout(()=>{$('#c'+k).innerHTML=`✅ ${r[0]}: <b>${e(r[1])}</b>`;if(k===2)setTimeout(()=>finish(sid),600)},700*(k+1)))}
function finish(sid){S.user.st='v';S.user.sid=sid;const me=S.user.name;
if(!S.items.some(i=>isMe(i.who))){S.items.unshift(mk(S.n++,'Áo thun basic trắng','Quần áo/Phụ kiện','Mới 95%',me,S.user.school,'Cổng trường','Cotton 100%, size M, ít mặc.','Sách chuyên ngành'),mk(S.n++,'Sổ tay ô ly A5 (3 quyển)','Khác','Mới 100%',me,S.user.school,'Thư viện','Chưa viết, bìa cứng.','Bút hoặc đèn học'));
S.offers.push({id:S.n++,by:'Linh Trần',to:me,target:S.items[0].id,give:[4],note:'Mình đổi tai nghe Sony lấy áo của bạn nhé!',status:'pending',msgs:[]})}
save();render();modal(`<h3>Đã xác thực ${TK}</h3><p class="sub">Bạn nhận được Tích Xanh Sinh Viên. Từ giờ bạn có thể đăng đồ và gửi offer. Chúng mình đã thêm 2 món mẫu và 1 offer để bạn thử luồng swap.</p><button class="btn" data-a="close">Bắt đầu</button>`)}
/* ---------- offer / meetup / chat / rating ---------- */
function offerM(id){const t=item(id),my=S.items.filter(i=>isMe(i.who));W.t=id;
modal(`<h3>Offer Swap cho “${e(t.t)}”</h3><p class="sub">Chọn 1–3 món của bạn để đổi lấy. ${t.want?`${e(t.who)} đang tìm: <b>${e(t.want)}</b>.`:''}</p>
${my.length?my.map(i=>`<label class="pick"><input type="checkbox" value="${i.id}"><span style="font-size:24px">${CE[i.cat]}</span><span>${e(i.t)}<br><small class="who">${i.cond}</small></span></label>`).join(''):`<div class="empty"><p>Bạn chưa có món nào trên sàn.</p><button class="btn" data-a="go" data-id="up">Đăng đồ trước</button></div>`}
${my.length?`<div class="f"><label>Lời nhắn (tuỳ chọn)<input id="on" maxlength="120" placeholder="Mình muốn đổi cuốn sách này lấy cái quạt KTX của bạn nhé!"></label><p id="ae" class="who" style="color:var(--pri2)"></p><button class="btn" data-a="send">Gửi offer</button></div>`:''}`)}
function chatBox(k){return `<div class="chat" id="cl">${(S.chats[k]||[]).map(m=>`<div class="msg ${m.me?'me':''}">${e(m.t)}</div>`).join('')||'<span class="who">Chưa có tin nhắn. Hãy chào một câu!</span>'}</div><div class="cs"><input id="ci" placeholder="Nhập tin nhắn…" aria-label="Tin nhắn"><button class="btn sm" data-a="say" data-id="${k}">Gửi</button></div>`}
function chatM(k,title){modal(`<h3>${e(title)}</h3>${chatBox(k)}`)}
function meetM(id){const o=S.offers.find(x=>x.id==id),other=o.by===S.user.name?o.to:o.by,d=new Date().toISOString().slice(0,10);W.o=id;
modal(`<h3>Hẹn địa điểm swap với ${e(other)}</h3><p class="sub">Chọn nơi công cộng, đông người, gần trường.</p><div class="f"><div class="spots">${SPOTS.map(s=>`<label><input type="radio" name="sp" value="${s}" ${o.where===s?'checked':''}>${s}</label>`).join('')}</div>
<div class="r2"><label>Ngày<input id="md" type="date" min="${d}" value="${o.date||d}"></label><label>Giờ<input id="mt" type="time" value="${o.time||'12:00'}"></label></div><button class="btn" data-a="plan">Lưu lịch hẹn</button></div>
<h3 style="margin-top:20px;font-size:17px">Chat trực tiếp</h3>${chatBox('o'+id)}`)}
function rateM(id){W={o:id,s:0};modal(`<h3>Đánh giá uy tín</h3><p class="sub">Trải nghiệm swap của bạn thế nào?</p><div class="stars" id="st">${[1,2,3,4,5].map(n=>`<button data-a="star" data-id="${n}" aria-label="${n} sao">★</button>`).join('')}</div><div class="f"><label>Nhận xét<input id="rt" maxlength="120" placeholder="Đúng hẹn, đồ giống mô tả…"></label><p id="ae" class="who" style="color:var(--pri2)"></p><button class="btn" data-a="rsend">Gửi đánh giá</button></div>`)}
function photos(){W.im=W.im||[];$('#ph').innerHTML=W.im.map(s=>`<div class="p"><img src="${s}" alt=""></div>`).join('')+(W.im.length<5?`<div class="p" id="add" role="button" tabindex="0" aria-label="Thêm ảnh">＋</div>`:'')}
/* ---------- actions ---------- */
const A={
go:id=>{closeM();go(id)},close:closeM,bg:(id,b,ev)=>{if(ev.target===b)closeM()},auth:authM,verify:verifyM,scan,
scroll:()=>$('#tabs').scrollIntoView({behavior:'smooth'}),
cat:id=>{F.cat=id;D=0;document.querySelectorAll('.tab').forEach(t=>t.classList.toggle('on',t.dataset.id===id));grid()},
mode:(id,b)=>{F.mode=id;D=0;document.querySelectorAll('.seg button').forEach(x=>x.classList.toggle('on',x===b));grid()},
reset:()=>{F.cat='';F.school='';F.q='';render()},prev:()=>{D=Math.max(0,D-1);grid()},next:()=>{D=Math.min(list().length-1,D+1);grid()},
fav:id=>{id=+id;S.saved=S.saved.includes(id)?S.saved.filter(x=>x!==id):[...S.saved,id];save();view==='saved'?render():grid();if(view!=='home'&&view!=='saved')render();toast(S.saved.includes(id)?'Đã lưu món đồ':'Đã bỏ lưu')},
open:id=>{const i=item(id),mine=isMe(i.who);modal(`<div class="card"><div class="art" style="background:${CC[i.cat]};cursor:default;aspect-ratio:16/10">${i.imgs&&i.imgs[0]?`<img src="${i.imgs[0]}" alt="">`:CE[i.cat]}<em class="cond">${i.cond}</em></div></div><h3 style="margin-top:14px">${e(i.t)}</h3><p class="who">${e(i.who)} ${TK} · ${e(i.school)} · 📍 ${e(i.loc)}</p><p style="margin:10px 0">${e(i.desc)||'Chưa có mô tả.'}</p>${i.want?`<p class="mini">Mong muốn đổi lại: <b>${e(i.want)}</b></p>`:''}<div class="bar" style="margin-top:14px">${mine?'<span class="who">Đây là đồ của bạn</span>':`<button class="ic" data-a="chat" data-id="${i.id}">💬</button><button class="btn" data-a="offer" data-id="${i.id}">🔄 Offer Swap</button>`}</div>`)},
chat:id=>{if(!S.user)return authM();const i=item(id);chatM('i'+id,'Hỏi nhanh '+i.who+' về “'+i.t+'”')},
say:k=>{const v=$('#ci').value.trim();if(!v)return;(S.chats[k]=S.chats[k]||[]).push({me:1,t:v});$('#ci').value='';paint(k);save();
setTimeout(()=>{(S.chats[k]=S.chats[k]||[]).push({t:['Ok bạn nhé 👍','Mình rảnh chiều nay, bạn thì sao?','Đồ còn nguyên nhé, yên tâm!'][S.chats[k].length%3]});paint(k);save()},1100)},
offer:id=>{if(gate())offerM(id)},
send:()=>{const g=[...document.querySelectorAll('.pick input:checked')].map(x=>+x.value);if(!g.length||g.length>3)return $('#ae').textContent='Chọn từ 1 đến 3 món để đổi.';
const t=item(W.t);S.offers.push({id:S.n++,by:S.user.name,to:t.who,target:t.id,give:g,note:$('#on').value.trim(),status:'pending',msgs:[]});save();closeM();go('swaps');toast('Đã gửi offer swap')},
accept:id=>{const o=S.offers.find(x=>x.id==id);o.status='acc';save();render();meetM(id)},
decline:id=>{S.offers.find(x=>x.id==id).status='no';save();render()},
cancel:id=>{S.offers=S.offers.filter(x=>x.id!=id);save();render()},
fake:id=>{S.offers.find(x=>x.id==id).status='acc';save();render();toast('Offer của bạn đã được chấp nhận. Hãy hẹn địa điểm.')},
meet:meetM,
plan:()=>{const o=S.offers.find(x=>x.id==W.o),s=document.querySelector('input[name=sp]:checked');if(!s)return toast('Chọn một địa điểm hẹn');o.where=s.value;o.date=$('#md').value;o.time=$('#mt').value;o.when=o.date.split('-').reverse().join('/')+' lúc '+o.time;save();render();closeM();toast('Đã lưu lịch hẹn')},
complete:id=>{const o=S.offers.find(x=>x.id==id);o.doneMe=1;save();render();toast('Đã xác nhận. Chờ đối phương bấm Complete Swap…');
setTimeout(()=>{o.status='done';save();if(view==='swaps')render();toast('Cả hai đã hoàn thành. Hãy đánh giá nhau!')},1800)},
rate:rateM,star:id=>{W.s=+id;document.querySelectorAll('#st button').forEach((b,k)=>b.classList.toggle('on',k<W.s))},
rsend:()=>{if(!W.s)return $('#ae').textContent='Chọn số sao từ 1 đến 5.';const o=S.offers.find(x=>x.id==W.o);o.rated=1;S.reviews.push({about:o.by===S.user.name?o.to:o.by,s:W.s,t:$('#rt').value.trim()});save();closeM();render();toast('Cảm ơn bạn đã đánh giá')},
otp:()=>{const n=$('#a1').value.trim(),m=$('#a3').value.trim();if(n.length<2)return $('#ae').textContent='Nhập họ và tên của bạn.';
if(!/^[^\s@]+@[^\s@]+\.edu\.vn$/i.test(m))return $('#ae').textContent='Cần email sinh viên có đuôi .edu.vn.';W={name:n,school:$('#a2').value,email:m,code:String(100000+Math.floor(Math.random()*899999))};otpStep()},
otpok:()=>{if($('#a4').value.trim()!==W.code)return $('#ae').textContent='Mã OTP chưa đúng. Kiểm tra lại mã trên màn hình.';
S.user={name:W.name,school:W.school,email:W.email,st:'u'};save();render();modal(`<h3>Tạo tài khoản thành công</h3><p class="sub">Tài khoản đang ở trạng thái <b>Unverified</b>: bạn chỉ được xem đồ. Xác thực thẻ sinh viên để đăng đồ và gửi offer.</p><div class="bar"><button class="btn" data-a="verify">Xác thực ngay</button><button class="btn ghost" data-a="close">Để sau</button></div>`)},
publish:()=>{if(!gate())return;const t=$('#u1').value.trim();if(t.length<3)return toast('Nhập tên sản phẩm');if(!$('#u6').value.trim())return toast('Nhập vị trí tiện giao dịch');
const n=mk(S.n++,t,$('#u2').value,$('#u3').value,S.user.name,S.user.school,$('#u6').value.trim(),$('#u4').value.trim(),$('#u5').value.trim());n.imgs=W.im||[];S.items.unshift(n);W.im=[];save();F.cat='';go('prof');toast('Đã đăng món đồ')},
logout:()=>{try{localStorage.removeItem('swapdrobe')}catch(_){}location.reload()}};
function paint(k){const c=$('#cl');if(c){c.innerHTML=S.chats[k].map(m=>`<div class="msg ${m.me?'me':''}">${e(m.t)}</div>`).join('');c.scrollTop=c.scrollHeight}}
document.addEventListener('click',ev=>{if(ev.target.id==='add'||ev.target.closest('#add')){if(!gate())return;$('#pf').click();return}
const b=ev.target.closest('[data-a]');if(!b)return;ev.preventDefault();const f=A[b.dataset.a];f&&f(b.dataset.id,b,ev)});
document.addEventListener('keydown',ev=>{if(ev.key==='Enter'&&ev.target.id==='ci')document.querySelector('[data-a=say]').click();if((ev.key==='Enter'||ev.key===' ')&&ev.target.getAttribute('role')==='button'){ev.preventDefault();ev.target.click()}});
document.addEventListener('input',ev=>{if(ev.target.id==='q'){F.q=ev.target.value;D=0;grid()}});
document.addEventListener('change',ev=>{const t=ev.target;if(t.id==='sc'){F.school=t.value;D=0;grid()}
if(t.id==='pf'){[...t.files].slice(0,5-(W.im||[]).length).forEach(f=>{const r=new FileReader();r.onload=()=>{(W.im=W.im||[]).push(r.result);photos()};r.readAsDataURL(f)});t.value=''}});
render();
</script></body></html>
