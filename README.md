# Synopsis
The goal is to create a simple app by rebuilding the HTML below in React.
``` HTML
<div class="dex">
  <div class="octo">
    <img src="https://octodex.github.com/images/nyantocat.gif">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/welcometocat.png">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/filmtocat.png">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/privateinvestocat.jpg">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/gobbleotron.gif">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/maxtocat.gif">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/mummytocat.gif">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/daftpunktocat-thomas.gif">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/spidertocat.png">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/stormtroopocat.png">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/heisencat.png">
  </div>
  <div class="octo">
    <img src="https://octodex.github.com/images/grim-repo.jpg">
  </div>
</div>
```
``` CSS
$grey:  #ccc;
$size: 150px;

.dex {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  border: 1px solid $grey;
  margin: 10px auto;
  padding: 10px;
  width: 750px;
}
.octo {
  border: 1px solid $grey;
  border-radius: 100px;
  box-shadow: 1px 2px 3px $grey;
  overflow: hidden;
  margin: 10px;
  width: $size;
  height: $size;
  img {
    width: 100%;
  }
}
```
# Motivation
To better learn the basic practices of React.js

# Deployed Code
[Check it here](http://tiy-2016q1-eh_cosmo-react.surge.sh/)
