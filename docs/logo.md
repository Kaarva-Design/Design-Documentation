---
id: logo
title: Logo
sidebar_label: Logo
---

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: '#E81D61',
      borderRadius: '2px',
      color: '#fff',
      padding: '0.5rem',
    }}> {children} </span> ); 

![Kaarva Logo](img/logo01.png)

The logo uses Airbnb Cereal Medium [(Refer Typography section ↗)](typography). Colors are #E81D61 (brand pink) and #161C2D (dark grey) [(Refer Color section ↗)](color).

### Download
The logo pack includes
* Logo variants (.png, .jpg, .svg)
* Source files (.ai, .psd)
* Logo animation (.mp4, .gif, .aep[source file])
* Favicon (.ico)


[<Highlight>Download Logo Pack </Highlight>](https://drive.google.com/open?id=1serxJ9EM25PU7eMVmM4cL-MLoL_R4JgF)

### Use in Web App
Component level import code
```javascript
import mainLogo from '../static/mainlogo.png'; //main logo
import kaarvaLogo from '../static/kaarvalogo.svg'; //white logo only
import kl from '../static/kl.svg'; //logoonly
import logoffline from '../static/kaarrvalogooffline.png'; //grey logo
import emilogo from '../static/icoonly.svg'; //emi logo

<img src={mainLogo} /> //example usage
```

### Brand Guidelines
The guidelines contain usage, localization, do's and dont's.  

[<Highlight>Download Brand Guidelines</Highlight>](https://drive.google.com/file/d/1hhA45ArlyxHyGK-PVShh5T7AT3l6zHNN/view?usp=sharing)

___

[Go to Main Repo ↗](https://drive.google.com/open?id=11KXuPq4HX1llnvEmzUOvAOFbjy5nM95N)