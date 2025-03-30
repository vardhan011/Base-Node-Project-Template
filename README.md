This is the base node js template, which anyone can use as it has  been prepared, by keeping some of the most important code principle snad project management
 recommendations. Feel free to change anything

 'src' -> All the actual source code regarding the projects will be reside,this will not include any tests,

 Lets take look inside the drc folder:

 - ' config ' -> setting up dotenv so tat we can use the environment an ehere in the cler fassion, this is done in the  'server-config.js'.one more example is to set up your logging libraray that  can help yuo to prepare the meaningful doubt, so the configuuration for this libaray should also be done.

 - ' route' -> In the routes folder we register a route and the corresponding middleaware and the controllers

 - ' middlewares ' -> they are just going to interset the incoimming wher we can  write our validators and authentatiors

 - 'controllers' -> kind of the last middlewares 







  - inside the srcconfig folder create a file named as config.json and write the folllowing code.
  ---
  - Goinside of src folder and run the follwing commmand
  ```
  npx sequelize init
  ```

- if you are setting up development envi,then write the username and password of your db and in dialect mention whatever db your are using example- myssql,etc

- if you are setting test or prod envi , make sure your are  also replace the host eith
