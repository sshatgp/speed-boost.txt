# speed-boost.txt
⚡ سكربت تسريع التصفح - Al-Sharaabi Boost  `txt ! ⚡ Performance Boost Script – Created by Al-Sharaabi
! ⚡ Performance Boost Script – Created by Al-Sharaabi

! ✅ Disable heavy fonts & tracking
||fonts.googleapis.com^$stylesheet,domain=*
||fonts.gstatic.com^$font,domain=*
||*.googletagmanager.com^$script
||*.google-analytics.com^$script
||*.doubleclick.net^$script
||*.facebook.net^$script
||*.twitter.com^$script
||*.tiktok.com^$script
||*.snapchat.com^$script
||*.cdn-cgi.com^$script

! 🚫 Block lazy-loaded ads and unnecessary scripts
||*.ads.js^$script
||*.analytics.js^$script
||*.tracking.js^$script
||*.clicktrack.*^$script
||*.admanager.*^$script
||*.tag.js^$script
||*.livechat.*^$script
||*.popup.*^$script
||*.interstitial.*^$script

! 🛑 Stop image-based ad requests
||ad*banner*.*$image
||promo*.*$image
||sponsor*.*$image
||adv/*$image
||advertising/*$image

! 💨 Block fake preloading and unused CDN resources
||*.cdn.*.com^$script
||*.preload.*.com^$script
||*.trackingcdn.*^$script

! 🧠 Block behavioral scripts
||*.heatmap.*^$script
||*.sessionrecord.*^$script
||*.userbehavior.*^$script
||*.fingerprint.*^$script

! 🧹 Optional CSS cleanup (advanced performance tweak)
##div[class*="widget"]
##div[class*="sidebar"]
##div[id*="related-post"]
##section[class*="related"]
##footer[class*="social"]
