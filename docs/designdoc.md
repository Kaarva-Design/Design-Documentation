---
id: designdoc
title: Design Documentation
---

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: '#E81D61',
      borderRadius: '2px',
      color: '#fff',
      padding: '0.5rem',
    }}> {children} </span> ); 

This design doc was made with [docusaurus](https://github.com/facebook/docusaurus), a react.js app.

![Design Doc](img/designdoc01.png)

[<Highlight>Download Project</Highlight>](https://drive.google.com/drive/folders/1kn_dA8yADxS27g73vKfKgjNYfjV1V7VH?usp=sharing)

### Updating this document

This website uses markdown files to render data.
Markdown is a very easy markup language.

Path to markdown files ```/kaarvaDesign/docs``` 

#### Adding new docs

To add new docs, create an md file with id and title just like in other .md files and put it in ```/docs``` folder. Next, open ```sidebar.js``` in the root directory and add it to the category you want it to come under.

### Deployment

To run a local sever, go to root folder ```/kaarvaDesign```

```shell
	sudo yarn //this will installl all node dependencies
	yarn start //this will start the live server at localhost:3000
```

___

[Go to Main Repo ↗](https://drive.google.com/open?id=11KXuPq4HX1llnvEmzUOvAOFbjy5nM95N)