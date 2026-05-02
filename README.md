# CSS-tips

## Liquid Glass (iOS 26)
```css
.liquid-glass{
  background-color: rgba(244, 244, 244, 0.1);
  backdrop-filter: blur(10px);
  color: white; /* optional */
  transition: backdrop-filter 0.3s ease;
  border: none;
  border-radius: 15px;
  padding: 30px;
}

.liquid-glass:hover{
  backdrop-filter: blur(20px);
}
```
