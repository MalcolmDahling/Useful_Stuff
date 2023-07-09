# Useful Stuff



# Git

<b>Force merge unsynced branch to main</b>
<br/>
--allow-unrelated-histories

<b>Refresh .gitignore</b>
<br/>
1. Make changes in .gitignore file.
2. git rm -r --cached .
3. git add .
4. git commit -m "Commit message"

<b>Fix git filename case on whole repo</b>
1. git rm -r --cached .</br>
2. git add --all ..</br>
Review that **only** changes staged are renames.</br>
3. git status.</br>
Commit your changes after reviewing.</br>
4. git commit -a -m "Fixing file name casing".</br>
5. git push</br>


<b>Delete all old commits</b>
1. Checkout<br/>
git checkout --orphan latest_branch

2. Add all the files<br/>
git add -A

3. Commit the changes<br/>
git commit -am "commit message"

4. Delete the branch<br/>
git branch -D main

5. Rename the current branch to main<br/>
git branch -m main

6. Finally, force update your repository<br/>
git push -f origin main


<b>Refresh branch list (remove old unused branches)</b><br/>
git remote update origin --prune<br/>



# VS Code

<b>Extensions</b>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag">Auto Rename Tag</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets">Reactjs code snippets</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=humao.rest-client">REST Client</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented">Sass</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components">vscode-styled-components</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=GitHub.copilot">GitHub Copilot</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=Angular.ng-template">Angular Language Service</a>
<br/>
<a href="https://marketplace.visualstudio.com/items?itemName=Prisma.prisma">Prisma</a>
<br/>

<b>Settings</b>
<br/>
<a href="https://raulmelo.dev/en/til/choose-the-suggestion-order-in-vscode">Choose suggestion order (log to console on top)</a>



# CSS

<b>Center element vertically and horizontally</b>
<br/>
position:'absolute',
<br/>
left:'50%',
<br/>
top:'50%',
<br/>
'-webkit-transform':'translate(-50%, -50%)',
<br/>
transform:'translate(-50%, -50%)'
<br/>



# Links
<a href="https://railway.app/">Railway</a><br/>
<a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">Flexbox Guide</a><br/>
<a href="https://css-tricks.com/snippets/css/complete-guide-grid/">Grid Guide</a><br/>
<a href="https://fonts.google.com/">Google Fonts</a><br/>
<a href="https://fonts.google.com/icons">Google Icons</a><br/>
<a href="https://iconify.design/">Iconify</a><br/>
<a href="https://color.adobe.com/sv/create/color-wheel">Adobe Color Picker</a><br/>
<a href="https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f">Deploy React app to Github Pages</a><br/>
<a href="https://app.svgator.com/">SVGator</a><br/>
<a href="https://www.youtube.com/watch?v=yCS2m01bQ6w">React useRef hook</a><br/>
<a href="https://html-css-js.com/css/generator/box-shadow/">Box shadow generator</a><br/>
<a href="https://screenfly.org/">Test website at different resolutions</a><br/>
<a href="https://screensiz.es/">Screen sizes</a><br/>
<a href="https://devcenter.heroku.com/articles/git">Deploy to Heroku</a><br/>
<a href="https://stackoverflow.com/questions/13716658/how-to-delete-all-commit-history-in-github">Delete commit history</a><br/>
<a href="https://stackoverflow.com/questions/25436312/gitignore-not-working">Gitignore not working</a><br/>
<a href="https://www.awwwards.com/">Awwwards</a><br/>
<a href="https://www.aremycolorsaccessible.com/">Are my colors accessible?</a><br/>
<a href="https://regex-generator.olafneumann.org/">Regex generator</a><br/>
<a href="https://enable-cors.org/index.html">Enable Cors</a><br/>
<a href="https://github.com/n3r4zzurr0/svg-spinners">SVG spinners</a><br/>
<a href="https://angel-rs.github.io/css-color-filter-generator/">CSS color filter generator</a><br/>
<a href="https://codepen.io/sosuke/pen/Pjoqqp">CSS filter colors</a><br/>
<a href="https://cssgradient.io/">Generate CSS gradients</a><br/>
<a href="https://animista.net/">Animista CSS Animations</a><br/>
<a href="https://keen-slider.io/">Keen-Slider</a><br/>
<a href="https://cssgrid-generator.netlify.app/">CSS Grid Generator</a><br/>
<a href="https://ngrok.com/">ngrok</a><br/>



# React

<b>Create React project with Typescript</b>
<br/>
npx create-react-app . --template typescript
<br/>

<b>Duplicate atom key error</b>
<br/>
Put <b>RECOIL_DUPLICATE_ATOM_KEY_CHECKING_ENABLED = false</b> in .env
<br/>

<a href="https://www.npmjs.com/package/react-router-dom"><b>Router</b></a>
<br/>
npm i react-router-dom
<br/>

<a href="https://www.npmjs.com/package/sass"><b>Sass</b></a>
<br/>
npm i sass
<br/>

<a href="https://www.npmjs.com/package/axios"><b>Axios</b></a>
<br/>
npm i axios
<br/>

<a href="https://www.npmjs.com/package/nanoid"><b>NanoId</b></a>
<br/>
npm i nanoid
<br/>

<a href="https://www.npmjs.com/package/gh-pages"><b>GH-Pages</b></a>
<br/>
npm i gh-pages --save-dev
<br/>

<a href="https://www.npmjs.com/package/react-helmet-async"><b>React Helmet Async</b></a>
<br/>
npm i react-helmet-async
<br/>

<a href="https://www.npmjs.com/package/tinymce"><b>TinyMCE</b></a>
<br/>
npm i --save @tinymce/tinymce-react
<br/>

<a href="https://www.npmjs.com/package/socket.io-client"><b>Socket.io Client</b></a>
<br/>
npm i socket.io-client
<br/>

<a href="https://www.npmjs.com/package/@use-it/interval"><b>UseInterval hook</b></a>
<br/>
npm i @use-it/interval
<br/>

<a href="https://www.npmjs.com/package/typewriter-effect"><b>Typewriter Effect</b></a>
<br/>
npm i typewriter-effect
<br/>

<a href="https://www.npmjs.com/package/react-gsap"><b>GreenSock Animation Platform</b></a>
<br/>
npm i react-gsap
<br/>

<a href="https://www.npmjs.com/package/body-scroll-lock"><b>Body Scroll Lock</b></a>
<br/>
npm i body-scroll-lock
<br/>
npm i @types/body-scroll-lock
<br/>

<a href="https://www.npmjs.com/package/react-hook-form"><b>React Hook Form</b></a>
<br/>
npm i react-hook-form
<br/>

<a href="https://www.npmjs.com/package/recoil"><b>Recoil.js</b></a>
<br/>
npm i recoil
<br/>

<a href="https://www.npmjs.com/package/@stitches/react"><b>Stitches</b></a>
<br/>
npm i @stitches/react
<br/>

<a href="https://www.npmjs.com/package/moment"><b>Moment.js</b></a>
<br/>
npm i moment --save
<br/>

<a href="https://www.npmjs.com/package/use-breakpoint"><b>use-breakpoint</b></a>
<br/>
npm i use-breakpoint
<br/>

<a href="https://www.npmjs.com/package/react-slick"><b>react-slick</b></a>
<br/>
npm i slick-carousel --save
<br/>
npm i react-slick --save
<br/>
npm i --save @types/react-slick
<br/>
<a href="https://github.com/kenwheeler/slick/issues/3271">Slick Center Mode - Animations Bug between last and first slide</a>
<br/>

<a href="https://www.npmjs.com/package/react-intersection-observer"><b>react-intersection-observer</b></a>
<br/>
npm i react-intersection-observer
<br/>

<a href="https://www.npmjs.com/package/throttle-debounce"><b>throttle-debounce</b></a>
<br/>
npm install throttle-debounce --save
<br/>
npm install --save @types/throttle-debounce
<br/>

<a href="https://www.npmjs.com/package/react-player">react-player</a>
<br/>
npm i react-player
<br/>

<a href="https://www.npmjs.com/package/react-scroll">react-scroll</a>
<br/>
npm i react-scroll
<br/>
npm i --save @types/react-scroll
<br/>

<a href="https://www.npmjs.com/package/slugify">slugify</a>
<br/>
npm i slugify
<br/>

<a href="https://keen-slider.io/">Keen-Slider</a>
<br/>
npm i keen-slider
<br/>

<a href="https://www.npmjs.com/package/@storyblok/react">@storyblok/react</a>
<br/>
npm i @storyblok/react
<br/>




# Next

<b>Create Next project with Typescript</b>
<br/>
npx create-next-app@latest . --ts
<br/>

<b>Enable Stiches server-rendering<b/>
<br/>
<a href="https://github.com/MalcolmDahling/Useful_Stuff/blob/main/_document.tsx">pages/_document.tsx</a>
<br/>

<b>Vanilla Extract<b/>
<br/>
npm install --save-dev @vanilla-extract/next-plugin
<br/>
npm install @vanilla-extract/recipes
<br/>
<a href="https://github.com/MalcolmDahling/Useful_Stuff/blob/main/next.config.js">Add changes to next.config.js</a>


# Node

<a href="https://www.npmjs.com/package/express"><b>Express</b></a>
<br/>
npm i express
<br/>

<a href="https://www.npmjs.com/package/nodemon"><b>Nodemon</b></a>
<br/>
npm i nodemon
<br/>

<a href="https://www.npmjs.com/package/crypto-js"><b>CryptoJS</b></a>
<br/>
npm i cryptojs
<br/>

<a href="https://www.npmjs.com/package/cors"><b>Cors</b></a>
<br/>
npm i cors
<br/>

<a href="https://www.npmjs.com/package/dotenv"><b>Dotenv</b></a>
<br/>
npm i dotenv
<br/>

<a href="https://www.npmjs.com/package/socket.io"><b>Socket.io</b></a>
<br/>
npm i socket.io
<br/>

<a href="https://www.npmjs.com/package/puppeteer"><b>Puppeteer</b></a>
<br/>
npm i puppeteer
<br/>

<a href="https://www.npmjs.com/package/mongodb"><b>MongoDB</b></a>
<br/>
npm i mongodb
<br/>

<a href="https://www.npmjs.com/package/mongoose"><b>Mongoose</b></a>
<br/>
npm i mongoose
<br/>

<a href="https://www.npmjs.com/package/mysql2"><b>MySQL</b></a>
<br/>
npm i mysql2
<br/>

<a href="https://www.npmjs.com/package/mailgun.js"><b>mailgun.js</b></a>
<br/>
npm i mailgun.js
<br/>

<a href="https://www.prisma.io/">Prisma.io</a>
<br/>
npm i prisma --save-dev
<br/>
<b>Run prisma script</b>
<br/>
npx ts-node --esm prisma/test.mts
<br/>

<a href="https://www.npmjs.com/package/storyblok-js-client">storyblok-js-client</a>
<br/>
npm i storyblok-js-client
<br/>



# ESLint
<a href="https://www.npmjs.com/package/eslint-config-airbnb"><b>eslint-config-airbnb</b></a>
<br/>
npx install-peerdeps --dev eslint-config-airbnb
<br/>

<a href="https://www.npmjs.com/package/eslint-config-airbnb-typescript"><b>eslint-config-airbnb-typescript</b></a>
<br/>
npm i eslint-config-airbnb-typescript @typescript-eslint/eslint-plugin@^5.13.0 @typescript-eslint/parser@^5.0.0 --save-dev
<br/>

<p>
.eslintrc.json:<br/>
  {<br/>
    "extends": ["next/core-web-vitals", "airbnb", "airbnb-typescript", "prettier", "plugin:node/recommended"],<br/>
    "plugins": ["prettier"]<br/>
  }<br/>
</p>

<a href="https://gist.github.com/bradtraversy/aab26d1e8983d9f8d79be1a9ca894ab4"><b>VSCode - ESLint, Prettier & Airbnb Setup</b></a>



# Socket.io
<b>Sending to sender-client only</b><br/>
socket.emit('message', "this is a test");<br/>

<b>Sending to all clients except sender</b><br/>
socket.broadcast.emit('message', "this is a test");<br/>

<b>Sending to all clients in 'game' room(channel) except sender</b><br/>
socket.broadcast.to('game').emit('message', 'nice game');<br/>

<b>Sending to sender client, only if they are in 'game' room(channel)</b><br/>
socket.to('game').emit('message', 'enjoy the game');<br/>

<b>Sending to individual socketid</b><br/>
socket.broadcast.to(socketid).emit('message', 'for your eyes only');<br/>

<b>Sending to all clients, include sender</b><br/>
io.emit('message', "this is a test");<br/>

<b>Sending to all clients in 'game' room(channel), include sender</b><br/>
io.in('game').emit('message', 'cool game');<br/>

<b>Sending to all clients in namespace 'myNamespace', include sender</b><br/>
io.of('myNamespace').emit('message', 'gg');<br/>

<b>Send to all connected clients</b><br/>
socket.emit();<br/>

<b>Send to all connected clients except the one that sent the message</b><br/>
socket.broadcast.emit();<br/>

<b>Event listener, can be called on client to execute on server</b><br/>
socket.on();<br/>

<b>For emiting to specific clients</b><br/>
io.sockets.socket();<br/>

<b>Send to all connected clients (same as socket.emit)</b><br/>
io.sockets.emit();<br/>

<b>Initial connection from a client.</b><br/>
io.sockets.on();<br/>
