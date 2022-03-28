# Installation Guide

## Cloning

You can download the project or clone it  
Click on the <span style="color:green">**green color**</span> **button** code button.

## Cloning project

```bash
git clone https://github.com/renkin4/KyoSampleIframe.git
```

## NPM

```bash
npm i && npm run dev 
```

## Yarn

```bash
yarn && yarn dev
```

--- 

URL Should be localhost:3000

### html

```html
<div id="iframe-container">
    <iframe src="https://kyo.studiomultiply.com" frameborder="0"></iframe>
</div>
```

### css

```css 
#iframe-container{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 80vh; 
  overflow: hidden;
}
```

for CSS you can change the height to your liking 