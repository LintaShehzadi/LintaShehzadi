# My Profile Banner 🌌

```aura
<div style={{
  display: 'flex',
  justifyContent: 'center',
  alignItems: 'center',
  background: '#0d1117',
  padding: '30px',
  width: '600px'
}}>

  {/* 🎆 BORDER CONTAINER: This box animates the colors around the banner */}
  <div style={{
    display: 'flex',
    padding: '6px', /* This sets the thickness of your moving border */
    borderRadius: '16px', /* Makes it a rectangle with rounded corners */
    background: 'linear-gradient(90deg, #ff007f, #7f00ff, #00f0ff, #ff007f)',
    backgroundSize: '200% 200%',
    animation: 'moveBannerBorder 4s linear infinite', /* Moving border animation */
    boxShadow: '0 8px 24px rgba(0, 240, 255, 0.3)'
  }}>

    {/* 📸 YOUR BANNER IMAGE: This fits inside the moving border */}
    <img 
      src="https://githubusercontent.com" 
      width={550}  /* Wide banner width */
      height={200} /* Shorter banner height */
      style={{ 
        borderRadius: '12px', /* Fits neatly inside the outer border */
        border: '4px solid #0d1117', /* Adds a crisp dark gap before the glowing border */
        objectFit: 'cover' /* Keeps your image from stretching or looking squished */
      }} 
    />

  </div>

  {/* ⚙️ CSS KEYFRAMES: This makes the neon gradient colors slide across the rectangle banner */}
  <style>{`
    @keyframes moveBannerBorder {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
  `}</style>

</div>
```
