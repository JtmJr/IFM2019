# IFM2019
Webpage for IFM Capstone Project
<!DOCTYPE html>
<html>
<head>
	
	<meta charset="utf-8">
	<style type="text/css">

	    @import url('http://jjohnson136.studio.mcad.edu/courses/webdev1/Week3/fakenews/css/bootstrap.css'); DO I NEED THIS FOR THIS SITE TO FUNCTION? */
    * { 
       -moz-box-sizing: border-box;
       box-sizing: border-box;
    }
    html {
       background: #fff url();
    }
    body {
       width: 90%;
       max-width: 60em;
       margin: 0 auto;
       padding: 2em 4em;
       font-size: 16px;
    }

/*navigation*/

.wrangler-logo {
    display: inline-block;
    float: left;
    margin: 1.5em;
    margin-right: 5em;
  }

nav {
    width: 100%;
    border-top: .5em solid #d3d3d3;
    font-weight: bolder;
 }

nav a {
    position: relative;
    margin-right: 0em;
    font-size: 1em;
    text-decoration: none;
    color: #000;
    font-family: "GT Pressura", sans-serif;
    letter-spacing: .075em;
}

nav li:hover {
    background-color: #e9e9e9;
}
/*
nav img:hover {
    opacity: .5;
}
*/
i { 
    color: #ddd;
}

nav li {
    text-decoration: none;
    float: left;
    display: inline-block;
    padding: 2em;
    line-height: .75;
    margin-top: .5em;
    text-align: center;
}

nav ul {
	padding-bottom: 100px;
	border-bottom: .5em solid #d3d3d3;
}
/*
.nav-search {
    z-index: 0;
    float: ; /*Did say float right here, originally, but this fucks my headline up pretty bad
    font-family: "Interstate-LightCondensed", sans-serif;
    margin-top: 1.875em;
    margin-right: 3.125em;
    } 
*/
/*.search-input {
     letter-spacing: .1em;
     width: 18.75em;
     font-size: .85em;
     background-color: #e5e5e5;
     border: none;
     line-height: 2;
     padding: 0 0 0 .625em; 
}*/

/* icon for search mock-up*/
/*
.fa-search {
    color:#91969a;
    z-index: 10;
    position: absolute;
    right: 3.4375em;
    top: 4.875em;
}
/*End Imputed Navigation css (from final proj)*/
.feature {
	background-color: #d3d3d3;
	margin: 1em;
	padding: 1em;
	padding-bottom: 2.5em;
}
.rhgirl {

	display: block;
	float: right;
	
	margin-top: 1em;
	margin-bottom: 2em;
	padding: 15px;
	padding-bottom: 2.5
	em;
}

.subtitle {
	width: 48%;
	margin-top: 1em;
 	border-top: .15em solid #eee;
 	border-bottom: .15em solid #eee;
 	float: left;
 	padding: 10px

}

.intro {
	width: 400px;
	margin-top: 1em;
    margin-right: 0em;
    clear: left;
    padding: 10px;
 }

img {
    max-width: 100%;
    display: block;
    
    }

h2 {

	font-size: 2em;
	width: 200px;
	}

h1, h2, h3, h4, h5, h6 {
    font-weight: bold;
    margin: 0.5em auto;
    }

p {
	;
}

h1 {
    font-family: "GT Pressura", sans-serif;
    color: #208ECD;
    margin: .5em;
    margin-top: .5em;
    margin-bottom: .25em;
    font-size: 8em;
    text-align: center;
    
    }

 h2 {
 	font-family: "GT Pressura", sans-serif;
	color: #000000;
    margin-top: 3em;
    padding: 1em 0;
    }
aside {
	
	padding: 0em 2em;
	border-top: 2em solid #208ECD;
	padding-bottom: 10em;
	margin: 20px;
}
/* IMAGE CONTAINER*/
.column {
  float: left;
  width: 33.33%;
  padding: 20px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: inline-block;
}

.notes {
	margin: 0em 1em;
	padding-top: 2em;
	clear: both;
}



footer a {
	padding-bottom: 2em;
	margin-bottom: 2em;
	position: relative;
    margin-right: 0em;
    font-size: 1em;
    text-decoration: none;
    color: #208ECD;
    font-family: "GT Pressura", sans-serif;
    letter-spacing: .075em;
}

footer li {
	text-decoration: none;
    float: left;
    display: inline-block;
    padding: 1em;
    line-height: .75;
    margin-top: -.25em;
    text-align: center;
}

p {
	
}
footer {
	width: 100%;
    font-weight: bolder;
	border-bottom: .5em solid #d3d3d3;
	border-top: .5em solid #d3d3d3;
	height: 5em;
	margin-top: 6em;
	padding: 1em;
}
/*not needed*/
    /*table {
    	margin-top: 50px;
    	margin-left: 50px;
    	margin-right: 50px;
    	width: 700px;
    	font-size: 1em;
    	caption-side: top;
        td, th: 5px;
    	border: 3px solid black;
    	border:1px solid black;
    	padding: 50px;
    	}
/*End not needed*/


		</style>
		<title>A3:Irish Fair of Minnesota Capstone</title>
	</head>

	<body>


    <nav> 
         <a href="#" class="logo"><img src="images/TEXTBLOCK.png" width="130" height="70" class="wrangler-logo" alt="ifm textblock logo"></a>
        
            <ul>

                 <li> <a href="Poster.html">POSTERS <i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="collateral.html">BRANDING <i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="https://www.irishfair.com">IFM <i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="https://www.mcad.edu/academic-programs/graphic-and-web-design">MAGWD Program<i class="fa fa-sort-desc"></i></a></li>
                 <!--<li><a href="#"> <i class="fa fa-sort-desc"></i></a></li>-->
            </ul>
        
        <!--<form action="http://www.wrangler-europe.com/search" class="nav-search" onsubmit="return checkSearchInput()" novalidate="novalidate" >
                <input type="text" name="searchterm" class="search-input" placeholder="Search for...">
              </form> -->
 </nav>

<h1>PROJECT:</h1>
<article class="highlight">
<div class="feature">

	<h2 class="subtitle"> Designing The 40th Anniversary Poster for the Irish Fair of Minnesota and 
 Rebranding the IFM For 2019</h2>
	<img src="images/Dancing-1080x1440.jpg" width="50%" class="rhgirl" alt="Little red head girl at IFM 2018">
	<p class="intro">I was an intern for the Irish Fair of Minnesota for 6 months of last year. At the end of the summer they asked me to do the poster for next year’s fair, which happens to be the 40th anniversary of the IFM. Taking elements from the poster design I’ll rebrand all of the collateral for this year as well: all IFM advertisements, brochures, the program,  and t-shirts for 2019. The chief design problem is to keep the Fair’s aesthetic/brand identity familiar but also update it, keeping it fresh, as the IFM moves forward.
</p>
</div>
</article>

<aside>
<div class="row">
  <div class="column">
    <img src="images/IFM_SUNV2-01.jpg" width="33.3%" alt="IFMPoster" style="width:100%">
  </div>
  <div class="column">
    <img src="images/merchtshirt.jpg" width="33.3%"alt="IFM Collateral" style="width:100%">
  </div>
  <div class="column">
    <video class="flower" controls no autoplay width="100%" height="200" alt="Summer is Coming" style="width:100%" src="video/"</video>
  </div>
</div>
<p class="notes" width="100%"> Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.</p>
</aside>

<h1>POSTER(S)</h1>
<article class+"main">
    <p>
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.</p>
    <img src="images/fitz_cartoon_ifm2-01 copy.jpg" class="poster1" alt="One IFM cartoon character">
    <p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>    
    <img src="images/fitz_cartoon_ifm-01 copy 2.jpg" class="poster2" alt="four IFM cartoon characters">


     <p>   Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.</p>

    <img src="images/poster3.jpg" class="poster3" alt="ribbon display of an assortment of Fair icons">
<p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

<img src="images/poster4.png" class="poster4" alt="steamboat on river">

<p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.</p>

<img src="images/poster5.jpg" class="poster5" alt="state of minnesota w/ loon integrate/masked">

<p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.</p>

<img src="images/poster6.jpg" class="poster6" alt="state of minnesota w/knotwork inside">

<p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit </p>

<img src="images/poster7.jpg" class="poster7" alt="state of mn w/irish icon and knotwerk stardust">

<p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.</p>

<img src="images/poster8.jpg" class="poster8" alt="knotwork flower w/knotwerk pollen">

<p>Lorem ipsum dolor sit amet, cons ectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit 
    </p>
</article>


<footer>
	 
        
            <ul>

                 <li> <a href="Poster.html">Feedback<i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="https://www.tumblr.com/blog/jmooridianjr-blog">Tumblr: As It Happened <i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="https://www.irishfair.com">MCAD <i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="https://jeff-mooridian-twf3.squarespace.com">Portfolio<i class="fa fa-sort-desc"></i></a></li>

                 <!--<li><a href="#"> <i class="fa fa-sort-desc"></i></a></li>-->
            </ul>
            <ul class="icons">

                 <li> <a href="icons/twiterer.png"></a></li>
                 <li> <a href="icons/fbk.png"><i class="fa fa-sort-desc"></i></a></li>
                 <li> <a href="icons/instgm.png"><i class="fa fa-sort-desc"></i></a></li>
                
                 
                 <!--<li><a href="#"> <i class="fa fa-sort-desc"></i></a></li>-->
            </ul>
        <!--<a href="#" class="logo"><img src="images/TEXTBLOCK.png" width="130" height="70" class="wrangler-logo" alt="ifm textblock logo"></a>-->	
        
</footer>
</body>
</html>
