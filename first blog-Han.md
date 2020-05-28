Author: Han Xiao, Founder & CEO of Jina AI. 

<p>In Feb. 2020, I left Tencent AI and found my startup Jina AI. Jina AI is a neural search company that provides cloud-native neural search solutions powered by AI and deep learning. On April 28th 2020, we released our core product &#8220;<strong><em>Jina</em></strong>&#8221; in open source. You can use Jina for searching anything: image-to-image, video-to-video, tweet-to-tweet, audio-to-audio, code-to-code, etc. To understand our ambition at Jina AI, I often explain Jina with two analogies.</p>



<ul><li><strong><em>A &#8220;Tensorflow&#8221; for search</em></strong>. Tensorflow, Pytorch, MXNet, Mindspore, are universal frameworks for deep learning. You can use them for recognizing cats from dogs, or playing Go and DOTA. They are powerful and versatile but not optimized for a specific domain. In Jina, we are focusing on one domain only: the search. We are building on top of the universal deep learning framework and provide an infrastructure for any AI-powered search applications.</li></ul>



<ul><li><strong>A design pattern.</strong>&nbsp; There are design patterns for every era: from functional programming to object-oriented programming. The same goes for the search system. Thirty years ago, it all started with a simple textbox. Many design patterns have been proposed for implementing the search system behind this textbox, some of which are incredibly successful commercial-wise. In the era of neural search, a query can go beyond a few keywords: an image, a video, a code snippet, or an audio file. When traditional symbolic search systems can not effectively handle these data formats, people need a new design pattern for building neural search systems. That&#8217;s what Jina is: a new design pattern for this new era.</li></ul>



<figure class="wp-block-image"><img src="https://lh6.googleusercontent.com/KY_Fx9crkb2mmLlNJWJsMdD0DEe5eeuuknXdd6xN6o8Ymro87rqyIqu2-W39MgYNLojuwIMcB5vT3pdjpqWaoVhBSxHDnCPi6vhE6sFLzcAFRm5BigbE5G-rgusaTc4V7omnXkGL" alt="" /></figure>



<h3>Who set me on this path?</h3>



<p>I&#8217;ve been working in the field of AI, especially in open-source AI for some time. You may have heard or used my previous work on Fashion-MNIST and bert-as-service. From 2018 to early 2020, I was an Engineering Lead at Tencent AI Lab, where I led a team to build the search infrastructure of China&#8217;s everyday app: <em>WeChat</em>.</p>



<p>In 2019, I was representing Tencent as the board member of the LF AI Foundation. It is this year I learned how professional open-source initiative works. Besides reviewing the proposal of high-quality open source projects, I actively engaged in meetings of the Governing Board, Technical Advisory Council, Outreach Committee, and Trusted AI Committee, providing input to this global community. I co-organized multiple offline events including LF AI Day Shanghai, a Christmas gathering. I helped to foster an open tech culture and expand LF AI&#8217;s influence within the company. By the end of 2019, Tencent has a seat in each subcommittee, and is among the most engaged corporate members of the Foundation.</p>



<p>Two things I learned during my work at the LF AI Foundation:</p>



<ul><li>Open source = Open source code + Open governance. Community is the key.</li><li>Open source AI infrastructure is the future, and I need to act now.</li></ul>



<p>I&#8217;m sure many share the same vision as I do. But my belief is so strong that it drives me jumping out of the tech giant and doing Jina AI as a startup from scratch. Challenging as it is, this is the opportunity I can not miss, and this is the future I believe in. All of my team share this belief as strong as I do. At Jina AI, we only do what we believe. I always tell my team: people who actually make change are the ones who believe that change is possible.</p>



<h3>Challenges of an OSS company</h3>



<p>Running an open-source software (OSS) company needs courage, an open mindset, and a strong belief.&nbsp;</p>



<p>As an OSS company, when you first show the codebase to the world, you need courage. The code quality is now a symbol of the company. Are you following the best practice? Are you making a tech debt here and there? Open source is an excellent touchstone to help you understand and improve the quality of software engineering and development procedures.&nbsp;</p>



<p>Embracing the community is vital for an OSS company. It requires an open mindset. Doing open source is not the same as doing a press release or a spotlight speech: it is not a one-way communication. You need to walk into the community, talk to them, solve their issues, answer their questions, and accept their criticisms. You need to manage your ego and do trivial things such as maintenance, housekeeping.</p>



<p>Some people may think that big tech companies hold a better position when committing to open-source because they can leverage better resources. That is not true. No matter how big the company is, each has its comfort zone built over the years. For many tech companies, open-source is a new game: the value it brings is often not quantifiable through short-term KPI/OKR, and the rules of play are not familiar to everyone. Not every decision-maker in the company believes in it. It&#8217;s like a person who has been playing Go for years, with a high rank, and enjoys it. One day you just show up and tell this guy: hey, let&#8217;s play mahjong, mahjong is fun! And you are expecting this guy to say &#8220;<em>sure</em>&#8220;? Regardless of the company&#8217;s size, it is always important to make everyone inside the company believe the value of open source. After all, it is always the individual who gets things done.</p>



<h3>Best time for AI engineering</h3>



<figure class="wp-block-image"><img src="https://lh3.googleusercontent.com/mv1pTEq9C42gCIz93TFVGnbVyp0j51jtgfn_ZRsHSdStG7zYscR-RKUeMBPdWta6-qG2k-_TKMoiwl69B52nIqj9itVgCSQsu6FSzkStak39hGl5mmwdGNLJSgr5GJ5FxMsXvX95" alt="" /></figure>



<p>For engineers who want to do open source on AI, this is the best time. Thanks to the deep learning frameworks and off-the-shelf pre-trained models, there are many opportunities in the end-to-end application market for individuals to make significant contributions. Ask your colleagues or friends &#8220;which AI package do you use for daily tasks such as machine translation/image enhancement/data compression/code completion?&#8221;, you would get different answers from person to person. It is often an indicator that the market is still uncontested, and there is ample opportunity for growth and building a community around it.</p>



<p>One thing I like to remind the AI open-source developer is the <strong><em>sustainability</em></strong> of the project. With new AI algorithms popping up every day, how do you keep up the pace? What is the scope of your project? How do you maintain the project when facing community requests? When I was developing bert-as-service, I received many requests on extending it to AlBERT, DistilBERT, BioBERT etc. I prioritize those that fit into my roadmap. Sometimes this means hard-feeling to some people. But let&#8217;s be frank, you can&#8217;t solve every issue, not by yourself. It is not how open source works and certainly not how you work. The most considerable risk of open-source software is that the core developers behind are burned-out. The best open source may not be shiniest, but the one that lives the longest. So keep your enthusiasm and stay long!</p>



<h3>Doing open-source is doing a startup</h3>



<p>In the end, doing open source projects is like doing a startup, technical advantage is only part of the story.</p>



<p>Uploading the code to Github is just a starting point, and there are tasks such as operating, branding, and community management to consider. Like entrepreneurship, you need to draw a &#8220;pie&#8221; that encapsulates the passions and dreams of the community. You need to have the determination and precise target not to get sidetracked by the community issues.</p>



<p>As someone with a Machine Learning Ph.D., I&#8217;ve never believed that some black-magic algorithm would be the competitive advantage of an open-source project. Instead, I&#8217;m more convinced that sound engineering, attention to detail, slick user-experience, and community-driven governance model ultimately determine user retention.</p>



<p>The most important thing is often your understanding and belief in open source. If you are an idealist, then you will inspire those idealists to march with you. If you&#8217;re a detail-oriented person, every little feature in your project will be worshipped by those who care about the details. If you are a warm-hearted person, then the community you build up will appreciate your selfless giving.</p>



<p>Whichever person you are, it&#8217;s what you believe in open source makes what open source is.</p>

