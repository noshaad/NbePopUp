# NbePopUp
<p>just simple fade pop up</p>

<h2>Documentation</h2>
<p><b>first we need jquery</b></p>
<p><b>then we need these styles</b><br/></p>

<pre>
.nbe-pop-up {
	position: fixed;
	height: 100%;
	width: 100%;
	background: #000000bf;
	top: 0;
	z-index: 9999;
	display: none;
	left: 0;
}
.nbe-pop-up-content {
	width: 100%;
	height: 100%;
	position: relative;
	box-sizing: border-box;
	background-color: #fff;
	padding: 0;
	transition: 1s all;
	border-radius: .5px;
	opacity: 0;
}
.nbe-pop-up-holder {
	max-width: 820px;
	position: relative;
	margin: auto;
	width: 100%;
}
.show-nbe-pop-up {
	width: 100%;
}
    </pre>
<p>  it's ok to change with or height or border radius and back ground but it dont change the position and displays  </p>
  <p><b>then we need the class NbePopUp</b> (you can find it bellow the html file)</p>
  <p><b>then we need our popup html and some trigger</b><br/> triggers can be any element but pop up must be like this(obviusly you can have any thing replace of content.. ..)</p>
  <pre>
&lt;div class="nbe-pop-up"&gt;
  &lt;div class="nbe-pop-up-holder"&gt;
	&lt;div class="nbe-pop-up-content"&gt;
		contetn content contetn content contetn content contetn content contetn content contetn content contetn
		content contetn content
	&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
  </pre>
  
  <p>and now we must make the js and browser know that which elment will make the pop up appear by clicking on it<br>
	for that we use 2 attribiut <br/>
	one is for the triger which is this: nbe-pop-triger="sometext"
	second one is  for the popup it self which is this:nbe-pop-trigee="sometext"<br>
	make sure both values are the same like now that both of them are "sometext"<br>
	and in the end they become like this:</p>
<pre>
&lt;button class="can-be-any-thing" nbe-pop-triger="name"&gt;click here&lt;/button&gt;
&lt;div class="nbe-pop-up" nbe-pop-trigee="name" &gt;
  &lt;div class="nbe-pop-up-holder"&gt;
	&lt;div class="nbe-pop-up-content"&gt;
		contetn content contetn content contetn content contetn content contetn content contetn content contetn
		content contetn content
	&lt;/div&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
  
