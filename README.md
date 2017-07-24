//META{"name":"Discord_Reborn","description":"A nice sleek transparent theme.","author":"Omniscient","version":"0.0"}*//

/* IMPORT CSS FROM GITHUB */
@import url("https://rawgit.com/0mniscient/Discord-Themes/master/css/Discord%20Reborn.css");
/*
===== IMPORTANT =====
CHANGE DISCORDS THEME TO DARK THEME IN APPEARANCE SETTINGS FOR THIS THEME TO WORK!
===== CUSTOMIZABLE COLORS =====
*/
:root { 
 --main-color: #057F95;
 --hover-color: #045B6B;
 }
 /*
===== CUSTOMIZABLE IMAGES =====
IMPORTANT: EVERY URL MUST BE HTTPS:// IN ORDER TO WORK IN DISCORD
RECOMMENDATIONS: EVERY URL AT THE BOTTOM SHOULD BE THE SAME TO MAKE THE THEME MATCH. (YOUR CHOICE)
--------------------------------------------------------------------------------------------------------------------------------------------
/*Change the url in .app to change the background behind chat */

.app { background-image: url("https://imgur.com/a/yLJHE") !important; background-size: cover !important; }

/*Change the url in .callout-backdrop to change the background when modal pop outs happen */

.callout-backdrop { background-color: black !important; background-image: url("https://imgur.com/a/yLJHE") !important; -webkit-transition: 0.3s all ease; -o-transition: 0.3s all ease; -moz-transition: 0.3s all ease; transition: 0.3s all ease; background-size: cover !important; -webkit-filter: brightness(75%); }

/*Change the urls below to change the background of a profile modal pop up */

.user-popout:before {
    background-image: url("https://imgur.com/a/yLJHE") !important;
    content: "";position: absolute;left: 0;top: 0;height: 100%;width: 100%;z-index: -1;background-position: 50% 50%;-webkit-filter: blur(3px);-webkit-transform: scale(1.05);transform: scale(1.05);}

#user-profile-modal .header:before {
    background: -webkit-linear-gradient(top, rgba(0, 0, 0, .3), rgba(0, 0, 0, 0.5)), url("https://imgur.com/RG03PyX.png") !important;
    background: linear-gradient(to bottom, rgba(0, 0, 0, .3), rgba(0, 0, 0, 0.5)), url("https://imgur.com/RG03PyX.png") !important;
    content: "";position: absolute;left: 0;top: 0;width: 100%;height: 100%;z-index: -1;background-position: 50% 50%;background-size: cover !important;-webkit-filter: blur(3px);-webkit-transform: scale(1.1);transform: scale(1.1);}

 /*
