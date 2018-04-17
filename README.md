This a mobile application developed using React and visual studio code with a couple of other resources for



1. Font - https://fonts.google.com/specimen/Roboto?selection.family=Roboto:300,400,500,700
2. SidNav- https://github.com/gauravchl/react-simple-sidenav
3. slick-https://github.com/akiran/react-slick
4. CSS preprocessors - yarn add node-sass-chokidar

#Copy this path package.js

"build-css": "node-sass-chokidar --include-path ./src --include-path ./node_modules src/ -o src/",
"watch-css": "npm run build-css && node-sass-chokidar --include-path ./src --include-path ./node_modules src/ -o src/ --watch --recursive",

#Allows imorts

@import 'nprogress/nprogress';
@import 'styles/_colors.scss';

5. Bootsrap - npm install --save react-bootstrap bootstrap@3

import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/css/bootstrap-theme.css';
import { Navbar, Jumbotron, Button } from 'react-bootstrap';

6. WebSocket
7. Jest - npm install --save jest-enzyme
import 'jest-enzyme';


