what is done in this project 
1. creating the webpack files 
2. using webpack loaders and plugins
3. using sass styles 
4. using service workers 
5. using meaning cloud api 
6. unit testing using jest framework




* creating the webpack files :

I have created 2 webpack files , first one in production mode and the second in develop mode .
then i have created package.json file to write the dependencies in it 
then i have installed the npm libraries which was needed in the project


* using webpackloaders and plugins :

webpackloaders: babel-loader, css loader, sass loader 
plugins: HtmlWebPackPlugin, MiniCssExtractPlugin, WorkboxPlugin.GenerateSW

* using sass styles :

I have created 4 sass files to style the project 

* using meaning cloud api :
i have used the the sentiment Analysis api from  meaning cloud.
The text provided would be  analyzed to determine if it expresses a positive/negative/neutral sentiment; to do this, the local polarity of the different sentences in the text is identified and the relationship between them evaluated, resulting in a global polarity value for the whole text.



to run the project :
1. you have to create a file called .env with your own API_KEY in it 
2. you have to  build node_modules folder with npm install in the terminal
3. then you have to build the dist folder with npm run build-prod 
4. finally start the server with npm start
5. you should find the application on the localhost:8081 on your browser
