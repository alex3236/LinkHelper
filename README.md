# Link Helper - Triple Click Text to Link

A user script that converts plain text URLs on web pages into clickable links, triggered by three clicks.  

![Screenshot](https://s2.loli.net/2025/04/04/sWSK4QmZAuXzYfj.gif)

## Features  

✅ **Smart Trigger**  
- Activates with three consecutive clicks (within 1 second) at the same location  
- 10-pixel position tolerance detection  

✅ **Accurate Recognition**  
- Automatically detects URLs starting with `http://`, `https://`, or `www.`  
- Skips text already enclosed in `<a>` tags  
- Supports simultaneous conversion of multiple URL text segments  

✅ **Safe Replacement**  
- Non-destructive DOM manipulation  
- Preserves original text formatting  
- Automatically adds `target="_blank"` attribute  

## Instructions  

1. **Locate the Text URL**  
   Find the plain text URL you want to convert (e.g., `https://example.com`)  

2. **Triple-Click Quickly**  
   Quickly click three times in a row (left mouse button) on the text URL  

3. **Automatic Conversion**  
   Once successful, the text will turn blue and become a clickable link