<div><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/uikit/2.24.2/css/uikit.almost-flat.min.css"/><section><h1>Commentt List</h1><p>For lists of comments.</p></section><section><h2>Usage</h2><p><code>npm install react-uikit-comment-list --save;</code></p><p>ES6 <br/><code>import CommentList from &#x27;react-uikit-comment-list&#x27;;</code><br/></p><p>ES5 <br/><code>var CommentList = require(&#x27;react-uikit-comment-list&#x27;);</code></p><p>See <a href="http://otissv.github.io/react-uikit-components">React UIKit Componets</a> for examples and full documentation.</p><h></h><p>Use the <code>&lt;CommentList&gt;</code> component for lists of comments. You can nest any number of <code>&lt;CommentList&gt;</code> components inside a comment list.</p><h3>Example</h3><pre class="uk-scrollable-text"><code>&lt;CommentList&gt;
  &lt;li&gt;
    &lt;Commnet title=&#x27;Author&#x27; meta=&#x27;12 days ago | Profile | #&#x27;
      avatar={{src:&#x27;docs/images/placeholder_avatar.svg&#x27;, alt: &#x27;Avatar placeholder&#x27;}}&gt;

      &lt;p&gt;
        Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
        nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
        erat, sed diam voluptua.
      &lt;/p&gt;
    &lt;/Commnet&gt;
    &lt;CommentList&gt;
      &lt;li&gt;
        &lt;Commnet title=&#x27;Author&#x27; meta=&#x27;12 days ago | Profile | #&#x27;
          avatar={{src:&#x27;docs/images/placeholder_avatar.svg&#x27;, alt: &#x27;Avatar placeholder&#x27;}}&gt;

          &lt;p&gt;
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
            erat, sed diam voluptua.
          &lt;/p&gt;
        &lt;/Commnet&gt;
      &lt;/li&gt;
    &lt;/CommentList&gt;
  &lt;/li&gt;
&lt;/CommentList&gt;
</code></pre></section><section><h2>Commet list props</h2><p>See <a href="https://github.com/otissv/react-uikit-base">base</a> for additional props.</p></section><section><h2>Tests</h2><p><code>npm run test</code> to run tests with minimal output.<br/><code>npm run test:spec</code> to run tests with detailed output.<br/><code>npm run test:watch</code>watches all directories and run tests with minimal output on file changes.<br/></p></section><section><h2>Build</h2><p><code>npm run build</code> to build files fro distribution.<br/><code>npm run build:watch</code> watches src directory and builds files on changes.<br/></p></section><section><h2>Lint</h2><p><code>npm run lint</code> lints scripts in src directory.<br/><code>npm run lint:watch</code> watches src directory and lints scripts in src directory.<br/></p></section><section><h2>License</h2><p>MIT</p></section></div>