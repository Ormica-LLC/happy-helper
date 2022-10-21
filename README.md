<h1 align="center">
  The Happy Helper Blog
</h1>

<p align="center">
   <a href="https://gatsbyjs.com" target="_blank">
     <img src="https://img.shields.io/badge/Built%20with-Gatsby-%23614dff?logo=gatsby" />
   </a>
   <a href="https://reactjs.org/" target="_blank">
     <img src="https://img.shields.io/badge/Powered%20by-React-%2361dafb?logo=react" />
   </a>
   <a>
     <img src="https://img.shields.io/github/license/BrianRuizy/gatsby-minimal-portfolio?color=red&style=flat" />
   </a>
</p>

</div>

![Cover](https://media.githubusercontent.com/media/Ormica-LLC/public-assets/10375ee8427e1391c518695a1d7bbc6d7c9cc020/happy-helper-header.png)

---

## Features

- 📝 Simplistic blog setup using posts created with MDX
- 🔎 Algolia Search, search by all attributes
- 🌗 Togglable support for both light and dark mode
- 📲 PWA support, installable on Android and iOS
- 💻 SEO ready with meta description and other head tags
- 📧 Getform.io contact form, easy to stay in touch

---

## Run the project

Not you must have already installed [Node.JS](https://www.gatsbyjs.com/docs/tutorial/part-zero/#install-nodejs-for-your-appropriate-operating-system) and [Gatsby CLI](https://www.gatsbyjs.com/docs/tutorial/part-zero/#install-nodejs-for-your-appropriate-operating-system).

```bash
nvm install 18
nvm use 18

npm install -g gatsby-cli
```

1. Install project dependencies ```npm install```. If having problems installing try with legacy peer dependencies, ```npm install --legacy-peer-deps```.

2. Start Developing. Navigate into the site’s directory and start up the local server ```gatsby develop``` 🎉.

---

## Adding blog posts

Adding your own content is super simple with the Jamstack design of the project. You won't need to write any HTML or CSS, just markdown (although you absolutely can if you wish to change the design or add your own features). The MDX posts are found in the `content/posts/` directory. With MDX you can even add react components to your posts as found below.

Visit [mdxjs.com](https://mdxjs.com) to see what other cool things you can implement.

```mdx
## Example header here

lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quidem quisquam.

<Alert severity="info">
  Visit <a href="https://python.org">here</a> for docs and examples.
</Alert>
```

![image](https://user-images.githubusercontent.com/23439187/179371961-520835ab-e4ef-4086-90d7-791e26934732.png)
