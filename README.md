<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>DIGITAL INTERVENTIONS FOR MENTAL HEALTH: A SYSTEMATIC REVIEW</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Lato&display=swap" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
<style type="text/css">
	@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lato&family=Quintessential&display=swap');

body {
  background: #000;
  box-sizing: border-box;
}

.blog-container {
  background: #fff;
  border-radius: 5px;
  box-shadow: rgba(0, 0, 0, 0.2) 0 4px 2px -2px;
  font-family: 'Lato', sans-serif;
  font-weight: 100;
  margin: 48px auto;
  width: 20rem;
}
@media screen and (min-width: 480px) {
  .blog-container {
    width: 28rem;
  }
}
@media screen and (min-width: 767px) {
  .blog-container {
    width: 40rem;
  }
}
@media screen and (min-width: 959px) {
  .blog-container {
    width: 50rem;
  }
}
@media screen and (max-width: 650px){
    #nav-toggle {
      display: none;
    }
}

.blog-container a {
  color: #4d4dff;
  text-decoration: none;
  transition: 0.25s ease;
}
.blog-container a:hover {
  border-color: #ff4d4d;
  color: #ff4d4d;
}

.blog-cover {
  background: url("../img/img 1.jpg");
  background-size: cover;
  border-radius: 5px 5px 0 0;
  height: 15rem;
  box-shadow: inset rgba(0, 0, 0, 0.2) 0 64px 64px 16px;
}

.blog-author,
.blog-author--no-cover {
  margin: 0 auto;
  padding-top: 0.125rem;
  width: 80%;
}

.blog-author h3::before,
.blog-author--no-cover h3::before {
  background: url("../img/avatar.jpg");
  background-size: cover;
  border-radius: 50%;
  content: " ";
  display: inline-block;
  height: 32px;
  margin-right: 0.5rem;
  position: relative;
  top: 8px;
  width: 32px;
}

.blog-author h3 {
  color: #fff;
  font-weight: 100;
}

.blog-author--no-cover h3 {
  color: #999999;
  font-weight: 100;
}

.blog-body {
  margin: 0 auto;
  width: 80%;
}

.video-body {
  height: 100%;
  width: 100%;
}

.blog-title h1 a {
  color: #333;
  font-weight: 100;
}

.blog-summary p {
  color: #4d4d4d;
  text-align: justify;
}

.blog-tags ul {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  list-style: none;
  padding-left: 0;
}

.blog-tags li + li {
  margin-left: 0.5rem;
}

.blog-tags a {
  border: 1px solid #999999;
  border-radius: 3px;
  color: #999999;
  font-size: 0.75rem;
  height: 1.5rem;
  line-height: 1.5rem;
  letter-spacing: 1px;
  padding: 0 0.5rem;
  text-align: center;
  text-transform: uppercase;
  white-space: nowrap;
  width: 5rem;
}

.blog-footer {
  border-top: 1px solid #e6e6e6;
  margin: 0 auto;
  padding-bottom: 0.125rem;
  width: 80%;
}

.blog-footer ul {
  list-style: none;
  display: flex;
  flex: row wrap;
  justify-content: flex-end;
  padding-left: 0;
}

.blog-footer li:first-child {
  margin-right: auto;
}

.blog-footer li + li {
  margin-left: 0.5rem;
}

.blog-footer li {
  color: #999999;
  font-size: 0.75rem;
  height: 1.5rem;
  letter-spacing: 1px;
  line-height: 1.5rem;
  text-align: center;
  text-transform: uppercase;
  position: relative;
  white-space: nowrap;
}
.blog-footer li a {
  color: #999999;
}

.comments {
  margin-right: 1rem;
}

.published-date {
  border: 1px solid #999999;
  border-radius: 3px;
  padding: 0 0.5rem;
}

.numero {
  position: relative;
  top: -0.5rem;
}

.icon-star,
.icon-bubble {
  fill: #999999;
  height: 24px;
  margin-right: 0.5rem;
  transition: 0.25s ease;
  width: 24px;
}
.icon-star:hover,
.icon-bubble:hover {
  fill: #ff4d4d;
}

nav {
  position: fixed;
  top: 100px;
  left: 0;
  margin-top: 25px;
}
nav a {
  display: block;
  text-align: center;
  color: #FFF;
  padding: 15px 20px;
  font-size: 40px;
  margin-left: -200px;
  width: 100px;
  height: 100px;
  transition-property: margin-left;
  transition-duration: 0.2s;
  transition-timing-function: ease;
  font-size: 20px;
  text-decoration: none;
  text-align: center;
}
nav a:hover {
  color: #CFD8DC;
}
nav a:nth-child(1) {
  transition-delay: 0s;
}
nav a:nth-child(2) {
  transition-delay: 0.2s;
}
nav a:nth-child(3) {
  transition-delay: 0.4s;
}
nav a:nth-child(4) {
  transition-delay: 0.6s;
}
#nav-toggle {
  width: 100px;
  height: 100px;
  border: none;
  background-color: rgba(0, 0, 0, 0);
  font: inherit;
  font-size: 40px;
  color: #FFF;
  transition: transform 0.2s ease;
  padding: 0;
}
#nav-toggle:after {
  content: "\f0c9";
  font-family: 'FontAwesome';
}
#nav-toggle:focus {
  outline: none;
}
#nav-toggle:hover {
  color: #CFD8DC;
}
.nav-open nav a {
  margin-left: 0;
}
.nav-open #nav-toggle {
  transform: rotate(-180deg);
}
.nav-open #nav-toggle:after {
  content: "\f00d";
}
.img-fluid {
  max-inline-size: 100%;
  block-size: auto;
  width: 700px;
  height: 250px;
}
.float-left {
  float: left;
}
.fluid-div {
  text-align: center;
  color: #fff;
}
.fluid-div p a {
  text-decoration: none;
  color: burlywood;
}
footer div {
  font-family: 'Quintessential', cursive;
}
</style>
</head>
<body>

<header class="float-left">
	  <button id="nav-toggle"></button>

<nav>
	<a href="#topic">TOPIC</a>
	<a href="#negative">NEGATIVE IMPACT</a>
	<a href="#remedy">REMEDY</a>
	<a href="#conclusion">CONCLUSION</a>
</nav>

</header>

<div class="blog-container">
  
  <div class="blog-header">
    <div class="blog-cover">
      <div class="blog-author">
        <h3>UCHENNA CHUKWUMA-ENYIOJI</h3>
      </div>
    </div>
  </div>

  <div class="blog-body">
    <div class="blog-title" id="topic">
      <h1><a href="#">SOCIAL MEDIA: THE BAD INFLUENCE ON NIGERIAN YOUTHS</a></h1>
    </div>
    <div class="blog-summary">
      <p>We all know that the world has evolved to the extent of digital literacy. Almost everyone is on social media, even the under-aged. This blog is written to compare the negative and positive effects of social media in my country Nigeria, from a personal point of view.</p>
      <p>According to Wikipedia, Social media are interactive technologies that facilitate the creation and sharing of information, ideas, interests, and other forms of expression through virtual communities and networks [Kietzmann et al, 2011; Obar et al, 2015]. We have so many social media apps like Facebook, Whatsapp, Instagram, Telegram, LinkedIn, TikTok, Snapchat,and many others.</p>
    </div>
    
    <div class="blog-summary">
    	<p>One of the benefits of social media is efficient and effective communication. It helps people to keep in touch with friends, family, colleagues and business partners all over the world. In this case, distance is not a barrier. 
      Social media also helps people review or get reviews of products and services. For example, reviews to a restaurant on their website or for companies like Amazon, there are reviews and ratings that help you decide on what products you want to purchase.
      </p>
    	<p>Collaborations is also a very good advantage of social media. Collaborative tools like Google and Wikipedia provide people with the chance to update their views and enable people edit and share documents online. Many individuals can collaborate in the most personalized way to get a result in a synchronized fashion.
      When it comes to businesses, social media is a great tool for Brand monitoring. Companies make use of brand monitoring tools to see what is being talked about their businesses. This online presence is possible with the use of social media.
      </p>
    </div>
    <div class="blog-summary">
    	<p>
    		Entertainment is now a very vital part of social media, most people use social media as an escape from the real world, where they can unwind. There are many online games and entertainment industries that are now very well dependant on the use of social media to promote their craft. This includes Media sharing and Paid advertisement.
    	</p>
    	<p>User-generated content, such as text messages or comments, digital photos or videos, and data generated from all online interactions are the lifeblood of social media [Obar et al 2015; Kaplan et al 2010].One of the surprising facts about social media is: There are about 3.5 billion active social media users and a new account is created every 6.4 seconds. Each user has an average of 7.6 social media accounts. They spend about 142 minutes on social networks every day[Soner Alemdar, 2022]. Facebook is the most used social media site [Alfred Lua].
    	</p>
    	<p>Social media is also used to document memories. learn and explore; Advertise yourself. Build friendships with ideas that grow by creating blogs, podcasts, video and gaming sites [O'Keeffe et al, 2011].
    	</p>
  
    </div>
    <div class="blog-title">
    	<h1><a href="#negative">NEGATIVE IMPACT OF SOCIAL MEDIA TO THE NIGERIAN YOUTHS. WHY?!</a></h1>
    </div>
    <div class="blog-summary">
    	<p>Let’s look at the negative impact of youths using social media in Nigeria. There are so many under-aged using these platforms. We all know that when children use social media it exposes them to a whole lot of unfiltered contents which may not be good for them. There are lots of fake and flashy lifestyles on the internet which encourages and influences the youths into thinking there are fast ways of making money. You will find a lot of celebrities and “social media influencers” flaunting loads of cash, accessories, houses, and luxury lifestyle. Everyone wants to show that they are living their best life even if that is not the case. </p>
    	<p>This has put some youths under pressure to live above their means so that they can also flaunt things they cannot afford. You will find a lot of young girls on Snapchat, Instagram etc going into prostitution so they can get the latest iphones or designer bags and wears or travel to different tourists destinations so they can post online. You can also find young boys going into illegal businesses and fraudulent acts called “yahoo yahoo”, where they scam people of their hard earned money and sell fake products and services to people. I have been a victim of this circumstance, I bought a shoe from an online vendor which never got delivered to me. These has made many genuine businesses suffer because people are skeptical about buying things online, except it is from a well-known company.  </p>
    	<p>The recent happenings on the internet are blood rituals which involve killing of innocent people just to make money. There are some youths doing blood rituals where they kill their loved ones and sacrifice them to deities whom promised them wealth in return. This fetish and diabolic act has drawn the attention of thousands of Nigerians, media houses and T.V stations. </p>
    	<p>Everyone is talking about this but how can it be solved?. How do we educate the youths that there’s no fast way of making money?. They need to know that wealth and success is a gradual process of determination, focus, hard work and consistency. Social media has promoted so many unreal lifestyles that need to be corrected. I believe the society in general has an important role to play. </p>
    	
    </div>
    <div class="blog-title" id="risk">
    	<h1><a href="#remedy">HOW DO WE REMEDY THIS SOCIETAL PLAGUE?</a></h1>
    </div>
    <div class="blog-summary">
    	<p>From a personal study, I believe the government can collaborate with some of social media platforms to enable only license adults to use some of these social media platforms. This can be done by requesting a valid I.D card before one can use a social media platform. Parents should equally monitor the use of social media by their underage kids.
		</p>
		<p>The rate of unemployment has also driven some youths into fraudulent acts to survive out of frustration. Therefore, creating more job opportunities will help reduce the crime rate. 
    Parents and schools should also educate children on the consequences of involving themselves in fraudulent lifestyle and make them understand that there’s no fast way of making money. Education is also very important, children and youths should be supported by the government to go to school. This will lift a lot of kids from the streets.
    With the rate of poverty being quite high, money only circulates among the rich. The government should also provide basic amenities for their people, this way, there are less things to worry about. 
    </p>
    </div>
    
    <div class="blog-title" id="conclusion">
    	<h1><a href="#conclusion">Conclusion:</a></h1>
    </div>
    <div class="blog-summary">
    	<p>One will often wonder, is the negative impact of social media outshining its advantages?. As a youth in Nigeria, I believe we all know right from wrong and are capable of making the right decisions. I believe if we all do our part, the society will be a better place to live in.</p>
    	<p><strong>REFERENCES</strong></p>
    	<p>1. Kaplan Andreas M.; Haenlein Michael (2010). "Users of the world, unite! The challenges and opportunities of social media" (PDF). Business Horizons. 53 (1): 61. doi:10.1016/j.bushor.2009.09.003. Archived from the original (PDF) on 2011-11-24. Retrieved 2016-12-07
		</p>
		<p>2. Kietzmann, Jan H; Kristopher Hermkens (2011). “social media? Get serious! Understanding the functional building blocks of social media”. Business Horizons (submitted manuscript). 54 (3): 241-251. doi:10.1016/j.bushor.2011.01.005.</p>
		<p>3. Obar, Jonathan A.; Wildman, Steve (2015). "Social media definition and the governance challenge: An introduction to the special issue". Telecommunications Policy. 39 (9): 745–750. doi:10.1016/j.telpol.2015.07.014. SSRN 2647377.</p>
		<p>4. O'Keeffe, Gwenn Schurgin; Clarke-Pearson, Kathleen; Media, Council on Communications and (April 1, 2011). "The Impact of Social Media on Children, Adolescents, and Families". Pediatrics. 127 (4): 800–804. doi:10.1542/peds.2011-0054. ISSN 0031-4005. PMID 21444588</p>
		<p>5. Soner Alemdar, Social media interesting facts you need to know in 2022.</p>
		
    </div>
    
  </div>
  
  <div class="blog-footer">
    <ul>
      
    </ul>
  </div>

</div>

<footer>
	<div class="fluid-div">
		<p>Project is maintained by - <a href="https://github.com/Ucybrown">Ucybrown</a></p>
		<br>
		<p>Hosted on GitHub Pages - Theme by <a href="https://twitter.com/Okoyeanthonyy">OkoyeTagbo</a> </p>
	</div>
</footer>


<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script type="text/javascript">
	$(function() {
    
	$('#nav-toggle').on('click', function() {
		$('body').toggleClass('nav-open');
	});
	
	});
</script>

</body>
</html>
