<!DOCTYPE html>
<html>
<title>Indian History</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Oswald">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open Sans">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
h1,h2,h3,h4,h5,h6 {font-family: "Oswald"}
body {font-family: "Open Sans"}
</style>
<body class="w3-light-grey">

<!-- Navigation bar with social media icons -->
<div class="w3-bar w3-black w3-hide-small">
  <a href="#" clHappyass="w3-bar-item w3-button"><i class="fa fa-instagram"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-snapchat"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-flickr"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-twitter"></i></a>
  <a href="#" class="w3-bar-item w3-button"><i class="fa fa-linkedin"></i></a>
  <a href="#" class="w3-bar-item w3-butto3.CSS Template<n w3-right"><i class="fa fa-search"></i></a>
</div>
  
<!-- w3-content defines a container for fixed size centered content, 
and is wrapped around the whole page content, except for the footer in this example -->
<div class="w3-content" style="max-width:1600px">

  <!-- Header -->
  <header class="w3-container w3-center w3-padding-48 w3-white">
    <h1 class="w3-xxxlarge"><b>Happy</b></h1>
    <h6>Independence day </h6>
  </header>

  <!-- Image header -->
  <header class="w3-display-container w3-wide" id="home">
    <img class="w3-image" src="download.jpeg" alt="Fashion Blog" width="1600" height="1060">
    <div class="w3-display-left w3-padding-large">
      <h1 class="w3-text-white">Happy</h1>
      <h1 class="w3-jumbo w3-text-white w3-hide-small"><b>Independence day</b></h1>
      <h6><button class="w3-button w3-white w3-padding-large w3-large w3-opacity w3-hover-opacity-off" onclick="document.getElementById('subscribe').style.display='block'">SUBSCRIBE</button></h6>
    </div>
  </header>

  <!-- Grid -->
  <div class="w3-row w3-padding w3-border"> 

    <!-- Blog entries -->
    <div class="w3-col l8 s12">
    
      <!-- Blog entry -->
      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
          <h3>How india got freedom?</h3>
          <h5>Title description, <span class="w3-opacity">August 15th 1947</h5>
        </div>

        <div class="w3-justify">
          <img src="flag.jpeg" alt="Girl Hat" style="width:100%" class="w3-padding-16">
          <p><strong>India got freedom in 1947</strong> India won its freedom from British colonial rule in 1947, after many decades of struggle. Mohandas Gandhi, known as Mahatma Gandhi, joined the fight in 1914 and led the country to independence, using his method of nonviolent protest known as satyagraha.</p>
          <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
          <p class="w3-right"><button class="w3-button w3-black" onclick="myFunction('demo1')" id="myBtn"><b>Replies  </b> <span class="w3-tag w3-white">1</span></button></p>
          <p class="w3-clear"></p>
          <div class="w3-row w3-margin-bottom" id="demo1" style="display:none">
            <hr>
              <div class="w3-col l2 m3">
                <img src="/w3images/avatar_smoke.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>From wikipedia <span class="w3-opacity w3-medium">May 3, 2015, 6:32 PM</span></h4>
                <p>Great wikipedia</p>
              </div>
          </div>
        </div>
      </div>
      <hr>

      <!-- Blog entry -->
      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
          <h3>About India</h3>
          <h5>Title description, <span class="w3-opacity">April 23, 2016</span></h5>
        </div>

        <div class="w3-justify">
          <img src="/w3images/man_hat.jpg" alt="Men in Hats" style="width:100%" class="w3-padding-16">
          <p><strong>Hats!</strong> India, officially the Republic of India, is a country in South Asia. It is the second-most populous country, the seventh-largest country by land area, and the most populous democracy in the world. Wikipedia
            Currency: Indian rupee Trending
            Capital: New Delhi
            President: Ram Nath Kovind
            Population: 136.64 crores (2019) World Bank
            Prime minister: Narendra Modi
          <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
          <p class="w3-right"><button class="w3-button w3-black" onclick="myFunction('demo2')"><b>Replies  </b> <span class="w3-tag w3-white">2</span></button></p>
          <p class="w3-clear"></p>
          
          <!-- Example of comment field -->
          <div id="demo2" style="display:none">
            <div class="w3-row">
              <hr>
              <div class="w3-col l2 m3">
                <img src="/w3images/girl_train.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Amber <span class="w3-opacity w3-medium">April 26, 2015, 10:52 PM</span></h4>
                <p>Love your blog page! Simply the best! Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p><br>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/girl.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Angie <span class="w3-opacity w3-medium">April 23, 2015, 9:12 PM</span></h4>
                <p>Love hats!!</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Blog entry -->
      <div class="w3-container w3-white w3-margin w3-padding-large">
        <div class="w3-center">
          <h3>About Indian culture</h3>
          <h5>Title description, <span class="w3-opacity">April 7, 2016</span></h5>
        </div>

        <div class="w3-justify">
          <img src="/w3images/runway.jpg" alt="Runway" style="width:100%" class="w3-padding-16">
          <p><strong></strong> TThroughout the history of India, Indian culture has been heavily influenced by Dharmic religions. They have been credited with shaping much of Indian philosophy, literature, architecture, art and music. ... India is the birthplace of Hinduism, Buddhism, Jainism, Sikhism, and other religions.
          <p class="w3-left"><button class="w3-button w3-white w3-border" onclick="likeFunction(this)"><b><i class="fa fa-thumbs-up"></i> Like</b></button></p>
          <p class="w3-right"><button class="w3-button w3-black" onclick="myFunction('demo3')"><b>Replies  </b> <span class="w3-tag w3-white">3</span></button></p>
          <p class="w3-clear"></p>
          
          <!-- Example of comment field -->
          <div id="demo3" style="display:none">
            <hr>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/girl_mountain.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Jane <span class="w3-opacity w3-medium">April 10, 2015, 7:22 PM</span></h4>
                <p>That was a great runway show! Thanks for everything.</p>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/boy.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>John <span class="w3-opacity w3-medium">April 8, 2015, 10:32 PM</span></h4>
                <p>Keep up the GREAT work! I am cheering for you!! Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
              </div>
            </div>
            <div class="w3-row w3-margin-bottom">
              <div class="w3-col l2 m3">
                <img src="/w3images/girl_hood.jpg" style="width:90px;">
              </div>
              <div class="w3-col l10 m9">
                <h4>Anja <span class="w3-opacity w3-medium">April 7, 2015, 9:12 PM</span></h4>
                <p>Cant wait for the runway to start!</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      
    <!-- END BLOG ENTRIES -->
    </div>

    <!-- About/Information menu -->
    <div class="w3-col l4">
      <!-- About Card -->
      <div class="w3-white w3-margin">
        <img src="/w3images/avatar_girl2.jpg" alt="Jane" style="width:100%" class="w3-grayscale">
        <div class="w3-container w3-black">
          <h4>My Name</h4>
          <p>Just me, myself and I, exploring the universe of uknownment. I have a heart of love and a interest of lorem ipsum and mauris neque quam blog. I want to share my world with you.</p>
        </div>Follow Me

      </div>
      <hr>

      <!-- Posts -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Freedoom Fighters</h4>
        </div>
        <ul class="w3-ul w3-hoverable w3-white">
          <li class="w3-padding-16">
            <img src="download (1).jpeg" alt="Image" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Mahatma Gandhi</span>
            <br>
            <span>Born on 2nd october 1869</span>
          </li>
          <li class="w3-padding-16">
            <img src="skillpundit-chandra-bose.jpg" alt="Image" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Subhas Chandra Bose</span>
            <br>
            <span>Born on 23rd January 1897</span>
          </li>
          <li class="w3-padding-16">
            <img src="download (2).jpeg" alt="Image" class="w3-left w3-margin-right" style="width:50px">
            <span class="w3-large">Sardar Vallabhbhai patel</span>
            <br>
            <span>Born on 31st of october 1875</span>
          </li>
          <li class="w3-padding-16">
            <img src="download (4).jpeg" alt="Image" class="w3-left w3-margin-right w3-sepia" style="width:50px">
            <span class="w3-large">Jawahar lal Nehru</span>
            <br>
            <span>14th November 1889</span>
          </li>
        </ul>
      </div>
      <hr>

      <!-- Advertising -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Jai hind</h4>
        </div>
        <div class="w3-container w3-white">
          <div class="w3-container w3-display-container w3-light-grey w3-section" style="height:200px">
            <span class="w3-display-middle">comming soon</span>
          </div>
        </div>
      </div>
      <hr>

      <!-- Tags -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Anout the website</h4>
        </div>
        <div class="w3-container w3-white">
          <p>
            <span class="w3-tag w3-black w3-margin-bottom">About India</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">Its culture</span> 
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">inovations</span> 
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">News</span>
            <span class="w3-tag w3-light-grey w3-small w3-margin-bottom">and more</span> 
          </p>
        </div>
      </div>
      <hr>

      <!-- Inspiration -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Our previous prime ministers</h4>
        </div>
        <div class="w3-row-padding w3-white">
          <div class="w3-col s6">
            <p><img src="list-of-all-prime-minister-india.jpg" alt="Jawahar lal nehru" style="width:100%"></p>
            <p><img src="/w3images/team1.jpg" alt="Indira Gandi" style="width:100%"></p>
          </div>
          <div class="w3-col s6">
            <p><img src="/w3images/avatar_hat.jpg" alt="Rajiv Gandi" style="width:100%" class="w3-grayscale"></p>
            <p><img src="/w3images/team4.jpg" alt="Inder kumar " style="width:100%"></p>
         </div>
        </div>
      </div>
      <hr>

      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Follow Me</h4>
        </div>
        <div class="w3-container w3-xlarge w3-padding">
          <i class="fa fa-facebook-official w3-hover-opacity"></i>
          <i class="fa fa-instagram w3-hover-opacity"></i>
          <i class="fa fa-snapchat w3-hover-opacity"></i>
          <i class="fa fa-pinterest-p w3-hover-opacity"></i>
          <i class="fa fa-twitter w3-hover-opacity"></i>
          <i class="fa fa-linkedin w3-hover-opacity"></i>
        </div>
      </div>
      <hr>
      
      <!-- Subscribe -->
      <div class="w3-white w3-margin">
        <div class="w3-container w3-padding w3-black">
          <h4>Subscribe</h4>
        </div>
        <div class="w3-container w3-white">
          <p>Enter your e-mail below and get notified on the latest updates.</p>
          <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail" style="width:100%"></p>
          <p><button type="button" onclick="document.getElementById('subscribe').style.display='block'" class="w3-button w3-block w3-red">Subscribe</button></p>
        </div>
      </div>

    <!-- END About/Intro Menu -->
    </div>

  <!-- END GRID -->
  </div>

<!-- END w3-content -->
</div>

<!-- Subscribe Modal -->
<div id="subscribe" class="w3-modal w3-animate-opacity">ow india got freedom?
  Title description, August 15th 194
  <div class="w3-modal-content" style="padding:32px">
    <div class="w3-container w3-white">
      <i onclick="document.getElementById('subscribe').style.display='none'" class="fa fa-remove w3-transparent w3-button w3-xlarge w3-right"></i>
      <h2 class="w3-wide">SUBSCRIBE</h2>
      <p>Thx for your time you will be reciving a code enter below</p>
      <p><input class="w3-input w3-border" type="text" placeholder="Emter the code"></p>
      <button type="button" class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom" onclick="document.getElementById('subscribe').style.display='none'">Subscribe</button>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-container w3-dark-grey" style="padding:32px">
  <a href="#" class="w3-button w3-black w3-padding-large w3-margin-bottom"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <p>Made by Rithesh <a href="https://raspberry.org" target="_blank">Using raspberry pi 4</a></p>
</footer>

<script>
// Toggle between hiding and showing blog replies/comments
document.getElementById("myBtn").click();
function myFunction(id) {
  var x = document.getElementById(id);
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}

function likeFunction(x) {
  x.style.fontWeight = "bold";
  x.innerHTML = "✓ Liked";
}
</script>
</body>
</html>
</html>
