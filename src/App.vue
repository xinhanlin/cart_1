<template>
  <div class="outer-wrapper">
    <div class="backgroud-color">
      <router-view></router-view>
    </div>
  </div>
</template>
<script></script>
<style scoped>
@media (min-width: 1400px) {
  .outer-wrapper {
    background-image: linear-gradient(to top, rgb(190, 193, 215), beige);
  }
  .backgroud-color {
    width: 1400px;
    margin: auto;
    background-image: linear-gradient(to top, beige, #0084ff);
  }
}
.backgroud-color {
  background-image: linear-gradient(to top, beige, #0084ff);
}
img {
  max-width: 100%;
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
}
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
  content: "";
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
button {
  padding: 0;
}
</style>
