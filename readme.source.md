# Welcome to my GitHub Profile! ✨

```aura
# Welcome to my Profile! ✨

```aura
<div style={{
  display: 'flex',
  justifyContent: 'center',
  alignItems: 'center',
  background: '#0d1117',
  padding: '30px',
  width: '600px'
}}>

  {/* 🎆 BORDER CONTAINER: This creates the moving glow around your banner */}
  <div style={{
    display: 'flex',
    padding: '6px', /* This is the thickness of your moving border */
    borderRadius: '16px', /* Nice rounded corners */
    background: 'linear-gradient(90deg, #ff007f, #7f00ff, #00f0ff, #ff007f)',
    backgroundSize: '200% 200%',
    animation: 'moveBannerBorder 4s linear infinite', /* Moving color effect */
    boxShadow: '0 8px 24px rgba(0, 240, 255, 0.3)'
  }}>

    {/* 📸 YOUR REPOSITORY BANNER IMAGE */}
    <img 
      src="https://githubusercontent.com" 
      width={550}  /* Banner width */
      height={200} /* Banner height */
      style={{ 
        borderRadius: '12px', /* Fits perfectly inside the border */
        border: '4px solid #0d1117', /* Clean dark line separating pic and colors */
        objectFit: 'cover' /* Stops the image from looking squished */
      }} 
    />

  </div>

  {/* ⚙️ CSS ANIMATION: Slides the colors smoothly from side to side */}
  <style>{`
    @keyframes moveBannerBorder {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  `}</style>

</div>
```

### What to do next:
1. Save and commit this file inside your **`readme.source.md`** file.
2. Go look at your **Actions** tab.
3. Wait for the yellow circle 🟡 to flip into a green checkmark ✅.

<FollowUp>
Once it finishes, head over to your main profile page! Are the colors **moving around your image** correctly now, or did you hit any spacing issues?

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

