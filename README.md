# kakaotalk-clone

- For CSS naming convention, refer to BEM (Block, Element, Modifier):
  https://css-tricks.com/bem-101/

- For CSS svg icons, use Font Awesome:
  https://fontawesome.com/kits/e6f61c6027/use?welcome=yes

- For quickly analyzing/getting color codes from reference websites:
  https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp/related

-For font style..

1. imported "Shizuru cursive"
   @import url("https://fonts.googleapis.com/css2?family=Shizuru&display=swap");
2. included it inside .body of styles.css ..as below..
   body {
   /_ font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif _/
   color: rgb(81, 95, 109);
   font-family: "Shizuru", cursive;
   font-weight: bolder;
   background-color: #ffd1dc;
   text-decoration: none;
   }

-Deploying static front web page via Github...

1. on main branch, commit and push
2. on gh-pages branch, update (pull) from main branch and push
   <git checkout gh-pages; git merge main; git push;>
3. check gh-pages link for your repository
