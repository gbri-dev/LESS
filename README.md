# LESS
npm install --save-dev less

scripts{
  "less": "lessc ./src/styles/main.less ./build/styles/main.css"
}

npm i -g less-watch-compiler

npm i --save-dev less-watch-compiler

scripts{
  "less": "less-watch-compiler ./src/styles ./build/styles"
}
