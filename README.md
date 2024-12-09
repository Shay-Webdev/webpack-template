# webpack-template

install necessary package with the following command:
    npm init -y
    
    npm i -D webpack webpack-cli clean-webpack-plugin css-loader css-minimizer-webpack-plugin html-loader html-webpack-plugin mini-css-extract-plugin style-loader webpack-dev-server webpack-merge 

npm install --save-dev --save-exact prettier
node --eval "fs.writeFileSync('.prettierrc','{}\n')"
node --eval "fs.writeFileSync('.prettierignore','# Ignore artifacts:\nbuild\ncoverage\n')"
npm init @eslint/config@latest
