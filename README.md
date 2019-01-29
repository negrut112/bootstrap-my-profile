# Bootstrap - My profile - example

<p>Using Bootstrap along HTML and CSS, I made a simple My profile, web-responsive page.<br>
    
You can check my work right here: <a href="https://negrut112.github.io/bootstrap-my-profile/">https://negrut112.github.io/bootstrap-my-profile/</a><br>
    
<img src="https://i.imgur.com/ttQw0Wh.jpg">

## CSS

<p>To make the page web-responsive I added next media querie:</p>
<pre><code>@media only screen and (max-width: 768px) {
/* For mobile phones: */
[class*=&quot;col-&quot;] {
    width: 100%;
}
</code></pre>
<p>}</p>

## HTML

<p>Inside &lt;head&gt; tags I inserted the Bootstrap library wich is a very useful tool, the title, setting the page to follow device witdth, character encoding and a library for icons.</p>
<p>&lt;head&gt;<br>
&lt;script src=&quot;<a href="https://code.jquery.com/jquery.min.js">https://code.jquery.com/jquery.min.js</a>“&gt;&lt;/script&gt;<br>
&lt;link href=”<a href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css</a>&quot; rel=“stylesheet” type=“text/css” /&gt;<br>
&lt;script src=&quot;<a href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js">https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js</a>“&gt;&lt;/script&gt;<br>
&lt;link rel=“stylesheet” href=”<a href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css</a>&quot;&gt;<br>
&lt;meta charset=“utf-8”&gt;<br>
&lt;meta name=“viewport” content=“width=device-width”&gt;<br>
&lt;title&gt;About Me - Practice&lt;/title&gt;<br>
&lt;/head&gt;</p>
<p>Inside the &lt;body&gt; tags happens all the action, starting with a container wrapping all elements. I used default bootstrap classes for differents html elements that will change their appearance.</p>
<p>&lt;div class=“container”&gt;<br>
&lt;div class=“row”&gt;<br>
&lt;div class=“col-xs-6”&gt;&lt;img src=&quot;<a href="https://i.imgur.com/G85poZC.jpg">https://i.imgur.com/G85poZC.jpg</a>&quot; alt=“Me at Fontana di Trevi” class=“img-responsive”&gt;&lt;/div&gt;<br>
&lt;div class=“col-xs-6”&gt;<br>
&lt;div class=“header”&gt;&lt;h2&gt;ALIN C. NEGRUȚ&lt;/h2&gt;<br>
&lt;h4&gt;Manufacturing Engineer, World Traveller  and Amateur Photographer, Romania.&lt;/h4&gt;<br>
&lt;/div&gt;</p>
<pre><code>  &lt;div class=&quot;well&quot;&gt; 
    &lt;p&gt;Hello there! I’m Alin,26 years old, Production Engineer living in Romania. I'm crazy about Technology, Engineering, and Programming. I’m also interested in travel, books, quality music and bodybuilding.&lt;/p&gt;
    &lt;p&gt;For the moment I'm in position of Charge of Stamping Process at RTR Romania, while next year I will graduate &quot;Management of Manufacturing Industrial Products&quot; Master studies at &quot;Vasile Alecsandri&quot; Univerisity of Bacau.
    &lt;p&gt;I'm lookig forward to graduate the CodeBerry class for programming so I ll be able to share efficiently with you my hobbies and experiences. I would like to develope a career in IT Industry as well for the fact that I want to put some ideas in practice.&lt;/p&gt;
  &lt;/div&gt;
  
  &lt;div class=&quot;alert alert-info&quot; &gt;#engineering #tehnology #programming #travelling #music #bodybuilding #photography&lt;/div&gt;
  
  &lt;div class=&quot;col-xs-6&quot;&gt;&lt;h4&gt;Work&lt;/h4&gt;
    &lt;h5&gt;Charge of Stamping Process, RTR Romania&lt;/h5&gt;&lt;/div&gt;
  &lt;div class=&quot;col-xs-6&quot;&gt;&lt;h4&gt;Education&lt;/h4&gt;
    &lt;h5&gt;&quot;Vasile Alecsandri&quot; University of Bacau&lt;/h5&gt;&lt;/div&gt;
  
  &lt;div class=&quot;contact&quot; align=&quot;center&quot;&gt;
    &lt;a class=&quot;fa fa-facebook-square&quot; style=&quot;font-size:36px&quot;&gt;&lt;/a&gt;
    &lt;a class=&quot;fa fa-linkedin-square&quot; style=&quot;font-size:36px&quot;&gt;&lt;/a&gt;
    &lt;a class=&quot;fa fa-instagram&quot; style=&quot;font-size:36px&quot;&gt;&lt;/a&gt;
    &lt;a class=&quot;fa fa-camera-retro&quot; style=&quot;font-size:36px&quot;&gt;&lt;/a&gt;
    &lt;a class=&quot;fa fa-youtube&quot; style=&quot;font-size:36px&quot;&gt;&lt;/a&gt;
  &lt;/div&gt;
</code></pre>
<p>&lt;/div&gt;<br>
&lt;/div&gt;<br>
&lt;/div&gt;</p>
