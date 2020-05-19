---
id: productwebsite
title: Product Website
---

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: '#E81D61',
      borderRadius: '2px',
      color: '#fff',
      padding: '0.5rem',
    }}> {children} </span> ); 

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

Location: https://www.kaarva.com

<Tabs
  defaultValue="v2"
  values={[
    { label: 'v2', value: 'v2', },
    { label: 'v1', value: 'v1', },
    { label: 'v0', value: 'v0', },
  ]
}>

<TabItem value="v2">

![Product Website](img/productwebsite01.png)

[Go to Bitbucket Repo ↗](https://bitbucket.org/rohankaarva/kaarva-website/src/kaarvav2/)

[<Highlight>Download Project</Highlight>](https://drive.google.com/open?id=1fXVFsCxKhYxZCzseK2zSbfkz5NiXm_ct)

Path to assets (including graphics and stylesheets) ```./assets```

### FAQ

Location: https://www.kaarva.com/faq/

Path to FAQ ```./faq```

Path to style ```./faq/style.css```

### Privacy Policy

Location: https://www.kaarva.com/privacy-policy.html

Path to FAQ ```./privacy-policy.html```

Path to style ```./css/privacy-policy.css```

### Terms of Service

Location: https://www.kaarva.com/terms-of-service.html

Path to FAQ ```./terms-of-service.html```

Path to style ```./css/terms-of-service.css```


### Deployment

```shell
git clone https://rohankaarva@bitbucket.org/rohankaarva/kaarva-website.git //makes a local copy of the repo
git checkout kaarva2 //change to v2 branch
```
Make the changes.

```shell
git add . //let git know of the changes
git commit -m "your commit message here" //commit those changes
git push origin kaarvav2 //push changes to remote repo
```

Once this is done, ask Rupesh to deploy these changes from the branch ```kaarvav2``` you just pushed the changes to.

</TabItem>

<TabItem value="v1">

![Product Website](img/productwebsite02.png)

[Go to Bitbucket Repo ↗](https://bitbucket.org/rohankaarva/kaarva-website/src/master/)

[<Highlight>Download Project</Highlight>](https://drive.google.com/open?id=13OcYiUXZ5EAVZ4Cu6JrLE0_xMtVMdULO)

Path to style ```./css```

### Deployment

```shell
git clone https://rohankaarva@bitbucket.org/rohankaarva/kaarva-website.git //makes a local copy of the repo
```
Make the changes.

```shell
git add . //let git know of the changes
git commit -m "your commit message here" //commit those changes
git push origin master //push changes to remote repo
```

Once this is done, ask Rupesh to deploy these changes from the branch ```master``` you just pushed the changes to.

</TabItem>
<TabItem value="v0">

[<Highlight>Download Project</Highlight>](https://drive.google.com/open?id=153H9BYKKQf4xzmqxCRP0g1j41lX539vt)	

</TabItem>

</Tabs>

___

[Go to Main Repo ↗](https://drive.google.com/open?id=11KXuPq4HX1llnvEmzUOvAOFbjy5nM95N)

