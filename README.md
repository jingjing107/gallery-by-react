# gallery-by-react
one photo gallery project based on react.    
借鉴其他人的git发布填坑经验：https://github.com/DodoMonster/galllery-by-react 和 https://github.com/pinmingkenan/gallery-by-react 
## 环境搭建    
1.项目启动      
npm start     
2.项目打包dist     
npm run dist      
##  项目发布      
1.将defaults.j中publicPath: '/assets/'修改为：publicPath: 'assets/',      
2.将index.html中<script type="text/javascript" src="／assets/app.js"></script>修改为：       
                <script type="text/javascript" src="assets/app.js"></script>       
3.执行命令：git add -A     
           git commit -m "init project"       
           git push    
