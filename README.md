<p align="center">
    <img src="media/NEO-banner.png" alt="NEO">
</p>

# Next Engine Optimization

Next Engine Optimization (NEO) is a developer tool in the form of a VS Code Extension that helps developers hone in on critical performance metrics that influence SEO. NEO is built for applications made with Next.js and aims to provide metrics during development so that engineers can make data-driven decisions to optimize their code.

#### NOTE: This is the repo for the WebPage, NOT the extension. The extension repo is: <a href='https://github.com/nsunku99/neo-extension'>github.com/nsunku99/neo-extension</a>

---

## Tech Stack

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![GoogleChrome](https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=for-the-badge&logo=Puppeteer&logoColor=white)
![eslint](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

<!-- ![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white) -->

---

## Motivation

Plenty of tools offer performance metrics post-deployment, but NEO brings the same level of metrics during the development process. NEO also provides metrics focused around SEO, so that developers can optimize their application's search engine performance during development.

---

## How can I use NEO?

(**We currently ONLY support Next.js applications using the App router with the src directory**)

1. Make sure to have your VSCode Workspace open to a **Next.js App router** project with the **src** directory.

<div style="margin: 50px" align="center" >
    <img src="media/gifs/openNextProject.gif" alt="NEO-Upload">
</div>

2. Head to the <a href='https://marketplace.visualstudio.com/items?itemName=NextEngineOptimization.next-engine-optimization'>VSCode Extension store </a>and download NEO.

<div style="margin: 50px" align="center" >
    <img src="media/gifs/downloadExtension.gif" alt="NEO-Download">
</div>

3. Once installed, you may need to reload your VS Code, but you can then activate it via:

- Keybind Activation: Press ctrl+k for Windows or cmd+k for Mac and then immediately after type n
- Command Palette Activation: Enter the Command Palette (Windows: ctrl+shift+p or Mac: cmd+shift+p) and type "Activate NEO"

<div style="margin: 50px" align="center" >
    <img src="media/gifs/cpActivate.gif" alt="NEO-Activate">
</div>

4. NEO will ask for your localhost link (i.e. http://localhost:3000 is the default for Next.js Projects), so first start your server (npm run dev, yarn dev, pnpm run dev, bun --bun run dev) and then input your localhost link.

<div style="margin: 50px" align="center" >
    <img src="media/gifs/inputLink.gif" alt="NEO-Input">
</div>

5. Right click on any folder that represents a page (Any folder with a page.js/ts file) and click "NEO: Generate Metrics"

6. Look at your metrics!

<div style="margin: 50px" align="center" >
    <img src="media/gifs/GeneratingMetrics.gif" alt="NEO-Activate">
</div>

## Contributors

|  Developed By  |                                                                                                                                                 |                                                                                                                                              |
| :------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------: |
|  Benson Zhen   |  [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bensonzhen)  |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bensonzhen/)   |
| Donald Twiford | [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KrankyKnight) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/donaldtwiford/) |
|  Justin Shim   |    [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/slip4k)    |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/justinshim/)   |
|  Nitesh Sunku  |   [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nsunku99)   |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/niteshsunku/)  |
|   Tom Nguyen   |  [![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nguyentomt)  |  [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyentomt/)   |
