---
id: partnerwebsite
title: Partner Website
---

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: '#E81D61',
      borderRadius: '2px',
      color: '#fff',
      padding: '0.5rem',
    }}> {children} </span> ); 

 Location: partner.kaarva.com

![Partner Website](img/partnerwebsite01.png)

[<Highlight>Download Project</Highlight>](https://drive.google.com/drive/folders/1kn_dA8yADxS27g73vKfKgjNYfjV1V7VH?usp=sharing)

[Go to BitBucket Repo ↗](https://bitbucket.org/kaarvatech/partners.kaarva.com/src/master/)

### Editing

Files path ```/partners/files/partner.kaarva.com```

### Deployment

:::note
Due to security reasons, the key and pem files have been removed from the project folder. Suren can give these files.
:::

Put ```nginx.key``` and ```nginx.pem``` in ```/partners/cert```

Run this command inside root directory ```/partners``` to push changes directly to production.

```shell
sudo ansible-playbook nginx.yml
```

___

[Go to Main Repo ↗](https://drive.google.com/open?id=11KXuPq4HX1llnvEmzUOvAOFbjy5nM95N)