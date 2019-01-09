Another attempt (you can't see most of the others, because I deleted the repos after not being able to make them work) at building a React app using the Semantic UI CSS framework. I suppose it's all been a good learning experience.

This one is from: https://www.robinwieruch.de/react-semantic-ui-tutorial/

The basic steps are
0. create-react-app app_name_goes_here
1. npm install semantic-ui-react
2. npm install semantic-ui-css
3. (in index.js) import 'semantic-ui-css/semantic.min.css';

At this point, you should have all the components in the Semantic-UI-React library at your disposal.

N.B.: If you want any components to use local image files, the images need to be put in the public folder of the CRA folder, and referenced with a *single* backslash: <Image src="/logo.png"/> --I discovered this through trial and error, and I can only assume that either my knowledge of file paths is woefully inadequate, or there's something going on that's just way beyond me.