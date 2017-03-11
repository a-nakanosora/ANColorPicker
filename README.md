# ANColorPicker
javascript plain color picker

![img](./doc/img/b.png)



## Supported Browsers
Only Chrome
(& may works on Firefox)

## Usage

    const ancp = new ANColorPicker()
    document.body.appendChild(ancp.getContainer())
    ancp.onChange(({rgb, hsv, isTrusted})=>console.log("rgb:",rgb, "hsv:",hsv, "isTrusted:",isTrusted))
    
    // set a color from outside
    ancp.setColor(200,100,50)

![img](./doc/img/f.gif)

---

    const ancp = new ANColorPicker(size=200)

    ancp.getContainer()

    ancp.setColor(r,g,b)

    ancp.setColorHsv(h,s,v)

    ancp.onChange(callback)
    -- callback : ({rgb, hsv, isTrusted})=>{ ... }
  
## License

MIT
