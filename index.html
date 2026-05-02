import { useState } from "react";

// ── 🔧 BAKKA TOKKITTI JIJJIIRI: Render deploy godhee URL kee asitti galchi ──
const BACKEND_URL = "https://osa-backend.onrender.com"; // ← URL kee Render irraa

const COLORS = {
  green:"#1B5E35", greenMid:"#2C7A3A", greenLight:"#3A9B4B",
  gold:"#F5A623", goldLight:"#FFD080", dark:"#0F1F14", card:"#162B1C",
  border:"#2A4D33", text:"#E8F5EA", muted:"#7BB88A",
  white:"#FFFFFF", error:"#FF6B6B", telebirr:"#E8192C",
};

const PRICE = 800;
const TELE  = "0904199725";

const courses = [
  { id:"webdev",          emoji:"🌐", title:"Web Development",       sub:"HTML · CSS · JavaScript",       dur:"Torban 8",  color:"#58A6FF" },
  { id:"entrepreneurship",emoji:"🚀", title:"Entrepreneurship",       sub:"Business Skills & Mindset",     dur:"Torban 8",  color:"#F5A623" },
  { id:"digitalmarketing",emoji:"📣", title:"Digital Marketing",      sub:"Social Media · Branding · SEO", dur:"Torban 6",  color:"#FF6B9D" },
  { id:"graphicdesign",   emoji:"🎨", title:"Graphic Design",         sub:"UI/UX · Canva · Adobe",         dur:"Torban 6",  color:"#BC8CFF" },
  { id:"mobileapp",       emoji:"📱", title:"Mobile App Development", sub:"Flutter · React Native",        dur:"Torban 10", color:"#3FB950" },
  { id:"ai",              emoji:"🤖", title:"AI & Data Skills",       sub:"Python · ML · ChatGPT Tools",   dur:"Torban 8",  color:"#FF9500" },
  { id:"videoediting",    emoji:"🎬", title:"Video Editing",          sub:"CapCut · Premiere · Reels",     dur:"Torban 6",  color:"#F85149" },
];

const regions  = ["Addis Ababa","Oromiyaa","Amaaraa","Tigiraay","Somaalee","Affaar","Beenishaangul-Gumuz","Gambeellaa","Harar","SNNP","Sidaamaa","Guraagee","Wallaggaa"];
const timeSlots= ["Galgala sa'a 2:30–3:30","Galgala sa'a 3:30–4:30","Guyyaa sa'a 9:30–10:30","Guyyaa sa'a 11:00–12:00"];
const durations = ["Ji'a 1","Ji'a 3","Ji'a 6","Ji'a 12"];
const devices   = ["Bilbila harkaa (Smartphone)","Desktop","Laptop","Tablet"];
const edLevels  = ["Kutaa 5–8","Kutaa 9–10","Kutaa 11–12","Koolleejjii","University","Postgraduate"];

const iStyle = {
  width:"100%", background:COLORS.dark, border:`1.5px solid ${COLORS.border}`,
  borderRadius:10, color:COLORS.text, fontSize:15, padding:"12px 16px",
  outline:"none", boxSizing:"border-box", fontFamily:"inherit", transition:"border-color 0.2s",
};

// ── UI Components ─────────────────────────────────────────────────────────────

function Field({ label, required, children, hint }) {
  return (
    <div style={{ marginBottom:24 }}>
      <label style={{ display:"block", color:COLORS.muted, fontSize:12, fontWeight:700,
        letterSpacing:"0.08em", marginBottom:8, textTransform:"uppercase" }}>
        {label}{required && <span style={{ color:COLORS.gold, marginLeft:3 }}>*</span>}
      </label>
      {children}
      {hint && <p style={{ color:COLORS.muted, fontSize:12, marginTop:6, marginBottom:0 }}>{hint}</p>}
    </div>
  );
}

function TInput({ value, onChange, placeholder, type="text" }) {
  const [f,setF] = useState(false);
  return <input type={type} value={value} onChange={e=>onChange(e.target.value)} placeholder={placeholder}
    style={{ ...iStyle, borderColor:f?COLORS.gold:COLORS.border }}
    onFocus={()=>setF(true)} onBlur={()=>setF(false)} />;
}

function Sel({ value, onChange, options, placeholder }) {
  const [f,setF] = useState(false);
  return (
    <select value={value} onChange={e=>onChange(e.target.value)}
      style={{ ...iStyle, borderColor:f?COLORS.gold:COLORS.border, cursor:"pointer",
        appearance:"none",
        backgroundImage:`url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 24 24' fill='none' stroke='%237BB88A' stroke-width='2'%3E%3Cpath d='M6 9l6 6 6-6'/%3E%3C/svg%3E")`,
        backgroundRepeat:"no-repeat", backgroundPosition:"right 14px center", paddingRight:40 }}
      onFocus={()=>setF(true)} onBlur={()=>setF(false)}>
      {placeholder && <option value="" disabled>{placeholder}</option>}
      {options.map(o=><option key={o} value={o} style={{ background:COLORS.dark }}>{o}</option>)}
    </select>
  );
}

function Radio({ options, selected, onChange }) {
  return (
    <div style={{ display:"flex", flexDirection:"column", gap:10 }}>
      {options.map(opt=>(
        <label key={opt} onClick={()=>onChange(opt)}
          style={{ display:"flex", alignItems:"center", gap:12, cursor:"pointer",
            color:selected===opt?COLORS.text:COLORS.muted, fontSize:14, userSelect:"none" }}>
          <span style={{ width:20, height:20, borderRadius:"50%", flexShrink:0,
            border:`2px solid ${selected===opt?COLORS.gold:COLORS.border}`,
            display:"flex", alignItems:"center", justifyContent:"center" }}>
            {selected===opt && <span style={{ width:9, height:9, borderRadius:"50%", background:COLORS.gold }} />}
          </span>
          {opt}
        </label>
      ))}
    </div>
  );
}

function Check({ options, selected, onChange }) {
  const toggle = v => onChange(selected.includes(v)?selected.filter(x=>x!==v):[...selected,v]);
  return (
    <div style={{ display:"flex", flexDirection:"column", gap:10 }}>
      {options.map(opt=>(
        <label key={opt} onClick={()=>toggle(opt)}
          style={{ display:"flex", alignItems:"center", gap:12, cursor:"pointer",
            color:selected.includes(opt)?COLORS.text:COLORS.muted, fontSize:14, userSelect:"none" }}>
          <span style={{ width:20, height:20, borderRadius:5, flexShrink:0,
            border:`2px solid ${selected.includes(opt)?COLORS.gold:COLORS.border}`,
            background:selected.includes(opt)?COLORS.gold:"transparent",
            display:"flex", alignItems:"center", justifyContent:"center", transition:"all 0.15s" }}>
            {selected.includes(opt) && (
              <svg width="11" height="11" viewBox="0 0 12 12" fill="none">
                <path d="M2 6l3 3 5-5" stroke="#0F1F14" strokeWidth="2.2" strokeLinecap="round" strokeLinejoin="round"/>
              </svg>
            )}
          </span>
          {opt}
        </label>
      ))}
    </div>
  );
}

function CourseCard({ c, selected, onToggle }) {
  const on = selected.includes(c.id);
  return (
    <div onClick={()=>onToggle(c.id)} style={{
      background:on?`${c.color}18`:COLORS.card,
      border:`2px solid ${on?c.color:COLORS.border}`,
      borderRadius:14, padding:"14px 12px", cursor:"pointer",
      transition:"all 0.2s", position:"relative", overflow:"hidden" }}>
      {on && (
        <div style={{ position:"absolute", top:8, right:10, width:22, height:22, borderRadius:"50%",
          background:c.color, display:"flex", alignItems:"center", justifyContent:"center" }}>
          <svg width="12" height="12" viewBox="0 0 12 12" fill="none">
            <path d="M2 6l3 3 5-5" stroke="#fff" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round"/>
          </svg>
        </div>
      )}
      <div style={{ fontSize:22, marginBottom:5 }}>{c.emoji}</div>
      <div style={{ fontWeight:700, color:on?COLORS.white:COLORS.text, fontSize:12, marginBottom:2 }}>{c.title}</div>
      <div style={{ color:COLORS.muted, fontSize:10, marginBottom:8, lineHeight:1.4 }}>{c.sub}</div>
      <div style={{ display:"flex", alignItems:"center", justifyContent:"space-between" }}>
        <span style={{ padding:"2px 7px", borderRadius:20, fontSize:9, fontWeight:600,
          background:on?`${c.color}30`:`${COLORS.border}80`,
          color:on?c.color:COLORS.muted }}>{c.dur}</span>
        <span style={{ fontSize:11, fontWeight:800, color:on?COLORS.gold:COLORS.muted }}>{PRICE.toLocaleString()} ብር</span>
      </div>
    </div>
  );
}

function StepBar({ step }) {
  const steps = ["Odeeffannoo","Koorsii","Karooraa","Kaffaltii","Xumuri"];
  return (
    <div style={{ marginBottom:32 }}>
      <div style={{ display:"flex", alignItems:"center" }}>
        {steps.map((s,i)=>{
          const active=i+1===step, done=i+1<step;
          return (
            <div key={s} style={{ display:"flex", alignItems:"center", flex:i<steps.length-1?1:"none" }}>
              <div style={{ display:"flex", flexDirection:"column", alignItems:"center" }}>
                <div style={{ width:30, height:30, borderRadius:"50%", flexShrink:0,
                  background:done?COLORS.gold:active?COLORS.greenLight:COLORS.card,
                  border:`2px solid ${done?COLORS.gold:active?COLORS.gold:COLORS.border}`,
                  display:"flex", alignItems:"center", justifyContent:"center",
                  color:done?COLORS.dark:active?COLORS.white:COLORS.muted,
                  fontWeight:700, fontSize:11, transition:"all 0.3s" }}>
                  {done
                    ? <svg width="13" height="13" viewBox="0 0 14 14" fill="none"><path d="M2.5 7l3 3 6-6" stroke={COLORS.dark} strokeWidth="2.2" strokeLinecap="round" strokeLinejoin="round"/></svg>
                    : i+1}
                </div>
                <span style={{ fontSize:8, color:active?COLORS.gold:COLORS.muted, marginTop:4,
                  fontWeight:active?700:400, whiteSpace:"nowrap" }}>{s}</span>
              </div>
              {i<steps.length-1 && (
                <div style={{ flex:1, height:2, background:done?COLORS.gold:COLORS.border,
                  margin:"0 4px", marginBottom:16, transition:"background 0.3s" }} />
              )}
            </div>
          );
        })}
      </div>
    </div>
  );
}

function SecTitle({ icon, text }) {
  return (
    <div style={{ display:"flex", alignItems:"center", gap:10, marginBottom:24 }}>
      <span style={{ fontSize:20 }}>{icon}</span>
      <h2 style={{ color:COLORS.white, fontSize:17, fontWeight:700, margin:0 }}>{text}</h2>
      <div style={{ flex:1, height:1, background:COLORS.border, marginLeft:8 }} />
    </div>
  );
}

function SRow({ label, value }) {
  return (
    <div style={{ display:"flex", gap:12, marginBottom:9, fontSize:13 }}>
      <span style={{ color:COLORS.muted, minWidth:100 }}>{label}</span>
      <span style={{ color:COLORS.text, flex:1 }}>{value||"—"}</span>
    </div>
  );
}

function Divider() {
  return <div style={{ height:1, background:COLORS.border, margin:"22px 0" }} />;
}

// ── Main App ──────────────────────────────────────────────────────────────────

export default function App() {
  const [step,    setStep]    = useState(1);
  const [done,    setDone]    = useState(false);
  const [loading, setLoading] = useState(false);
  const [error,   setError]   = useState("");
  const [copied,  setCopied]  = useState(false);

  const [form, setForm] = useState({
    fullName:"", dob:"", region:"", gender:"", phone:"", education:"",
    courses:[], time:"", duration:"", devices:[], inviteFriends:"",
    expectation:"", comments:"", txId:"", payerName:"",
  });

  const set = f => v => setForm(x=>({...x,[f]:v}));

  const toggleCourse = id => set("courses")(
    form.courses.includes(id) ? form.courses.filter(c=>c!==id) : [...form.courses, id]
  );

  const total = form.courses.length * PRICE;

  const canNext = () => {
    if (step===1) return form.fullName&&form.dob&&form.region&&form.gender&&form.phone&&form.education;
    if (step===2) return form.courses.length>0;
    if (step===3) return form.time&&form.duration&&form.devices.length>0&&form.inviteFriends;
    if (step===4) return !!form.txId;
    return true;
  };

  const copyNum = () => {
    navigator.clipboard?.writeText(TELE).catch(()=>{});
    setCopied(true); setTimeout(()=>setCopied(false), 2000);
  };

  // ── Submit to Render backend ──────────────────────────────────────────────
  const handleSubmit = async () => {
    setLoading(true);
    setError("");
    try {
      const res = await fetch(`${BACKEND_URL}/submit`, {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({
          ...form,
          courses: form.courses.map(id => courses.find(c=>c.id===id)?.title || id),
          total,
        }),
      });
      const data = await res.json();
      if (!res.ok || !data.ok) throw new Error(data.message || "Server error");
      setDone(true);
    } catch (err) {
      setError(`❌ Dogoggora: ${err.message}. Interneti mirkaneessi ykn booda yaali.`);
    } finally {
      setLoading(false);
    }
  };

  // ── Success Screen ────────────────────────────────────────────────────────
  if (done) return (
    <div style={{ minHeight:"100vh", background:COLORS.dark, display:"flex", alignItems:"center",
      justifyContent:"center", padding:24, fontFamily:"Georgia,serif" }}>
      <div style={{ textAlign:"center", maxWidth:420 }}>
        <div style={{ fontSize:60, marginBottom:14 }}>🎉</div>
        <div style={{ fontSize:24, fontWeight:700, color:COLORS.gold, marginBottom:10 }}>
          Galatoomi, {form.fullName.split(" ")[0]}!
        </div>
        <div style={{ color:COLORS.muted, fontSize:14, lineHeight:1.7, marginBottom:24 }}>
          Galmeen kee milkaa'inaan ergame! Gareen OSA Telegram irratti beeksifame — guyyaa 1–2 keessatti si quunnama.
        </div>
        {/* Summary */}
        <div style={{ background:COLORS.card, border:`1px solid ${COLORS.border}`, borderRadius:14,
          padding:18, textAlign:"left", marginBottom:16 }}>
          <div style={{ color:COLORS.muted, fontSize:11, fontWeight:700, letterSpacing:"0.08em",
            textTransform:"uppercase", marginBottom:12 }}>Koorsiiwwan Filatamte</div>
          {form.courses.map(cid=>{
            const c = courses.find(x=>x.id===cid);
            return (
              <div key={cid} style={{ display:"flex", alignItems:"center", gap:10, marginBottom:9 }}>
                <span style={{ fontSize:16 }}>{c?.emoji}</span>
                <span style={{ color:COLORS.text, fontSize:13, flex:1 }}>{c?.title}</span>
                <span style={{ color:COLORS.gold, fontSize:12, fontWeight:700 }}>{PRICE.toLocaleString()} ብር</span>
              </div>
            );
          })}
          <div style={{ height:1, background:COLORS.border, margin:"10px 0" }} />
          <div style={{ display:"flex", justifyContent:"space-between" }}>
            <span style={{ color:COLORS.muted, fontSize:13 }}>Waliigala</span>
            <span style={{ color:COLORS.gold, fontWeight:800, fontSize:16 }}>{total.toLocaleString()} ብር</span>
          </div>
        </div>
        <div style={{ background:`${COLORS.telebirr}18`, border:`1px solid ${COLORS.telebirr}40`,
          borderRadius:10, padding:"10px 16px", fontSize:13, color:COLORS.text, marginBottom:20 }}>
          📲 Transaction ID: <strong style={{ color:COLORS.gold }}>{form.txId}</strong>
        </div>
        <div style={{ color:COLORS.muted, fontSize:11 }}>
          IFA DARGAGGOOTAA MUL'ATA ISAANII KEESSATTI ✨<br/>
          <span style={{ color:COLORS.border }}>Oromia Skills Academy · osk.academy</span>
        </div>
      </div>
    </div>
  );

  // ── Main Form ─────────────────────────────────────────────────────────────
  return (
    <div style={{ minHeight:"100vh", background:COLORS.dark, fontFamily:"Georgia,serif", paddingBottom:60 }}>

      {/* Header */}
      <div style={{ background:`linear-gradient(135deg,${COLORS.green} 0%,${COLORS.dark} 100%)`,
        padding:"28px 24px 22px", textAlign:"center", borderBottom:`1px solid ${COLORS.border}`,
        position:"relative", overflow:"hidden" }}>
        <div style={{ position:"absolute", top:-40, right:-40, width:150, height:150,
          borderRadius:"50%", background:`${COLORS.gold}10`, pointerEvents:"none" }} />
        <div style={{ display:"inline-block", background:COLORS.gold, color:COLORS.dark, fontSize:10,
          fontWeight:800, letterSpacing:"0.15em", padding:"4px 14px", borderRadius:20,
          marginBottom:10, textTransform:"uppercase" }}>Oromia Skills Academy</div>
        <h1 style={{ color:COLORS.white, fontSize:22, fontWeight:700, margin:"0 0 6px", lineHeight:1.3 }}>
          Barnoota Technology<br/><span style={{ color:COLORS.gold }}>Bilisaan</span>
        </h1>
        <p style={{ color:`${COLORS.text}88`, fontSize:12, margin:0 }}>
          Koorsii filadhu · Telebirr kaffalti · <strong style={{ color:COLORS.goldLight }}>Barnoota jalqabi!</strong>
        </p>
        {form.courses.length > 0 && (
          <div style={{ marginTop:12, display:"inline-block", background:`${COLORS.gold}22`,
            border:`1px solid ${COLORS.gold}50`, borderRadius:20, padding:"4px 14px",
            color:COLORS.gold, fontSize:13, fontWeight:700 }}>
            💳 Waliigala: {total.toLocaleString()} ብር
          </div>
        )}
      </div>

      <div style={{ maxWidth:560, margin:"0 auto", padding:"28px 18px 0" }}>
        <StepBar step={step} />

        {/* ── Step 1: Personal Info ── */}
        {step===1 && (
          <div>
            <SecTitle icon="👤" text="Odeeffannoo Dhuunfaa" />
            <Field label="Maqaa Guutuu" required>
              <TInput value={form.fullName} onChange={set("fullName")} placeholder="Fkn: Chaltu Gurmessa Dida" />
            </Field>
            <Field label="Guyyaa Dhalootaa" required>
              <TInput value={form.dob} onChange={set("dob")} type="date" />
            </Field>
            <Field label="Godina/Bulchiinsa Jiraattan" required>
              <Sel value={form.region} onChange={set("region")} options={regions} placeholder="Filadhu..." />
            </Field>
            <Field label="Saala" required>
              <Radio options={["Dhiira","Dhalaa"]} selected={form.gender} onChange={set("gender")} />
            </Field>
            <Field label="Lakkoofsa Bilbilaa" required hint="Lakkoofsa Telegram ykn WhatsApp qabdu galchi">
              <TInput value={form.phone} onChange={set("phone")} placeholder="+251 9XX XXX XXX" type="tel" />
            </Field>
            <Field label="Sadarkaa Barnootaa" required>
              <Sel value={form.education} onChange={set("education")} options={edLevels} placeholder="Filadhu..." />
            </Field>
          </div>
        )}

        {/* ── Step 2: Course Selection ── */}
        {step===2 && (
          <div>
            <SecTitle icon="📚" text="Koorsii Filannoo" />
            <div style={{ background:`${COLORS.gold}15`, border:`1px solid ${COLORS.gold}40`,
              borderRadius:10, padding:"10px 14px", marginBottom:18,
              display:"flex", alignItems:"center", gap:10 }}>
              <span style={{ fontSize:18 }}>💰</span>
              <span style={{ color:COLORS.goldLight, fontSize:13, lineHeight:1.5 }}>
                Koorsii tokkoon <strong>{PRICE.toLocaleString()} ብር</strong> — Telebirr <strong>{TELE}</strong>
              </span>
            </div>
            <div style={{ display:"grid", gridTemplateColumns:"1fr 1fr", gap:11, marginBottom:8 }}>
              {courses.map(c=><CourseCard key={c.id} c={c} selected={form.courses} onToggle={toggleCourse} />)}
            </div>
            {form.courses.length > 0 && (
              <div style={{ marginTop:14, padding:"12px 16px", background:`${COLORS.gold}18`,
                border:`1px solid ${COLORS.gold}40`, borderRadius:10,
                display:"flex", justifyContent:"space-between", alignItems:"center" }}>
                <span style={{ color:COLORS.goldLight, fontSize:13 }}>✓ Koorsiiwwan {form.courses.length} filatameera</span>
                <span style={{ color:COLORS.gold, fontWeight:800, fontSize:16 }}>{total.toLocaleString()} ብር</span>
              </div>
            )}
          </div>
        )}

        {/* ── Step 3: Schedule ── */}
        {step===3 && (
          <div>
            <SecTitle icon="📅" text="Karooraa fi Meeshaalee" />
            <Field label="Sa'aatii Barnootaa Mijaawaa" required>
              <Radio options={timeSlots} selected={form.time} onChange={set("time")} />
            </Field>
            <Divider />
            <Field label="Yeroo Hammam Baratta?" required>
              <div style={{ display:"grid", gridTemplateColumns:"1fr 1fr", gap:10 }}>
                {durations.map(d=>(
                  <div key={d} onClick={()=>set("duration")(d)} style={{
                    padding:"12px 16px", borderRadius:10, textAlign:"center", cursor:"pointer",
                    border:`2px solid ${form.duration===d?COLORS.gold:COLORS.border}`,
                    background:form.duration===d?`${COLORS.gold}18`:COLORS.card,
                    color:form.duration===d?COLORS.gold:COLORS.muted,
                    fontWeight:form.duration===d?700:400, fontSize:14, transition:"all 0.15s" }}>{d}</div>
                ))}
              </div>
            </Field>
            <Divider />
            <Field label="Meeshaalee Qabda" required hint="Waan hunda filachuu dandeessa">
              <Check options={devices} selected={form.devices} onChange={set("devices")} />
            </Field>
            <Divider />
            <Field label="Hiriyyoota Kee Affeeruu Barbaadda?" required>
              <Radio options={["Eyyee, nan afeera!","Lakki","Itti nan yaada"]}
                selected={form.inviteFriends} onChange={set("inviteFriends")} />
            </Field>
            <Divider />
            <Field label="Dhuma Barnoota Kanaa Irratti Maal Eegda?">
              <textarea value={form.expectation} onChange={e=>set("expectation")(e.target.value)}
                placeholder="Fkn: Weebsaayite daldala kootii hojjechuuf..." rows={3}
                style={{ ...iStyle, resize:"vertical", minHeight:80, lineHeight:1.6 }} />
            </Field>
          </div>
        )}

        {/* ── Step 4: Payment ── */}
        {step===4 && (
          <div>
            <SecTitle icon="📲" text="Kaffaltii — Telebirr" />
            {/* Price breakdown */}
            <div style={{ background:COLORS.card, border:`1px solid ${COLORS.border}`, borderRadius:14, padding:18, marginBottom:20 }}>
              <div style={{ color:COLORS.muted, fontSize:11, fontWeight:700, letterSpacing:"0.1em",
                textTransform:"uppercase", marginBottom:12 }}>Koorsiiwwan Filatamte</div>
              {form.courses.map(cid=>{
                const c=courses.find(x=>x.id===cid);
                return (
                  <div key={cid} style={{ display:"flex", alignItems:"center", gap:10, marginBottom:9 }}>
                    <span style={{ fontSize:16 }}>{c?.emoji}</span>
                    <span style={{ color:COLORS.text, fontSize:13, flex:1 }}>{c?.title}</span>
                    <span style={{ color:COLORS.gold, fontSize:13, fontWeight:700 }}>{PRICE.toLocaleString()} ብር</span>
                  </div>
                );
              })}
              <div style={{ height:1, background:COLORS.border, margin:"12px 0" }} />
              <div style={{ display:"flex", justifyContent:"space-between", alignItems:"center" }}>
                <span style={{ color:COLORS.muted, fontSize:13 }}>Koorsiiwwan {form.courses.length} × {PRICE} ብር</span>
                <span style={{ color:COLORS.gold, fontSize:20, fontWeight:800 }}>{total.toLocaleString()} ብር</span>
              </div>
            </div>

            {/* Telebirr card */}
            <div style={{ background:"linear-gradient(135deg,#C0001A 0%,#E8192C 50%,#FF3347 100%)",
              borderRadius:16, padding:22, marginBottom:22, position:"relative", overflow:"hidden" }}>
              <div style={{ position:"absolute", top:-30, right:-30, width:110, height:110,
                borderRadius:"50%", background:"rgba(255,255,255,0.08)" }} />
              <div style={{ display:"flex", alignItems:"center", gap:10, marginBottom:16 }}>
                <span style={{ fontSize:26 }}>📲</span>
                <div>
                  <div style={{ color:COLORS.white, fontWeight:800, fontSize:17 }}>Telebirr</div>
                  <div style={{ color:"rgba(255,255,255,0.7)", fontSize:11 }}>Kaffaltii Bilbilaan</div>
                </div>
              </div>
              {[
                "Telebirr app kee bani",
                `"Send Money" cuqaasi`,
                `Lakkoofsa ${TELE} galchi`,
                `${total.toLocaleString()} ብር ergi`,
                "Confirmation ID / Screenshot kee ↓ galchi",
              ].map((s,i)=>(
                <div key={i} style={{ display:"flex", alignItems:"flex-start", gap:10, marginBottom:10 }}>
                  <span style={{ width:22, height:22, borderRadius:"50%", background:"rgba(255,255,255,0.2)",
                    display:"flex", alignItems:"center", justifyContent:"center",
                    color:COLORS.white, fontSize:10, fontWeight:800, flexShrink:0, marginTop:1 }}>{i+1}</span>
                  <span style={{ color:"rgba(255,255,255,0.9)", fontSize:13, lineHeight:1.5 }}>{s}</span>
                </div>
              ))}
              {/* Number chip */}
              <div style={{ background:"rgba(0,0,0,0.25)", borderRadius:10, padding:"12px 14px",
                display:"flex", alignItems:"center", justifyContent:"space-between", marginTop:6 }}>
                <div>
                  <div style={{ color:"rgba(255,255,255,0.55)", fontSize:9, marginBottom:3, letterSpacing:"0.08em" }}>TELEBIRR LAKKOOFSA</div>
                  <div style={{ color:COLORS.white, fontWeight:800, fontSize:20, letterSpacing:"0.1em" }}>{TELE}</div>
                </div>
                <button onClick={copyNum} style={{ background:copied?"rgba(255,255,255,0.3)":"rgba(255,255,255,0.15)",
                  border:"1.5px solid rgba(255,255,255,0.4)", borderRadius:8, color:COLORS.white,
                  fontSize:12, fontWeight:700, padding:"8px 12px", cursor:"pointer",
                  fontFamily:"inherit", transition:"all 0.2s" }}>
                  {copied?"✓ Copied!":"📋 Copy"}
                </button>
              </div>
            </div>

            <Field label="Transaction ID / Confirmation Code" required
              hint="Telebirr irraa ergaa mirkaneessaa keessaa argatta">
              <TInput value={form.txId} onChange={set("txId")} placeholder="Fkn: TXN2024XXXXXX" />
            </Field>
            <Field label="Maqaa Kaffaltaa (Yoo Adda Ta'e)" hint="Yoo bilbilli adda ta'e galchi">
              <TInput value={form.payerName} onChange={set("payerName")}
                placeholder="Maqaa Telebirr irratti galame" />
            </Field>
            <div style={{ background:`${COLORS.gold}15`, border:`1px solid ${COLORS.gold}40`,
              borderRadius:10, padding:"10px 14px", fontSize:13, color:COLORS.goldLight, lineHeight:1.6 }}>
              ⚠️ Kaffaltiin mirkanaayee booda qofa galmeen ni fudhatama. Gareen OSA guyyaa 1–2 keessatti si quunnama.
            </div>
          </div>
        )}

        {/* ── Step 5: Confirm ── */}
        {step===5 && (
          <div>
            <SecTitle icon="✅" text="Xumuri — Mirkaneessi" />
            <div style={{ background:COLORS.card, border:`1px solid ${COLORS.border}`,
              borderRadius:14, padding:20, marginBottom:18 }}>
              <div style={{ color:COLORS.muted, fontSize:11, fontWeight:700, letterSpacing:"0.1em",
                textTransform:"uppercase", marginBottom:14 }}>Gabaasa Galmee</div>
              <SRow label="Maqaa"        value={form.fullName} />
              <SRow label="Bilbila"      value={form.phone} />
              <SRow label="Godina"       value={form.region} />
              <SRow label="Barnoota"     value={form.education} />
              <SRow label="Koorsiiwwan"  value={form.courses.map(id=>courses.find(c=>c.id===id)?.title).join(", ")} />
              <SRow label="Yeroo"        value={form.time} />
              <SRow label="Muddama"      value={form.duration} />
              <div style={{ height:1, background:COLORS.border, margin:"10px 0" }} />
              <SRow label="Waliigala"    value={`${total.toLocaleString()} ብር`} />
              <SRow label="Tx ID"        value={form.txId} />
            </div>

            {/* Error message */}
            {error && (
              <div style={{ background:`${COLORS.error}18`, border:`1px solid ${COLORS.error}50`,
                borderRadius:10, padding:"12px 14px", fontSize:13, color:COLORS.error,
                lineHeight:1.6, marginBottom:16 }}>
                {error}
              </div>
            )}

            <div style={{ background:`${COLORS.greenLight}18`, border:`1px solid ${COLORS.greenLight}40`,
              borderRadius:10, padding:"12px 14px", fontSize:13, color:COLORS.text, lineHeight:1.6 }}>
              ✅ Odeeffannoon hundi sirriidha yoo ta'e — "Galmee Xumuri" cuqaasi. Ergaan Telegram @yondan0011 tti ergama!
            </div>
          </div>
        )}

        {/* ── Navigation ── */}
        <div style={{ display:"flex", gap:12, marginTop:28 }}>
          {step > 1 && (
            <button onClick={()=>{ setError(""); setStep(step-1); }} style={{
              flex:1, padding:"14px 0", borderRadius:12,
              border:`1.5px solid ${COLORS.border}`, background:"transparent",
              color:COLORS.muted, fontSize:15, fontWeight:600,
              cursor:"pointer", fontFamily:"inherit" }}>
              ← Duubatti
            </button>
          )}
          <button
            onClick={()=>{
              if (step < 5) { setError(""); setStep(step+1); }
              else handleSubmit();
            }}
            disabled={!canNext() || loading}
            style={{
              flex:2, padding:"14px 0", borderRadius:12, border:"none",
              background: !canNext() || loading
                ? COLORS.border
                : step===4
                  ? `linear-gradient(135deg,${COLORS.telebirr} 0%,#C0001A 100%)`
                  : `linear-gradient(135deg,${COLORS.gold} 0%,#E8960E 100%)`,
              color: !canNext() || loading ? COLORS.muted : COLORS.white,
              fontSize:15, fontWeight:700,
              cursor: !canNext() || loading ? "not-allowed" : "pointer",
              transition:"all 0.2s", fontFamily:"inherit",
              display:"flex", alignItems:"center", justifyContent:"center", gap:8 }}>
            {loading
              ? <><Spinner /> Ergaa jira...</>
              : step===5 ? "✓ Galmee Xumuri & Ergi"
              : step===4 ? "📲 Kaffaltii Mirkaneessi →"
              : "Itti Fufuu →"}
          </button>
        </div>

        <p style={{ textAlign:"center", color:COLORS.muted, fontSize:11, marginTop:18 }}>
          Oromia Skills Academy · Barnoota Technology Bilisaan · osk.academy
        </p>
      </div>
    </div>
  );
}

function Spinner() {
  return (
    <svg width="16" height="16" viewBox="0 0 24 24" fill="none"
      style={{ animation:"spin 0.8s linear infinite" }}>
      <style>{`@keyframes spin{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}`}</style>
      <circle cx="12" cy="12" r="10" stroke="rgba(255,255,255,0.3)" strokeWidth="3"/>
      <path d="M12 2a10 10 0 0 1 10 10" stroke="white" strokeWidth="3" strokeLinecap="round"/>
    </svg>
  );
}
