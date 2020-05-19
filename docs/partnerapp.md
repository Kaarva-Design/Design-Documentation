---
id: partnerapp
title: Partner App
---

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: '#E81D61',
      borderRadius: '2px',
      color: '#fff',
      padding: '0.5rem',
    }}> {children} </span> ); 

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs
  defaultValue="v1"
  values={[
    { label: 'v1', value: 'v1', },
    { label: 'v0', value: 'v0', },
  ]
}>

<TabItem value="v1">

![Partner App](img/partnerapp01.png)

[<Highlight>Download Project</Highlight>](https://drive.google.com/open?id=1cyMSbLMiwM4I0FgTZxOBJnKnuGooHSL2)

</TabItem>

<TabItem value="v0">

![Partner App](img/partnerapp02.png)

[<Highlight>Download Project</Highlight>](https://drive.google.com/open?id=1Ick40mynOHc87jz_bIliVKb7MvEoAPCa)


</TabItem>

</Tabs>

___

[Go to Main Repo ↗](https://drive.google.com/open?id=11KXuPq4HX1llnvEmzUOvAOFbjy5nM95N)