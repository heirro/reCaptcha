# About reCaptcha v1

reCaptcha Google Service, development for the callback data or target.

# Using API from Google the latest update

Just add 1 more script for callback a form reCaptcha. look display like a:

* <script src="https://www.google.com/recaptcha/api.js" async defer></script>
* <script src="https://cdn.rawgit.com/heirro/reCaptcha/3175119d/callback.js" ></script>

# Using code
* form id="notBot"
* class="g recaptcha" data-sitekey="YOUR SITEKEY" data-callback="signSecure"
  
1. signSecure add the 'data-callback' was permanently in the callback.js, you can't edited. And customized attribut use button/input.
2. notBot in the Form as "id" calling function in the callback.js, and permanently function.

<b>note</b>: callback.js a latest commit, that using CDN by RawGit.

Cordially, <br/>
Vava Heirro
