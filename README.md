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

<strong> 404 not found when i refresh a page rather then go to the page. </strong>

"To fix this issue on Render:
Navigate to your Render project settings.
Go to the "Redirects/Rewrites" section.
Add the following rule:"
1. Source: /*
2. Destination: /
3. Action: Rewrite"