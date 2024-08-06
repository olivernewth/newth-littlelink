
  <!-- Page Information
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta charset="utf-8">
  <title>Oliver Grosvenor-Newth</title>
  <meta name="description" content="https://littlelink.io">
  <meta name="author" content="Seth Cottle">

  <!-- Mobile Specific Metas
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta name="viewport" content="width=device-width, initial-scale=1">


  <!-- CSS
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="stylesheet" href="css/normalize.css">

    <!-- Themes:
            Auto:   css/skeleton-auto.css
            Light:  css/skeleton-light.css
            Dark:   css/skeleton-dark.css
     -->
    <link rel="stylesheet" href="css/skeleton-auto.css">

    <!-- Brand Styles -->
    <link rel="stylesheet" href="css/brands.css">


  <!-- Favicon
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="icon" type="image/png" href="images/littlelink.png">

</head>

<body>

  <!-- Primary Page Layout
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <div class="container">
    <div class="row">
      <div class="column" style="margin-top: 10%">

        <!-- 

          ## Getting Started with LittleLink

          This page has been built with every pre-designed button available in LittleLink by default. You can rearrange and delete as needed.

          You can add your own brand or others brands you may need in the `css/brands.css` file. 

          You can add custom icons to `images/icons/...`. It is recommended to use a 24x24 .SVG.

          Edit the "Your Image Here" section to add your own personal branding, like a picture of yourself or your brand logo!

          Edit the "Title" section to change the page heading. You can use something like your name, your social handle, or your brand name.

          Edit the "Short Bio" section tell users about yourself or your brand.

        -->

        <!-- Your Image Here -->
        <img src="images/littlelink.svg" class="avatar" srcset="images/littlelink.svg 2x" alt="">

        <!-- Title -->
        <h1 role="heading">Oliver Grosvenor-Newth</h1>

        <!-- Short Bio -->
        <p>An open source DIY Linktree alternative.</p>

        <!--

          ## Breaking down <a> attributes:
          
          1.) class="button button-default" | The first "button" here is telling this <a> tag that it should make this element a button and applies the default styling in `css/brands.css`.
          The second portion, button-default, is declaring the specific brand style you would like to apply. Here we're applying the "default" style and color.
          If you want to make this button to use the brand colors for Discord, just change "button-default" to "button-discord". Brands are found in `css/brands.css`. You can always edit & add your own there.

          2.) Replace the # in href="#" with the desired target URL for the button.

          3.) target="_blank" | This attribute opens links in a new tab. Remove this attribute to prevent links from opening in a new tab.

          4.) rel="noopener" | This attribute instructs the browser to navigate to the target resource without granting the new browsing context access to the document that opened it.
          This is especially useful when opening untrusted links. https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types/noopener

          5.) role="button" | The button role identifies an element as a button to assistive technology such as screen readers.

          ## Breaking down the <img> attributes:
          
          1.) class="icon" | This class is telling the <img> tag that it should use the styling for icons found in `css/brands.css`.

          2.) src="images/icons/[icon-name].svg" | This defines the icon you would like to display from the 'images/icons/' folder. For example, you can change this to src="images/icons/discord.svg" to use the Discord icon.
          Add your own 24x24 icons to the "icons" folder to reference them. We recommend providing a SVG.

          3.) alt="" | Since the text at the end of the snippet, "..>[Button Text]</a><br>", explains what the button is, we use "alt=""" to nullify the icon annoucement from the accessibility tree. 
          This can improve the experience for assistive technology users by hiding what is essentially duplicated

        -->

        <!-- Default LittleLink -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/littlelink.svg" alt="Little Link Logo">Website</a><br>

        <!-- Amazon -->
        <a class="button button-amazon" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/amazon.svg" alt="Amazon Wishlist Logo">Amazon Wishlist</a><br>

        <!-- Amazon Music -->
        <a class="button button-amazon-music" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/amazon-music.svg" alt="Amazon Music Logo">Listen on Amazon Music</a><br>       
        
        <!-- Apple App Store -->
        <a class="button button-appstore" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/apple.svg" alt="Apple Logo">Apple App Store</a><br>

        <!-- Apple Music -->
        <a class="button button-apple-music" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/apple-music.svg" alt="Apple Music Logo">Listen on Apple Music</a><br>            
       
        <!-- Apple Music Alternate -->
        <a class="button button-apple-music-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/apple-music-alt.svg" alt="Apple Music Logo">Listen on Apple Music</a><br> 

        <!-- Apple Podcasts -->
        <a class="button button-apple-podcasts" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/apple-podcasts.svg" alt="Apple Podcasts Logo">Listen on Apple Podcasts</a><br> 
        
        <!-- Apple Podcasts Alternate -->
        <a class="button button-apple-podcasts-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/apple-podcasts-alt.svg" alt="Apple Podcasts Logo">Listen on Apple Podcasts</a><br> 

        <!-- Bandcamp -->
        <a class="button button-bandcamp" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/bandcamp.svg" alt="Bandcamp Logo">Bandcamp</a><br> 

        <!-- Behance -->
        <a class="button button-behance" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/behance.svg" alt="Behance Logo">Behance</a><br> 
  
        <!-- Bluesky -->
        <a class="button button-bluesky" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/bluesky.svg" alt="Bluesky Logo">Bluesky</a><br> 

        <!-- Bluesky Alt -->
        <a class="button button-bluesky-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/bluesky-alt.svg" alt="Bluesky Logo">Bluesky</a><br> 

        <!-- Buy Me A Coffee -->
        <a class="button button-coffee" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/buy-me-a-coffee.svg" alt="Buy Me A Coffee Logo">Buy Me A Coffee</a><br>

        <!-- Calendly -->
        <a class="button button-calendly" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/calendly.svg" alt="Calendly Logo">Schedule with Calendly</a><br>

        <!-- Cash App -->
        <a class="button button-cash-app" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/cash-app-dollar.svg" alt="Cash App Logo">Cash App</a><br>

        <!-- Dev.to -->
        <a class="button button-dev-to" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/dev-to.svg" alt="Dev.to Logo">Dev.to</a><br>

        <!-- Discogs -->
        <a class="button button-discogs" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/discogs.svg" alt="Discogs Logo">Discogs</a><br>

        <!-- Discogs Alt -->
        <a class="button button-discogs-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/discogs-alt.svg" alt="Discogs Logo">Discogs</a><br>

        <!-- Discord -->
        <a class="button button-discord" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/discord.svg" alt="Discord Logo">Discord</a><br>

        <!-- Dribbble -->
        <a class="button button-dribbble" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/dribbble.svg" alt="Dribbble Logo">Dribbble</a><br>

        <!-- Etsy -->
        <a class="button button-etsy" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/etsy.svg" alt="Etsy Logo">Shop on Etsy</a><br>

        <!-- Facebook -->
        <a class="button button-faceb" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/facebook.svg" alt="Facebook Logo">Find us on Facebook</a><br>

        <!-- Facebook Messenger -->
        <a class="button button-messenger" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/messenger.svg" alt="Messenger Logo">Chat on Messenger</a><br>

        <!-- Figma -->
        <a class="button button-figma" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/figma.svg" alt="Figma Logo">Figma Community</a><br>

        <!-- Fiverr -->
        <a class="button button-fiverr" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/fiverr.svg" alt="Fiverr Logo">Fiverr Gig</a><br>

        <!-- Flickr -->
        <a class="button button-flickr" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/flickr.svg" alt="Flickr Logo">Flickr</a><br>

        <!-- GitHub -->
        <a class="button button-github" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/github.svg" alt="GitHub Logo">GitHub</a><br>

        <!-- GitLab -->
        <a class="button button-gitlab" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/gitlab.svg" alt="GitLab Logo">GitLab</a><br>

        <!-- GoFundMe -->
        <a class="button button-gofundme" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/gofundme.svg" alt="GoFundMe Logo">GoFundMe</a><br>

        <!-- Goodreads -->
        <a class="button button-goodreads" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/goodreads.svg" alt="Goodreads Logo">Goodreads</a><br>

        <!-- Google Drive -->
        <a class="button button-google-black" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/google-drive.svg" alt="Google Drive Logo">View in Google Drive</a><br>

        <!-- Google Play Store -->
        <a class="button button-playstore" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/google-play.svg" alt="Google Play Store Logo">Google Play Store</a><br>

        <!-- Google Scholar -->
        <a class="button button-google-scholar" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/google-scholar.svg" alt="Google Scholar Logo">Google Scholar</a><br>

        <!-- Hashnode -->
        <a class="button button-hashnode" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/hashnode.svg" alt="Hashnode Logo">Hashnode</a><br>

        <!-- Instagram -->
        <a class="button button-instagram" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/instagram.svg" alt="Instagram Logo">Instagram</a><br>

        <!-- Kick -->
        <a class="button button-kick" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/kick.svg" alt="Kick Logo">Kick</a><br>

        <!-- Kick Alt -->
        <a class="button button-kick-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/kick-alt.svg" alt="Kick Logo">Kick</a><br>
        
        <!-- Kickstarter -->
        <a class="button button-kickstarter" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/kickstarter.svg" alt="Kickstarter Logo">Kickstarter</a><br>

        <!-- Kit -->
        <a class="button button-kit" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/kit.svg" alt="Kit Logo">Kit</a><br>

        <!-- Ko-fi -->
        <a class="button button-ko-fi" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/ko-fi.svg" alt="Ko-fi Logo">Ko-fi</a><br>

        <!-- Last.fm -->
        <a class="button button-last-fm" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/last-fm.svg" alt="">Last.fm</a><br>

        <!-- Letterboxd -->
        <a class="button button-letterboxd" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/letterboxd.svg" alt="">Letterboxd</a><br>

        <!-- Line -->
        <a class="button button-line" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/line.svg" alt="Line Logo">Line</a><br>

        <!-- LinkedIn -->
        <a class="button button-linked" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/linkedin.svg" alt="LinkedIn Logo">LinkedIn</a><br>

        <!-- Mailchimp -->
        <a class="button button-mailchimp" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/mailchimp.svg" alt="Mailchimp Logo">Mailchimp</a><br>

        <!-- Mastodon -->
        <a class="button button-mastodon" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/mastodon.svg" alt="Mastodon Logo">Mastodon</a><br>

        <!-- Medium -->
        <a class="button button-medium" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/medium.svg" alt="Medium Logo">Medium</a><br>

        <!-- Microsoft Store -->
        <a class="button button-microsoft" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/microsoft.svg" alt="Microsoft Logo">Get it from Microsoft</a><br>
        
        <!-- NGL -->
        <a class="button button-ngl" href="#" target="_blank" rel="noopener"><img class="icon" aria-hidden="true" src="images/icons/ngl.svg" alt="NGL Logo">NGL</a><br>
        
        <!-- Notion -->
        <a class="button button-notion" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/notion.svg" alt="Notion Logo">Notion</a><br>

        <!-- OnlyFans -->
        <a class="button button-onlyfans" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/onlyfans.svg" alt="OnlyFans Logo">OnlyFans (18+)</a><br>

        <!-- Patreon -->
        <a class="button button-patreon" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/patreon.svg" alt="Patreon Logo">Patreon</a><br>

        <!-- PayPal -->
        <a class="button button-paypal" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/paypal.svg" alt="PayPal Logo">PayPal</a><br>

        <!-- Pinterest -->
        <a class="button button-pinterest" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/pinterest.svg" alt="Pinterest Logo">Pinterest</a><br>

        <!-- Product Hunt -->
        <a class="button button-product-hunt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/product-hunt.svg" alt="Product Hunt Logo">Product Hunt</a><br>

        <!-- Read.cv -->
        <a class="button button-read-cv" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/read-cv.svg" alt="Read.cv logo">Read.cv</a><br>

        <!-- Redbubble -->
        <a class="button button-redbubble" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/redbubble.svg" alt="Redbubble Logo">Redbubble</a><br>

        <!-- Reddit -->
        <a class="button button-reddit" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/reddit.svg" alt="Reddit Logo">Reddit</a><br>

        <!-- Revolut -->
        <a class="button button-revolut" href="" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/revolut.svg" alt="Revolut Logo">Revolut</a><br>
        
        <!-- Shop -->
        <a class="button button-shop" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/shop.svg" alt="Shop Logo">Buy with Shop</a><br>

        <!-- Signal -->
        <a class="button button-signal" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/signal.svg" alt="Signal Logo">Signal</a><br>

        <!-- Slack -->
        <a class="button button-slack" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/slack.svg" alt="Slack Logo">Join Slack</a><br>

        <!-- Snapchat -->
        <a class="button button-snapchat" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/snapchat.svg" alt="Snapchat Logo">Snapchat</a><br>

        <!-- SoundCloud -->
        <a class="button button-soundcloud" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/soundcloud.svg" alt="SoundCloud Logo">SoundCloud</a><br>

        <!-- Spotify -->
        <a class="button button-spotify" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/spotify.svg" alt="Spotify Logo">Listen on Spotify</a><br>

        <!-- Spotify Alt -->
        <a class="button button-spotify-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/spotify-alt.svg" alt="Spotify Logo">Listen on Spotify</a><br>

        <!-- Square -->
        <a class="button button-square" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/square.svg" alt="Square Logo">Buy with Square</a><br>

        <!-- Stack Overflow -->
        <a class="button button-stack-overflow" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/stack-overflow.svg" alt="Stack Overflow Logo">Stack Overflow</a><br>

        <!-- Steam -->
        <a class="button button-steam" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/steam.svg" alt="Steam Logo">Steam</a><br>

        <!-- Steam Alt -->
        <a class="button button-steam-alt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/steam.svg" alt="Steam Logo">Steam</a><br>

        <!-- Strava -->
        <a class="button button-strava" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/strava.svg" alt="Strava Logo">Strava</a><br>

        <!-- Substack -->
        <a class="button button-substack" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/substack.svg" alt="Substack Logo">Substack</a><br>

        <!-- Telegram -->
        <a class="button button-telegram" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/telegram.svg" alt="Telegram Logo">Telegram</a><br>

        <!-- Threads -->
        <a class="button button-threads" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/threads.svg" alt="Threads Logo">Threads</a><br>

        <!-- Threema -->
        <a class="button button-threema" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/threema.svg" alt="Threema Logo">Threema</a><br>

        <!-- TikTok -->
        <a class="button button-tiktok" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/tiktok.svg" alt="TikTok Logo">TikTok</a><br>

        <!-- Trakt -->
        <a class="button button-trakt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/trakt.svg" alt="Trakt Logo">Trakt</a><br>

        <!-- Trello -->
        <a class="button button-trello" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/trello.svg" alt="Trello Logo">Trello</a><br>

        <!-- Tumblr -->
        <a class="button button-tumb" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/tumblr.svg" alt="Tumblr Logo">Tumblr</a><br>

        <!-- Twitch -->
        <a class="button button-twitch" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/twitch.svg" alt="Twitch Logo">Twitch</a><br>

        <!-- Unsplash -->
        <a class="button button-unsplash" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/unsplash.svg" alt="Unsplash Logo">Unsplash</a><br>

        <!-- Untappd -->
        <a class="button button-untappd" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/untappd.svg" alt="Untappd Logo">Untappd</a><br>

        <!-- Upwork -->
        <a class="button button-upwork" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/upwork.svg" alt="Upwork Logo">Upwork</a><br>

        <!-- Venmo -->
        <a class="button button-venmo" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/venmo.svg" alt="Venmo Logo">Venmo</a><br>

        <!-- Vimeo -->
        <a class="button button-vimeo" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/vimeo.svg" alt="Vimeo Logo">Vimeo</a><br>

        <!-- VSCO -->
        <a class="button button-vsco" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/vsco.svg" alt="VSCO Logo">VSCO</a><br>

        <!-- WhatsApp -->
        <a class="button button-whatsapp" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/whatsapp.svg" alt="WhatsApp Logo">WhatsApp</a><br>

        <!-- WordPress -->
        <a class="button button-wordpress" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/wordpress.svg" alt="WordPress Logo">WordPress</a><br>

        <!-- X -->
        <a class="button button-x" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/x.svg" alt="X Logo">Follow on X</a><br>

        <!-- YouTube -->
        <a class="button button-yt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/youtube.svg" alt="YouTube Logo">YouTube</a><br>        

        <!-- YouTube Music -->
        <a class="button button-yt" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/youtube-music.svg" alt="YouTube Music Logo">Listen on YouTube Music</a><br>

        <!-- Zoom -->
        <a class="button button-zoom" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/zoom.svg" alt="Zoom Logo">Join Zoom Webinar</a><br>  

        <!-- Generic Blog -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-blog.svg" alt="Blog Icon">Read our blog</a><br>

        <!-- Generic Calendar -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-calendar.svg" alt="Calendar Icon">Event RSVP</a><br>

        <!-- Generic Cloud -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-cloud.svg" alt="Cloud Icon">Download File</a><br>

        <!-- Generic Code -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-code.svg" alt="Code Icon">View the code</a><br>

        <!-- Generic Computer -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-computer.svg" alt="Computer Icon">Homelab Setup</a><br>

        <!-- Generic Email -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-email.svg" alt="Email Icon">Email Us</a><br>

        <!-- Generic Email Alt -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-email-alt.svg" alt="Email Icon">Email Us</a><br>

        <!-- Generic Homepage -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-homepage.svg" alt="Homepage Icon">Visit Homepage</a><br>

        <!-- Generic Map -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-map.svg" alt="Map Icon">Get Directions</a><br>

        <!-- Generic Phone -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-phone.svg" alt="Phone Icon">Call Us</a><br>

        <!-- Generic Review -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-review.svg" alt="Review Icon">Leave us a review</a><br>

        <!-- Generic RSS -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-rss.svg" alt="RSS Icon">RSS Subscribe</a><br>

        <!-- Generic Shopping Bag -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-shopping-bag.svg" alt="Shopping Bag Icon">Visit Our Shop</a><br>
                
        <!-- Generic Shopping Tag -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-shopping-tag.svg" alt="Shopping Tag Icon">10% Discount</a><br>

        <!-- Generic SMS -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-sms.svg" alt="SMS Icon">Send us a message</a><br>

        <!-- Generic Website -->
        <a class="button button-default" href="#" target="_blank" rel="noopener" role="button"><img class="icon" aria-hidden="true" src="images/icons/generic-website.svg" alt="Website Icon">Visit Website</a><br>
        <br>
        <!-- 
            Footer:
            This includes a link to privacy.html page which can be setup for your Privacy Policy.
            This also includes a link to the LittleLink repository to make forking LittleLink easier.
            You can edit or remove anything here to make your own footer.
        -->
        <p><a href="privacy.html">Privacy Policy</a> | Build your own by forking <a href="https://littlelink.io" target="_blank" rel="noopener" role="button">LittleLink</a>.</p>

      </div>
    </div>
  </div>

  <!-- End Document
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
</body>

</html>
