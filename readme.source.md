```aura width=900 height=230 align=center
<div style={{ display: 'flex', position: 'relative', width: '100%', height: '100%', background: '#05060a', borderRadius: '14px', alignItems: 'center', justifyContent: 'center' }}>
  <svg width="900" height="230" viewBox="0 0 900 230" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="30%" cy="40%" r="60%">
        <stop offset="0%" stopColor="#7c3aed" stopOpacity="0.85" />
        <stop offset="100%" stopColor="#05060a" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="g2" cx="72%" cy="62%" r="55%">
        <stop offset="0%" stopColor="#06b6d4" stopOpacity="0.8" />
        <stop offset="100%" stopColor="#05060a" stopOpacity="0" />
      </radialGradient>
      <linearGradient id="ln" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stopColor="#22d3ee" />
        <stop offset="50%" stopColor="#a78bfa" />
        <stop offset="100%" stopColor="#f472b6" />
      </linearGradient>
    </defs>
    <ellipse cx="260" cy="95" rx="320" ry="170" fill="url(#g1)">
      <animate attributeName="opacity" values="0.45;0.9;0.45" dur="5s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="translate" values="-50 0;50 0;-50 0" dur="9s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="650" cy="140" rx="300" ry="160" fill="url(#g2)">
      <animate attributeName="opacity" values="0.9;0.45;0.9" dur="7s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="translate" values="50 0;-50 0;50 0" dur="12s" repeatCount="indefinite" />
    </ellipse>
    <line x1="120" y1="178" x2="780" y2="178" stroke="url(#ln)" strokeWidth="2" strokeDasharray="1100" strokeDashoffset="1100">
      <animate attributeName="strokeDashoffset" values="1100;0" dur="3s" repeatCount="indefinite" />
    </line>
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 2 }}>
    <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '70px', fontWeight: 800, letterSpacing: '2px', color: 'transparent', backgroundImage: 'linear-gradient(90deg,#22d3ee,#a78bfa,#f472b6)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>HASSAN AIDIBE</div>
    <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '18px', fontWeight: 500, letterSpacing: '8px', color: '#94a3b8', marginTop: '8px' }}>FULLSTACK DEVELOPER</div>
  </div>
</div>
```

```aura width=900 height=64 align=center
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '10px', padding: '0 22px', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', width: '12px', height: '12px', borderRadius: '6px', background: '#ff5f56', marginRight: '8px' }}></div>
  <div style={{ display: 'flex', width: '12px', height: '12px', borderRadius: '6px', background: '#ffbd2e', marginRight: '8px' }}></div>
  <div style={{ display: 'flex', width: '12px', height: '12px', borderRadius: '6px', background: '#27c93f', marginRight: '20px' }}></div>
  <div style={{ display: 'flex', fontSize: '17px', color: '#22d3ee', marginRight: '12px' }}>~ $</div>
  <div style={{ display: 'flex', fontSize: '17px', color: '#e2e8f0' }}>shipping SaaS in production · open to CDI</div>
  <div style={{ display: 'flex', width: '10px', height: '18px', background: '#a78bfa', marginLeft: '6px' }}></div>
</div>
```

```aura width=900 height=300 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '12px', padding: '24px 30px', color: '#e2e8f0', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', color: '#64748b', fontSize: '15px', marginBottom: '14px' }}>hassan@dev:~$ whoami --stack</div>
  <div style={{ display: 'flex', flexDirection: 'column', fontSize: '15px', lineHeight: '1.7' }}>
    <div style={{ display: 'flex' }}><span style={{ color: '#a78bfa', width: '110px' }}>front</span><span style={{ color: '#e2e8f0' }}>React · Next.js · Vue.js · React Native · TypeScript · TailwindCSS</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#22d3ee', width: '110px' }}>back</span><span style={{ color: '#e2e8f0' }}>Node.js · Express · Laravel · Symfony · PHP · Golang · GraphQL</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#f472b6', width: '110px' }}>infra</span><span style={{ color: '#e2e8f0' }}>Docker · Kubernetes · Terraform · GitHub Actions</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#34d399', width: '110px' }}>ai / ml</span><span style={{ color: '#e2e8f0' }}>Mistral · AssemblyAI · ElevenLabs · GPT-4o · Claude Code</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#fbbf24', width: '110px' }}>data</span><span style={{ color: '#e2e8f0' }}>PostgreSQL · MySQL · Redis</span></div>
  </div>
  <div style={{ display: 'flex', color: '#64748b', fontSize: '15px', margin: '18px 0 12px' }}>hassan@dev:~$ ls --shipped</div>
  <div style={{ display: 'flex', flexDirection: 'column', fontSize: '14px', lineHeight: '1.7' }}>
    <div style={{ display: 'flex' }}><span style={{ color: '#22d3ee', width: '120px' }}>Klark</span><span style={{ color: '#94a3b8' }}>SaaS B2B all-in-one · 12 modules · micro-frontends (Module Federation)</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#a78bfa', width: '120px' }}>Soluweld</span><span style={{ color: '#94a3b8' }}>SaaS B2B · gestion & coordination du soudage industriel</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#f472b6', width: '120px' }}>Gustave AI</span><span style={{ color: '#94a3b8' }}>chatbot IA conciergerie Airbnb · fine-tuning Mistral</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#34d399', width: '120px' }}>Dubba</span><span style={{ color: '#94a3b8' }}>plateforme web de doublage vidéo · word-level + diarisation</span></div>
  </div>
</div>
```

```aura width=900 height=118 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#05060a', borderRadius: '12px', padding: '20px 30px', fontFamily: 'Inter', justifyContent: 'center' }}>
  <div style={{ display: 'flex', color: '#64748b', fontSize: '15px', marginBottom: '10px' }}>hassan@dev:~$ ./contact.sh</div>
  <div style={{ display: 'flex', fontSize: '15px' }}>
    <span style={{ color: '#22d3ee', marginRight: '28px' }}>HETIC · Mastere CTO & Tech Lead</span>
    <span style={{ color: '#a78bfa', marginRight: '28px' }}>linkedin.com/in/Hassan-Aidibe</span>
    <span style={{ color: '#f472b6' }}>github.com/HascoVice</span>
  </div>
</div>
```
