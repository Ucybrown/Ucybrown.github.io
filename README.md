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
	<a href="#causes">CAUSES</a>
	<a href="#risk">RISK FACTORS</a>
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
      <h1><a href="#">DIGITAL INTERVENTIONS FOR MENTAL HEALTH: A SYSTEMATIC REVIEW</a></h1>
    </div>
    <div class="blog-summary">
      <p>The prevalence of mental health disorders continues to increase [Stansfeld S. et al, 2016]. It is estimated that  in 2017, 264 million people (3.4%) worldwide suffered from depression and 284 million (3.7%) of the population suffered from an anxiety disorder. This includes phobias, obsessive-compulsive disorder (OCD), post-traumatic stress disorder (PTSD), or generalized anxiety disorder (GAD) [Ritchie H et al 2019; Roser M. et al, 2019].</p>
      <img src="img/img 3.jpg" class="img-fluid">
      <p>The variety and functionality of digital health technologies continues to evolve. Forms of DHI include computer-based cognitive-behavioral therapy (CBT), but may also include telehealth or telemedicine using telecommunication processes such as SMS text messaging, email and video conferencing for telemedicine delivery. More recently, there has also been the emergence of mHealth or mobile health, which integrates smartphone apps, remote monitoring, and wearables. Digital health interventions (DHIs) can be stand-alone interventions, used as a model of step-by-step care, provided in addition to direct treatment, or mediated by a healthcare professional such as a therapist [Palmqvist B et al,2007; Zulman DM et al, 2015]. Many systematic reviews have shown that for people with depression and anxiety disorders, DHI can be as effective as face-to-face therapy [Andersson G, 2014; Cuijpers P,2010]. </p>
    </div>
    <div class="blog-title">
    	<h1><a href="#">WHAT IS DEPRESSION AND ANXIETY DISORDER</a></h1>
    </div>
    <div class="blog-summary">
    	<p>Depression is a mood disorder that causes a persistent feeling of sadness and loss of interest. Also called major depressive disorder or clinical depression, it affects how you feel, think and behave and can lead to a variety of emotional and physical problems. You may have trouble doing normal day-to-day activities, and sometimes you may feel as if life isn't worth living [Mayo Clinic, 2018].</p>
    	<p>Anxiety disorder is a mental health disorder characterized by feelings of worry, anxiety or fear that are strong enough to interfere with one's daily activities[google]. Examples of anxiety disorders include panic attacks, obsessive-compulsive disorder and post-traumatic stress disorder[google].</p>
    </div>
    <div class="blog-title" id="causes">
    	<h1><a href="#">CAUSES OF DEPRESSION AND ANXIETY DISORDER </a></h1>
    </div>
    <div class="blog-summary">
    	<p>
    		There are several possible causes of depression. They can range from biological to circumstantial.
			Common causes include [Higuera, 2021]:
    	</p>
    	<p><strong>Brain chemistry:</strong>There may be a chemical imbalance in parts of the brain that manage mood, thoughts, sleep, appetite, and behavior in people who have depression.
    	</p>
    	<p><strong>Hormone levels:</strong> Changes in female hormones estrogen and progesterone during different periods of time like during the menstrual cycle, postpartum period, peri-menopause, or menopause may all raise a person’s risk for depression.
    	</p>
    	<p><strong>Family history:</strong> You’re at a higher risk for developing depression if you have a family history of depression or another mood disorder.</p>
    	<p><strong>Early childhood trauma:</strong>Some events affect the way your body reacts to fear and stressful situations.</p>
    	<p><strong>Brain structure:</strong>There’s a greater risk for depression if the frontal lobe of your brain is less active. However, scientists don’t know if this happens before or after the onset of depressive symptoms.</p>
    	<p><strong>Medical conditions:</strong> Certain conditions mayTrusted Source put you at higher risk, such as chronic illness, insomnia, chronic pain, Parkinson’s disease, stroke, heart attack, and cancer.</p>
    	<p><strong>Substance use:</strong>A history of substance or alcohol misuse can affect your risk.</p>
    	<p><strong>Pain:</strong>People who feel emotional or chronic physical pain for long periods of time are significantly more likelyTrusted Source to develop depression.</p>
    </div>
    <div class="blog-title">
    	<h1><a href="#">CAUSES OF ANXIETY INCLUDE [Bhargava MD.,2020]:</a></h1>
    </div>
    <div class="blog-summary">
    	<p><strong>Genetics:</strong> Anxiety disorders can run in families. </p>
    	<p><strong>Brain chemistry:</strong>Some research suggests anxiety disorders may be linked to faulty circuits in the brain that control fear and emotions. </p>
    	<p><strong>Environmental stress:</strong>This refers to stressful events you have seen or lived through. Life events often linked to anxiety disorders include childhood abuse and neglect, a death of a loved one, or being attacked or seeing violence.</p>
    	<p><strong>Drug withdrawal or misuse:</strong> Certain drugs may be used to hide or decrease certain anxiety symptoms. Anxiety disorder often goes hand in hand with alcohol and substance use.</p>
    	<p><strong>Medical conditions:</strong>Some heart, lung, and thyroid conditions can cause symptoms similar to anxiety disorders or make anxiety symptoms worse. It’s important to get a full physical exam to rule out other medical conditions when talking to your doctor about anxiety. </p>
    </div>
    <div class="blog-title" id="risk">
    	<h1><a href="#">RISK FACTORS OF DEPRESSION AND ANXIETY DISORDER</a></h1>
    </div>
    <div class="blog-summary">
    	<p>The risk factors of depression and anxiety are quite similar. However they will be highlighted separately in this research paper.Risk factors of Depression include:
		</p>
		<p>1. Death of a loved on or loss of a job.</p>
		<p>2. Genetics</p>
		<p>3. Conflict</p>
		<p>4. Abuse: this includes physical abuse such as sexual molestation.</p>
		<p>5. Life events like new job, loss of employment, retirement, marriage divorce, and birth of a new born(this is often considered as postpartum depression).</p>
		<p>6. Illnesses such as chronic pain, insomnia, ADHD(Attention Deficit Hyperactivity Disorder) and anxiety.</p>
    </div>
    <div class="blog-title">
    	<h1><a href="#">RISK FACTORS OF ANXIETY INCLUDE:</a></h1>
    </div>
    <div class="blog-summary">
    	<p>1. An absent parent.</p>
    	<p>2. Trauma from past experiences and events( this appears in the form of post traumatic stress disorder PTSD).</p>
    	<p>3. Personality (shyness in social gatherings, fixation on details, over-sensitivity, rigidness).</p>
    	<p>4. Depression.</p>
    	<p>5. Self harm.</p>
    	<p>6. Loneliness.</p>
    	<p>7. Physical illness.</p>
    	<p>8. Gender (women are more likely to have anxiety).</p>
    	<p>9. Constant stress.</p>
    </div>
    <div class="blog-summary">
    	<p><strong>Purpose:</strong></p>
    	<p>This aim is to identify, evaluate, and synthesize the available high-quality literature on the opinions and experiences of service users on the acceptability and applicability of DHI for depression and anxiety. 
		Method: An organized search strategy was established and seven electronic databases were searched. Qualitative and mixed-method studies published in English were included. Meta-synthesis was used to analyze and deduce the results of the included studies.
		</p>
		<p><strong>Method:</strong></p>
		<p>An organized search strategy was established and seven electronic databases were searched. Qualitative and mixed-method studies published in English were included. Meta-synthesis was used to analyze and deduce the results of the included studies.</p>
		<p><strong>Result:</strong></p>
		<p>A total of 24 studies were included in meta-synthesis, and 3 key themes emerged as descriptive subtopics. Three key themes were the original motivations and approaches to DHI, the personalization of treatment, and the value of receiving personal support from DHI. The method used suggests that the initial beliefs of those who participated in DHI may have a significant impact on their participation in this type of intervention. Personal support has been highly regarded as an important factor in DHI's success. The main reason was that personalized care was possible.</p>
    </div>
    <img src="img/img 2.png" style="max-inline-size: 100%;block-size: auto;">
    <div class="blog-title" id="conclusion">
    	<h1><a href="#">Conclusion:</a></h1>
    </div>
    <div class="blog-summary">
    	<p>The results of this organized review have implications for the development of future DHI to improve the absorption, retention, and outcome of DHI in depression, anxiety. DHI should be personalized according to an individual's specific needs. Future studies should investigate whether the results can be generalized to other health conditions.</p>
    	<p><strong>REFERENCES</strong></p>
    	<p>1. Andersson G, Cuijpers P, Carlbring P, Riper H, Hedman E. Guided internet-based vs face-to-face cognitive behavior therapy for psychiatric and somatic disorders: a systematic review and meta-analysis. World Psychiatry 2014 Oct;13(3):288-295 [FREE Full text] [CrossRef] [Medline]
		</p>
		<p>2. Bhargava Hansa D., Causes of Anxiety disorder, June 21, 2020.</p>
		<p>3. Higuera Valencia, Everything You Need to Know About Depression (Major Depressive Disorder),2021.</p>
		<p>4. Mayo Clinic, what is depression?, 2018.</p>
		<p>5. Palmqvist B, Carlbring P, Andersson G. Internet-delivered treatments with or without therapist input: does the therapist factor have implications for efficacy and cost? Expert Rev Pharmacoecon Outcomes Res 2007 Jun;7(3):291-297. [CrossRef] [Medline].</p>
		<p>6. Ritchie H, Roser M. Our World in Data. 2019. Mental Health <a href="https://ourworldindata.org/mental-health.">URL</a> </p>
		<p>7. Stansfeld S, Clark C, Bebbington P. Common mental disorders. In: McManus S, Bebbington P, Jenkins R, Brugha R, editors. Mental Health and Wellbeing in England: Adult Psychiatric Morbidity Survey. Leeds, UK: NHS Digital; 2016:1-32.</p>
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
