# About reCaptcha v1

reCaptcha Google Service, development for the callback data or target.

## How to user API from Google

Just add 1 more script for callback a form reCaptcha. look display like a:
```
<script src="https://www.google.com/recaptcha/api.js" async defer></script>
```
```
<script src="https://cdn.rawgit.com/heirro/reCaptcha.js/441e8b5f/callback.js" ></script>
```

# Using code
```
<form id="notBot" method="" action=""></form>
```
```
<button class="g recaptcha" data-sitekey="YOUR SITEKEY" data-callback="signSecure">reCaptcha</button>
```
1. notBot in the Form as "id" calling function in the callback.js, and permanently function.
2. signSecure add the 'data-callback' was permanently in the callback.js, you can't edited. And customized attribut use button/input.

<b>note</b>:
```
callback.js a latest commit, that using CDN by RawGit.
```
Cordially, <br/>
Vava Heirro
