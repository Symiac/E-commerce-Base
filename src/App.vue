<template>
  <div id="app">
  <!--  <HelloWorld msg="Welcome to Your Vue.js App"/>  -->
    <v-header></v-header>
    <v-menu></v-menu>
   <!-- <v-crumb></v-crumb>  -->
    <v-content></v-content>
    <v-footer></v-footer>
   <!-- <home></home>  -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import header from './components/header/headlogo'
import menu from './components/menu/menu'
import content from './components/content/content'
import footer from './components/footer/footer'
//  import breadcrumb from './components/Breadcrumb/Breadcrumb'
//  import home from './components/home'

export default {
  name: 'app',
  components: {
  //  "HelloWorld":HelloWorld,
    "v-header": header,
    "v-menu": menu,
  //  "v-crumb": breadcrumb,
    "v-content": content,
    "v-footer": footer,
  //  "v-home": home

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0 auto;
};
.body{
 margin: 0;
 padding: 0;
}

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif}

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

body {
  line-height: 1;
}

ol,
ul {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: '';
  content: none;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}
</style>
