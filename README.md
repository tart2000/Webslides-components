# Webslides-components
A list of webslides components with visual rendering 

-------

![alt text](/screenshots/webslides_1_1600x1200.png)

```html
<section class="bg-black-blue aligncenter">
 <span class="background dark" style="background-image:url('https://source.unsplash.com/6njoEbtarec/')"></span>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <p class="text-subtitle">WebSlides Tutorial</p>
    <h1 class="text-landing">Components</h1>
    <p class="text-symbols">* * *</p>
    <p>
      <a class="button ghost" href="https://github.com/jlantunez/webslides" title="Download WebSlides">
        <svg class="fa-github">
          <use xlink:href="#fa-github"></use>
        </svg>
        Free Download
      </a>
    </p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_2_1600x1200.png)
```html
<section class="aligncenter">
  <div class="wrap">
    <h2><strong>WebSlides Components</strong></h2>
    <p class="text-intro">A quick reference guide for beginners.</p>
    <ul class="flexblock border">
      <li>
        <!--div required = padding li or li>a-->
        <div>
          <h3><a target="_blank" href="#slide=3">Architecture</a></h3>
          <ol>
            <li><a target="_blank" href="#slide=3">Markup</a></li>
            <li><a target="_blank" href="#slide=4">CSS Syntax</a></li>
            <li><a target="_blank" href="#slide=5">Layout</a></li>
            <li><a target="_blank" href="#slide=6">Headers</a></li>
            <li><a target="_blank" href="#slide=7">Footers</a></li>
            <li><a target="_blank" href="#slide=8">Navigation</a></li>
            <li><a target="_blank" href="#slide=9">Grid</a></li>
            <li><a target="_blank" href="#slide=14">Alignments</a></li>
            <li><a target="_blank" href="#slide=27">Background Colors</a></li>
            <li><a target="_blank" href="#slide=29">Gradients</a></li>
          </ol>
        </div>
      </li>
      <li>
        <!--div required = padding li or li>a-->
        <div>
          <h3><a target="_blank" href="#slide=33">Contents (Flexible Blocks)</a></h3>
          <ol>
            <li><a target="_blank" href="#slide=33">Multipurpose</a></li>
            <li><a target="_blank" href="#slide=37">Clients</a></li>
            <li><a target="_blank" href="#slide=39">Steps</a></li>
            <li><a target="_blank" href="#slide=40">Features</a></li>
            <li><a target="_blank" href="#slide=41">Specs</a></li>
            <li><a target="_blank" href="#slide=43">CVs and News</a></li>
            <li><a target="_blank" href="#slide=44">Galleries (portfolios, teams...)</a></li>
            <li><a target="_blank" href="#slide=47">Metrics</a></li>
            <li><a target="_blank" href="#slide=48">Plans (Pricing)</a></li>
            <li><a target="_blank" href="#slide=50">Work</a></li>
          </ol>
        </div>
      </li>
      <li>
        <!--div required = padding li or li>a-->
        <div>
          <h3><a target="_blank" href="#slide=51">Landings</a></h3>
          <ol>
            <li><a target="_blank" href="#slide=51">Welcomes</a></li>
            <li><a target="_blank" href="#slide=56">Covers</a></li>
            <li><a target="_blank" href="#slide=62">Data</a></li>
            <li><a target="_blank" href="#slide=66">Abouts</a></li>
            <li><a target="_blank" href="#slide=70">Benefits</a></li>
            <li><a target="_blank" href="#slide=73">Cards</a></li>
            <li><a target="_blank" href="#slide=77">Offers and Discounts</a></li>
            <li><a target="_blank" href="#slide=82">Quotes</a></li>
            <li><a target="_blank" href="#slide=88">Buttons and Badges</a></li>
            <li><a target="_blank" href="#slide=89">Forms</a></li>
          </ol>
        </div>
      </li>
      <li>
        <!--div required = padding li or li>a-->
        <div>
          <h3><a target="_blank" href="#slide=94">Media</a></h3>
          <ol>
            <li><a target="_blank" href="#slide=95">Background Images</a></li>
            <li><a target="_blank" href="#slide=101">Background Videos</a></li>
            <li><a target="_blank" href="#slide=103">Embedding videos, charts...</a></li>
            <li><a target="_blank" href="#slide=108">Maps</a></li>
            <li><a target="_blank" href="#slide=109">500+ SVG Icons</a></li>
            <li><a target="_blank" href="#slide=110">Logos</a></li>
            <li><a target="_blank" href="#slide=111">Avatars</a></li>
            <li><a target="_blank" href="#slide=112">Devices</a></li>
            <li><a target="_blank" href="#slide=113">Screenshots</a></li>
            <li><a target="_blank" href="#slide=114">CSS Animations</a></li>
          </ol>
        </div>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_3_1600x1200.png)
```html
<section>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <div class="grid vertical-align">
      <div class="column">
        <h3><strong>WebSlides is really easy</strong></h3>
        <p class="text-intro">Each parent <code>&lt;section&gt;</code> in the #webslides element is an individual slide. </p>
        <p>Code looks superb. It uses <strong>intuitive markup with popular naming conventions</strong>. There's no need to overuse classes or nesting. Just focus on your ideas. <strong>Based on <a href="https://github.com/jennschiffer/SimpleSlides">SimpleSlides</a>, by <a href="http://jennmoney.biz">Jenn Schiffer</a></strong> :)</p>
      </div>
      <!-- .end .column -->
      <div class="column">
        <pre>&lt;article id="webslides"&gt;
<span class="code-comment">&lt;!-- Slide 1 --&gt;</span>
&lt;section&gt;
&lt;h1&gt;Design for trust&lt;/h1&gt;
&lt;/section&gt;
<span class="code-comment">&lt;!-- Slide 2 --&gt;</span>
&lt;section class="bg-primary"&gt;
&lt;div class="wrap"&gt;
&lt;h2&gt;.wrap = container 1200px with fadein&lt;/h2&gt;
&lt;/div&gt;
&lt;/section&gt;
&lt;/article&gt;
</pre>
      </div>
      <!-- .end .column -->
    </div>
    <!-- .end .grid -->
    <hr>
    <p class="aligncenter">Vertical sliding? <code>&lt;article id="webslides" class="vertical"&gt;</code></p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_4_1600x1200.png)
```html
<section>
  <div class="wrap size-50">
    <h2>
      <svg class="fa-heart-o">
        <use xlink:href="#fa-heart-o"></use>
      </svg>
      CSS Syntax
    </h2>
    <p class="text-intro">WebSlides is so easy to understand and love. Baseline: 8.</p>
    <hr>
    <ul class="description">
      <li><span class="text-label">Typography:</span> .text-landing, .text-subtitle, .text-data, .text-intro...</li>
      <li><span class="text-label">BG Colors:</span> .bg-primary, .bg-blue,.bg-apple...</li>
      <li><span class="text-label">BG Images:</span> .background, .background-center-bottom...</li>
      <li><span class="text-label">Cards:</span> .card-60, .card-50, .card-40...</li>
      <li><span class="text-label">Sizes:</span> .wrap.size-50, .img.size-40...</li>
      <li><span class="text-label">Flex Blocks:</span> .flexblock.clients, .flexblock.gallery, .flexblock.metrics...</li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_5_1600x1200.png)
```html
<section>
  <header>
    <!--.wrap o <nav> = container 1200px -->
    <div class="wrap">
      <p class="logo"><a href="#" title="Logo">Logo</a> <span class="alignright">.alignright</span></p>
    </div>
  </header>
  <div class="aligncenter fadeInUp">
    <h1>Layout</h1>
    <p>Centering vertically and horizontally.</p>
  </div>
  <footer>
    <div class="wrap">
      <p>
        <span class="alignleft">
        Footer
        </span>
        <span class="alignright">
          <a href="#" title="Twitter">
            <svg class="fa-twitter">
              <use xlink:href="#fa-twitter"></use>
            </svg>
            @username
          </a>
        </span>
      </p>
    </div>
  </footer>
</section>
```
![alt text](/screenshots/webslides_6_1600x1200.png)
```html
<section>
  <header class="bg-white">
    <!--.wrap o <nav> = container 1200px -->
    <div class="wrap">
      <p class="logo"><a href="#" title="Logo">Logo</a> <span class="alignright">.alignright</span></p>
    </div>
  </header>
  <div class="wrap aligncenter">
    <h1>Headers</h1>
    <p><code>&lt;header class="bg-white"&gt;</code></p>
  </div>
</section>
```
![alt text](/screenshots/webslides_7_1600x1200.png)
```html
<section>
  <div class="wrap aligncenter">
    <h1>Footers</h1>
    <p><code>&lt;footer class="bg-white"&gt;</code></p>
  </div>
  <footer class="bg-white">
    <!--.wrap o <nav> = container 1200px -->
    <div class="wrap">
      <p>
        <span class="alignleft"><a href="https://google.com" title="Google"><img src="../static/images/logos/google.svg" alt="Google"></a></span>
        <span class="alignright">
          <a href="#" title="Twitter">
            <svg class="fa-twitter">
              <use xlink:href="#fa-twitter"></use>
            </svg>
            @username
          </a>
        </span>
      </p>
    </div>
  </footer>
</section>
```
![alt text](/screenshots/webslides_8_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h1>Navigation</h1>
    <ul class="tabs">
      <li class="tab current" data-tab="tab-1">ul.tabs</li>
      <li class="tab" data-tab="tab-2">columns</li>
    </ul>
    <div id="tab-1" class="tab-content current">
      <nav role="navigation">
        <ul>
          <li><a href="">About</a></li>
          <li><a href="">Clients</a></li>
          <li class="facebook">
            <a rel="external" href="https://facebook.com/webslides" title="Facebook">
              <svg class="fa-facebook">
                <use xlink:href="#fa-facebook"></use>
              </svg>
              Facebook
            </a>
          </li>
          <li class="twitter">
            <a rel="external" href="https://twitter.com/webslides" title="Twitter">
              <svg class="fa-twitter">
                <use xlink:href="#fa-twitter"></use>
              </svg>
              @WebSlides
            </a>
          </li>
        </ul>
      </nav>
      <p>nav</p>
      <nav role="navigation" class="navbar">
        <ul>
          <li><a href="">About</a></li>
          <li><a href="">Services</a></li>
          <li><a href="">Clients</a></li>
          <li><a href="">Contact</a></li>
          <li class="facebook">
            <a rel="external" href="https://facebook.com/webslides" title="Facebook">
              <svg class="fa-facebook">
                <use xlink:href="#fa-facebook"></use>
              </svg>
              Facebook
            </a>
          </li>
          <li class="twitter">
            <a rel="external" href="https://twitter.com/webslides" title="Twitter">
              <svg class="fa-twitter">
                <use xlink:href="#fa-twitter"></use>
              </svg>
              @WebSlides
            </a>
          </li>
        </ul>
      </nav>
      <p>nav.navbar</p>
    </div>
    <!-- end .tab-content -->
    <div id="tab-2" class="tab-content">
      <div class="grid">
        <div class="column">
          <h3>Company</h3>
          <ul>
            <li><a href="">About</a></li>
            <li><a href="">Team</a></li>
            <li><a href="">Blog</a></li>
          </ul>
        </div>
        <!-- .end .column -->
        <div class="column">
          <h3>Support</h3>
          <ul>
            <li><a href="">Shipping &amp; Returns</a></li>
            <li><a href="">FAQ</a></li>
            <li><a href="">Contact</a></li>
          </ul>
        </div>
        <!-- .end .column -->
        <div class="column">
          <h3>Legal</h3>
          <ul>
            <li><a href="">Terms of Service</a></li>
            <li><a href="">Privacy Policy</a></li>
            <li><a href="">Cookies</a></li>
          </ul>
        </div>
        <!-- .end .column -->
        <div class="column">
          <h3>Community</h3>
          <ul>
            <li>
              <a href="">
                <svg class="fa-facebook">
                  <use xlink:href="#fa-facebook"></use>
                </svg>
                Facebook
              </a>
            </li>
            <li>
              <a href="">
                <svg class="fa-youtube">
                  <use xlink:href="#fa-youtube"></use>
                </svg>
                YouTube
              </a>
            </li>
            <li>
              <a href="">
                <svg class="fa-twitter">
                  <use xlink:href="#fa-twitter"></use>
                </svg>
                Twitter
              </a>
            </li>
          </ul>
        </div>
        <!-- .end .column -->
      </div>
      <!-- .end .grid -->
    </div>
    <!-- end .tab-content -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_9_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>.grid > .column</h2>
    <p>Basic Grid (auto-fill and equal height).</p>
    <hr>
    <div class="grid">
      <div class="column">
        <h3>.column 1</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
      <div class="column">
        <h3>.column 2</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome. Just focus on your content. Have less. Do more.</p>
      </div>
      <div class="column">
        <h3>.column 3</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
    </div>
    <!--end .grid -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_10_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>.grid.<strong>vertical-align</strong> > .column</h2>
    <hr>
    <div class="grid vertical-align">
      <div class="column">
        <h3>.column 1</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
      <div class="column">
        <h3>.column 2</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome. Just focus on your content. Have less. Do more. Create beautiful solutions. Our children's world will be better.</p>
      </div>
      <div class="column">
        <h3>.column 3</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
    </div>
    <!--end .grid -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_11_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>.grid.<strong>sm</strong> (sidebar + main)</h2>
    <hr>
    <div class="grid sm">
      <div class="column">
        <h3>.column 1</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
      <div class="column">
        <h3>.column 2</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome. Just focus on your content. Have less. Do more. Create beautiful solutions. Our children's world will be better.</p>
      </div>
    </div>
    <!--end .grid -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_12_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>.grid.<strong>ms</strong> (main +  sidebar)</h2>
    <hr>
    <div class="grid ms">
      <div class="column">
        <h3>.column 1</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
      <div class="column">
        <h3>.column 2</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome. Just focus on your content. Have less. Do more. Create beautiful solutions. Our children's world will be better.</p>
      </div>
    </div>
    <!--end .grid -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_13_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>.grid.<strong>sms</strong> (sidebar + main +  sidebar)</h2>
    <hr>
    <div class="grid sms">
      <div class="column">
        <h3>.column 1</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome.</p>
      </div>
      <div class="column">
        <h3>.column 2</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome. Just focus on your content. Have less. Do more. Create beautiful solutions. Our children's world will be better.</p>
      </div>
      <div class="column">
        <h3>.column 3</h3>
        <p>Incredibly versatile! Auto-fill and equal height. Flexbox is awesome. Just focus on your content. Have less. Do more. Create beautiful solutions. Our children's world will be better.</p>
      </div>
    </div>
    <!--end .grid -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_14_1600x1200.png)
```html
<section class="aligncenter">
  <h2>Simple CSS Alignments</h2>
  <p>Put content wherever you want.</p>
</section>
```
![alt text](/screenshots/webslides_15_1600x1200.png)
```html
<section class="slide-top">
  <div class="wrap">
    <div class="content-left">
      <h3>1/9 left top</h3>
      <p>Put content wherever you want. Have less. Do more. Create beautiful solutions.</p>
      <p><code>.slide-top and .content-left</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_16_1600x1200.png)
```html
<section class="slide-top">
  <div class="wrap">
    <div class="content-center">
      <h3>2/9 center top</h3>
      <p>Your story needs to be clear. A great lasting story is about everyone or it will not last. </p>
      <p><code>.slide-top and .content-center</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_17_1600x1200.png)
```html
<section class="slide-top">
  <div class="wrap">
    <div class="content-right">
      <h3>3/9 right top</h3>
      <p>Your story needs to be short. Select words carefully, each one must convey a meaning.</p>
      <p><code>.slide-top and .content-right</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_18_1600x1200.png)
```html
<section>
  <div class="wrap">
    <div class="content-left">
      <h3>4/9 left center</h3>
      <p>Your slides should be clear and well structured. What's the point of the story? Why is that relevant?</p>
      <p><code>.content-left</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_19_1600x1200.png)
```html
<section>
  <div class="wrap">
    <div class="content-center">
      <h3>5/9 center</h3>
      <p>Stories are all around us. They are what move us, make us feel alive, and inspire us.</p>
      <p><code>.content-center</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_20_1600x1200.png)
```html
<section>
  <div class="wrap">
    <div class="content-right">
      <h3>6/9 right center</h3>
      <p>Your presentation should have the same elements as a good book. Action, failure, and success. </p>
      <p><code>.content-right</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_21_1600x1200.png)
```html
<section class="slide-bottom">
  <div class="wrap">
    <div class="content-left">
      <h3>7/9 left bottom</h3>
      <p>How to tell strategic stories? What Promised Land is the company conveying through its words and images.</p>
      <p><code>.slide-bottom</code> and <code>.content-left</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_22_1600x1200.png)
```html
<section class="slide-bottom">
  <div class="wrap">
    <div class="content-center">
      <h3>8/9 center bottom</h3>
      <p>What's the Promised Land? What change do you want to bring to the world? The Promised Land is the North Star.</p>
      <p><code>.slide-bottom</code> and <code>.content-center</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_23_1600x1200.png)
```html
<section class="slide-bottom">
  <div class="wrap">
    <div class="content-right">
      <h3>9/9 right bottom</h3>
      <p>Your origin story helps people decide whether or not to trust you. How was your life before the life-changing event?</p>
      <p><code>.slide-bottom</code> and <code>.content-right</code></p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_24_1600x1200.png)
```html
<section>
  <div class="wrap">
    <img class="alignright size-50" src="../static/images/iphone.png" alt="iPhone">
    <h2>img.size-50</h2>
    <p><code>img.alignright.size-50</code></p>
    <p>Jobs unveiled the iPhone to the public on January 9, 2007, at the Macworld 2007 convention at the Moscone Center in San Francisco.  Apple sold 6.1 million first generation iPhone units over five quarters.</p>
    <p><strong>Image size recommended</strong>:<br> 800x600px / 600x450px.</p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_25_1600x1200.png)
```html
<section>
  <div class="wrap">
    <img class="alignleft size-50" src="../static/images/iphone.png" alt="iPhone">
    <h2>img.size-50</h2>
    <p><code>img.alignleft.size-50</code></p>
    <p>Jobs unveiled the iPhone to the public on January 9, 2007, at the Macworld 2007 convention at the Moscone Center in San Francisco.  Apple sold 6.1 million first generation iPhone units over five quarters.</p>
    <p><strong>Image size recommended</strong>:<br> 800x600px / 600x450px.</p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_26_1600x1200.png)
```html
<section>
  <div class="wrap">
    <img class="alignleft size-30" src="../static/images/iphone.png" alt="iPhone">
    <h2>img.size-30</h2>
    <p><code>img.alignleft.size-30</code></p>
    <p>Jobs unveiled the iPhone to the public on January 9, 2007, at the Macworld 2007 convention at the Moscone Center in San Francisco.</p>
    <p><strong>Image size recommended</strong>:<br> 800x600px / 600x450px.</p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_27_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>Corporate Backgrounds</h3>
    <ul class="flexblock">
      <li class="bg-primary">
        <h2>.bg-primary</h2>
        #44d
      </li>
      <li class="bg-secondary">
        <h2>.bg-secondary</h2>
        #67d
      </li>
      <li class="bg-light">
        <h2>.bg-light</h2>
        #edf2f7
      </li>
      <li>
        <h2>body</h2>
        #f7f9fb
      </li>
    </ul>
    <hr>
    <h3>General Colors</h3>
    <ul class="flexblock">
      <li class="bg-black">
        <h2>.bg-black</h2>
        #111
      </li>
      <li class="bg-black-blue">
        <h2>.bg-black-blue</h2>
        #123
      </li>
      <li class="bg-white">
        <h2>.bg-white</h2>
        #fff
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_28_1600x1200.png)
```html
<section>
  <div class="wrap">
    <ul class="flexblock">
      <li class="bg-red">
        <h2>.bg-red</h2>
        #c23
      </li>
      <li class="bg-green">
        <h2>.bg-green</h2>
        #077
      </li>
      <li class="bg-blue">
        <h2>.bg-blue</h2>
        #346
      </li>
      <li class="bg-purple">
        <h2>.bg-purple</h2>
        #62b
      </li>
    </ul>
    <hr>
    <h3>Transparent Backgrounds</h3>
    <ul class="flexblock">
      <li class="bg-trans-dark">
        <h2>.bg-trans-dark</h2>
        rgba(0,0,0 , 0.5)
      </li>
      <li class="bg-trans-light">
        <h2>.bg-trans-light</h2>
        rgba(255,255,255 , 0.2)
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_29_1600x1200.png)
```html
<section class="bg-gradient-h">
  <div class="wrap">
    <h1>Gradients</h1>
    <ul class="flexblock border">
      <li>Horizontal <code>.bg-gradient-h</code></li>
      <li>Radial <code>.bg-gradient-r</code></li>
      <li>Vertical <code>.bg-gradient-v</code></li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_3à_1600x1200.png)
```html
<section class="bg-gradient-v aligncenter">
  <div class="wrap">
    <h2>Vertical Gradient</h2>
    <p><code>.bg-gradient-v</code></p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_31_1600x1200.png)
```html
<section class="bg-gradient-r aligncenter">
  <div class="wrap">
    <h2>Radial Gradient</h2>
    <p><code>.bg-gradient-r</code></p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_32_1600x1200.png)
```html
<section class="bg-apple aligncenter">
  <h2>One more background :)</h2>
  <p><code>.bg-apple</code></p>
</section>
```
![alt text](/screenshots/webslides_33_1600x1200.png)
```html
<section class="aligncenter">
  <div class="wrap">
    <div class="content-center">
      <h2 class="text-landing">Contents</h2>
      <p><code>ul.flexblock</code> = Flexible blocks<br> with auto-fill and equal height.</p>
    </div>
    <hr>
    <ul class="flexblock">
      <li>
        <h2>
          <svg class="fa-bar-chart">
            <use xlink:href="#fa-bar-chart"></use>
          </svg>
          .flexblock li 1
        </h2>
        Multipurpose: services, features, specs...
      </li>
      <li>
        <h2>
          <svg class="fa-balance-scale">
            <use xlink:href="#fa-balance-scale"></use>
          </svg>
          .flexblock li 2
        </h2>
        Multipurpose: benefits, clients, work...
      </li>
      <li>
        <h2>
          <svg class="fa-cog">
            <use xlink:href="#fa-cog"></use>
          </svg>
          .flexblock li 3
        </h2>
        Multipurpose: news, metrics, plans...
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_34_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>Multipurpose (services, work...)</h3>
    <p><code>ul.flexblock.blink</code> (block link)</p>
    <ul class="flexblock blink">
      <li>
        <a href="#">
          <h2>
            <svg class="fa-bar-chart">
              <use xlink:href="#fa-bar-chart"></use>
            </svg>
            Purpose
          </h2>
          Businesses that people love
        </a>
      </li>
      <li>
        <a href="">
          <h2>
            <svg class="fa-balance-scale">
              <use xlink:href="#fa-balance-scale"></use>
            </svg>
            Principles
          </h2>
          Ethics of openness and good taste
        </a>
      </li>
      <li>
        <a href="#">
          <h2>
            <svg class="fa-cog">
              <use xlink:href="#fa-cog"></use>
            </svg>
            Process
          </h2>
          Useful &rarr; Easy &rarr; Fast &rarr; Beautiful
        </a>
      </li>
    </ul>
    <hr>
    <h3>Multipurpose (services, work...)</h3>
    <p><code>ul.flexblock.border</code></p>
    <ul class="flexblock border">
      <li>
        <h2>
          <svg class="fa-bar-chart">
            <use xlink:href="#fa-bar-chart"></use>
          </svg>
          Purpose
        </h2>
        Businesses that people love
      </li>
      <li>
        <h2>
          <svg class="fa-balance-scale">
            <use xlink:href="#fa-balance-scale"></use>
          </svg>
          Principles
        </h2>
        Ethics of openness and good taste
      </li>
      <li>
        <h2>
          <svg class="fa-cog">
            <use xlink:href="#fa-cog"></use>
          </svg>
          Process
        </h2>
        Useful &rarr; Easy &rarr; Fast &rarr; Beautiful
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_35_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>Multipurpose (services, clients...)</h3>
    <p><code>ul.flexblock.blink.border</code></p>
    <ul class="flexblock blink border">
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <h3>Interfaces</h3>
            <ol>
              <li>Architecture</li>
              <li>Design</li>
              <li>Development</li>
            </ol>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <h3>Content Strategy</h3>
            Beautiful and engaging stories that inspires consumers to take action.
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <h3>Customer Experience</h3>
            Attitude. Little details. People always remember how you made them feel.
          </div>
        </a>
      </li>
      <li>
        <a href="">
          <!--div required = padding li or li>a-->
          <div>
            <h3>Recruitment</h3>
            We like to help startups by working with them since the beginning.
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <img class="aligncenter" src="../static/images/logos/google.svg" alt="Google"> Collaboration with the Acme team to design their mobile apps.
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <img class="aligncenter blacklogo" src="../static/images/logos/google.svg" alt="Google"> We worked closely with the UX team on photography for the site. <code>img.blacklogo</code>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <img class="aligncenter graylogo" src="../static/images/logos/google.svg" alt="Google"> Acme hired us to help make the reading experience totally engaging. <code>img.graylogo</code>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <!--div required = padding li or li>a-->
          <div>
            <img class="aligncenter graylogo" src="../static/images/logos/google.svg" alt="Google"> We worked with Acme to develop recruiting processes. <code>img.graylogo</code>
          </div>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_36_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>Multipurpose</h3>
    <p><code>ul.flexblock.blink.border</code></p>
    <ul class="flexblock border blink">
      <li>
        <a href="">
          <h3>Google</h3>
          2016.- Google Drive
        </a>
      </li>
      <li><a href="#" title="Facebook"><strong>Facebook</strong> 2016.- F8 Conference</a></li>
      <li><a href="#" title="Airbnb"><strong>Airbnb</strong>2015.- Creative Direction</a></li>
      <li><a href="#" title="Microsoft"><strong>Microsoft</strong> 2015.- Content Strategy</a></li>
      <li><a href="#" title="The New York Times"><strong>The New York Times</strong>2015.- Recruitment</a></li>
      <li><a href="#" title="Netflix"><strong>Netflix</strong> 2014.- Mobile Apps</a></li>
      <li><a href="#" title="Instagram"><strong>Instagram</strong>2014.- Identity</a></li>
      <li><a href="#" title="Spotify"><strong>Spotify</strong> 2013.- TV Commercials</a></li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_37_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>Clients</h2>
    <p><code>ul.flexblock.clients</code></p>
    <ul class="flexblock clients">
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/google.svg" alt="Google">
            <figcaption>
              <h3>Interfaces</h3>
              <p>Collaboration with the Acme team to design their mobile apps. <code>img.blacklogo</code></p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/microsoft.svg" alt="Microsoft">
            <figcaption>
              <h3>Brand</h3>
              <p>We worked with the UX team on photography for the site <code>img.blacklogo</code></p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/instagram.svg" alt="Instagram">
            <figcaption>
              <h3>Recruiting</h3>
              <p>We worked with Acme to develop recruiting processes. <code>img.blacklogo</code></p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/netflix.svg" alt="Netflix">
            <figcaption>
              <h3>Content Strategy</h3>
              <p>We partnered with various Netflix divisions to create a campaign for House of Cards.</p>
            </figcaption>
          </figure>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_38_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2>Clients</h2>
    <p><code>ul.flexblock.clients.border</code></p>
    <ul class="flexblock clients border">
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/google.svg" alt="Google">
            <figcaption>
              <h3>Interfaces</h3>
              <p>Collaboration with the Acme team to design their mobile apps. <code>img.blacklogo</code></p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/microsoft.svg" alt="Microsoft">
            <figcaption>
              <h3>Brand</h3>
              <p>We worked with the UX team on photography for the site <code>img.blacklogo</code></p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/instagram.svg" alt="Instagram">
            <figcaption>
              <h3>Recruiting</h3>
              <p>We worked with Acme to develop recruiting processes. <code>img.blacklogo</code></p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#" title="Client">
          <figure>
            <img class="blacklogo" src="../static/images/logos/netflix.svg" alt="Netflix">
            <figcaption>
              <h3>Content Strategy</h3>
              <p>We partnered with various Netflix divisions to create a campaign for House of Cards.</p>
            </figcaption>
          </figure>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_39_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>ul.flexblock.steps</h3>
    <ul class="flexblock steps">
      <!-- li>a? Add blink = <ul class="flexblock steps blink">-->
      <li>
        <span>
          <svg class="fa-heartbeat">
            <use xlink:href="#fa-heartbeat"></use>
          </svg>
        </span>
        <h2>01. Passion</h2>
        <p>When you're really passionate about your job, you can change the world.</p>
      </li>
      <li>
        <div class="process step-2"></div>
        <span>
          <svg class="fa-magic">
            <use xlink:href="#fa-magic"></use>
          </svg>
        </span>
        <h2>02. Purpose</h2>
        <p>Why does this business exist? How are you different? Why matters?</p>
      </li>
      <li>
        <div class="process step-3"></div>
        <span>
          <svg class="fa-balance-scale">
            <use xlink:href="#fa-balance-scale"></use>
          </svg>
        </span>
        <h2>03. Principles</h2>
        <p>Leadership through usefulness, openness, empathy, and good taste.</p>
      </li>
      <li>
        <div class="process step-4"></div>
        <span>
          <svg class="fa-cog">
            <use xlink:href="#fa-cog"></use>
          </svg>
        </span>
        <h2>04. Process</h2>
        <ul>
          <li>Useful</li>
          <li>Easy</li>
          <li>Fast</li>
          <li>Beautiful</li>
        </ul>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_40_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>ul.flexblock.features</h3>
    <ul class="flexblock features">
      <li>
        <div>
          <h2>
            <span>&rarr;</span>
            Simple Navigation
          </h2>
          with arrow keys and swipe.
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-link">
              <use xlink:href="#fa-link"></use>
            </svg>
            Permalinks
          </h2>
          Go to a specific slide.
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-clock-o">
              <use xlink:href="#fa-clock-o"></use>
            </svg>
            Slide Counter
          </h2>
          Current/Total number
        </div>
      </li>
      <li>
        <div>
          <h2>
            <span>40<sup>+</sup></span>
            Beautiful Components
          </h2>
          Covers, cards, quotes...
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-text-height">
              <use xlink:href="#fa-text-height"></use>
            </svg>
            Vertical Rhythm
          </h2>
          Use multiples of 8.
        </div>
      </li>
      <li>
        <div>
          <h2>
            <span>500<sup>+</sup></span>
            SVG Icons
          </h2>
          Font Awesome Kit.
        </div>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_41_1600x1200.png)
```html
<section>
  <div class="wrap">
    <!-- [class*="content-"] = container max-width:50% = 600px -->
    <div class="content-center">
      <h3>ul.flexblock.specs</h3>
      <ul class="flexblock specs">
        <li>
          <div>
            <h2>
              <svg class="fa-long-arrow-right">
                <use xlink:href="#fa-long-arrow-right"></use>
              </svg>
              Navigation with arrow keys and slide counter
            </h2>
            Fade transition to all slides.
          </div>
        </li>
        <li>
          <div>
            <h2>
              <svg class="fa-link">
                <use xlink:href="#fa-link"></use>
              </svg>
              Permalinks
            </h2>
            Go to a specific slide. URL: #slide=number
          </div>
        </li>
        <li>
          <div>
            <h2>
              <svg class="fa-text-height">
                <use xlink:href="#fa-text-height"></use>
              </svg>
              Vertical rhythm
            </h2>
            Use multiples of 8.
          </div>
        </li>
      </ul>
    </div>
    <!-- end .content-center -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_42_1600x1200.png)
```html
<section>
  <div class="wrap">
    <div class="card-50">
      <div class="flex-content">
        <h3>ul.flexblock.specs</h3>
        <ul class="flexblock specs">
          <li>
            <div>
              <svg class="fa-wifi">
                <use xlink:href="#fa-wifi"></use>
              </svg>
              <h2>Ultra-Fast WiFi</h2>
              Simple and secure file sharing.
            </div>
          </li>
          <li>
            <div>
              <svg class="fa-battery-full">
                <use xlink:href="#fa-battery-full"></use>
              </svg>
              <h2>All day battery life</h2>
              Your battery worries may be over.
            </div>
          </li>
          <li>
            <div>
              <svg class="fa-life-ring">
                <use xlink:href="#fa-life-ring"></use>
              </svg>
              <h2>Lifetime Warranty </h2>
              We'll fix it or if we can't, we'll replace it.
            </div>
          </li>
        </ul>
      </div>
      <!-- end .flex-content-->
      <figure>
        <img class="aligncenter" src="../static/images/iphone.png" alt="iPhone">
      </figure>
    </div>
    <!-- .end card-50 -->
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_43_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>CVS and News</h3>
    <p><code>ul.flexblock.activity</code></p>
    <ul class="flexblock activity">
      <li>
        <a href="#" title="UX Designer at ACME">
          <div>
            <p class="year">
              2016
            </p>
            <p class="title">
              UX Designer at ACME
            </p>
            <p class="summary">
              This is a job description for the UX Designer role at ACME. Be concise. Content like a tweet: 2-3 lines recommended.
            </p>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="14 world famous buildings to inspire you">
          <p class="year">
            2 mins ago
          </p>
          <p class="title">
            14 world famous buildings to inspire you
          </p>
          <p class="summary">
            From the Colosseum to the Chrysler building, get a dose of inspiration from 14 of the world's most famous buildings.
          </p>
        </a>
      </li>
      <li>
        <a href="#" title="Co-Founder of GAMMA">
          <p class="year">
            2013
          </p>
          <p class="title">
            Co-Founder of GAMMA
          </p>
          <p class="summary">
            The culture within an organization is an essential part for success. This is a job description. Be concise. 2-3 lines recommended.
          </p>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_44_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>Portfolio, team, work, showcase...</h3>
    <p><code>ul.flexblock.gallery</code></p>
    <ul class="flexblock gallery">
      <li>
        <a href="#">
          <figure>
            <img alt="Thumbnail" src="https://source.unsplash.com/vCF5sB7QecM/800x600">
            <figcaption>
              <h2>uWatch</h2>
              <p>By Jane Doe</p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#">
          <figure>
            <img alt="Thumbnail " src="https://source.unsplash.com/yvx7LSZSzeo/800x600">
            <figcaption>
              <h2>Ellen Daniels</h2>
              <p>CEO</p>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="#">
          <figure>
            <img alt="Thumbnail" src="https://source.unsplash.com/-sQ4FsomXEs/800x600">
            <figcaption>
              <h2>New York</h2>
              <p>3,456 rooms</p>
            </figcaption>
          </figure>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_45_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>Portfolio, team, work, showcase...</h3>
    <p><code>ul.flexblock.gallery + .overlay</code></p>
    <ul class="flexblock gallery">
      <li>
        <a href="#">
          <figure>
            <img alt="Thumbnail " src="https://source.unsplash.com/-sQ4FsomXEs/800x600">
            <div class="overlay">
              <h2>New York</h2>
              <p>1,234 rooms</p>
            </div>
          </figure>
        </a>
      </li>
      <li>
        <a href="#">
          <figure>
            <img alt="Thumbnail" src="https://source.unsplash.com/vCF5sB7QecM/800x600">
            <span class="overlay">
              <h2>uWatch</h2>
              <time datetime="2017-12-17T21:23:34-05:00">December 2017</time>
            </span>
          </figure>
        </a>
      </li>
      <li>
        <a href="#">
          <figure>
            <img alt="Thumbnail" src="https://source.unsplash.com/yvx7LSZSzeo/800x600">
            <span class="overlay">
              <h2>Ellen Daniels</h2>
              <p>CEO</p>
            </span>
          </figure>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_46_1600x1200.png)
```html
<section class="aligncenter">
  <div class="wrap">
    <ul class="flexblock gallery">
      <li>
        <a href="../demos/why-webslides.html" title="Why WebSlides?">
          <figure>
            <img alt="Thumbnail Why WebSlides?" src="https://webslides.tv/static/images/demos-why.png">
            <figcaption>
              <h2>Why WebSlides?</h2>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="../demos/landings.html" title="Landings">
          <figure>
            <img alt="Thumbnail Landings" src="https://webslides.tv/static/images/demos-landings.png">
            <figcaption>
              <h2>Landings</h2>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="../demos/portfolios.html" title="Portfolios">
          <figure>
            <img alt="Thumbnail Portfolios" src="https://webslides.tv/static/images/demos-portfolios.png">
            <figcaption>
              <h2>Portfolios</h2>
            </figcaption>
          </figure>
        </a>
      </li>
      <li>
        <a href="../demos/keynote.html" title="Apple Keynote">
          <figure>
            <img alt="Thumbnail Apple Keynote" src="https://webslides.tv/static/images/demos-apple.png">
            <figcaption>
              <h2>Apple Keynote</h2>
            </figcaption>
          </figure>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_47_1600x1200.png)
```html
<section class="bg-green">
  <div class="wrap">
    <h3>ul.flexblock.metrics.border</h3>
    <!-- li>a? Add blink = <ul class="flexblock metrics blink">-->
    <ul class="flexblock metrics border">
      <li> Founded
        <span>2024</span>
      </li>
      <li>
        <span>
          <svg class="fa-users">
            <use xlink:href="#fa-users"></use>
          </svg>
        </span>
        24M Subscribers
      </li>
      <li>
        <span>
          <svg class="fa-line-chart">
            <use xlink:href="#fa-line-chart"></use>
          </svg>
        </span>
        Revenue: $16M
      </li>
      <li>
        Monthly Growth
        <span>64%</span>
      </li>
      <li>
        <span>
          <svg class="fa-building-o">
            <use xlink:href="#fa-building-o"></use>
          </svg>
        </span>
        8 Offices
      </li>
      <li>
        <span>
          <svg class="fa-smile-o">
            <use xlink:href="#fa-smile-o"></use>
          </svg>
        </span>
        48 Employees
      </li>
      <li>
        <span>
          <svg class="fa-usd">
            <use xlink:href="#fa-usd"></use>
          </svg>
        </span>
        EBITDA: $2,4M
      </li>
      <li>
        <span>
          <svg class="fa-university">
            <use xlink:href="#fa-university"></use>
          </svg>
        </span>
        Bank: $32M
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_48_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h2 class="aligncenter">ul.flexblock.plans.blink</h2>
    <ul class="flexblock plans blink">
      <li>
        <a href="#" title="Register">
          <h2>Basic</h2>
          <div>
            <span class="price">Free</span>
            <p>Good karma. Just essential features. 100% customizable. Make it yours.</p>
            <span class="button ghost">Select</span>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Purchase">
          <h2>Medium</h2>
          <div>
            <span class="price"><sup>$</sup>4,99 <sup>/month</sup></span>
            <p>Clean markup with popular naming conventions. Minimum effort.</p>
            <span class="button radius">Buy Now</span>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Purchase">
          <h2>Premium <sup>(save 20%)</sup></h2>
          <div>
            <span class="price"><sup>$</sup>40 <sup>/year</sup></span>
            <p>Prototype faster. Create landings and portfolios. Unlimited projects.</p>
            <span class="button ghost">Select</span>
          </div>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_49_1600x1200.png)
```html
<section>
  <div class="wrap size-50">
    <ul class="flexblock plans blink">
      <li>
        <a href="#" title="Register">
          <h2>Basic</h2>
          <div>
            <span class="price">Free</span>
            <ul>
              <li>
                <svg class="fa-check">
                  <use xlink:href="#fa-check"></use>
                </svg>
                <strong>Free</strong> forever
              </li>
              <li>
                <svg class="fa-check">
                  <use xlink:href="#fa-check"></use>
                </svg>
                <strong>Eternal</strong> sunshine
              </li>
              <li>
                <svg class="fa-check">
                  <use xlink:href="#fa-check"></use>
                </svg>
                <strong>Ads</strong>
              </li>
            </ul>
            <span class="button ghost">Select</span>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Purchase">
          <h2>Good Karma</h2>
          <div>
            <span class="price"><sup>$</sup>40 <sup>/year</sup></span>
            <ul>
              <li>
                <svg class="fa-check">
                  <use xlink:href="#fa-check"></use>
                </svg>
                <strong>Exclusive</strong> content
              </li>
              <li>
                <svg class="fa-check">
                  <use xlink:href="#fa-check"></use>
                </svg>
                <strong>Unlimited</strong> projects
              </li>
              <li>
                <svg class="fa-check">
                  <use xlink:href="#fa-check"></use>
                </svg>
                <strong>Unlimited</strong> users
              </li>
            </ul>
            <span class="button">Select</span>
          </div>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_50_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h3>ul.work</h3>
    <ul class="work">
      <li class="work-label">
        <p class="work-title">Work</p>
        <p class="work-client">Client</p>
        <p class="work-services">Services</p>
        <p class="work-date">Year</p>
      </li>
      <li>
        <a href="#" rel="external">
          <p class="work-title"><span>Redesign of Netflix</span></p>
          <p class="work-client"><span>Netflix</span></p>
          <p class="work-services"><span>Frontend</span></p>
          <p class="work-date"><span>2015-2016</span></p>
        </a>
      </li>
      <li>
        <a href="#" rel="external">
          <p class="work-title"><span>Airbnb TV Commercials</span></p>
          <p class="work-client"><span>Airbnb</span></p>
          <p class="work-services"><span>Video, Storytelling</span></p>
          <p class="work-date"><span>2015</span></p>
        </a>
      </li>
      <li>
        <a href="#" rel="external">
          <p class="work-title"><span>Tesla Software</span></p>
          <p class="work-client"><span>Tesla Motors</span></p>
          <p class="work-services"><span>Visual Design</span></p>
          <p class="work-date"><span>2014</span></p>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_51_1600x1200.png)
```html
<section class="aligncenter">
  <span class="background-right-top" style="background-image:url('https://webslides.tv/static/images/balloon.png')"></span>
  <div class="wrap">
    <p class="text-subtitle">Powered by <a href="https://twitter.com/search?f=tweets&vertical=default&q=%23WebSlides&src=typd">#WebSlides</a></p>
    <h1 class="text-landing">Landings</h1>
    <p class="text-intro">Create a simple web presence easily. <br> Clean markup and lovely CSS.
    </p>
    <p>
      <a href="https://github.com/jlantunez/webslides" class="button">
        <svg class="fa-github">
          <use xlink:href="#fa-github"></use>
        </svg>
        WebSlides
      </a>
    </p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_52_1600x1200.png)
```html
<section class="bg-primary">
  <span class="background-right-bottom" style="background-image:url('../static/images/iphone-hand.png')"></span>
  <div class="wrap">
    <div class="content-left">
      <p class="text-subtitle">Welcomes</p>
      <h2>
        <svg class="fa-apple">
          <use xlink:href="#fa-apple"></use>
        </svg>
        <strong>Call to action</strong>
      </h2>
      <p>Use your iPhone to pay securely and easily at over a million store locations and within apps — with a single touch.</p>
      <p>
        <a href="#" class="badge-ios" title="iOS App">iOS app</a>
        <a href="#" class="badge-android" title="Android app">Android app</a>
      </p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_53_1600x1200.png)
```html
<section>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <div class="cta-cover">
      <h1><strong>HTML Presentations</strong> Made Easy</h1>
      <p class="alignright">
        <a class="button" href="https://webslides.tv/webslides-latest.zip" title="Download WebSlides">
          <svg class="fa-cloud-download">
            <use xlink:href="#fa-cloud-download"></use>
          </svg>
          WebSlides
        </a>
        <span class="try"><a href="../demos/index.html" title="WebSlides Demos">Demos</a> &middot; <a href="https://github.com/jlantunez/webslides" title="Github">Github</a></span>
      </p>
    </div>
    <ul class="flexblock features">
      <li>
        <div>
          <h2><span>100<sup>%</sup></span> customizable</h2>
          Clean markup.
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-heart-o">
              <use xlink:href="#fa-heart-o"></use>
            </svg>
            Good Karma
          </h2>
          Just essential features.
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-code">
              <use xlink:href="#fa-code"></use>
            </svg>
            Prototype faster
          </h2>
          Design landings, portfolios...
        </div>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_54_1600x1200.png)
```html
<section>
  <div class="wrap">
    <h1>Design <span>for</span> understanding</h1>
    <ul class="flexblock features">
      <li>
        <div>
          <h2><span>100<sup>%</sup></span> purpose</h2>
          Businesses that people love
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-heart-o">
              <use xlink:href="#fa-heart-o"></use>
            </svg>
            Principles
          </h2>
          Useful &rarr; Easy &rarr; Fast &rarr; Beautiful
        </div>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_55_1600x1200.png)
```html
<section class="aligncenter">
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <div id="tab-3" class="tab-content current">
      <h1 class="text-landing">Tell a Story</h1>
      <p class="text-intro"><strong>Hi, this is WebSlides</strong>. HTML presentations made simple. <br>I'm a cute solution with clean markup and <strong>lovely CSS</strong>.</p>
    </div>
    <div id="tab-4" class="tab-content">
      <ul class="flexblock features">
        <li>
          <div>
            <svg class="fa-heart-o">
              <use xlink:href="#fa-heart-o"></use>
            </svg>
            <h2>Indexed content</h2>
            Sharing is caring.
          </div>
        </li>
        <li>
          <div>
            <h2>
              <svg class="fa-magic">
                <use xlink:href="#fa-magic"></use>
              </svg>
              Just essential features
            </h2>
            Keyboard navigation...
          </div>
        </li>
        <li>
          <div>
            <svg class="fa-bolt">
              <use xlink:href="#fa-bolt"></use>
            </svg>
            <h2>
              Prototype faster
            </h2>
            with clean code
          </div>
        </li>
      </ul>
    </div>
    <ul class="tabs">
      <li class="tab current" data-tab="tab-3">Purpose</li>
      <li class="tab" data-tab="tab-4">Benefits</li>
    </ul>
  </div>
</section>
```
![alt text](/screenshots/webslides_56_1600x1200.png)
```html
<section class="bg-black aligncenter">
  <!-- Overlay/Opacity: [class*="bg-"] > .background.dark or .light -->
  <span class="background" style="background-image:url('https://source.unsplash.com/UJbHNoVPZW0/')"></span>
  <div class="wrap">
    <h1 class="text-landing text-shadow"><strong>Covers</strong></h1>
  </div>
  <footer>
    <div class="wrap">
      <p>
        <span class="alignleft"> <a href="#" title="Instagram">
        <img class="whitelogo" src="../static/images/logos/instagram.svg" alt="Instagram">
        </a></span>
        <span class="alignright">
        <a href="#" class="badge-ios" title="iOS App">iOS app</a>
        <a href="#" class="badge-android" title="Android app">Android app</a>
        </span>
      </p>
    </div>
  </footer>
</section>
```
![alt text](/screenshots/webslides_57_1600x1200.png)
```html
<section class="bg-black aligncenter">
  <!-- Overlay/Opacity: [class*="bg-"] > .background.dark or .light -->
  <span class="background" style="background-image:url('https://source.unsplash.com/mGYxAWITqMg/')"></span>
  <div class="wrap">
    <p class="text-subtitle">Plan your next trip</p>
    <h1 class="text-landing text-shadow">Summ.er</h1>
    <p class="text-intro">The best places at the best price.</p>
    <p>
      <a href="#" class="badge-ios" title="iOS App">Install iOS app</a>
      <a href="#" class="badge-android" title="Android app">Install Android app</a>
    </p>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_58_1600x1200.png)
```html
<section class="bg-black aligncenter">
  <span class="background" style="background-image:url('https://source.unsplash.com/-g4dgdOExsw/')"></span>
  <div class="wrap">
    <h1 class="text-landing text-shadow"><strong>California</strong></h1>
    <p class="text-shadow">
      <svg class="fa-map-marker">
        <use xlink:href="#fa-map-marker"></use>
      </svg>
      Yosemite National Park.
    </p>
  </div>
  <footer class="bg-trans-dark">
    <div class="wrap">
      <p>
        <span class="alignleft"> <a href="#" title="Instagram">
        <img class="whitelogo" src="../static/images/logos/instagram.svg" alt="Instagram">
        </a></span>
        <span class="alignright">
        <a href="#" class="badge-ios" title="iOS App">Install iOS app</a>
        <a href="#" class="badge-android" title="Android app">Install Android app</a>
        </span>
      </p>
    </div>
  </footer>
</section>
```
![alt text](/screenshots/webslides_59_1600x1200.png)
```html
<section class="bg-gradient-v">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/nxfuA21kNHY/1440x1440')"></span>
  <div class="wrap size-60">
    <p class="text-context">GOOD KARMA</p>
    <h2>Making HTML Presentations Easy</h2>
  </div>
  <!-- .end .wrap -->
</section>
```
![alt text](/screenshots/webslides_60_1600x1200.png)
```html
<section class="bg-black slide-top">
  <span class="background" style="background-image:url('https://source.unsplash.com/sK1hW5knKkw/')"></span>
  <div class="wrap">
    <h2 class="text-landing">Living on Mars</h2>
    <p class="text-context text-intro">Paula Chan, CEO of SpaceY.</p>
  </div>
  <!-- .end .wrap -->
  <footer>
    <div class="wrap">
      <p>
        <span class="alignright"><img class="whitelogo" src="../static/images/logos/nyt.svg" alt="The New York Times"></span>
      </p>
    </div>
    <!-- .end .wrap -->
  </footer>
</section>

<section class="bg-black slide-top">
  <span class="background" style="background-image:url('https://source.unsplash.com/Q14J2k8VE3U/')"></span>
  <div class="wrap">
    <p class="text-context"><strong>PROBLEM &amp; SOLUTION</strong></p>
    <h2>The history of the music industry is also the story of the development of technology.</h2>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black aligncenter">
  <span class="background light" style="background-image:url('https://source.unsplash.com/rCOWMC8qf8A/')"></span>
  <div class="wrap">
    <h2 class="text-data">4,623,781</h2>
    <h3>downloads in first 24 hours </h3>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-apple aligncenter">
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <h2 class="text-data">$56 Billion</h2>
    <h3>Revenue in Q3 2017</h3>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black slide-bottom">
  <span class="background" style="background-image:url('https://source.unsplash.com/RSOxw9X-suY/')"></span>
  <div class="wrap">
    <div class="content-left">
      <p>
        <svg class="large fa-tree">
          <use xlink:href="#fa-tree"></use>
        </svg>
      </p>
      <h2>1,000,000</h2>
      <h3>We're working to protect up to a million acres of sustainable forest.</h3>
    </div>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="content-left">
      <h2>WebSlides help you build a culture of innovation.</h2>
    </div>
    <!-- end .content-left -->
    <div class="content-left">
      <p>All content is for demo purposes only, to show an example of a live site. The easiest way to make HTML presentations. Inspire and engage. </p>
    </div>
    <!-- end .content-left -->
    <ul class="flexblock metrics">
      <li> Founded
        <span>2040</span>
      </li>
      <li>
        <span>120+</span>
        Prebuilt Slides
      </li>
      <li>
        <span>
          <svg class="fa-users">
            <use xlink:href="#fa-users"></use>
          </svg>
        </span>
        24M Downloads
      </li>
      <li>
        <span>
          <svg class="fa-line-chart">
            <use xlink:href="#fa-line-chart"></use>
          </svg>
        </span>
        Revenue: $16M
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>

<section class="frame bg-primary aligncenter">
  <div class="wrap">
    <h2 class="text-landing">Abouts</h2>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <div class="content-left">
      <h2>WebSlides was made to inspire people.</h2>
    </div>
    <div class="content-left">
      <p>There are great presentation tools out there. This is about <strong>good karma</strong>: hypertext, clean code, and <strong>beauty</strong> as narrative elements. Three essential features.</p>
    </div>
    <ul class="flexblock features">
      <li>
        <div>
          <h2>
            <span>&rarr;</span>
            Keyboard navigation
          </h2>
          and swipe gestures.
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-link">
              <use xlink:href="#fa-link"></use>
            </svg>
            Go to a specific slide
          </h2>
          URL: #slide=number
        </div>
      </li>
      <li>
        <div>
          <h2>
            <svg class="fa-clock o">
              <use xlink:href="#fa-clock-o"></use>
            </svg>
            Slide counter
          </h2>
          Current/Total number.
        </div>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-primary">
  <div class="wrap">
    <div class="content-left">
      <h2>WebSlides help you build a culture of excellence.</h2>
    </div>
    <!-- end .content-left -->
    <div class="content-left">
      <p>All content is for demo purposes only, to show an example of a live site. All images are the copyright of their respective owners.</p>
    </div>
    <!-- end .content-left -->
    <ul class="flexblock">
      <li>
        <div>
          <img class="whitelogo" src="../static/images/logos/google.svg" alt="Google">
        </div>
      </li>
      <li>
        <div>
          <img class="whitelogo" src="../static/images/logos/microsoft.svg" alt="Microsoft">
        </div>
      </li>
      <li>
        <div>
          <img class="whitelogo" src="../static/images/logos/thetimes.svg" alt="The Times">
        </div>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-50">
  <h3>Table of Contents</h3>
  <hr>
    <div class="toc">
      <ol>
        <li>
          <a href="#" title="Go to Learning to see">
          <span class="chapter">Prologue: Learning to See</span>
          <span class="toc-page">01</span>
          </a>
        </li>
        <li><a href="#" title="Go to What is Design?"><span class="chapter">What is Design?</span>
          <span class="toc-page">04</span></a>
        </li>
        <li>
          <a href="#" title="Go to What is Beauty?"><span class="chapter">What is Beauty?</span>
          <span class="toc-page">08</span></a>
          <ol>
            <li><a href="#" title="Go to Harmony"><span class="chapter">Harmony</span>
              <span class="toc-page">12</span></a>
            </li>
            <li><a href="#" title="Go to Simplicity vs. Clarity"><span class="chapter">Simplicity vs. Clarity</span>
              <span class="toc-page">14</span></a>
            </li>
          </ol>
        </li>
        <li>
          <a href="#" title="Go to Building a Culture"><span class="chapter">Building a Culture</span>
          <span class="toc-page">16</span></a>
          <ol>
            <li>
              <span class="chapter">Purpose</span>
              <span class="toc-page">17</span>
              <ol>
                <li>
                  <span class="chapter">Valuable</span>
                  <span class="toc-page">18</span>
                  <ol>
                    <li><span class="chapter">Easy</span>
                      <span class="toc-page">20</span>
                    </li>
                    <li><span class="chapter">Elegant</span>
                      <span class="toc-page">21</span>
                    </li>
                  </ol>
              </ol>
            </li>
            <li><span class="chapter">Principles</span>
              <span class="toc-page">24</span>
            </li>
          </ol>
        </li>
        <li><span class="chapter">Epilogue</span>
          <span class="toc-page">40</span>
        </li>
      </ol>
    </div>
    <!-- end .toc -->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <div class="content-left">
      <h2>iPhone 7</h2>
      <p>A phone should be absolutely simple, beautiful, and magical to use. 3D Touch, 12MP photos, and 4K video.</p>
      <div class="content-left">
        <h3>Benefit 1</h3>
        <p>The easiest way to make HTML presentations. Incredibly versatile. 120+ slides.</p>
      </div>
      <!-- .end .content-left -->
      <div class="content-left">
        <h3>Benefit 2</h3>
        <p>The art of storytelling. Inspire teams, fascinate customers, and gain attention from investors.</p>
      </div>
      <!-- .end .content-left -->
    </div>
    <!-- .end .content-left -->
    <div class="content-left">
      <img src="../static/images/iphone.png" alt="iPhone">
    </div>
    <!-- .end .content-left -->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="grid vertical-align">
      <div class="column">
        <figure><img class="aligncenter" src="../static/images/iphone.png" alt="iPhone"></figure>
      </div>
      <div class="column">
        <h1>
          <svg class="fa-apple">
            <use xlink:href="#fa-apple"></use>
          </svg>
          iPhone 7
        </h1>
        <p class="text-intro">3D Touch, 12MP photos, and 4K video. Centering vertically using grid.vertical-align</p>
        <p>Every iPhone they have made was built on the same belief. That a phone should be more than a collection of features. That, above all, a phone should be absolutely simple, beautiful, and magical to use.</p>
        <p><a class="button" href="http://apple.com/iphone/">apple.com/iphone</a></p>
      </div>
    </div>
    <!-- end .grid-->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="grid vertical-align">
      <div class="column">
        <h1>
          <svg class="fa-android">
            <use xlink:href="#fa-android"></use>
          </svg>
          Pixel
        </h1>
        <p class="text-intro">The first phone with the Google Assistant built in. Centering vertically using grid.vertical-align.</p>
        <p>It has the highest rated smartphone camera. Ever. A battery that lasts all day. <strong>Unlimited storage for all your photos and videos</strong>. And it’s the first phone with the Google Assistant built in.</p>
      </div>
      <!-- end .column-->
      <div class="column">
        <figure>
          <img src="../static/images/android.png" alt="Pixel Phone">
        </figure>
      </div>
      <!-- end figure-->
    </div>
    <!-- end .grid-->
  </div>
  <!-- end .wrap-->
</section>

<section class="frame bg-blue aligncenter">
  <div class="wrap">
    <h2 class="text-landing">Cards</h2>
    <p>Centering vertically using flexbox.</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="card-50 bg-white">
      <figure>
        <img src="https://source.unsplash.com/pRU-VnBVJMQ/800x600" alt="Florence, Italy">
        <figcaption>
          <a href="https://unsplash.com/@jonko" title="Jonathan Körner">
            <svg class="fa-camera">
              <use xlink:href="#fa-camera"></use>
            </svg>
            Jonathan Körner (Unsplash)
          </a>
        </figcaption>
      </figure>
      <!-- end figure-->
      <div class="flex-content">
        <h2>
          Cards
        </h2>
        <p>Florence, Italy &mdash; <strong>.card-50</strong></p>
        <ul class="description">
          <li>
            <strong class="text-label">Area:</strong> 102.41 km<sup>2</sup>
          </li>
          <li><strong class="text-label">Population:</strong> 383,083.</li>
          <li><strong class="text-label">Website:</strong> <a href="http://www.comune.fi.it/">comune.fi.it</a></li>
        </ul>
        <p>
          Florence was a centre of medieval European trade and finance and one of the wealthiest cities of the time. It is considered the birthplace of the Renaissance, and has been called "the Athens of the Middle Ages".
        </p>
      </div>
      <!-- end .flex-content-->
    </div>
    <!-- .end .card50 -->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="card-60 bg-white">
      <figure>
        <img src="https://source.unsplash.com/lOqxtpaxZXQ/800x600" alt="Il Doumo, Florence">
        <figcaption>
          <a href="https://unsplash.com/@karlyewolff" title="Karlye Wolff">
            <svg class="fa-camera">
              <use xlink:href="#fa-camera"></use>
            </svg>
            Karlye Wolff (Unsplash)
          </a>
        </figcaption>
      </figure>
      <!-- end figure-->
      <div class="flex-content">
        <h2>
          Cards
        </h2>
        <p>Il Duomo, Florence &mdash; <strong>.card-60</strong></p>
        <p>
          <strong>Stendhal syndrome</strong> is a disorder that causes rapid heartbeat and dizziness when an individual is exposed to an experience of great personal significance, particularly viewing art.
        </p>
        <p>
          The illness is named after the 19th-century French author Stendhal, who described his experience with the phenomenon during his 1817 visit to Florence.
        </p>
      </div>
      <!-- end .flex-content-->
    </div>
    <!-- .end .card50 -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="fullscreen">
  <div class="card-50">
    <figure>
      <img src="https://source.unsplash.com/2QHEC81Dt0c/" alt="Áqaba, Jordan">
      <figcaption>
        <a href="https://unsplash.com/@dburka" title="Daniel Burka">
          <svg class="fa-camera">
            <use xlink:href="#fa-camera"></use>
          </svg>
          Daniel Burka (Unsplash)
        </a>
      </figcaption>
    </figure>
    <!-- end figure-->
    <div class="flex-content">
      <h2>Discover Jordan
      </h2>
      <p>.fullscreen > .card-50</p>
      <p class="text-intro">Aqaba is the only coastal city in Jordan and the largest and most populous city on the Gulf of Aqaba.</p>
      <p class="aligncenter"><a class="button" href="https://en.wikipedia.org/wiki/Aqaba">Read more &raquo;</a></p>
    </div>
    <!-- end .flex-content-->
  </div>
  <!-- end .card-50-->
</section>

<section class="aligncenter">
  <div class="wrap">
    <h2><strong>Offers and Discounts</strong></h2>
  </div>
  <!-- .end .wrap -->
</section>

<section class="frame bg-red">
  <div class="wrap">
    <div class="cta">
      <div class="number">
        <p><span><sup>$</sup>40</span></p>
      </div>
      <!--end .number -->
      <div class="benefit">
        <h2>Watch TV shows anytime, anywhere</h2>
        <p>.frame.bg-red</p>
      </div>
      <!--end .benefit -->
    </div>
    <!--end .cta -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="frame bg-red">
  <div class="wrap">
    <div class="cta">
      <div class="number">
        <img class="whitelogo" src="../static/images/logos/netflix.svg" alt="Netflix">
      </div>
      <!--end .number -->
      <div class="benefit">
        <h2>Get 8 weeks free</h2>
      </div>
      <!--end .benefit -->
    </div>
    <!--end .cta -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="frame bg-red">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/R1J6Z1cnJZc/')"></span>
  <div class="wrap">
    <div class="cta">
      <div class="number">
        <img class="whitelogo" src="../static/images/logos/netflix.svg" alt="Netflix">
      </div>
      <!--end .number -->
      <div class="benefit">
        <h2>Get 8 weeks free</h2>
      </div>
      <!--end .benefit -->
    </div>
    <!--end .cta -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-red">
  <div class="wrap">
    <h2 class="aligncenter">Choose one plan</h2>
    <p class="aligncenter">Simple pricing. No credit card required!</p>
    <table>
      <thead>
       <tr>
        <th>Plans</th>
        <th>Good</th>
        <th>Better</th>
        <th>Awesome</th>
       </tr>
      </thead>
      <tbody>
        <tr>
          <td>Price</td>
          <td>Free</td>
          <td>$6</td>
          <td>$10</td>
        </tr>
        <tr>
          <td>HD Streaming</td>
          <td>No</td>
          <td>Yes</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>Screens you can watch on at the same time</td>
          <td>1</td>
          <td>2</td>
          <td>Unlimited</td>
        </tr>
        <tr>
          <td>Access to exclusive content</td>
          <td>No</td>
          <td>No</td>
          <td>Yes</td>
        </tr>
      </tbody>
    </table>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black aligncenter">
  <span class="background light" style="background-image:url('https://source.unsplash.com/hHL08lF7Ikc/')"></span>
  <div class="wrap">
    <h2 class="text-landing"><strong>Quotes</strong></h2>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <!-- alignment [class*="content-"] = container max-width:50% = 600px -->
    <div class="content-center">
      <h2><strong>Why WebSlides?</strong></h2>
      <blockquote>
        <p>"I feel guilty as a web designer when I have to use PowerPoint and Keynote. So I made #WebSlides."</p>
        <p><cite> <img class="avatar-40" src="../static/images/avatar.jpg" alt="Avatar"> <a href="http://twitter.com/jlantunez/">@jlantunez</a></cite></p>
      </blockquote>
    </div>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black-blue">
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <blockquote class="wall">
      <p>Leadership is not bullying and leadership is not aggression. Leadership is the expectation that you can use your voice for good.</p>
      <p><cite><a href="https://en.wikipedia.org/wiki/Sheryl_Sandberg">Sheryl Sandberg</a>, COO of Facebook.</cite></p>
    </blockquote>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-primary">
  <!--.wrap = container 1200px -->
  <div class="wrap size-50">
    <blockquote class="wall">
      <p>Finally, everything you need to make HTML presentations in a simple way.</p>
      <p><cite><a href="https://twitter.com/jlantunez">@jlantunez</a></cite></p>
    </blockquote>
  </div>
  <!-- .end .wrap -->
  <footer>
    <div class="wrap">
      <p>
        <span class="alignleft"><img class="whitelogo" src="../static/images/logos/google.svg" alt="Google"></span>
        <span class="alignright">#TechConf</span>
      </p>
    </div>
  </footer>
</section>

<section>
  <div class="wrap">
    <div class="card-50">
      <a href="https://en.wikipedia.org/wiki/Leonardo_da_Vinci" title="Leonardo da Vinci - Wikipedia">
        <blockquote>
          <p>&ldquo;WebSlides helped us build a culture of innovation and excellence.&rdquo;</p>
          <p><cite>Leonardo da Vinci</cite></p>
        </blockquote>
        <figure><img src="../static/images/davinci.png" alt="Leonardo da Vinci"></figure>
      </a>
    </div>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-primary">
  <span class="background-left-bottom" style="background-image:url('https://webslides.tv/static/images/satya.png')"></span>
  <div class="wrap">
    <div class="content-right">
      <blockquote>
        <p>"Businesses and users are going to use technology only if they can trust it."</p>
        <p><cite>Satya Nadella.</cite></p>
      </blockquote>
    </div>
  </div>
  <!-- .end .wrap -->
  <footer>
    <p class="alignright"><img class="whitelogo" src="../static/images/logos/microsoft.svg" alt="Microsoft"></p>
  </footer>
</section>

<section>
  <div class="wrap">
    <div class="content-left">
      <h2>Buttons</h2>
      <p>
        <a href="#" class="button" title="Button">
        .button</a>
        <a href="#" class="button" title="Button">
          <svg class="fa-github">
            <use xlink:href="#fa-github"></use>
          </svg>
          svg icon
        </a>
      </p>
      <p>
        <a href="#" class="button radius" title="Button">
        .button.radius</a> <a href="#" class="button ghost" title="Button">
        .button.ghost</a>
      </p>
    </div>
    <div class="content-left">
      <h2>Badges</h2>
      <p><code>a.badge-ios</code> and <code>a.badge-android</code></p>
      <p>
        <a href="#" class="badge-ios" title="Download iOS App">
        iOS App</a>
        <a href="#" class="badge-android" title="Download Android App">
        Android App</a>
      </p>
    </div>
  </div>
  <!-- .end .wrap -->
</section>
<section class="bg-black aligncenter">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/CxYHfBkC0vs/')"></span>
  <div class="wrap">
    <h1 class="text-landing">Forms</h1>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black">
  <span class="background" style="background-image:url('https://source.unsplash.com/p3UCTiZIU6M/')"></span>
  <!--.wrap = container 1200px -->
  <div class="wrap size-70 aligncenter">
    <h2>Planning a vacation?</h2>
    <p class="text-intro">Hidden attractions and unusual things to do.</p>
    <form action="/" method="post" class="bg-trans-dark">
      <ul class="flexblock">
        <li><input type="email" tabindex="1" name="email" placeholder="your@email.com" required></li>
        <li><input type="password" tabindex="2" name="password" placeholder="Password" required></li>
        <li><button type="submit" class="radius" tabindex="3" title="Sign Up">Sign Up &rsaquo;</button></li>
      </ul>
    </form>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-green">
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <div class="grid vertical-align">
      <div class="column">
        <form action="/" method="post">
          <fieldset>
            <legend>Create a free account</legend>
            <p><input type="text" tabindex="1" name="username" placeholder="Username" required></p>
            <p><input type="email" tabindex="2" name="email" placeholder="your@email.com" required></p>
            <p><input type="password" tabindex="3" name="password" placeholder="Password" required></p>
            <p><button type="submit" tabindex="4" title="Sign Up">Sign Up &rsaquo;</button></p>
          </fieldset>
        </form>
      </div>
      <!-- .end .column -->
      <div class="column">
        <ul class="flexblock specs">
          <li>
            <div>
              <svg class="fa-heart-o">
                <use xlink:href="#fa-heart-o"></use>
              </svg>
              <h2>Good karma </h2>
              Just essential features.
            </div>
          </li>
          <li>
            <div>
              <svg class="fa-bolt">
                <use xlink:href="#fa-bolt"></use>
              </svg>
              <h2>Fast &amp; Versatile</h2>
              No need to know code. 120+ slides.
            </div>
          </li>
          <li>
            <div>
              <svg class="fa-lock">
                <use xlink:href="#fa-lock"></use>
              </svg>
              <h2>Private Network</h2>
              Simple and secure file sharing.
            </div>
          </li>
        </ul>
      </div>
      <!-- .end .column -->
    </div>
    <!-- .end .grid -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-apple">
  <span class="background-right-bottom" style="background-image:url('../static/images/iphone-hand.png')"></span>
  <div class="wrap">
    <div class="content-left">
      <h1>
        <svg class="fa-apple">
          <use xlink:href="#fa-apple"></use>
        </svg>
        Pay
      </h1>
      <p>Use your iPhone to pay securely and easily at over a million store locations and within apps — with a single touch. See where you can use Apple Pay:
      </p>
      <form action="/" class="user" method="post">
        <input type="search" name="location" tabindex="1" placeholder="Stores in your city..." required>
        <button type="submit" tabindex="2" title="Search">Search &rsaquo;</button>
      </form>
    </div>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-primary">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/RkBTPqPEGDo/')"></span>
  <!--.wrap = container 1200px -->
  <div class="wrap size-30">
    <p><a href="#" title="Microsoft"><img class="whitelogo aligncenter" src="../static/images/logos/microsoft.svg" alt="Microsoft"></a></p>
    <form action="/" method="post">
      <fieldset>
        <legend>Welcome back</legend>
        <p><label>Username or Email</label>
          <input type="text" tabindex="1" name="email" placeholder="your@email.com" required>
        </p>
        <p><label>Password <span class="alignright"><a href="#" title="Forgot password?">Forgot?</a></span></label>
          <input type="password" tabindex="2" name="password" placeholder="6 characters minimum" required>
        </p>
        <p>
          <button type="submit" tabindex="3" title="Login">Login &rsaquo;</button>
        </p>
      </fieldset>
    </form>
    <p class="aligncenter">Don't have an account? <a href="#" title="Register">Sign up!</a></p>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black aligncenter">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/Zq_K89I9E-8/)"></span>
  <div class="wrap">
    <h2 class="text-landing">Media</h2>
    <p class="text-intro">Background images, videos, charts, maps...</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <span class="background" style="background-image:url('https://source.unsplash.com/LcDPAqX8dt8/)"></span>
  <div class="wrap size-50">
    <h3>
      <svg class="fa-camera">
        <use xlink:href="#fa-camera"></use>
      </svg>
      Unsplash = Fullscreen Backgrounds
    </h3>
    <p class="text-intro"><a href="https://source.unsplash.com/">How to embed Unsplash photos? &rarr;</a></p>
    <pre>&lt;section&gt;
&lt;span class="background" style="background-image:url('https://source.unsplash.com/LcDPAqX8dt8/')"&gt;&lt;/span&gt;
&lt;div class="wrap"&gt;
&lt;h1&gt;Slide&lt;/h1&gt;
&lt;/div&gt;
&lt;/section&gt;</pre>
    <p>
      <svg class="fa-info">
        <use xlink:href="#fa-info"></use>
      </svg>
      Position .background outside of .wrap container.
    </p>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black aligncenter">
  <span class="background light" style="background-image:url('https://source.unsplash.com/1_CMoFsPfso/')"></span>
  <div class="wrap size-50">
    <h1 class="text-landing text-shadow">Opacity</h1>
    <p><code>[class*="bg-"] > .background.light</code></p>
    <pre>&lt;section class="bg-black"&gt;
&lt;span class="background light" style="background-image:url('https://source.unsplash.com/1_CMoFsPfso/')"&gt;&lt;/span&gt;
&lt;div class="wrap"&gt;
&lt;h1&gt;Slide&lt;/h1&gt;
&lt;/div&gt;
&lt;/section&gt;</pre>
  </div>
</section>

<section class="bg-black aligncenter">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/1_CMoFsPfso')"></span>
  <div class="wrap size-50">
    <h1 class="text-landing text-shadow">Opacity</h1>
    <p><code>[class*="bg-"] > .background.dark</code></p>
    <pre>&lt;section class="bg-black"&gt;
&lt;span class="background dark" style="background-image:url('https://source.unsplash.com/1_CMoFsPfso/')"&gt;&lt;/span&gt;
&lt;div class="wrap"&gt;
&lt;h1&gt;Slide&lt;/h1&gt;
&lt;/div&gt;
&lt;/section&gt;</pre>
  </div>
</section>

<section>
  <div class="wrap">
    <h3>16 Different Backgrounds</h3>
    <ul class="text-cols">
      <li><strong>.background</strong> (cover)</li>
      <li>.background-top (cover)</li>
      <li>.background-bottom (cover)</li>
      <li>.background.light (opacity)</li>
      <li>.background.dark (opacity)</li>
      <li>.background-center</li>
      <li>.background-center-top</li>
      <li>.background-center-bottom</li>
      <li>.background-left</li>
      <li>.background-left-top</li>
      <li>.background-left-bottom</li>
      <li>.background-right</li>
      <li>.background-right-top</li>
      <li>.background-right-bottom</li>
      <li>.background-anim (animated)</li>
      <li>.<strong>background-video</strong> (fullscreen)</li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <span class="background-right-bottom" style="background-image:url('../static/images/iphone-hand.png')"></span>
  <div class="wrap">
    <div class="content-left">
      <h3>.background-(position)</h3>
      <p><code>.background-right-bottom</code></p>
      <ul class="flexblock specs">
        <li>
          <div>
            <svg class="fa-wifi">
              <use xlink:href="#fa-wifi"></use>
            </svg>
            <h2>Ultra-Fast WiFi</h2>
            Simple and secure file sharing.
          </div>
        </li>
        <li>
          <div>
            <svg class="fa-battery-full">
              <use xlink:href="#fa-battery-full"></use>
            </svg>
            <h2>All day battery life</h2>
            Your battery worries may be over.
          </div>
        </li>
        <li>
          <div>
            <svg class="fa-life-ring">
              <use xlink:href="#fa-life-ring"></use>
            </svg>
            <h2>Lifetime Warranty </h2>
            We'll fix it or if we can't, we'll replace it.
          </div>
        </li>
      </ul>
    </div>
  </div>
  <!-- .end .wrap -->
</section>

<section class="aligncenter bg-black">
  <span class="background anim" style="background-image:url('https://source.unsplash.com/n9WPPWiPPJw/')"></span>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <h2>.background.anim</h2>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-60">
    <h3>Background Videos</h3>
    <pre>&lt;video class="background-video" autoplay muted loop poster="image.jpg"&gt;
&lt;source src="video.mp4" type="video/mp4"&gt;
&lt;/video&gt;</pre>
    <p><code>.background-video</code></p>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-blue aligncenter">
  <video class="background-video dark" autoplay loop muted poster="https://webslides.tv/static/images/peggy.jpg">
    <source src="https://webslides.tv/static/videos/peggy.mp4" type="video/mp4">
  </video>
  <div class="wrap">
    <h2><strong>Be Awesome</strong></h2>
    <p>Overlay: <code>section.bg-blue > .background-video.dark</code> or .light</p>
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black aligncenter">
  <span class="background dark" style="background-image:url('https://source.unsplash.com/MDGpwpMY2Ws/')"></span>
  <div class="wrap">
    <h2>Embedding Media</h2>
    <p>Videos, charts, maps...</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="content-left">
      <h3>Responsive Videos</h3>
      <pre>&lt;div class="embed"&gt;
&lt;iframe src="https://www.youtube.com/embed/XjJQBjWYDTs"&gt;
&lt;/iframe&gt;
&lt;/div&gt;</pre>
      <p><code>.embed</code></p>
    </div>
    <!-- end .content-left -->
    <div class="content-left">
      <!-- <div class="embed"> = Responsive -->
      <div class="embed">
        <iframe src="https://www.youtube.com/embed/XjJQBjWYDTs" allowfullscreen></iframe>
      </div>
      <!-- end .embed -->
    </div>
    <!-- end .content-left -->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-60">
    <!-- Responsive video/iframe... Add <div class="embed"> -->
    <div class="embed">
      <iframe width="800" height="450" src="https://www.youtube.com/embed/_m67JbGjWnc?list=PL27Ptt5XwkS39IrY8SeNaELghs_NLjMEs" allowfullscreen></iframe>
    </div>
    <!-- .end .embed -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="fullscreen">
  <!-- Fullscreen Video -->
  <div class="embed">
    <iframe width="800" height="450" src="https://www.youtube.com/embed/BzMLA8YIgG0" allowfullscreen></iframe>
  </div>
  <!-- .end .embed -->
</section>

<section>
  <div class="wrap size-60">
    <h3><a href="https://www.theatlas.com/" title="I love Quartz's charts">Charts</a></h3>
    <!-- Responsive video/iframe/chart... Add <div class="embed"> -->
    <div class="embed">
      <!-- I love Quartz's charts -->
      <div class="atlas-chart" data-id="H1tz4P9G" data-width="640" data-height="449"><img alt="Chart" src="https://www.theatlas.com/i/atlas_H1tz4P9G.png" style="max-width: 100%;"></div>
      <script src="https://www.theatlas.com/javascripts/atlas.js"></script>
    </div>
    <!-- end .embed -->
  </div>
  <!-- .end .wrap -->
</section>

<section class="bg-black-blue frame">
  <div class="wrap size-50">
    <p class="text-context">Status of Net Neutrality around the world.</p>
    <div class="embed">
      <iframe width='800' height='450' src='https://dejiaccessnow.carto.com/viz/4f239c60-356f-11e5-b01c-0e853d047bba/embed_map' allowfullscreen></iframe>
    </div>
    <!-- .end .embed -->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-50">
    <p class="text-subtitle">Optional &middot; 500+ icons</p>
    <h2>
      <a href="http://fontawesome.io/icons/">
        <svg class="fa-flag">
          <use xlink:href="#fa-flag"></use>
        </svg>
        Font Awesome
      </a>
      as SVG icons
    </h2>
    <pre>&lt;svg class="fa-flag"&gt;
&lt;use xlink:href="#fa-flag"&gt;&lt;/use&gt;
&lt;/svg&gt;</pre>
    <p>How to change icons?</p>
    <ol class="text-cols">
      <li>Go to <a href="http://fontastic.me/">fontastic.me</a>.</li>
      <li>Create a free account.</li>
      <li>Select new icons.</li>
      <li>Publish as SVG sprite.</li>
      <li>Edit <strong>svg-icons.css</strong> and <strong>svg.icons.js</strong>.</li>
    </ol>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <h2>Transparent Logos</h2>
    <p>
      Change the color of a .svg/.png image using CSS. Images are property of their respective owners.
    </p>
    <hr>
    <ul class="flexblock blink">
      <li>
        <a href="#" title="Block Link = .blink">
          <div>
            <img src="../static/images/logos/google.svg" alt="Google">
            <p><strong>Height recommended</strong>: 48px</p>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <div>
            <img class="blacklogo" src="../static/images/logos/airbnb.svg" alt="Airbnb">
            <p><code>img.blacklogo</code></p>
          </div>
        </a>
      </li>
      <li>
        <a href="#" title="Block Link = .blink">
          <div>
            <img class="graylogo" src="../static/images/logos/microsoft.svg" alt="Microsoft">
            <p><code>img.graylogo</code></p>
          </div>
        </a>
      </li>
      <li class="bg-blue">
        <a href="" title="Block Link = .blink">
          <div>
            <img class="whitelogo" src="../static/images/logos/netflix.svg" alt="Netflix">
            <p><code>img.whitelogo</code></p>
          </div>
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <!--.wrap = container 1200px -->
  <div class="wrap">
    <blockquote class="wall">
      <p>"An avatar is the graphical representation of the user or the user's alter ego or character. The <a href="https://en.wikipedia.org/wiki/Avatar_(computing)">word avatar</a> originates in Hinduism."</p>
      <p><cite> <a href="http://twitter.com/username/"><img class="avatar-56" src="../static/images/avatar.jpg" alt="Avatar"> @username</a>, .avatar-56</cite></p>
    </blockquote>
    <hr>
    <p><code>img[class*="avatar-"]</code> (80, 72, 64, 56, 48, and 40).</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap">
    <div class="grid vertical-align">
      <div class="column">
        <h2>Devices</h2>
        <ul class="flexblock specs">
          <li>
            <div>
              <svg class="fa-wifi">
                <use xlink:href="#fa-wifi"></use>
              </svg>
              <h2>Ultra-Fast WiFi</h2>
              Simple and secure file sharing.
            </div>
          </li>
          <li>
            <div>
              <svg class="fa-battery-full">
                <use xlink:href="#fa-battery-full"></use>
              </svg>
              <h2>All day battery life</h2>
              Your battery worries may be over.
            </div>
          </li>
          <li>
            <div>
              <svg class="fa-life-ring">
                <use xlink:href="#fa-life-ring"></use>
              </svg>
              <h2>Lifetime Warranty </h2>
              We'll fix it or if we can't, we'll replace it.
            </div>
          </li>
        </ul>
      </div>
      <!-- end .column-->
      <div class="column">
        <figure>
          <img class="aligncenter" src="../static/images/iphone.png" alt="iPhone">
        </figure>
      </div>
      <!-- end .column-->
    </div>
    <!-- end .grid-->
  </div>
  <!-- end .wrap-->
</section>

<section>
  <div class="wrap">
    <div class="content-left">
      <figure class="browser">
        <img alt="Screenshot" src="https://webslides.tv/static/images/cover-apple.jpg">
      </figure>
    </div>
    <!-- .end .content-left -->
    <div class="content-left">
      <h2>Screenshots</h2>
      <p>HTML/CSS Browser.</p>
      <pre>&lt;figure class="browser"&gt;
&lt;img alt="Screenshot" src="image.png"&gt;
&lt;/figure&gt;</pre>
    </div>
    <!-- .end .content-left -->
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-50">
    <h2>CSS Animations</h2>
    <p>Fadein transition to all slides.</p>
    <pre>&lt;article id="webslides"&gt;
&lt;section&gt;
&lt;div class="wrap fadeInUp"&gt;
&lt;h1&gt;Slide&lt;/h1&gt;
&lt;/div&gt;
&lt;/section&gt;
&lt;/article&gt;</pre>
    <p>Just 3 basic animations: .fadeIn, .fadeInUp, and .zoomIn.</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap aligncenter fadeInUp">
    <h2>Slide</h2>
    <p>.fadeInUp</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-40 zoomIn aligncenter">
    <figure>
      <img src="../static/images/android.png" alt="Pixel Phone">
    </figure>
    <p>.zoomIn</p>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-50">
    <h3>.slow (animation duration)</h3>
    <pre>&lt;section&gt;
&lt;div class="wrap"&gt;
&lt;h2 class="fadeIn slow"&gt;Slide 1&lt;/h2&gt;
&lt;/div&gt;
&lt;/section&gt;</pre>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap aligncenter">
    <h2 class="fadeIn slow">h2.fadeIn.slow</h2>
  </div>
  <!-- .end .wrap -->
</section>

<section>
  <div class="wrap size-60">
    <h3>WebSlides is clean, consistent, and <strong>extensible</strong>.</h3>
    <p>If you want to add more animations, videos...</p>
    <ul class="flexblock border blink">
      <li>
        <a href="https://github.com/daneden/animate.css/" title="Animate.css">
          <h2>Animate.css</h2>
          Highly recommended. It is so easy and cool.
        </a>
      </li>
      <li>
        <a href="https://github.com/VincentGarreau/particles.js" title="particles.js">
          <h2>particles.js</h2>
          A lightweight .js library for creating particles.
        </a>
      </li>
      <li>
        <a href="https://pixabay.com/en/videos" title="Pixabay">
          <h2>Pixabay</h2>
          Beautiful background videos. 100% license free.
        </a>
      </li>
    </ul>
  </div>
  <!-- .end .wrap -->
</section>

<section class="aligncenter">
  <!-- .wrap = container 1200px -->
  <div class="wrap">
    <h2><strong>Start in Seconds</strong> </h2>
    <p class="text-intro">Create your own presentation instantly. <br>120+ prebuilt slides ready to use.</p>
    <p>
      <a href="https://webslides.tv/webslides-latest.zip" class="button" title="Download WebSlides">
        <svg class="fa-cloud-download">
          <use xlink:href="#fa-cloud-download"></use>
        </svg>
        Free Download
      </a>
      <span class="try">
        <a href="https://www.paypal.me/jlantunez/8" title="Good karma :)">
          <svg class="fa-paypal">
            <use xlink:href="#fa-paypal"></use>
          </svg>
          Pay what you want.
        </a>
      </span>
    </p>
  </div>
  <!-- .end .wrap -->
</section>
```
