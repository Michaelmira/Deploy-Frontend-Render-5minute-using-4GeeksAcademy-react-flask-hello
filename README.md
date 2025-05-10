<h1> Deploy-Frontend-Render-5minute-using-4GeeksAcademy-react-flask-hello </h1>

<h2> Replace or Optimize the following files. </h2>
1. <strong> add render.yaml to root </strong> #Copy and paste in supplied template
<br>
2. <strong> Replace requirements.txt in root </strong> # Copy and paste in supplied template
<br>
3. <strong> add server.js to root </strong> #Copy and paste in supplied template
<br>
4. <strong> add static.json file to root </strong> #Copy and paste in supplied template
<br>
5. <strong> Optimize package.json to root </strong> #Copy and paste Optimize your current file with added functionality and optimize it with supplied optimized template version
<br>
2. <strong> Replace webpack.common.js in root </strong> # Copy and paste in supplied template
<br>
2. <strong> Replace webpack.prod.js in root </strong> # Copy and paste in supplied template
<br>

# replace webpack.common.js
# replace webpack.prod.js

# npm install

# pnpm install

# pnpm add html-webpack-plugin@latest  ???

# Render Static Site.
1. Build Command: npm run build
2. Publish Directory: dist   

<h1>FAQ</h1>

<strong> 404 not found when i refresh a page rather then go to the page. </strong>

"To fix this issue on Render:
Navigate to your Render project settings.
Go to the "Redirects/Rewrites" section.
Add the following rule:"
1. Source: /*
2. Destination: /
3. Action: Rewrite"

<h4>If gettihng pnpm lock error, delete the pnpm-lock.yaml and do pnpm install</h4>
<h4>If gettihng npm lock error, delete the package-lock.jsonm and do npm install</h4>

   
<p>Notes: 
pnpm install --no-frozen-lockfile
git add pnpm-lock.yaml
git commit -m "Update lockfile to match package.json"
git push
</p>

<p>Notes: Optimized for react 16..... ("react": "^16.8.4",</p>
