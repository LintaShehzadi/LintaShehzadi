# Welcome to my GitHub Profile! ✨

```aura
<div style={{
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'center',
  alignItems: 'center',
  width: '600px',
  padding: '4px', /* This creates space for the moving border to show */
  borderRadius: '24px',
  background: 'linear-gradient(90deg, #ff007f, #7f00ff, #00f0ff, #ff007f)',
  backgroundSize: '300% 300%',
  animation: 'moveBorder 6s linear infinite',
  fontFamily: '"Space Grotesk", "Segoe UI", sans-serif', /* 💅 Custom sleek font */
  boxShadow: '0 12px 40px rgba(0,0,0,0.5)'
}}>
  
  {/* Inner Content Card */}
  <div style={{
    display: 'flex',
    flexDirection: 'column',
    background: '#0d1117', /* Dark GitHub background */
    width: '100%',
    padding: '30px',
    borderRadius: '20px',
    gap: '20px'
  }}>
    
    {/* Heading with Cool Gradient Text */}
    <h1 style={{ 
      margin: 0, 
      fontSize: '32px', 
      fontWeight: 'bold',
      background: 'linear-gradient(to right, #00f0ff, #7f00ff)',
      WebkitBackgroundClip: 'text',
      WebkitTextFillColor: 'transparent'
    }}>
      Hello, I'm a Developer! 🚀
    </h1>

    <p style={{ color: '#8b949e', fontSize: '16px', margin: 0, lineHeight: '1.5' }}>
      Building beautiful user experiences and mastering code step-by-step.
    </p>

    {/* Languages Section */}
    <div style={{ display: 'flex', gap: '12px', flexWrap: 'wrap', marginTop: '10px' }}>
      <div style={{ background: 'rgba(0, 240, 255, 0.1)', border: '1px solid #00f0ff', padding: '8px 16px', borderRadius: '20px', color: '#00f0ff', fontWeight: 'bold' }}>
        🟨 JavaScript
      </div>
      <div style={{ background: 'rgba(127, 0, 255, 0.1)', border: '1px solid #7f00ff', padding: '8px 16px', borderRadius: '20px', color: '#a347ff', fontWeight: 'bold' }}>
        🟦 Python
      </div>
      <div style={{ background: 'rgba(255, 0, 127, 0.1)', border: '1px solid #ff007f', padding: '8px 16px', borderRadius: '20px', color: '#ff47a3', fontWeight: 'bold' }}>
        🎨 UI/UX Design
      </div>
    </div>

  </div>

  {/* CSS Code to make the border move and crawl */}
  <style>{`
    @keyframes moveBorder {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  `}</style>
</div>
```

