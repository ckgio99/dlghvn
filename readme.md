<html lang="vi" dir="ltr">
   <script id="allow-copy_script">(function agent() {
      let unlock = false
      document.addEventListener('allow_copy', (event) => {
        unlock = event.detail.unlock
      })
      
      const copyEvents = [
        'copy',
        'cut',
        'contextmenu',
        'selectstart',
        'mousedown',
        'mouseup',
        'mousemove',
        'keydown',
        'keypress',
        'keyup',
      ]
      const rejectOtherHandlers = (e) => {
        if (unlock) {
          e.stopPropagation()
          if (e.stopImmediatePropagation) e.stopImmediatePropagation()
        }
      }
      copyEvents.forEach((evt) => {
        document.documentElement.addEventListener(evt, rejectOtherHandlers, {
          capture: true,
        })
      })
      })()
   </script>
   <head>
      <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <title>Đây Là Giang Hồ Wiki</title>
      <script defer="" src="https://ckgio99.github.io/dlghvn/static_files/fuse.min.32195737929df2c8096e855a5789cbb3f1331224d9169e8705493e7008f47df8.js"></script>
      <script src="https://ckgio99.github.io/dlghvn/static_files/enquire.min.dfb99dee1e029d51d6cfb672d847929890b1585402de17f5ed092edd72a688b4.js"></script>
      <script defer="" src="https://ckgio99.github.io/dlghvn/static_files/lazysizes.min.fb649fcae62177dfe63e67081ddceb830b5ce1f05a4184e9bbb7d87ac4b8f4e5.js"></script>
      <script defer="" src="https://ckgio99.github.io/dlghvn/static_files/getParents.min.1618c696be7c98933f9a92677f518b512a74e55bdbb976b09936b4182e93181b.js"></script>
      <script defer="" src="https://ckgio99.github.io/dlghvn/static_files/fadeinout.min.efa35f4c090622130b3f4cfae6971448b5ffb61c5f0a8f21cdfd157fa712abc4.js"></script>
      <script defer="" src="https://ckgio99.github.io/dlghvn/static_files/closest.min.js"></script>
      <link rel="stylesheet" href="https://ckgio99.github.io/dlghvn/static_files/main.min.css">
      <meta name="theme-color" content="#403E41">
      <meta name="msapplication-navbutton-color" content="#403E41">
      <meta name="apple-mobile-web-app-status-bar-style" content="#403E41">
   </head>
   <body id="root" class="theme__dark">
      <script>
         var localTheme = localStorage.getItem('theme');
         if (localTheme) {
             document.getElementById('root').className = 'theme__' + localTheme;
         }
      </script>
      <div id="container">
      <div class="wrapper" data-type="page" data-kind="home">
      <nav class="navbar scrolling" role="navigation" aria-label="main navigation" data-dir="ltr">
         <div class="navbar__brand">
            <a href="https://ckgio99.github.io/dlghvn/" title="Home" rel="home" class="navbar__logo-link">
            <img src="https://ckgio99.github.io/dlghvn/static_files/logo.png" alt="Home" class="navbar__logo">
            </a>
            <a href="https://ckgio99.github.io/dlghvn/" title="Home" rel="home" class="navbar__title-link">
               <h6 class="navbar__title">Zzo</h6>
            </a>
         </div>
         <div class="mobile-search__btn navbar-search" data-ani="true">
            <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" fill="currentColor" viewBox="0 0 24 24">
               <path fill="none" d="M0 0h24v24H0V0z"></path>
               <path d="M15.5 14h-.79l-.28-.27c1.2-1.4 1.82-3.31 1.48-5.34-.47-2.78-2.79-5-5.59-5.34-4.23-.52-7.79 3.04-7.27 7.27.34 2.8 2.56 5.12 5.34 5.59 2.03.34 3.94-.28 5.34-1.48l.27.28v.79l4.25 4.25c.41.41 1.08.41 1.49 0 .41-.41.41-1.08 0-1.49L15.5 14zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
            </svg>
         </div>
         <div id="search-mobile-container" class="mobile-search hide" data-dir="ltr" style="display: none;">
            <div class="mobile-search__top">
               <input id="search-mobile" type="text" aria-label="Mobile Search" placeholder="Search" class="mobile-search__top--input">
               <div id="search-mobile-close" class="mobile-search__top--icon">
                  <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24">
                     <path opacity=".87" fill="none" d="M0 0h24v24H0V0z"></path>
                     <path fill="currentColor" d="M12 2C6.47 2 2 6.47 2 12s4.47 10 10 10 10-4.47 10-10S17.53 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm3.59-13L12 10.59 8.41 7 7 8.41 10.59 12 7 15.59 8.41 17 12 13.41 15.59 17 17 15.59 13.41 12 17 8.41z"></path>
                  </svg>
               </div>
            </div>
            <div id="search-mobile-results" class="mobile-search__body">
            </div>
         </div>
         <a role="button" class="navbar__burger" aria-label="menu" aria-expanded="false" data-ani="true">
         <span aria-hidden="true"></span>
         <span aria-hidden="true"></span>
         <span aria-hidden="true"></span>
         </a>
         <div class="navbarm__collapse" data-open="false">
            <ul dir="ltr">
               <li class="navbarm__menu--item ">
                  <a href="https://ckgio99.github.io/dlghvn/presentation">Pt</a>
               </li>
               <li class="navbarm__menu--item ">
                  <a href="https://ckgio99.github.io/dlghvn/gallery">
                     Gallery
                     <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24">
                        <path fill="currentColor" d="M8.12 9.29L12 13.17l3.88-3.88c.39-.39 1.02-.39 1.41 0 .39.39.39 1.02 0 1.41l-4.59 4.59c-.39.39-1.02.39-1.41 0L6.7 10.7c-.39-.39-.39-1.02 0-1.41.39-.38 1.03-.39 1.42 0z"></path>
                     </svg>
                  </a>
               </li>
               <li class="navbarm__menu--item navbarm__menu--subitem">
                  <a href="https://ckgio99.github.io/dlghvn/gallery/cartoon">Cartoon</a>
               </li>
               <li class="navbarm__menu--item navbarm__menu--subitem">
                  <a href="https://ckgio99.github.io/dlghvn/gallery/photo">Photo</a>
               </li>
            </ul>
         </div>
         <div class="navbar__menu">
            <a href="https://ckgio99.github.io/dlghvn/presentation" class="navbar__menu-item navbar__slide-down " dir="ltr" data-ani="true">Pt</a>
            <div class="navbar__dropdown navbar__slide-down" data-ani="true">
               <a href="https://ckgio99.github.io/dlghvn/gallery" class="navbar__menu-item " dir="ltr">
                  Gallery
                  <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24">
                     <path fill="currentColor" d="M8.12 9.29L12 13.17l3.88-3.88c.39-.39 1.02-.39 1.41 0 .39.39.39 1.02 0 1.41l-4.59 4.59c-.39.39-1.02.39-1.41 0L6.7 10.7c-.39-.39-.39-1.02 0-1.41.39-.38 1.03-.39 1.42 0z"></path>
                  </svg>
               </a>
               <div class="navbar__dropdown--content">
                  <a href="https://ckgio99.github.io/dlghvn/gallery/cartoon" class="navbar__dropdown--item" dir="ltr">Cartoon</a>
                  <a href="https://ckgio99.github.io/dlghvn/gallery/photo" class="navbar__dropdown--item" dir="ltr">Photo</a>
               </div>
            </div>
         </div>
      </nav>
      <header class="header ">
         <div class="site-header basicflex-column site-header__align-center" data-ani="true" style="width: 100%; height: 200px; padding: 0px 50px;">
            <div class="site-header__title site-header__title--shadow" style="font-size: 44px; ;">
               Đây Là Giang Hồ
            </div>
            <div style="height: 16px"></div>
            <div class="site-header__subtitle" style="font-size: 18px; " data-cursive="true">
               Game Chơi Cho Vui
            </div>
         </div>
      </header>
      <main class="main inner" data-sidebar-position="right">
         <div class="list__main lm">
            <div class="summary__container" data-display="block">
               <article class="summary-classic" data-ani="true">
                  <div class="summary-classic__flex-box">
                     <div class="summary-classic__image-container summary-classic__image-wrapper" data-position="right" data-hwm="">
                        <a href="https://ckgio99.github.io/dlghvn/tang-bao-cac.html">
                        <img src="https://ckgio99.github.io/dlghvn/img/tang-bao-cac.png" class="summary-classic__image lazyloaded" data-ani="true" data-hwm="" style="">
                        </a>
                     </div>
                     <div class="summary-classic__content">
                        <header>
                           <h5 class="title h5"><a href="https://ckgio99.github.io/dlghvn/tang-bao-cac.html">Tàng Bảo Các</a> </h5>
                        </header>
                        <div>
                           <div class="summary-classic__text p2">
                              Tổng hợp các món đồ có trong Tàng Bảo Các của tất cả các môn phái.
                           </div>
                        </div>
                     </div>
                  </div>
                  <hr>
               </article>
            </div>
            <div class="search-result" data-display="none">
               <div class="search-result__header">
                  <div class="search-result__close" data-dir="ltr">
                     <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24">
                        <path opacity=".87" fill="none" d="M0 0h24v24H0V0z"></path>
                        <path fill="currentColor" d="M12 2C6.47 2 2 6.47 2 12s4.47 10 10 10 10-4.47 10-10S17.53 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm3.59-13L12 10.59 8.41 7 7 8.41 10.59 12 7 15.59 8.41 17 12 13.41 15.59 17 17 15.59 13.41 12 17 8.41z"></path>
                     </svg>
                  </div>
               </div>
               <div class="search-result__body">
                  <ul>
                     <li class="search-result__item">
                        <div class="search-result__item--title">
                        </div>
                        <div class="search-result__item--desc">
                        </div>
                     </li>
                  </ul>
               </div>
            </div>
         </div>
         <aside class="list__sidebar r" data-dir="ltr">
            <div class="sidebar">
               <div class="search">
                  <span class="icon">
                     <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" fill="currentColor" viewBox="0 0 24 24">
                        <path fill="none" d="M0 0h24v24H0V0z"></path>
                        <path d="M15.5 14h-.79l-.28-.27c1.2-1.4 1.82-3.31 1.48-5.34-.47-2.78-2.79-5-5.59-5.34-4.23-.52-7.79 3.04-7.27 7.27.34 2.8 2.56 5.12 5.34 5.59 2.03.34 3.94-.28 5.34-1.48l.27.28v.79l4.25 4.25c.41.41 1.08.41 1.49 0 .41-.41.41-1.08 0-1.49L15.5 14zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
                     </svg>
                  </span>
                  <input id="search" aria-label="Site Search" class="input" type="text" placeholder="Search" autocomplete="off">
                  <div id="search-results" class="dropdown">
                     <div id="search-menu" class="dropdown-menu" role="menu">
                     </div>
                  </div>
               </div>
               <section class="bio" data-dir="ltr">
                  <hr class="hr-slash bio-hr">
                  <div class="bio__photo-wrapper">
                     <img data-src="https://ckgio99.github.io/dlghvn/img/ava.jpg" src="https://ckgio99.github.io/dlghvn/img/ava.jpg" class="bio__photo lazyloaded" data-ani="true">
                  </div>
                  <hr class="hr-slash bio-hr">
                  <div class="bio__name">
                     Chuôn Không Gió
                  </div>
                  <div class="bio__desc">
                     Gà Mờ
                  </div>
               </section>
               <hr class="hr-fade sidebar-hr">
         </aside>
      
      <script>
         var sidebarPosition = JSON.parse("\"right\"");
         
         var enableSidebar = JSON.parse("true");
         
         var listMainElem = document.querySelector('.list__main');
         var listSideElem = document.querySelector('.list__sidebar');
         
         var gridSmall = 'l';
         var gridBig = 'mr';
         var gridFull = 'lmr'
         
         if (sidebarPosition === "right") {
             gridSmall = 'r';
             gridBig = 'lm'
         }
         
         enquire.register("screen and (max-width: 769px)", {
             match: function () {
                 if (enableSidebar) {
                     listMainElem.classList.remove(gridBig);
                     listMainElem.classList.add(gridFull);
                     listSideElem.classList.remove(gridSmall);
                     listSideElem.classList.add('hide');
                 } else {
                     if (listMainElem && !listMainElem.classList.contains(gridFull)) {
                         listMainElem.classList.remove(gridBig);
                         listMainElem.classList.add(gridFull);
                     }
         
                     if (listSideElem && !listSideElem.classList.contains('hide')) {
                         listSideElem.classList.add('hide');
                     }
                 }
         
             },
             unmatch: function () {
                 if (enableSidebar) {
                     listMainElem.classList.remove(gridFull);
                     listMainElem.classList.add(gridBig);
                     listSideElem.classList.add(gridSmall);
                     listSideElem.classList.remove('hide');
                 } else {
                     if (listMainElem && !listMainElem.classList.contains(gridFull)) {
                         listMainElem.classList.remove(gridBig);
                         listMainElem.classList.add(gridFull);
                     }
         
                     if (listSideElem && !listSideElem.classList.contains('hide')) {
                         listSideElem.classList.add('hide');
                     }
                 }
         
                 var navCollapseBtn = document.querySelector('.navbar__burger');
                 var navCollapse = document.getElementsByClassName('navbarm__collapse')[0];
                 if (navCollapse) {
                     navCollapse.setAttribute('data-open', false);
                     navCollapse.style.maxHeight = 0;
                     navCollapseBtn.classList.remove('is-active');
                 }
                 if (document.getElementsByClassName('navbar__menu')[0]) {
                     document.getElementsByClassName('navbar__menu')[0].classList.remove('is-active');
                 }
                 if (document.getElementsByClassName('mobile-search')[0]) {
                     document.getElementsByClassName('mobile-search')[0].classList.add('hide');
                 }
             },
             setup: function () { },
             deferSetup: true,
             destroy: function () { },
         });
      </script>
      <script>
         window.onload = function() {
           
           
           var enableBusuanzi = JSON.parse("false");
           if (enableBusuanzi) {
             var sitePvElem = document.querySelector('#busuanzi_value_site_pv');
             var siteUvElem = document.querySelector('#busuanzi_value_site_uv');
             sitePvElem.textContent = sitePvElem.textContent.replace(/(\d)(?=(\d\d\d)+(?!\d))/g, "$1,");
             siteUvElem.textContent = siteUvElem.textContent.replace(/(\d)(?=(\d\d\d)+(?!\d))/g, "$1,");
           }
         }
      </script>
      <footer class="footer">
      <div class="footer__social">
      <div class="footer__poweredby">
      <p class="caption">
      ©2021, All Rights Reserved
      </p>
      <p class="caption">Developed by Chuông Không Gió</p>
      </div> 
      </footer>
      </div>
      <div class="wrapper__right" data-pad="true" dir="ltr">
      <script>document.querySelector('.wrapper__right').classList.remove('hide')</script>
      </div>
      </div>
   </body>
</html>