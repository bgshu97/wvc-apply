<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
<nav role="navigation" tabindex="0" aria-label="Navigation">
	<ul id="skip-links" class="list-unstyled">
		<li><a class="skip" href="#main-content" tabindex="0">Skip to Main Content</a></li>
		<li><a class="skip" href="#gateway-nav" tabindex="0">Skip to Utility Navigation</a></li>
		<li><a class="skip" href="#main-nav" tabindex="0">Skip to Main Navigation</a></li>
		<li><a class="skip" href="#footer-skip" tabindex="0">Skip to Footer</a></li>
	</ul>
</nav><div class="mobile-menu-only">
   <header id="menu-outer" role="banner" aria-label="banner" class="header-mobile mobile js-header-scrolling nav-down collapsed">
      <div class="logo-port"><a id="mobile-logo-link" href="/" tabindex="0"><img src="/src/assets/wvc-logo-white.svg" alt="West Valley College - Link To Homepage"></a></div>
      <div id="mobile-menu-buttons--container"><label for="searchtoggl" class="sr-only">Toggle Search Input</label><button id="searchtoggl" tabindex="0" aria-label="Toggle Search Input"><span class="fa fa-search fa-lg" aria-hidden="true"></span></button></div>
      <div id="searchbar" class="clearfix">
         <form id="searchform" method="get" aria-expanded="false" action="/search/results.html"><label for="s" class="sr-only">Search West Valley</label><input type="search" name="q" id="s" placeholder="Search West Valley" aria-label="Search West Valley" autocomplete="off" tabindex="0"><button type="submit" id="searchsubmit" class="fa fa-search fa-4x" aria-label="Submit Search Query" tabindex="0"></button></form>
      </div>
      <div id="js-append-menu-toggle" class="mobile-menu-toggle--container">
         <div id="sm_menu_ham"><label for="nav-icon3" class="sr-only">Toggle Menu</label><button id="nav-icon3" aria-label="Toggle Menu" tabindex="0" aria-expanded="false"><span aria-hidden="true"></span><span aria-hidden="true"></span><span aria-hidden="true"></span><span aria-hidden="true"></span><span class="mmlabel">MENU</span></button></div>
      </div>
      <nav id="mobile-menu-navigation" role="navigation" aria-label="Navigation">
         
      <div class="sm_menu_outer"><ul class="mobile_menu" role="menu"><!--mobile menu-->
            <li role="menuitem" class="hasChild"><a aria-haspopup="true" aria-expanded="false" tabindex="0" href="/admissions/">ADMISSIONS</a>
               
               <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                  <li><a aria-haspopup="false" aria-expanded="false" href="/admissions/">ADMISSIONS</a></li>
                  <li class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/admissions/apply-now.html">Apply Now</a>
                     
                     <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                        <li><a aria-haspopup="false" aria-expanded="false" href="/admissions/apply-now.html">Apply Now</a></li>
                        <li><a href="/admissions/apply.html">Steps to Apply</a></li>
                     </ul>
                  </li>
                  <li class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/admissions/assessment/">Assessment</a>
                     
                     <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                        <li><a aria-haspopup="false" aria-expanded="false" href="/admissions/assessment/">Assessment</a></li>
                        <li><a href="https://esars.wvm.edu/eSARS/WV-Assessment/eSARS.asp?WCI=Init&amp;WCE=Settings">Appointment Finder</a></li>
                        <li><a href="/admissions/assessment/challenge-form.html">Challenge Form</a></li>
                        <li><a href="/admissions/assessment/prerequisite_form.html">Prerequisite Form</a></li>
                     </ul>
                  </li>
                  <li><a href="/admissions/fee-schedule.html">Fees and Tuition</a></li>
                  <li class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/financial-aid/">Financial Aid</a>
                     
                     <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                        <li><a aria-haspopup="false" aria-expanded="false" href="/financial-aid/">Financial Aid</a></li>
                        <li><a href="/financial-aid/programs.html">Programs and Awards</a></li>
                        <li><a href="/financial-aid/scholarships.html">Scholarships</a></li>
                     </ul>
                  </li>
                  <li><a href="/admissions/orientation.html">Orientation</a></li>
                  <li><a href="/admissions/registration/">Registration</a></li>
                  <li><a href="/admissions/records/">Transcripts</a></li>
               </ul>
            </li>
            <li role="menuitem" class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/academics/">ACADEMICS</a>
               
               <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                  <li><a aria-haspopup="false" aria-expanded="false" href="/academics/">ACADEMICS</a></li>
                  <li><a href="/catalog/programs/">Academic Programs</a></li>
                  <li><a href="/services/careers/">Career Services</a></li>
                  <li class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/schools/">Schools</a>
                     
                     <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                        <li><a aria-haspopup="false" aria-expanded="false" href="/schools/">Schools</a></li>
                        <li><a href="/schools/art-design/">Art and Design</a></li>
                        <li><a href="/schools/health-human-development/">Health and Human Development</a></li>
                        <li><a href="/schools/language-arts/">Language Arts</a></li>
                        <li><a href="/schools/professional-studies/">Professional Studies</a></li>
                        <li><a href="/schools/science-math/">Science and Math</a></li>
                        <li><a href="/schools/social-science/">Social Sciences</a></li>
                     </ul>
                  </li>
               </ul>
            </li>
            <li role="menuitem" class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/contact/">Campus Information</a>
               
               <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                  <li><a aria-haspopup="false" aria-expanded="false" href="/contact/">Campus Information</a></li>
                  <li><a href="/faculty/">Directory</a></li>
                  <li><a href="/maps/">Maps</a></li>
                  <li><a href="/parking/">Parking</a></li>
               </ul>
            </li>
            <li role="menuitem" class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/services/">STUDENT SERVICES</a>
               
               <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                  <li><a aria-haspopup="false" aria-expanded="false" href="/services/">STUDENT SERVICES</a></li>
                  <li><a href="/services/bookstore/">Bookstore</a></li>
                  <li><a href="/services/careers/">Career Services</a></li>
                  <li><a href="/services/counseling/">Counseling</a></li>
                  <li><a href="/services/desp/">Disability Services</a></li>
                  <li><a href="/services/eops/">EOPS</a></li>
                  <li><a href="/services/health/">Health Services</a></li>
                  <li class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="/learning-communities/">Learning Communities</a>
                     
                     <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                        <li><a aria-haspopup="false" aria-expanded="false" href="/learning-communities/">Learning Communities</a></li>
                        <li><a href="/learning-communities/first-year/">First Year Experience</a></li>
                        <li><a href="/learning-communities/honors/">Honors</a></li>
                        <li><a href="/learning-communities/puente/">Puente</a></li>
                        <li><a href="/learning-communities/summer-bridge/">Summer Bridge</a></li>
                        <li><a href="/learning-communities/umoja/">Umoja</a></li>
                     </ul>
                  </li>
                  <li><a href="/admissions/outreach/">Outreach</a></li>
                  <li><a href="/services/success-center/">Success Center</a></li>
                  <li><a href="/services/transfer/">Transfer Center</a></li>
                  <li><a href="/services/veterans/">Veterans</a></li>
               </ul>
            </li>
            <li role="menuitem" class="hasChild"><a aria-haspopup="true" aria-expanded="false" href="#">ABOUT US</a>
               
               <ul class="submenu" role="group" aria-expanded="false"><li class="back"><a href="#" class="js-back" aria-label="Navigate back to top level links"><span aria-hidden="true" class="fa fa-arrow-left"></span>BACK</a></li>
                  <li><a aria-haspopup="false" aria-expanded="false" href="#">ABOUT US</a></li>
                  <li><a href="/tours/">Campus Tours</a></li>
                  <li><a href="/about/facts.html">Fast Facts</a></li>
                  <li><a href="/about/administration/">Our Administration</a></li>
               </ul>
            </li>
            <li role="menuitem"><a href="https://westvalley.prestosports.com/landing/index" target="_blank" rel="noopener">ATHLETICS</a></li>
            <li role="menuitem"><a title="Canvas" href="https://wvm.instructure.com" target="_blank" rel="noopener">Canvas</a></li>
            <li role="menuitem"><a href="https://outlook.com/owa/wvm.edu">Webmail</a></li>
            <li role="menuitem"><a href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing" target="_blank" rel="noopener">WVC Portal</a></li>
            <li role="menuitem"><a title="Starfish" href="https://wvm.starfishsolutions.com/starfish-ops" target="_blank" rel="noopener">Starfish</a></li>
            <li class="mobile-quicklinks"><a role="menuitem" href="/future-students/">Future Students</a><a role="menuitem" class="" href="/current-students/">Current Students</a><a role="menuitem" href="/faculty-staff/">Faculty and Staff</a><a role="menuitem" href="/community/">Community</a></li>
            <li class="a-theme-toggles"><button id="mobile-sun-button" class="nav-link m-theme-toggle" aria-label="Toggle to Light Theme"></button><label for="mobile-sun-button" class="sr-only">Toggle to Light Theme</label><span class="a-vertical-line" aria-hidden="true"></span><button id="mobile-moon-button" class="nav-link m-theme-toggle" aria-label="Toggle to Dark Theme"></button><label for="mobile-moon-button" class="sr-only">Toggle to Dark Theme</label></li>
         </ul></div></nav>
   </header>
</div><header id="header" role="banner" aria-label="banner" class="header desktop-header js-header-scrolling nav-down desktop">
   <div class="container-fluid">
      <div class="row">
         <div class="container-base container-max-width--1650">
            <div class="row">
               <div class="col-md-8 col-lg-8">
                  <div class="navbar-nav-container row" id="gateway-nav">
                     <nav id="tablet-nav" role="navigation" aria-label="Navigation">
                        <ul class="navbar-nav mt-2 mt-md-0 nav--menu accessible-megamenu" role="menu">
                           <li role="menuitem" id="utilities-dropdown" class="js-nav--item"><a href="#" class="nav-link nav-link-toplvl--button droplink" aria-label="Info For. Press the Enter key to open the submenu panel.">Info For</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-2" aria-expanded="false" aria-hidden="true">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Info For</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a href="/future-students/">Future Students</a></li>
                                       <li role="menuitem"><a class="" href="/current-students/">Current Students</a></li>
                                       <li role="menuitem"><a href="/faculty-staff/">Faculty and Staff</a></li>
                                       <li role="menuitem"><a href="/community/">Community</a></li>
                                    </ul>
                                 </li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="https://web.wvm.edu/#/canvas" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Canvas. Press the Enter key to open the submenu panel. Press enter key twice to visit Top Level Navigation Link" target="_blank" rel="noopener">Canvas</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-4" aria-expanded="false" aria-hidden="true">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Canvas</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="https://web.wvm.edu/#/canvas" target="_blank" rel="noopener">Canvas Login Info</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" title="Canvas Login" href="https://wvm.instructure.com" target="_blank" rel="noopener">Canvas Login</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/services/starfish/" class="nav-link nav-link-toplvl js-sub--nav" aria-label="Top Level Link - Starfish." title="Starfish" rel="noopener" id="js-subnav-6" aria-expanded="false" aria-hidden="true">Starfish</a></li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing" class="nav-link nav-link-toplvl" aria-label="Top Level Link - WVC Portal." target="_blank" rel="noopener">WVC Portal</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-8" aria-expanded="false" aria-hidden="true">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Portal</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="https://web.wvm.edu/#/" target="_blank" rel="noopener">Portal Login Help</a></li>
                                       <li role="menuitem"><a class="" href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing_get_started" target="_blank" rel="noopener">First Time Login</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" title="Portal Login" href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing" target="_blank" rel="noopener">Portal Login</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/classes/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Classes.">Classes</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-10" aria-expanded="false" aria-hidden="true">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Classes</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="/classes/schedule/">Class Schedule</a></li>
                                       <li role="menuitem"><a class="" href="/catalog/">Course Catalog</a></li>
                                       <li role="menuitem"><a class="" href="/classes/online.html">Online</a></li>
                                       <li role="menuitem"><a class="" href="/catalog/programs/">Programs</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" title="Classes" href="/classes/">Visit Classes Page</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/library/" class="nav-link nav-link-toplvl js-sub--nav" aria-label="Top Level Link - Library." id="js-subnav-12" aria-expanded="false" aria-hidden="true">Library</a></li>
                        </ul>
                     </nav>
                     <ul class="list-unstyled nav-theme-toggles--tablet">
                        <li class="nav-item p-md-0 mr-md-4 a-theme-toggles"><button id="tablet-sun-button" class="nav-link m-theme-toggle" aria-label="Toggle to Light Theme"></button><label for="tablet-sun-button" class="sr-only">Toggle to Light Theme</label><span class="a-vertical-line" aria-hidden="true"></span><button id="tablet-moon-button" class="nav-link m-theme-toggle" aria-label="Toggle to Dark Theme"></button><label for="tablet-moon-button" class="sr-only">Toggle to Dark Theme</label></li>
                     </ul>
                     <nav id="desktop-nav" role="navigation" aria-label="Navigation">
                        <ul id="desktop-only-links" class="p-md-0 mr-md-4 dropdown-ul nav--menu accessible-megamenu" role="menu">
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/future-students/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Future Students. Press the Enter key to open the submenu panel. Press enter key twice to visit Top Level Navigation Link" id="js-subnav-13" aria-controls="js-subnav-14" aria-expanded="false">Future Students</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-14" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-13">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Future Student Resources</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a href="/high-school-students/index.html">High School</a></li>
                                       <li role="menuitem"><a href="/services/international/index.html">International Students</a></li>
                                       <li role="menuitem"><a href="/graduating-high-school-students/index.html">Graduating Seniors</a></li>
                                       <li role="menuitem"><a href="/schools/continuing-education/index.html">Community Education</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" href="/future-students/">Visit Future Student Page</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/current-students/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Current Students." id="js-subnav-15" aria-controls="js-subnav-16" aria-expanded="false">Current Students</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-16" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-15">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Current Student Resources</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="/calendar/academic.html">Academic Calendar</a></li>
                                       <li role="menuitem"><a class="" href="/classes/schedule/">Class Schedule</a></li>
                                       <li role="menuitem"><a title="Mental Health Resources" href="/services/health/mental-health-resources.html">Mental Health Resources</a></li>
                                       <li role="menuitem"><a class="" href="/library/">Library</a></li>
                                       <li role="menuitem"><a class="" href="/contact/">Service Hours</a></li>
                                       <li role="menuitem"><a class="" href="https://wvmwebmail.wvm.edu/" target="_blank" rel="noopener">Student Email</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" href="/current-students/">Visit Current Student Page</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/faculty-staff/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Faculty and Staff." id="js-subnav-17" aria-controls="js-subnav-18" aria-expanded="false">Faculty and Staff</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-18" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-17">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Faculty and Staff Resources</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a href="/committees/accreditation/">Accreditation</a></li>
                                       <li role="menuitem"><a href="/committees/">Committees</a></li>
                                       <li role="menuitem"><a href="https://westvalley.elumenapp.com/public/">Courses and Programs</a></li>
                                       <li role="menuitem"><a href="/faculty/">Directory</a></li>
                                       <li role="menuitem"><a href="/contact/">Service Hours</a></li>
                                       <li role="menuitem"><a href="https://outlook.com/owa/wvm.edu" target="_blank" rel="noopener">Web Mail</a></li>
                                       <li role="menuitem"><a href="/distance-education/">WVC Online</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" href="/faculty-staff/">Visit Faculty and Staff Page</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/community/" class="nav-link nav-link-toplvl border-right--white" aria-label="Top Level Link - Community." id="js-subnav-19" aria-controls="js-subnav-20" aria-expanded="false">Community</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-20" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-19">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Community Resources</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a href="/facility-rentals/">Facility Rentals</a></li>
                                       <li role="menuitem"><a title="Foundation" href="https://foundation.wvm.edu/" target="_blank">Foundation</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" href="/community/">Visit Community Page</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="https://web.wvm.edu/#/canvas" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Canvas." target="_blank" rel="noopener" id="js-subnav-21" aria-controls="js-subnav-22" aria-expanded="false">Canvas</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-22" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-21">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Canvas</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="https://web.wvm.edu/#/canvas" target="_blank" rel="noopener">Canvas Login Info</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" title="Canvas Login" href="https://wvm.instructure.com" target="_blank" rel="noopener">Canvas Login</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/services/starfish/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Starfish." title="Starfish" rel="noopener" id="js-subnav-23">Starfish</a></li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing" class="nav-link nav-link-toplvl" aria-label="Top Level Link - WVC Portal." target="_blank" rel="noopener" id="js-subnav-24" aria-controls="js-subnav-25" aria-expanded="false">WVC Portal</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-25" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-24">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Portal</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="https://web.wvm.edu/#/" target="_blank" rel="noopener">Portal Login Help</a></li>
                                       <li role="menuitem"><a class="" href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing_get_started" target="_blank" rel="noopener">First Time Login</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" title="Portal Login" href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/myPortal_landing" target="_blank" rel="noopener">Portal Login</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/classes/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Classes." id="js-subnav-26" aria-controls="js-subnav-27" aria-expanded="false">Classes</a><ul class="sub-nav-group js-sub--nav" role="menu" id="js-subnav-27" aria-expanded="false" aria-hidden="true" aria-labelledby="js-subnav-26">
                                 <li role="menuitem">
                                    <h2 class="subnav-heading has-border">Classes</h2>
                                    <ul class="two-column-links" role="menu">
                                       <li role="menuitem"><a class="" href="/classes/schedule/">Class Schedule</a></li>
                                       <li role="menuitem"><a class="" href="/catalog/">Course Catalog</a></li>
                                       <li role="menuitem"><a class="" href="/classes/online.html">Online</a></li>
                                       <li role="menuitem"><a class="" href="/catalog/programs/">Programs</a></li>
                                    </ul><a class="a-base-button a-button--primary-trans" title="Classes" href="/classes/">Visit Classes Page</a></li>
                              </ul>
                           </li>
                           <li class="nav-item js-nav--item" role="menuitem"><a href="/library/" class="nav-link nav-link-toplvl" aria-label="Top Level Link - Library." id="js-subnav-28">Library</a></li>
                        </ul>
                     </nav>
                     <ul class="list-unstyled nav-theme-toggles--desktop">
                        <li class="nav-item p-md-0 mr-md-4 a-theme-toggles"><button id="sun-button" class="nav-link m-theme-toggle" aria-label="Toggle to Light Theme"></button><label for="sun-button" class="sr-only">Toggle to Light Theme</label><span class="a-vertical-line" aria-hidden="true"></span><button id="moon-button" class="nav-link m-theme-toggle" aria-label="Toggle to Dark Theme"></button><label for="moon-button" class="sr-only">Toggle to Dark Theme</label></li>
                     </ul>
                  </div>
               </div>
               <div class="col-md-4 m-right-nav">
                  <nav class="navbar">
                     <form id="global-search-form" class="form-inline" action="/search/results.html"><label class="sr-only" for="global-search">SEARCH WEST VALLEY</label><input class="search-form-control mr-md-2" type="text" name="q" placeholder="SEARCH WEST VALLEY" id="global-search"><label class="sr-only" for="global-search-submit">Submit Search Query</label><button id="global-search-submit" class="button--toggle my-2 my-md-0" type="submit" aria-label="Submit Search Query"><span class="fa fa-search" aria-hidden="true"></span></button><label class="sr-only" for="global-search-toggle">Toggle Search Input</label><button id="global-search-toggle" class="my-2 my-md-0" type="button" aria-label="Toggle Search Input"><span id="toggle-icon" class="fa fa-search" aria-hidden="true"></span></button></form>
                  </nav>
               </div>
            </div>
         </div>
         <nav class="navbar navbar-expand-md" id="main-nav" role="navigation" aria-label="Main Navigation">
            <div class="container-base container-max-width--1650">
               <div class="collapse navbar-collapse navbarToggler">
                  <div class="col-md-4 col-lg-3"><a class="navbar-brand" href="/"><img class="logo" src="/src/assets/wvc-logo.svg" alt="West Valley College - Link To Homepage"></a></div>
                  <div class="no-padding--tablet col-md-8 col-lg-9">
                     <ul class="navbar-nav mt-md-0" role="menu">
                        <li class="nav-item" role="menuitem"><a class="nav-link" title="Apply Now" href="/onboard/">Apply</a></li>
                        <li class="nav-item" role="menuitem"><a class="nav-link" title="Admissions" href="/admissions/">Admissions</a></li>
                        <li class="nav-item" role="menuitem"><a class="nav-link" title="Academics" href="/academics/">Academics</a></li>
                        <li class="nav-item" role="menuitem"><a class="nav-link" title="Student Services" href="/services/">Student Services</a></li>
                        <li class="nav-item" role="menuitem"><a class="nav-link" title="About" href="/about/">About Us</a></li>
                        <li class="nav-item" role="menuitem"><a class="nav-link" title="WVC Athletics" href="https://westvalley.prestosports.com/landing/index" target="_blank" rel="noopener">Athletics</a></li>
                     </ul>
                  </div>
               </div>
            </div>
         </nav>
      </div>
   </div>
</header><!-- OU Search Ignore End Here --><!-- OU Search Ignore Start Here --><div class="o-breadcrumb"><div class="container-base container-max-width--1650"><div class="row"><div class="col-12"><nav class="m-breadcrumb"><a class="breadcrumb-item" href="https://www.westvalley.edu/">Home</a><span class="breadcrumb-item active">Get On Board<span class="sr-only">Current Page</span></span></nav></div></div></div></div><!-- OU Search Ignore End Here --><section class="m-content-header"><div class="container-base container-max-width--1650 content-header"><div class="row"><div class="col-12"><h1>Get On Board</h1></div></div></div></section><div class="container-base container-max-width--1650"><div class="row"><aside id="subnav-aside" role="complementary" class="subnav-container left-subnav col-md-12 col-lg-3"><!-- OU Search Ignore Start Here --><h2 id="subnav-toggle" class="section-title"></h2><span id="focus-toggle" class="sr-only" tabindex="0">Open subnavigation</span><div class="subnav-content"><nav id="subnavigation" role="navigation"><ul class="subnav menu">
	<li class="top-level-menu-item"><a href="/onboard/">Home</a></li>
	<li class="top-level-menu-item"><a href="/admissions/free-tuition.html">Free Tuition for District Residents</a></li>
	<li class="top-level-menu-item"><a href="/onboard/apply.html">Step 1: Apply</a></li>
	<li class="top-level-menu-item"><a href="/onboard/activate.html">Step 2: Activate</a></li>
	<li class="top-level-menu-item"><a href="/onboard/empower.html">Step 3: Empower</a></li>
	<li class="top-level-menu-item"><a href="/onboard/register.html">Step 4: Register</a></li>
	<li class="top-level-menu-item"><a href="/onboard/prepare.html">Step 5: Prepare</a></li>
</ul></nav></div><!-- OU Search Ignore End Here --><section id="supplementary-content-section" aria-label="Supplementary Content" class="supplementary-content">
		
		

	<div class="card text-left bg-transparent"><div class="card-header">Need Help?</div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Email AskWVC" href="mailto:askwvc@westvalley.edu" target="_blank" rel="noopener">Email: askwvc@westvalley.edu</a><a class="list-group-item list-group-item-action" title="Call Hello Desk" href="tel:+14087412633" target="_blank" rel="noopener">Phone: (408) 741-2633</a><a class="list-group-item list-group-item-action" title="Video Library" href="/onboard/videos.html">Video Library</a></div></div>
 

	</section></aside><div class="col-md-12 col-lg-9"><main id="main-content"><div class="full-bleed"><div class="row"><div class="col"><h2 xmlns:ouc="http://omniupdate.com/XSL/Variables">Join our community. Become a West Valley College student today.</h2>


    <h3 class="app-begin">Begin Your Application:</h3>
    <div class="app-begin-container">
      <a href="https://www.westvalley.edu/high-school-students/index.html" class="imageLink a-base-button a-button--primary w-40 mx-md-auto wv-full-width-sm" role="button" target="_blank" rel="noopener">High School</a>
      <a href="https://www.westvalley.edu/graduating-high-school-students/index.html" class="imageLink a-base-button a-button--primary w-40 mx-md-auto wv-full-width-sm" role="button" target="_blank" rel="noopener">Graduating Seniors</a>
      <a href="https://www.westvalley.edu/services/international/index.html" class="imageLink a-base-button a-button--primary w-40 mx-md-auto wv-full-width-sm" role="button" target="_blank" rel="noopener">International Students</a>
      <a href="https://www.westvalley.edu/schools/continuing-education/index.html" class="imageLink a-base-button a-button--primary w-40 mx-md-auto wv-full-width-sm" role="button" target="_blank" rel="noopener">Community Education</a>
    </div>


	<div class="card-deck"><div class="card text-left bg-transparent"><img src="https://www.westvalley.edu/onboard/_files/images/card-apply.jpg" class="card-img-top" alt="Smiling female student in wheelchair with laptop"><div class="card-body"><p xmlns:ouc="http://omniupdate.com/XSL/Variables"><em>Apply now to West Valley College.</em></p>
<p xmlns:ouc="http://omniupdate.com/XSL/Variables">Within 48 hours after applying, you will receive a welcome email with your Student ID Number and WVC Username.</p>
<p xmlns:ouc="http://omniupdate.com/XSL/Variables"><em>NOTE: If you do not receive an email with your Student ID Number within 48 hours, search your inbox for a message with the subject, “Welcome to West Valley College” and forward that message to <a title="Admissions email" href="mailto:wvc.admissions@westvalley.edu" data-values-rep-one="KNIL_LAICEPS" data-values-rep-two="EERF" data-values-rep-three="ude.yellavtsew" data-values-rep-four="YELLAV_TSEW" data-values-rep-five="@" data-values-rep-six=":otliam" data-values-do-something="true">wvc.admissions@westvalley.edu</a></em></p></div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Create an Open CCC Apply account " href="https://www.opencccapply.net/gateway/apply?cccMisCode=493" target="_blank" rel="noopener">Create an Open CCC Apply account</a><a class="list-group-item list-group-item-action" title="Submit an application for admission to &nbsp;West Valley College" href="https://www.opencccapply.net/gateway/apply?cccMisCode=493" target="_blank" rel="noopener">Submit an application for admission to West Valley College</a></div><div class="card-body"><div class="w-100"><a href="/onboard/apply.html" class="imageLink a-base-button  a-button--primary" role="button" target="_self">See More Details</a></div></div></div>
 
 

	<div class="card text-left bg-transparent"><img src="https://www.westvalley.edu/onboard/_files/images/card-activate.jpg" class="card-img-top" alt="Two smiling male students looking at laptop"><div class="card-body"><p xmlns:ouc="http://omniupdate.com/XSL/Variables"><em>Once you receive your welcome email or text, activate access to your portal, WVC systems and WVC Go App.</em></p></div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Log into the WVC Portal" href="https://web.wvm.edu/#/get-started" target="_blank" rel="noopener">Log into the WVC Portal</a><a class="list-group-item list-group-item-action" title="Complete Guided Self-Placement (this will activate your email account)" href="https://generalssb-prod.ec.wvm.edu/BannerExtensibility/customPage/page/sgp3" target="_blank" rel="noopener">Complete My Placement (this will activate your email account)</a><a class="list-group-item list-group-item-action" title="Download the WVC Go App and login" href="/mobile/">Download the WVC Go App and login</a></div><div class="card-body"><div class="w-100"><a href="/onboard/activate.html" class="imageLink a-base-button  a-button--primary" role="button" target="_self">See More Details</a></div></div></div>
 
 

	<div class="card text-left bg-transparent"><img src="https://www.westvalley.edu/onboard/_files/images/card-empower.jpg" class="card-img-top" alt="Female student flexing bicep and smiling"><div class="card-body"><p xmlns:ouc="http://omniupdate.com/XSL/Variables"><em>Empower yourself for a successful college experience.</em></p></div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Complete an orientation" href="/admissions/orientation.html">Complete an orientation</a><a class="list-group-item list-group-item-action" title="Apply for Financial Aid or Dream Act" href="/financial-aid/">Apply for Financial Aid or Dream Act</a><a class="list-group-item list-group-item-action" title="Investigate and apply to support programs" href="/learning-communities/#tabs-2">Investigate and apply to support programs</a><a class="list-group-item list-group-item-action" title="Meet with a counselor" href="/services/online/guides/">Meet with a counselor</a></div><div class="card-body"><div class="w-100"><a href="/onboard/empower.html" class="imageLink a-base-button  a-button--primary" role="button" target="_self">See More Details</a></div></div></div></div>
 

<div xmlns:ouc="http://omniupdate.com/XSL/Variables" class="row">
<div class="col-md-4">


	<div class="card text-left bg-transparent"><img src="https://www.westvalley.edu/onboard/_files/images/card-register.jpg" class="card-img-top" alt="Laptop with student hand holding mobile phone"><div class="card-body"><p><em>Register for the classes that meet your goals.</em></p></div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Search for classes" href="https://schedule.wvm.edu/?college=wv" target="_blank" rel="noopener">Search for classes</a><a class="list-group-item list-group-item-action" title="Submit pre-requisites for classes (if needed)" href="/admissions/assessment/prerequisite_form.html">Submit pre-requisites for classes (if needed)</a><a class="list-group-item list-group-item-action" title="Register for classes" href="/admissions/registration.html">Register for classes</a><a class="list-group-item list-group-item-action" title="Register for classes" href="https://www.westvalley.edu/academics/career-programs/index.html">See Class Programs</a></div><div class="card-body"><div class="w-100"><a href="/onboard/register.html" class="imageLink a-base-button  a-button--primary" role="button" target="_self">See More Details</a></div></div></div>
 

</div>
<div class="col-md-4">


	<div class="card text-left bg-transparent"><img src="https://www.westvalley.edu/onboard/_files/images/card-prepare.jpg" class="card-img-top" alt="Female student smiling and holding books"><div class="card-body"><p><em>Congratulations! You are registered! Now, prepare for success in the classroom.</em></p></div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Pay your fees" href="/admissions/fee-schedule.html">Pay your fees</a><a class="list-group-item list-group-item-action" href="/services/welcome-center/">Request student ID</a><a class="list-group-item list-group-item-action" title="Find and purchase textbooks" href="https://bncvirtual.com/wvm" target="_blank" rel="noopener">Find and purchase textbooks</a><a class="list-group-item list-group-item-action" title="Request TNT (Textbooks and Technology)" href="/library/textbooks-and-technology.html">Investigate free TNT (Textbooks and Technology)</a><a class="list-group-item list-group-item-action" title="Request parking permit" href="/parking/">Request parking permit</a><a class="list-group-item list-group-item-action" title="Log into Canvas" href="https://wvm.instructure.com/" target="_blank" rel="noopener">Log into and navigate Canvas one week prior to class starting</a></div><div class="card-body"><div class="w-100"><a href="/onboard/prepare.html" class="imageLink a-base-button  a-button--primary" role="button" target="_self">See More Details</a></div></div></div>
 

</div>
<div class="col-md-4">


	<div class="card text-left bg-transparent"><div class="card-header">Need Help?</div><div class="list-group list-group-flush "><a class="list-group-item list-group-item-action" title="Email AskWVC" href="mailto:askwvc@westvalley.edu" target="_blank" rel="noopener">Email: askwvc@westvalley.edu</a></div></div>
 

</div>
</div></div></div></div></main></div></div></div><!-- OU Search Ignore Start Here --><footer id="footer-skip" class="o-footer-section"><section id="o-footer-bottom" class="o-footer-bottom">
   <div class="container-base container-max-width--1650">
      <div class="row">
         <div class="col-md-12">
            <div class="row">
               <div class="col-md-6">
                  <div class="m-footer-links">
                     <div class="row">
                        <div class="col-sm-6 col-md-6">
                           <div class="m-footer-links--left">
                              <ul>
                                 <li><a href="//www.wvm.edu/Pages/default.aspx" target="_blank">West Valley-Mission Community College District</a></li>
                                 <li><a href="//www.missioncollege.edu/" target="_blank">Mission College</a></li>
                              </ul>
                           </div>
                        </div>
                        <div class="col-sm-6 col-md-6">
                           <div class="m-footer-links--right">
                              <ul>
                                 <li><a href="/accessibility/">Accessibility</a></li>
                                 <li><a href="/policies/">Policies</a></li>
                                 <!-- Terms of Use -->
                              </ul>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div class="col-md-6">
                  <div class="m-footer-links m-footer-links--layout">
                     <div class="row">
                        <div class="col-sm-6 col-md-6">
                           <div class="m-footer-links--left">
                              <ul>
                                 <li><a href="/maps/">Maps</a></li>
                                 <li><a href="/parking/">Parking</a></li>
                              </ul>
                           </div>
                        </div>
                        <div class="col-sm-6 col-md-6">
                           <div class="m-footer-links--right">
                              <ul>
                                 <li><a href="//wvm.edu/services/police/prepare/Pages/default.aspx" target="_blank">Emergency Information</a></li>
                                 <li><a href="/sitemap.html">Sitemap</a></li>
                              </ul>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <div class="row">
         <div class="col-12">
            <div class="m-footer-links hasTopBorder--layout">
               <p class="a-copyright-address">© Copyright West Valley College | 14000 Fruitvale Ave, Saratoga, California 95070</p><br><span id="directedit"><a href="https://a.cms.omniupdate.com/11/?skin=oucampus&amp;account=westvalley&amp;site=www&amp;action=de&amp;path=/onboard/index.pcf" id="de" target="_top" rel="nofollow">Last Updated 8/14/24</a></span></div>
         </div>
      </div>
   </div>
</section></footer><!-- OU Search Ignore End Here --><!-- OU Search Ignore Start Here -->
<!-- VENDOR -->
<!-- <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.min.js" integrity="sha256-VazP97ZCwtekAsvgPBSUwPFKdrwD3unUfSGVYrahUqU=" crossorigin="anonymous"></script>
<script src="/_resources/libs/jquery-search-table/jquery-search-table.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js" integrity="sha384-wHAiFfRlMFy6i5SRaxvfOCifBUQy1xHdJ/yoi7FRNXMRBu5WHdZYu1hA6ZOblgut" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js" integrity="sha384-B0UglyR+jN6CkvvICOB2joaf5I4l3gm9GU6Hc1og6Ls7i6U/mkkaduKaBhlAXv9k" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
<script src="/_resources/libs/jquery-accessible-menu/jquery-accessibleMegaMenu.js"></script><script src="/_resources/libs/jquery-accessible-menu/jquery-accessibleMegaMenu.js"></script> -->
<!-- <script src="/_resources/libs/jwplayer/jwplayer.js"></script> -->
<!-- <script>jwplayer.key="u3OTqxsL+6BM3j81tbrwz2Q31lKEHbwXKSX4yg==";</script>
<script src="/_resources/libs/multiple-select/multiple-select.js"></script>
<script src="/_resources/js/vendor.js"></script> -->

<!-- SCRIPTS -->
<!-- <script src="/_resources/js/main.js?v=1.1"></script>
<script src="/_resources/js/direct-edit.js"></script> -->

<!-- Pingdom -->
<!-- <script src="//rum-static.pingdom.net/pa-53194237abe53dea54961deb.js" async=""></script> -->

<!-- Mouseflow -->
<!-- <script type="text/javascript">
	window._mfq = window._mfq || [];
	(function() {
		var mf = document.createElement("script");
		mf.type = "text/javascript"; mf.defer = true;
		mf.src = "//cdn.mouseflow.com/projects/f97e1952-c42e-4af0-8f3c-4442e3c155e1.js";
		document.getElementsByTagName("head")[0].appendChild(mf);
	})();
</script> -->

<!-- Google Tag Manager (noscript) -->
<noscript>
	<iframe src="https://www.googletagmanager.com/ns.html?id=GTM-TCR8QNR" height="0" width="0" style="display:none;visibility:hidden"></iframe>
</noscript>
<!-- End Google Tag Manager (noscript) --><!-- Google Analytics (gtag.js) -->
<!-- <script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-4494000-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-4494000-1');
  gtag('config', 'UA-4494000-4');
</script> -->
OU Search Ignore End Here<div style="display:none;"></div><div id="js-back-to-top--container"><label for="js-back-to-top" class="sr-only">Scrolls back to top of the Web Page</label><button id="js-back-to-top" class="m-back-to-top-base m-back-to-top" title="Return to Top"><span class="fa fa-arrow-up" aria-hidden="true"></span></button></div>
<!-- <script src="https://www.westvalley.edu/ou-alerts/alerts-config.alerts.js?v=2.1-20240429125031"></script> -->
<!-- <script>
	// archive alert processing
	if (document.getElementById(ouEmergencyAlerts.archivedAlertDivId)) {
		ouEmergencyAlerts.loadAlertFeed("processAlertFeedForArchivePage", "activeAlertFeed", "archiveActiveAlertHeading");  
		setTimeout(function() {
			ouEmergencyAlerts.loadAlertFeed("processAlertFeedForArchivePage", "archiveAlertFeed", "archiveAlertHeading");
		}, 200);
	}
	// active alert processing
	ouEmergencyAlerts.determineActiveAlertOutput();
</script> -->
<!-- <script type="text/template" id="oualerts-active-announcement">
<div id="oualerts-active-alert-display" class="oualerts-notify oualerts-notify-announcement oualerts-top oualerts-top-fixed ouAlertsFadeInDown oualerts-animated-fast">
	<div class="oualerts-notify-body">
		{% if (o.showDate) { %}
		<div class="oualerts-notify-date">{%=ouEmergencyAlerts.alertDateFormat("F d, Y h:i A",o.pubDate)%}</div>
		{% } %}
		<h3 class="oualerts-notify-title">
			
						<svg class="oualerts-notify-icon" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 271 286"><path fill-rule="evenodd" d="M241.964 157.267v69.997c0 5.11-5.639 8.199-9.934 5.442l-86.454-55.51h-13.388l11.06 28.862c18.297 3.828 32.042 20.078 32.042 39.544 0 22.311-18.056 40.398-40.328 40.398-17.471 0-32.347-11.13-37.949-26.698l-.0122.005-31.4593-82.111h-5.3193C26.9624 177.196 0 150.187 0 116.869c0-33.3175 26.9624-60.3268 60.2222-60.3268h85.3538L232.03 1.0324c4.295-2.7574 9.934.3319 9.934 5.4417v69.9975h18.282c5.939 0 10.754 4.8231 10.754 10.7727v59.2497c0 5.95-4.815 10.773-10.754 10.773h-18.282zm-15.055 54.237l-75.278-48.334V70.5682l75.278-48.3337V211.504zm15.055-69.319h13.98V91.5533h-13.98v50.6317z" clip-rule="evenodd"/></svg>
					
			{%=o.title%}
		</h3>
		{% if (o.subtitle) { %}
		<p class="oualerts-notify-subtitle"><strong>{%=o.subtitle %}</strong></p>
		{% } %}
		{% if (o.description) { %}
		<p class="oualerts-notify-msg">{%=o.description %}
			{% } %}
			{% if (o.guid) { %}
			<br>
			<a href="{%=o.guid %}" class="oualerts-notify-link">More info...</a>
			{% } %}
			{% if (o.description) { %}
		</p>
		{% } %}
		<p class="oualerts-notify-footer">
			<button class="oualerts-close-button" id="oualerts-close-button">Hide</button>
		</p>
	</div>
</div>
</script> -->
<!-- <script type="text/template" id="oualerts-active-warning">
<div id="oualerts-active-alert-display" class="oualerts-notify oualerts-notify-warning oualerts-top oualerts-top-fixed ouAlertsFadeInDown oualerts-animated-fast">
	<div class="oualerts-notify-body">
		{% if (o.showDate) { %}
		<div class="oualerts-notify-date">{%=ouEmergencyAlerts.alertDateFormat("F d, Y h:i A",o.pubDate)%}</div>
		{% } %}
		<h3 class="oualerts-notify-title">
			
						<svg class="oualerts-notify-icon" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 273 273"><path fill-rule="evenodd" d="M273 136.5c0 75.387-61.113 136.5-136.5 136.5C61.1131 273 0 211.887 0 136.5 0 61.1131 61.1131 0 136.5 0 211.887 0 273 61.1131 273 136.5zM123 58v105h27V58h-27zm0 157v-26.5h27V215h-27z" clip-rule="evenodd"/></svg>
					
			{%=o.title%}
		</h3>
		{% if (o.subtitle) { %}
		<p class="oualerts-notify-subtitle"><strong>{%=o.subtitle %}</strong></p>
		{% } %}
		{% if (o.description) { %}
		<p class="oualerts-notify-msg">{%=o.description %}
			{% } %}
			{% if (o.guid) { %}
			<br>
			<a href="{%=o.guid %}" class="oualerts-notify-link">Read More...</a>
			{% } %}
			{% if (o.description) { %}
		</p>
		{% } %}
		<p class="oualerts-notify-footer">
			<button class="oualerts-close-button" id="oualerts-close-button">Close</button>
		</p>
	</div>
</div>
</script> -->

<!-- <script type="text/template" id="oualerts-active-emergency">
<div id="oualerts-active-alert-display" class="oualerts-notify oualerts-notify-emergency oualerts-top oualerts-top-fixed ouAlertsFadeInDown oualerts-animated-fast">
	<div class="oualerts-notify-body">
		{% if (o.showDate) { %}
		<div class="oualerts-notify-date">{%=ouEmergencyAlerts.alertDateFormat("F d, Y h:i A",o.pubDate)%}</div>
		{% } %}
		<h3 class="oualerts-notify-title">
			
						<svg class="oualerts-notify-icon" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 298 273"><path fill-rule="evenodd" d="M137.626 7.553c4.947-8.9403 17.801-8.9403 22.748 0l135.948 245.652c4.795 8.665-1.471 19.295-11.374 19.295H13.0524c-9.903 0-16.1695-10.63-11.3744-19.295L137.626 7.553zM136.5 85v100h25V85h-25zm0 149.5v-24h25v24h-25z" clip-rule="evenodd"/></svg>
					
			{%=o.title%}
		</h3>
		{% if (o.subtitle) { %}
		<p class="oualerts-notify-subtitle"><strong>{%=o.subtitle %}</strong></p>
		{% } %}
		{% if (o.description) { %}
		<p class="oualerts-notify-msg">{%=o.description %}
			{% } %}
			{% if (o.guid) { %}
			<br>
			<a href="{%=o.guid %}" class="oualerts-notify-link">More info...</a>
			{% } %}
			{% if (o.description) { %}
		</p>
		{% } %}
		<p class="oualerts-notify-footer">
			<button class="oualerts-close-button" id="oualerts-close-button">Close</button>
		</p>
	</div>
</div>
</script> -->
<!-- <script type="text/template" id="oualerts-archived-template">
{% if (o[0].htmlHeading) { %}
<h2 class="oualerts-archive-main-heading">{%=o[0].htmlHeading %}</h2>
{% } %}
<ul class="oualerts-achive-list">
	{% for (var i=0; o.length > i; i++) { %}
	<li class="oualerts-achive-list-item oualerts-archive-type-{%=o[i].severity%}">
		<div class="oualerts-achive-list-item-inner">
			<h3 class="oualerts-archive-title">{%=o[i].title%}</h3>
			<div class="oualerts-archive-date">{%=ouEmergencyAlerts.alertDateFormat("F d, Y h:i A",o[i].pubDate)%}</div>
			{% if (o[i].subtitle) { %}
			<p class="oualerts-archive-subtitle"><strong>{%=o[i].subtitle %}</strong></p>
			{% } %}
			{% if (o[i].description) { %}
			<p class="oualerts-archive-msg">{%=o[i].description %}
				{% } %}
				{% if (o[i].guid) { %}
				<a href="{%=o[i].guid %}" class="oualerts-archive-link">{%=ouEmergencyAlerts[o[i].severity + "Archive"].readMoreText%}</a>
				{% } %}
				{% if (o[i].description) { %}
			</p>
			{% } %}
			{% if (o[i].updates) { %}
			<h4 class="oualerts-archive-list-update-header">{%=ouEmergencyAlerts[o[i].severity + "Archive"].updateText %}</h4>
			<ul class="oualerts-achive-list-update">
				{% for (var k=0; o[i].updates.length > k; k++) { %}
				<li class="oualerts-achive-list-item-update">
					<div class="oualerts-achive-list-item-update-inner">
						<h5 class="oualerts-archive-title-update">{%=o[i].updates[k].title%}</h5>
						<div class="oualerts-archive-date-update">{%=ouEmergencyAlerts.alertDateFormat("F d, Y h:i A",o[i].updates[k].pubDate)%}</div>
						{% if (o[i].updates[k].subtitle) { %}
						<p class="oualerts-archive-subtitle-update"><strong>{%=o[i].updates[k].subtitle %}</strong></p>
						{% } %}
						{% if (o[i].updates[k].description) { %}
						<p class="oualerts-archive-msg-update">{%=o[i].updates[k].description %}
							{% } %}
							{% if (o[i].updates[k].guid) { %}
							<a href="{%=o[i].updates[k].guid %}" class="oualerts-archive-link-update">{%=ouEmergencyAlerts[o[i].severity + "Archive"].readMoreText%}</a>
							{% } %}
							{% if (o[i].updates[k].description) { %}
						</p>
						{% } %}
					</div>
				</li>
				{% } %}
			</ul>
			{% } %}
		</div>
	</li>
	{% } %}
</ul>
</script> -->
</template>

<style scoped>
@charset "UTF-8";
/*!
* Bootstrap v4.2.1 (https://getbootstrap.com/)
* Copyright 2011-2018 The Bootstrap Authors
* Copyright 2011-2018 Twitter, Inc.
* Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
*/
:root {
	--blue: #007bff;
	--indigo: #6610f2;
	--purple: #6f42c1;
	--pink: #e83e8c;
	--red: #dc3545;
	--orange: #fd7e14;
	--yellow: #ffc107;
	--green: #28a745;
	--teal: #20c997;
	--cyan: #17a2b8;
	--white: #fff;
	--gray: #6c757d;
	--gray-dark: #343a40;
	--primary: #007bff;
	--secondary: #6c757d;
	--success: #28a745;
	--info: #17a2b8;
	--warning: #ffc107;
	--danger: #dc3545;
	--light: #f8f9fa;
	--dark: #343a40;
	--breakpoint-xs: 0;
	--breakpoint-sm: 576px;
	--breakpoint-md: 768px;
	--breakpoint-lg: 992px;
	--breakpoint-xl: 1200px;
	--font-family-sans-serif: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
	--font-family-monospace: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
}
/* --------------------------------
Begin Bootstrap Print Styles
----------------------------------- */
@media print {
	*,
	*::before,
	*::after {
		text-shadow: none !important;
		box-shadow: none !important;
	}
	a:not(.btn) {
		text-decoration: underline;
	}
	abbr[title]::after {
		content: " (" attr(title) ")";
	}
	pre {
		white-space: pre-wrap !important;
	}
	pre,
	blockquote {
		border: 1px solid #adb5bd;
		page-break-inside: avoid;
	}
	thead {
		display: table-header-group;
	}
	tr,
	img {
		page-break-inside: avoid;
	}
	p,
	h2,
	h3 {
		orphans: 3;
		widows: 3;
	}
	h2,
	h3 {
		page-break-after: avoid;
	}
	@page {
		size: a3;
	}
	body {
		min-width: 992px !important;
	}
	.container {
		min-width: 992px !important;
	}
	.navbar {
		display: none;
	}
	.badge {
		border: 1px solid #000;
	}
	.table {
		border-collapse: collapse !important;
	}
	.table td,
	.table th {
		background-color: #fff !important;
	}
	.table-bordered th,
	.table-bordered td {
		border: 1px solid #dee2e6 !important;
	}
	.table-dark {
		color: inherit;
	}
	.table-dark th,
	.table-dark td,
	.table-dark thead th,
	.table-dark tbody + tbody {
		border-color: #dee2e6;
	}
	.table .thead-dark th {
		color: inherit;
		border-color: #dee2e6;
	}
}
/* --------------------------------
End Bootstrap Print Styles
----------------------------------- */
/* --------------------------------
Begin Bootstrap Core Styles
----------------------------------- */
*,
*::before,
*::after {
	box-sizing: border-box;
}

html {
	font-family: sans-serif;
	line-height: 1.15;
	-webkit-text-size-adjust: 100%;
	-webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

article, aside, figcaption, figure, footer, header, hgroup, main, nav, section {
	display: block;
}

body {
	margin: 0;
	font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
	font-size: 1rem;
	font-weight: 400;
	line-height: 1.5;
	color: #212529;
	text-align: left;
	background-color: #fff;
}

[tabindex="-1"]:focus {
	outline: 0 !important;
}

hr {
	box-sizing: content-box;
	height: 0;
	overflow: visible;
}

h1, h2, h3, h4, h5, h6 {
	margin-top: 0;
	margin-bottom: 0.5rem;
}

p {
	margin-top: 0;
	margin-bottom: 1rem;
}

abbr[title],
abbr[data-original-title] {
	text-decoration: underline;
	-webkit-text-decoration: underline dotted;
	text-decoration: underline dotted;
	cursor: help;
	border-bottom: 0;
	text-decoration-skip-ink: none;
}

address {
	margin-bottom: 1rem;
	font-style: normal;
	line-height: inherit;
}

ol,
ul,
dl {
	margin-top: 0;
	margin-bottom: 1rem;
}

ol ol,
ul ul,
ol ul,
ul ol {
	margin-bottom: 0;
}

dt {
	font-weight: 700;
}

dd {
	margin-bottom: .5rem;
	margin-left: 0;
}

blockquote {
	margin: 0 0 1rem;
}

b,
strong {
	font-weight: bolder;
}

small {
	font-size: 80%;
}

sub,
sup {
	position: relative;
	font-size: 75%;
	line-height: 0;
	vertical-align: baseline;
}

sub {
	bottom: -.25em;
}

sup {
	top: -.5em;
}

a {
	color: #007bff;
	text-decoration: none;
	background-color: transparent;
}

a:hover {
	color: #0056b3;
	text-decoration: underline;
}

a:not([href]):not([tabindex]) {
	color: inherit;
	text-decoration: none;
}

a:not([href]):not([tabindex]):hover, a:not([href]):not([tabindex]):focus {
	color: inherit;
	text-decoration: none;
}

a:not([href]):not([tabindex]):focus {
	outline: 0;
}

pre,
code,
kbd,
samp {
	font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
	font-size: 1em;
}

pre {
	margin-top: 0;
	margin-bottom: 1rem;
	overflow: auto;
}

figure {
	margin: 0 0 1rem;
}

img {
	vertical-align: middle;
	border-style: none;
}

svg {
	overflow: hidden;
	vertical-align: middle;
}

table {
	border-collapse: collapse;
}

caption {
	padding-top: 0.75rem;
	padding-bottom: 0.75rem;
	color: #212529;
	text-align: left;
	caption-side: bottom;
}

.caption-top {
	caption-side: top;
}

th {
	text-align: inherit;
}

label {
	display: inline-block;
	margin-bottom: 0.5rem;
}

button {
	border-radius: 0;
}

button:focus {
	outline: 1px dotted;
	outline: 5px auto -webkit-focus-ring-color;
}

input,
button,
select,
optgroup,
textarea {

	margin: 0;
	font-family: inherit;
	font-size: inherit;
	/*   line-height: inherit; */
}

button,
input {
	overflow: visible;
}

button,
select {
	text-transform: none;
}

button,
[type="button"],
[type="reset"],
[type="submit"] {
	-webkit-appearance: button;
}

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
	padding: 0;
	border-style: none;
}

input[type="radio"],
input[type="checkbox"] {
	box-sizing: border-box;
	padding: 0;
}

input[type="date"],
input[type="time"],
input[type="datetime-local"],
input[type="month"] {
	-webkit-appearance: listbox;
}

textarea {
	overflow: auto;
	resize: vertical;
}

fieldset {
	min-width: 0;
	padding: 0;
	margin: 0;
	border: 0;
}

legend {
	display: block;
	width: 100%;
	max-width: 100%;
	padding: 0;
	margin-bottom: .5rem;
	font-size: 1.5rem;
	line-height: inherit;
	color: inherit;
	white-space: normal;
}

progress {
	vertical-align: baseline;
}

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
	height: auto;
}

[type="search"] {
	outline-offset: -2px;
	-webkit-appearance: none;
}

[type="search"]::-webkit-search-decoration {
	-webkit-appearance: none;
}

::-webkit-file-upload-button {
	font: inherit;
	-webkit-appearance: button;
}

output {
	display: inline-block;
}

summary {
	display: list-item;
	cursor: pointer;
}

template {
	display: none;
}

[hidden] {
	display: none !important;
}

h1, h2, h3, h4, h5, h6,
.h1, .h2, .h3, .h4, .h5, .h6 {
	margin-bottom: 0.5rem;
	font-family: inherit;
	font-weight: 500;
	line-height: 1.2;
	color: inherit;
}

h1, .h1 {
	font-size: 2.5rem;
}

h2, .h2 {
	font-size: 2rem;
}

h3, .h3 {
	font-size: 1.75rem;
}

h4, .h4 {
	font-size: 1.5rem;
}

h5, .h5 {
	font-size: 1.25rem;
}

h6, .h6 {
	font-size: 1rem;
}

.lead {
	font-size: 1.25rem;
	font-weight: 300;
}

.display-1 {
	font-size: 6rem;
	font-weight: 300;
	line-height: 1.2;
}

.display-2 {
	font-size: 5.5rem;
	font-weight: 300;
	line-height: 1.2;
}

.display-3 {
	font-size: 4.5rem;
	font-weight: 300;
	line-height: 1.2;
}

.display-4 {
	font-size: 3.5rem;
	font-weight: 300;
	line-height: 1.2;
}

hr {
	margin-top: 1rem;
	margin-bottom: 1rem;
	border: 0;
	border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
	font-size: 80%;
	font-weight: 400;
}

mark,
.mark {
	padding: 0.2em;
	background-color: #fcf8e3;
}

.list-unstyled {
	padding-left: 0;
	list-style: none;
}

.list-inline {
	padding-left: 0;
	list-style: none;
}

.list-inline-item {
	display: inline-block;
}

.list-inline-item:not(:last-child) {
	margin-right: 0.5rem;
}

.initialism {
	font-size: 90%;
	text-transform: uppercase;
}

.blockquote {
	margin-bottom: 1rem;
	font-size: 1.25rem;
}

.blockquote-footer {
	display: block;
	font-size: 80%;
	color: #6c757d;
}

.blockquote-footer::before {
	content: "\2014\00A0";
}

.img-fluid {
	max-width: 100%;
	height: auto;
}

.img-thumbnail {
	padding: 0.25rem;
	background-color: #fff;
	border: 1px solid #dee2e6;
	border-radius: 0.25rem;
	max-width: 100%;
	height: auto;
}

.figure {
	display: inline-block;
}

.figure-img {
	margin-bottom: 0.5rem;
	line-height: 1;
}

.figure-caption {
	font-size: 90%;
	color: #6c757d;
}

code {
	font-size: 87.5%;
	color: #e83e8c;
	word-break: break-word;
}

a > code {
	color: inherit;
}

kbd {
	padding: 0.2rem 0.4rem;
	font-size: 87.5%;
	color: #fff;
	background-color: #212529;
	border-radius: 0.2rem;
}

kbd kbd {
	padding: 0;
	font-size: 100%;
	font-weight: 700;
}

pre {
	display: block;
	font-size: 87.5%;
	color: #212529;
}

pre code {
	font-size: inherit;
	color: inherit;
	word-break: normal;
}

.pre-scrollable {
	max-height: 340px;
	overflow-y: scroll;
}

.container {
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
	margin-right: auto;
	margin-left: auto;
}

@media (min-width: 576px) {
	.container {
		max-width: 540px;
	}
}

@media (min-width: 768px) {
	.container {
		max-width: 720px;
	}
}

@media (min-width: 992px) {
	.container {
		max-width: 960px;
	}
}

@media (min-width: 1200px) {
	.container {
		max-width: 1140px;
	}
}

.container-fluid {
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
	margin-right: auto;
	margin-left: auto;
}

.row {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	margin-right: -15px;
	margin-left: -15px;
}

.no-gutters {
	margin-right: 0;
	margin-left: 0;
}

.no-gutters > .col,
.no-gutters > [class*="col-"] {
	padding-right: 0;
	padding-left: 0;
}

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12, .col,
.col-auto, .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12, .col-sm,
.col-sm-auto, .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12, .col-md,
.col-md-auto, .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12, .col-lg,
.col-lg-auto, .col-xl-1, .col-xl-2, .col-xl-3, .col-xl-4, .col-xl-5, .col-xl-6, .col-xl-7, .col-xl-8, .col-xl-9, .col-xl-10, .col-xl-11, .col-xl-12, .col-xl,
.col-xl-auto {
	position: relative;
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
}

.col {
	-ms-flex-preferred-size: 0;
	flex-basis: 0;
	-ms-flex-positive: 1;
	flex-grow: 1;
	max-width: 100%;
}

.col-auto {
	-ms-flex: 0 0 auto;
	flex: 0 0 auto;
	width: auto;
	max-width: 100%;
}

.col-1 {
	-ms-flex: 0 0 8.333333%;
	flex: 0 0 8.333333%;
	max-width: 8.333333%;
}

.col-2 {
	-ms-flex: 0 0 16.666667%;
	flex: 0 0 16.666667%;
	max-width: 16.666667%;
}

.col-3 {
	-ms-flex: 0 0 25%;
	flex: 0 0 25%;
	max-width: 25%;
}

.col-4 {
	-ms-flex: 0 0 33.333333%;
	flex: 0 0 33.333333%;
	max-width: 33.333333%;
}

.col-5 {
	-ms-flex: 0 0 41.666667%;
	flex: 0 0 41.666667%;
	max-width: 41.666667%;
}

.col-6 {
	-ms-flex: 0 0 50%;
	flex: 0 0 50%;
	max-width: 50%;
}

.col-7 {
	-ms-flex: 0 0 58.333333%;
	flex: 0 0 58.333333%;
	max-width: 58.333333%;
}

.col-8 {
	-ms-flex: 0 0 66.666667%;
	flex: 0 0 66.666667%;
	max-width: 66.666667%;
}

.col-9 {
	-ms-flex: 0 0 75%;
	flex: 0 0 75%;
	max-width: 75%;
}

.col-10 {
	-ms-flex: 0 0 83.333333%;
	flex: 0 0 83.333333%;
	max-width: 83.333333%;
}

.col-11 {
	-ms-flex: 0 0 91.666667%;
	flex: 0 0 91.666667%;
	max-width: 91.666667%;
}

.col-12 {
	-ms-flex: 0 0 100%;
	flex: 0 0 100%;
	max-width: 100%;
}

.order-first {
	-ms-flex-order: -1;
	order: -1;
}

.order-last {
	-ms-flex-order: 13;
	order: 13;
}

.order-0 {
	-ms-flex-order: 0;
	order: 0;
}

.order-1 {
	-ms-flex-order: 1;
	order: 1;
}

.order-2 {
	-ms-flex-order: 2;
	order: 2;
}

.order-3 {
	-ms-flex-order: 3;
	order: 3;
}

.order-4 {
	-ms-flex-order: 4;
	order: 4;
}

.order-5 {
	-ms-flex-order: 5;
	order: 5;
}

.order-6 {
	-ms-flex-order: 6;
	order: 6;
}

.order-7 {
	-ms-flex-order: 7;
	order: 7;
}

.order-8 {
	-ms-flex-order: 8;
	order: 8;
}

.order-9 {
	-ms-flex-order: 9;
	order: 9;
}

.order-10 {
	-ms-flex-order: 10;
	order: 10;
}

.order-11 {
	-ms-flex-order: 11;
	order: 11;
}

.order-12 {
	-ms-flex-order: 12;
	order: 12;
}

.offset-1 {
	margin-left: 8.333333%;
}

.offset-2 {
	margin-left: 16.666667%;
}

.offset-3 {
	margin-left: 25%;
}

.offset-4 {
	margin-left: 33.333333%;
}

.offset-5 {
	margin-left: 41.666667%;
}

.offset-6 {
	margin-left: 50%;
}

.offset-7 {
	margin-left: 58.333333%;
}

.offset-8 {
	margin-left: 66.666667%;
}

.offset-9 {
	margin-left: 75%;
}

.offset-10 {
	margin-left: 83.333333%;
}

.offset-11 {
	margin-left: 91.666667%;
}

@media (min-width: 576px) {
	.col-sm {
		-ms-flex-preferred-size: 0;
		flex-basis: 0;
		-ms-flex-positive: 1;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-sm-auto {
		-ms-flex: 0 0 auto;
		flex: 0 0 auto;
		width: auto;
		max-width: 100%;
	}
	.col-sm-1 {
		-ms-flex: 0 0 8.333333%;
		flex: 0 0 8.333333%;
		max-width: 8.333333%;
	}
	.col-sm-2 {
		-ms-flex: 0 0 16.666667%;
		flex: 0 0 16.666667%;
		max-width: 16.666667%;
	}
	.col-sm-3 {
		-ms-flex: 0 0 25%;
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-sm-4 {
		-ms-flex: 0 0 33.333333%;
		flex: 0 0 33.333333%;
		max-width: 33.333333%;
	}
	.col-sm-5 {
		-ms-flex: 0 0 41.666667%;
		flex: 0 0 41.666667%;
		max-width: 41.666667%;
	}
	.col-sm-6 {
		-ms-flex: 0 0 50%;
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-sm-7 {
		-ms-flex: 0 0 58.333333%;
		flex: 0 0 58.333333%;
		max-width: 58.333333%;
	}
	.col-sm-8 {
		-ms-flex: 0 0 66.666667%;
		flex: 0 0 66.666667%;
		max-width: 66.666667%;
	}
	.col-sm-9 {
		-ms-flex: 0 0 75%;
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-sm-10 {
		-ms-flex: 0 0 83.333333%;
		flex: 0 0 83.333333%;
		max-width: 83.333333%;
	}
	.col-sm-11 {
		-ms-flex: 0 0 91.666667%;
		flex: 0 0 91.666667%;
		max-width: 91.666667%;
	}
	.col-sm-12 {
		-ms-flex: 0 0 100%;
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-sm-first {
		-ms-flex-order: -1;
		order: -1;
	}
	.order-sm-last {
		-ms-flex-order: 13;
		order: 13;
	}
	.order-sm-0 {
		-ms-flex-order: 0;
		order: 0;
	}
	.order-sm-1 {
		-ms-flex-order: 1;
		order: 1;
	}
	.order-sm-2 {
		-ms-flex-order: 2;
		order: 2;
	}
	.order-sm-3 {
		-ms-flex-order: 3;
		order: 3;
	}
	.order-sm-4 {
		-ms-flex-order: 4;
		order: 4;
	}
	.order-sm-5 {
		-ms-flex-order: 5;
		order: 5;
	}
	.order-sm-6 {
		-ms-flex-order: 6;
		order: 6;
	}
	.order-sm-7 {
		-ms-flex-order: 7;
		order: 7;
	}
	.order-sm-8 {
		-ms-flex-order: 8;
		order: 8;
	}
	.order-sm-9 {
		-ms-flex-order: 9;
		order: 9;
	}
	.order-sm-10 {
		-ms-flex-order: 10;
		order: 10;
	}
	.order-sm-11 {
		-ms-flex-order: 11;
		order: 11;
	}
	.order-sm-12 {
		-ms-flex-order: 12;
		order: 12;
	}
	.offset-sm-0 {
		margin-left: 0;
	}
	.offset-sm-1 {
		margin-left: 8.333333%;
	}
	.offset-sm-2 {
		margin-left: 16.666667%;
	}
	.offset-sm-3 {
		margin-left: 25%;
	}
	.offset-sm-4 {
		margin-left: 33.333333%;
	}
	.offset-sm-5 {
		margin-left: 41.666667%;
	}
	.offset-sm-6 {
		margin-left: 50%;
	}
	.offset-sm-7 {
		margin-left: 58.333333%;
	}
	.offset-sm-8 {
		margin-left: 66.666667%;
	}
	.offset-sm-9 {
		margin-left: 75%;
	}
	.offset-sm-10 {
		margin-left: 83.333333%;
	}
	.offset-sm-11 {
		margin-left: 91.666667%;
	}
}

@media (min-width: 768px) {
	.col-md {
		-ms-flex-preferred-size: 0;
		flex-basis: 0;
		-ms-flex-positive: 1;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-md-auto {
		-ms-flex: 0 0 auto;
		flex: 0 0 auto;
		width: auto;
		max-width: 100%;
	}
	.col-md-1 {
		-ms-flex: 0 0 8.333333%;
		flex: 0 0 8.333333%;
		max-width: 8.333333%;
	}
	.col-md-2 {
		-ms-flex: 0 0 16.666667%;
		flex: 0 0 16.666667%;
		max-width: 16.666667%;
	}
	.col-md-3 {
		-ms-flex: 0 0 25%;
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-md-4 {
		-ms-flex: 0 0 33.333333%;
		flex: 0 0 33.333333%;
		max-width: 33.333333%;
	}
	.col-md-5 {
		-ms-flex: 0 0 41.666667%;
		flex: 0 0 41.666667%;
		max-width: 41.666667%;
	}
	.col-md-6 {
		-ms-flex: 0 0 50%;
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-md-7 {
		-ms-flex: 0 0 58.333333%;
		flex: 0 0 58.333333%;
		max-width: 58.333333%;
	}
	.col-md-8 {
		-ms-flex: 0 0 66.666667%;
		flex: 0 0 66.666667%;
		max-width: 66.666667%;
	}
	.col-md-9 {
		-ms-flex: 0 0 75%;
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-md-10 {
		-ms-flex: 0 0 83.333333%;
		flex: 0 0 83.333333%;
		max-width: 83.333333%;
	}
	.col-md-11 {
		-ms-flex: 0 0 91.666667%;
		flex: 0 0 91.666667%;
		max-width: 91.666667%;
	}
	.col-md-12 {
		-ms-flex: 0 0 100%;
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-md-first {
		-ms-flex-order: -1;
		order: -1;
	}
	.order-md-last {
		-ms-flex-order: 13;
		order: 13;
	}
	.order-md-0 {
		-ms-flex-order: 0;
		order: 0;
	}
	.order-md-1 {
		-ms-flex-order: 1;
		order: 1;
	}
	.order-md-2 {
		-ms-flex-order: 2;
		order: 2;
	}
	.order-md-3 {
		-ms-flex-order: 3;
		order: 3;
	}
	.order-md-4 {
		-ms-flex-order: 4;
		order: 4;
	}
	.order-md-5 {
		-ms-flex-order: 5;
		order: 5;
	}
	.order-md-6 {
		-ms-flex-order: 6;
		order: 6;
	}
	.order-md-7 {
		-ms-flex-order: 7;
		order: 7;
	}
	.order-md-8 {
		-ms-flex-order: 8;
		order: 8;
	}
	.order-md-9 {
		-ms-flex-order: 9;
		order: 9;
	}
	.order-md-10 {
		-ms-flex-order: 10;
		order: 10;
	}
	.order-md-11 {
		-ms-flex-order: 11;
		order: 11;
	}
	.order-md-12 {
		-ms-flex-order: 12;
		order: 12;
	}
	.offset-md-0 {
		margin-left: 0;
	}
	.offset-md-1 {
		margin-left: 8.333333%;
	}
	.offset-md-2 {
		margin-left: 16.666667%;
	}
	.offset-md-3 {
		margin-left: 25%;
	}
	.offset-md-4 {
		margin-left: 33.333333%;
	}
	.offset-md-5 {
		margin-left: 41.666667%;
	}
	.offset-md-6 {
		margin-left: 50%;
	}
	.offset-md-7 {
		margin-left: 58.333333%;
	}
	.offset-md-8 {
		margin-left: 66.666667%;
	}
	.offset-md-9 {
		margin-left: 75%;
	}
	.offset-md-10 {
		margin-left: 83.333333%;
	}
	.offset-md-11 {
		margin-left: 91.666667%;
	}
}

@media (min-width: 992px) {
	.col-lg {
		-ms-flex-preferred-size: 0;
		flex-basis: 0;
		-ms-flex-positive: 1;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-lg-auto {
		-ms-flex: 0 0 auto;
		flex: 0 0 auto;
		width: auto;
		max-width: 100%;
	}
	.col-lg-1 {
		-ms-flex: 0 0 8.333333%;
		flex: 0 0 8.333333%;
		max-width: 8.333333%;
	}
	.col-lg-2 {
		-ms-flex: 0 0 16.666667%;
		flex: 0 0 16.666667%;
		max-width: 16.666667%;
	}
	.col-lg-3 {
		-ms-flex: 0 0 25%;
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-lg-4 {
		-ms-flex: 0 0 33.333333%;
		flex: 0 0 33.333333%;
		max-width: 33.333333%;
	}
	.col-lg-5 {
		-ms-flex: 0 0 41.666667%;
		flex: 0 0 41.666667%;
		max-width: 41.666667%;
	}
	.col-lg-6 {
		-ms-flex: 0 0 50%;
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-lg-7 {
		-ms-flex: 0 0 58.333333%;
		flex: 0 0 58.333333%;
		max-width: 58.333333%;
	}
	.col-lg-8 {
		-ms-flex: 0 0 66.666667%;
		flex: 0 0 66.666667%;
		max-width: 66.666667%;
	}
	.col-lg-9 {
		-ms-flex: 0 0 75%;
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-lg-10 {
		-ms-flex: 0 0 83.333333%;
		flex: 0 0 83.333333%;
		max-width: 83.333333%;
	}
	.col-lg-11 {
		-ms-flex: 0 0 91.666667%;
		flex: 0 0 91.666667%;
		max-width: 91.666667%;
	}
	.col-lg-12 {
		-ms-flex: 0 0 100%;
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-lg-first {
		-ms-flex-order: -1;
		order: -1;
	}
	.order-lg-last {
		-ms-flex-order: 13;
		order: 13;
	}
	.order-lg-0 {
		-ms-flex-order: 0;
		order: 0;
	}
	.order-lg-1 {
		-ms-flex-order: 1;
		order: 1;
	}
	.order-lg-2 {
		-ms-flex-order: 2;
		order: 2;
	}
	.order-lg-3 {
		-ms-flex-order: 3;
		order: 3;
	}
	.order-lg-4 {
		-ms-flex-order: 4;
		order: 4;
	}
	.order-lg-5 {
		-ms-flex-order: 5;
		order: 5;
	}
	.order-lg-6 {
		-ms-flex-order: 6;
		order: 6;
	}
	.order-lg-7 {
		-ms-flex-order: 7;
		order: 7;
	}
	.order-lg-8 {
		-ms-flex-order: 8;
		order: 8;
	}
	.order-lg-9 {
		-ms-flex-order: 9;
		order: 9;
	}
	.order-lg-10 {
		-ms-flex-order: 10;
		order: 10;
	}
	.order-lg-11 {
		-ms-flex-order: 11;
		order: 11;
	}
	.order-lg-12 {
		-ms-flex-order: 12;
		order: 12;
	}
	.offset-lg-0 {
		margin-left: 0;
	}
	.offset-lg-1 {
		margin-left: 8.333333%;
	}
	.offset-lg-2 {
		margin-left: 16.666667%;
	}
	.offset-lg-3 {
		margin-left: 25%;
	}
	.offset-lg-4 {
		margin-left: 33.333333%;
	}
	.offset-lg-5 {
		margin-left: 41.666667%;
	}
	.offset-lg-6 {
		margin-left: 50%;
	}
	.offset-lg-7 {
		margin-left: 58.333333%;
	}
	.offset-lg-8 {
		margin-left: 66.666667%;
	}
	.offset-lg-9 {
		margin-left: 75%;
	}
	.offset-lg-10 {
		margin-left: 83.333333%;
	}
	.offset-lg-11 {
		margin-left: 91.666667%;
	}
}

@media (min-width: 1200px) {
	.col-xl {
		-ms-flex-preferred-size: 0;
		flex-basis: 0;
		-ms-flex-positive: 1;
		flex-grow: 1;
		max-width: 100%;
	}
	.col-xl-auto {
		-ms-flex: 0 0 auto;
		flex: 0 0 auto;
		width: auto;
		max-width: 100%;
	}
	.col-xl-1 {
		-ms-flex: 0 0 8.333333%;
		flex: 0 0 8.333333%;
		max-width: 8.333333%;
	}
	.col-xl-2 {
		-ms-flex: 0 0 16.666667%;
		flex: 0 0 16.666667%;
		max-width: 16.666667%;
	}
	.col-xl-3 {
		-ms-flex: 0 0 25%;
		flex: 0 0 25%;
		max-width: 25%;
	}
	.col-xl-4 {
		-ms-flex: 0 0 33.333333%;
		flex: 0 0 33.333333%;
		max-width: 33.333333%;
	}
	.col-xl-5 {
		-ms-flex: 0 0 41.666667%;
		flex: 0 0 41.666667%;
		max-width: 41.666667%;
	}
	.col-xl-6 {
		-ms-flex: 0 0 50%;
		flex: 0 0 50%;
		max-width: 50%;
	}
	.col-xl-7 {
		-ms-flex: 0 0 58.333333%;
		flex: 0 0 58.333333%;
		max-width: 58.333333%;
	}
	.col-xl-8 {
		-ms-flex: 0 0 66.666667%;
		flex: 0 0 66.666667%;
		max-width: 66.666667%;
	}
	.col-xl-9 {
		-ms-flex: 0 0 75%;
		flex: 0 0 75%;
		max-width: 75%;
	}
	.col-xl-10 {
		-ms-flex: 0 0 83.333333%;
		flex: 0 0 83.333333%;
		max-width: 83.333333%;
	}
	.col-xl-11 {
		-ms-flex: 0 0 91.666667%;
		flex: 0 0 91.666667%;
		max-width: 91.666667%;
	}
	.col-xl-12 {
		-ms-flex: 0 0 100%;
		flex: 0 0 100%;
		max-width: 100%;
	}
	.order-xl-first {
		-ms-flex-order: -1;
		order: -1;
	}
	.order-xl-last {
		-ms-flex-order: 13;
		order: 13;
	}
	.order-xl-0 {
		-ms-flex-order: 0;
		order: 0;
	}
	.order-xl-1 {
		-ms-flex-order: 1;
		order: 1;
	}
	.order-xl-2 {
		-ms-flex-order: 2;
		order: 2;
	}
	.order-xl-3 {
		-ms-flex-order: 3;
		order: 3;
	}
	.order-xl-4 {
		-ms-flex-order: 4;
		order: 4;
	}
	.order-xl-5 {
		-ms-flex-order: 5;
		order: 5;
	}
	.order-xl-6 {
		-ms-flex-order: 6;
		order: 6;
	}
	.order-xl-7 {
		-ms-flex-order: 7;
		order: 7;
	}
	.order-xl-8 {
		-ms-flex-order: 8;
		order: 8;
	}
	.order-xl-9 {
		-ms-flex-order: 9;
		order: 9;
	}
	.order-xl-10 {
		-ms-flex-order: 10;
		order: 10;
	}
	.order-xl-11 {
		-ms-flex-order: 11;
		order: 11;
	}
	.order-xl-12 {
		-ms-flex-order: 12;
		order: 12;
	}
	.offset-xl-0 {
		margin-left: 0;
	}
	.offset-xl-1 {
		margin-left: 8.333333%;
	}
	.offset-xl-2 {
		margin-left: 16.666667%;
	}
	.offset-xl-3 {
		margin-left: 25%;
	}
	.offset-xl-4 {
		margin-left: 33.333333%;
	}
	.offset-xl-5 {
		margin-left: 41.666667%;
	}
	.offset-xl-6 {
		margin-left: 50%;
	}
	.offset-xl-7 {
		margin-left: 58.333333%;
	}
	.offset-xl-8 {
		margin-left: 66.666667%;
	}
	.offset-xl-9 {
		margin-left: 75%;
	}
	.offset-xl-10 {
		margin-left: 83.333333%;
	}
	.offset-xl-11 {
		margin-left: 91.666667%;
	}
}

.table {
	width: 100%;
	margin-bottom: 1rem;
	background-color: transparent;
}

.table th,
.table td {
	padding: 0.75rem;
	vertical-align: top;
	border-top: 1px solid #dee2e6;
}

.table thead th {
	vertical-align: bottom;
	border-bottom: 2px solid #dee2e6;
}

.table tbody + tbody {
	border-top: 2px solid #dee2e6;
}

.table .table {
	background-color: #fff;
}

.table-sm th,
.table-sm td {
	padding: 0.3rem;
}

.table-bordered {
	border: 1px solid #dee2e6;
}

.table-bordered th,
.table-bordered td {
	border: 1px solid #dee2e6;
}

.table-bordered thead th,
.table-bordered thead td {
	border-bottom-width: 2px;
}

.table-borderless th,
.table-borderless td,
.table-borderless thead th,
.table-borderless tbody + tbody {
	border: 0;
}

.table-striped tbody tr:nth-of-type(odd) {
	background-color: rgba(0, 0, 0, 0.05);
}

.table-hover tbody tr:hover {
	background-color: rgba(0, 0, 0, 0.075);
}

.table-primary,
.table-primary > th,
.table-primary > td {
	background-color: #b8daff;
}

.table-primary th,
.table-primary td,
.table-primary thead th,
.table-primary tbody + tbody {
	border-color: #7abaff;
}

.table-hover .table-primary:hover {
	background-color: #9fcdff;
}

.table-hover .table-primary:hover > td,
.table-hover .table-primary:hover > th {
	background-color: #9fcdff;
}

.table-secondary,
.table-secondary > th,
.table-secondary > td {
	background-color: #d6d8db;
}

.table-secondary th,
.table-secondary td,
.table-secondary thead th,
.table-secondary tbody + tbody {
	border-color: #b3b7bb;
}

.table-hover .table-secondary:hover {
	background-color: #c8cbcf;
}

.table-hover .table-secondary:hover > td,
.table-hover .table-secondary:hover > th {
	background-color: #c8cbcf;
}

.table-success,
.table-success > th,
.table-success > td {
	background-color: #c3e6cb;
}

.table-success th,
.table-success td,
.table-success thead th,
.table-success tbody + tbody {
	border-color: #8fd19e;
}

.table-hover .table-success:hover {
	background-color: #b1dfbb;
}

.table-hover .table-success:hover > td,
.table-hover .table-success:hover > th {
	background-color: #b1dfbb;
}

.table-info,
.table-info > th,
.table-info > td {
	background-color: #bee5eb;
}

.table-info th,
.table-info td,
.table-info thead th,
.table-info tbody + tbody {
	border-color: #86cfda;
}

.table-hover .table-info:hover {
	background-color: #abdde5;
}

.table-hover .table-info:hover > td,
.table-hover .table-info:hover > th {
	background-color: #abdde5;
}

.table-warning,
.table-warning > th,
.table-warning > td {
	background-color: #ffeeba;
}

.table-warning th,
.table-warning td,
.table-warning thead th,
.table-warning tbody + tbody {
	border-color: #ffdf7e;
}

.table-hover .table-warning:hover {
	background-color: #ffe8a1;
}

.table-hover .table-warning:hover > td,
.table-hover .table-warning:hover > th {
	background-color: #ffe8a1;
}

.table-danger,
.table-danger > th,
.table-danger > td {
	background-color: #f5c6cb;
}

.table-danger th,
.table-danger td,
.table-danger thead th,
.table-danger tbody + tbody {
	border-color: #ed969e;
}

.table-hover .table-danger:hover {
	background-color: #f1b0b7;
}

.table-hover .table-danger:hover > td,
.table-hover .table-danger:hover > th {
	background-color: #f1b0b7;
}

.table-light,
.table-light > th,
.table-light > td {
	background-color: #fdfdfe;
}

.table-light th,
.table-light td,
.table-light thead th,
.table-light tbody + tbody {
	border-color: #fbfcfc;
}

.table-hover .table-light:hover {
	background-color: #ececf6;
}

.table-hover .table-light:hover > td,
.table-hover .table-light:hover > th {
	background-color: #ececf6;
}

.table-dark,
.table-dark > th,
.table-dark > td {
	background-color: #c6c8ca;
}

.table-dark th,
.table-dark td,
.table-dark thead th,
.table-dark tbody + tbody {
	border-color: #95999c;
}

.table-hover .table-dark:hover {
	background-color: #b9bbbe;
}

.table-hover .table-dark:hover > td,
.table-hover .table-dark:hover > th {
	background-color: #b9bbbe;
}

.table-active,
.table-active > th,
.table-active > td {
	background-color: rgba(0, 0, 0, 0.075);
}

.table-hover .table-active:hover {
	background-color: rgba(0, 0, 0, 0.075);
}

.table-hover .table-active:hover > td,
.table-hover .table-active:hover > th {
	background-color: rgba(0, 0, 0, 0.075);
}

.table .thead-dark th {
	color: #fff;
	background-color: #212529;
	border-color: #32383e;
}

.table .thead-light th {
	color: #495057;
	background-color: #e9ecef;
	border-color: #dee2e6;
}

.table-dark {
	color: #fff;
	background-color: #212529;
}

.table-dark th,
.table-dark td,
.table-dark thead th {
	border-color: #32383e;
}

.table-dark.table-bordered {
	border: 0;
}

.table-dark.table-striped tbody tr:nth-of-type(odd) {
	background-color: rgba(255, 255, 255, 0.05);
}

.table-dark.table-hover tbody tr:hover {
	background-color: rgba(255, 255, 255, 0.075);
}

@media (max-width: 575.98px) {
	.table-responsive-sm {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-sm > .table-bordered {
		border: 0;
	}
}

@media (max-width: 767.98px) {
	.table-responsive-md {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-md > .table-bordered {
		border: 0;
	}
}

@media (max-width: 991.98px) {
	.table-responsive-lg {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-lg > .table-bordered {
		border: 0;
	}
}

@media (max-width: 1199.98px) {
	.table-responsive-xl {
		display: block;
		width: 100%;
		overflow-x: auto;
		-webkit-overflow-scrolling: touch;
		-ms-overflow-style: -ms-autohiding-scrollbar;
	}
	.table-responsive-xl > .table-bordered {
		border: 0;
	}
}

.table-responsive {
	display: block;
	width: 100%;
	overflow-x: auto;
	-webkit-overflow-scrolling: touch;
	-ms-overflow-style: -ms-autohiding-scrollbar;
}

.table-responsive > .table-bordered {
	border: 0;
}

.form-control {
	display: block;
	width: 100%;
	height: calc(2.25rem + 2px);
	padding: 0.375rem 0.75rem;
	font-size: 1rem;
	font-weight: 400;
	line-height: 1.5;
	color: #495057;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
	transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

@media screen and (prefers-reduced-motion: reduce) {
	.form-control {
		transition: none;
	}
}

.form-control::-ms-expand {
	background-color: transparent;
	border: 0;
}

.form-control:focus {
	color: #495057;
	background-color: #fff;
	border-color: #80bdff;
	outline: 0;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.form-control::-webkit-input-placeholder {
	color: #6c757d;
	opacity: 1;
}

.form-control::-moz-placeholder {
	color: #6c757d;
	opacity: 1;
}

.form-control:-ms-input-placeholder {
	color: #6c757d;
	opacity: 1;
}

.form-control::-ms-input-placeholder {
	color: #6c757d;
	opacity: 1;
}

.form-control::placeholder {
	color: #6c757d;
	opacity: 1;
}

.form-control:disabled, .form-control[readonly] {
	background-color: #e9ecef;
	opacity: 1;
}

select.form-control:focus::-ms-value {
	color: #495057;
	background-color: #fff;
}

.form-control-file,
.form-control-range {
	display: block;
	width: 100%;
}

.col-form-label {
	padding-top: calc(0.375rem + 1px);
	padding-bottom: calc(0.375rem + 1px);
	margin-bottom: 0;
	font-size: inherit;
	line-height: 1.5;
}

.col-form-label-lg {
	padding-top: calc(0.5rem + 1px);
	padding-bottom: calc(0.5rem + 1px);
	font-size: 1.25rem;
	line-height: 1.5;
}

.col-form-label-sm {
	padding-top: calc(0.25rem + 1px);
	padding-bottom: calc(0.25rem + 1px);
	font-size: 0.875rem;
	line-height: 1.5;
}

.form-control-plaintext {
	display: block;
	width: 100%;
	padding-top: 0.375rem;
	padding-bottom: 0.375rem;
	margin-bottom: 0;
	line-height: 1.5;
	color: #212529;
	background-color: transparent;
	border: solid transparent;
	border-width: 1px 0;
}

.form-control-plaintext.form-control-sm, .form-control-plaintext.form-control-lg {
	padding-right: 0;
	padding-left: 0;
}

.form-control-sm {
	height: calc(1.8125rem + 2px);
	padding: 0.25rem 0.5rem;
	font-size: 0.875rem;
	line-height: 1.5;
	border-radius: 0.2rem;
}

.form-control-lg {
	height: calc(2.875rem + 2px);
	padding: 0.5rem 1rem;
	font-size: 1.25rem;
	line-height: 1.5;
	border-radius: 0.3rem;
}

select.form-control[size], select.form-control[multiple] {
	height: auto;
}

textarea.form-control {
	height: auto;
}

.form-group {
	margin-bottom: 1rem;
}

.form-text {
	display: block;
	margin-top: 0.25rem;
}

.form-row {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	margin-right: -5px;
	margin-left: -5px;
}

.form-row > .col,
.form-row > [class*="col-"] {
	padding-right: 5px;
	padding-left: 5px;
}

.form-check {
	position: relative;
	display: block;
	padding-left: 1.25rem;
}

.form-check-input {
	position: absolute;
	margin-top: 0.3rem;
	margin-left: -1.25rem;
}

.form-check-input:disabled ~ .form-check-label {
	color: #6c757d;
}

.form-check-label {
	margin-bottom: 0;
}

.form-check-inline {
	display: -ms-inline-flexbox;
	display: inline-flex;
	-ms-flex-align: center;
	align-items: center;
	padding-left: 0;
	margin-right: 0.75rem;
}

.form-check-inline .form-check-input {
	position: static;
	margin-top: 0;
	margin-right: 0.3125rem;
	margin-left: 0;
}

.valid-feedback {
	display: none;
	width: 100%;
	margin-top: 0.25rem;
	font-size: 80%;
	color: #28a745;
}

.valid-tooltip {
	position: absolute;
	top: 100%;
	z-index: 5;
	display: none;
	max-width: 100%;
	padding: 0.25rem 0.5rem;
	margin-top: .1rem;
	font-size: 0.875rem;
	line-height: 1.5;
	color: #fff;
	background-color: rgba(40, 167, 69, 0.9);
	border-radius: 0.25rem;
}

.was-validated .form-control:valid, .form-control.is-valid {
	border-color: #28a745;
	padding-right: 2.25rem;
	background-repeat: no-repeat;
	background-position: center right calc(2.25rem / 4);
	background-size: calc(2.25rem / 2) calc(2.25rem / 2);
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%2328a745' d='M2.3 6.73L.6 4.53c-.4-1.04.46-1.4 1.1-.8l1.1 1.4 3.4-3.8c.6-.63 1.6-.27 1.2.7l-4 4.6c-.43.5-.8.4-1.1.1z'/%3e%3c/svg%3e");
}

.was-validated .form-control:valid:focus, .form-control.is-valid:focus {
	border-color: #28a745;
	box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.25);
}

.was-validated .form-control:valid ~ .valid-feedback,
.was-validated .form-control:valid ~ .valid-tooltip, .form-control.is-valid ~ .valid-feedback,
.form-control.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated textarea.form-control:valid, textarea.form-control.is-valid {
	padding-right: 2.25rem;
	background-position: top calc(2.25rem / 4) right calc(2.25rem / 4);
}

.was-validated .custom-select:valid, .custom-select.is-valid {
	border-color: #28a745;
	padding-right: 3.4375rem;
	background: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3e%3cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3e%3c/svg%3e") no-repeat right 0.75rem center/8px 10px, url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%2328a745' d='M2.3 6.73L.6 4.53c-.4-1.04.46-1.4 1.1-.8l1.1 1.4 3.4-3.8c.6-.63 1.6-.27 1.2.7l-4 4.6c-.43.5-.8.4-1.1.1z'/%3e%3c/svg%3e") no-repeat center right 1.75rem/1.125rem 1.125rem;
}

.was-validated .custom-select:valid:focus, .custom-select.is-valid:focus {
	border-color: #28a745;
	box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.25);
}

.was-validated .custom-select:valid ~ .valid-feedback,
.was-validated .custom-select:valid ~ .valid-tooltip, .custom-select.is-valid ~ .valid-feedback,
.custom-select.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .form-control-file:valid ~ .valid-feedback,
.was-validated .form-control-file:valid ~ .valid-tooltip, .form-control-file.is-valid ~ .valid-feedback,
.form-control-file.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .form-check-input:valid ~ .form-check-label, .form-check-input.is-valid ~ .form-check-label {
	color: #28a745;
}

.was-validated .form-check-input:valid ~ .valid-feedback,
.was-validated .form-check-input:valid ~ .valid-tooltip, .form-check-input.is-valid ~ .valid-feedback,
.form-check-input.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .custom-control-input:valid ~ .custom-control-label, .custom-control-input.is-valid ~ .custom-control-label {
	color: #28a745;
}

.was-validated .custom-control-input:valid ~ .custom-control-label::before, .custom-control-input.is-valid ~ .custom-control-label::before {
	border-color: #28a745;
}

.was-validated .custom-control-input:valid ~ .valid-feedback,
.was-validated .custom-control-input:valid ~ .valid-tooltip, .custom-control-input.is-valid ~ .valid-feedback,
.custom-control-input.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .custom-control-input:valid:checked ~ .custom-control-label::before, .custom-control-input.is-valid:checked ~ .custom-control-label::before {
	border-color: #34ce57;
	background-color: #34ce57;
}

.was-validated .custom-control-input:valid:focus ~ .custom-control-label::before, .custom-control-input.is-valid:focus ~ .custom-control-label::before {
	box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.25);
}

.was-validated .custom-control-input:valid:focus:not(:checked) ~ .custom-control-label::before, .custom-control-input.is-valid:focus:not(:checked) ~ .custom-control-label::before {
	border-color: #28a745;
}

.was-validated .custom-file-input:valid ~ .custom-file-label, .custom-file-input.is-valid ~ .custom-file-label {
	border-color: #28a745;
}

.was-validated .custom-file-input:valid ~ .valid-feedback,
.was-validated .custom-file-input:valid ~ .valid-tooltip, .custom-file-input.is-valid ~ .valid-feedback,
.custom-file-input.is-valid ~ .valid-tooltip {
	display: block;
}

.was-validated .custom-file-input:valid:focus ~ .custom-file-label, .custom-file-input.is-valid:focus ~ .custom-file-label {
	border-color: #28a745;
	box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.25);
}

.invalid-feedback {
	display: none;
	width: 100%;
	margin-top: 0.25rem;
	font-size: 80%;
	color: #dc3545;
}

.invalid-tooltip {
	position: absolute;
	top: 100%;
	z-index: 5;
	display: none;
	max-width: 100%;
	padding: 0.25rem 0.5rem;
	margin-top: .1rem;
	font-size: 0.875rem;
	line-height: 1.5;
	color: #fff;
	background-color: rgba(220, 53, 69, 0.9);
	border-radius: 0.25rem;
}

.was-validated .form-control:invalid, .form-control.is-invalid {
	border-color: #dc3545;
	padding-right: 2.25rem;
	background-repeat: no-repeat;
	background-position: center right calc(2.25rem / 4);
	background-size: calc(2.25rem / 2) calc(2.25rem / 2);
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23dc3545' viewBox='-2 -2 7 7'%3e%3cpath stroke='%23d9534f' d='M0 0l3 3m0-3L0 3'/%3e%3ccircle r='.5'/%3e%3ccircle cx='3' r='.5'/%3e%3ccircle cy='3' r='.5'/%3e%3ccircle cx='3' cy='3' r='.5'/%3e%3c/svg%3E");
}

.was-validated .form-control:invalid:focus, .form-control.is-invalid:focus {
	border-color: #dc3545;
	box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.25);
}

.was-validated .form-control:invalid ~ .invalid-feedback,
.was-validated .form-control:invalid ~ .invalid-tooltip, .form-control.is-invalid ~ .invalid-feedback,
.form-control.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated textarea.form-control:invalid, textarea.form-control.is-invalid {
	padding-right: 2.25rem;
	background-position: top calc(2.25rem / 4) right calc(2.25rem / 4);
}

.was-validated .custom-select:invalid, .custom-select.is-invalid {
	border-color: #dc3545;
	padding-right: 3.4375rem;
	background: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3e%3cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3e%3c/svg%3e") no-repeat right 0.75rem center/8px 10px, url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23dc3545' viewBox='-2 -2 7 7'%3e%3cpath stroke='%23d9534f' d='M0 0l3 3m0-3L0 3'/%3e%3ccircle r='.5'/%3e%3ccircle cx='3' r='.5'/%3e%3ccircle cy='3' r='.5'/%3e%3ccircle cx='3' cy='3' r='.5'/%3e%3c/svg%3E") no-repeat center right 1.75rem/1.125rem 1.125rem;
}

.was-validated .custom-select:invalid:focus, .custom-select.is-invalid:focus {
	border-color: #dc3545;
	box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.25);
}

.was-validated .custom-select:invalid ~ .invalid-feedback,
.was-validated .custom-select:invalid ~ .invalid-tooltip, .custom-select.is-invalid ~ .invalid-feedback,
.custom-select.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .form-control-file:invalid ~ .invalid-feedback,
.was-validated .form-control-file:invalid ~ .invalid-tooltip, .form-control-file.is-invalid ~ .invalid-feedback,
.form-control-file.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .form-check-input:invalid ~ .form-check-label, .form-check-input.is-invalid ~ .form-check-label {
	color: #dc3545;
}

.was-validated .form-check-input:invalid ~ .invalid-feedback,
.was-validated .form-check-input:invalid ~ .invalid-tooltip, .form-check-input.is-invalid ~ .invalid-feedback,
.form-check-input.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .custom-control-input:invalid ~ .custom-control-label, .custom-control-input.is-invalid ~ .custom-control-label {
	color: #dc3545;
}

.was-validated .custom-control-input:invalid ~ .custom-control-label::before, .custom-control-input.is-invalid ~ .custom-control-label::before {
	border-color: #dc3545;
}

.was-validated .custom-control-input:invalid ~ .invalid-feedback,
.was-validated .custom-control-input:invalid ~ .invalid-tooltip, .custom-control-input.is-invalid ~ .invalid-feedback,
.custom-control-input.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .custom-control-input:invalid:checked ~ .custom-control-label::before, .custom-control-input.is-invalid:checked ~ .custom-control-label::before {
	border-color: #e4606d;
	background-color: #e4606d;
}

.was-validated .custom-control-input:invalid:focus ~ .custom-control-label::before, .custom-control-input.is-invalid:focus ~ .custom-control-label::before {
	box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.25);
}

.was-validated .custom-control-input:invalid:focus:not(:checked) ~ .custom-control-label::before, .custom-control-input.is-invalid:focus:not(:checked) ~ .custom-control-label::before {
	border-color: #dc3545;
}

.was-validated .custom-file-input:invalid ~ .custom-file-label, .custom-file-input.is-invalid ~ .custom-file-label {
	border-color: #dc3545;
}

.was-validated .custom-file-input:invalid ~ .invalid-feedback,
.was-validated .custom-file-input:invalid ~ .invalid-tooltip, .custom-file-input.is-invalid ~ .invalid-feedback,
.custom-file-input.is-invalid ~ .invalid-tooltip {
	display: block;
}

.was-validated .custom-file-input:invalid:focus ~ .custom-file-label, .custom-file-input.is-invalid:focus ~ .custom-file-label {
	border-color: #dc3545;
	box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.25);
}

.form-inline {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-flow: row wrap;
	flex-flow: row wrap;
	-ms-flex-align: center;
	align-items: center;
}

.form-inline .form-check {
	width: 100%;
}

@media (min-width: 576px) {
	.form-inline label {
		display: -ms-flexbox;
		display: flex;
		-ms-flex-align: center;
		align-items: center;
		-ms-flex-pack: center;
		justify-content: center;
		margin-bottom: 0;
	}
	.form-inline .form-group {
		display: -ms-flexbox;
		display: flex;
		-ms-flex: 0 0 auto;
		flex: 0 0 auto;
		-ms-flex-flow: row wrap;
		flex-flow: row wrap;
		-ms-flex-align: center;
		align-items: center;
		margin-bottom: 0;
	}
	.form-inline .form-control {
		display: inline-block;
		width: auto;
		vertical-align: middle;
	}
	.form-inline .form-control-plaintext {
		display: inline-block;
	}
	.form-inline .input-group,
	.form-inline .custom-select {
		width: auto;
	}
	.form-inline .form-check {
		display: -ms-flexbox;
		display: flex;
		-ms-flex-align: center;
		align-items: center;
		-ms-flex-pack: center;
		justify-content: center;
		width: auto;
		padding-left: 0;
	}
	.form-inline .form-check-input {
		position: relative;
		margin-top: 0;
		margin-right: 0.25rem;
		margin-left: 0;
	}
	.form-inline .custom-control {
		-ms-flex-align: center;
		align-items: center;
		-ms-flex-pack: center;
		justify-content: center;
	}
	.form-inline .custom-control-label {
		margin-bottom: 0;
	}
}

.btn {
	display: inline-block;
	font-weight: 400;
	color: #212529;
	text-align: center;
	vertical-align: middle;
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	background-color: transparent;
	border: 1px solid transparent;
	padding: 0.375rem 0.75rem;
	font-size: 1rem;
	line-height: 1.5;
	border-radius: 0.25rem;
	transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

@media screen and (prefers-reduced-motion: reduce) {
	.btn {
		transition: none;
	}
}

.btn:hover {
	color: #212529;
	text-decoration: none;
}

.btn:focus, .btn.focus {
	outline: 0;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.btn.disabled, .btn:disabled {
	opacity: 0.65;
}

.btn:not(:disabled):not(.disabled) {
	cursor: pointer;
}

a.btn.disabled,
fieldset:disabled a.btn {
	pointer-events: none;
}

.btn-primary {
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.btn-primary:hover {
	color: #fff;
	background-color: #0069d9;
	border-color: #0062cc;
}

.btn-primary:focus, .btn-primary.focus {
	box-shadow: 0 0 0 0.2rem rgba(38, 143, 255, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.btn-primary:not(:disabled):not(.disabled):active, .btn-primary:not(:disabled):not(.disabled).active,
.show > .btn-primary.dropdown-toggle {
	color: #fff;
	background-color: #0062cc;
	border-color: #005cbf;
}

.btn-primary:not(:disabled):not(.disabled):active:focus, .btn-primary:not(:disabled):not(.disabled).active:focus,
.show > .btn-primary.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(38, 143, 255, 0.5);
}

.btn-secondary {
	color: #fff;
	background-color: #6c757d;
	border-color: #6c757d;
}

.btn-secondary:hover {
	color: #fff;
	background-color: #5a6268;
	border-color: #545b62;
}

.btn-secondary:focus, .btn-secondary.focus {
	box-shadow: 0 0 0 0.2rem rgba(130, 138, 145, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
	color: #fff;
	background-color: #6c757d;
	border-color: #6c757d;
}

.btn-secondary:not(:disabled):not(.disabled):active, .btn-secondary:not(:disabled):not(.disabled).active,
.show > .btn-secondary.dropdown-toggle {
	color: #fff;
	background-color: #545b62;
	border-color: #4e555b;
}

.btn-secondary:not(:disabled):not(.disabled):active:focus, .btn-secondary:not(:disabled):not(.disabled).active:focus,
.show > .btn-secondary.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(130, 138, 145, 0.5);
}

.btn-success {
	color: #fff;
	background-color: #28a745;
	border-color: #28a745;
}

.btn-success:hover {
	color: #fff;
	background-color: #218838;
	border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
	box-shadow: 0 0 0 0.2rem rgba(72, 180, 97, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
	color: #fff;
	background-color: #28a745;
	border-color: #28a745;
}

.btn-success:not(:disabled):not(.disabled):active, .btn-success:not(:disabled):not(.disabled).active,
.show > .btn-success.dropdown-toggle {
	color: #fff;
	background-color: #1e7e34;
	border-color: #1c7430;
}

.btn-success:not(:disabled):not(.disabled):active:focus, .btn-success:not(:disabled):not(.disabled).active:focus,
.show > .btn-success.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(72, 180, 97, 0.5);
}

.btn-info {
	color: #fff;
	background-color: #17a2b8;
	border-color: #17a2b8;
}

.btn-info:hover {
	color: #fff;
	background-color: #138496;
	border-color: #117a8b;
}

.btn-info:focus, .btn-info.focus {
	box-shadow: 0 0 0 0.2rem rgba(58, 176, 195, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
	color: #fff;
	background-color: #17a2b8;
	border-color: #17a2b8;
}

.btn-info:not(:disabled):not(.disabled):active, .btn-info:not(:disabled):not(.disabled).active,
.show > .btn-info.dropdown-toggle {
	color: #fff;
	background-color: #117a8b;
	border-color: #10707f;
}

.btn-info:not(:disabled):not(.disabled):active:focus, .btn-info:not(:disabled):not(.disabled).active:focus,
.show > .btn-info.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(58, 176, 195, 0.5);
}

.btn-warning {
	color: #212529;
	background-color: #ffc107;
	border-color: #ffc107;
}

.btn-warning:hover {
	color: #212529;
	background-color: #e0a800;
	border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
	box-shadow: 0 0 0 0.2rem rgba(222, 170, 12, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
	color: #212529;
	background-color: #ffc107;
	border-color: #ffc107;
}

.btn-warning:not(:disabled):not(.disabled):active, .btn-warning:not(:disabled):not(.disabled).active,
.show > .btn-warning.dropdown-toggle {
	color: #212529;
	background-color: #d39e00;
	border-color: #c69500;
}

.btn-warning:not(:disabled):not(.disabled):active:focus, .btn-warning:not(:disabled):not(.disabled).active:focus,
.show > .btn-warning.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(222, 170, 12, 0.5);
}

.btn-danger {
	color: #fff;
	background-color: #dc3545;
	border-color: #dc3545;
}

.btn-danger:hover {
	color: #fff;
	background-color: #c82333;
	border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
	box-shadow: 0 0 0 0.2rem rgba(225, 83, 97, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
	color: #fff;
	background-color: #dc3545;
	border-color: #dc3545;
}

.btn-danger:not(:disabled):not(.disabled):active, .btn-danger:not(:disabled):not(.disabled).active,
.show > .btn-danger.dropdown-toggle {
	color: #fff;
	background-color: #bd2130;
	border-color: #b21f2d;
}

.btn-danger:not(:disabled):not(.disabled):active:focus, .btn-danger:not(:disabled):not(.disabled).active:focus,
.show > .btn-danger.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(225, 83, 97, 0.5);
}

.btn-light {
	color: #212529;
	background-color: #f8f9fa;
	border-color: #f8f9fa;
}

.btn-light:hover {
	color: #212529;
	background-color: #e2e6ea;
	border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
	box-shadow: 0 0 0 0.2rem rgba(216, 217, 219, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
	color: #212529;
	background-color: #f8f9fa;
	border-color: #f8f9fa;
}

.btn-light:not(:disabled):not(.disabled):active, .btn-light:not(:disabled):not(.disabled).active,
.show > .btn-light.dropdown-toggle {
	color: #212529;
	background-color: #dae0e5;
	border-color: #d3d9df;
}

.btn-light:not(:disabled):not(.disabled):active:focus, .btn-light:not(:disabled):not(.disabled).active:focus,
.show > .btn-light.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(216, 217, 219, 0.5);
}

.btn-dark {
	color: #fff;
	background-color: #343a40;
	border-color: #343a40;
}

.btn-dark:hover {
	color: #fff;
	background-color: #23272b;
	border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
	box-shadow: 0 0 0 0.2rem rgba(82, 88, 93, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
	color: #fff;
	background-color: #343a40;
	border-color: #343a40;
}

.btn-dark:not(:disabled):not(.disabled):active, .btn-dark:not(:disabled):not(.disabled).active,
.show > .btn-dark.dropdown-toggle {
	color: #fff;
	background-color: #1d2124;
	border-color: #171a1d;
}

.btn-dark:not(:disabled):not(.disabled):active:focus, .btn-dark:not(:disabled):not(.disabled).active:focus,
.show > .btn-dark.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(82, 88, 93, 0.5);
}

.btn-outline-primary {
	color: #007bff;
	border-color: #007bff;
}

.btn-outline-primary:hover {
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
	color: #007bff;
	background-color: transparent;
}

.btn-outline-primary:not(:disabled):not(.disabled):active, .btn-outline-primary:not(:disabled):not(.disabled).active,
.show > .btn-outline-primary.dropdown-toggle {
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.btn-outline-primary:not(:disabled):not(.disabled):active:focus, .btn-outline-primary:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-primary.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.5);
}

.btn-outline-secondary {
	color: #6c757d;
	border-color: #6c757d;
}

.btn-outline-secondary:hover {
	color: #fff;
	background-color: #6c757d;
	border-color: #6c757d;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
	box-shadow: 0 0 0 0.2rem rgba(108, 117, 125, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
	color: #6c757d;
	background-color: transparent;
}

.btn-outline-secondary:not(:disabled):not(.disabled):active, .btn-outline-secondary:not(:disabled):not(.disabled).active,
.show > .btn-outline-secondary.dropdown-toggle {
	color: #fff;
	background-color: #6c757d;
	border-color: #6c757d;
}

.btn-outline-secondary:not(:disabled):not(.disabled):active:focus, .btn-outline-secondary:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-secondary.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(108, 117, 125, 0.5);
}

.btn-outline-success {
	color: #28a745;
	border-color: #28a745;
}

.btn-outline-success:hover {
	color: #fff;
	background-color: #28a745;
	border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
	box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
	color: #28a745;
	background-color: transparent;
}

.btn-outline-success:not(:disabled):not(.disabled):active, .btn-outline-success:not(:disabled):not(.disabled).active,
.show > .btn-outline-success.dropdown-toggle {
	color: #fff;
	background-color: #28a745;
	border-color: #28a745;
}

.btn-outline-success:not(:disabled):not(.disabled):active:focus, .btn-outline-success:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-success.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(40, 167, 69, 0.5);
}

.btn-outline-info {
	color: #17a2b8;
	border-color: #17a2b8;
}

.btn-outline-info:hover {
	color: #fff;
	background-color: #17a2b8;
	border-color: #17a2b8;
}

.btn-outline-info:focus, .btn-outline-info.focus {
	box-shadow: 0 0 0 0.2rem rgba(23, 162, 184, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
	color: #17a2b8;
	background-color: transparent;
}

.btn-outline-info:not(:disabled):not(.disabled):active, .btn-outline-info:not(:disabled):not(.disabled).active,
.show > .btn-outline-info.dropdown-toggle {
	color: #fff;
	background-color: #17a2b8;
	border-color: #17a2b8;
}

.btn-outline-info:not(:disabled):not(.disabled):active:focus, .btn-outline-info:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-info.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(23, 162, 184, 0.5);
}

.btn-outline-warning {
	color: #ffc107;
	border-color: #ffc107;
}

.btn-outline-warning:hover {
	color: #212529;
	background-color: #ffc107;
	border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
	box-shadow: 0 0 0 0.2rem rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
	color: #ffc107;
	background-color: transparent;
}

.btn-outline-warning:not(:disabled):not(.disabled):active, .btn-outline-warning:not(:disabled):not(.disabled).active,
.show > .btn-outline-warning.dropdown-toggle {
	color: #212529;
	background-color: #ffc107;
	border-color: #ffc107;
}

.btn-outline-warning:not(:disabled):not(.disabled):active:focus, .btn-outline-warning:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-warning.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(255, 193, 7, 0.5);
}

.btn-outline-danger {
	color: #dc3545;
	border-color: #dc3545;
}

.btn-outline-danger:hover {
	color: #fff;
	background-color: #dc3545;
	border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
	box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
	color: #dc3545;
	background-color: transparent;
}

.btn-outline-danger:not(:disabled):not(.disabled):active, .btn-outline-danger:not(:disabled):not(.disabled).active,
.show > .btn-outline-danger.dropdown-toggle {
	color: #fff;
	background-color: #dc3545;
	border-color: #dc3545;
}

.btn-outline-danger:not(:disabled):not(.disabled):active:focus, .btn-outline-danger:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-danger.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(220, 53, 69, 0.5);
}

.btn-outline-light {
	color: #f8f9fa;
	border-color: #f8f9fa;
}

.btn-outline-light:hover {
	color: #212529;
	background-color: #f8f9fa;
	border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
	box-shadow: 0 0 0 0.2rem rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
	color: #f8f9fa;
	background-color: transparent;
}

.btn-outline-light:not(:disabled):not(.disabled):active, .btn-outline-light:not(:disabled):not(.disabled).active,
.show > .btn-outline-light.dropdown-toggle {
	color: #212529;
	background-color: #f8f9fa;
	border-color: #f8f9fa;
}

.btn-outline-light:not(:disabled):not(.disabled):active:focus, .btn-outline-light:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-light.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(248, 249, 250, 0.5);
}

.btn-outline-dark {
	color: #343a40;
	border-color: #343a40;
}

.btn-outline-dark:hover {
	color: #fff;
	background-color: #343a40;
	border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
	box-shadow: 0 0 0 0.2rem rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
	color: #343a40;
	background-color: transparent;
}

.btn-outline-dark:not(:disabled):not(.disabled):active, .btn-outline-dark:not(:disabled):not(.disabled).active,
.show > .btn-outline-dark.dropdown-toggle {
	color: #fff;
	background-color: #343a40;
	border-color: #343a40;
}

.btn-outline-dark:not(:disabled):not(.disabled):active:focus, .btn-outline-dark:not(:disabled):not(.disabled).active:focus,
.show > .btn-outline-dark.dropdown-toggle:focus {
	box-shadow: 0 0 0 0.2rem rgba(52, 58, 64, 0.5);
}

.btn-link {
	font-weight: 400;
	color: #007bff;
}

.btn-link:hover {
	color: #0056b3;
	text-decoration: underline;
}

.btn-link:focus, .btn-link.focus {
	text-decoration: underline;
	box-shadow: none;
}

.btn-link:disabled, .btn-link.disabled {
	color: #6c757d;
	pointer-events: none;
}

.btn-lg, .btn-group-lg > .btn {
	padding: 0.5rem 1rem;
	font-size: 1.25rem;
	line-height: 1.5;
	border-radius: 0.3rem;
}

.btn-sm, .btn-group-sm > .btn {
	padding: 0.25rem 0.5rem;
	font-size: 0.875rem;
	line-height: 1.5;
	border-radius: 0.2rem;
}

.btn-block {
	display: block !important;
	width: 100%;
}

.btn-block + .btn-block {
	margin-top: 0.5rem;
}

input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
	width: 100%;
}

.fade {
	transition: opacity 0.15s linear;
}

@media screen and (prefers-reduced-motion: reduce) {
	.fade {
		transition: none;
	}
}

.fade:not(.show) {
	opacity: 0;
}

.collapse:not(.show) {
	display: none;
}

.collapsing {
	position: relative;
	height: 0;
	overflow: hidden;
	transition: height 0.35s ease;
}

@media screen and (prefers-reduced-motion: reduce) {
	.collapsing {
		transition: none;
	}
}

.dropup,
.dropright,
.dropdown,
.dropleft {
	position: relative;
}

.dropdown-toggle::after {
	display: inline-block;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0.3em solid;
	border-right: 0.3em solid transparent;
	border-bottom: 0;
	border-left: 0.3em solid transparent;
}

.dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropdown-menu {
	position: absolute;
	top: 100%;
	left: 0;
	z-index: 1000;
	display: none;
	float: left;
	min-width: 10rem;
	padding: 0.5rem 0;
	margin: 0.125rem 0 0;
	font-size: 1rem;
	color: #212529;
	text-align: left;
	list-style: none;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.15);
	border-radius: 0.25rem;
}

.dropdown-menu-right {
	right: 0;
	left: auto;
}

@media (min-width: 576px) {
	.dropdown-menu-sm-right {
		right: 0;
		left: auto;
	}
}

@media (min-width: 768px) {
	.dropdown-menu-md-right {
		right: 0;
		left: auto;
	}
}

@media (min-width: 992px) {
	.dropdown-menu-lg-right {
		right: 0;
		left: auto;
	}
}

@media (min-width: 1200px) {
	.dropdown-menu-xl-right {
		right: 0;
		left: auto;
	}
}

.dropdown-menu-left {
	right: auto;
	left: 0;
}

@media (min-width: 576px) {
	.dropdown-menu-sm-left {
		right: auto;
		left: 0;
	}
}

@media (min-width: 768px) {
	.dropdown-menu-md-left {
		right: auto;
		left: 0;
	}
}

@media (min-width: 992px) {
	.dropdown-menu-lg-left {
		right: auto;
		left: 0;
	}
}

@media (min-width: 1200px) {
	.dropdown-menu-xl-left {
		right: auto;
		left: 0;
	}
}

.dropup .dropdown-menu {
	top: auto;
	bottom: 100%;
	margin-top: 0;
	margin-bottom: 0.125rem;
}

.dropup .dropdown-toggle::after {
	display: inline-block;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0;
	border-right: 0.3em solid transparent;
	border-bottom: 0.3em solid;
	border-left: 0.3em solid transparent;
}

.dropup .dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropright .dropdown-menu {
	top: 0;
	right: auto;
	left: 100%;
	margin-top: 0;
	margin-left: 0.125rem;
}

.dropright .dropdown-toggle::after {
	display: inline-block;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0.3em solid transparent;
	border-right: 0;
	border-bottom: 0.3em solid transparent;
	border-left: 0.3em solid;
}

.dropright .dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropright .dropdown-toggle::after {
	vertical-align: 0;
}

.dropleft .dropdown-menu {
	top: 0;
	right: 100%;
	left: auto;
	margin-top: 0;
	margin-right: 0.125rem;
}

.dropleft .dropdown-toggle::after {
	display: inline-block;
	margin-left: 0.255em;
	vertical-align: 0.255em;
	content: "";
}

.dropleft .dropdown-toggle::after {
	display: none;
}

.dropleft .dropdown-toggle::before {
	display: inline-block;
	margin-right: 0.255em;
	vertical-align: 0.255em;
	content: "";
	border-top: 0.3em solid transparent;
	border-right: 0.3em solid;
	border-bottom: 0.3em solid transparent;
}

.dropleft .dropdown-toggle:empty::after {
	margin-left: 0;
}

.dropleft .dropdown-toggle::before {
	vertical-align: 0;
}

.dropdown-menu[x-placement^="top"], .dropdown-menu[x-placement^="right"], .dropdown-menu[x-placement^="bottom"], .dropdown-menu[x-placement^="left"] {
	right: auto;
	bottom: auto;
}

.dropdown-divider {
	height: 0;
	margin: 0.5rem 0;
	overflow: hidden;
	border-top: 1px solid #e9ecef;
}

.dropdown-item {
	display: block;
	width: 100%;
	padding: 0.25rem 1.5rem;
	clear: both;
	font-weight: 400;
	color: #212529;
	text-align: inherit;
	white-space: nowrap;
	background-color: transparent;
	border: 0;
}

.dropdown-item:first-child {
	border-top-left-radius: calc(0.25rem - 1px);
	border-top-right-radius: calc(0.25rem - 1px);
}

.dropdown-item:last-child {
	border-bottom-right-radius: calc(0.25rem - 1px);
	border-bottom-left-radius: calc(0.25rem - 1px);
}

.dropdown-item:hover, .dropdown-item:focus {
	color: #16181b;
	text-decoration: none;
	background-color: #f8f9fa;
}

.dropdown-item.active, .dropdown-item:active {
	color: #fff;
	text-decoration: none;
	background-color: #007bff;
}

.dropdown-item.disabled, .dropdown-item:disabled {
	color: #6c757d;
	pointer-events: none;
	background-color: transparent;
}

.dropdown-menu.show {
	display: block;
}

.dropdown-header {
	display: block;
	padding: 0.5rem 1.5rem;
	margin-bottom: 0;
	font-size: 0.875rem;
	color: #6c757d;
	white-space: nowrap;
}

.dropdown-item-text {
	display: block;
	padding: 0.25rem 1.5rem;
	color: #212529;
}

.btn-group,
.btn-group-vertical {
	position: relative;
	display: -ms-inline-flexbox;
	display: inline-flex;
	vertical-align: middle;
}

.btn-group > .btn,
.btn-group-vertical > .btn {
	position: relative;
	-ms-flex: 1 1 auto;
	flex: 1 1 auto;
}

.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover {
	z-index: 1;
}

.btn-group > .btn:focus, .btn-group > .btn:active, .btn-group > .btn.active,
.btn-group-vertical > .btn:focus,
.btn-group-vertical > .btn:active,
.btn-group-vertical > .btn.active {
	z-index: 1;
}

.btn-toolbar {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-ms-flex-pack: start;
	justify-content: flex-start;
}

.btn-toolbar .input-group {
	width: auto;
}

.btn-group > .btn:not(:first-child),
.btn-group > .btn-group:not(:first-child) {
	margin-left: -1px;
}

.btn-group > .btn:not(:last-child):not(.dropdown-toggle),
.btn-group > .btn-group:not(:last-child) > .btn {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.btn-group > .btn:not(:first-child),
.btn-group > .btn-group:not(:first-child) > .btn {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.dropdown-toggle-split {
	padding-right: 0.5625rem;
	padding-left: 0.5625rem;
}

.dropdown-toggle-split::after,
.dropup .dropdown-toggle-split::after,
.dropright .dropdown-toggle-split::after {
	margin-left: 0;
}

.dropleft .dropdown-toggle-split::before {
	margin-right: 0;
}

.btn-sm + .dropdown-toggle-split, .btn-group-sm > .btn + .dropdown-toggle-split {
	padding-right: 0.375rem;
	padding-left: 0.375rem;
}

.btn-lg + .dropdown-toggle-split, .btn-group-lg > .btn + .dropdown-toggle-split {
	padding-right: 0.75rem;
	padding-left: 0.75rem;
}

.btn-group-vertical {
	-ms-flex-direction: column;
	flex-direction: column;
	-ms-flex-align: start;
	align-items: flex-start;
	-ms-flex-pack: center;
	justify-content: center;
}

.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group {
	width: 100%;
}

.btn-group-vertical > .btn:not(:first-child),
.btn-group-vertical > .btn-group:not(:first-child) {
	margin-top: -1px;
}

.btn-group-vertical > .btn:not(:last-child):not(.dropdown-toggle),
.btn-group-vertical > .btn-group:not(:last-child) > .btn {
	border-bottom-right-radius: 0;
	border-bottom-left-radius: 0;
}

.btn-group-vertical > .btn:not(:first-child),
.btn-group-vertical > .btn-group:not(:first-child) > .btn {
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.btn-group-toggle > .btn,
.btn-group-toggle > .btn-group > .btn {
	margin-bottom: 0;
}

.btn-group-toggle > .btn input[type="radio"],
.btn-group-toggle > .btn input[type="checkbox"],
.btn-group-toggle > .btn-group > .btn input[type="radio"],
.btn-group-toggle > .btn-group > .btn input[type="checkbox"] {
	position: absolute;
	clip: rect(0, 0, 0, 0);
	pointer-events: none;
}

.input-group {
	position: relative;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-ms-flex-align: stretch;
	align-items: stretch;
	width: 100%;
}

.input-group > .form-control,
.input-group > .form-control-plaintext,
.input-group > .custom-select,
.input-group > .custom-file {
	position: relative;
	-ms-flex: 1 1 auto;
	flex: 1 1 auto;
	width: 1%;
	margin-bottom: 0;
}

.input-group > .form-control + .form-control,
.input-group > .form-control + .custom-select,
.input-group > .form-control + .custom-file,
.input-group > .form-control-plaintext + .form-control,
.input-group > .form-control-plaintext + .custom-select,
.input-group > .form-control-plaintext + .custom-file,
.input-group > .custom-select + .form-control,
.input-group > .custom-select + .custom-select,
.input-group > .custom-select + .custom-file,
.input-group > .custom-file + .form-control,
.input-group > .custom-file + .custom-select,
.input-group > .custom-file + .custom-file {
	margin-left: -1px;
}

.input-group > .form-control:focus,
.input-group > .custom-select:focus,
.input-group > .custom-file .custom-file-input:focus ~ .custom-file-label {
	z-index: 3;
}

.input-group > .custom-file .custom-file-input:focus {
	z-index: 4;
}

.input-group > .form-control:not(:last-child),
.input-group > .custom-select:not(:last-child) {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.input-group > .form-control:not(:first-child),
.input-group > .custom-select:not(:first-child) {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.input-group > .custom-file {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: center;
	align-items: center;
}

.input-group > .custom-file:not(:last-child) .custom-file-label,
.input-group > .custom-file:not(:last-child) .custom-file-label::after {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.input-group > .custom-file:not(:first-child) .custom-file-label {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.input-group-prepend,
.input-group-append {
	display: -ms-flexbox;
	display: flex;
}

.input-group-prepend .btn,
.input-group-append .btn {
	position: relative;
	z-index: 2;
}

.input-group-prepend .btn:focus,
.input-group-append .btn:focus {
	z-index: 3;
}

.input-group-prepend .btn + .btn,
.input-group-prepend .btn + .input-group-text,
.input-group-prepend .input-group-text + .input-group-text,
.input-group-prepend .input-group-text + .btn,
.input-group-append .btn + .btn,
.input-group-append .btn + .input-group-text,
.input-group-append .input-group-text + .input-group-text,
.input-group-append .input-group-text + .btn {
	margin-left: -1px;
}

.input-group-prepend {
	margin-right: -1px;
}

.input-group-append {
	margin-left: -1px;
}

.input-group-text {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: center;
	align-items: center;
	padding: 0.375rem 0.75rem;
	margin-bottom: 0;
	font-size: 1rem;
	font-weight: 400;
	line-height: 1.5;
	color: #495057;
	text-align: center;
	white-space: nowrap;
	background-color: #e9ecef;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
}

.input-group-text input[type="radio"],
.input-group-text input[type="checkbox"] {
	margin-top: 0;
}

.input-group-lg > .form-control:not(textarea),
.input-group-lg > .custom-select {
	height: calc(2.875rem + 2px);
}

.input-group-lg > .form-control,
.input-group-lg > .custom-select,
.input-group-lg > .input-group-prepend > .input-group-text,
.input-group-lg > .input-group-append > .input-group-text,
.input-group-lg > .input-group-prepend > .btn,
.input-group-lg > .input-group-append > .btn {
	padding: 0.5rem 1rem;
	font-size: 1.25rem;
	line-height: 1.5;
	border-radius: 0.3rem;
}

.input-group-sm > .form-control:not(textarea),
.input-group-sm > .custom-select {
	height: calc(1.8125rem + 2px);
}

.input-group-sm > .form-control,
.input-group-sm > .custom-select,
.input-group-sm > .input-group-prepend > .input-group-text,
.input-group-sm > .input-group-append > .input-group-text,
.input-group-sm > .input-group-prepend > .btn,
.input-group-sm > .input-group-append > .btn {
	padding: 0.25rem 0.5rem;
	font-size: 0.875rem;
	line-height: 1.5;
	border-radius: 0.2rem;
}

.input-group-lg > .custom-select,
.input-group-sm > .custom-select {
	padding-right: 1.75rem;
}

.input-group > .input-group-prepend > .btn,
.input-group > .input-group-prepend > .input-group-text,
.input-group > .input-group-append:not(:last-child) > .btn,
.input-group > .input-group-append:not(:last-child) > .input-group-text,
.input-group > .input-group-append:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group > .input-group-append:last-child > .input-group-text:not(:last-child) {
	border-top-right-radius: 0;
	border-bottom-right-radius: 0;
}

.input-group > .input-group-append > .btn,
.input-group > .input-group-append > .input-group-text,
.input-group > .input-group-prepend:not(:first-child) > .btn,
.input-group > .input-group-prepend:not(:first-child) > .input-group-text,
.input-group > .input-group-prepend:first-child > .btn:not(:first-child),
.input-group > .input-group-prepend:first-child > .input-group-text:not(:first-child) {
	border-top-left-radius: 0;
	border-bottom-left-radius: 0;
}

.custom-control {
	position: relative;
	display: block;
	min-height: 1.5rem;
	padding-left: 1.5rem;
}

.custom-control-inline {
	display: -ms-inline-flexbox;
	display: inline-flex;
	margin-right: 1rem;
}

.custom-control-input {
	position: absolute;
	z-index: -1;
	opacity: 0;
}

.custom-control-input:checked ~ .custom-control-label::before {
	color: #fff;
	border-color: #007bff;
	background-color: #007bff;
}

.custom-control-input:focus ~ .custom-control-label::before {
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-control-input:focus:not(:checked) ~ .custom-control-label::before {
	border-color: #80bdff;
}

.custom-control-input:not(:disabled):active ~ .custom-control-label::before {
	color: #fff;
	background-color: #b3d7ff;
	border-color: #b3d7ff;
}

.custom-control-input:disabled ~ .custom-control-label {
	color: #6c757d;
}

.custom-control-input:disabled ~ .custom-control-label::before {
	background-color: #e9ecef;
}

.custom-control-label {
	position: relative;
	margin-bottom: 0;
	vertical-align: top;
}

.custom-control-label::before {
	position: absolute;
	top: 0.25rem;
	left: -1.5rem;
	display: block;
	width: 1rem;
	height: 1rem;
	pointer-events: none;
	content: "";
	background-color: #fff;
	border: #adb5bd solid 1px;
}

.custom-control-label::after {
	position: absolute;
	top: 0.25rem;
	left: -1.5rem;
	display: block;
	width: 1rem;
	height: 1rem;
	content: "";
	background-repeat: no-repeat;
	background-position: center center;
	background-size: 50% 50%;
}

.custom-checkbox .custom-control-label::before {
	border-radius: 0.25rem;
}

.custom-checkbox .custom-control-input:checked ~ .custom-control-label::after {
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23fff' d='M6.564.75l-3.59 3.612-1.538-1.55L0 4.26 2.974 7.25 8 2.193z'/%3e%3c/svg%3e");
}

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-label::before {
	border-color: #007bff;
	background-color: #007bff;
}

.custom-checkbox .custom-control-input:indeterminate ~ .custom-control-label::after {
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 4'%3e%3cpath stroke='%23fff' d='M0 2h4'/%3e%3c/svg%3e");
}

.custom-checkbox .custom-control-input:disabled:checked ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-checkbox .custom-control-input:disabled:indeterminate ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-radio .custom-control-label::before {
	border-radius: 50%;
}

.custom-radio .custom-control-input:checked ~ .custom-control-label::after {
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='%23fff'/%3e%3c/svg%3e");
}

.custom-radio .custom-control-input:disabled:checked ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-switch {
	padding-left: 2.25rem;
}

.custom-switch .custom-control-label::before {
	left: -2.25rem;
	width: 1.75rem;
	pointer-events: all;
	border-radius: 0.5rem;
}

.custom-switch .custom-control-label::after {
	top: calc(0.25rem + 2px);
	left: calc(-2.25rem + 2px);
	width: calc(1rem - 4px);
	height: calc(1rem - 4px);
	background-color: #adb5bd;
	border-radius: 0.5rem;
	transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out, -webkit-transform 0.15s ease-in-out;
	transition: transform 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
	transition: transform 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out, -webkit-transform 0.15s ease-in-out;
}

@media screen and (prefers-reduced-motion: reduce) {
	.custom-switch .custom-control-label::after {
		transition: none;
	}
}

.custom-switch .custom-control-input:checked ~ .custom-control-label::after {
	background-color: #fff;
	-webkit-transform: translateX(0.75rem);
	transform: translateX(0.75rem);
}

.custom-switch .custom-control-input:disabled:checked ~ .custom-control-label::before {
	background-color: rgba(0, 123, 255, 0.5);
}

.custom-select {
	display: inline-block;
	width: 100%;
	height: calc(2.25rem + 2px);
	padding: 0.375rem 1.75rem 0.375rem 0.75rem;
	font-weight: 400;
	line-height: 1.5;
	color: #495057;
	vertical-align: middle;
	background: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3e%3cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3e%3c/svg%3e") no-repeat right 0.75rem center/8px 10px;
	background-color: #fff;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
}

.custom-select:focus {
	border-color: #80bdff;
	outline: 0;
	box-shadow: 0 0 0 0.2rem rgba(128, 189, 255, 0.5);
}

.custom-select:focus::-ms-value {
	color: #495057;
	background-color: #fff;
}

.custom-select[multiple], .custom-select[size]:not([size="1"]) {
	height: auto;
	padding-right: 0.75rem;
	background-image: none;
}

.custom-select:disabled {
	color: #6c757d;
	background-color: #e9ecef;
}

.custom-select::-ms-expand {
	opacity: 0;
}

.custom-select-sm {
	height: calc(1.8125rem + 2px);
	padding-top: 0.25rem;
	padding-bottom: 0.25rem;
	padding-left: 0.5rem;
	font-size: 0.875rem;
}

.custom-select-lg {
	height: calc(2.875rem + 2px);
	padding-top: 0.5rem;
	padding-bottom: 0.5rem;
	padding-left: 1rem;
	font-size: 1.25rem;
}

.custom-file {
	position: relative;
	display: inline-block;
	width: 100%;
	height: calc(2.25rem + 2px);
	margin-bottom: 0;
}

.custom-file-input {
	position: relative;
	z-index: 2;
	width: 100%;
	height: calc(2.25rem + 2px);
	margin: 0;
	opacity: 0;
}

.custom-file-input:focus ~ .custom-file-label {
	border-color: #80bdff;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-file-input:disabled ~ .custom-file-label {
	background-color: #e9ecef;
}

.custom-file-input:lang(en) ~ .custom-file-label::after {
	content: "Browse";
}

.custom-file-input ~ .custom-file-label[data-browse]::after {
	content: attr(data-browse);
}

.custom-file-label {
	position: absolute;
	top: 0;
	right: 0;
	left: 0;
	z-index: 1;
	height: calc(2.25rem + 2px);
	padding: 0.375rem 0.75rem;
	font-weight: 400;
	line-height: 1.5;
	color: #495057;
	background-color: #fff;
	border: 1px solid #ced4da;
	border-radius: 0.25rem;
}

.custom-file-label::after {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	z-index: 3;
	display: block;
	height: 2.25rem;
	padding: 0.375rem 0.75rem;
	line-height: 1.5;
	color: #495057;
	content: "Browse";
	background-color: #e9ecef;
	border-left: inherit;
	border-radius: 0 0.25rem 0.25rem 0;
}

.custom-range {
	width: 100%;
	height: calc(1rem + 0.4rem);
	padding: 0;
	background-color: transparent;
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
}

.custom-range:focus {
	outline: none;
}

.custom-range:focus::-webkit-slider-thumb {
	box-shadow: 0 0 0 1px #fff, 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-range:focus::-moz-range-thumb {
	box-shadow: 0 0 0 1px #fff, 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-range:focus::-ms-thumb {
	box-shadow: 0 0 0 1px #fff, 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.custom-range::-moz-focus-outer {
	border: 0;
}

.custom-range::-webkit-slider-thumb {
	width: 1rem;
	height: 1rem;
	margin-top: -0.25rem;
	background-color: #007bff;
	border: 0;
	border-radius: 1rem;
	transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
	-webkit-appearance: none;
	appearance: none;
}

@media screen and (prefers-reduced-motion: reduce) {
	.custom-range::-webkit-slider-thumb {
		transition: none;
	}
}

.custom-range::-webkit-slider-thumb:active {
	background-color: #b3d7ff;
}

.custom-range::-webkit-slider-runnable-track {
	width: 100%;
	height: 0.5rem;
	color: transparent;
	cursor: pointer;
	background-color: #dee2e6;
	border-color: transparent;
	border-radius: 1rem;
}

.custom-range::-moz-range-thumb {
	width: 1rem;
	height: 1rem;
	background-color: #007bff;
	border: 0;
	border-radius: 1rem;
	transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
	-moz-appearance: none;
	appearance: none;
}

@media screen and (prefers-reduced-motion: reduce) {
	.custom-range::-moz-range-thumb {
		transition: none;
	}
}

.custom-range::-moz-range-thumb:active {
	background-color: #b3d7ff;
}

.custom-range::-moz-range-track {
	width: 100%;
	height: 0.5rem;
	color: transparent;
	cursor: pointer;
	background-color: #dee2e6;
	border-color: transparent;
	border-radius: 1rem;
}

.custom-range::-ms-thumb {
	width: 1rem;
	height: 1rem;
	margin-top: 0;
	margin-right: 0.2rem;
	margin-left: 0.2rem;
	background-color: #007bff;
	border: 0;
	border-radius: 1rem;
	transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
	appearance: none;
}

@media screen and (prefers-reduced-motion: reduce) {
	.custom-range::-ms-thumb {
		transition: none;
	}
}

.custom-range::-ms-thumb:active {
	background-color: #b3d7ff;
}

.custom-range::-ms-track {
	width: 100%;
	height: 0.5rem;
	color: transparent;
	cursor: pointer;
	background-color: transparent;
	border-color: transparent;
	border-width: 0.5rem;
}

.custom-range::-ms-fill-lower {
	background-color: #dee2e6;
	border-radius: 1rem;
}

.custom-range::-ms-fill-upper {
	margin-right: 15px;
	background-color: #dee2e6;
	border-radius: 1rem;
}

.custom-range:disabled::-webkit-slider-thumb {
	background-color: #adb5bd;
}

.custom-range:disabled::-webkit-slider-runnable-track {
	cursor: default;
}

.custom-range:disabled::-moz-range-thumb {
	background-color: #adb5bd;
}

.custom-range:disabled::-moz-range-track {
	cursor: default;
}

.custom-range:disabled::-ms-thumb {
	background-color: #adb5bd;
}

.custom-control-label::before,
.custom-file-label,
.custom-select {
	transition: background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

@media screen and (prefers-reduced-motion: reduce) {
	.custom-control-label::before,
	.custom-file-label,
	.custom-select {
		transition: none;
	}
}

.nav {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	padding-left: 0;
	margin-bottom: 0;
	list-style: none;
}

.nav-link {
	display: block;
	padding: 0.5rem 1rem;
}

.nav-link:hover, .nav-link:focus {
	text-decoration: none;
}

.nav-link.disabled {
	color: #6c757d;
	pointer-events: none;
	cursor: default;
}

.nav-tabs {
	border-bottom: 1px solid #dee2e6;
}

.nav-tabs .nav-item {
	margin-bottom: -1px;
}

.nav-tabs .nav-link {
	border: 1px solid transparent;
	border-top-left-radius: 0.25rem;
	border-top-right-radius: 0.25rem;
}

.nav-tabs .nav-link:hover, .nav-tabs .nav-link:focus {
	border-color: #e9ecef #e9ecef #dee2e6;
}

.nav-tabs .nav-link.disabled {
	color: #6c757d;
	background-color: transparent;
	border-color: transparent;
}

.nav-tabs .nav-link.active,
.nav-tabs .nav-item.show .nav-link {
	color: #495057;
	background-color: #fff;
	border-color: #dee2e6 #dee2e6 #fff;
}

.nav-tabs .dropdown-menu {
	margin-top: -1px;
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.nav-pills .nav-link {
	border-radius: 0.25rem;
}

.nav-pills .nav-link.active,
.nav-pills .show > .nav-link {
	color: #fff;
	background-color: #007bff;
}

.nav-fill .nav-item {
	-ms-flex: 1 1 auto;
	flex: 1 1 auto;
	text-align: center;
}

.nav-justified .nav-item {
	-ms-flex-preferred-size: 0;
	flex-basis: 0;
	-ms-flex-positive: 1;
	flex-grow: 1;
	text-align: center;
}

.tab-content > .tab-pane {
	display: none;
}

.tab-content > .active {
	display: block;
}

.navbar {
	position: relative;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-pack: justify;
	justify-content: space-between;
	padding: 0.5rem 1rem;
}

.navbar > .container,
.navbar > .container-fluid {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-pack: justify;
	justify-content: space-between;
}

.navbar-brand {
	display: inline-block;
	padding-top: 0.3125rem;
	padding-bottom: 0.3125rem;
	margin-right: 1rem;
	font-size: 1.25rem;
	line-height: inherit;
	white-space: nowrap;
}

.navbar-brand:hover, .navbar-brand:focus {
	text-decoration: none;
}

.navbar-nav {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	padding-left: 0;
	margin-bottom: 0;
	list-style: none;
}

.navbar-nav .nav-link {
	padding-right: 0;
	padding-left: 0;
}

.navbar-nav .dropdown-menu {
	position: static;
	float: none;
}

.navbar-text {
	display: inline-block;
	padding-top: 0.5rem;
	padding-bottom: 0.5rem;
}

.navbar-collapse {
	-ms-flex-preferred-size: 100%;
	flex-basis: 100%;
	-ms-flex-positive: 1;
	flex-grow: 1;
	-ms-flex-align: center;
	align-items: center;
}

.navbar-toggler {
	padding: 0.25rem 0.75rem;
	font-size: 1.25rem;
	line-height: 1;
	background-color: transparent;
	border: 1px solid transparent;
	border-radius: 0.25rem;
}

.navbar-toggler:hover, .navbar-toggler:focus {
	text-decoration: none;
}

.navbar-toggler:not(:disabled):not(.disabled) {
	cursor: pointer;
}

.navbar-toggler-icon {
	display: inline-block;
	width: 1.5em;
	height: 1.5em;
	vertical-align: middle;
	content: "";
	background: no-repeat center center;
	background-size: 100% 100%;
}

@media (max-width: 575.98px) {
	.navbar-expand-sm > .container,
	.navbar-expand-sm > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 576px) {
	.navbar-expand-sm {
		-ms-flex-flow: row nowrap;
		flex-flow: row nowrap;
		-ms-flex-pack: start;
		justify-content: flex-start;
	}
	.navbar-expand-sm .navbar-nav {
		-ms-flex-direction: row;
		flex-direction: row;
	}
	.navbar-expand-sm .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-sm .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-sm > .container,
	.navbar-expand-sm > .container-fluid {
		-ms-flex-wrap: nowrap;
		flex-wrap: nowrap;
	}
	.navbar-expand-sm .navbar-collapse {
		display: -ms-flexbox !important;
		display: flex !important;
		-ms-flex-preferred-size: auto;
		flex-basis: auto;
	}
	.navbar-expand-sm .navbar-toggler {
		display: none;
	}
}

@media (max-width: 767.98px) {
	.navbar-expand-md > .container,
	.navbar-expand-md > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 768px) {
	.navbar-expand-md {
		-ms-flex-flow: row nowrap;
		flex-flow: row nowrap;
		-ms-flex-pack: start;
		justify-content: flex-start;
	}
	.navbar-expand-md .navbar-nav {
		-ms-flex-direction: row;
		flex-direction: row;
	}
	.navbar-expand-md .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-md .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-md > .container,
	.navbar-expand-md > .container-fluid {
		-ms-flex-wrap: nowrap;
		flex-wrap: nowrap;
	}
	.navbar-expand-md .navbar-collapse {
		display: -ms-flexbox !important;
		display: flex !important;
		-ms-flex-preferred-size: auto;
		flex-basis: auto;
	}
	.navbar-expand-md .navbar-toggler {
		display: none;
	}
}

@media (max-width: 991.98px) {
	.navbar-expand-lg > .container,
	.navbar-expand-lg > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 992px) {
	.navbar-expand-lg {
		-ms-flex-flow: row nowrap;
		flex-flow: row nowrap;
		-ms-flex-pack: start;
		justify-content: flex-start;
	}
	.navbar-expand-lg .navbar-nav {
		-ms-flex-direction: row;
		flex-direction: row;
	}
	.navbar-expand-lg .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-lg .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-lg > .container,
	.navbar-expand-lg > .container-fluid {
		-ms-flex-wrap: nowrap;
		flex-wrap: nowrap;
	}
	.navbar-expand-lg .navbar-collapse {
		display: -ms-flexbox !important;
		display: flex !important;
		-ms-flex-preferred-size: auto;
		flex-basis: auto;
	}
	.navbar-expand-lg .navbar-toggler {
		display: none;
	}
}

@media (max-width: 1199.98px) {
	.navbar-expand-xl > .container,
	.navbar-expand-xl > .container-fluid {
		padding-right: 0;
		padding-left: 0;
	}
}

@media (min-width: 1200px) {
	.navbar-expand-xl {
		-ms-flex-flow: row nowrap;
		flex-flow: row nowrap;
		-ms-flex-pack: start;
		justify-content: flex-start;
	}
	.navbar-expand-xl .navbar-nav {
		-ms-flex-direction: row;
		flex-direction: row;
	}
	.navbar-expand-xl .navbar-nav .dropdown-menu {
		position: absolute;
	}
	.navbar-expand-xl .navbar-nav .nav-link {
		padding-right: 0.5rem;
		padding-left: 0.5rem;
	}
	.navbar-expand-xl > .container,
	.navbar-expand-xl > .container-fluid {
		-ms-flex-wrap: nowrap;
		flex-wrap: nowrap;
	}
	.navbar-expand-xl .navbar-collapse {
		display: -ms-flexbox !important;
		display: flex !important;
		-ms-flex-preferred-size: auto;
		flex-basis: auto;
	}
	.navbar-expand-xl .navbar-toggler {
		display: none;
	}
}

.navbar-expand {
	-ms-flex-flow: row nowrap;
	flex-flow: row nowrap;
	-ms-flex-pack: start;
	justify-content: flex-start;
}

.navbar-expand > .container,
.navbar-expand > .container-fluid {
	padding-right: 0;
	padding-left: 0;
}

.navbar-expand .navbar-nav {
	-ms-flex-direction: row;
	flex-direction: row;
}

.navbar-expand .navbar-nav .dropdown-menu {
	position: absolute;
}

.navbar-expand .navbar-nav .nav-link {
	padding-right: 0.5rem;
	padding-left: 0.5rem;
}

.navbar-expand > .container,
.navbar-expand > .container-fluid {
	-ms-flex-wrap: nowrap;
	flex-wrap: nowrap;
}

.navbar-expand .navbar-collapse {
	display: -ms-flexbox !important;
	display: flex !important;
	-ms-flex-preferred-size: auto;
	flex-basis: auto;
}

.navbar-expand .navbar-toggler {
	display: none;
}

.navbar-light .navbar-brand {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:hover, .navbar-light .navbar-brand:focus {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
	color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:hover, .navbar-light .navbar-nav .nav-link:focus {
	color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
	color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
	color: rgba(0, 0, 0, 0.5);
	border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
	background-image: url("data:image/svg+xml,%3csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3e%3cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
}

.navbar-light .navbar-text {
	color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-text a {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-text a:hover, .navbar-light .navbar-text a:focus {
	color: rgba(0, 0, 0, 0.9);
}

.navbar-dark .navbar-brand {
	color: #fff;
}

.navbar-dark .navbar-brand:hover, .navbar-dark .navbar-brand:focus {
	color: #fff;
}

.navbar-dark .navbar-nav .nav-link {
	color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:hover, .navbar-dark .navbar-nav .nav-link:focus {
	color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
	color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
	color: #fff;
}

.navbar-dark .navbar-toggler {
	color: rgba(255, 255, 255, 0.5);
	border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
	background-image: url("data:image/svg+xml,%3csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3e%3cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
}

.navbar-dark .navbar-text {
	color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-text a {
	color: #fff;
}

.navbar-dark .navbar-text a:hover, .navbar-dark .navbar-text a:focus {
	color: #fff;
}

.card {
	position: relative;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	min-width: 0;
	word-wrap: break-word;
	background-color: #fff;
	background-clip: border-box;
	border: 1px solid rgba(0, 0, 0, 0.125);
	border-radius: 0.25rem;
}

.card > hr {
	margin-right: 0;
	margin-left: 0;
}

.card > .list-group:first-child .list-group-item:first-child {
	border-top-left-radius: 0.25rem;
	border-top-right-radius: 0.25rem;
}

.card > .list-group:last-child .list-group-item:last-child {
	border-bottom-right-radius: 0.25rem;
	border-bottom-left-radius: 0.25rem;
}

.card-body {
	-ms-flex: 1 1 auto;
	flex: 1 1 auto;
	padding: 1.25rem;
}

.card-title {
	margin-bottom: 0.75rem;
}

.card-subtitle {
	margin-top: -0.375rem;
	margin-bottom: 0;
}

.card-text:last-child {
	margin-bottom: 0;
}

.card-link:hover {
	text-decoration: none;
}

.card-link + .card-link {
	margin-left: 1.25rem;
}

.card-header {
	padding: 0.75rem 1.25rem;
	margin-bottom: 0;
	color: inherit;
	background-color: rgba(0, 0, 0, 0.03);
	border-bottom: 1px solid rgba(0, 0, 0, 0.125);
}

.card-header:first-child {
	border-radius: calc(0.25rem - 1px) calc(0.25rem - 1px) 0 0;
}

.card-header + .list-group .list-group-item:first-child {
	border-top: 0;
}

.card-footer {
	padding: 0.75rem 1.25rem;
	background-color: rgba(0, 0, 0, 0.03);
	border-top: 1px solid rgba(0, 0, 0, 0.125);
}

.card-footer:last-child {
	border-radius: 0 0 calc(0.25rem - 1px) calc(0.25rem - 1px);
}

.card-header-tabs {
	margin-right: -0.625rem;
	margin-bottom: -0.75rem;
	margin-left: -0.625rem;
	border-bottom: 0;
}

.card-header-pills {
	margin-right: -0.625rem;
	margin-left: -0.625rem;
}

.card-img-overlay {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	padding: 1.25rem;
}

.card-img {
	width: 100%;
	border-radius: calc(0.25rem - 1px);
}

.card-img-top {
	width: 100%;
	border-top-left-radius: calc(0.25rem - 1px);
	border-top-right-radius: calc(0.25rem - 1px);
}

.card-img-bottom {
	width: 100%;
	border-bottom-right-radius: calc(0.25rem - 1px);
	border-bottom-left-radius: calc(0.25rem - 1px);
}

.card-deck {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
}

.card-deck .card {
	margin-bottom: 15px;
}

@media (min-width: 576px) {
	.card-deck {
		-ms-flex-flow: row wrap;
		flex-flow: row wrap;
		margin-right: -15px;
		margin-left: -15px;
		margin-bottom: 30px;
	}
	.card-deck .card {
		display: -ms-flexbox;
		display: flex;
		-ms-flex: 1 0 0%;
		flex: 1 0 0%;
		-ms-flex-direction: column;
		flex-direction: column;
		margin-right: 15px;
		margin-bottom: 0;
		margin-left: 15px;
	}
}

.card-group {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
}

.card-group > .card {
	margin-bottom: 15px;
}

@media (min-width: 576px) {
	.card-group {
		-ms-flex-flow: row wrap;
		flex-flow: row wrap;
	}
	.card-group > .card {
		-ms-flex: 1 0 0%;
		flex: 1 0 0%;
		margin-bottom: 0;
	}
	.card-group > .card + .card {
		margin-left: 0;
		border-left: 0;
	}
	.card-group > .card:first-child {
		border-top-right-radius: 0;
		border-bottom-right-radius: 0;
	}
	.card-group > .card:first-child .card-img-top,
	.card-group > .card:first-child .card-header {
		border-top-right-radius: 0;
	}
	.card-group > .card:first-child .card-img-bottom,
	.card-group > .card:first-child .card-footer {
		border-bottom-right-radius: 0;
	}
	.card-group > .card:last-child {
		border-top-left-radius: 0;
		border-bottom-left-radius: 0;
	}
	.card-group > .card:last-child .card-img-top,
	.card-group > .card:last-child .card-header {
		border-top-left-radius: 0;
	}
	.card-group > .card:last-child .card-img-bottom,
	.card-group > .card:last-child .card-footer {
		border-bottom-left-radius: 0;
	}
	.card-group > .card:only-child {
		border-radius: 0.25rem;
	}
	.card-group > .card:only-child .card-img-top,
	.card-group > .card:only-child .card-header {
		border-top-left-radius: 0.25rem;
		border-top-right-radius: 0.25rem;
	}
	.card-group > .card:only-child .card-img-bottom,
	.card-group > .card:only-child .card-footer {
		border-bottom-right-radius: 0.25rem;
		border-bottom-left-radius: 0.25rem;
	}
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) {
		border-radius: 0;
	}
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-img-top,
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-img-bottom,
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-header,
	.card-group > .card:not(:first-child):not(:last-child):not(:only-child) .card-footer {
		border-radius: 0;
	}
}

.card-columns .card {
	margin-bottom: 0.75rem;
}

@media (min-width: 576px) {
	.card-columns {
		-webkit-column-count: 3;
		-moz-column-count: 3;
		column-count: 3;
		-webkit-column-gap: 1.25rem;
		-moz-column-gap: 1.25rem;
		column-gap: 1.25rem;
		orphans: 1;
		widows: 1;
	}
	.card-columns .card {
		display: inline-block;
		width: 100%;
	}
}

.accordion .card {
	overflow: hidden;
}

.accordion .card:not(:first-of-type) .card-header:first-child {
	border-radius: 0;
}

.accordion .card:not(:first-of-type):not(:last-of-type) {
	border-bottom: 0;
	border-radius: 0;
}

.accordion .card:first-of-type {
	border-bottom: 0;
	border-bottom-right-radius: 0;
	border-bottom-left-radius: 0;
}

.accordion .card:last-of-type {
	border-top-left-radius: 0;
	border-top-right-radius: 0;
}

.accordion .card .card-header {
	margin-bottom: -1px;
}

.breadcrumb {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	padding: 0.75rem 1rem;
	margin-bottom: 1rem;
	list-style: none;
	background-color: #e9ecef;
	border-radius: 0.25rem;
}

.breadcrumb-item + .breadcrumb-item {
	padding-left: 0.5rem;
}

.breadcrumb-item + .breadcrumb-item::before {
	display: inline-block;
	padding-right: 0.5rem;
	color: #6c757d;
	content: "/";
}

.breadcrumb-item + .breadcrumb-item:hover::before {
	text-decoration: underline;
}

.breadcrumb-item + .breadcrumb-item:hover::before {
	text-decoration: none;
}

.breadcrumb-item.active {
	color: #6c757d;
}

.pagination {
	display: -ms-flexbox;
	display: flex;
	padding-left: 0;
	list-style: none;
	border-radius: 0.25rem;
}

.page-link {
	position: relative;
	display: block;
	padding: 0.5rem 0.75rem;
	margin-left: -1px;
	line-height: 1.25;
	color: #007bff;
	background-color: #fff;
	border: 1px solid #dee2e6;
}

.page-link:hover {
	z-index: 2;
	color: #0056b3;
	text-decoration: none;
	background-color: #e9ecef;
	border-color: #dee2e6;
}

.page-link:focus {
	z-index: 2;
	outline: 0;
	box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.page-link:not(:disabled):not(.disabled) {
	cursor: pointer;
}

.page-item:first-child .page-link {
	margin-left: 0;
	border-top-left-radius: 0.25rem;
	border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
	border-top-right-radius: 0.25rem;
	border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
	z-index: 1;
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.page-item.disabled .page-link {
	color: #6c757d;
	pointer-events: none;
	cursor: auto;
	background-color: #fff;
	border-color: #dee2e6;
}

.pagination-lg .page-link {
	padding: 0.75rem 1.5rem;
	font-size: 1.25rem;
	line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
	border-top-left-radius: 0.3rem;
	border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
	border-top-right-radius: 0.3rem;
	border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
	padding: 0.25rem 0.5rem;
	font-size: 0.875rem;
	line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
	border-top-left-radius: 0.2rem;
	border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
	border-top-right-radius: 0.2rem;
	border-bottom-right-radius: 0.2rem;
}

.badge {
	display: inline-block;
	padding: 0.25em 0.4em;
	font-size: 75%;
	font-weight: 700;
	line-height: 1;
	text-align: center;
	white-space: nowrap;
	vertical-align: baseline;
	border-radius: 0.25rem;
}

a.badge:hover, a.badge:focus {
	text-decoration: none;
}

.badge:empty {
	display: none;
}

.btn .badge {
	position: relative;
	top: -1px;
}

.badge-pill {
	padding-right: 0.6em;
	padding-left: 0.6em;
	border-radius: 10rem;
}

.badge-primary {
	color: #fff;
	background-color: #007bff;
}

a.badge-primary:hover, a.badge-primary:focus {
	color: #fff;
	background-color: #0062cc;
}

.badge-secondary {
	color: #fff;
	background-color: #6c757d;
}

a.badge-secondary:hover, a.badge-secondary:focus {
	color: #fff;
	background-color: #545b62;
}

.badge-success {
	color: #fff;
	background-color: #28a745;
}

a.badge-success:hover, a.badge-success:focus {
	color: #fff;
	background-color: #1e7e34;
}

.badge-info {
	color: #fff;
	background-color: #17a2b8;
}

a.badge-info:hover, a.badge-info:focus {
	color: #fff;
	background-color: #117a8b;
}

.badge-warning {
	color: #212529;
	background-color: #ffc107;
}

a.badge-warning:hover, a.badge-warning:focus {
	color: #212529;
	background-color: #d39e00;
}

.badge-danger {
	color: #fff;
	background-color: #dc3545;
}

a.badge-danger:hover, a.badge-danger:focus {
	color: #fff;
	background-color: #bd2130;
}

.badge-light {
	color: #212529;
	background-color: #f8f9fa;
}

a.badge-light:hover, a.badge-light:focus {
	color: #212529;
	background-color: #dae0e5;
}

.badge-dark {
	color: #fff;
	background-color: #343a40;
}

a.badge-dark:hover, a.badge-dark:focus {
	color: #fff;
	background-color: #1d2124;
}

.jumbotron {
	padding: 2rem 1rem;
	margin-bottom: 2rem;
	background-color: #e9ecef;
	border-radius: 0.3rem;
}

@media (min-width: 576px) {
	.jumbotron {
		padding: 4rem 2rem;
	}
}

.jumbotron-fluid {
	padding-right: 0;
	padding-left: 0;
	border-radius: 0;
}

.alert {
	position: relative;
	padding: 0.75rem 1.25rem;
	margin-bottom: 1rem;
	border: 1px solid transparent;
	border-radius: 0.25rem;
}

.alert-heading {
	color: inherit;
}

.alert-link {
	font-weight: 700;
}

.alert-dismissible {
	padding-right: 4rem;
}

.alert-dismissible .close {
	position: absolute;
	top: 0;
	right: 0;
	padding: 0.75rem 1.25rem;
	color: inherit;
}

.alert-primary {
	color: #004085;
	background-color: #cce5ff;
	border-color: #b8daff;
}

.alert-primary hr {
	border-top-color: #9fcdff;
}

.alert-primary .alert-link {
	color: #002752;
}

.alert-secondary {
	color: #383d41;
	background-color: #e2e3e5;
	border-color: #d6d8db;
}

.alert-secondary hr {
	border-top-color: #c8cbcf;
}

.alert-secondary .alert-link {
	color: #202326;
}

.alert-success {
	color: #155724;
	background-color: #d4edda;
	border-color: #c3e6cb;
}

.alert-success hr {
	border-top-color: #b1dfbb;
}

.alert-success .alert-link {
	color: #0b2e13;
}

.alert-info {
	color: #0c5460;
	background-color: #d1ecf1;
	border-color: #bee5eb;
}

.alert-info hr {
	border-top-color: #abdde5;
}

.alert-info .alert-link {
	color: #062c33;
}

.alert-warning {
	color: #856404;
	background-color: #fff3cd;
	border-color: #ffeeba;
}

.alert-warning hr {
	border-top-color: #ffe8a1;
}

.alert-warning .alert-link {
	color: #533f03;
}

.alert-danger {
	color: #721c24;
	background-color: #f8d7da;
	border-color: #f5c6cb;
}

.alert-danger hr {
	border-top-color: #f1b0b7;
}

.alert-danger .alert-link {
	color: #491217;
}

.alert-light {
	color: #818182;
	background-color: #fefefe;
	border-color: #fdfdfe;
}

.alert-light hr {
	border-top-color: #ececf6;
}

.alert-light .alert-link {
	color: #686868;
}

.alert-dark {
	color: #1b1e21;
	background-color: #d6d8d9;
	border-color: #c6c8ca;
}

.alert-dark hr {
	border-top-color: #b9bbbe;
}

.alert-dark .alert-link {
	color: #040505;
}

@-webkit-keyframes progress-bar-stripes {
	from {
		background-position: 1rem 0;
	}
	to {
		background-position: 0 0;
	}
}

@keyframes progress-bar-stripes {
	from {
		background-position: 1rem 0;
	}
	to {
		background-position: 0 0;
	}
}

.progress {
	display: -ms-flexbox;
	display: flex;
	height: 1rem;
	overflow: hidden;
	font-size: 0.75rem;
	background-color: #e9ecef;
	border-radius: 0.25rem;
}

.progress-bar {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	-ms-flex-pack: center;
	justify-content: center;
	color: #fff;
	text-align: center;
	white-space: nowrap;
	background-color: #007bff;
	transition: width 0.6s ease;
}

@media screen and (prefers-reduced-motion: reduce) {
	.progress-bar {
		transition: none;
	}
}

.progress-bar-striped {
	background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
	background-size: 1rem 1rem;
}

.progress-bar-animated {
	-webkit-animation: progress-bar-stripes 1s linear infinite;
	animation: progress-bar-stripes 1s linear infinite;
}

.media {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: start;
	align-items: flex-start;
}

.media-body {
	-ms-flex: 1;
	flex: 1;
}

.list-group {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	padding-left: 0;
	margin-bottom: 0;
}

.list-group-item-action {
	width: 100%;
	color: #495057;
	text-align: inherit;
}

.list-group-item-action:hover, .list-group-item-action:focus {
	/*   color: #495057; */
	color: #003893;
	text-decoration: underline !important;
	background-color: #f8f9fa;
}

.list-group-item-action:active {
	color: #212529;
	background-color: #e9ecef;
}

.list-group-item {
	position: relative;
	display: block;
	padding: 0.75rem 1.25rem;
	margin-bottom: -1px;
	background-color: #fff;
	border: 1px solid rgba(0, 0, 0, 0.125);
}

.list-group-item:first-child {
	border-top-left-radius: 0.25rem;
	border-top-right-radius: 0.25rem;
}

.list-group-item:last-child {
	margin-bottom: 0;
	border-bottom-right-radius: 0.25rem;
	border-bottom-left-radius: 0.25rem;
}

.list-group-item:hover, .list-group-item:focus {
	z-index: 1;
	text-decoration: none;
}

.list-group-item.disabled, .list-group-item:disabled {
	color: #6c757d;
	pointer-events: none;
	background-color: #fff;
}

.list-group-item.active {
	z-index: 2;
	color: #fff;
	background-color: #007bff;
	border-color: #007bff;
}

.list-group-flush .list-group-item {
	border-right: 0;
	border-left: 0;
	border-radius: 0;
}

.list-group-flush .list-group-item:last-child {
	margin-bottom: -1px;
}

.list-group-flush:first-child .list-group-item:first-child {
	border-top: 0;
}

.list-group-flush:last-child .list-group-item:last-child {
	margin-bottom: 0;
	border-bottom: 0;
}

.list-group-item-primary {
	color: #004085;
	background-color: #b8daff;
}

.list-group-item-primary.list-group-item-action:hover, .list-group-item-primary.list-group-item-action:focus {
	color: #004085;
	background-color: #9fcdff;
}

.list-group-item-primary.list-group-item-action.active {
	color: #fff;
	background-color: #004085;
	border-color: #004085;
}

.list-group-item-secondary {
	color: #383d41;
	background-color: #d6d8db;
}

.list-group-item-secondary.list-group-item-action:hover, .list-group-item-secondary.list-group-item-action:focus {
	color: #383d41;
	background-color: #c8cbcf;
}

.list-group-item-secondary.list-group-item-action.active {
	color: #fff;
	background-color: #383d41;
	border-color: #383d41;
}

.list-group-item-success {
	color: #155724;
	background-color: #c3e6cb;
}

.list-group-item-success.list-group-item-action:hover, .list-group-item-success.list-group-item-action:focus {
	color: #155724;
	background-color: #b1dfbb;
}

.list-group-item-success.list-group-item-action.active {
	color: #fff;
	background-color: #155724;
	border-color: #155724;
}

.list-group-item-info {
	color: #0c5460;
	background-color: #bee5eb;
}

.list-group-item-info.list-group-item-action:hover, .list-group-item-info.list-group-item-action:focus {
	color: #0c5460;
	background-color: #abdde5;
}

.list-group-item-info.list-group-item-action.active {
	color: #fff;
	background-color: #0c5460;
	border-color: #0c5460;
}

.list-group-item-warning {
	color: #856404;
	background-color: #ffeeba;
}

.list-group-item-warning.list-group-item-action:hover, .list-group-item-warning.list-group-item-action:focus {
	color: #856404;
	background-color: #ffe8a1;
}

.list-group-item-warning.list-group-item-action.active {
	color: #fff;
	background-color: #856404;
	border-color: #856404;
}

.list-group-item-danger {
	color: #721c24;
	background-color: #f5c6cb;
}

.list-group-item-danger.list-group-item-action:hover, .list-group-item-danger.list-group-item-action:focus {
	color: #721c24;
	background-color: #f1b0b7;
}

.list-group-item-danger.list-group-item-action.active {
	color: #fff;
	background-color: #721c24;
	border-color: #721c24;
}

.list-group-item-light {
	color: #818182;
	background-color: #fdfdfe;
}

.list-group-item-light.list-group-item-action:hover, .list-group-item-light.list-group-item-action:focus {
	color: #818182;
	background-color: #ececf6;
}

.list-group-item-light.list-group-item-action.active {
	color: #fff;
	background-color: #818182;
	border-color: #818182;
}

.list-group-item-dark {
	color: #1b1e21;
	background-color: #c6c8ca;
}

.list-group-item-dark.list-group-item-action:hover, .list-group-item-dark.list-group-item-action:focus {
	color: #1b1e21;
	background-color: #b9bbbe;
}

.list-group-item-dark.list-group-item-action.active {
	color: #fff;
	background-color: #1b1e21;
	border-color: #1b1e21;
}

.close {
	float: right;
	font-size: 1.5rem;
	font-weight: 700;
	line-height: 1;
	color: #000;
	text-shadow: 0 1px 0 #fff;
	opacity: .5;
}

.close:hover {
	color: #000;
	text-decoration: none;
}

.close:not(:disabled):not(.disabled) {
	cursor: pointer;
}

.close:not(:disabled):not(.disabled):hover, .close:not(:disabled):not(.disabled):focus {
	opacity: .75;
}

button.close {
	padding: 0;
	background-color: transparent;
	border: 0;
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
}

a.close.disabled {
	pointer-events: none;
}

.toast {
	max-width: 350px;
	overflow: hidden;
	font-size: 0.875rem;
	background-color: rgba(255, 255, 255, 0.85);
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.1);
	border-radius: 0.25rem;
	box-shadow: 0 0.25rem 0.75rem rgba(0, 0, 0, 0.1);
	-webkit-backdrop-filter: blur(10px);
	backdrop-filter: blur(10px);
	opacity: 0;
}

.toast:not(:last-child) {
	margin-bottom: 0.75rem;
}

.toast.showing {
	opacity: 1;
}

.toast.show {
	display: block;
	opacity: 1;
}

.toast.hide {
	display: none;
}

.toast-header {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: center;
	align-items: center;
	padding: 0.25rem 0.75rem;
	color: #6c757d;
	background-color: rgba(255, 255, 255, 0.85);
	background-clip: padding-box;
	border-bottom: 1px solid rgba(0, 0, 0, 0.05);
}

.toast-body {
	padding: 0.75rem;
}

.modal-open {
	overflow: hidden;
}

.modal-open .modal {
	overflow-x: hidden;
	overflow-y: auto;
}

.modal {
	position: fixed;
	top: 0;
	left: 0;
	z-index: 1050;
	display: none;
	width: 100%;
	height: 100%;
	overflow: hidden;
	outline: 0;
}

.modal-dialog {
	position: relative;
	width: auto;
	margin: 0.5rem;
	pointer-events: none;
}

.modal.fade .modal-dialog {
	transition: -webkit-transform 0.3s ease-out;
	transition: transform 0.3s ease-out;
	transition: transform 0.3s ease-out, -webkit-transform 0.3s ease-out;
	-webkit-transform: translate(0, -50px);
	transform: translate(0, -50px);
}

@media screen and (prefers-reduced-motion: reduce) {
	.modal.fade .modal-dialog {
		transition: none;
	}
}

.modal.show .modal-dialog {
	-webkit-transform: none;
	transform: none;
}

.modal-dialog-centered {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: center;
	align-items: center;
	min-height: calc(100% - (0.5rem * 2));
}

.modal-dialog-centered::before {
	display: block;
	height: calc(100vh - (0.5rem * 2));
	content: "";
}

.modal-content {
	position: relative;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	width: 100%;
	pointer-events: auto;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.2);
	border-radius: 0.3rem;
	outline: 0;
}

.modal-backdrop {
	position: fixed;
	top: 0;
	left: 0;
	z-index: 1040;
	width: 100vw;
	height: 100vh;
	background-color: #000;
}

.modal-backdrop.fade {
	opacity: 0;
}

.modal-backdrop.show {
	opacity: 0.5;
}

.modal-header {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: start;
	align-items: flex-start;
	-ms-flex-pack: justify;
	justify-content: space-between;
	padding: 1rem 1rem;
	border-bottom: 1px solid #e9ecef;
	border-top-left-radius: 0.3rem;
	border-top-right-radius: 0.3rem;
}

.modal-header .close {
	padding: 1rem 1rem;
	margin: -1rem -1rem -1rem auto;
}

.modal-title {
	margin-bottom: 0;
	line-height: 1.5;
}

.modal-body {
	position: relative;
	-ms-flex: 1 1 auto;
	flex: 1 1 auto;
	padding: 1rem;
}

.modal-footer {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-pack: end;
	justify-content: flex-end;
	padding: 1rem;
	border-top: 1px solid #e9ecef;
	border-bottom-right-radius: 0.3rem;
	border-bottom-left-radius: 0.3rem;
}

.modal-footer > :not(:first-child) {
	margin-left: .25rem;
}

.modal-footer > :not(:last-child) {
	margin-right: .25rem;
}

.modal-scrollbar-measure {
	position: absolute;
	top: -9999px;
	width: 50px;
	height: 50px;
	overflow: scroll;
}

@media (min-width: 576px) {
	.modal-dialog {
		max-width: 500px;
		margin: 1.75rem auto;
	}
	.modal-dialog-centered {
		min-height: calc(100% - (1.75rem * 2));
	}
	.modal-dialog-centered::before {
		height: calc(100vh - (1.75rem * 2));
	}
	.modal-sm {
		max-width: 300px;
	}
}

@media (min-width: 992px) {
	.modal-lg,
	.modal-xl {
		max-width: 800px;
	}
}

@media (min-width: 1200px) {
	.modal-xl {
		max-width: 1140px;
	}
}

.tooltip {
	position: absolute;
	z-index: 1070;
	display: block;
	margin: 0;
	font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
	font-style: normal;
	font-weight: 400;
	line-height: 1.5;
	text-align: left;
	text-align: start;
	text-decoration: none;
	text-shadow: none;
	text-transform: none;
	letter-spacing: normal;
	word-break: normal;
	word-spacing: normal;
	white-space: normal;
	line-break: auto;
	font-size: 0.875rem;
	word-wrap: break-word;
	opacity: 0;
}

.tooltip.show {
	opacity: 0.9;
}

.tooltip .arrow {
	position: absolute;
	display: block;
	width: 0.8rem;
	height: 0.4rem;
}

.tooltip .arrow::before {
	position: absolute;
	content: "";
	border-color: transparent;
	border-style: solid;
}

.bs-tooltip-top, .bs-tooltip-auto[x-placement^="top"] {
	padding: 0.4rem 0;
}

.bs-tooltip-top .arrow, .bs-tooltip-auto[x-placement^="top"] .arrow {
	bottom: 0;
}

.bs-tooltip-top .arrow::before, .bs-tooltip-auto[x-placement^="top"] .arrow::before {
	top: 0;
	border-width: 0.4rem 0.4rem 0;
	border-top-color: #000;
}

.bs-tooltip-right, .bs-tooltip-auto[x-placement^="right"] {
	padding: 0 0.4rem;
}

.bs-tooltip-right .arrow, .bs-tooltip-auto[x-placement^="right"] .arrow {
	left: 0;
	width: 0.4rem;
	height: 0.8rem;
}

.bs-tooltip-right .arrow::before, .bs-tooltip-auto[x-placement^="right"] .arrow::before {
	right: 0;
	border-width: 0.4rem 0.4rem 0.4rem 0;
	border-right-color: #000;
}

.bs-tooltip-bottom, .bs-tooltip-auto[x-placement^="bottom"] {
	padding: 0.4rem 0;
}

.bs-tooltip-bottom .arrow, .bs-tooltip-auto[x-placement^="bottom"] .arrow {
	top: 0;
}

.bs-tooltip-bottom .arrow::before, .bs-tooltip-auto[x-placement^="bottom"] .arrow::before {
	bottom: 0;
	border-width: 0 0.4rem 0.4rem;
	border-bottom-color: #000;
}

.bs-tooltip-left, .bs-tooltip-auto[x-placement^="left"] {
	padding: 0 0.4rem;
}

.bs-tooltip-left .arrow, .bs-tooltip-auto[x-placement^="left"] .arrow {
	right: 0;
	width: 0.4rem;
	height: 0.8rem;
}

.bs-tooltip-left .arrow::before, .bs-tooltip-auto[x-placement^="left"] .arrow::before {
	left: 0;
	border-width: 0.4rem 0 0.4rem 0.4rem;
	border-left-color: #000;
}

.tooltip-inner {
	max-width: 200px;
	padding: 0.25rem 0.5rem;
	color: #fff;
	text-align: center;
	background-color: #000;
	border-radius: 0.25rem;
}

.popover {
	position: absolute;
	top: 0;
	left: 0;
	z-index: 1060;
	display: block;
	max-width: 276px;
	font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
	font-style: normal;
	font-weight: 400;
	line-height: 1.5;
	text-align: left;
	text-align: start;
	text-decoration: none;
	text-shadow: none;
	text-transform: none;
	letter-spacing: normal;
	word-break: normal;
	word-spacing: normal;
	white-space: normal;
	line-break: auto;
	font-size: 0.875rem;
	word-wrap: break-word;
	background-color: #fff;
	background-clip: padding-box;
	border: 1px solid rgba(0, 0, 0, 0.2);
	border-radius: 0.3rem;
}

.popover .arrow {
	position: absolute;
	display: block;
	width: 1rem;
	height: 0.5rem;
	margin: 0 0.3rem;
}

.popover .arrow::before, .popover .arrow::after {
	position: absolute;
	display: block;
	content: "";
	border-color: transparent;
	border-style: solid;
}

.bs-popover-top, .bs-popover-auto[x-placement^="top"] {
	margin-bottom: 0.5rem;
}

.bs-popover-top .arrow, .bs-popover-auto[x-placement^="top"] .arrow {
	bottom: calc((0.5rem + 1px) * -1);
}

.bs-popover-top .arrow::before, .bs-popover-auto[x-placement^="top"] .arrow::before,
.bs-popover-top .arrow::after,
.bs-popover-auto[x-placement^="top"] .arrow::after {
	border-width: 0.5rem 0.5rem 0;
}

.bs-popover-top .arrow::before, .bs-popover-auto[x-placement^="top"] .arrow::before {
	bottom: 0;
	border-top-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-top .arrow::after,
.bs-popover-auto[x-placement^="top"] .arrow::after {
	bottom: 1px;
	border-top-color: #fff;
}

.bs-popover-right, .bs-popover-auto[x-placement^="right"] {
	margin-left: 0.5rem;
}

.bs-popover-right .arrow, .bs-popover-auto[x-placement^="right"] .arrow {
	left: calc((0.5rem + 1px) * -1);
	width: 0.5rem;
	height: 1rem;
	margin: 0.3rem 0;
}

.bs-popover-right .arrow::before, .bs-popover-auto[x-placement^="right"] .arrow::before,
.bs-popover-right .arrow::after,
.bs-popover-auto[x-placement^="right"] .arrow::after {
	border-width: 0.5rem 0.5rem 0.5rem 0;
}

.bs-popover-right .arrow::before, .bs-popover-auto[x-placement^="right"] .arrow::before {
	left: 0;
	border-right-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-right .arrow::after,
.bs-popover-auto[x-placement^="right"] .arrow::after {
	left: 1px;
	border-right-color: #fff;
}

.bs-popover-bottom, .bs-popover-auto[x-placement^="bottom"] {
	margin-top: 0.5rem;
}

.bs-popover-bottom .arrow, .bs-popover-auto[x-placement^="bottom"] .arrow {
	top: calc((0.5rem + 1px) * -1);
}

.bs-popover-bottom .arrow::before, .bs-popover-auto[x-placement^="bottom"] .arrow::before,
.bs-popover-bottom .arrow::after,
.bs-popover-auto[x-placement^="bottom"] .arrow::after {
	border-width: 0 0.5rem 0.5rem 0.5rem;
}

.bs-popover-bottom .arrow::before, .bs-popover-auto[x-placement^="bottom"] .arrow::before {
	top: 0;
	border-bottom-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-bottom .arrow::after,
.bs-popover-auto[x-placement^="bottom"] .arrow::after {
	top: 1px;
	border-bottom-color: #fff;
}

.bs-popover-bottom .popover-header::before, .bs-popover-auto[x-placement^="bottom"] .popover-header::before {
	position: absolute;
	top: 0;
	left: 50%;
	display: block;
	width: 1rem;
	margin-left: -0.5rem;
	content: "";
	border-bottom: 1px solid #f7f7f7;
}

.bs-popover-left, .bs-popover-auto[x-placement^="left"] {
	margin-right: 0.5rem;
}

.bs-popover-left .arrow, .bs-popover-auto[x-placement^="left"] .arrow {
	right: calc((0.5rem + 1px) * -1);
	width: 0.5rem;
	height: 1rem;
	margin: 0.3rem 0;
}

.bs-popover-left .arrow::before, .bs-popover-auto[x-placement^="left"] .arrow::before,
.bs-popover-left .arrow::after,
.bs-popover-auto[x-placement^="left"] .arrow::after {
	border-width: 0.5rem 0 0.5rem 0.5rem;
}

.bs-popover-left .arrow::before, .bs-popover-auto[x-placement^="left"] .arrow::before {
	right: 0;
	border-left-color: rgba(0, 0, 0, 0.25);
}


.bs-popover-left .arrow::after,
.bs-popover-auto[x-placement^="left"] .arrow::after {
	right: 1px;
	border-left-color: #fff;
}

.popover-header {
	padding: 0.5rem 0.75rem;
	margin-bottom: 0;
	font-size: 1rem;
	color: inherit;
	background-color: #f7f7f7;
	border-bottom: 1px solid #ebebeb;
	border-top-left-radius: calc(0.3rem - 1px);
	border-top-right-radius: calc(0.3rem - 1px);
}

.popover-header:empty {
	display: none;
}

.popover-body {
	padding: 0.5rem 0.75rem;
	color: #212529;
}

.carousel {
	position: relative;
}

.carousel.pointer-event {
	-ms-touch-action: pan-y;
	touch-action: pan-y;
}

.carousel-inner {
	position: relative;
	width: 100%;
	overflow: hidden;
}

.carousel-inner::after {
	display: block;
	clear: both;
	content: "";
}

.carousel-item {
	position: relative;
	display: none;
	float: left;
	width: 100%;
	margin-right: -100%;
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	transition: -webkit-transform 0.6s ease-in-out;
	transition: transform 0.6s ease-in-out;
	transition: transform 0.6s ease-in-out, -webkit-transform 0.6s ease-in-out;
}

@media screen and (prefers-reduced-motion: reduce) {
	.carousel-item {
		transition: none;
	}
}

.carousel-item.active,
.carousel-item-next,
.carousel-item-prev {
	display: block;
}

.carousel-item-next:not(.carousel-item-left),
.active.carousel-item-right {
	-webkit-transform: translateX(100%);
	transform: translateX(100%);
}

.carousel-item-prev:not(.carousel-item-right),
.active.carousel-item-left {
	-webkit-transform: translateX(-100%);
	transform: translateX(-100%);
}

.carousel-fade .carousel-item {
	opacity: 0;
	transition-property: opacity;
	-webkit-transform: none;
	transform: none;
}

.carousel-fade .carousel-item.active,
.carousel-fade .carousel-item-next.carousel-item-left,
.carousel-fade .carousel-item-prev.carousel-item-right {
	z-index: 1;
	opacity: 1;
}

.carousel-fade .active.carousel-item-left,
.carousel-fade .active.carousel-item-right {
	z-index: 0;
	opacity: 0;
	transition: 0s 0.6s opacity;
}

@media screen and (prefers-reduced-motion: reduce) {
	.carousel-fade .active.carousel-item-left,
	.carousel-fade .active.carousel-item-right {
		transition: none;
	}
}

.carousel-control-prev,
.carousel-control-next {
	position: absolute;
	top: 0;
	bottom: 0;
	z-index: 1;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-align: center;
	align-items: center;
	-ms-flex-pack: center;
	justify-content: center;
	width: 15%;
	color: #fff;
	text-align: center;
	opacity: 0.5;
	transition: opacity 0.15s ease;
}

@media screen and (prefers-reduced-motion: reduce) {
	.carousel-control-prev,
	.carousel-control-next {
		transition: none;
	}
}

.carousel-control-prev:hover, .carousel-control-prev:focus,
.carousel-control-next:hover,
.carousel-control-next:focus {
	color: #fff;
	text-decoration: none;
	outline: 0;
	opacity: 0.9;
}

.carousel-control-prev {
	left: 0;
}

.carousel-control-next {
	right: 0;
}

.carousel-control-prev-icon,
.carousel-control-next-icon {
	display: inline-block;
	width: 20px;
	height: 20px;
	background: transparent no-repeat center center;
	background-size: 100% 100%;
}

.carousel-control-prev-icon {
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3e%3cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3e%3c/svg%3e");
}

.carousel-control-next-icon {
	background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3e%3cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3e%3c/svg%3e");
}

.carousel-indicators {
	position: absolute;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 15;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-pack: center;
	justify-content: center;
	padding-left: 0;
	margin-right: 15%;
	margin-left: 15%;
	list-style: none;
}

.carousel-indicators li {
	box-sizing: content-box;
	-ms-flex: 0 1 auto;
	flex: 0 1 auto;
	width: 30px;
	height: 3px;
	margin-right: 3px;
	margin-left: 3px;
	text-indent: -999px;
	cursor: pointer;
	background-color: #fff;
	background-clip: padding-box;
	border-top: 10px solid transparent;
	border-bottom: 10px solid transparent;
	opacity: .5;
	transition: opacity 0.6s ease;
}

@media screen and (prefers-reduced-motion: reduce) {
	.carousel-indicators li {
		transition: none;
	}
}

.carousel-indicators .active {
	opacity: 1;
}

.carousel-caption {
	position: absolute;
	right: 15%;
	bottom: 20px;
	left: 15%;
	z-index: 10;
	padding-top: 20px;
	padding-bottom: 20px;
	color: #fff;
	text-align: center;
}

@-webkit-keyframes spinner-border {
	to {
		-webkit-transform: rotate(360deg);
		transform: rotate(360deg);
	}
}

@keyframes spinner-border {
	to {
		-webkit-transform: rotate(360deg);
		transform: rotate(360deg);
	}
}

.spinner-border {
	display: inline-block;
	width: 2rem;
	height: 2rem;
	vertical-align: text-bottom;
	border: 0.25em solid currentColor;
	border-right-color: transparent;
	border-radius: 50%;
	-webkit-animation: spinner-border .75s linear infinite;
	animation: spinner-border .75s linear infinite;
}

.spinner-border-sm {
	width: 1rem;
	height: 1rem;
	border-width: 0.2em;
}

@-webkit-keyframes spinner-grow {
	0% {
		-webkit-transform: scale(0);
		transform: scale(0);
	}
	50% {
		opacity: 1;
	}
}

@keyframes spinner-grow {
	0% {
		-webkit-transform: scale(0);
		transform: scale(0);
	}
	50% {
		opacity: 1;
	}
}

.spinner-grow {
	display: inline-block;
	width: 2rem;
	height: 2rem;
	vertical-align: text-bottom;
	background-color: currentColor;
	border-radius: 50%;
	opacity: 0;
	-webkit-animation: spinner-grow .75s linear infinite;
	animation: spinner-grow .75s linear infinite;
}

.spinner-grow-sm {
	width: 1rem;
	height: 1rem;
}

.align-baseline {
	vertical-align: baseline !important;
}

.align-top {
	vertical-align: top !important;
}

.align-middle {
	vertical-align: middle !important;
}

.align-bottom {
	vertical-align: bottom !important;
}

.align-text-bottom {
	vertical-align: text-bottom !important;
}

.align-text-top {
	vertical-align: text-top !important;
}

.bg-primary {
	background-color: #007bff !important;
}

a.bg-primary:hover, a.bg-primary:focus,
button.bg-primary:hover,
button.bg-primary:focus {
	background-color: #0062cc !important;
}

.bg-secondary {
	background-color: #6c757d !important;
}

a.bg-secondary:hover, a.bg-secondary:focus,
button.bg-secondary:hover,
button.bg-secondary:focus {
	background-color: #545b62 !important;
}

.bg-success {
	background-color: #28a745 !important;
}

a.bg-success:hover, a.bg-success:focus,
button.bg-success:hover,
button.bg-success:focus {
	background-color: #1e7e34 !important;
}

.bg-info {
	background-color: #17a2b8 !important;
}

a.bg-info:hover, a.bg-info:focus,
button.bg-info:hover,
button.bg-info:focus {
	background-color: #117a8b !important;
}

.bg-warning {
	background-color: #ffc107 !important;
}

a.bg-warning:hover, a.bg-warning:focus,
button.bg-warning:hover,
button.bg-warning:focus {
	background-color: #d39e00 !important;
}

.bg-danger {
	background-color: #dc3545 !important;
}

a.bg-danger:hover, a.bg-danger:focus,
button.bg-danger:hover,
button.bg-danger:focus {
	background-color: #bd2130 !important;
}

.bg-light {
	background-color: #f8f9fa !important;
}

a.bg-light:hover, a.bg-light:focus,
button.bg-light:hover,
button.bg-light:focus {
	background-color: #dae0e5 !important;
}

.bg-dark {
	background-color: #343a40 !important;
}

a.bg-dark:hover, a.bg-dark:focus,
button.bg-dark:hover,
button.bg-dark:focus {
	background-color: #1d2124 !important;
}

.bg-white {
	background-color: #fff !important;
}

.bg-transparent {
	background-color: transparent !important;
}

.border {
	border: 1px solid #dee2e6 !important;
}

.border-top {
	border-top: 1px solid #dee2e6 !important;
}

.border-right {
	border-right: 1px solid #dee2e6 !important;
}

.border-bottom {
	border-bottom: 1px solid #dee2e6 !important;
}

.border-left {
	border-left: 1px solid #dee2e6 !important;
}

.border-0 {
	border: 0 !important;
}

.border-top-0 {
	border-top: 0 !important;
}

.border-right-0 {
	border-right: 0 !important;
}

.border-bottom-0 {
	border-bottom: 0 !important;
}

.border-left-0 {
	border-left: 0 !important;
}

.border-primary {
	border-color: #007bff !important;
}

.border-secondary {
	border-color: #6c757d !important;
}

.border-success {
	border-color: #28a745 !important;
}

.border-info {
	border-color: #17a2b8 !important;
}

.border-warning {
	border-color: #ffc107 !important;
}

.border-danger {
	border-color: #dc3545 !important;
}

.border-light {
	border-color: #f8f9fa !important;
}

.border-dark {
	border-color: #343a40 !important;
}

.border-white {
	border-color: #fff !important;
}

.rounded {
	border-radius: 0.25rem !important;
}

.rounded-top {
	border-top-left-radius: 0.25rem !important;
	border-top-right-radius: 0.25rem !important;
}

.rounded-right {
	border-top-right-radius: 0.25rem !important;
	border-bottom-right-radius: 0.25rem !important;
}

.rounded-bottom {
	border-bottom-right-radius: 0.25rem !important;
	border-bottom-left-radius: 0.25rem !important;
}

.rounded-left {
	border-top-left-radius: 0.25rem !important;
	border-bottom-left-radius: 0.25rem !important;
}

.rounded-circle {
	border-radius: 50% !important;
}

.rounded-pill {
	border-radius: 50rem !important;
}

.rounded-0 {
	border-radius: 0 !important;
}

.clearfix::after {
	display: block;
	clear: both;
	content: "";
}

.d-none {
	display: none !important;
}

.d-inline {
	display: inline !important;
}

.d-inline-block {
	display: inline-block !important;
}

.d-block {
	display: block !important;
}

.d-table {
	display: table !important;
}

.d-table-row {
	display: table-row !important;
}

.d-table-cell {
	display: table-cell !important;
}

.d-flex {
	display: -ms-flexbox !important;
	display: flex !important;
}

.d-inline-flex {
	display: -ms-inline-flexbox !important;
	display: inline-flex !important;
}

@media (min-width: 576px) {
	.d-sm-none {
		display: none !important;
	}
	.d-sm-inline {
		display: inline !important;
	}
	.d-sm-inline-block {
		display: inline-block !important;
	}
	.d-sm-block {
		display: block !important;
	}
	.d-sm-table {
		display: table !important;
	}
	.d-sm-table-row {
		display: table-row !important;
	}
	.d-sm-table-cell {
		display: table-cell !important;
	}
	.d-sm-flex {
		display: -ms-flexbox !important;
		display: flex !important;
	}
	.d-sm-inline-flex {
		display: -ms-inline-flexbox !important;
		display: inline-flex !important;
	}
}

@media (min-width: 768px) {
	.d-md-none {
		display: none !important;
	}
	.d-md-inline {
		display: inline !important;
	}
	.d-md-inline-block {
		display: inline-block !important;
	}
	.d-md-block {
		display: block !important;
	}
	.d-md-table {
		display: table !important;
	}
	.d-md-table-row {
		display: table-row !important;
	}
	.d-md-table-cell {
		display: table-cell !important;
	}
	.d-md-flex {
		display: -ms-flexbox !important;
		display: flex !important;
	}
	.d-md-inline-flex {
		display: -ms-inline-flexbox !important;
		display: inline-flex !important;
	}
}

@media (min-width: 992px) {
	.d-lg-none {
		display: none !important;
	}
	.d-lg-inline {
		display: inline !important;
	}
	.d-lg-inline-block {
		display: inline-block !important;
	}
	.d-lg-block {
		display: block !important;
	}
	.d-lg-table {
		display: table !important;
	}
	.d-lg-table-row {
		display: table-row !important;
	}
	.d-lg-table-cell {
		display: table-cell !important;
	}
	.d-lg-flex {
		display: -ms-flexbox !important;
		display: flex !important;
	}
	.d-lg-inline-flex {
		display: -ms-inline-flexbox !important;
		display: inline-flex !important;
	}
}

@media (min-width: 1200px) {
	.d-xl-none {
		display: none !important;
	}
	.d-xl-inline {
		display: inline !important;
	}
	.d-xl-inline-block {
		display: inline-block !important;
	}
	.d-xl-block {
		display: block !important;
	}
	.d-xl-table {
		display: table !important;
	}
	.d-xl-table-row {
		display: table-row !important;
	}
	.d-xl-table-cell {
		display: table-cell !important;
	}
	.d-xl-flex {
		display: -ms-flexbox !important;
		display: flex !important;
	}
	.d-xl-inline-flex {
		display: -ms-inline-flexbox !important;
		display: inline-flex !important;
	}
}

@media print {
	.d-print-none {
		display: none !important;
	}
	.d-print-inline {
		display: inline !important;
	}
	.d-print-inline-block {
		display: inline-block !important;
	}
	.d-print-block {
		display: block !important;
	}
	.d-print-table {
		display: table !important;
	}
	.d-print-table-row {
		display: table-row !important;
	}
	.d-print-table-cell {
		display: table-cell !important;
	}
	.d-print-flex {
		display: -ms-flexbox !important;
		display: flex !important;
	}
	.d-print-inline-flex {
		display: -ms-inline-flexbox !important;
		display: inline-flex !important;
	}
}

.embed-responsive {
	position: relative;
	display: block;
	width: 100%;
	padding: 0;
	overflow: hidden;
}

.embed-responsive::before {
	display: block;
	content: "";
}

.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
	position: absolute;
	top: 0;
	bottom: 0;
	left: 0;
	width: 100%;
	height: 100%;
	border: 0;
}

.embed-responsive-21by9::before {
	padding-top: 42.857143%;
}

.embed-responsive-16by9::before {
	padding-top: 56.25%;
}

.embed-responsive-3by4::before {
	padding-top: 133.333333%;
}

.embed-responsive-1by1::before {
	padding-top: 100%;
}

.flex-row {
	-ms-flex-direction: row !important;
	flex-direction: row !important;
}

.flex-column {
	-ms-flex-direction: column !important;
	flex-direction: column !important;
}

.flex-row-reverse {
	-ms-flex-direction: row-reverse !important;
	flex-direction: row-reverse !important;
}

.flex-column-reverse {
	-ms-flex-direction: column-reverse !important;
	flex-direction: column-reverse !important;
}

.flex-wrap {
	-ms-flex-wrap: wrap !important;
	flex-wrap: wrap !important;
}

.flex-nowrap {
	-ms-flex-wrap: nowrap !important;
	flex-wrap: nowrap !important;
}

.flex-wrap-reverse {
	-ms-flex-wrap: wrap-reverse !important;
	flex-wrap: wrap-reverse !important;
}

.flex-fill {
	-ms-flex: 1 1 auto !important;
	flex: 1 1 auto !important;
}

.flex-grow-0 {
	-ms-flex-positive: 0 !important;
	flex-grow: 0 !important;
}

.flex-grow-1 {
	-ms-flex-positive: 1 !important;
	flex-grow: 1 !important;
}

.flex-shrink-0 {
	-ms-flex-negative: 0 !important;
	flex-shrink: 0 !important;
}

.flex-shrink-1 {
	-ms-flex-negative: 1 !important;
	flex-shrink: 1 !important;
}

.justify-content-start {
	-ms-flex-pack: start !important;
	justify-content: flex-start !important;
}

.justify-content-end {
	-ms-flex-pack: end !important;
	justify-content: flex-end !important;
}

.justify-content-center {
	-ms-flex-pack: center !important;
	justify-content: center !important;
}

.justify-content-between {
	-ms-flex-pack: justify !important;
	justify-content: space-between !important;
}

.justify-content-around {
	-ms-flex-pack: distribute !important;
	justify-content: space-around !important;
}

.align-items-start {
	-ms-flex-align: start !important;
	align-items: flex-start !important;
}

.align-items-end {
	-ms-flex-align: end !important;
	align-items: flex-end !important;
}

.align-items-center {
	-ms-flex-align: center !important;
	align-items: center !important;
}

.align-items-baseline {
	-ms-flex-align: baseline !important;
	align-items: baseline !important;
}

.align-items-stretch {
	-ms-flex-align: stretch !important;
	align-items: stretch !important;
}

.align-content-start {
	-ms-flex-line-pack: start !important;
	align-content: flex-start !important;
}

.align-content-end {
	-ms-flex-line-pack: end !important;
	align-content: flex-end !important;
}

.align-content-center {
	-ms-flex-line-pack: center !important;
	align-content: center !important;
}

.align-content-between {
	-ms-flex-line-pack: justify !important;
	align-content: space-between !important;
}

.align-content-around {
	-ms-flex-line-pack: distribute !important;
	align-content: space-around !important;
}

.align-content-stretch {
	-ms-flex-line-pack: stretch !important;
	align-content: stretch !important;
}

.align-self-auto {
	-ms-flex-item-align: auto !important;
	align-self: auto !important;
}

.align-self-start {
	-ms-flex-item-align: start !important;
	align-self: flex-start !important;
}

.align-self-end {
	-ms-flex-item-align: end !important;
	align-self: flex-end !important;
}

.align-self-center {
	-ms-flex-item-align: center !important;
	align-self: center !important;
}

.align-self-baseline {
	-ms-flex-item-align: baseline !important;
	align-self: baseline !important;
}

.align-self-stretch {
	-ms-flex-item-align: stretch !important;
	align-self: stretch !important;
}

@media (min-width: 576px) {
	.flex-sm-row {
		-ms-flex-direction: row !important;
		flex-direction: row !important;
	}
	.flex-sm-column {
		-ms-flex-direction: column !important;
		flex-direction: column !important;
	}
	.flex-sm-row-reverse {
		-ms-flex-direction: row-reverse !important;
		flex-direction: row-reverse !important;
	}
	.flex-sm-column-reverse {
		-ms-flex-direction: column-reverse !important;
		flex-direction: column-reverse !important;
	}
	.flex-sm-wrap {
		-ms-flex-wrap: wrap !important;
		flex-wrap: wrap !important;
	}
	.flex-sm-nowrap {
		-ms-flex-wrap: nowrap !important;
		flex-wrap: nowrap !important;
	}
	.flex-sm-wrap-reverse {
		-ms-flex-wrap: wrap-reverse !important;
		flex-wrap: wrap-reverse !important;
	}
	.flex-sm-fill {
		-ms-flex: 1 1 auto !important;
		flex: 1 1 auto !important;
	}
	.flex-sm-grow-0 {
		-ms-flex-positive: 0 !important;
		flex-grow: 0 !important;
	}
	.flex-sm-grow-1 {
		-ms-flex-positive: 1 !important;
		flex-grow: 1 !important;
	}
	.flex-sm-shrink-0 {
		-ms-flex-negative: 0 !important;
		flex-shrink: 0 !important;
	}
	.flex-sm-shrink-1 {
		-ms-flex-negative: 1 !important;
		flex-shrink: 1 !important;
	}
	.justify-content-sm-start {
		-ms-flex-pack: start !important;
		justify-content: flex-start !important;
	}
	.justify-content-sm-end {
		-ms-flex-pack: end !important;
		justify-content: flex-end !important;
	}
	.justify-content-sm-center {
		-ms-flex-pack: center !important;
		justify-content: center !important;
	}
	.justify-content-sm-between {
		-ms-flex-pack: justify !important;
		justify-content: space-between !important;
	}
	.justify-content-sm-around {
		-ms-flex-pack: distribute !important;
		justify-content: space-around !important;
	}
	.align-items-sm-start {
		-ms-flex-align: start !important;
		align-items: flex-start !important;
	}
	.align-items-sm-end {
		-ms-flex-align: end !important;
		align-items: flex-end !important;
	}
	.align-items-sm-center {
		-ms-flex-align: center !important;
		align-items: center !important;
	}
	.align-items-sm-baseline {
		-ms-flex-align: baseline !important;
		align-items: baseline !important;
	}
	.align-items-sm-stretch {
		-ms-flex-align: stretch !important;
		align-items: stretch !important;
	}
	.align-content-sm-start {
		-ms-flex-line-pack: start !important;
		align-content: flex-start !important;
	}
	.align-content-sm-end {
		-ms-flex-line-pack: end !important;
		align-content: flex-end !important;
	}
	.align-content-sm-center {
		-ms-flex-line-pack: center !important;
		align-content: center !important;
	}
	.align-content-sm-between {
		-ms-flex-line-pack: justify !important;
		align-content: space-between !important;
	}
	.align-content-sm-around {
		-ms-flex-line-pack: distribute !important;
		align-content: space-around !important;
	}
	.align-content-sm-stretch {
		-ms-flex-line-pack: stretch !important;
		align-content: stretch !important;
	}
	.align-self-sm-auto {
		-ms-flex-item-align: auto !important;
		align-self: auto !important;
	}
	.align-self-sm-start {
		-ms-flex-item-align: start !important;
		align-self: flex-start !important;
	}
	.align-self-sm-end {
		-ms-flex-item-align: end !important;
		align-self: flex-end !important;
	}
	.align-self-sm-center {
		-ms-flex-item-align: center !important;
		align-self: center !important;
	}
	.align-self-sm-baseline {
		-ms-flex-item-align: baseline !important;
		align-self: baseline !important;
	}
	.align-self-sm-stretch {
		-ms-flex-item-align: stretch !important;
		align-self: stretch !important;
	}
}

@media (min-width: 768px) {
	.flex-md-row {
		-ms-flex-direction: row !important;
		flex-direction: row !important;
	}
	.flex-md-column {
		-ms-flex-direction: column !important;
		flex-direction: column !important;
	}
	.flex-md-row-reverse {
		-ms-flex-direction: row-reverse !important;
		flex-direction: row-reverse !important;
	}
	.flex-md-column-reverse {
		-ms-flex-direction: column-reverse !important;
		flex-direction: column-reverse !important;
	}
	.flex-md-wrap {
		-ms-flex-wrap: wrap !important;
		flex-wrap: wrap !important;
	}
	.flex-md-nowrap {
		-ms-flex-wrap: nowrap !important;
		flex-wrap: nowrap !important;
	}
	.flex-md-wrap-reverse {
		-ms-flex-wrap: wrap-reverse !important;
		flex-wrap: wrap-reverse !important;
	}
	.flex-md-fill {
		-ms-flex: 1 1 auto !important;
		flex: 1 1 auto !important;
	}
	.flex-md-grow-0 {
		-ms-flex-positive: 0 !important;
		flex-grow: 0 !important;
	}
	.flex-md-grow-1 {
		-ms-flex-positive: 1 !important;
		flex-grow: 1 !important;
	}
	.flex-md-shrink-0 {
		-ms-flex-negative: 0 !important;
		flex-shrink: 0 !important;
	}
	.flex-md-shrink-1 {
		-ms-flex-negative: 1 !important;
		flex-shrink: 1 !important;
	}
	.justify-content-md-start {
		-ms-flex-pack: start !important;
		justify-content: flex-start !important;
	}
	.justify-content-md-end {
		-ms-flex-pack: end !important;
		justify-content: flex-end !important;
	}
	.justify-content-md-center {
		-ms-flex-pack: center !important;
		justify-content: center !important;
	}
	.justify-content-md-between {
		-ms-flex-pack: justify !important;
		justify-content: space-between !important;
	}
	.justify-content-md-around {
		-ms-flex-pack: distribute !important;
		justify-content: space-around !important;
	}
	.align-items-md-start {
		-ms-flex-align: start !important;
		align-items: flex-start !important;
	}
	.align-items-md-end {
		-ms-flex-align: end !important;
		align-items: flex-end !important;
	}
	.align-items-md-center {
		-ms-flex-align: center !important;
		align-items: center !important;
	}
	.align-items-md-baseline {
		-ms-flex-align: baseline !important;
		align-items: baseline !important;
	}
	.align-items-md-stretch {
		-ms-flex-align: stretch !important;
		align-items: stretch !important;
	}
	.align-content-md-start {
		-ms-flex-line-pack: start !important;
		align-content: flex-start !important;
	}
	.align-content-md-end {
		-ms-flex-line-pack: end !important;
		align-content: flex-end !important;
	}
	.align-content-md-center {
		-ms-flex-line-pack: center !important;
		align-content: center !important;
	}
	.align-content-md-between {
		-ms-flex-line-pack: justify !important;
		align-content: space-between !important;
	}
	.align-content-md-around {
		-ms-flex-line-pack: distribute !important;
		align-content: space-around !important;
	}
	.align-content-md-stretch {
		-ms-flex-line-pack: stretch !important;
		align-content: stretch !important;
	}
	.align-self-md-auto {
		-ms-flex-item-align: auto !important;
		align-self: auto !important;
	}
	.align-self-md-start {
		-ms-flex-item-align: start !important;
		align-self: flex-start !important;
	}
	.align-self-md-end {
		-ms-flex-item-align: end !important;
		align-self: flex-end !important;
	}
	.align-self-md-center {
		-ms-flex-item-align: center !important;
		align-self: center !important;
	}
	.align-self-md-baseline {
		-ms-flex-item-align: baseline !important;
		align-self: baseline !important;
	}
	.align-self-md-stretch {
		-ms-flex-item-align: stretch !important;
		align-self: stretch !important;
	}
}

@media (min-width: 992px) {
	.flex-lg-row {
		-ms-flex-direction: row !important;
		flex-direction: row !important;
	}
	.flex-lg-column {
		-ms-flex-direction: column !important;
		flex-direction: column !important;
	}
	.flex-lg-row-reverse {
		-ms-flex-direction: row-reverse !important;
		flex-direction: row-reverse !important;
	}
	.flex-lg-column-reverse {
		-ms-flex-direction: column-reverse !important;
		flex-direction: column-reverse !important;
	}
	.flex-lg-wrap {
		-ms-flex-wrap: wrap !important;
		flex-wrap: wrap !important;
	}
	.flex-lg-nowrap {
		-ms-flex-wrap: nowrap !important;
		flex-wrap: nowrap !important;
	}
	.flex-lg-wrap-reverse {
		-ms-flex-wrap: wrap-reverse !important;
		flex-wrap: wrap-reverse !important;
	}
	.flex-lg-fill {
		-ms-flex: 1 1 auto !important;
		flex: 1 1 auto !important;
	}
	.flex-lg-grow-0 {
		-ms-flex-positive: 0 !important;
		flex-grow: 0 !important;
	}
	.flex-lg-grow-1 {
		-ms-flex-positive: 1 !important;
		flex-grow: 1 !important;
	}
	.flex-lg-shrink-0 {
		-ms-flex-negative: 0 !important;
		flex-shrink: 0 !important;
	}
	.flex-lg-shrink-1 {
		-ms-flex-negative: 1 !important;
		flex-shrink: 1 !important;
	}
	.justify-content-lg-start {
		-ms-flex-pack: start !important;
		justify-content: flex-start !important;
	}
	.justify-content-lg-end {
		-ms-flex-pack: end !important;
		justify-content: flex-end !important;
	}
	.justify-content-lg-center {
		-ms-flex-pack: center !important;
		justify-content: center !important;
	}
	.justify-content-lg-between {
		-ms-flex-pack: justify !important;
		justify-content: space-between !important;
	}
	.justify-content-lg-around {
		-ms-flex-pack: distribute !important;
		justify-content: space-around !important;
	}
	.align-items-lg-start {
		-ms-flex-align: start !important;
		align-items: flex-start !important;
	}
	.align-items-lg-end {
		-ms-flex-align: end !important;
		align-items: flex-end !important;
	}
	.align-items-lg-center {
		-ms-flex-align: center !important;
		align-items: center !important;
	}
	.align-items-lg-baseline {
		-ms-flex-align: baseline !important;
		align-items: baseline !important;
	}
	.align-items-lg-stretch {
		-ms-flex-align: stretch !important;
		align-items: stretch !important;
	}
	.align-content-lg-start {
		-ms-flex-line-pack: start !important;
		align-content: flex-start !important;
	}
	.align-content-lg-end {
		-ms-flex-line-pack: end !important;
		align-content: flex-end !important;
	}
	.align-content-lg-center {
		-ms-flex-line-pack: center !important;
		align-content: center !important;
	}
	.align-content-lg-between {
		-ms-flex-line-pack: justify !important;
		align-content: space-between !important;
	}
	.align-content-lg-around {
		-ms-flex-line-pack: distribute !important;
		align-content: space-around !important;
	}
	.align-content-lg-stretch {
		-ms-flex-line-pack: stretch !important;
		align-content: stretch !important;
	}
	.align-self-lg-auto {
		-ms-flex-item-align: auto !important;
		align-self: auto !important;
	}
	.align-self-lg-start {
		-ms-flex-item-align: start !important;
		align-self: flex-start !important;
	}
	.align-self-lg-end {
		-ms-flex-item-align: end !important;
		align-self: flex-end !important;
	}
	.align-self-lg-center {
		-ms-flex-item-align: center !important;
		align-self: center !important;
	}
	.align-self-lg-baseline {
		-ms-flex-item-align: baseline !important;
		align-self: baseline !important;
	}
	.align-self-lg-stretch {
		-ms-flex-item-align: stretch !important;
		align-self: stretch !important;
	}
}

@media (min-width: 1200px) {
	.flex-xl-row {
		-ms-flex-direction: row !important;
		flex-direction: row !important;
	}
	.flex-xl-column {
		-ms-flex-direction: column !important;
		flex-direction: column !important;
	}
	.flex-xl-row-reverse {
		-ms-flex-direction: row-reverse !important;
		flex-direction: row-reverse !important;
	}
	.flex-xl-column-reverse {
		-ms-flex-direction: column-reverse !important;
		flex-direction: column-reverse !important;
	}
	.flex-xl-wrap {
		-ms-flex-wrap: wrap !important;
		flex-wrap: wrap !important;
	}
	.flex-xl-nowrap {
		-ms-flex-wrap: nowrap !important;
		flex-wrap: nowrap !important;
	}
	.flex-xl-wrap-reverse {
		-ms-flex-wrap: wrap-reverse !important;
		flex-wrap: wrap-reverse !important;
	}
	.flex-xl-fill {
		-ms-flex: 1 1 auto !important;
		flex: 1 1 auto !important;
	}
	.flex-xl-grow-0 {
		-ms-flex-positive: 0 !important;
		flex-grow: 0 !important;
	}
	.flex-xl-grow-1 {
		-ms-flex-positive: 1 !important;
		flex-grow: 1 !important;
	}
	.flex-xl-shrink-0 {
		-ms-flex-negative: 0 !important;
		flex-shrink: 0 !important;
	}
	.flex-xl-shrink-1 {
		-ms-flex-negative: 1 !important;
		flex-shrink: 1 !important;
	}
	.justify-content-xl-start {
		-ms-flex-pack: start !important;
		justify-content: flex-start !important;
	}
	.justify-content-xl-end {
		-ms-flex-pack: end !important;
		justify-content: flex-end !important;
	}
	.justify-content-xl-center {
		-ms-flex-pack: center !important;
		justify-content: center !important;
	}
	.justify-content-xl-between {
		-ms-flex-pack: justify !important;
		justify-content: space-between !important;
	}
	.justify-content-xl-around {
		-ms-flex-pack: distribute !important;
		justify-content: space-around !important;
	}
	.align-items-xl-start {
		-ms-flex-align: start !important;
		align-items: flex-start !important;
	}
	.align-items-xl-end {
		-ms-flex-align: end !important;
		align-items: flex-end !important;
	}
	.align-items-xl-center {
		-ms-flex-align: center !important;
		align-items: center !important;
	}
	.align-items-xl-baseline {
		-ms-flex-align: baseline !important;
		align-items: baseline !important;
	}
	.align-items-xl-stretch {
		-ms-flex-align: stretch !important;
		align-items: stretch !important;
	}
	.align-content-xl-start {
		-ms-flex-line-pack: start !important;
		align-content: flex-start !important;
	}
	.align-content-xl-end {
		-ms-flex-line-pack: end !important;
		align-content: flex-end !important;
	}
	.align-content-xl-center {
		-ms-flex-line-pack: center !important;
		align-content: center !important;
	}
	.align-content-xl-between {
		-ms-flex-line-pack: justify !important;
		align-content: space-between !important;
	}
	.align-content-xl-around {
		-ms-flex-line-pack: distribute !important;
		align-content: space-around !important;
	}
	.align-content-xl-stretch {
		-ms-flex-line-pack: stretch !important;
		align-content: stretch !important;
	}
	.align-self-xl-auto {
		-ms-flex-item-align: auto !important;
		align-self: auto !important;
	}
	.align-self-xl-start {
		-ms-flex-item-align: start !important;
		align-self: flex-start !important;
	}
	.align-self-xl-end {
		-ms-flex-item-align: end !important;
		align-self: flex-end !important;
	}
	.align-self-xl-center {
		-ms-flex-item-align: center !important;
		align-self: center !important;
	}
	.align-self-xl-baseline {
		-ms-flex-item-align: baseline !important;
		align-self: baseline !important;
	}
	.align-self-xl-stretch {
		-ms-flex-item-align: stretch !important;
		align-self: stretch !important;
	}
}

.float-left {
	float: left !important;
}

.float-right {
	float: right !important;
}

.float-none {
	float: none !important;
}

@media (min-width: 576px) {
	.float-sm-left {
		float: left !important;
	}
	.float-sm-right {
		float: right !important;
	}
	.float-sm-none {
		float: none !important;
	}
}

@media (min-width: 768px) {
	.float-md-left {
		float: left !important;
	}
	.float-md-right {
		float: right !important;
	}
	.float-md-none {
		float: none !important;
	}
}

@media (min-width: 992px) {
	.float-lg-left {
		float: left !important;
	}
	.float-lg-right {
		float: right !important;
	}
	.float-lg-none {
		float: none !important;
	}
}

@media (min-width: 1200px) {
	.float-xl-left {
		float: left !important;
	}
	.float-xl-right {
		float: right !important;
	}
	.float-xl-none {
		float: none !important;
	}
}

.overflow-auto {
	overflow: auto !important;
}

.overflow-hidden {
	overflow: hidden !important;
}

.position-static {
	position: static !important;
}

.position-relative {
	position: relative !important;
}

.position-absolute {
	position: absolute !important;
}

.position-fixed {
	position: fixed !important;
}

.position-sticky {
	position: -webkit-sticky !important;
	position: sticky !important;
}

.fixed-top {
	position: fixed;
	top: 0;
	right: 0;
	left: 0;
	z-index: 1030;
}

.fixed-bottom {
	position: fixed;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1030;
}

@supports ((position: -webkit-sticky) or (position: sticky)) {
	.sticky-top {
		position: -webkit-sticky;
		position: sticky;
		top: 0;
		z-index: 1020;
	}
}

.sr-only {
	position: absolute;
	width: 1px;
	height: 1px;
	padding: 0;
	overflow: hidden;
	clip: rect(0, 0, 0, 0);
	white-space: nowrap;
	border: 0;
}

.sr-only-focusable:active, .sr-only-focusable:focus {
	position: static;
	width: auto;
	height: auto;
	overflow: visible;
	clip: auto;
	white-space: normal;
}

.shadow-sm {
	box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075) !important;
}

.shadow {
	box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15) !important;
}

.shadow-lg {
	box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175) !important;
}

.shadow-none {
	box-shadow: none !important;
}

.w-25 {
	width: 25% !important;
}

.w-40 {
  width: 40% !important;
}

.w-50 {
	width: 50% !important;
}

.w-75 {
	width: 75% !important;
}

.w-100 {
	width: 100% !important;
}

.w-auto {
	width: auto !important;
}

.h-25 {
	height: 25% !important;
}

.h-50 {
	height: 50% !important;
}

.h-75 {
	height: 75% !important;
}

.h-100 {
	height: 100% !important;
}

.h-auto {
	height: auto !important;
}

.mw-100 {
	max-width: 100% !important;
}

.mh-100 {
	max-height: 100% !important;
}

.min-vw-100 {
	min-width: 100vw !important;
}

.min-vh-100 {
	min-height: 100vh !important;
}

.vw-100 {
	width: 100vw !important;
}

.vh-100 {
	height: 100vh !important;
}

.m-0 {
	margin: 0 !important;
}

.mt-0,
.my-0 {
	margin-top: 0 !important;
}

.mr-0,
.mx-0 {
	margin-right: 0 !important;
}

.mb-0,
.my-0 {
	margin-bottom: 0 !important;
}

.ml-0,
.mx-0 {
	margin-left: 0 !important;
}

.m-1 {
	margin: 0.25rem !important;
}

.mt-1,
.my-1 {
	margin-top: 0.25rem !important;
}

.mr-1,
.mx-1 {
	margin-right: 0.25rem !important;
}

.mb-1,
.my-1 {
	margin-bottom: 0.25rem !important;
}

.ml-1,
.mx-1 {
	margin-left: 0.25rem !important;
}

.m-2 {
	margin: 0.5rem !important;
}

.mt-2,
.my-2 {
	margin-top: 0.5rem !important;
}

.mr-2,
.mx-2 {
	margin-right: 0.5rem !important;
}

.mb-2,
.my-2 {
	margin-bottom: 0.5rem !important;
}

.ml-2,
.mx-2 {
	margin-left: 0.5rem !important;
}

.m-3 {
	margin: 1rem !important;
}

.mt-3,
.my-3 {
	margin-top: 1rem !important;
}

.mr-3,
.mx-3 {
	margin-right: 1rem !important;
}

.mb-3,
.my-3 {
	margin-bottom: 1rem !important;
}

.ml-3,
.mx-3 {
	margin-left: 1rem !important;
}

.m-4 {
	margin: 1.5rem !important;
}

.mt-4,
.my-4 {
	margin-top: 1.5rem !important;
}

.mr-4,
.mx-4 {
	margin-right: 1.5rem !important;
}

.mb-4,
.my-4 {
	margin-bottom: 1.5rem !important;
}

.ml-4,
.mx-4 {
	margin-left: 1.5rem !important;
}

.m-5 {
	margin: 3rem !important;
}

.mt-5,
.my-5 {
	margin-top: 3rem !important;
}

.mr-5,
.mx-5 {
	margin-right: 3rem !important;
}

.mb-5,
.my-5 {
	margin-bottom: 3rem !important;
}

.ml-5,
.mx-5 {
	margin-left: 3rem !important;
}

.p-0 {
	padding: 0 !important;
}

.pt-0,
.py-0 {
	padding-top: 0 !important;
}

.pr-0,
.px-0 {
	padding-right: 0 !important;
}

.pb-0,
.py-0 {
	padding-bottom: 0 !important;
}

.pl-0,
.px-0 {
	padding-left: 0 !important;
}

.p-1 {
	padding: 0.25rem !important;
}

.pt-1,
.py-1 {
	padding-top: 0.25rem !important;
}

.pr-1,
.px-1 {
	padding-right: 0.25rem !important;
}

.pb-1,
.py-1 {
	padding-bottom: 0.25rem !important;
}

.pl-1,
.px-1 {
	padding-left: 0.25rem !important;
}

.p-2 {
	padding: 0.5rem !important;
}

.pt-2,
.py-2 {
	padding-top: 0.5rem !important;
}

.pr-2,
.px-2 {
	padding-right: 0.5rem !important;
}

.pb-2,
.py-2 {
	padding-bottom: 0.5rem !important;
}

.pl-2,
.px-2 {
	padding-left: 0.5rem !important;
}

.p-3 {
	padding: 1rem !important;
}

.pt-3,
.py-3 {
	padding-top: 1rem !important;
}

.pr-3,
.px-3 {
	padding-right: 1rem !important;
}

.pb-3,
.py-3 {
	padding-bottom: 1rem !important;
}

.pl-3,
.px-3 {
	padding-left: 1rem !important;
}

.p-4 {
	padding: 1.5rem !important;
}

.pt-4,
.py-4 {
	padding-top: 1.5rem !important;
}

.pr-4,
.px-4 {
	padding-right: 1.5rem !important;
}

.pb-4,
.py-4 {
	padding-bottom: 1.5rem !important;
}

.pl-4,
.px-4 {
	padding-left: 1.5rem !important;
}

.p-5 {
	padding: 3rem !important;
}

.pt-5,
.py-5 {
	padding-top: 3rem !important;
}

.pr-5,
.px-5 {
	padding-right: 3rem !important;
}

.pb-5,
.py-5 {
	padding-bottom: 3rem !important;
}

.pl-5,
.px-5 {
	padding-left: 3rem !important;
}

.m-n1 {
	margin: -0.25rem !important;
}

.mt-n1,
.my-n1 {
	margin-top: -0.25rem !important;
}

.mr-n1,
.mx-n1 {
	margin-right: -0.25rem !important;
}

.mb-n1,
.my-n1 {
	margin-bottom: -0.25rem !important;
}

.ml-n1,
.mx-n1 {
	margin-left: -0.25rem !important;
}

.m-n2 {
	margin: -0.5rem !important;
}

.mt-n2,
.my-n2 {
	margin-top: -0.5rem !important;
}

.mr-n2,
.mx-n2 {
	margin-right: -0.5rem !important;
}

.mb-n2,
.my-n2 {
	margin-bottom: -0.5rem !important;
}

.ml-n2,
.mx-n2 {
	margin-left: -0.5rem !important;
}

.m-n3 {
	margin: -1rem !important;
}

.mt-n3,
.my-n3 {
	margin-top: -1rem !important;
}

.mr-n3,
.mx-n3 {
	margin-right: -1rem !important;
}

.mb-n3,
.my-n3 {
	margin-bottom: -1rem !important;
}

.ml-n3,
.mx-n3 {
	margin-left: -1rem !important;
}

.m-n4 {
	margin: -1.5rem !important;
}

.mt-n4,
.my-n4 {
	margin-top: -1.5rem !important;
}

.mr-n4,
.mx-n4 {
	margin-right: -1.5rem !important;
}

.mb-n4,
.my-n4 {
	margin-bottom: -1.5rem !important;
}

.ml-n4,
.mx-n4 {
	margin-left: -1.5rem !important;
}

.m-n5 {
	margin: -3rem !important;
}

.mt-n5,
.my-n5 {
	margin-top: -3rem !important;
}

.mr-n5,
.mx-n5 {
	margin-right: -3rem !important;
}

.mb-n5,
.my-n5 {
	margin-bottom: -3rem !important;
}

.ml-n5,
.mx-n5 {
	margin-left: -3rem !important;
}

.m-auto {
	margin: auto !important;
}

.mt-auto,
.my-auto {
	margin-top: auto !important;
}

.mr-auto,
.mx-auto {
	margin-right: auto !important;
}

.mb-auto,
.my-auto {
	margin-bottom: auto !important;
}

.ml-auto,
.mx-auto {
	margin-left: auto !important;
}

@media (min-width: 576px) {
	.m-sm-0 {
		margin: 0 !important;
	}
	.mt-sm-0,
	.my-sm-0 {
		margin-top: 0 !important;
	}
	.mr-sm-0,
	.mx-sm-0 {
		margin-right: 0 !important;
	}
	.mb-sm-0,
	.my-sm-0 {
		margin-bottom: 0 !important;
	}
	.ml-sm-0,
	.mx-sm-0 {
		margin-left: 0 !important;
	}
	.m-sm-1 {
		margin: 0.25rem !important;
	}
	.mt-sm-1,
	.my-sm-1 {
		margin-top: 0.25rem !important;
	}
	.mr-sm-1,
	.mx-sm-1 {
		margin-right: 0.25rem !important;
	}
	.mb-sm-1,
	.my-sm-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-sm-1,
	.mx-sm-1 {
		margin-left: 0.25rem !important;
	}
	.m-sm-2 {
		margin: 0.5rem !important;
	}
	.mt-sm-2,
	.my-sm-2 {
		margin-top: 0.5rem !important;
	}
	.mr-sm-2,
	.mx-sm-2 {
		margin-right: 0.5rem !important;
	}
	.mb-sm-2,
	.my-sm-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-sm-2,
	.mx-sm-2 {
		margin-left: 0.5rem !important;
	}
	.m-sm-3 {
		margin: 1rem !important;
	}
	.mt-sm-3,
	.my-sm-3 {
		margin-top: 1rem !important;
	}
	.mr-sm-3,
	.mx-sm-3 {
		margin-right: 1rem !important;
	}
	.mb-sm-3,
	.my-sm-3 {
		margin-bottom: 1rem !important;
	}
	.ml-sm-3,
	.mx-sm-3 {
		margin-left: 1rem !important;
	}
	.m-sm-4 {
		margin: 1.5rem !important;
	}
	.mt-sm-4,
	.my-sm-4 {
		margin-top: 1.5rem !important;
	}
	.mr-sm-4,
	.mx-sm-4 {
		margin-right: 1.5rem !important;
	}
	.mb-sm-4,
	.my-sm-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-sm-4,
	.mx-sm-4 {
		margin-left: 1.5rem !important;
	}
	.m-sm-5 {
		margin: 3rem !important;
	}
	.mt-sm-5,
	.my-sm-5 {
		margin-top: 3rem !important;
	}
	.mr-sm-5,
	.mx-sm-5 {
		margin-right: 3rem !important;
	}
	.mb-sm-5,
	.my-sm-5 {
		margin-bottom: 3rem !important;
	}
	.ml-sm-5,
	.mx-sm-5 {
		margin-left: 3rem !important;
	}
	.p-sm-0 {
		padding: 0 !important;
	}
	.pt-sm-0,
	.py-sm-0 {
		padding-top: 0 !important;
	}
	.pr-sm-0,
	.px-sm-0 {
		padding-right: 0 !important;
	}
	.pb-sm-0,
	.py-sm-0 {
		padding-bottom: 0 !important;
	}
	.pl-sm-0,
	.px-sm-0 {
		padding-left: 0 !important;
	}
	.p-sm-1 {
		padding: 0.25rem !important;
	}
	.pt-sm-1,
	.py-sm-1 {
		padding-top: 0.25rem !important;
	}
	.pr-sm-1,
	.px-sm-1 {
		padding-right: 0.25rem !important;
	}
	.pb-sm-1,
	.py-sm-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-sm-1,
	.px-sm-1 {
		padding-left: 0.25rem !important;
	}
	.p-sm-2 {
		padding: 0.5rem !important;
	}
	.pt-sm-2,
	.py-sm-2 {
		padding-top: 0.5rem !important;
	}
	.pr-sm-2,
	.px-sm-2 {
		padding-right: 0.5rem !important;
	}
	.pb-sm-2,
	.py-sm-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-sm-2,
	.px-sm-2 {
		padding-left: 0.5rem !important;
	}
	.p-sm-3 {
		padding: 1rem !important;
	}
	.pt-sm-3,
	.py-sm-3 {
		padding-top: 1rem !important;
	}
	.pr-sm-3,
	.px-sm-3 {
		padding-right: 1rem !important;
	}
	.pb-sm-3,
	.py-sm-3 {
		padding-bottom: 1rem !important;
	}
	.pl-sm-3,
	.px-sm-3 {
		padding-left: 1rem !important;
	}
	.p-sm-4 {
		padding: 1.5rem !important;
	}
	.pt-sm-4,
	.py-sm-4 {
		padding-top: 1.5rem !important;
	}
	.pr-sm-4,
	.px-sm-4 {
		padding-right: 1.5rem !important;
	}
	.pb-sm-4,
	.py-sm-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-sm-4,
	.px-sm-4 {
		padding-left: 1.5rem !important;
	}
	.p-sm-5 {
		padding: 3rem !important;
	}
	.pt-sm-5,
	.py-sm-5 {
		padding-top: 3rem !important;
	}
	.pr-sm-5,
	.px-sm-5 {
		padding-right: 3rem !important;
	}
	.pb-sm-5,
	.py-sm-5 {
		padding-bottom: 3rem !important;
	}
	.pl-sm-5,
	.px-sm-5 {
		padding-left: 3rem !important;
	}
	.m-sm-n1 {
		margin: -0.25rem !important;
	}
	.mt-sm-n1,
	.my-sm-n1 {
		margin-top: -0.25rem !important;
	}
	.mr-sm-n1,
	.mx-sm-n1 {
		margin-right: -0.25rem !important;
	}
	.mb-sm-n1,
	.my-sm-n1 {
		margin-bottom: -0.25rem !important;
	}
	.ml-sm-n1,
	.mx-sm-n1 {
		margin-left: -0.25rem !important;
	}
	.m-sm-n2 {
		margin: -0.5rem !important;
	}
	.mt-sm-n2,
	.my-sm-n2 {
		margin-top: -0.5rem !important;
	}
	.mr-sm-n2,
	.mx-sm-n2 {
		margin-right: -0.5rem !important;
	}
	.mb-sm-n2,
	.my-sm-n2 {
		margin-bottom: -0.5rem !important;
	}
	.ml-sm-n2,
	.mx-sm-n2 {
		margin-left: -0.5rem !important;
	}
	.m-sm-n3 {
		margin: -1rem !important;
	}
	.mt-sm-n3,
	.my-sm-n3 {
		margin-top: -1rem !important;
	}
	.mr-sm-n3,
	.mx-sm-n3 {
		margin-right: -1rem !important;
	}
	.mb-sm-n3,
	.my-sm-n3 {
		margin-bottom: -1rem !important;
	}
	.ml-sm-n3,
	.mx-sm-n3 {
		margin-left: -1rem !important;
	}
	.m-sm-n4 {
		margin: -1.5rem !important;
	}
	.mt-sm-n4,
	.my-sm-n4 {
		margin-top: -1.5rem !important;
	}
	.mr-sm-n4,
	.mx-sm-n4 {
		margin-right: -1.5rem !important;
	}
	.mb-sm-n4,
	.my-sm-n4 {
		margin-bottom: -1.5rem !important;
	}
	.ml-sm-n4,
	.mx-sm-n4 {
		margin-left: -1.5rem !important;
	}
	.m-sm-n5 {
		margin: -3rem !important;
	}
	.mt-sm-n5,
	.my-sm-n5 {
		margin-top: -3rem !important;
	}
	.mr-sm-n5,
	.mx-sm-n5 {
		margin-right: -3rem !important;
	}
	.mb-sm-n5,
	.my-sm-n5 {
		margin-bottom: -3rem !important;
	}
	.ml-sm-n5,
	.mx-sm-n5 {
		margin-left: -3rem !important;
	}
	.m-sm-auto {
		margin: auto !important;
	}
	.mt-sm-auto,
	.my-sm-auto {
		margin-top: auto !important;
	}
	.mr-sm-auto,
	.mx-sm-auto {
		margin-right: auto !important;
	}
	.mb-sm-auto,
	.my-sm-auto {
		margin-bottom: auto !important;
	}
	.ml-sm-auto,
	.mx-sm-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 768px) {
	.m-md-0 {
		margin: 0 !important;
	}
	.mt-md-0,
	.my-md-0 {
		margin-top: 0 !important;
	}
	.mr-md-0,
	.mx-md-0 {
		margin-right: 0 !important;
	}
	.mb-md-0,
	.my-md-0 {
		margin-bottom: 0 !important;
	}
	.ml-md-0,
	.mx-md-0 {
		margin-left: 0 !important;
	}
	.m-md-1 {
		margin: 0.25rem !important;
	}
	.mt-md-1,
	.my-md-1 {
		margin-top: 0.25rem !important;
	}
	.mr-md-1,
	.mx-md-1 {
		margin-right: 0.25rem !important;
	}
	.mb-md-1,
	.my-md-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-md-1,
	.mx-md-1 {
		margin-left: 0.25rem !important;
	}
	.m-md-2 {
		margin: 0.5rem !important;
	}
	.mt-md-2,
	.my-md-2 {
		margin-top: 0.5rem !important;
	}
	.mr-md-2,
	.mx-md-2 {
		margin-right: 0.5rem !important;
	}
	.mb-md-2,
	.my-md-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-md-2,
	.mx-md-2 {
		margin-left: 0.5rem !important;
	}
	.m-md-3 {
		margin: 1rem !important;
	}
	.mt-md-3,
	.my-md-3 {
		margin-top: 1rem !important;
	}
	.mr-md-3,
	.mx-md-3 {
		margin-right: 1rem !important;
	}
	.mb-md-3,
	.my-md-3 {
		margin-bottom: 1rem !important;
	}
	.ml-md-3,
	.mx-md-3 {
		margin-left: 1rem !important;
	}
	.m-md-4 {
		margin: 1.5rem !important;
	}
	.mt-md-4,
	.my-md-4 {
		margin-top: 1.5rem !important;
	}
	.mr-md-4,
	.mx-md-4 {
		margin-right: 1.5rem !important;
	}
	.mb-md-4,
	.my-md-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-md-4,
	.mx-md-4 {
		margin-left: 1.5rem !important;
	}
	.m-md-5 {
		margin: 3rem !important;
	}
	.mt-md-5,
	.my-md-5 {
		margin-top: 3rem !important;
	}
	.mr-md-5,
	.mx-md-5 {
		margin-right: 3rem !important;
	}
	.mb-md-5,
	.my-md-5 {
		margin-bottom: 3rem !important;
	}
	.ml-md-5,
	.mx-md-5 {
		margin-left: 3rem !important;
	}
	.p-md-0 {
		padding: 0 !important;
	}
	.pt-md-0,
	.py-md-0 {
		padding-top: 0 !important;
	}
	.pr-md-0,
	.px-md-0 {
		padding-right: 0 !important;
	}
	.pb-md-0,
	.py-md-0 {
		padding-bottom: 0 !important;
	}
	.pl-md-0,
	.px-md-0 {
		padding-left: 0 !important;
	}
	.p-md-1 {
		padding: 0.25rem !important;
	}
	.pt-md-1,
	.py-md-1 {
		padding-top: 0.25rem !important;
	}
	.pr-md-1,
	.px-md-1 {
		padding-right: 0.25rem !important;
	}
	.pb-md-1,
	.py-md-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-md-1,
	.px-md-1 {
		padding-left: 0.25rem !important;
	}
	.p-md-2 {
		padding: 0.5rem !important;
	}
	.pt-md-2,
	.py-md-2 {
		padding-top: 0.5rem !important;
	}
	.pr-md-2,
	.px-md-2 {
		padding-right: 0.5rem !important;
	}
	.pb-md-2,
	.py-md-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-md-2,
	.px-md-2 {
		padding-left: 0.5rem !important;
	}
	.p-md-3 {
		padding: 1rem !important;
	}
	.pt-md-3,
	.py-md-3 {
		padding-top: 1rem !important;
	}
	.pr-md-3,
	.px-md-3 {
		padding-right: 1rem !important;
	}
	.pb-md-3,
	.py-md-3 {
		padding-bottom: 1rem !important;
	}
	.pl-md-3,
	.px-md-3 {
		padding-left: 1rem !important;
	}
	.p-md-4 {
		padding: 1.5rem !important;
	}
	.pt-md-4,
	.py-md-4 {
		padding-top: 1.5rem !important;
	}
	.pr-md-4,
	.px-md-4 {
		padding-right: 1.5rem !important;
	}
	.pb-md-4,
	.py-md-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-md-4,
	.px-md-4 {
		padding-left: 1.5rem !important;
	}
	.p-md-5 {
		padding: 3rem !important;
	}
	.pt-md-5,
	.py-md-5 {
		padding-top: 3rem !important;
	}
	.pr-md-5,
	.px-md-5 {
		padding-right: 3rem !important;
	}
	.pb-md-5,
	.py-md-5 {
		padding-bottom: 3rem !important;
	}
	.pl-md-5,
	.px-md-5 {
		padding-left: 3rem !important;
	}
	.m-md-n1 {
		margin: -0.25rem !important;
	}
	.mt-md-n1,
	.my-md-n1 {
		margin-top: -0.25rem !important;
	}
	.mr-md-n1,
	.mx-md-n1 {
		margin-right: -0.25rem !important;
	}
	.mb-md-n1,
	.my-md-n1 {
		margin-bottom: -0.25rem !important;
	}
	.ml-md-n1,
	.mx-md-n1 {
		margin-left: -0.25rem !important;
	}
	.m-md-n2 {
		margin: -0.5rem !important;
	}
	.mt-md-n2,
	.my-md-n2 {
		margin-top: -0.5rem !important;
	}
	.mr-md-n2,
	.mx-md-n2 {
		margin-right: -0.5rem !important;
	}
	.mb-md-n2,
	.my-md-n2 {
		margin-bottom: -0.5rem !important;
	}
	.ml-md-n2,
	.mx-md-n2 {
		margin-left: -0.5rem !important;
	}
	.m-md-n3 {
		margin: -1rem !important;
	}
	.mt-md-n3,
	.my-md-n3 {
		margin-top: -1rem !important;
	}
	.mr-md-n3,
	.mx-md-n3 {
		margin-right: -1rem !important;
	}
	.mb-md-n3,
	.my-md-n3 {
		margin-bottom: -1rem !important;
	}
	.ml-md-n3,
	.mx-md-n3 {
		margin-left: -1rem !important;
	}
	.m-md-n4 {
		margin: -1.5rem !important;
	}
	.mt-md-n4,
	.my-md-n4 {
		margin-top: -1.5rem !important;
	}
	.mr-md-n4,
	.mx-md-n4 {
		margin-right: -1.5rem !important;
	}
	.mb-md-n4,
	.my-md-n4 {
		margin-bottom: -1.5rem !important;
	}
	.ml-md-n4,
	.mx-md-n4 {
		margin-left: -1.5rem !important;
	}
	.m-md-n5 {
		margin: -3rem !important;
	}
	.mt-md-n5,
	.my-md-n5 {
		margin-top: -3rem !important;
	}
	.mr-md-n5,
	.mx-md-n5 {
		margin-right: -3rem !important;
	}
	.mb-md-n5,
	.my-md-n5 {
		margin-bottom: -3rem !important;
	}
	.ml-md-n5,
	.mx-md-n5 {
		margin-left: -3rem !important;
	}
	.m-md-auto {
		margin: auto !important;
	}
	.mt-md-auto,
	.my-md-auto {
		margin-top: auto !important;
	}
	.mr-md-auto,
	.mx-md-auto {
		margin-right: auto !important;
	}
	.mb-md-auto,
	.my-md-auto {
		margin-bottom: auto !important;
	}
	.ml-md-auto,
	.mx-md-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 992px) {
	.m-lg-0 {
		margin: 0 !important;
	}
	.mt-lg-0,
	.my-lg-0 {
		margin-top: 0 !important;
	}
	.mr-lg-0,
	.mx-lg-0 {
		margin-right: 0 !important;
	}
	.mb-lg-0,
	.my-lg-0 {
		margin-bottom: 0 !important;
	}
	.ml-lg-0,
	.mx-lg-0 {
		margin-left: 0 !important;
	}
	.m-lg-1 {
		margin: 0.25rem !important;
	}
	.mt-lg-1,
	.my-lg-1 {
		margin-top: 0.25rem !important;
	}
	.mr-lg-1,
	.mx-lg-1 {
		margin-right: 0.25rem !important;
	}
	.mb-lg-1,
	.my-lg-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-lg-1,
	.mx-lg-1 {
		margin-left: 0.25rem !important;
	}
	.m-lg-2 {
		margin: 0.5rem !important;
	}
	.mt-lg-2,
	.my-lg-2 {
		margin-top: 0.5rem !important;
	}
	.mr-lg-2,
	.mx-lg-2 {
		margin-right: 0.5rem !important;
	}
	.mb-lg-2,
	.my-lg-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-lg-2,
	.mx-lg-2 {
		margin-left: 0.5rem !important;
	}
	.m-lg-3 {
		margin: 1rem !important;
	}
	.mt-lg-3,
	.my-lg-3 {
		margin-top: 1rem !important;
	}
	.mr-lg-3,
	.mx-lg-3 {
		margin-right: 1rem !important;
	}
	.mb-lg-3,
	.my-lg-3 {
		margin-bottom: 1rem !important;
	}
	.ml-lg-3,
	.mx-lg-3 {
		margin-left: 1rem !important;
	}
	.m-lg-4 {
		margin: 1.5rem !important;
	}
	.mt-lg-4,
	.my-lg-4 {
		margin-top: 1.5rem !important;
	}
	.mr-lg-4,
	.mx-lg-4 {
		margin-right: 1.5rem !important;
	}
	.mb-lg-4,
	.my-lg-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-lg-4,
	.mx-lg-4 {
		margin-left: 1.5rem !important;
	}
	.m-lg-5 {
		margin: 3rem !important;
	}
	.mt-lg-5,
	.my-lg-5 {
		margin-top: 3rem !important;
	}
	.mr-lg-5,
	.mx-lg-5 {
		margin-right: 3rem !important;
	}
	.mb-lg-5,
	.my-lg-5 {
		margin-bottom: 3rem !important;
	}
	.ml-lg-5,
	.mx-lg-5 {
		margin-left: 3rem !important;
	}
	.p-lg-0 {
		padding: 0 !important;
	}
	.pt-lg-0,
	.py-lg-0 {
		padding-top: 0 !important;
	}
	.pr-lg-0,
	.px-lg-0 {
		padding-right: 0 !important;
	}
	.pb-lg-0,
	.py-lg-0 {
		padding-bottom: 0 !important;
	}
	.pl-lg-0,
	.px-lg-0 {
		padding-left: 0 !important;
	}
	.p-lg-1 {
		padding: 0.25rem !important;
	}
	.pt-lg-1,
	.py-lg-1 {
		padding-top: 0.25rem !important;
	}
	.pr-lg-1,
	.px-lg-1 {
		padding-right: 0.25rem !important;
	}
	.pb-lg-1,
	.py-lg-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-lg-1,
	.px-lg-1 {
		padding-left: 0.25rem !important;
	}
	.p-lg-2 {
		padding: 0.5rem !important;
	}
	.pt-lg-2,
	.py-lg-2 {
		padding-top: 0.5rem !important;
	}
	.pr-lg-2,
	.px-lg-2 {
		padding-right: 0.5rem !important;
	}
	.pb-lg-2,
	.py-lg-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-lg-2,
	.px-lg-2 {
		padding-left: 0.5rem !important;
	}
	.p-lg-3 {
		padding: 1rem !important;
	}
	.pt-lg-3,
	.py-lg-3 {
		padding-top: 1rem !important;
	}
	.pr-lg-3,
	.px-lg-3 {
		padding-right: 1rem !important;
	}
	.pb-lg-3,
	.py-lg-3 {
		padding-bottom: 1rem !important;
	}
	.pl-lg-3,
	.px-lg-3 {
		padding-left: 1rem !important;
	}
	.p-lg-4 {
		padding: 1.5rem !important;
	}
	.pt-lg-4,
	.py-lg-4 {
		padding-top: 1.5rem !important;
	}
	.pr-lg-4,
	.px-lg-4 {
		padding-right: 1.5rem !important;
	}
	.pb-lg-4,
	.py-lg-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-lg-4,
	.px-lg-4 {
		padding-left: 1.5rem !important;
	}
	.p-lg-5 {
		padding: 3rem !important;
	}
	.pt-lg-5,
	.py-lg-5 {
		padding-top: 3rem !important;
	}
	.pr-lg-5,
	.px-lg-5 {
		padding-right: 3rem !important;
	}
	.pb-lg-5,
	.py-lg-5 {
		padding-bottom: 3rem !important;
	}
	.pl-lg-5,
	.px-lg-5 {
		padding-left: 3rem !important;
	}
	.m-lg-n1 {
		margin: -0.25rem !important;
	}
	.mt-lg-n1,
	.my-lg-n1 {
		margin-top: -0.25rem !important;
	}
	.mr-lg-n1,
	.mx-lg-n1 {
		margin-right: -0.25rem !important;
	}
	.mb-lg-n1,
	.my-lg-n1 {
		margin-bottom: -0.25rem !important;
	}
	.ml-lg-n1,
	.mx-lg-n1 {
		margin-left: -0.25rem !important;
	}
	.m-lg-n2 {
		margin: -0.5rem !important;
	}
	.mt-lg-n2,
	.my-lg-n2 {
		margin-top: -0.5rem !important;
	}
	.mr-lg-n2,
	.mx-lg-n2 {
		margin-right: -0.5rem !important;
	}
	.mb-lg-n2,
	.my-lg-n2 {
		margin-bottom: -0.5rem !important;
	}
	.ml-lg-n2,
	.mx-lg-n2 {
		margin-left: -0.5rem !important;
	}
	.m-lg-n3 {
		margin: -1rem !important;
	}
	.mt-lg-n3,
	.my-lg-n3 {
		margin-top: -1rem !important;
	}
	.mr-lg-n3,
	.mx-lg-n3 {
		margin-right: -1rem !important;
	}
	.mb-lg-n3,
	.my-lg-n3 {
		margin-bottom: -1rem !important;
	}
	.ml-lg-n3,
	.mx-lg-n3 {
		margin-left: -1rem !important;
	}
	.m-lg-n4 {
		margin: -1.5rem !important;
	}
	.mt-lg-n4,
	.my-lg-n4 {
		margin-top: -1.5rem !important;
	}
	.mr-lg-n4,
	.mx-lg-n4 {
		margin-right: -1.5rem !important;
	}
	.mb-lg-n4,
	.my-lg-n4 {
		margin-bottom: -1.5rem !important;
	}
	.ml-lg-n4,
	.mx-lg-n4 {
		margin-left: -1.5rem !important;
	}
	.m-lg-n5 {
		margin: -3rem !important;
	}
	.mt-lg-n5,
	.my-lg-n5 {
		margin-top: -3rem !important;
	}
	.mr-lg-n5,
	.mx-lg-n5 {
		margin-right: -3rem !important;
	}
	.mb-lg-n5,
	.my-lg-n5 {
		margin-bottom: -3rem !important;
	}
	.ml-lg-n5,
	.mx-lg-n5 {
		margin-left: -3rem !important;
	}
	.m-lg-auto {
		margin: auto !important;
	}
	.mt-lg-auto,
	.my-lg-auto {
		margin-top: auto !important;
	}
	.mr-lg-auto,
	.mx-lg-auto {
		margin-right: auto !important;
	}
	.mb-lg-auto,
	.my-lg-auto {
		margin-bottom: auto !important;
	}
	.ml-lg-auto,
	.mx-lg-auto {
		margin-left: auto !important;
	}
}

@media (min-width: 1200px) {
	.m-xl-0 {
		margin: 0 !important;
	}
	.mt-xl-0,
	.my-xl-0 {
		margin-top: 0 !important;
	}
	.mr-xl-0,
	.mx-xl-0 {
		margin-right: 0 !important;
	}
	.mb-xl-0,
	.my-xl-0 {
		margin-bottom: 0 !important;
	}
	.ml-xl-0,
	.mx-xl-0 {
		margin-left: 0 !important;
	}
	.m-xl-1 {
		margin: 0.25rem !important;
	}
	.mt-xl-1,
	.my-xl-1 {
		margin-top: 0.25rem !important;
	}
	.mr-xl-1,
	.mx-xl-1 {
		margin-right: 0.25rem !important;
	}
	.mb-xl-1,
	.my-xl-1 {
		margin-bottom: 0.25rem !important;
	}
	.ml-xl-1,
	.mx-xl-1 {
		margin-left: 0.25rem !important;
	}
	.m-xl-2 {
		margin: 0.5rem !important;
	}
	.mt-xl-2,
	.my-xl-2 {
		margin-top: 0.5rem !important;
	}
	.mr-xl-2,
	.mx-xl-2 {
		margin-right: 0.5rem !important;
	}
	.mb-xl-2,
	.my-xl-2 {
		margin-bottom: 0.5rem !important;
	}
	.ml-xl-2,
	.mx-xl-2 {
		margin-left: 0.5rem !important;
	}
	.m-xl-3 {
		margin: 1rem !important;
	}
	.mt-xl-3,
	.my-xl-3 {
		margin-top: 1rem !important;
	}
	.mr-xl-3,
	.mx-xl-3 {
		margin-right: 1rem !important;
	}
	.mb-xl-3,
	.my-xl-3 {
		margin-bottom: 1rem !important;
	}
	.ml-xl-3,
	.mx-xl-3 {
		margin-left: 1rem !important;
	}
	.m-xl-4 {
		margin: 1.5rem !important;
	}
	.mt-xl-4,
	.my-xl-4 {
		margin-top: 1.5rem !important;
	}
	.mr-xl-4,
	.mx-xl-4 {
		margin-right: 1.5rem !important;
	}
	.mb-xl-4,
	.my-xl-4 {
		margin-bottom: 1.5rem !important;
	}
	.ml-xl-4,
	.mx-xl-4 {
		margin-left: 1.5rem !important;
	}
	.m-xl-5 {
		margin: 3rem !important;
	}
	.mt-xl-5,
	.my-xl-5 {
		margin-top: 3rem !important;
	}
	.mr-xl-5,
	.mx-xl-5 {
		margin-right: 3rem !important;
	}
	.mb-xl-5,
	.my-xl-5 {
		margin-bottom: 3rem !important;
	}
	.ml-xl-5,
	.mx-xl-5 {
		margin-left: 3rem !important;
	}
	.p-xl-0 {
		padding: 0 !important;
	}
	.pt-xl-0,
	.py-xl-0 {
		padding-top: 0 !important;
	}
	.pr-xl-0,
	.px-xl-0 {
		padding-right: 0 !important;
	}
	.pb-xl-0,
	.py-xl-0 {
		padding-bottom: 0 !important;
	}
	.pl-xl-0,
	.px-xl-0 {
		padding-left: 0 !important;
	}
	.p-xl-1 {
		padding: 0.25rem !important;
	}
	.pt-xl-1,
	.py-xl-1 {
		padding-top: 0.25rem !important;
	}
	.pr-xl-1,
	.px-xl-1 {
		padding-right: 0.25rem !important;
	}
	.pb-xl-1,
	.py-xl-1 {
		padding-bottom: 0.25rem !important;
	}
	.pl-xl-1,
	.px-xl-1 {
		padding-left: 0.25rem !important;
	}
	.p-xl-2 {
		padding: 0.5rem !important;
	}
	.pt-xl-2,
	.py-xl-2 {
		padding-top: 0.5rem !important;
	}
	.pr-xl-2,
	.px-xl-2 {
		padding-right: 0.5rem !important;
	}
	.pb-xl-2,
	.py-xl-2 {
		padding-bottom: 0.5rem !important;
	}
	.pl-xl-2,
	.px-xl-2 {
		padding-left: 0.5rem !important;
	}
	.p-xl-3 {
		padding: 1rem !important;
	}
	.pt-xl-3,
	.py-xl-3 {
		padding-top: 1rem !important;
	}
	.pr-xl-3,
	.px-xl-3 {
		padding-right: 1rem !important;
	}
	.pb-xl-3,
	.py-xl-3 {
		padding-bottom: 1rem !important;
	}
	.pl-xl-3,
	.px-xl-3 {
		padding-left: 1rem !important;
	}
	.p-xl-4 {
		padding: 1.5rem !important;
	}
	.pt-xl-4,
	.py-xl-4 {
		padding-top: 1.5rem !important;
	}
	.pr-xl-4,
	.px-xl-4 {
		padding-right: 1.5rem !important;
	}
	.pb-xl-4,
	.py-xl-4 {
		padding-bottom: 1.5rem !important;
	}
	.pl-xl-4,
	.px-xl-4 {
		padding-left: 1.5rem !important;
	}
	.p-xl-5 {
		padding: 3rem !important;
	}
	.pt-xl-5,
	.py-xl-5 {
		padding-top: 3rem !important;
	}
	.pr-xl-5,
	.px-xl-5 {
		padding-right: 3rem !important;
	}
	.pb-xl-5,
	.py-xl-5 {
		padding-bottom: 3rem !important;
	}
	.pl-xl-5,
	.px-xl-5 {
		padding-left: 3rem !important;
	}
	.m-xl-n1 {
		margin: -0.25rem !important;
	}
	.mt-xl-n1,
	.my-xl-n1 {
		margin-top: -0.25rem !important;
	}
	.mr-xl-n1,
	.mx-xl-n1 {
		margin-right: -0.25rem !important;
	}
	.mb-xl-n1,
	.my-xl-n1 {
		margin-bottom: -0.25rem !important;
	}
	.ml-xl-n1,
	.mx-xl-n1 {
		margin-left: -0.25rem !important;
	}
	.m-xl-n2 {
		margin: -0.5rem !important;
	}
	.mt-xl-n2,
	.my-xl-n2 {
		margin-top: -0.5rem !important;
	}
	.mr-xl-n2,
	.mx-xl-n2 {
		margin-right: -0.5rem !important;
	}
	.mb-xl-n2,
	.my-xl-n2 {
		margin-bottom: -0.5rem !important;
	}
	.ml-xl-n2,
	.mx-xl-n2 {
		margin-left: -0.5rem !important;
	}
	.m-xl-n3 {
		margin: -1rem !important;
	}
	.mt-xl-n3,
	.my-xl-n3 {
		margin-top: -1rem !important;
	}
	.mr-xl-n3,
	.mx-xl-n3 {
		margin-right: -1rem !important;
	}
	.mb-xl-n3,
	.my-xl-n3 {
		margin-bottom: -1rem !important;
	}
	.ml-xl-n3,
	.mx-xl-n3 {
		margin-left: -1rem !important;
	}
	.m-xl-n4 {
		margin: -1.5rem !important;
	}
	.mt-xl-n4,
	.my-xl-n4 {
		margin-top: -1.5rem !important;
	}
	.mr-xl-n4,
	.mx-xl-n4 {
		margin-right: -1.5rem !important;
	}
	.mb-xl-n4,
	.my-xl-n4 {
		margin-bottom: -1.5rem !important;
	}
	.ml-xl-n4,
	.mx-xl-n4 {
		margin-left: -1.5rem !important;
	}
	.m-xl-n5 {
		margin: -3rem !important;
	}
	.mt-xl-n5,
	.my-xl-n5 {
		margin-top: -3rem !important;
	}
	.mr-xl-n5,
	.mx-xl-n5 {
		margin-right: -3rem !important;
	}
	.mb-xl-n5,
	.my-xl-n5 {
		margin-bottom: -3rem !important;
	}
	.ml-xl-n5,
	.mx-xl-n5 {
		margin-left: -3rem !important;
	}
	.m-xl-auto {
		margin: auto !important;
	}
	.mt-xl-auto,
	.my-xl-auto {
		margin-top: auto !important;
	}
	.mr-xl-auto,
	.mx-xl-auto {
		margin-right: auto !important;
	}
	.mb-xl-auto,
	.my-xl-auto {
		margin-bottom: auto !important;
	}
	.ml-xl-auto,
	.mx-xl-auto {
		margin-left: auto !important;
	}
}

.text-monospace {
	font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
}

.text-justify {
	text-align: justify !important;
}

.text-wrap {
	white-space: normal !important;
}

.text-nowrap {
	white-space: nowrap !important;
}

.text-truncate {
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}

.text-left {
	text-align: left !important;
}

.text-right {
	text-align: right !important;
}

.text-center {
	text-align: center !important;
}

@media (min-width: 576px) {
	.text-sm-left {
		text-align: left !important;
	}
	.text-sm-right {
		text-align: right !important;
	}
	.text-sm-center {
		text-align: center !important;
	}
}

@media (min-width: 768px) {
	.text-md-left {
		text-align: left !important;
	}
	.text-md-right {
		text-align: right !important;
	}
	.text-md-center {
		text-align: center !important;
	}
}

@media (min-width: 992px) {
	.text-lg-left {
		text-align: left !important;
	}
	.text-lg-right {
		text-align: right !important;
	}
	.text-lg-center {
		text-align: center !important;
	}
}

@media (min-width: 1200px) {
	.text-xl-left {
		text-align: left !important;
	}
	.text-xl-right {
		text-align: right !important;
	}
	.text-xl-center {
		text-align: center !important;
	}
}

.text-lowercase {
	text-transform: lowercase !important;
}

.text-uppercase {
	text-transform: uppercase !important;
}

.text-capitalize {
	text-transform: capitalize !important;
}

.font-weight-light {
	font-weight: 300 !important;
}

.font-weight-lighter {
	font-weight: lighter !important;
}

.font-weight-normal {
	font-weight: 400 !important;
}

.font-weight-bold {
	font-weight: 700 !important;
}

.font-weight-bolder {
	font-weight: bolder !important;
}

.font-italic {
	font-style: italic !important;
}

.text-white {
	color: #fff !important;
}

.text-primary {
	color: #007bff !important;
}

a.text-primary:hover, a.text-primary:focus {
	color: #0056b3 !important;
}

.text-secondary {
	color: #6c757d !important;
}

a.text-secondary:hover, a.text-secondary:focus {
	color: #494f54 !important;
}

.text-success {
	color: #28a745 !important;
}

a.text-success:hover, a.text-success:focus {
	color: #19692c !important;
}

.text-info {
	color: #17a2b8 !important;
}

a.text-info:hover, a.text-info:focus {
	color: #0f6674 !important;
}

.text-warning {
	color: #ffc107 !important;
}

a.text-warning:hover, a.text-warning:focus {
	color: #ba8b00 !important;
}

.text-danger {
	color: #dc3545 !important;
}

a.text-danger:hover, a.text-danger:focus {
	color: #a71d2a !important;
}

.text-light {
	color: #f8f9fa !important;
}

a.text-light:hover, a.text-light:focus {
	color: #cbd3da !important;
}

.text-dark {
	color: #343a40 !important;
}

a.text-dark:hover, a.text-dark:focus {
	color: #121416 !important;
}

.text-body {
	color: #212529 !important;
}

.text-muted {
	color: #6c757d !important;
}

.text-black-50 {
	color: rgba(0, 0, 0, 0.5) !important;
}

.text-white-50 {
	color: rgba(255, 255, 255, 0.5) !important;
}

.text-hide {
	font: 0/0 a;
	color: transparent;
	text-shadow: none;
	background-color: transparent;
	border: 0;
}

.text-decoration-none {
	text-decoration: none !important;
}

.text-reset {
	color: inherit !important;
}

.visible {
	visibility: visible !important;
}

.invisible {
	visibility: hidden !important;
}
/* --------------------------------
End Bootstrap Core Styles
----------------------------------- */
/* --------------------------------
Begin Core Site Styles
----------------------------------- */
.slick-lightbox {
	position: fixed;
	top: 0;
	left: 0;
	z-index: 9999;
	width: 100%;
	height: 100%;
	background: black;
	-webkit-transition: opacity 0.5s ease;
	-o-transition: opacity 0.5s ease;
	-moz-transition: opacity 0.5s ease;
	transition: opacity 0.5s ease;
}

.slick-lightbox .slick-loading .slick-list {
	background-color: transparent;
}

.slick-lightbox .slick-prev {
	left: 15px;
}

.slick-lightbox .slick-next {
	right: 15px;
}

.slick-lightbox-hide {
	opacity: 0;
}

.slick-lightbox-hide.slick-lightbox-ie {
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=0)";
	filter: alpha(opacity=0);
}

.slick-lightbox-hide-init {
	position: absolute;
	top: -9999px;
	opacity: 0;
}

.slick-lightbox-hide-init.slick-lightbox-ie {
	-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=0)";
	filter: alpha(opacity=0);
}

.slick-lightbox-inner {
	position: fixed;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
}

.slick-lightbox-slick-item {
	text-align: center;
	overflow: hidden;
}

.slick-lightbox-slick-item:before {
	content: '';
	display: inline-block;
	height: 100%;
	vertical-align: middle;
	margin-right: -0.25em;
}

.slick-caption-bottom .slick-lightbox-slick-item .slick-lightbox-slick-item .slick-lightbox-slick-caption {
	position: absolute;
	bottom: 0;
	left: 0;
	text-align: center;
	width: 100%;
	margin-bottom: 20px;
}

.slick-caption-dynamic .slick-lightbox-slick-item .slick-lightbox-slick-item .slick-lightbox-slick-caption {
	display: block;
	text-align: center;
}

.slick-lightbox-slick-item-inner {
	display: inline-block;
	vertical-align: middle;
	max-width: 90%;
	max-height: 90%;
}

.slick-lightbox-slick-img {
	margin: 0 auto;
	display: block;
	max-width: 90%;
	max-height: 90%;
}

.slick-lightbox-slick-caption {
	margin: 10px 0 0;
	color: white;
}

.slick-lightbox-close {
	position: absolute;
	top: 15px;
	right: 15px;
	display: block;
	height: 20px;
	width: 20px;
	line-height: 0;
	font-size: 0;
	cursor: pointer;
	background: transparent;
	color: transparent;
	padding: 0;
	border: none;
}

.slick-lightbox-close:focus {
	outline: none;
}

.slick-lightbox-close:before {
	font-family: "slick";
	font-size: 20px;
	line-height: 1;
	color: white;
	opacity: 0.85;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	content: '×';
}

@-o-viewport {
	width: device-width;
}

@viewport {
	width: device-width;
}

html {
	background-color: transparent;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	height: 100%;
}

*:before, *:after {
	-webkit-box-sizing: inherit;
	-moz-box-sizing: inherit;
	box-sizing: inherit;
}

.home-page main {
	margin-top: 60px;
}

@media (min-width: 992px) {
	.home-page main {
		margin-top: 119px;
	}
}

@media all and (min-width: 906px) {
	.home-page main {
		margin-top: 115px;
	}
}

body {
	-webkit-font-smoothing: antialiased;
	/*   color: #ffffff; */
	font-family: "Helvetica Neue", "Helvetica", "Arial", sans-serif;
	min-height: 100%;
	text-rendering: optimizeLegibility;
}

a {
	background: transparent;
	color: #ffffff;
	text-decoration: none;
	-webkit-transition: color .2s;
	-o-transition: color .2s;
	-moz-transition: color .2s;
	transition: color .2s;
}

img {
	height: auto;
	max-width: 100%;
	width: auto;
}

@media (min-width: 768px) {
	img {
		/* width: 100%; */
	}
}

.logo {
	width: auto;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	font-family: "Helvetica Neue", "Helvetica", "Arial", sans-serif;
}

/**
** BASE
**/
.home-page h1, .home-page h3 {
	text-transform: uppercase;
}

h1 {
	font-weight: bold;
	font-size: 1.5rem;
	line-height: 1.5rem;
}

@media (min-width: 576px) {
	h1 {
		font-size: 1.75rem;
	}
}

@media (min-width: 768px) {
	h1 {
		font-size: 2.188rem;
		line-height: 2.5rem;
	}
}

h2 {
	font-weight: bold;
	font-size: 1.5rem;
	line-height: 1.5rem;
	/*   text-transform: capitalize; */
}

h3 {
	font-weight: bold;
	font-size: 1.25rem;
	line-height: 1.45rem;
}

h4 {
	font-weight: bold;
	font-size: 0.9rem;
	line-height: 1.2rem;
	/*   text-transform: capitalize; */
}

h5 {
	font-weight: normal;
	font-size: 0.75rem;
	line-height: 1.1rem;
	text-transform: uppercase;
}

h6 {
	font-size: 0.688rem;
	line-height: 1.063rem;
	/*   text-transform: capitalize; */
}

p, ul, ol, dd, dt, .m-pull-quote, .a-blockquote-footer {
	font-size: 1rem;
	line-height: 1.4rem;
}

.email {
	word-wrap: break-word;
}

ol {
	margin-left: -1.5rem;
}

ol li {
	padding: 5px 0 0 8px;
}

.has-border {
	border-bottom: 1px solid;
}

.m-block-quote {
	margin: 1rem 0;
	padding: 0 1rem;
	display: block;
	/*   width: 65%; */
	float: left;
	clear: left;
	text-align: center;
}

.m-block-quote .a-blockquote-footer {
	padding-top: 0.5rem;
	font-weight: bold;
}

.modal-header {
	padding: 1rem 0;
	margin: 0 1rem;
}

.modal-content {
	border-radius: 0;
	padding: 1rem;
}

.modal-footer {
	border: 0;
}

.a-quotation {
	display: block;
	position: relative;
}

.a-quotation .a-quote-icon {
	width: 8%;
	position: relative;
	top: -17px;
}

.a-quotation:before, .a-quotation:after {
	content: "";
	top: 0;
	width: 42%;
	display: inline-block;
	position: absolute;
}

.a-quotation:before {
	left: 0;
	margin-left: 0px;
}

.a-quotation:after {
	right: 0;
	margin-right: 0px;
}

.m-block-quote p {
	font-size: 1rem;
}

.m-pull-quote {
	display: block;
	padding: 1rem;
	clear: left;
	margin: 1rem 0 1rem;
}

a {
	font-size: 1rem;
}

.a-custom-h4, .a-custom-ul {
	color: #ffffff;
}

.a-custom-h4 a, .a-custom-ul a {
	color: #ffffff;
}

ul {
	list-style-type: disc;
}

a {
	color: #003893;
	-webkit-transition: none;
	-o-transition: none;
	-moz-transition: none;
	transition: none;
}

p {
	margin-bottom: 1rem;
}

button {
	font-weight: bold;
	font-family: "Helvetica Neue", "Helvetica", "Arial", sans-serif;
}

iframe {
	width: 100%;
}

main {
	margin-bottom: 2rem;
}

aside {
	margin-bottom: 2rem;
}

figure {
	margin: 1rem 0;
}

.m-card-image {
	margin: 0;
}

.m-lightbox figure {
	margin: 0;
}

figcaption {
	padding: 1rem;
	font-style: italic;
	font-size: 1rem;
	line-height: 1.5rem;
}

.m-card--link {
	text-decoration: none;
}

.m-card--link:hover {
	text-decoration: underline;
}

/*
*** IE BUG FIXES
*/
@media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
	/* IE10+ CSS styles go here */
	.slick-slider, .slick-list {
		width: 100%;
	}
	#gateway-nav {
		height: 48px;
	}
	.sub-nav-group {
		width: 20rem;
	}
}

/*
*** Safari Fixes for Hero Slider on Home Page
*/
/*
*** JUICER FEED OVERRIDE
*/
#juicer-feed-override {
	max-height: 100% !important;
}

/*
*** Marketing Pages
*/
.marketing-page .m-caption-overlay {
	top: 25vh;
}

@media (min-width: 768px) {
	.marketing-page .m-caption-overlay {
		top: 46%;
	}
}

.marketing-page .a-figure-caption {
	padding-top: 2rem;
}

@media (min-width: 768px) {
	.marketing-page .a-figure-caption {
		padding-top: 4rem;
	}
}

.developer-note {
	clear: both;
}

@media (min-width: 992px) {
	.a-base-button {
		width: auto;
	}
}

.--layout-column-divider {
	border-right: 1px solid #ffffff;
}

.--layout-width-50 {
	width: 100%;
}

@media (min-width: 992px) {
	.--layout-width-50 {
		width: 50%;
	}
}

.vertical-center--layout {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

/*
*@desc Custom Grid Styles
*/
.container-base {
	width: 100%;
	padding-right: 15px;
	padding-left: 15px;
	margin-right: auto;
	margin-left: auto;
}

/*
*@desc Custom Grid Styles
*@extends .container-base
*/
.container-max-width--1650 {
	max-width: 1650px;
}

.a-layout-fullscreen-arrows {
	display: block;
	width: 95%;
	top: -6rem;
	position: relative;
	margin: 0 auto;
}

@media (min-width: 768px) {
	.a-layout-fullscreen-arrows {
		display: none;
	}
}

.a-layout-vertical-center {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

.layout-inline-block {
	display: inline-block;
}

.layout-block {
	display: block;
}

.layout-fullwidth {
	width: 100%;
}

.--layout-height {
	height: auto;
}

@media (min-width: 768px) {
	.--layout-height {
		height: 65vh;
	}
}

.--layout-horizontal-image-height {
	padding: 10rem 0;
}

@media (min-width: 768px) {
	.--layout-horizontal-image-height {
		padding: 4rem 0;
	}
}

@media (min-width: 992px) {
	.--layout-horizontal-image-height {
		padding: 7rem 0;
	}
}

.--layout-vertical-image-height {
	padding: 8rem 0;
	margin-bottom: 1rem;
}

@media (min-width: 768px) {
	.--layout-vertical-image-height {
		padding: 5rem 0;
	}
}

@media (min-width: 992px) {
	.--layout-vertical-image-height {
		padding: 7rem 0;
	}
}

@media (min-width: 1200px) {
	.--layout-vertical-image-height {
		padding: 12rem 0;
	}
}

.--layout-card-padding {
	padding: 2rem 3rem 2rem 1.5rem;
}

.--layout-horizontal-card-padding {
	padding: 1px 1rem 1rem 1rem;
}

@media (min-width: 768px) {
	.--layout-horizontal-card-padding {
		padding-left: 16px;
		padding-top: 1px;
		padding-bottom: 1px;
		padding-right: 0;
	}
}

.--layout-vertical-card-padding {
	padding-top: 1px;
	padding-right: 1rem;
	padding-left: 1rem;
	padding-bottom: 1rem;
}

.--layout-home-cta-header {
	background: #d8d8d8 !important;
	padding-left: 2rem;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

.home-cta-base--layout {
	background: #003893;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

.home-cta--bgcolor-one {
	background: #003893;
}

.home-cta--bgcolor-two {
	background: #14325f;
}

.home-cta--bgcolor-three {
	background: #0054A0;
}

/*
** @desc Layout for Card images
*/
.layout-card-img--row {
	padding: 1px 1rem 0;
}

/*
** Layout for Footer section
*/
.hasTopBorder--layout {
	border-top: 1px solid #ffffff;
	padding-top: 0.5rem;
}

.footer-bottom-ctas--layout {
	margin-right: -15px;
}

@media all and (min-width: 578px) and (max-width: 768px) {
	.footer-bottom-ctas--layout {
		margin-right: -2rem;
	}
}

.center-in-column--layout {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-flex-wrap: wrap;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
	-webkit-box-align: center;
	-webkit-align-items: center;
	-moz-box-align: center;
	-ms-flex-align: center;
	align-items: center;
}

@media (min-width: 576px) {
	.center-in-column--layout {
		-webkit-box-pack: center;
		-webkit-justify-content: center;
		-moz-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
	}
}

.vertical-in-column--layout {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-flex-wrap: wrap;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-webkit-align-content: center;
	-ms-flex-line-pack: center;
	align-content: center;
}

/*
* Base Atoms
*/
a {
	text-decoration: underline;
}

.a-bold-text {
	font-weight: bold;
}

/*
*@desc Fast Facts 
*/
.a-fact {
	font-size: 5rem;
	text-align: center;
}

/*
*@desc Fast Facts Skins
*@extends .a-fact
*/
.a-fact-skin-orange {
	color: #CF4B06;
}

/*
*@desc Calendar Atoms
*/
.a-date-month, .a-date-day, .a-date-number {
	color: #ffffff;
}

.a-date-month {
	font-size: 1.375rem;
	line-height: 1.688rem;
	font-weight: lighter;
	background: #CF4B06;
	position: absolute;
	width: 30%;
	top: 17px;
	z-index: 5;
	text-align: center;
	font-weight: 300;
	padding-top: 0.5rem;
	padding-bottom: 0.5rem;
	color: #ffffff;
	display: block;
}

.a-date-number {
	font-weight: bold;
	font-size: 3.75rem;
	line-height: 2.5rem;
	color: #ffffff;
	display: block;
}

.a-date-day {
	font-size: 0.688rem;
	line-height: 1.063rem;
	font-weight: bold;
}

.a-calendar-caption {
	background: rgba(0, 0, 0, 0.5);
	padding: 2rem;
	text-align: center;
	width: 100%;
	position: relative;
	left: 50%;
	top: 50%;
	margin-top: -3rem;
	margin-bottom: -3rem;
	-webkit-transform: translate(-50%, -50%);
	-moz-transform: translate(-50%, -50%);
	-ms-transform: translate(-50%, -50%);
	-o-transform: translate(-50%, -50%);
	transform: translate(-50%, -50%);
}

@media screen and (min-width: 992px) and (max-width: 1250px) {
	.a-calendar-caption {
		padding: 1rem;
		margin-top: -2rem;
		margin-bottom: -2rem;
	}
}

.a-date-month, .a-date-number, .a-calendar-caption {
	text-transform: uppercase;
}

/* 
** Links Atoms
*/
a {
	text-decoration: none;
}

a:hover {
	text-decoration: underline;
}

.a-cta {
	padding-top: 2rem;
	padding-left: 1rem;
	padding-right: 1rem;
}

.a-event-cta {
	color: inherit;
	text-decoration: none;
}

.a-event-cta:hover {
	color: inherit;
}

.o-calendar .m-card:hover {
	border-bottom: 5px solid #00CC36;
	cursor: pointer;
}

.heading-link--has-border {
	text-decoration: none;
}

.a-fullscreen-slide {
	background-size: cover;
	background-position: top center;
	background-repeat: no-repeat;
	height: 50vh;
	display: -webkit-box !important;
	display: -webkit-flex !important;
	display: -moz-box !important;
	display: -ms-flexbox !important;
	display: flex !important;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

.a-fullscreen-slide:before {
	content: '';
	position: absolute;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
	background: rgba(20, 50, 95, 0.7);
}

.a-fullscreen-slide-orange:before {
	content: '';
	position: absolute;
	left: 0;
	right: 0;
	top: 0;
	bottom: 0;
	background: rgb(207, 75, 6, .8);
}

@media (min-width: 768px) {
	.a-fullscreen-slide {
		height: 65vh;
	}
	.a-fullscreen-slide:before {
		content: '';
		position: absolute;
		left: 0;
		right: 0;
		top: 0;
		bottom: 0;
		background: rgba(20, 50, 95, 0);
	}
}

.a-fullscreen-dots {
	display: none;
	visibility: visible;
}

.a-fullscreen-dots li {
	position: relative;
	display: inline-block;
	padding: 0;
	cursor: pointer;
	margin: 5px 0.2rem;
}

@media (min-width: 768px) {
	.a-fullscreen-dots {
		display: block;
		position: relative;
		top: -4rem;
		left: 0.5rem;
	}
}

.a-light-dots {
	width: 20.8px !important;
	height: 20.8px !important;
	border-radius: 50% !important;
	padding: 12px;
	display: inline-block;
	vertical-align: middle;
	cursor: pointer;
	background: transparent;
	border: 1px solid #ffffff;
}

/**
* @desc     Base Button Styles
*/
button:hover {
	cursor: pointer;
}

.a-base-button {
	font-weight: bold;
	font-size: 1.25rem;
	line-height: 1.5rem;
	text-transform: none;
	text-decoration: none;
	padding: 0.5rem 1rem;
	display: block;
	text-align: center;
	margin: 1rem 0;
}

.a-base-button--full-width {
	font-weight: bold;
	font-size: 1.25rem;
	line-height: 1.5rem;
	text-transform: none;
	text-decoration: none;
	padding: 0.5rem 1rem;
	display: block;
	text-align: center;
	margin: 1rem 0;
}

.a-base-button:hover {
	text-decoration: none;
	text-align: center;
}

.a-width--50 {
	width: 50%;
}

.a-base-button--inline-block {
	padding: 0.5rem 1rem;
	display: inline-block;
	width: auto;
}

/**
* @desc         Button Skins
* @extends      .a-base-button
*/
.a-primary-button--light {
	background: #ffffff;
	color: #14325f !important;
	font-weight: bold;
	text-transform: none;
}

.a-primary-button--light:hover {
	background: #14325f;
	color: #ffffff !important;
}

/*
*** Hero Slider Buttons
*/
.slick-dots {
	position: relative;
	display: block;
	width: 100%;
	list-style: none;
	text-align: left;
	visibility: visible;
}

/* Arrows */
.slick-prev,
.slick-next {
	visibility: visible;
	font-size: 1rem;
	line-height: 0;
	position: absolute;
	top: 50%;
	display: block;
	width: auto;
	height: auto;
	padding: 30px 0 0 0;
	-webkit-transform: translate(0, -50%);
	-moz-transform: translate(0, -50%);
	-ms-transform: translate(0, -50%);
	-o-transform: translate(0, -50%);
	transform: translate(0, -50%);
	cursor: pointer;
	color: transparent;
	border: none;
	outline: none;
	background: transparent;
	z-index: 5;
}

.slick-prev:hover,
.slick-prev:focus,
.slick-next:hover,
.slick-next:focus {
	background: transparent;
}

.slick-prev:hover:before,
.slick-prev:focus:before,
.slick-next:hover:before,
.slick-next:focus:before {
	opacity: 1;
}

.slick-prev.slick-disabled:before,
.slick-next.slick-disabled:before {
	opacity: .25;
}

.slick-prev:before,
.slick-next:before {
	font-family: 'Font Awesome 5 Free';
	font-size: 3rem;
	line-height: 1;
	opacity: 1;
	color: #ffffff;
	cursor: pointer;
}

.slick-prev {
	left: 1rem;
}

.slick-prev:before {
	content: '\f104';
}

.slick-next {
	right: 1rem;
}

.slick-next:before {
	content: '\f105';
}

.a-figure-caption {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	width: 100%;
	background: transparent;
	margin-bottom: 0;
	top: 0;
	padding-top: 2rem;
	padding-bottom: 2rem;
	padding-left: 2rem;
	padding-right: 2rem;
}

.a-figure-caption p {
	display: none;
}

@media (min-width: 768px) {
	.a-figure-caption {
		width: 100%;
		height: 65vh;
	}
	.a-figure-caption p {
		display: block;
	}
}

.a-fullwidth-image {
	width: 100%;
}

.a-fullwidth-bg-image {
	background-size: cover;
	background-position: top;
	background-repeat: no-repeat;
}

.a-bg-color-overlay {
	position: relative;
	width: 100%;
	height: 100%;
	background: center center no-repeat;
	background-size: cover;
}

.--layout-bg-color-orange:before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background-image: -webkit-gradient(linear, left top, right top, from(#b93a00), to(#b93a00));
	background-image: -webkit-linear-gradient(left, #b93a00, #b93a00);
	background-image: -moz- oldlinear-gradient(left, #b93a00, #b93a00);
	background-image: -o-linear-gradient(left, #b93a00, #b93a00);
	background-image: linear-gradient(to right, #b93a00, #b93a00);
	opacity: 0.8;
}

.--layout-bg-color-blue:before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background-image: -webkit-gradient(linear, left top, right top, from(#003893), to(#003893));
	background-image: -webkit-linear-gradient(left, #003893, #003893);
	background-image: -moz- oldlinear-gradient(left, #003893, #003893);
	background-image: -o-linear-gradient(left, #003893, #003893);
	background-image: linear-gradient(to right, #003893, #003893);
	opacity: 0.8;
}

/*
** Footer Atoms
*/
.a-temperature {
	color: #003893;
	font-size: 1.875rem;
	line-height: 2.25rem;
	font-weight: bold;
	margin-bottom: 0;
}

.a-weather-status {
	color: #282828;
	font-size: 0.75rem;
	line-height: 1.25rem;
	display: block;
	font-weight: normal;
}

.a-temp-fah {
	font-family: Arial, Helvetica, sans-serif;
}

.a-footer-links--heading {
	color: #ffffff;
	text-transform: uppercase;
	margin-bottom: 1rem;
	border-bottom: 1px solid #ffffff;
}

.a-news-story--title {
	color: #003893;
	text-transform: uppercase;
	font-weight: bold;
	font-size: 0.75rem;
	line-height: 1rem;
}

.a-copyright-address {
	color: #FFFFFF !important;
}
/* Hero Overlay Blue */
.m-caption-overlay {
	height: auto;
	position: absolute;
	top: 50%;
	-webkit-transform: translateY(-50%);
	-moz-transform: translateY(-50%);
	-ms-transform: translateY(-50%);
	-o-transform: translateY(-50%);
	transform: translateY(-50%);
	left: 0;
	bottom: 0;
	width: 100%;
	padding: 0 2rem;
	display: block;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-align: center;
	-webkit-align-items: center;
	-moz-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	display: block;
}

@media (min-width: 768px) {
	.m-caption-overlay {
		position: absolute;
		top: 50%;
		-webkit-transform: translate(0%, -50%);
		-moz-transform: translate(0%, -50%);
		-ms-transform: translate(0%, -50%);
		-o-transform: translate(0%, -50%);
		transform: translate(0%, -50%);
		position: relative;
		width: 50%;
		height: 65vh;
		width: 50%;
		height: 65vh;
		left: -15px;
		background: rgba(20, 50, 95, 0.7);
	}
}

@media (min-width: 992px) {
	.m-caption-overlay {
		width: 40%;
	}
}

.m-caption-overlay .a-base-button {
	width: 100%;
}

@media (min-width: 576px) {
	.m-caption-overlay .a-base-button {
		width: 50%;
	}
}

.m-caption-overlay figure {
	background: transparent !important;
}
/* Hero Overlay Orange */
.m-caption-overlay-orange {
	height: auto;
	position: absolute;
	top: 50%;
	-webkit-transform: translateY(-50%);
	-moz-transform: translateY(-50%);
	-ms-transform: translateY(-50%);
	-o-transform: translateY(-50%);
	transform: translateY(-50%);
	left: 0;
	bottom: 0;
	width: 100%;
	padding: 0 2rem;
	display: block;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-align: center;
	-webkit-align-items: center;
	-moz-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	display: block;
}

@media (min-width: 768px) {
	.m-caption-overlay-orange {
		position: absolute;
		top: 50%;
		-webkit-transform: translate(0%, -50%);
		-moz-transform: translate(0%, -50%);
		-ms-transform: translate(0%, -50%);
		-o-transform: translate(0%, -50%);
		transform: translate(0%, -50%);
		position: relative;
		width: 50%;
		height: 65vh;
		width: 50%;
		height: 65vh;
		left: -15px;
		background: rgba(207, 75, 6, 0.8);
	}
}

@media (min-width: 992px) {
	.m-caption-overlay-orange {
		width: 40%;
	}
}

.m-caption-overlay-orange .a-base-button {
	width: 100%;
}

@media (min-width: 576px) {
	.m-caption-overlay-orange .a-base-button {
		width: 50%;
	}
}

.m-caption-overlay-orange figure {
	background: transparent !important;
}

/*
** Home Tab Accordion Molecules
*/
#tab1 .tab-panel--left, #tab4 .tab-panel--left {
	padding-right: 15px;
}

.tab-panel--left {
	border-right: 0;
	padding-right: 15px;
}

@media (min-width: 768px) {
	.tab-panel--left {
		padding-right: 4rem;
	}
}

.tab-panel--right {
	padding-left: 15px;
}

@media (min-width: 768px) {
	.tab-panel--right {
		padding-left: 4rem;
	}
}

.tab-panel--left, .tab-panel--right {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

@media (min-width: 768px) {
	.tab-panel--left, .tab-panel--right {
		-webkit-box-pack: unset;
		-webkit-justify-content: unset;
		-moz-box-pack: unset;
		-ms-flex-pack: unset;
		justify-content: unset;
	}
}

.container--tab {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-flex-wrap: wrap;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

@media (min-width: 992px) {
	.container--tab {
		-webkit-box-orient: horizontal;
		-webkit-box-direction: normal;
		-webkit-flex-direction: row;
		-moz-box-orient: horizontal;
		-moz-box-direction: normal;
		-ms-flex-direction: row;
		flex-direction: row;
	}
}

.container-fluid--custom {
	width: 100%;
	padding-right: 0px;
	padding-left: 0px;
	margin-right: auto;
	margin-left: auto;
}

.row--custom {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-flex-wrap: wrap;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	margin-right: 0px;
	margin-left: 0px;
}

.tab-content--heading {
	display: none;
	width: 100%;
	text-align: center;
}

.m-card {
	margin: 1rem 0;
}

.m-card .m-card-content {
	padding: 1rem 2rem 1rem 2rem;
}

.m-card--horizontal {
	margin-left: 0px;
	margin-right: 0;
}

.m-card--vertical .a-fullwidth-bg-image {
	padding: 20rem 0;
}

@media (min-width: 768px) {
	.m-card--vertical .a-fullwidth-bg-image {
		padding: 10rem 0;
	}
}

.inner .m-card--horizontal .m-card-image {
	min-width: -webkit-calc(100%);
	min-width: -moz-calc(100%);
	min-width: calc(100%);
}

.m-card--horizontal figure {
	background-color: transparent !important;
}

.m-card--horizontal .m-card-image {
	position: relative;
	border: 0;
	min-width: -webkit-calc(100% + 27px);
	min-width: -moz-calc(100% + 27px);
	min-width: calc(100% + 27px);
	min-height: -webkit-calc(100% + 0px);
	min-height: -moz-calc(100% + 0px);
	min-height: calc(100% + 0px);
	-webkit-backface-visibility: hidden;
	backface-visibility: hidden;
	overflow: hidden;
	width: 100%;
	height: 30vh;
	top: 0;
	left: 0;
	-webkit-transform: none;
	-moz-transform: none;
	-ms-transform: none;
	-o-transform: none;
	transform: none;
	background-size: cover;
	background-position: top center;
	background-repeat: no-repeat;
}

@media (min-width: 576px) {
	.m-card--horizontal .m-card-image {
		height: 50vh;
	}
}

@media (min-width: 992px) {
	.m-card--horizontal .m-card-image {
		height: 200px;
	}
}

@supports ((-webkit-transform: translate3d(0, 0, 0)) or (transform: translate3d(0, 0, 0))) {
	.m-card--horizontal .m-card-image {
		top: 50%;
		left: 50%;
		-webkit-transform: translate3d(-50%, -50%, 0) scale(1);
		-moz-transform: translate3d(-50%, -50%, 0) scale(1);
		transform: translate3d(-50%, -50%, 0) scale(1);
	}
}

.m-card--horizontal .m-card-content {
	margin-top: 0px;
	margin-bottom: 0px;
	padding: 1rem 2rem;
}

@media (min-width: 992px) {
	.m-card--horizontal .m-card-content {
		margin-top: 1rem;
		margin-bottom: 1rem;
		padding: 0.5rem;
	}
}

.m-card--horizontal .a-base-button {
	width: 100%;
}

@media (min-width: 992px) {
	.m-card--horizontal .a-base-button {
		width: 50%;
	}
}

.m-card--vertical.a-card--bgcolor-light .m-card-image {
	border: 1px solid #ffffff;
}

.m-card--vertical.a-card--bgcolor-dark .m-card-image {
	border: 1px solid #282828;
}

.m-card--vertical, .m-card--homecustom {
	border-bottom: 5px solid transparent;
}

.m-card--vertical li, .m-card--homecustom li {
	margin-left: -1rem;
}

.m-card img {
	width: 100%;
}

.o-tabs-accordion--custom .m-card--horizontal .m-card-image {
	min-width: -webkit-calc(100% + 31px);
	min-width: -moz-calc(100% + 31px);
	min-width: calc(100% + 31px);
	min-height: -webkit-calc(100% + 1px);
	min-height: -moz-calc(100% + 1px);
	min-height: calc(100% + 1px);
}

@media (min-width: 992px) {
	.o-tabs-accordion--custom .m-card--horizontal .m-card-image {
		min-width: -webkit-calc(100% + 30px);
		min-width: -moz-calc(100% + 30px);
		min-width: calc(100% + 30px);
	}
}

.o-tabs-accordion--custom .m-card--horizontal .m-card-content {
	padding: 0.5rem;
}

.m-card--link:hover {
	text-decoration: none;
}

/*
** Home Cards Molecule
*/
/*
** Fast Facts
*/
.m-fast-fact {
	padding: 3rem;
	margin: 4rem 0;
	border: 0;
}

@media (min-width: 992px) {
	.m-fast-fact {
		border-right: 1px solid #00CC36;
		padding: 1rem;
	}
}

.m-fast-fact .a-fact {
	margin-bottom: 2.5rem;
}

.m-fast-fact--last-child {
	border-right: 0;
}

/*
** Events Center Mode Slider Molecules
*/
.localist-widget-hl button {
	background: transparent;
	border: transparent;
}

.localist-widget-hl .slick-slide {
	-webkit-transform: scale(1);
	-moz-transform: scale(1);
	-ms-transform: scale(1);
	-o-transform: scale(1);
	transform: scale(1);
	opacity: 1;
	padding: 0;
	margin: 0;
}

@media (min-width: 576px) {
	.localist-widget-hl .slick-slide {
		-webkit-transform: scale(0.8);
		-moz-transform: scale(0.8);
		-ms-transform: scale(0.8);
		-o-transform: scale(0.8);
		transform: scale(0.8);
		opacity: 0.7;
		-webkit-transition: 0.3s ease-in-out all;
		-o-transition: 0.3s ease-in-out all;
		-moz-transition: 0.3s ease-in-out all;
		transition: 0.3s ease-in-out all;
	}
}

.localist-widget-hl .slick-slide.slick-center {
	opacity: 1;
	-webkit-transform: scale(1);
	-moz-transform: scale(1);
	-ms-transform: scale(1);
	-o-transform: scale(1);
	transform: scale(1);
	-webkit-transition: 0.2s ease transform;
	-o-transition: 0.2s ease transform;
	-moz-transition: 0.2s ease transform;
	transition: 0.2s ease transform;
	position: relative;
	z-index: 5 !important;
}

.localist-widget-hl .slick-slide.slick-center .event-card {
	height: auto;
	z-index: 10 !important;
	-webkit-box-shadow: 0 0 5px 2px rgba(219, 219, 219, 0.5);
	box-shadow: 0 0 5px 2px rgba(219, 219, 219, 0.5);
	margin-left: 1rem;
	margin-right: 1rem;
}

@media (min-width: 576px) {
	.localist-widget-hl .slick-slide.slick-center .event-card {
		margin-left: -58px;
		margin-right: -58px;
	}
}

.localist-widget-hl figcaption {
	margin-top: -0.5rem;
	margin-bottom: 4rem;
	text-align: center;
}

/*
** Blog Events Molecules
*/
.m-events {
	padding-right: 4rem;
}

.m-events .a-date-month {
	background: transparent;
	width: 100%;
	position: relative;
	display: block;
	text-align: center;
}

.m-events .a-date-month, .m-events .a-date-number {
	color: #14325f;
}

.m-events .a-date-number, .m-events .a-date-day {
	display: block;
	margin-top: 5px;
}

.m-events .a-button--outline {
	width: 50%;
	margin: 1rem auto;
}

@media (min-width: 768px) {
	.m-events .a-button--outline {
		width: 100%;
	}
}

@media (min-width: 992px) {
	.m-events .a-button--outline {
		width: 50%;
	}
}

.event-dates--layout {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
}

@media (min-width: 992px) {
	.event-dates--layout {
		-webkit-box-pack: center;
		-webkit-justify-content: center;
		-moz-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
	}
}

.m-blog {
	padding-left: 0rem;
}

@media (min-width: 768px) {
	.m-blog {
		padding-left: 4rem;
	}
}

.m-blog .a-base-button {
	width: 50%;
	margin: 2rem auto;
}

.m-blog .m-card-content .a-base-button {
	margin: 0 auto;
	width: 100%;
}

@media (min-width: 768px) {
	.m-blog .m-card-content .a-base-button {
		margin: unset;
		width: 50%;
	}
}

/*
*** Back To Top Button Molecules
*/
#js-back-to-top--container {
	display: none;
}

@media (min-width: 768px) {
	#js-back-to-top--container {
		display: block;
	}
}

.m-back-to-top-base {
	position: fixed;
	/* Fixed/sticky position */
	bottom: 20px;
	/* Place the button at the bottom of the page */
	right: 30px;
	/* Place the button 30px from the right */
	z-index: 99;
	/* Make sure it does not overlap */
	border: none;
	/* Remove borders */
	outline: none;
	/* Remove outline */
	width: 2.938rem;
	height: 2.938rem;
}

.m-back-to-top span {
	font-size: 1.313rem;
}

.m-back-to-top span:hover {
	cursor: pointer;
}

/*
** Footer Molecules
*/
.m-weather-info {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	-webkit-align-content: center;
	-ms-flex-line-pack: center;
	align-content: center;
}

.m-footer-social-icons {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
	margin-left: -0.1px;
}

@media (min-width: 768px) {
	.m-footer-social-icons {
		margin-left: 0;
	}
}

@media (min-width: 992px) {
	.m-footer-social-icons {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-orient: horizontal;
		-webkit-box-direction: normal;
		-webkit-flex-direction: row;
		-moz-box-orient: horizontal;
		-moz-box-direction: normal;
		-ms-flex-direction: row;
		flex-direction: row;
		-webkit-box-pack: end;
		-webkit-justify-content: flex-end;
		-moz-box-pack: end;
		-ms-flex-pack: end;
		justify-content: flex-end;
	}
}

.m-footer-social-icons .fa {
	color: #282828;
	font-size: 2rem;
	padding: 0.5rem 0.5rem 0.5rem 0;
}

.m-news-story {
	margin-top: 1rem;
}

@media (min-width: 768px) {
	.m-news-story {
		margin-top: 1rem;
	}
}

.m-footer-links {
	margin-bottom: 1.5rem;
}

.m-footer-links ul {
	padding: 0;
}

.m-footer-links li {
	list-style: none;
}

.m-footer-links a {
	color: #ffffff;
	font-size: 0.85rem;
	line-height: 1.2rem;
}

.m-footer-links--right {
	margin-top: -1rem;
}

@media (min-width: 576px) {
	.m-footer-links--right {
		margin-top: 0;
	}
}

@media (min-width: 768px) {
	.m-footer-links--right {
		margin-top: -1rem;
	}
}

.m-footer-links--layout {
	margin-top: -1rem;
}

@media (min-width: 768px) {
	.m-footer-links--layout {
		margin-top: 0;
	}
}

/*
*** GET INVOVLED SECTION MOLECULES ***
*/
#cta-region .a-cta {
	text-decoration: none;
}

#cta-region .heading--dark {
	color: #282828 !important;
	font-size: 2.188rem;
	line-height: 2.5rem;
	text-transform: uppercase;
	border-bottom: 0 !important;
}

#cta-region h2, #cta-region h3, #cta-region h4, #cta-region h5, #cta-region h6 {
	color: #ffffff;
	border-bottom: 1px solid #ffffff;
}

#cta-region p {
	color: #ffffff;
	margin: 1rem 0;
}

/*
*** Content Top Molecules
*/
#m-content-top {
	margin-bottom: 16px;
}

#m-content-top.state-content-top--hasBgImage {
	-webkit-box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.6);
	box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.6);
}

#m-content-top img {
	width: 100%;
	-webkit-box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.6);
	box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.6);
}

/*
*** Right Sidebar Molecule
*/
.m-embed-video-container {
	margin: 1rem 0;
}

.m-embed-video-container iframe {
	border: 0;
}

.a-embed-video p {
	margin: 0.5rem 0;
}

/*
** Breadcrumb Molecules
*/
.pdf-button {
	height: 25px;
	position: relative;
	margin-top: -25px;
	padding-top: .25rem;
	padding-left: .5rem;
	padding-right: .5rem;
	font-size: .8rem;
	font-weight: 500;
	text-transform: none;
	text-align: center;
	line-height: .938rem;
}

@media (max-width: 905px) {
	#pdf-button {
		display: none;
	}
}

.o-breadcrumb {
	background: #EFEFEF;
	padding: 0.5rem 0;
	margin-top: 60px;
}

.o-breadcrumb .m-breadcrumb a {
	color: #282828;
	text-decoration: none;
}

.o-breadcrumb .m-breadcrumb a:hover {
	text-decoration: underline;
}

.o-breadcrumb .m-breadcrumb a:active {
	text-decoration: underline;
}

.o-breadcrumb .m-breadcrumb a:focus {
	text-decoration: underline;
}

.o-breadcrumb .m-breadcrumb .active {
	text-decoration: underline;
	color: #282828;
}

@media (max-width: 905px) {
	.o-breadcrumb {
		margin-top: 60px;
	}
}

@media (min-width: 906px) {
	.o-breadcrumb {
		margin-top: 115px;
	}
}


.breadcrumb-catalog {
	background: #EFEFEF;
	padding: 0.5rem 0;
	margin-top: 0px !important;
}

@media (max-width: 905px) {
	.breadcrumb-catalog {
		margin-top: 0px !important;
		margin-bottom: 20px;
	}
}

@media (min-width: 906px) {
	.breadcrumb-catalog {
		margin-top: 0px !important;
		margin-bottom: 20px;
	}
}

.m-content-header {
	background: transparent;
	padding: 1rem 0 1rem 0;
}

/*
*** ACCORDION MOLECULES ***
*/
.accordion-container {
	margin: 1rem 0 1rem 0;
	padding-bottom: 1rem;
}

.accordion-container h3 {
	border-bottom: 0 !important;
}

.accordion-container .accordion-card {
	margin: 1rem 0 -1rem 0;
	border: 0;
	background: transparent;
}

.accordion-container .accordion-card a[data-toggle=collapse] {
	display: block;
	line-height: 1.2;
	text-decoration: none;
	padding: 0;
	border: 0;
	background: transparent;
}

.accordion-container .accordion-card .accordion-link.collapsed {
	padding: 1rem;
}

.accordion-container .accordion-card .card-header a:before {
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f105";
	display: block;
	margin-right: 1rem;
	float: left;
	-webkit-transform: rotateZ(90deg);
	-moz-transform: rotateZ(90deg);
	-ms-transform: rotate(90deg);
	-o-transform: rotateZ(90deg);
	transform: rotateZ(90deg);
	-webkit-transition: all .2s;
	-o-transition: all .2s;
	-moz-transition: all .2s;
	transition: all .2s;
}

.accordion-container .accordion-card .card-header a.collapsed:before {
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f105";
	-webkit-transform: rotateZ(0deg);
	-moz-transform: rotateZ(0deg);
	-ms-transform: rotate(0deg);
	-o-transform: rotateZ(0deg);
	transform: rotateZ(0deg);
}

.accordion-container .accordion-card .accordion-link {
	padding: 1rem;
	border-radius: 0;
}

.accordion-container .accordion-card .card-block {
	border-radius: 0;
	padding: 1rem;
}

.accordion-container .accordion-card p {
	margin: 0.5rem 1rem;
}

/*
*** TABLE MOLECULES ***
*/
.m-table {
	background: transparent;
	margin: 1rem 0;
}

.m-table .table-header {
	background: transparent;
	border: 0;
	padding: 0;
	margin-bottom: 1.5rem;
}

.m-table .table th, .m-table .table td {
	text-align: center;
}

.m-table .a-table-content {
	border: 0;
}

.m-table thead {
	border-bottom: 0;
}

.m-table thead th {
	text-transform: uppercase;
	vertical-align: middle;
	text-align: center;
}

@media (max-width: 768px) {
	.m-table .hide-phone {
		display: none;
	}
}

@media (max-width: 992px) {
	.m-table .hide-tablet {
		display: none;
	}
}

.dataTables_length {
	padding: 0.5rem;
	margin: 0.5rem;
	float: none !important;
	text-align: left !important;
}

@media (min-width: 576px) {
	.dataTables_length {
		float: left !important;
		text-align: center !important;
	}
}

.dataTables_filter {
	padding: 0.5rem;
	margin: 0.5rem;
	float: none !important;
	text-align: left !important;
}

@media (min-width: 576px) {
	.dataTables_filter {
		float: right !important;
		text-align: center !important;
	}
}

.dataTables_filter label {
	text-transform: uppercase;
	font-weight: bold;
}

.dataTables_length label {
	text-transform: uppercase;
	font-weight: bold;
}

.dataTables_wrapper .dataTables_filter input {
	margin-left: 0.5em;
	position: relative;
	height: 3vh;
}

#search-table_info {
	text-transform: uppercase;
	font-weight: bold;
}

.paginate_button.current {
	border-radius: 0px !important;
	border: 0 !important;
}

#search-table_previous, #search-table_next {
	border-radius: 0px;
	text-transform: uppercase;
	font-weight: bold;
}

#search-table_previous {
	padding: 0rem 1rem !important;
}

#search-table_next {
	padding: 0rem 1rem !important;
}

.dataTables_wrapper .dataTables_paginate .paginate_button.disabled, .dataTables_wrapper .dataTables_paginate .paginate_button.disabled:hover, .dataTables_wrapper .dataTables_paginate .paginate_button.disabled:active {
	cursor: default;
	border: 0px !important;
	background: transparent !important;
	-webkit-box-shadow: none;
	box-shadow: none;
}

table.dataTable.row-border tbody th, table.dataTable.row-border tbody td, table.dataTable.display tbody th, table.dataTable.display tbody td {
	border-top: 0px;
}

#search-table_wrapper tbody {
	border: 0px;
}

.dataTables_paginate, .dataTables_info {
	padding: 0.5rem;
	margin: 0.5rem;
	float: none;
	text-align: left;
}

@media (min-width: 576px) {
	.dataTables_paginate, .dataTables_info {
		float: left;
		text-align: center;
	}
}

/*
*** Table Code from Interim West Valley Site - uses .table-striped class
*/
/* *** table default *** */
/*
** Call to Action Molecules
*/
.m-cta--card {
	padding: 2rem 2.1rem;
	margin: 1rem 0 2rem 0;
}

.m-cta--card h2, .m-cta--card h3, .m-cta--card h4, .m-cta--card h5, .m-cta--card h6 {
	text-transform: capitalize;
}

.m-cta--card p {
	padding-top: 8px;
	margin-bottom: 0;
}

/*
*** Blue CTA Molecule
*/
.m-cta--blue {
	padding: 1.5rem 2rem;
	margin: 1rem 0 2rem 0;
}

/*
*** jQuery TABS MOLECULES ***
*/
#tabs {
	margin: 0;
	padding: 1rem 0;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	margin: 1rem 0px;
	padding: 0;
	border: 1px solid transparent;
}

@media (min-width: 768px) {
	#tabs {
		margin: 1rem 0;
	}
}

#tabs li.ui-tabs-tab.ui-corner-top.ui-state-default.ui-tab.ui-tabs-active.ui-state-active {
	padding: 0px;
}

.m-tabs {
	margin-left: -1rem;
	margin-right: -1rem;
	margin-top: 1rem;
	margin-bottom: 1rem;
}

@media (min-width: 768px) {
	.m-tabs {
		margin-top: 3rem;
		margin-bottom: 2rem;
		margin-left: -15px;
		margin-right: -15px;
	}
}

.m-tabs h2, .m-tabs h3, .m-tabs h4, .m-tabs h5, .m-tabs h6 {
	text-transform: uppercase;
	border-bottom: 0 !important;
}

.m-tabs .ui-tab a {
	text-align: center;
	display: block;
	word-break: normal;
	text-decoration: none;
	font-size: 0.6875rem;
	padding: 0;
	text-transform: uppercase;
}

.m-tabs .ui-tab {
	list-style: none;
}

.m-tabs .ui-tabs-nav {
	margin: 0 auto;
	padding-left: 0px;
	padding-right: 0px;
	font-weight: bold;
	clear: left;
	width: 100%;
}

.m-tabs .ui-tabs-nav li {
	display: inline-block;
	float: left;
	width: 33.33%;
	position: relative;
}

.m-tabs .ui-tabs-nav a {
	padding: 0.5rem;
}

.m-tabs .a-tab-panel {
	margin-bottom: 2px;
	margin-top: 0px;
	margin-right: 0px !important;
	margin-left: 0px !important;
	clear: left;
	margin-left: 0px;
	margin-right: 0px;
}

@media (min-width: 768px) {
	.m-tabs .a-tab-panel {
		margin-top: -1px;
		margin-right: 0px !important;
		margin-left: 0px !important;
	}
}

.m-tabs .a-tab-content {
	padding: 2rem 2rem 1rem 2rem;
	-webkit-transition: opacity 0.3s ease-in-out;
	-o-transition: opacity 0.3s ease-in-out;
	-moz-transition: opacity 0.3s ease-in-out;
	transition: opacity 0.3s ease-in-out;
}

.m-tabs .ui-tab {
	margin: 0px;
	padding: 2rem 0;
}

@media (min-width: 768px) {
	.m-tabs .ui-tab {
		margin: 0px;
		padding: 0px;
	}
}

.m-tabs .ui-tabs-active {
	padding: 2rem 0;
}

@media (min-width: 768px) {
	.m-tabs .ui-tabs-active {
		padding: 0px;
		border-bottom: 0 !important;
	}
}

.m-tabs .ui-tabs-active a {
	position: relative;
	padding: 2rem;
}

@media (min-width: 768px) {
	.m-tabs .ui-tabs-active a {
		padding: 0.5rem;
	}
}

/*
*** Custom Dropdown Molecule
*/
.m-dropdown {
	display: block;
	width: 100%;
	position: relative;
	padding: 1rem 0;
}

.m-dropdown ul {
	display: none;
	float: left;
	width: 100%;
	z-index: 2;
	background: #ffffff;
	border: 1px solid #282828;
	border-left: 1px solid #282828;
	border-right: 1px solid #282828;
	border-top: 0;
	padding: 0;
}

.m-dropdown ul li {
	display: block;
	float: left;
	width: 100%;
}

.m-dropdown ul li a {
	display: block;
	color: #282828;
	line-height: 1.063rem;
	font-size: 1rem;
	line-height: 1.063rem;
	width: -webkit-calc(100% - 20px);
	width: -moz-calc(100% - 20px);
	width: calc(100% - 20px);
	padding: 0 1.5rem 1rem;
	margin: 0;
	border: 0;
	text-decoration: none;
	font-weight: 300;
}

.m-dropdown ul li a:hover {
	background: transparent;
	color: #003893;
	font-weight: bold;
	border: 0;
	-webkit-box-shadow: none;
	box-shadow: none;
	padding: 0 1.5rem 1rem;
}

.m-dropdown .a-dropdown-menu {
	color: #282828;
	line-height: 1.063rem;
	font-size: 1rem;
	line-height: 1.063rem;
	text-align: left;
	font-weight: 300;
	position: relative;
	border: 1px solid transparent;
	outline: none;
	padding: 1rem 12px;
	cursor: pointer;
	text-transform: unset;
	background: #ffffff;
	display: inline-block;
	width: 100%;
	border-radius: 0;
}

.m-dropdown .a-dropdown-menu:after {
	font-family: Font Awesome 5 Free;
	content: '\f104';
	font-weight: 900;
	font-size: 1.8rem;
	position: absolute;
	color: #9b9b9b;
	-webkit-transform: rotateZ(0deg);
	-moz-transform: rotateZ(0deg);
	-ms-transform: rotate(0deg);
	-o-transform: rotateZ(0deg);
	transform: rotateZ(0deg);
	-webkit-transition: all .2s;
	-o-transition: all .2s;
	-moz-transition: all .2s;
	transition: all .2s;
	right: 0;
	padding: 0 1rem;
}

.m-dropdown.open .a-dropdown-menu:after {
	-webkit-transform: rotateZ(-90deg);
	-moz-transform: rotateZ(-90deg);
	-ms-transform: rotate(-90deg);
	-o-transform: rotateZ(-90deg);
	transform: rotateZ(-90deg);
}

.m-dropdown.open ul {
	display: block;
	position: relative;
	top: 100%;
	padding: 1rem;
}

@media (min-width: 576px) {
	.m-dropdown.open ul {
		position: relative;
	}
}

/*
*** Form Molecules
*/
.form-control .ms-choice {
	height: 34px;
	line-height: 32px;
	font-size: 1rem;
	line-height: 3rem;
}

.inner > form {
	margin: 1rem 0 1rem 0;
}

form {
	clear: left;
}

form, .form-control {
	font-size: 1rem;
	line-height: 1.063rem;
}

label {
	cursor: pointer;
	display: block;
}

.ms-drop ul > li label {
	margin-left: 10px;
}

.a-input-field {
	position: relative;
	margin: 10px 1px 0;
	max-width: 100%;
	overflow: hidden;
}

.a-input-text-label {
	-webkit-transition: 500ms;
	-o-transition: 500ms;
	-moz-transition: 500ms;
	transition: 500ms;
	position: absolute;
	top: 0;
	right: 0;
	left: 0;
	border-top-left-radius: 0px;
	border-top-right-radius: 0px;
	padding-top: 5px;
	padding-bottom: 1px;
	padding-left: 10px;
	text-align: left;
	text-transform: uppercase;
	font-size: 13px;
	line-height: 14px;
	font-weight: bold;
}

.label-reveals {
	margin-left: 0 !important;
}

.m-form .a-input-text {
	-webkit-transition: 500ms;
	-o-transition: 500ms;
	-moz-transition: 500ms;
	transition: 500ms;
	margin-bottom: 10px;
	border: 0;
	border-radius: 0px;
	-webkit-box-shadow: none;
	box-shadow: none;
	padding-top: 20px;
	padding-bottom: 9px;
	height: 54px;
	text-align: left;
}

.m-form .a-input-text-textarea {
	-webkit-transition: 500ms;
	-o-transition: 500ms;
	-moz-transition: 500ms;
	transition: 500ms;
	margin-bottom: 10px;
	border: 0;
	padding-top: 22px !important;
	border-radius: 0px;
	-webkit-box-shadow: none;
	box-shadow: none;
	padding-bottom: 9px;
	height: auto;
	text-align: left;
}

.m-form .a-input-text:focus {
	padding-top: 24px;
}

.m-form .a-input-text:focus + .a-input-text-label {
	border-bottom: 1px solid transparent;
}

.m-form .a-input-text-label {
	margin-left: 10px;
}

.form-control {
	border: 1px solid transparent;
	border-radius: 0;
}

.form-control + .input-group-addon:not(:first-child) {
	border: 0;
	background: transparent;
}

.ms-choice > span {
	padding-left: 13px;
}

.ms-choice > div {
	position: absolute;
	top: 0;
	right: 0;
	width: 20px;
	height: 8px;
}

.ms-drop ul {
	padding: 5px 0px;
}

.input-group-item input[type="text"] {
	border: 1px solid transparent;
}

.form-group select, .form-group textarea {
	padding: 0.375rem 0.75rem !important;
}

.form-group input[type="text"], .form-group input[type="email"], .form-group input[type="number"], .form-group select, .form-group textarea {
	min-height: 52px;
	text-align: left;
}

.form-group select, .form-group textarea {
	padding: 0.75rem 1.5rem;
}

.form-group select {
	cursor: pointer;
}

.form-group input[type="checkbox"],
.form-group input[type="radio"] {
	border: 0;
	clip: rect(0 0 0 0);
	height: 1px;
	margin: -1px;
	overflow: hidden;
	padding: 0;
	position: absolute;
	width: 1px;
}

.form-group input[type="checkbox"]:active + label:before,
.form-group input[type="radio"]:active + label:before {
	-webkit-transition-duration: 0;
	-moz-transition-duration: 0;
	-o-transition-duration: 0;
	transition-duration: 0;
	-webkit-filter: brightness(0.2);
	filter: brightness(0.2);
}

.form-group input[type="checkbox"] + label,
.form-group input[type="radio"] + label {
	position: relative;
	padding-left: 26px;
	font-weight: normal;
}

.form-group input[type="checkbox"] + label:before,
.form-group input[type="checkbox"] + label:after,
.form-group input[type="radio"] + label:before,
.form-group input[type="radio"] + label:after {
	-webkit-box-sizing: content-box;
	-moz-box-sizing: content-box;
	box-sizing: content-box;
	position: absolute;
	content: '';
	display: block;
	left: 0;
}

.form-group input[type="checkbox"] + label:before,
.form-group input[type="radio"] + label:before {
	top: 50%;
	width: 16px;
	height: 16px;
	margin-top: -10px;
	text-align: center;
}

.form-group input[type="checkbox"] + label:after,
.form-group input[type="radio"] + label:after {
	top: 50%;
	left: 2px;
	width: 16px;
	height: 16px;
	margin-top: -8px;
	-webkit-transform: scale(0);
	-moz-transform: scale(0);
	-ms-transform: scale(0);
	-o-transform: scale(0);
	transform: scale(0);
	-webkit-transform-origin: 50%;
	-moz-transform-origin: 50%;
	-ms-transform-origin: 50%;
	-o-transform-origin: 50%;
	transform-origin: 50%;
	-webkit-transition: -webkit-transform 200ms ease-out;
	transition: -webkit-transform 200ms ease-out;
	-o-transition: -o-transform 200ms ease-out;
	-moz-transition: transform 200ms ease-out, -moz-transform 200ms ease-out;
	transition: transform 200ms ease-out;
	transition: transform 200ms ease-out, -webkit-transform 200ms ease-out, -moz-transform 200ms ease-out, -o-transform 200ms ease-out;
}

.form-group input[type="checkbox"]:checked + label:after,
.form-group input[type="radio"]:checked + label:before {
	-webkit-animation: borderscale 300ms ease-in;
	-moz-animation: borderscale 300ms ease-in;
	animation: borderscale 300ms ease-in;
}

.form-group input[type="checkbox"]:checked + label:after,
.form-group input[type="radio"]:checked + label:after {
	-webkit-transform: scale(1);
	-moz-transform: scale(1);
	-ms-transform: scale(1);
	-o-transform: scale(1);
	transform: scale(1);
}

.form-group input[type="radio"] + label:before,
.form-group input[type="radio"] + label:after {
	border-radius: 50%;
}

.form-group input[type="checkbox"] + label:after {
	top: 50%;
	left: 2px;
	width: 16px;
	height: 16px;
	margin-top: -8px;
	-webkit-transition: none;
	-o-transition: none;
	-moz-transition: none;
	transition: none;
}

.form-control::-ms-expand {
	background-color: transparent;
	border: 0;
}

.form-control::-webkit-input-placeholder {
	opacity: 1;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control::-moz-placeholder {
	opacity: 1;
	line-height: 1.063rem;
	font-size: 1rem;
}

.form-control:-ms-input-placeholder {
	opacity: 1;
	line-height: 1.063rem;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control:-moz-placeholder {
	opacity: 1;
	line-height: 1.063rem;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control::-ms-input-placeholder {
	opacity: 1;
	line-height: 1.063rem;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control::placeholder {
	opacity: 1;
	line-height: 1.063rem;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control-textarea--base {
	display: block;
	width: 100%;
}

.form-control-textarea::-webkit-input-placeholder {
	opacity: 1;
	font-size: 1rem;
	padding-top: 15px;
}

.form-control-textarea::-moz-placeholder {
	opacity: 1;
	padding-top: 15px;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control-textarea:-ms-input-placeholder {
	opacity: 1;
	padding-top: 15px;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control-textarea:-moz-placeholder {
	opacity: 1;
	padding-top: 15px;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control-textarea::-ms-input-placeholder {
	opacity: 1;
	padding-top: 15px;
	font-size: 1rem;
	line-height: 1.063rem;
}

.form-control-textarea::placeholder {
	opacity: 1;
	padding-top: 15px;
	font-size: 1rem;
	line-height: 1.063rem;
}

.file-input {
	display: inline-block;
	position: relative;
}

.file-input > [type='file'] {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	opacity: 0;
	z-index: 10;
	cursor: pointer;
}

.file-input > .label {
	white-space: nowrap;
	opacity: 1;
}

.file-input.-chosen > .label {
	opacity: 1;
}

.custom-select {
	display: inline-block;
	max-width: 100%;
	vertical-align: middle;
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
	-webkit-box-shadow: none;
	box-shadow: none;
}

.custom-select:disabled {
	background-color: transparent;
}

.custom-select::-ms-expand {
	opacity: 0;
}

/*
*** Media Object Molecule
*/
.media-object--float {
	margin: 1rem 0;
}

.media-object--float img {
	position: relative;
	float: left;
	padding-top: 0;
	padding-right: 1.5rem;
	padding-left: 0rem;
	padding-bottom: 0.5rem;
	width: auto;
}

@media (min-width: 576px) {
	.media-object--float img {
		padding-right: 1.5rem;
	}
}

.media-object--float p {
	word-wrap: break-word;
}

.media-object {
	clear: left;
}

.media-object img {
	margin-bottom: 1rem;
}

.media-object .media-object-image--caption {
	font-style: italic;
	margin: 1rem 0;
}

.m-image-figure img {
	width: 100%;
}

.m-card-image {
	background-color: transparent !important;
}

/*
*** Alerts Molecules
*/
.m-alert {
	padding: 1rem;
	margin: 1rem 0;
}

/*
*** List Group Molecules
*/
.m-list-group {
	margin: 1rem 0;
}

.m-list-group .list-group-item {
	border-radius: 0;
	text-decoration: none;
	margin-bottom: 0.8rem;
}

.m-list-group .list-group-item:last-child {
	margin-bottom: 0 !important;
}

/*
*** Light Box Molecules
*/
.m-lightbox {
	margin: 2rem 0;
}

.m-lightbox img {
	width: 100%;
}

.m-lightbox a {
	margin: 0;
	padding: 0;
	text-decoration: none;
}

.m-lightbox ul {
	margin-left: -1rem;
	margin-right: -1rem;
	margin-top: 0;
	margin-bottom: 0;
	padding: 0;
}

.m-lightbox ul li {
	list-style: none;
	margin: 0;
	padding-left: 1px;
	margin-bottom: 1rem;
}

@media (min-width: 768px) {
	.m-lightbox ul li {
		margin-bottom: 0;
	}
}

.m-lightbox figcaption {
	padding: 1rem;
}

.m-lightbox figcaption p {
	font-style: italic;
	text-decoration: none;
	border-bottom: 0;
	margin-bottom: 0;
}

.slick-lightbox-close:before {
	content: "\f00d";
	font-family: "Font Awesome 5 Free";
	font-weight: 900;
}

/*
*** Scrollspy Molecules
*/
.m-scrollspy {
	padding: 1rem 0;
}

.m-scrollspy .list-group-item {
	text-decoration: none;
	padding: 1rem;
	border-radius: 0;
	font-size: 0.875rem;
	line-height: 1.125rem;
	text-transform: uppercase;
	font-weight: bold;
}

.scrollspy-content-container {
	padding: 1rem;
	margin-top: 1px;
	margin-left: 0px;
	height: auto;
	border-radius: 0;
}

@media (min-width: 768px) {
	.scrollspy-content-container {
		margin-left: -30px;
		margin-top: 0px;
	}
}

.scrollspy-content {
	height: 21.6vh;
	padding: 0;
	overflow-y: scroll;
	height: 18vh;
	border-radius: 0;
	padding: 0;
}

.scrollspy-content h6 {
	font-weight: bold;
}

.scrollspy-content p {
	margin-left: 8px;
}

.scrollspy-content::-webkit-scrollbar-track {
	-webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	border-radius: 10px;
}

.scrollspy-content::-webkit-scrollbar {
	width: 12px;
}

.scrollspy-content::-webkit-scrollbar-thumb {
	border-radius: 10px;
	-webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
}

/*
*** Tooltip molecules
*/
.tooltip.show {
	opacity: 1;
}

.tooltip {
	font-size: 0.563rem;
	line-height: 0.938rem;
	font-weight: bold;
	text-align: center;
	text-transform: uppercase;
	margin-top: -8px !important;
}

.tooltip-inner {
	border-radius: 0;
	padding: 0.5rem 1rem;
}

/*
*** Video Molecules
*/
.m-embed-video {
	margin: 1rem 0;
}

.jwplayer {
	width: 100% !important;
}

/*
*** Pagination Molecule
*/
.pagination {
	display: block;
}

@media (max-width: 767px) {
	.pagination {
		display: inline-block;
	}
	.pagination .page-link {
		padding: .5rem .7rem;
	}
}

.pagination .page-item {
	float: left;
}

@media (min-width: 576px) {
	.pagination {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
	}
	.pagination .page-item {
		float: none;
	}
}

.pagination .page-link {
	font-size: 0.875rem;
	line-height: 1rem;
	border: 1px solid transparent;
	border-radius: 0px !important;
	text-decoration: none;
}

.pagination .page-link:hover {
	text-decoration: underline;
}

.pagination .page-link:focus {
	background: transparent;
}

/* For Font Awesome 4 - fa.fa- */
.pagination span.fa.fa-angle-left, .pagination span.fa.fa-angle-right, .pagination span.fa.fa-angle-double-right, .pagination span.fa.fa-angle-double-left {
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	font-size: 1.2rem;
}

/* For Font Awesome 5 - fas.fa */
.pagination span.fas.fa-angle-left, .pagination span.fas.fa-angle-right, .pagination span.fas.fa-angle-double-right, .pagination span.fas.fa-angle-double-left {
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	font-size: 1.2rem;
}

.pagination-nav {
	margin: 1rem 0;
}

.page-link.active {
	text-decoration: underline;
}

/*
*** BROWSER UPDATE ALERT NOTIFICATION MOLECULE
* TO SEE THE NOTIFICATION EXAMPLE GO TO: www.websitename.com/#test-bu
*/
body .buorg {
	background-position: 8px 17px;
	position: absolute;
	position: fixed;
	z-index: 111111;
	width: 100%;
	bottom: 0px;
	left: 0px;
	border-bottom: 1px solid #333333;
	text-align: center;
	cursor: pointer;
	background-color: #14325f;
	color: #ffffff !important;
	font: 17px Calibri,Helvetica,Arial,sans-serif;
	-webkit-box-shadow: 0 0 5px rgba(0, 0, 0, 0.8);
	box-shadow: 0 0 5px rgba(0, 0, 0, 0.8);
}

body .buorg div a, .buorg div a:visited {
	text-indent: 0;
	color: #ffffff !important;
	text-decoration: none;
	-webkit-box-shadow: 0 0 2px rgba(0, 0, 0, 0.4);
	box-shadow: 0 0 2px rgba(0, 0, 0, 0.4);
	padding: 1px 10px;
	border-radius: 0px;
	font-weight: normal;
	text-transform: uppercase;
	background: #00CC36;
	white-space: nowrap;
	margin: 0 2px;
	display: inline-block;
}

body #buorgig {
	background-color: #dc3545;
}

body .buorg-fadeout {
	-webkit-transition: visibility 0s 5s, opacity 5s ease-out .5s;
	-o-transition: visibility 0s 5s, opacity 5s ease-out .5s;
	-moz-transition: visibility 0s 5s, opacity 5s ease-out .5s;
	transition: visibility 0s 5s, opacity 5s ease-out .5s;
}

/*
** Base Organism styles
*/
.o-cta-region {
	padding: 0 0 2rem 0;
}

.o-home-cards, .o-fast-facts {
	padding: 2rem;
}

/*
*** HEADER ORGANISM ***
*/
#skips-links {
	position: fixed;
	margin: 0rem;
	top: 0;
	padding: 20rem;
	z-index: 9999;
}

.skip {
	position: absolute;
	left: -99999px;
	top: 0;
}

#skips-links a {
	position: absolute;
	left: -99999px;
	top: 0px;
}

#skip-links a:focus, #skip-links a:active {
	position: fixed;
	left: 0;
	z-index: 9999;
	width: 100%;
	height: auto;
	margin: 0 auto;
	padding: 0.5rem;
	text-align: left;
	background: #ffffff;
	color: #14325f !important;
	text-decoration: none;
	font-weight: bold;
	font-family: inherit;
	font-size: 14px;
	-webkit-box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.15);
	box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.15);
}

.oualerts-is-active #skip-links a:focus, .oualerts-is-active #skip-links a:active {
	position: relative;
	padding: 1rem 0.5rem 1rem 0.5rem;
}

.oualerts-is-active header.desktop, .oualerts-is-active header.mobile {
	position: relative;
}

.oualerts-is-active .sm_menu_outer, .oualerts-is-active #searchbar {
	position: absolute;
	top: 60px;
}

.oualerts-is-active .home-page #main-content, .oualerts-is-active #main-content {
	margin-top: 0;
}


.oualerts-is-active .o-breadcrumb {
	margin-top: 0 !important;
}

.oualerts-is-active .nav-up, .oualerts-is-active .nav-down {
	top: 0 !important;
	-webkit-transition: none !important;
	-o-transition: none !important;
	-moz-transition: none !important;
	transition: none !important;
}

/*
** jQuery Accessible Mega Menu
*/
/* mega menu list */
.js-nav--menu {
	display: block;
	position: relative;
	list-style: none;
	z-index: 15;
}

/* a top level navigation item in the mega menu */
.js-nav--item {
	list-style: none;
	display: block;
}

.js-nav--item .open .nav-link-toplvl {
	background: #F6F6F6 !important;
	color: #14325f !important;
}

/* first descendant link within a top level navigation item */
.js-nav--item > a, .js-nav--item > .nav-link-toplvl--button.open {
	position: relative;
}

.js-nav--item > a.open, .js-nav--item > .nav-link-toplvl--button.open {
	background-color: #F6F6F6 !important;
	color: #14325f !important;
}

.js-nav--item > a.focus, .js-nav--item > .nav-link-toplvl--button.focus {
	background-color: #F6F6F6 !important;
	color: #14325f !important;
}

/* sub-navigation panel */
.js-sub--nav {
	position: absolute;
	display: none;
	background: #ffffff;
	top: 3em;
	padding: 1em 2em;
	width: 20em;
}

.hover, .focus {
	background: #F6F6F6 !important;
	color: #14325f !important;
}

/* sub-navigation panel open state */
.js-sub--nav.open {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	-webkit-box-shadow: 0 13px 9px rgba(20, 50, 95, 0.5);
	box-shadow: 0 13px 9px rgba(20, 50, 95, 0.5);
}

.js-sub--nav ul {
	vertical-align: top;
}

.js-sub--nav li {
	list-style-type: none;
}

.nav-link-toplvl--button {
	background: none;
	border: 0px !important;
	font-size: 0.8rem;
	line-height: 1.2;
	font-weight: normal;
}

@media screen and (min-width: 770px) and (max-width: 911px) {
	#main-nav .nav-link {
		font-size: 12px;
	}
}

@media screen and (min-width: 911px) and (max-width: 991px) {
	#main-nav .nav-link {
		font-size: 16px;
	}
}

@media screen and (min-width: 770px) and (max-width: 991px) {
	.navbar-expand-md .navbar-nav .nav-link {
		padding-right: 8px;
		padding-left: 0;
	}
	.no-padding--tablet {
		padding-left: 0px;
		padding-right: 0px;
	}
}

@media (max-width: 871px) {
	.hide--tablet {
		display: none !important;
	}
}

@media (min-width: 876px) {
	.hide--desktop {
		display: none !important;
	}
}

/**
* Main Body Styles
*/
@media (min-width: 770px) and (max-width: 991px) {
	.home-page main {
		margin-top: 116px;
	}
	.nav-up {
		top: -116px !important;
	}
	.o-breadcrumb {
		margin-top: 116px;
	}
}

header.desktop {
	display: none;
	position: fixed;
	z-index: 1000;
	right: 0;
	left: 0;
	padding: 0;
	margin-top: -1rem;
	-webkit-transition: top 0.2s ease-in-out;
	-o-transition: top 0.2s ease-in-out;
	-moz-transition: top 0.2s ease-in-out;
	transition: top 0.2s ease-in-out;
	background: #14325f;
}

header.desktop .two-column-links {
	-webkit-column-count: 2;
	-moz-column-count: 2;
	column-count: 2;
}

header.desktop .form-control::-webkit-input-placeholder {
	opacity: 1;
	font-size: 14px;
}

header.desktop .form-control::-moz-placeholder {
	font-size: 14px;
}

header.desktop .form-control:-ms-input-placeholder {
	font-size: 14px;
}

header.desktop .form-control:-moz-placeholder {
	font-size: 14px;
}

header.desktop .form-control::-ms-input-placeholder {
	font-size: 14px;
}

header.desktop .form-control::placeholder {
	font-size: 14px;
}

header.desktop .a-button--primary-trans {
	border: 1px solid #14325f;
	background: transparent;
	color: #14325f;
	font-weight: bold !important;
	text-align: center !important;
}

header.desktop .a-button--primary-trans:hover {
	background: #14325f !important;
	color: #ffffff !important;
	text-decoration: none !important;
}

header.desktop .a-button--primary-trans:focus {
	background: #14325f !important;
	color: #ffffff !important;
	text-decoration: none !important;
}

@media (min-width: 768px) {
	header.desktop {
		padding: 0;
		margin-top: 0;
		background: #14325f;
	}
}

header.desktop h2, header.desktop h3, header.desktop h4, header.desktop h5, header.desktop h6 {
	color: #14325f;
	border-bottom: 1px solid #14325f !important;
}

header.desktop ul {
	margin-left: 0;
}

header.desktop .border-right--white:after {
	content: '';
	display: inline-block;
	position: absolute;
	width: 1px;
	height: 25px;
	margin: -5px 9px;
	background: #ffffff;
}

header.desktop .dropdown-ul {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
	margin: 0;
}

header.desktop .dropdown-ul li {
	list-style: none;
}

header.desktop #gateway-nav .dropdownli.hover .m-gateway-nav-submenu {
	display: -webkit-box !important;
	display: -webkit-flex !important;
	display: -moz-box !important;
	display: -ms-flexbox !important;
	display: flex !important;
	z-index: 1000;
}

header.desktop #gateway-nav .dropdownli.hover .m-gateway-nav-submenu,
header.desktop #gateway-nav .dropdownli.hover .m-gateway-nav-submenu,
header.desktop #gateway-nav .dropdownli.hover:focus .m-gateway-nav-submenu,
header.desktop #gateway-nav .dropdownli.hover:active .m-gateway-nav-submenu {
	opacity: 1;
}

header.desktop #gateway-nav .dropdownli.hover .m-gateway-nav-submenu a,
header.desktop #gateway-nav .dropdownli.hover .m-gateway-nav-submenu a,
header.desktop #gateway-nav .dropdownli.hover:focus .m-gateway-nav-submenu a,
header.desktop #gateway-nav .dropdownli.hover:active .m-gateway-nav-submenu a {
	color: #14325f;
}

header.desktop .droplink:hover {
	background: #F6F6F6;
}

header.desktop .focus--background.hover {
	background: #F6F6F6;
}

header.desktop .focus--background.hover .nav-link-toplvl, header.desktop .focus--background.hover .nav-link-toplvl--button {
	color: #14325f !important;
}

header.desktop .hover-link {
	background: #F6F6F6 !important;
	color: #14325f !important;
}

header.desktop .navbar {
	width: 100%;
	position: relative;
}

header.desktop .navbar-collapse {
	width: 100%;
	margin-left: 0;
}

@media (min-width: 768px) {
	header.desktop .navbar-collapse {
		width: auto;
		margin-left: auto;
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-webkit-flex-direction: column;
		-moz-box-orient: vertical;
		-moz-box-direction: normal;
		-ms-flex-direction: column;
		flex-direction: column;
		-webkit-box-pack: center;
		-webkit-justify-content: center;
		-moz-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
	}
}

@media (min-width: 992px) {
	header.desktop .navbar-collapse {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-orient: horizontal;
		-webkit-box-direction: normal;
		-webkit-flex-direction: row;
		-moz-box-orient: horizontal;
		-moz-box-direction: normal;
		-ms-flex-direction: row;
		flex-direction: row;
		-webkit-box-pack: center;
		-webkit-justify-content: center;
		-moz-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
	}
}

header.desktop #global-search::-webkit-input-placeholder {
	color: #282828;
}

header.desktop #global-search::-moz-placeholder {
	color: #282828;
}

header.desktop #global-search:-ms-input-placeholder {
	color: #282828;
}

header.desktop #global-search:-moz-placeholder {
	color: #282828;
}

header.desktop #global-search::-ms-input-placeholder {
	color: #282828;
}

header.desktop #global-search::placeholder {
	color: #282828;
}

header.desktop .form-inline {
	background: #ffffff;
	display: inline;
}

@media (min-width: 768px) {
	header.desktop .form-inline {
		background: transparent;
	}
}

header.desktop .form-inline .search-form-control {
	background: #ffffff;
	border: 1px solid #ffffff;
	border-radius: 0;
	padding: 0.375rem 0.75rem;
	font-size: 14px;
	margin-left: -28px;
	margin-right: 0px !important;
	width: -webkit-calc(100% - 17px);
	width: -moz-calc(100% - 17px);
	width: calc(100% - 17px);
	line-height: 1.3;
	font-weight: 400;
	color: #000000;
}

header.desktop .form-inline .search-form-control:placeholder {
	color: #282828;
	font-size: 14px;
	font-style: italic;
	width: 100%;
}

header.desktop .form-inline .button--toggle {
	width: auto;
	color: #ffffff;
	border: 1px solid #0054A0;
	padding: 12px 20px;
	background: #0054A0;
	margin-left: -12px;
	-webkit-transform-origin: none;
	-moz-transform-origin: none;
	-ms-transform-origin: none;
	-o-transform-origin: none;
	transform-origin: none;
	-webkit-transform: none;
	-moz-transform: none;
	-ms-transform: none;
	-o-transform: none;
	transform: none;
	-webkit-transition: none;
	-o-transition: none;
	-moz-transition: none;
	transition: none;
	border-radius: 0;
}

@media (min-width: 768px) {
	header.desktop .form-inline .button--toggle {
		padding: 0.3rem 0.5rem 0.3rem 0.5rem;
		position: absolute;
		margin: 0;
		right: 25px;
		top: 0px;
		height: 32px;
	}
}

header.desktop .form-inline .button--toggle .fa {
	color: #ffffff;
	-webkit-transition: none;
	-o-transition: none;
	-moz-transition: none;
	transition: none;
	font-size: 18px;
	-webkit-transform: translate(0, 0);
	-moz-transform: translate(0, 0);
	-ms-transform: translate(0, 0);
	-o-transform: translate(0, 0);
	transform: translate(0, 0);
}

header.desktop .form-inline .button--toggle:hover {
	cursor: pointer;
}

header.desktop .form-inline .button--toggle:hover:before {
	-webkit-transform: none;
	-moz-transform: none;
	-ms-transform: none;
	-o-transform: none;
	transform: none;
	-webkit-transform-origin: none;
	-moz-transform-origin: none;
	-ms-transform-origin: none;
	-o-transform-origin: none;
	transform-origin: none;
	fill: transparent;
}

header.desktop .form-inline .button--toggle:active {
	background: #0054A0;
	border: 1px solid transparent;
}

header.desktop .m-right-nav {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

header.desktop #utilities-dropdown .nav-link-toplvl--button:after {
	display: inline;
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f107";
	padding-left: 5px;
}

header.desktop #utilities-dropdown:after {
	content: "";
	width: 1px;
	height: 26px;
	position: relative;
	left: 0;
	top: 11px;
	background: #ffffff;
}

header.desktop .no-padding {
	padding: 0 !important;
}

header.desktop #tablet-nav, header.desktop #desktop-nav {
	display: none;
}

header.desktop .nav-theme-toggles--tablet, header.desktop .nav-theme-toggles--desktop {
	display: none;
}

@media screen and (max-width: 1309px) {
	header.desktop #tablet-nav {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
	}
	header.desktop .nav-theme-toggles--tablet {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
	}
}

@media screen and (min-width: 1310px) {
	header.desktop #utilities-dropdown {
		display: none !important;
	}
	header.desktop #desktop-nav {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-orient: vertical;
		-webkit-box-direction: normal;
		-webkit-flex-direction: column;
		-moz-box-orient: vertical;
		-moz-box-direction: normal;
		-ms-flex-direction: column;
		flex-direction: column;
		-webkit-box-pack: center;
		-webkit-justify-content: center;
		-moz-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
		-webkit-box-align: center;
		-webkit-align-items: center;
		-moz-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		-webkit-align-content: center;
		-ms-flex-line-pack: center;
		align-content: center;
		margin-bottom: -1px;
	}
	header.desktop .nav-theme-toggles--desktop {
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
	}
}

@media screen and (min-width: 770px) and (max-width: 1309px) {
	header.desktop .is-in-utility--dropdown {
		display: none !important;
	}
	header.desktop #utilities-dropdown {
		display: block;
	}
}

@media screen and (max-width: 875px) {
	header.desktop .is-in-utility-dropdown--tablet {
		display: none;
	}
	header.desktop .m-gateway-nav-submenu.is-in-utility-dropdown--tablet {
		display: none !important;
	}
}

header.desktop #global-search {
	display: none;
}

header.desktop #global-search-submit {
	display: none;
	top: 7.9px;
	border: 2px solid #0054A0;
}

header.desktop #global-search-form {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-transition: opacity 0.2s ease;
	-o-transition: opacity 0.2s ease;
	-moz-transition: opacity 0.2s ease;
	transition: opacity 0.2s ease;
	width: 100%;
}

header.desktop #global-search-toggle {
	border: 1px solid transparent;
	border-radius: 0;
	position: absolute;
	background: transparent !important;
	right: 0;
	top: 12px;
	padding-right: 0px;
	padding-left: 1px;
	padding-bottom: 0px;
	padding-top: 0px;
}

header.desktop #global-search-toggle:hover {
	background: transparent;
	cursor: pointer;
}

header.desktop #toggle-icon {
	color: #ffffff;
	font-size: 20px;
}

header.desktop .nav-theme-toggles--tablet, header.desktop .nav-theme-toggles--desktop {
	margin-top: 12px;
	margin-bottom: 12px;
}

header.desktop .a-theme-toggles {
	margin: 0 30px;
}

@media (min-width: 770px) {
	header.desktop {
		display: block;
	}
}

#main-nav-form-container {
	border-top: 1px solid #EFEFEF;
	display: none;
}

@media (min-width: 768px) {
	#main-nav-form-container {
		border-top: 0;
		display: -webkit-box;
		display: -webkit-flex;
		display: -moz-box;
		display: -ms-flexbox;
		display: flex;
	}
}

.navbar-toggler {
	padding: 0.25rem 0.75rem 0.5rem;
	display: block;
	z-index: 999;
	cursor: pointer;
}

@media (min-width: 768px) {
	.navbar-toggler {
		display: none;
	}
}

.navbar-toggler span {
	color: #ffffff;
}

.navbar-toggler-icon {
	padding: 1rem 0;
}

#gateway-nav, #main-nav {
	position: relative;
}

#gateway-nav a, #main-nav a {
	font-weight: 400;
	text-decoration: none;
}

#gateway-nav a:hover, #main-nav a:hover {
	text-decoration: underline;
}

#gateway-nav {
	z-index: 1000;
	background: transparent;
}

#gateway-nav .navbar-nav-container {
	margin-bottom: -8px !important;
}

#gateway-nav .navbar {
	padding-top: .125rem !important;
}

@media (min-width: 768px) {
	#gateway-nav {
		background: transparent;
		margin-bottom: 0;
		margin-left: -8px;
	}
}

#gateway-nav .nav-link-toplvl, #gateway-nav .nav-link-toplvl--button {
	color: #ffffff;
	text-align: left;
	padding: 1rem 10px;
}

#gateway-nav .nav-link-toplvl:hover, #gateway-nav .nav-link-toplvl--button:hover {
	text-decoration: none;
}

@media (min-width: 768px) {
	#gateway-nav a {
		font-size: 0.8rem;
		line-height: 1.2;
	}
}

#gateway-nav .navbar-nav {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	padding-top: 1px;
}

#gateway-nav .dropdownli {
	position: relative;
	display: inline-block;
}

#gateway-nav .dropdownli:hover {
	background: #F6F6F6;
}

#gateway-nav .dropdownli:hover a {
	color: #14325f;
}

#gateway-nav .dropdownli:hover .m-gateway-nav-submenu {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	z-index: 1000;
	-webkit-transition: display 0.2s linear;
	-o-transition: display 0.2s linear;
	-moz-transition: display 0.2s linear;
	transition: display 0.2s linear;
}

#main-nav {
	padding: 0.5rem 0;
	background: #ffffff;
	border-top: 0;
	-webkit-box-ordinal-group: 2;
	-webkit-order: 1;
	-moz-box-ordinal-group: 2;
	-ms-flex-order: 1;
	order: 1;
	z-index: 999;
	-webkit-box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.15);
	box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.15);
}

@media (min-width: 768px) {
	#main-nav {
		-webkit-box-ordinal-group: 3;
		-webkit-order: 2;
		-moz-box-ordinal-group: 3;
		-ms-flex-order: 2;
		order: 2;
		border-top: 1px solid #ffffff;
	}
}

#main-nav .nav-link {
	display: inline-block;
	position: relative;
	color: #14325f;
	line-height: 1rem;
	font-weight: bold;
	text-align: center;
}

#main-nav .nav-link:hover {
	text-decoration: underline;
	-webkit-text-decoration-color: #CF4B06;
	-moz-text-decoration-color: #CF4B06;
	text-decoration-color: #CF4B06;
}

#main-nav .navbar-brand {
	position: relative;
	z-index: 999;
	white-space: nowrap;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
}

@media (min-width: 768px) {
	#main-nav .navbar-brand {
		margin-left: -4px;
	}
}

#main-nav .navbar-brand img {
	display: block;
}

#main-nav .navbar-brand:hover {
	cursor: pointer;
	border-bottom: 0;
}

@media all and (min-width: 1082px) {
	#main-nav .navbar-nav li {
		width: auto;
	}
}

#main-nav .navbar-nav {
	margin-top: 0;
	-webkit-box-pack: end;
	-webkit-justify-content: flex-end;
	-moz-box-pack: end;
	-ms-flex-pack: end;
	justify-content: flex-end;
}

#main-nav .navbar-nav li {
	border-bottom: 1px solid #d8d8d8;
}

@media (min-width: 768px) {
	#main-nav .navbar-nav li {
		border-bottom: 1px solid transparent;
	}
}

#main-nav .navbar-nav li:last-child {
	border-bottom: 0;
}

#main-nav .collapse {
	margin: 0;
	width: 100%;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
}

@media (min-width: 768px) {
	#main-nav .collapse {
		margin: 0 auto;
		width: auto;
	}
}

.sub-nav-group {
	display: none;
	position: absolute;
	min-width: 20rem;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	-webkit-align-content: center;
	-ms-flex-line-pack: center;
	align-content: center;
	padding: 1rem 1.5rem;
	background: #F6F6F6;
}

.sub-nav-group h2 {
	font-size: 12px;
	text-align: left;
}

.sub-nav-group li {
	list-style: none;
	padding: 0.5rem 0;
}

.sub-nav-group li a {
	font-size: 0.56rem;
	line-height: 0.875rem;
	text-align: left;
	color: #14325f;
}

.sub-nav-group ul {
	padding: 0;
	min-width: 100%;
}

.a-theme-toggles {
	display: inherit;
	margin-right: 0 !important;
}

.a-vertical-line {
	color: #ffffff;
	padding-left: 0.38em;
	padding-right: 0.38em;
}

.a-vertical-line:after {
	content: '';
	border: 0.5px solid #ffffff;
	height: 24px;
	margin-left: 1.5px;
	margin-right: 1.5px;
	display: block;
}

.a-theme-toggles {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	-webkit-box-align: center;
	-webkit-align-items: center;
	-moz-box-align: center;
	-ms-flex-align: center;
	align-items: center;
}

#sun-button, #moon-button, #tablet-sun-button, #tablet-moon-button {
	width: 100%;
}

#sun-button, #tablet-sun-button {
	background-image: url("/_resources/img/sun.svg");
	padding: 0.6rem;
}

#moon-button, #tablet-moon-button {
	background-image: url("/_resources/img/moon.svg");
	padding: 0.6rem;
}

.m-theme-toggle {
	background-color: transparent;
	background-size: contain;
	background-position: center;
	background-repeat: no-repeat;
	border: 2px solid transparent;
}

.m-theme-toggle:hover {
	cursor: pointer;
}

.marketing-page header.desktop {
	display: block;
	background: transparent;
	margin-top: 0rem;
}

.marketing-page .o-breadcrumb {
	margin-top: 69px;
}

.nav-up {
	top: -144px;
}

.nav-down {
	top: 0px;
}

/* .o-hero-image {
margin-top: 100px;
} */

@media (max-width: 768px) {
	.o-hero-image {
		margin-top:0px;
	}
}

.o-hero-image .slick-prev.slick-arrow, .o-hero-image .slick-next.slick-arrow {
	display: block;
	font-size: 1rem;
	line-height: 0;
	position: absolute;
	top: 50%;
	display: block;
	width: auto;
	height: auto;
	padding: 0;
	-webkit-transform: translate(0, -50%);
	-moz-transform: translate(0, -50%);
	-ms-transform: translate(0, -50%);
	-o-transform: translate(0, -50%);
	transform: translate(0, -50%);
	cursor: pointer;
	color: transparent;
	border: none;
	outline: none;
	background: transparent;
	z-index: 5;
}

.o-hero-image .slick-prev.slick-arrow {
	left: 1rem;
}

.o-hero-image .slick-next.slick-arrow {
	right: 0;
}

@media (min-width: 768px) {
	.o-hero-image button.slick-prev.slick-arrow, .o-hero-image .slick-next.slick-arrow {
		display: none !important;
	}
}

/*
*** Home Tabs to Accordion Organisms
*/
.o-tabs-accordion {
	margin: 0 auto;
	padding: 0;
}

.o-tabs-accordion .has-border {
	margin-bottom: 16px;
	padding-bottom: 2px;
}

.o-tabs-accordion .ui-tabs-nav li:last-child {
	border-right: 0;
}

.o-tabs-accordion .ui-tabs-tab {
	list-style: none;
	text-align: center;
	margin: 0;
	padding: 0;
	border: 0;
	width: 100%;
}

.o-tabs-accordion .ui-tabs-tab a {
	display: block;
	padding: 1.5rem;
	width: 100%;
	text-decoration: none;
	font-weight: bold;
}

.o-tabs-accordion .ui-tabs-panel {
	padding: 2rem;
}

@media (min-width: 992px) {
	.o-tabs-accordion .ui-tabs-panel {
		padding: 4rem;
	}
}

.o-tabs-accordion .ui-tabs-active {
	margin-bottom: 0px !important;
	padding-bottom: 0px !important;
	font-weight: bold;
}

.o-tabs-accordion .a-date-month {
	top: 0;
	padding-top: 0;
	padding-bottom: 0;
}

.o-tabs-accordion .ui-tabs-nav {
	position: relative;
	margin: 0 auto;
	padding: 0;
	clear: both;
}

.o-tabs-accordion .ui-tabs-nav .ui-tabs-anchor {
	padding: 1.5rem;
	text-align: center;
	text-transform: capitalize;
	font-weight: bold;
	text-decoration: none;
	margin: 0;
	width: 100%;
}

.o-tabs-accordion .ui-tabs-nav li {
	display: inline;
	float: left;
	width: 25%;
	padding: 0;
	margin: 0;
}

.tabs-panels {
	clear: both;
	width: 100%;
}

/*
*** Home Tabs to Accordion Custom Theme
*/
.o-tabs-accordion--custom .state-has-border--right {
	border-right: 0;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .state-has-border--right {
		border-right: 1px solid #ffffff;
	}
}

.o-tabs-accordion--custom .has-border {
	border-bottom: 1px solid #ffffff !important;
}

.o-tabs-accordion--custom .ui-tabs-tab .ui-tabs-anchor {
	background: #EFEFEF;
	color: #282828;
	border: 1px solid transparent;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .ui-tabs-tab .ui-tabs-anchor {
		border: 1px solid transparent;
	}
}

.o-tabs-accordion--custom .ui-tabs-tab .ui-tabs-anchor:hover {
	background: #14325f;
	color: #ffffff;
	border: 1px solid transparent;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .ui-tabs-tab .ui-tabs-anchor:hover {
		border: 1px solid transparent;
	}
}

.o-tabs-accordion--custom .ui-tabs-tab {
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent;
	border-bottom: 1px solid #282828;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .ui-tabs-tab {
		border-right: 1px solid #282828;
		border-bottom: 0px;
	}
}

.o-tabs-accordion--custom .ui-tabs-active .ui-tabs-anchor {
	background: #14325f;
	border: 1px solid transparent;
	color: #ffffff;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .ui-tabs-active .ui-tabs-anchor {
		border: 1px solid #14325f;
	}
}

.o-tabs-accordion--custom .ui-tabs-active {
	border: 1px solid #14325f;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .ui-tabs-active {
		border: 1px solid #14325f;
	}
}

.o-tabs-accordion--custom .ui-state-hover {
	border: 1px solid #14325f;
}

@media (min-width: 768px) {
	.o-tabs-accordion--custom .ui-state-hover {
		border: 1px solid #14325f;
	}
}

.o-tabs-accordion--custom .ui-tabs-panel h2, .o-tabs-accordion--custom h3, .o-tabs-accordion--custom h4, .o-tabs-accordion--custom h5, .o-tabs-accordion--custom h6, .o-tabs-accordion--custom .ui-tabs-panel p, .o-tabs-accordion--custom .ui-tabs-panel ul li, .o-tabs-accordion--custom .ui-tabs-panel ul li a {
	color: #ffffff !important;
}

.o-tabs-accordion--custom .m-card h2, .o-tabs-accordion--custom .m-card h3, .o-tabs-accordion--custom .m-card h4, .o-tabs-accordion--custom .m-card h5, .o-tabs-accordion--custom .m-card h6 {
	color: #14325f !important;
}

.o-tabs-accordion--custom .m-card p {
	color: #282828 !important;
}

.o-tabs-accordion--custom .m-card--vertical, .o-tabs-accordion--custom .m-card--horizontal {
	background: #F6F6F6 !important;
}

.o-tabs-accordion--custom .m-card--vertical .m-card-content .a-button--primary-trans-alt, .o-tabs-accordion--custom .m-card--horizontal .m-card-content .a-button--primary-trans-alt {
	background: transparent !important;
	border: 1px solid #14325f !important;
	color: #282828;
}

.o-tabs-accordion--custom .m-card--vertical .m-card-content .a-button--primary-trans-alt:hover, .o-tabs-accordion--custom .m-card--horizontal .m-card-content .a-button--primary-trans-alt:hover {
	background: #14325f !important;
	color: #ffffff;
}

.o-tabs-accordion--custom .m-events .a-date-number {
	color: #ffffff;
}

.o-tabs-accordion--custom .ui-tabs-tab a:active {
	border: 0;
	outline: 0;
	-webkit-box-shadow: none;
	box-shadow: none;
}

.o-gateway-tabs {
	padding-bottom: 0;
}

@media (min-width: 992px) {
	.o-gateway-tabs {
		padding-bottom: 8rem;
	}
}

.o-gateway-tabs .m-card {
	margin-bottom: 1rem;
}

.o-gateway-tabs .m-card-content {
	padding: 1rem 3rem 1rem 3rem;
}

/*
** Home Cta Section Organism
*/
.o-cta-region .home-cta-base--layout {
	border-bottom: 5px solid transparent;
}

.o-cta-region .m-cta {
	padding: 3rem 0;
}

#cta-region .home-cta-base--layout:hover {
	border-bottom: 5px solid #00CC36;
}

#home-cards .a-base-button {
	width: 50%;
	margin: 2rem auto;
}

/*
** Home Cards Organism
*/
.o-home-cards .a-button--outline {
	width: 50%;
	margin: 0 auto;
	margin-top: 1rem;
}

@media (min-width: 768px) {
	.o-home-cards .a-button--outline {
		display: none;
	}
}

/*
** Fast Facts Organism
*/
.o-fast-facts .slick-prev:before, .o-fast-facts .slick-next:before {
	color: #9b9b9b;
}

.o-fast-facts .slick-next {
	right: 0;
}

.o-fast-facts .a-fact {
	font-size: 3rem;
}

@media (min-width: 768px) {
	.o-fast-facts .a-fact {
		font-size: 5rem;
	}
}

/*
** Events Organism
*/
.o-calendar {
	padding: 3rem 2rem;
}

.o-calendar a {
	text-decoration: none;
}

.o-calendar .a-base-button {
	width: 50%;
	margin-top: 2rem;
	margin-left: auto;
	margin-right: auto;
}

.o-calendar .a-date-month {
	font-size: 0.938rem;
	line-height: 1.25;
}

.o-calendar .a-date-number {
	font-size: 2.063rem;
	line-height: 2.375rem;
}

.o-calendar .prev, .o-calendar .next {
	color: #ffffff;
	position: absolute;
	cursor: pointer;
	z-index: 2;
	font-weight: bold;
	font-size: 3rem;
	padding: 1rem 1.5rem;
	bottom: 0;
}

.o-calendar .prev:before, .o-calendar .next:before {
	position: absolute;
	top: 0;
	right: 0;
	width: 100%;
	height: 100%;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-align: center;
	-webkit-align-items: center;
	-moz-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

.o-calendar .prev {
	left: -2rem;
	top: -15.5px;
}

.o-calendar .next {
	right: -2rem;
	top: -15.5px;
}

.o-calendar .m-card--vertical .a-fullwidth-bg-image {
	padding: 8rem 0;
}

@media (min-width: 576px) {
	.o-calendar .m-card--vertical .a-fullwidth-bg-image {
		padding: 10rem 0;
	}
}

@media (min-width: 576px) and (max-width: 991px) {
	.o-calendar .m-card--vertical .a-fullwidth-bg-image {
		padding: 15rem 0;
	}
}

.o-calendar.state-hasBgImage--blue {
	/*
	*** Home Page Events - What's Happening At WVC Color Overlay Styles - Localist Calendar
	*/
}

.o-calendar.state-hasBgImage--blue h2, .o-calendar.state-hasBgImage--blue h3, .o-calendar.state-hasBgImage--blue h4, .o-calendar.state-hasBgImage--blue h5, .o-calendar.state-hasBgImage--blue h6 {
	color: #ffffff;
	border-bottom: 1px solid #ffffff;
}

.o-calendar.state-hasBgImage--blue .a-base-button {
	background: #ffffff;
	color: #14325f;
}

.o-calendar.state-hasBgImage--blue .a-base-button:hover {
	background: #14325f;
	color: #ffffff;
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-card {
	background: #F6F6F6;
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-card p {
	font-size: 0.875rem;
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-card:hover, .o-calendar.state-hasBgImage--blue .localist-widget-hl .event-card:active {
	border-bottom: 4px solid #00CC36;
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-details {
	background: rgba(20, 50, 95, 0.8);
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-list .event-overview .content {
	border: 1px solid #F6F6F6;
	background: #F6F6F6;
}

.o-calendar.state-hasBgImage--blue .event-details dd {
	color: #ffffff;
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-card .content p {
	color: #282828;
}

.o-calendar.state-hasBgImage--blue .localist-widget-hl .event-card .content:before {
	background: #F6F6F6;
}

.o-calendar--custom .prev:before, .o-calendar--custom .next:before {
	color: #ffffff !important;
}

/*
** Events Organism
*/
.o-events {
	padding: 3rem 2rem;
}

.localist-widget-hl ol {
	margin: 0;
	padding: 0;
	list-style: none;
	font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

/*  Hide LI items for Omni Calendar feed - 2023-10-31 */
.event-list li:nth-of-type(1n+11) {
  display: none;
}

.localist-widget-hl .event-list {
	clear: both;
	position: relative;
	-webkit-transition: opacity .10s ease-out,left .5s ease-out;
	-moz-transition: opacity .10s ease-out,left .5s ease-out;
	-o-transition: opacity .10s ease-out,left .5s ease-out;
	transition: opacity .10s ease-out,left .5s ease-out;
}

.localist-widget-hl li.event {
	-webkit-transition: opacity .10s .10s ease-out,-webkit-transform .10s .10s ease-out,visibility .10s .10s ease-out;
	-moz-transition: opacity .10s .10s ease-out,-moz-transform .10s .10s ease-out,visibility .10s .10s ease-out;
	-webkit-transition: opacity .10s .10s ease-out,visibility .10s .10s ease-out,-webkit-transform .10s .10s ease-out;
	transition: opacity .10s .10s ease-out,visibility .10s .10s ease-out,-webkit-transform .10s .10s ease-out;
	-o-transition: opacity .10s .10s ease-out,visibility .10s .10s ease-out,-o-transform .10s .10s ease-out;
	-moz-transition: opacity .10s .10s ease-out,transform .10s .10s ease-out,visibility .10s .10s ease-out,-moz-transform .10s .10s ease-out;
	transition: opacity .10s .10s ease-out,transform .10s .10s ease-out,visibility .10s .10s ease-out;
	transition: opacity .10s .10s ease-out,transform .10s .10s ease-out,visibility .10s .10s ease-out,-webkit-transform .10s .10s ease-out,-moz-transform .10s .10s ease-out,-o-transform .10s .10s ease-out;
}

.localist-widget-hl .event-list li {
	margin-bottom: 20px;
}

.localist-widget-hl .event-card {
	display: block;
	overflow: hidden;
	margin-bottom: 25px;
	padding: 0;
	position: relative;
	background: #fff;
	border: px solid #ffffff;
	color: #989694;
	font-size: .8125rem;
}

.localist-widget-hl .event-overview {
	-webkit-transition: all .10s ease-out;
	-moz-transition: all .10s ease-out;
	-o-transition: all .10s ease-out;
	transition: all .10s ease-out;
}

.localist-widget-hl .event-details {
	background: rgba(84, 130, 171, 0.8);
	color: #fff;
	width: 100%;
	height: 100%;
	left: 0;
	opacity: 0;
	padding: 20px;
	position: absolute;
	top: 0;
	visibility: hidden;
	-webkit-transition: all .10s ease-out;
	-moz-transition: all .10s ease-out;
	-o-transition: all .10s ease-out;
	transition: all .10s ease-out;
}

.localist-widget-hl dl {
	border: 0;
	font-family: inherit;
	font-size: 100%;
	font-style: inherit;
	font-weight: inherit;
	margin: 0;
	outline: 0;
	padding: 0;
	vertical-align: baseline;
}

.localist-widget-hl .event-specs dt {
	background-position: center;
	background-repeat: no-repeat;
	clear: both;
	margin-right: 15px;
	overflow: hidden;
	text-indent: -9999px;
	width: 40px;
	float: left;
}

.localist-widget-hl .event-specs dt, .event-specs dd {
	padding: 14px 0 17px;
}

.localist-widget-hl .event-specs dd {
	border-top: 1px solid #ffffff;
	position: relative;
	margin: 0;
	padding-left: 55px;
}

.localist-widget-hl .event-detail-title {
	display: block;
	line-height: 1.1875em;
	margin-bottom: 1.5em;
	font-size: 13px;
}

.localist-widget-hl .event-specs dd:before {
	position: absolute;
	top: 0;
	left: 40px;
	width: 1px;
	height: 100%;
	background: rgba(255, 255, 255, 0.15);
	content: '';
}

.localist-widget-hl strong {
	font-weight: 700;
}

.localist-widget-hl .event-specs {
	border-bottom: 1px solid #ffffff;
	border-width: 1px 0;
	line-height: normal;
	overflow: hidden;
}

.localist-widget-hl .cover {
	height: 100%;
	left: 0;
	position: absolute;
	text-indent: -9999px;
	top: 0;
	width: 100%;
}

.localist-widget-hl .event-card header {
	overflow: hidden;
	position: relative;
	height: 13.538em;
}

.localist-widget-hl .event-card:hover .event-details {
	opacity: 1;
	visibility: visible;
}

.localist-widget-hl .event-list .event-overview .content {
	height: 7.615384615em;
	border: 1px solid #ffffff;
	border-width: 0 1px;
	padding: 23px 20px 19px;
}

.localist-widget-hl .event-card:hover .event-title, .localist-widget-hl .event-card:hover .event-short-date, .localist-widget-hl .event-card:hover .content:before {
	opacity: 0;
	text-decoration: none;
	visibility: hidden;
}

.localist-widget-hl .event-card .content:before {
	background: #fff;
	bottom: 0;
	content: '';
	height: 17px;
	left: 1px;
	position: absolute;
	right: 1px;
}

.localist-widget-hl .event-card:hover .event-title, .localist-widget-hl .event-card:hover .event--date, .localist-widget-hl .event-card:hover .content:before {
	opacity: 0;
	text-decoration: none;
	visibility: hidden;
}

.localist-widget-hl .event-card .content p {
	overflow: hidden;
	margin: 0;
	display: -webkit-box;
	-o-text-overflow: ellipsis;
	text-overflow: ellipsis;
	-webkit-line-clamp: 3;
	-webkit-box-orient: vertical;
	-moz-box-orient: vertical;
	box-orient: vertical;
	line-height: 1.5em;
	font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
	color: #414141;
}

.localist-widget-hl .event-title {
	background: rgba(0, 0, 0, 0.5) left top;
	bottom: 0;
	color: #fff;
	font-weight: 800;
	left: 0;
	overflow: hidden;
	padding: 7px 20px 5px;
	position: absolute;
	-o-text-overflow: ellipsis;
	text-overflow: ellipsis;
	width: 100%;
	white-space: nowrap;
	z-index: 1;
	line-height: 1.875rem;
	font-size: .8125rem;
	font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
	margin: 0;
	outline: 0;
	vertical-align: baseline;
	border: 0;
	-webkit-transition: all .10s ease-out;
	-moz-transition: all .10s ease-out;
	-o-transition: all .10s ease-out;
	transition: all .10s ease-out;
}

.localist-widget-hl .event-short-date {
	background: #CF4B06;
	position: absolute;
	width: 4em;
	height: 4em;
	top: 0;
	left: 0;
	z-index: 1;
	padding: .333333333em 0 0;
	color: #fff;
	font-weight: 500 !important;
	font-size: 20px;
	line-height: 1.111111111em;
	font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
	text-align: center;
	text-transform: uppercase;
	-webkit-transition: all .10s ease-out;
	-moz-transition: all .10s ease-out;
	-o-transition: all .10s ease-out;
	transition: all .10s ease-out;
}

.localist-widget-hl .event-card:hover .event-img {
	-webkit-transform: scale(1.75) translateX(-30%) translateY(16%);
	-moz-transform: scale(1.75) translateX(-30%) translateY(16%);
	-ms-transform: scale(1.75) translateX(-30%) translateY(16%);
	-o-transform: scale(1.75) translateX(-30%) translateY(16%);
	transform: scale(1.75) translateX(-30%) translateY(16%);
}

.localist-widget-hl .event-card .content:before {
	position: absolute;
	background: #fff;
	left: 1px;
	bottom: 0;
	right: 1px;
	content: '';
	height: 17px;
}

.localist-widget-hl .event-img {
	position: relative;
	width: auto;
	height: auto;
	min-height: 100%;
	min-width: 100%;
	display: block;
	left: 50%;
	-webkit-transform-origin: center center;
	-moz-transform-origin: center center;
	-ms-transform-origin: center center;
	-o-transform-origin: center center;
	transform-origin: center center;
	-webkit-transform: translateX(-50%);
	-moz-transform: translateX(-50%);
	-ms-transform: translateX(-50%);
	-o-transform: translateX(-50%);
	transform: translateX(-50%);
	-webkit-transition: all .10s ease-out;
	-moz-transition: all .10s ease-out;
	-o-transition: all .10s ease-out;
	transition: all .10s ease-out;
}

.localist-widget-hl .event-card img {
	display: block;
	height: auto;
	width: 100%;
}

.localist-widget-hl .event-card .event-title {
	text-transform: uppercase;
}

.localist-widget-hl .event-card:hover .event-title, .localist-widget-hl .event-card:hover .localist-widget-hl .event-short-date, .localist-widget-hl .event-card:hover .content:before {
	opacity: 0;
	text-decoration: none;
	visibility: hidden;
}

.localist-widget-hl .event-card .event-short-date {
	background: #CF4B06;
}

.localist-widget-hl .event-card:hover header {
	overflow: visible;
}

.localist-widget-hl .event-card:hover {
	border-color: rgba(84, 130, 171, 0.8);
}

.localist-widget-hl .event-card:hover .event-overview {
	-webkit-filter: blur(5px);
	filter: blur(5px);
}

.localist-widget-hl .event-list .event-card {
	height: 21.153846154em;
}

.localist-widget-hl .event-short-date abbr {
	display: block;
	font-size: 35px;
	font-weight: 800;
	line-height: 1.181818182em;
	border: 0 none;
	text-decoration: none;
}

.localist-widget-hl * {
	-moz-box-sizing: border-box;
	-webkit-box-sizing: border-box;
	box-sizing: border-box;
}

.localist-widget-hl .pin {
	width: 17px;
	height: 17px;
	border-radius: 48% 50% 50% 0;
	background: #fff;
	-webkit-transform: rotate(-45deg);
	-moz-transform: rotate(-45deg);
	-ms-transform: rotate(-45deg);
	-o-transform: rotate(-45deg);
	transform: rotate(-45deg);
	float: left;
	margin-left: 10px;
	text-indent: initial;
	-webkit-backface-visibility: hidden;
}

.localist-widget-hl .pin:after {
	content: "";
	width: 6px;
	height: 6px;
	margin: 5px 0 0 6px;
	background: rgba(84, 130, 171, 0.8);
	border-radius: 50%;
	position: absolute;
}

.localist-widget-hl .clock {
	float: left;
	margin-top: 0;
	border: 2px solid #fff;
	display: inline-block;
	position: relative;
	vertical-align: top;
	border-radius: 100%;
	height: 18px;
	width: 18px;
	margin-left: 8px;
	-webkit-backface-visibility: hidden;
}

.localist-widget-hl .clock:before {
	height: 4px;
	left: 8px;
	top: 4px;
	-webkit-transform: rotate(90deg);
	-moz-transform: rotate(90deg);
	-ms-transform: rotate(90deg);
	-o-transform: rotate(90deg);
	transform: rotate(90deg);
	border: 1px solid #fff;
	content: '';
	position: absolute;
}

.localist-widget-hl .clock:after {
	height: 4px;
	left: 6px;
	top: 2px;
	border: 1px solid #fff;
	content: '';
	position: absolute;
}

@media only screen and (min-width: 30em) {
	.localist-widget-hl .event-list > li:nth-child(2n+1) {
		clear: left;
	}
	.localist-widget-hl .event-list > li:not(:nth-child(2n)) {
		margin-right: 5%;
	}
}

@media only screen and (min-width: 45em) {
	.localist-widget-hl .event-list > li:nth-child(3n+1) {
		clear: left;
	}
	.localist-widget-hl .event-list > li:not(:nth-child(3n)) {
		margin-right: 3.125%;
	}
	.localist-widget-hl .event-list li:nth-child(2n+1):not(:nth-child(3n+1)) {
		clear: none;
	}
	.localist-widget-hl .event-list > li:nth-child(3n) {
		margin-right: 0;
	}
}

@media only screen and (min-width: 62.5em) {
	.localist-widget-hl .event-list > li:not(:nth-child(5n)) {
		margin-right: 1.66667%;
	}
	.localist-widget-hl .event-list > li:nth-child(5n+1) {
		clear: left;
	}
	.localist-widget-hl .event-list li:nth-child(3n+1) {
		clear: none;
	}
	.localist-widget-hl .event-list > li:nth-child(5n) {
		margin-right: 0;
	}
}

@media only screen and (min-width: 30em) {
	.localist-widget-hl .event-list > li {
		float: left;
		margin-bottom: 5%;
		width: 47.5%;
	}
}

@media only screen and (min-width: 45em) {
	.localist-widget-hl .event-list > li {
		float: left;
		margin-bottom: 3.125%;
		width: 31.25%;
	}
}

@media only screen and (min-width: 62.5em) {
	.localist-widget-hl .event-list > li {
		float: left;
		margin-bottom: 1.66667%;
		width: 18.66667%;
	}
}

/*
** Campus Life Organism
*/
.hide-on-mobile {
	display: none;
}

@media (min-width: 768px) {
	.hide-on-mobile {
		display: block;
	}
}

.hide-on-tablet {
	display: none;
}

@media (min-width: 1200px) {
	.hide-on-tablet {
		display: block;
	}
}

.o-campus-life {
	/* ---- grid ---- */
	/* clearfix */
	/* ---- grid-item ---- */
}

.o-campus-life .a-base-button {
	width: 100%;
	margin: 1rem auto;
}

@media (min-width: 768px) {
	.o-campus-life .a-base-button {
		width: 50%;
	}
}

.o-campus-life img {
	width: 100%;
}

.o-campus-life .grid-image {
	background-size: cover !important;
	background-position: top center !important;
	background-repeat: no-repeat !important;
	position: relative;
}

.o-campus-life .grid-content {
	padding: 0.5rem;
	text-align: center;
	position: absolute;
	top: 50%;
	left: 50%;
	-webkit-transform: translate(-50%, -50%);
	-moz-transform: translate(-50%, -50%);
	-ms-transform: translate(-50%, -50%);
	-o-transform: translate(-50%, -50%);
	transform: translate(-50%, -50%);
}

.o-campus-life .grid-content p {
	margin-bottom: 0px;
}

.o-campus-life .grid {
	background: transparent;
	max-width: 100%;
	margin: 1rem auto;
}

.o-campus-life .grid:after {
	content: '';
	display: block;
	clear: both;
}

.o-campus-life .square-block-content--hide-content p {
	display: none;
}

@media (min-width: 1366px) {
	.o-campus-life .square-block-content--hide-content p {
		display: block;
	}
}

.o-campus-life .grid-item {
	width: 160px;
	height: 120px;
	float: left;
	background: #F6F6F6;
	border: 0px;
	border-radius: 0px;
}

.o-campus-life .grid-item--width1 {
	width: 50%;
	height: 150px;
}

@media (min-width: 768px) {
	.o-campus-life .grid-item--width1 {
		width: 20%;
	}
}

.o-campus-life .grid-item--width2 {
	width: 40%;
}

.o-campus-life .grid-item--width3 {
	width: 50%;
	height: 150px;
}

@media (min-width: 768px) {
	.o-campus-life .grid-item--width3 {
		width: 60%;
	}
}

.o-campus-life .grid-item--width4 {
	width: 80%;
}

.o-campus-life .grid-item--height2 {
	height: 150px;
}

@media (min-width: 576px) {
	.o-campus-life .grid-item--height2 {
		height: 250px;
	}
}

@media (min-width: 768px) {
	.o-campus-life .grid-item--height2 {
		height: 200px;
	}
}

.o-campus-life .grid-item--height3 {
	height: 260px;
}

.o-campus-life .grid-item--height4 {
	height: 150px;
}

@media (min-width: 576px) {
	.o-campus-life .grid-item--height4 {
		height: 250px;
	}
}

@media (min-width: 768px) {
	.o-campus-life .grid-item--height4 {
		height: 400px;
	}
}

.o-campus-life .grid-item--height500px {
	height: 400px;
}

/*
* Footer Organisms
*/
.o-footer-section a {
	text-decoration: none;
}

.o-footer-section a:hover {
	text-decoration: underline;
}

.o-footer-section .a-base-button:hover {
	text-decoration: none;
}

.o-footer-top {
	background: transparent;
	-webkit-box-shadow: 0px -4px 4px rgba(0, 0, 0, 0.1);
	box-shadow: 0px -4px 4px rgba(0, 0, 0, 0.1);
	padding: 1.5rem 1rem;
}

.o-footer-middle {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	padding: 3rem 1rem;
}

.o-footer-middle .a-base-button {
	margin: 0.5rem 0;
}

@media (min-width: 768px) {
	.o-footer-middle .a-base-button {
		margin: 0;
	}
}

.o-footer-middle .m-footer-links--right {
	margin-top: -1rem;
}

@media (min-width: 576px) {
	.o-footer-middle .m-footer-links--right {
		margin-top: 0;
	}
}

@media (min-width: 768px) {
	.o-footer-middle .m-footer-links--right {
		margin-top: -1rem;
	}
}

#o-footer-bottom a {
	color: #ffffff;
}

.o-footer-bottom {
	background: #14325f;
	padding: 2rem 1rem;
}

.o-footer-bottom .m-footer-links {
	margin-bottom: 0;
}

.o-footer-bottom .m-footer-links--right {
	margin-top: -1rem;
}

@media (min-width: 576px) {
	.o-footer-bottom .m-footer-links--right {
		margin-top: 0;
	}
}

@media (min-width: 992px) {
	.o-footer-bottom .m-footer-links--right {
		margin-top: 0;
	}
}

/*mobile menu styles*/
@media (min-width: 770px) {
	#searchtoggl {
		display: none;
	}
}

body.mmactive {
	overflow: hidden !important;
	max-height: 100% !important;
}

.logo-port img {
	width: auto;
}

.mobile-menu-only {
	display: none;
}

@media (min-width: 0px) and (max-width: 770px) {
	.mobile-menu-only {
		display: block;
	}
}

.mobile_menu {
	display: none;
	position: relative;
}

.sm_menu_outer.active .mobile_menu {
	display: block;
	padding: 0;
	margin: 0;
	background-color: #fff;
}

.sm_menu_outer {
	overflow-y: scroll;
	overflow-x: hidden;
	position: fixed;
	top: 60px;
	right: 0;
	z-index: -9;
	width: 100%;
	opacity: 0;
	-webkit-transition: opacity 0.2s;
	-o-transition: opacity 0.2s;
	-moz-transition: opacity 0.2s;
	transition: opacity 0.2s;
}

.sm_menu_outer.active {
	opacity: 1;
	z-index: 999;
}

.sm_menu_outer .mobile_menu li.back a {
	padding: 10px 5px 10px 5px;
	display: block;
	text-align: center;
	border: 1px solid #14325F;
	font: 600 12px/140% "HelveticaNeue", sans-serif;
	width: 86%;
	margin: auto;
	margin-top: 10px;
	margin-bottom: 10px;
	font-weight: bold;
	color: #14325f;
	background: transparent;
}

.sm_menu_outer .mobile_menu li.back span {
	font-size: 12px;
	padding-right: 6px;
}

.sm_menu_outer .mobile_menu a {
	color: #14325f;
	display: block;
	font: 600 12px/140% "HelveticaNeue", sans-serif;
	letter-spacing: 1px;
	padding: 16px 0px 16px 30px;
	text-transform: uppercase;
	text-decoration: none;
}

/*Sub Menu anim */
.sm_menu_outer .mobile_menu .submenu {
	background-color: #ffffff;
	height: 100%;
	position: absolute;
	right: -100%;
	top: 0;
	-webkit-transition: all 0.5s ease 0s;
	-o-transition: all 0.5s ease 0s;
	-moz-transition: all 0.5s ease 0s;
	transition: all 0.5s ease 0s;
	width: 100%;
	z-index: 999;
	padding: 0;
}

/* Support for long submenu */
.sm_menu_outer .mobile_menu li.active > .submenu {
	right: 0;
	margin-bottom: 300px;
	overflow-y: hidden;
	overflow-x: hidden;
}
.sm_menu_outer .mobile_menu li.active, .ul.submenu .active{
	min-height: 197px;
	height: 100%;
}

/* Support for fixed mobile header when submenu is active - scroll fix */
.sm_menu_outer.active .mobile_menu > .header-mobile, .nav-up {
	position: fixed;
	top: 0;
}

/* Support for first submenu parent LI to have background */
#mobile-menu-navigation > div > ul > li.hasChild.active > ul > li:nth-child(2) {
	background-color: #efefef;
	border-bottom: 1px solid #14325f;
	-webkit-box-shadow: 0 0.5px 0.5px rgba(20, 50, 95, 0.5);
	box-shadow: 0 0.5px 0.5px rgba(20, 50, 95, 0.5);
}
#mobile-menu-navigation > div > ul > li.hasChild.active > ul > li.hasChild.active > ul > li:nth-child(2) {
	background-color: #efefef;
	border-bottom: 1px solid #14325f;
	-webkit-box-shadow: 0 0.5px 0.5px rgba(20, 50, 95, 0.5);
	box-shadow: 0 0.5px 0.5px rgba(20, 50, 95, 0.5);
}

/* Remove background for mobile-blue submenu */
#mobile-menu-navigation > div > ul > li.mobile-blue.hasChild.active > ul > li:nth-child(2) {
	background-color: transparent;
	border-bottom: 0.5px solid rgba(20, 50, 95, 0.5);
	-webkit-box-shadow: none;
	box-shadow: none;
}


.sm_menu_outer .mobile_menu li {
	list-style-type: none;
	border-bottom: 0.5px solid rgba(20, 50, 95, 0.5);
}

.sm_menu_outer .mobile_menu li.hasChild > a {
	background: url("/_resources/img/angle-right.svg") no-repeat scroll 95% center/2.5% auto;
}

.sm_menu_outer .mobile_menu li.hasChild.mobile-blue > a {
	background: url("/_resources/img/angle-right-white.svg") no-repeat scroll 95% center/2.5% auto;
}

/*Hamburger Animation */
#nav-icon3 {
	width: 23px;
	position: relative;
	margin: 0;
	-webkit-transform: rotate(0deg);
	-moz-transform: rotate(0deg);
	-o-transform: rotate(0deg);
	-ms-transform: rotate(0deg);
	transform: rotate(0deg);
	-webkit-transition: .5s ease-in-out;
	-moz-transition: .5s ease-in-out;
	-o-transition: .5s ease-in-out;
	transition: .5s ease-in-out;
	cursor: pointer;
	top: -18px;
}

.mobile-menu-toggle--container {
	position: absolute;
	top: 50%;
	-webkit-transform: translateY(-50%);
	-moz-transform: translateY(-50%);
	-ms-transform: translateY(-50%);
	-o-transform: translateY(-50%);
	transform: translateY(-50%);
	right: 8px;
}

#nav-icon3 span {
	display: block;
	position: absolute;
	height: 3px;
	width: 23px;
	background: #fff;
	border-radius: 0px;
	opacity: 1;
	left: 0;
	-webkit-transform: rotate(0deg);
	-moz-transform: rotate(0deg);
	-o-transform: rotate(0deg);
	-ms-transform: rotate(0deg);
	transform: rotate(0deg);
	-webkit-transition: .25s ease-in-out;
	-moz-transition: .25s ease-in-out;
	-o-transition: .25s ease-in-out;
	transition: .25s ease-in-out;
}

#nav-icon3 span:nth-child(1) {
	top: 0px;
}

#nav-icon3 span:nth-child(2), #nav-icon3 span:nth-child(3) {
	top: 7px;
}

#nav-icon3 span:nth-child(4) {
	top: 14px;
}

.open #nav-icon3 span:nth-child(1) {
	top: 7px;
	width: 0%;
	left: 50%;
}

.open #nav-icon3 span:nth-child(2) {
	-webkit-transform: rotate(45deg);
	-moz-transform: rotate(45deg);
	-o-transform: rotate(45deg);
	-ms-transform: rotate(45deg);
	transform: rotate(45deg);
}

.open #nav-icon3 span:nth-child(3) {
	-webkit-transform: rotate(-45deg);
	-moz-transform: rotate(-45deg);
	-o-transform: rotate(-45deg);
	-ms-transform: rotate(-45deg);
	transform: rotate(-45deg);
}

.open #nav-icon3 span:nth-child(4) {
	top: 7px;
	width: 0%;
	left: 50%;
}

#sm_menu_ham {
	cursor: pointer;
	position: relative;
	top: 0px;
	right: 0;
	float: right;
	z-index: 9999;
}

#sm_menu_ham button {
	background: transparent;
	border: 0;
	color: #ffffff;
}

#sm_menu_ham .mmlabel {
	color: #ffffff;
	font-size: 8px;
	font-family: "HelveticaNeue", sans-serif;
	position: absolute;
	line-height: 5px;
	top: 24px;
	left: 0px;
	margin: 0 auto;
	background-color: transparent;
}

/**#sm_menu_ham button:after {
content:'MENU';
color: $white;
font-size: 8px;
position: fixed;
font-family: "HelveticaNeue", sans-serif;
display: block;
top:22px;
left:-1px;
}**/
/**#sm_menu_ham.open button:after {
content:'CLOSE';
//  margin-top: 2px;
margin-left: -2px;
}**/
/*@media (min-width: 0px) and (max-width: 767px) {}
@media (min-width: 768px) and (max-width: 991px) {}
@media (min-width: 992px) and (max-width: 1024px) {}*/
@media (max-width: 769px) {
	#sm_menu_ham,
	.sm_menu_outer {
		display: block;
	}
}

@media (min-width: 770px) {
	#sm_menu_ham,
	.sm_menu_outer {
		display: none;
	}
}

/*custom classes*/
header.mobile {
	height: 60px;
	background-color: #14325f;
	position: fixed;
	width: 100%;
	left: 0px;
	padding: 16px 0px;
	z-index: 999;
	-webkit-transition: top 0.2s ease-in-out;
	-o-transition: top 0.2s ease-in-out;
	-moz-transition: top 0.2s ease-in-out;
	transition: top 0.2s ease-in-out;
}

header.mobile .logo-port {
	padding-left: 15px;
	position: absolute;
	top: 50%;
	-webkit-transform: translateY(-50%);
	-moz-transform: translateY(-50%);
	-ms-transform: translateY(-50%);
	-o-transform: translateY(-50%);
	transform: translateY(-50%);
}

header.mobile .logo-port img {
	height: 33px;
	color: #ffffff;
}

.menu-wrap {
	height: 100vh;
	width: 50%;
	padding: 0;
	float: left;
	position: relative;
}

.show-in-mobile {
	display: none;
}

@media (min-width: 0px) and (max-width: 769px) {
	.show-in-mobile {
		display: block;
	}
}

.mobile-quicklinks {
	background-color: #14325f;
}

.sm_menu_outer .mobile_menu .mobile-quicklinks a {
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	display: inline-block;
	white-space: nowrap;
	width: 50%;
	color: #ffffff;
	text-align: center;
	padding-left: 0;
	font-size: 11px;
	font-weight: 500;
	border: 1px solid #415e8a;
	border-top: none;
	border-left: none;
	border-right: none;
}

.sm_menu_outer .mobile_menu .mobile-quicklinks a:nth-child(odd) {
	border-right: 1px solid #415e8a;
}

li.mobile-blue {
	background-color: #14325f;
}

.sm_menu_outer .mobile_menu li.mobile-blue a {
	color: #ffffff;
}

.sm_menu_outer .mobile_menu li.mobile-blue ul li a {
	color: #14325f;
}

.mobile-theme-toggle {
	background-color: #14325f;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	border-top: 1px solid #415e8a;
	padding: 15px 15px 15px 30px;
	-webkit-box-shadow: 0 3px 4px 0 rgba(0, 0, 0, 0.5);
	box-shadow: 0 3px 4px 0 rgba(0, 0, 0, 0.5);
}

.mobile-theme-toggle img {
	width: auto;
}

.mm-divider {
	color: #ffffff;
	position: relative;
	padding: 0 14px;
}

.device-ios #searchtoggl {
	top: 5px !important;
}

.device-ios #sm_menu_ham .mmlabel {
	position: absolute;
	line-height: 2.5px;
}

.device-ios #mobile-menu-buttons--container {
	right: 28px !important;
}

/** hidden search field **/
#searchtoggl {
	background: transparent;
	border: 0;
	position: relative;
	right: 0px;
	left: 0px;
	top: 4px;
	padding-right: 28px;
}

#searchtoggl .fa {
	color: #ffffff;
	line-height: 1em;
	font-size: 1.1em;
}

#searchform {
	width: 90%;
	margin: auto;
}

#searchbar {
	position: fixed;
	left: 0;
	top: 60px;
	display: none;
	float: left;
	width: 100%;
	height: 62px;
	z-index: 9999;
	background: #14325f;
}

#s {
	display: block;
	width: 88%;
	border: 0;
	outline: none;
	padding: 0 0 0 12px;
	height: 40px;
	line-height: 40px;
	font-size: 1rem;
	font-weight: normal;
	color: #000000 !important;
	margin: auto;
}

#searchsubmit {
	display: block;
	color: #282828;
	border: 0;
	outline: none;
	cursor: pointer;
	position: absolute;
	right: 10%;
	top: 0px;
	color: #fff;
	background-color: #0054A0;
	font-size: 14px;
	padding: 13px;
}

#searchtoggl .fa:after {
	content: 'SEARCH';
	color: #ffffff;
	font-size: 8px;
	font-family: "HelveticaNeue", sans-serif;
	margin-top: 0;
	margin-left: 1px;
	font-weight: bold;
	display: block;
}

.mobile-nav-up {
	top: -60px;
}

.mobile-nav-down {
	top: 0px;
}

.sm_menu_outer .a-theme-toggles {
	display: inherit;
	background: #14325f;
	padding: 1rem;
	border-top: 1px solid #415e8a;
	-webkit-box-shadow: 0 3px 4px 0 rgba(0, 0, 0, 0.5);
	box-shadow: 0 3px 4px 0 rgba(0, 0, 0, 0.5);
}

.sm_menu_outer .a-vertical-line {
	color: #ffffff;
	padding-left: 0.38em;
	padding-right: 0.38em;
}

.sm_menu_outer .a-vertical-line:after {
	content: '';
	border: 0.5px solid #ffffff;
	height: 24px;
	margin-left: 1.5px;
	margin-right: 1.5px;
	display: block;
}

.sm_menu_outer .a-theme-toggles {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
	-webkit-box-align: center;
	-webkit-align-items: center;
	-moz-box-align: center;
	-ms-flex-align: center;
	align-items: center;
}

.sm_menu_outer #mobile-sun-button, .sm_menu_outer #mobile-moon-button {
	width: auto;
	background-size: contain;
}

.sm_menu_outer #mobile-sun-button {
	background-image: url("/_resources/img/sun.svg");
	padding: 0.6rem;
	margin-left: 12px;
}

.sm_menu_outer #mobile-moon-button {
	background-image: url("/_resources/img/moon.svg");
	padding: 0.6rem;
}

.sm_menu_outer .m-theme-toggle {
	background-color: transparent;
	background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	border: 2px solid transparent;
}

.sm_menu_outer .m-theme-toggle:hover {
	cursor: pointer;
}

#mobile-menu-buttons--container {
	position: absolute;
	top: 50%;
	-webkit-transform: translateY(-50%);
	-moz-transform: translateY(-50%);
	-ms-transform: translateY(-50%);
	-o-transform: translateY(-50%);
	transform: translateY(-50%);
	right: 28px;
}

/*
*** HERO SLIDER ORGANISMS ***
*/
#hero-slider {
	margin-bottom: 0px;
	visibility: hidden;
	height: 50vh;
}

#hero-slider h1, #hero-slider p {
	color: #ffffff;
}

@media (min-width: 768px) {


	#hero-slider {
		height: 65vh;
		min-height: 500px;
	}
}

/*
*** HOME CARDS ORGANISMS ***
*/
#home-cards p {
	margin: 1rem 0;
}

/*
*** FAST FACTS ORGANISMS ***
*/
#fast-facts .a-fact {
	text-align: center;
}

/*
*** EVENTS ORGANISMS
*/
#events h3 {
	padding-bottom: 0.5rem;
	margin-bottom: 1rem;
}

/*
*** EVENTS ORGANISMS
*/
#events h3 {
	padding-bottom: 0.5rem;
	margin-bottom: 1rem;
}

/*
*** CAMPUS LIFE ORGANISMS
*/
#campus-life {
	margin: 1rem auto;
}

/**
* Subnav Organism
*/
#o-right-sidebar h3 {
	padding-bottom: 8px;
}

#subnav-aside .top-level-menu-item {
	border-left: 4px solid transparent;
}

.subnav-container {
	margin: 0 0 1.875rem 0;
	padding: 0 1rem;
	margin-top: 16px;
}

@media (max-width: 992px){
	.subnav-container {
		margin-top: 0px;
	}
}

.subnav-container .subnav-content {
	margin-bottom: 2.5rem;
}

.subnav-container .section-title {
	margin: 0;
	padding: 0.75rem;
	position: relative;
	font-weight: normal;
	cursor: pointer;
	z-index: 5;
}

@media (min-width: 992px) {
	.subnav-container .section-title {
		display: block;
		border: 0;
		text-align: left;
		font-weight: 600;
		padding: 0 0.75rem 0.75rem 0;
		display: none;
	}
}

.subnav-container .section-title:before {
	display: inline-block;
	font-family: 'Font Awesome 5 Free';
	content: "\f105";
	font-weight: 900;
	padding-left: 5px;
	position: relative;
	-webkit-transition: -webkit-transform 0.3s;
	transition: -webkit-transform 0.3s;
	-o-transition: -o-transform 0.3s;
	-moz-transition: transform 0.3s, -moz-transform 0.3s;
	transition: transform 0.3s;
	transition: transform 0.3s, -webkit-transform 0.3s, -moz-transform 0.3s, -o-transform 0.3s;
	margin-right: 1rem;
}

@media (min-width: 992px) {
	.subnav-container .section-title:before {
		display: none;
	}
}

.subnav-container ul {
	margin: 0;
	padding: 0;
	list-style-type: none;
}

@media (min-width: 768px) {
	.subnav-container ul.subnav {
		display: block;
		background: transparent;
	}
}

.subnav-container ul.subnav > li > a, .subnav-container ul.subnav > li span {
	display: block;
	margin: 0;
	padding-top: 1rem;
	padding-bottom: 1rem;
	padding-left: 2.5rem;
	position: relative;
}

.subnav-container ul.subnav > li > a:hover, .subnav-container ul.subnav > li span:hover {
	text-decoration: none;
	border-bottom: none;
}

.subnav-container ul.sub-menu {
	display: none;
	margin: 0;
	padding: 0 0 0 2.313rem;
}

.subnav-container ul.sub-menu li a {
	text-decoration: none;
}

.subnav-container ul.sub-menu li a:focus {
	text-decoration: underline;
	font-weight: bold;
}

.subnav-container ul.sub-menu li a:hover {
	text-decoration: underline;
}

.subnav-container ul.sub-menu li a:active {
	font-weight: bold;
}

.subnav-container .menu-item-has-children .list-toggle {
	display: block;
	position: absolute;
	background: inherit;
	border: 0;
	text-shadow: none;
	z-index: 1;
}

.subnav-container .menu-item-has-children .list-toggle:before {
	display: inline-block;
	font-family: 'Font Awesome 5 Free';
	content: "\f105";
	font-weight: 900;
	padding-left: 5px;
	position: relative;
	cursor: pointer;
}


.subnav-container .menu-item-has-children .list-toggle:hover {
	text-decoration: none;
}

.subnav-container .menu-item-has-children.list-item-open {
	-webkit-box-pack: start;
	-webkit-justify-content: flex-start;
	-moz-box-pack: start;
	-ms-flex-pack: start;
	justify-content: flex-start;
}

.subnav-container .menu-item-has-children.list-item-open .list-toggle {
	-webkit-transform: rotateZ(90deg);
	-moz-transform: rotateZ(90deg);
	-ms-transform: rotate(90deg);
	-o-transform: rotateZ(90deg);
	transform: rotateZ(90deg);
	margin-top: 7px;
}

.subnav-container .menu-item-has-children.list-item-open .list-toggle:before {
	margin-left: 8px;
}

.subnav-container .menu-item-has-children.list-item-open .sub-menu {
	display: block;
}

#focus-toggle {
	display: none;
}

@media (max-width: 991px) {
	#focus-toggle {
		display: block;
	}
	.subnav-open #subnav-toggle:before {
		-webkit-transform: rotateZ(90deg);
		-moz-transform: rotateZ(90deg);
		-ms-transform: rotate(90deg);
		-o-transform: rotateZ(90deg);
		transform: rotateZ(90deg);
	}
	.subnav-content {
		display: none;
	}
	.subnav-open .subnav-content {
		display: block;
	}
}

.extra-info {
	border: 0;
	-webkit-box-shadow: none;
	box-shadow: none;
	padding: 1rem 0;
}

.extra-info h2 {
	text-align: left;
	padding-bottom: 0.5rem;
	margin-bottom: 1rem;
}

.subnav-container ul, .supplementary-content ul {
	margin: 0;
	padding: 0;
	list-style-type: none;
}

.subnav-container li, .supplementary-content li {
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: vertical;
	-webkit-box-direction: normal;
	-webkit-flex-direction: column;
	-moz-box-orient: vertical;
	-moz-box-direction: normal;
	-ms-flex-direction: column;
	flex-direction: column;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
	margin: 0;
}

.subnav-container li a, .supplementary-content li a {
	display: block;
	margin: 0;
	padding: 10px;
	font-weight: normal;
	text-decoration: none;
}

@media (min-width: 992px) {
	.subnav-container li a, .supplementary-content li a {
		background: none;
	}
}

.subnav-container li a:hover, .supplementary-content li a:hover {
	text-decoration: none;
}

@media (min-width: 992px) {
	.subnav-container li a:hover, .supplementary-content li a:hover {
		background: none;
		text-decoration: underline;
	}
}

.supplementary-content {
	padding: 0 1rem;
}

@media (min-width: 992px) {
	.supplementary-content {
		padding: 0 1rem 0 0;
	}
}

/*
*** Slider Organism
*/
.o-slider {
	margin: 1rem 0;
}

.o-slider .m-slide {
	padding: 0;
	margin-top: 1rem;
}

.o-slider .a-slide-caption {
	padding: 1.5rem;
}

.o-slider p {
	font-style: italic;
	margin-bottom: 0;
}

.o-slider .m-slide img {
	width: 100%;
}

.o-slider .m-caption-slider-nav {
	margin-top: -1rem;
	margin-bottom: 1rem;
	display: -webkit-box;
	display: -webkit-flex;
	display: -moz-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-orient: horizontal;
	-webkit-box-direction: normal;
	-webkit-flex-direction: row;
	-moz-box-orient: horizontal;
	-moz-box-direction: normal;
	-ms-flex-direction: row;
	flex-direction: row;
	-webkit-box-pack: center;
	-webkit-justify-content: center;
	-moz-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}

.o-slider .slick-dots {
	width: auto;
	display: inline;
	top: -1px;
}

.o-slider .slick-dots li {
	margin: 0 2px;
}

.o-slider .slick-dots li button:before {
	font-size: 15px;
	font-family: Font Awesome 5 Free;
	content: "\f1db";
	opacity: 1;
	font-weight: 900;
}

.o-slider .slick-dots li.slick-active button:before {
	font-family: Font Awesome 5 Free;
	font-weight: 900;
	content: "\f111";
}

.o-slider .fa {
	font-weight: bold;
	font-size: 1.8rem;
}

.o-slider .prev, .o-slider .next {
	background: transparent;
	border: 0;
	position: relative;
	right: auto;
	top: auto;
	display: inline;
	z-index: 5;
}

.o-slider .prev:hover, .o-slider .next:hover {
	cursor: pointer;
}

.o-slider .prev {
	left: -8px;
}

.o-slider .next {
	right: -8px;
}

.a-outline-btn-skin:hover,
.a-home-white-button:hover {
	cursor: pointer;
	text-decoration: none;
}

.a-outline-btn-skin:hover {
	background: #00CC36;
	color: #282828;
}

.a-home-white-button:hover {
	background: #d8d8d8;
	text-decoration: none;
}

.a-fullscreen-dots li button:hover {
	outline: none;
}

.a-fullscreen-dots li.slick-active button {
	background: #ffffff;
}

/*
** Home Tab Accordion States
*/
.state-hasBgImage--purple {
	background: -webkit-gradient(linear, left top, right top, from(rgba(36, 13, 92, 0.8)), to(rgba(36, 13, 92, 0.8))), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -o-linear-gradient(left, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: linear-gradient(to right, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background-size: cover !important;
}

.state-hasBgImage--orange {
	background: -webkit-gradient(linear, left top, right top, from(rgba(185, 58, 0, 0.8)), to(rgba(185, 58, 0, 0.8))), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -o-linear-gradient(left, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: linear-gradient(to right, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background-size: cover !important;
}

.state-hasBgImage--red {
	background: -webkit-gradient(linear, left top, right top, from(rgba(150, 0, 20, 0.8)), to(rgba(150, 0, 20, 0.8))), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -o-linear-gradient(left, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: linear-gradient(to right, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background-size: cover !important;
}

.state-hasBgImage--dark-blue {
	background: -webkit-gradient(linear, left top, right top, from(rgba(20, 50, 95, 0.8)), to(rgba(20, 50, 95, 0.8))), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: -o-linear-gradient(left, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background: linear-gradient(to right, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)), url("/_resources/img/tab-background.jpg") no-repeat center !important;
	background-size: cover !important;
}

.state-hasBgImage--blue {
	background-size: cover;
	background-repeat: no-repeat;
	position: relative;
	width: 100%;
	height: 100%;
}

.state-hasBgImage--blue:before {
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	background: -webkit-gradient(linear, left top, right top, from(rgba(0, 56, 147, 0.9)), to(rgba(0, 56, 147, 0.9))), no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(0, 56, 147, 0.9), rgba(0, 56, 147, 0.9)), no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(0, 56, 147, 0.9), rgba(0, 56, 147, 0.9)), no-repeat center !important;
	background: -o-linear-gradient(left, rgba(0, 56, 147, 0.9), rgba(0, 56, 147, 0.9)), no-repeat center !important;
	background: linear-gradient(to right, rgba(0, 56, 147, 0.9), rgba(0, 56, 147, 0.9)), no-repeat center !important;
}

.state-content-top-hasBgImage--purple:before {
	background: -webkit-gradient(linear, left top, right top, from(rgba(36, 13, 92, 0.8)), to(rgba(36, 13, 92, 0.8))) no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)) no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)) no-repeat center !important;
	background: -o-linear-gradient(left, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)) no-repeat center !important;
	background: linear-gradient(to right, rgba(36, 13, 92, 0.8), rgba(36, 13, 92, 0.8)) no-repeat center !important;
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
}

.state-content-top-hasBgImage--orange:before {
	background: -webkit-gradient(linear, left top, right top, from(rgba(185, 58, 0, 0.8)), to(rgba(185, 58, 0, 0.8))) no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)) no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)) no-repeat center !important;
	background: -o-linear-gradient(left, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)) no-repeat center !important;
	background: linear-gradient(to right, rgba(185, 58, 0, 0.8), rgba(185, 58, 0, 0.8)) no-repeat center !important;
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
}

.state-content-top-hasBgImage--red:before {
	background: -webkit-gradient(linear, left top, right top, from(rgba(150, 0, 20, 0.8)), to(rgba(150, 0, 20, 0.8))) no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)) no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)) no-repeat center !important;
	background: -o-linear-gradient(left, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)) no-repeat center !important;
	background: linear-gradient(to right, rgba(150, 0, 20, 0.8), rgba(150, 0, 20, 0.8)) no-repeat center !important;
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
}

.state-content-top-hasBgImage--dark-blue:before {
	background: -webkit-gradient(linear, left top, right top, from(rgba(20, 50, 95, 0.8)), to(rgba(20, 50, 95, 0.8))) no-repeat center !important;
	background: -webkit-linear-gradient(left, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)) no-repeat center !important;
	background: -moz- oldlinear-gradient(left, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)) no-repeat center !important;
	background: -o-linear-gradient(left, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)) no-repeat center !important;
	background: linear-gradient(to right, rgba(20, 50, 95, 0.8), rgba(20, 50, 95, 0.8)) no-repeat center !important;
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
}

.state-content-top--hasBgImage {
	background-size: cover;
	background-image: url("/_resources/img/tab-background.jpg");
	height: 50vh;
	background-repeat: no-repeat;
	position: relative;
	width: 100%;
}

@media (min-width: 768px) {
	.state-content-top--hasBgImage {
		height: 65vh;
	}
}

.state-content-top--hasBgImage .m-caption-overlay {
	background: rgba(20, 50, 95, 0.7);
}

.state-content-top--hasBgImage .m-caption-overlay h1, .state-content-top--hasBgImage .m-caption-overlay h2, .state-content-top--hasBgImage .m-caption-overlay h3, .state-content-top--hasBgImage .m-caption-overlay h4, .state-content-top--hasBgImage .m-caption-overlay h5, .state-content-top--hasBgImage .m-caption-overlay h6, .state-content-top--hasBgImage .m-caption-overlay p {
	color: #ffffff;
}

.state-content-top--hasBgImage .m-caption-overlay .a-figure-caption {
	width: auto;
}

.state-content-top--hasBgImage .a-figure-caption {
	background: transparent;
	width: auto;
}

@media (min-width: 768px) {
	.state-content-top--hasBgImage .a-figure-caption {
		width: 50%;
	}
}

.state-content-top--hasBgImage .a-figure-caption h1, .state-content-top--hasBgImage .a-figure-caption h2, .state-content-top--hasBgImage .a-figure-caption h3, .state-content-top--hasBgImage .a-figure-caption h4, .state-content-top--hasBgImage .a-figure-caption h5, .state-content-top--hasBgImage .a-figure-caption h6, .state-content-top--hasBgImage .a-figure-caption p {
	color: #ffffff;
}

.state-content-top--hasBgImage .a-figure-caption .a-figure-caption-content {
	position: relative;
	left: 0;
}

@media (min-width: 768px) {
	.state-content-top--hasBgImage .a-figure-caption .a-figure-caption-content {
		left: 5rem;
	}
}

.state--noCardImage p {
	margin: 1rem 0;
}

@media (min-width: 1200px) {
	.state--noCardImage p {
		margin: 0.5rem 0;
	}
}

.state--noCardImage ul {
	margin-bottom: 2rem;
}

@media (min-width: 1200px) {
	.state--noCardImage ul {
		margin-bottom: 1rem;
	}
}

.state--noCardImage .m-card-content {
	padding: 2rem 2rem 1rem 2rem;
}

/*
*** Marketing Page Header States
*/
.state-has-dark-background {
	background: #282828 !important;
	border-top: 1px solid #282828 !important;
}

.state-has-primary-blue--background {
	background: #003893 !important;
	border-top: 1px solid #003893 !important;
}

.state-has-primary-orange--background {
	background: #CF4B06 !important;
	border-top: 1px solid #CF4B06 !important;
}

/*
*** Cards with No Image
*/
.m-card--no-image {
	padding: 2rem 2rem 1rem 2rem !important;
}

/*
*** States for Layout
*/
.state-has-padding--top {
	padding-top: 2rem;
}

@media (min-width: 768px) {
	.state-has-padding--top {
		padding-top: 3rem;
	}
}

.state-has-margin--top {
	margin-top: 0;
}

@media (min-width: 768px) {
	.state-has-margin--top {
		margin-top: 1rem;
	}
}

.state-has-padding--left {
	padding-left: 15px;
}

@media (min-width: 768px) {
	.state-has-padding--left {
		padding-left: 4rem;
	}
}

.state-has-padding--right {
	padding-right: 15px;
}

@media (min-width: 768px) {
	.state-has-padding--right {
		padding-right: 4rem;
	}
}

/*
*** States: Home Events in Tabs & Home Events in Academic Dates & Deadlines
*/
.state-has-border--right {
	border-right: 0;
}

@media (min-width: 768px) {
	.state-has-border--right {
		border-right: 1px solid #ffffff;
	}
}

.state-has-border--right-green {
	border-right: 0;
}

@media (min-width: 768px) {
	.state-has-border--right-green {
		border-right: 1px solid #00CC36;
	}
}

/*
*** Overides added to fix Safari issues
*/
@media print {
	*:before, *:after {
		background: transparent !important;
		color: #000 !important;
		-webkit-box-shadow: none !important;
		box-shadow: none !important;
		text-shadow: none !important;
	}
	a,
	a:visited {
		text-decoration: underline;
	}
	a[href]:after {
		content: " (" attr(href) ")";
	}
	abbr[title]:after {
		content: " (" attr(title) ")";
	}
	a[href^="#"]:after,
	a[href^="javascript:"]:after {
		content: "";
	}
	pre,
	blockquote {
		border: 1px solid #999;
		page-break-inside: avoid;
	}
	thead {
		display: table-header-group;
	}
	tr,
	img {
		page-break-inside: avoid;
	}
	img {
		max-width: 100% !important;
	}
	p,
	h2,
	h3 {
		orphans: 3;
		widows: 3;
	}
	h2,
	h3 {
		page-break-after: avoid;
	}
}

/* Legacy CSS for Migration */

/* Bootstrap Inline Button */
a.btn {
	display: inline-block;
	padding: 20px 10px;
	margin-bottom: 5px;
	color: #333;
	font: 600 18px/24px Arial, Helvetica, sans-serif;
	text-align: center;
	white-space: normal;
	vertical-align: middle;
	-ms-touch-action: manipulation;
	touch-action: manipulation;
	cursor: pointer;
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	background-color: #e7e7e7;
	background-image: none;
	border: none;
	border-radius: 0;
	box-sizing: border-box;
	-webkit-transition: all 0.3s;
	transition: all 0.3s;
	font-size: 1.25rem;
}

a.btn, a.btn-secondary .ui-widget-content a {
	background-color: #14325f;
	color: #fff !important;
	border: none;
}

a.btn-secondary:hover {
	background-color: #0e2343;
	color: #fff !important;
	border: none;
}

/* :target {
	scroll-margin-top: 335px;
	scroll-snap-margin-top: 335px;
} */

.stretched-link::after {
	position: absolute;
	top: 0;
	right: 0;
	bottom: 0;
	left: 0;
	z-index: 1;
	pointer-events: auto;
	content: "";
	background-color: rgba(0,0,0,0);
}

/* GSE - Remove Promotion */
.gsc-promotion {
	display: none;
}

/**
** THEMES
**/
/** Both Themes **/
.accordion-container .accordion-card .accordion-link:before {
	margin-bottom: 15px;
}

/**
**  LIGHT THEME
**/
.light-theme {
	background: #ffffff;
	/*
	** Small Help Text for Forms
	*/
	/*
	*** SUBNAV LIGHT THEME
	*/
	/*
	*** ACCORDION LIGHT THEME MOLECULES ***
	*/
	/*
	*** jQuery TABS LIGHT THEME MOLECULES ***
	*/
	/**
	** Landscape Card CTAs Molecules
	**/
	/**
	** Vertical Card CTAs Molecules
	**/
	/*
	*** Home Tabs to Accordion Organisms Light Theme
	*/
	/*
	*** HOME CARDS ORGANISMS ***
	*/
	/*
	*** FAST FACTS ORGANISMS
	*/
	/*
	*** EVENTS ORGANISMS
	*/
	/*
	*** FOOTER MIDDLE NO BACKGROUND IMAGE
	*/
	/*
	*** Back To Top Molecules
	*/
	/*
	*** Right Sidebar Card Molecules
	*/
	/*
	*** Slider Organism
	*/
	/*
	*** Base Button Atoms
	*/
	/*
	*** Light Box Molecules
	*/
	/*
	*** Scrollspy Light Theme Molecules
	*/
	/*
	*** Tooltip Light Theme Mmolecules
	*/
	/*
	*** Blue CTA Light Theme Molecule
	*/
	/*
	*** Pagination Molecule Light Theme
	*/
	/*
	*** Custom Dropdown Light Theme Molecule
	*/
	/*
	*** Form Light Theme Molecules
	*/
	/*
	*** Home Page Events - What's Happening At WVC Light Theme Styles - Localist Calendar
	*/
	/*
	*** Home Page Campus Life Section Light Theme
	*/
	/*
	*** TABLE MOLECULE JQUERY SEARCH LIGHT THEME ***
	*/
	/* ====================================
	JUICER - LIGHT THEME - Overrides

	version: 1.01
	last modified: 2018-03-02
	author: D.Niemann
	email: wv.webmaster@westvalley.edu
	website: westvalley.edu

	Versions:
	1.00: Initial
	1.01: Fix .j-close for .j-overloay modal close - Ln 544 - remove background-size add top property
	1.02: Properties for .j-twiiter-post-icon:before Ln 292
	======================================= */
	/* =====================
	FEED STYLES
	======================= */
	/* CARD BACKGROUND */
	/* =====================
	FILTERS STYLES
	======================= */
	/* =====================
	FILTER - ALL STYLES
	======================== */
	/* ==========================
	FILTER - FACEBOOK STYLES
	============================= */
	/* ===========================
	FILTER - INSTAGRAM STYLES
	============================== */
	/* =========================
	FILTER - TWITTER STYLES
	============================ */
	/* =========================
	FILTER - YOUTUBE STYLES
	============================ */
	/* =====================
	POSTER FEED STYLES
	======================== */
	/* SOCIAL ICON - LINK ON POSTER CARD */
	/* =============================
	POPUP POSTER OVERLAY STYLES
	================================ */
	/*======================================
	GLOBAL FIXES - POPUP OVERLAY
	======================================== */
}

.light-theme #sun-button, .light-theme #mobile-sun-button, .light-theme #tablet-sun-button {
	background-image: url("/_resources/img/sun-green.svg");
	background-size: contain;
}

.light-theme #subnav-aside .top-level-menu-item:hover {
	border-left: 4px solid #14325f;
}

.light-theme #subnav-aside .top-level-menu-item.list-item-open {
	border-left: 4px solid #14325f;
}
.light-theme #fileHelp {
	color: #000000 !important;
}

.light-theme html, .light-theme main, .light-theme aside {
	background: #ffffff;
	-webkit-transition: all 0ms ease;
	-o-transition: all 0ms ease;
	-moz-transition: all 0ms ease;
	transition: all 0ms ease;
}

.light-theme h1 {
	color: #14325f;
}

.light-theme h5, .light-theme h6, .light-theme p {
	color: #282828;
}

.light-theme h2 {
	color: #14325f;
}

.light-theme .has-border {
	border-bottom: 1px solid #14325f;
}

.light-theme .heading-link--has-border:hover, .light-theme .heading-link--has-border:active, .light-theme .heading-link--has-border:focus {
	border: 0;
	text-decoration: underline;
}

.light-theme .heading-link--has-border:hover h5, .light-theme .heading-link--has-border:hover h6, .light-theme .heading-link--has-border:active h5, .light-theme .heading-link--has-border:active h6, .light-theme .heading-link--has-border:focus h5, .light-theme .heading-link--has-border:focus h6 {
	color: #14325f;
}

.light-theme h3 {
	color: #14325f;
}

.light-theme h4 {
	color: #14325f;
}

.light-theme h5, .light-theme h6 {
	color: #282828;
}

.light-theme a {
	color: #003893;
}

.light-theme p {
	color: #282828;
}

.light-theme small {
	color: #282828;
}

.light-theme ol, .light-theme ul {
	color: #282828;
}

.light-theme ol a, .light-theme ul a {
	color: #003893;
}

.light-theme dd, .light-theme dt, .light-theme .a-blockquote-footer {
	color: #282828;
}

.light-theme mark {
	background: #ebb000;
}

.light-theme figure {
	background: #14325f;
	color: #ffffff;
}

.light-theme .m-pull-quote {
	background: #F6F6F6;
	color: #282828;
	border-left: 5px solid #00CC36;
}

.light-theme .o-footer-top {
	background: #EFEFEF;
}

.light-theme #temps {
	color: #14325f;
}

.light-theme #weather {
	color: #282828;
}

.light-theme .m-footer-social-icons .fa {
	color: #282828;
}

.light-theme .state-noBgImage .a-footer-links--heading {
	color: #14325f;
	border-bottom: 1px solid #14325f;
}

.light-theme .state-noBgImage a {
	color: #282828;
}

.light-theme .state-noBgImage .a-base-button {
	background: transparent;
	border: 1px solid #00CC36;
	color: #282828;
}

.light-theme .state-noBgImage .a-base-button:hover {
	background: #00CC36;
}

.light-theme .subnav-container .section-title {
	background: #EFEFEF;
	color: #282828;
}

@media (min-width: 992px) {
	.light-theme .subnav-container .section-title {
		background: transparent;
		color: #14325f;
	}
}

.light-theme .subnav-container .section-title:before {
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f105";
	color: #282828;
}

.light-theme .subnav-container #subnavigation {
	border-bottom: 1px solid #14325f;
}

.light-theme .subnav-container ul.subnav {
	background: #ffffff;
}

@media (min-width: 576px) {
	.light-theme .subnav-container ul.subnav {
		background: transparent;
	}
}

.light-theme .subnav-container ul.subnav > li > a {
	border-top: 1px solid #14325f;
	color: #282828;
}
.light-theme .subnav-container ul.subnav > li span {
	border-top: 1px solid #14325f;
}

.light-theme .subnav-container ul.subnav > li:hover {
	background: #EFEFEF;
	background: #f6f6f6;
}

.light-theme .subnav-container ul.sub-menu {
	background: transparent;
}

@media (min-width: 768px) {
	.light-theme .subnav-container ul.sub-menu {
		background: transparent;
	}
}

.light-theme .subnav-container ul.sub-menu li a {
	color: #282828;
}
.light-theme #subnavigation > ul > li.top-level-menu-item.menu-item-has-children.list-item-open > span {
	background: #f6f6f6;
	/*   border-bottom: 0.5px solid #14325f; */
	/*   border-left: 3px solid #14325f; */
	margin-bottom: 5px;
	-webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.1);
	box-shadow: 0px 3px 4px rgba(0, 0, 0, 0.2);
}
.light-theme #subnav-aside .top-level-menu-item > ul, li.list-item-open {
	border-left: 4px solid #14325f;
	margin-left: -4px;
}

.light-theme .subnav-container .menu-item-has-children button.list-toggle {
	background: transparent;
}

.light-theme .subnav-container .menu-item-has-children button.list-toggle:before {
	display: inline-block;
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f105";
	color: #282828;
}

.light-theme .subnav-container .menu-item-has-children button.list-toggle span {
	color: #282828;
}

.light-theme .subnav-container .menu-item-has-children button.list-toggle:hover {
	color: #ffffff;
}

.light-theme .extra-info {
	background: transparent;
}

.light-theme .extra-info h2 {
	color: #14325f;
	border-bottom: 1px solid #14325f;
}

.light-theme .extra-info a {
	color: #003893;
}

.light-theme .subnav-container li a, .light-theme .supplementary-content li a {
	background: transparent;
}

@media (min-width: 768px) {
	.light-theme .subnav-container li a, .light-theme .supplementary-content li a {
		background: none;
	}
}

.light-theme .subnav-container li a:hover, .light-theme .supplementary-content li a:hover {
	color: #14325f;
}

.light-theme .subnav-container li a:focus, .light-theme .supplementary-content li a:focus {
	color: #14325f;
}

.light-theme .subnav-container #top-level-link--active, .light-theme .supplementary-content #top-level-link--active {
	color: #14325f;
	font-weight: 600;
}

.light-theme .subnav-container #current-page-item, .light-theme .supplementary-content #current-page-item {
	color: #282828;
	font-weight: normal;
}

.light-theme .accordion-container .accordion-card {
	background: transparent;
}

.light-theme .accordion-container .accordion-card a[data-toggle=collapse] {
	color: #282828;
}

.light-theme .accordion-container .accordion-card .card-header {
	padding: 0;
}

.light-theme .accordion-container .accordion-card .accordion-link.collapsed {
	border-top: 1px solid #d8d8d8;
	border-left: 1px solid #d8d8d8;
	border-right: 1px solid #d8d8d8;
	border-bottom: 1px solid transparent;
	background: #EFEFEF;
}

.light-theme .accordion-container .accordion-card .accordion-link.collapsed a:before {
	color: #282828;
}

.light-theme .accordion-container .accordion-card .accordion-link.collapsed:hover {
	background: #14325f;
	border: 1px solid #14325f;
	color: #ffffff;
}

.light-theme .accordion-container .accordion-card .accordion-link {
	padding: 1rem;
	border-top: 1px solid #d8d8d8;
	border-left: 1px solid #d8d8d8;
	border-right: 1px solid #d8d8d8;
	border-bottom: 0;
	background: #ffffff;
}

.light-theme .accordion-container .accordion-card .accordion-link a:before {
	color: #282828;
}

.light-theme .accordion-container .accordion-card .card-block {
	margin-top: -1px;
	border-top: 0;
	border-top: 1px solid #d8d8d8;
	border-left: 1px solid #d8d8d8;
	border-right: 1px solid #d8d8d8;
	border-bottom: 1px solid #d8d8d8;
	-webkit-transition: all 150ms linear;
	-o-transition: all 150ms linear;
	-moz-transition: all 150ms linear;
	transition: all 150ms linear;
}

.light-theme .m-cta--card {
	background: #F6F6F6;
}

.light-theme .m-table {
	background: transparent;
}

.light-theme .m-table .table-header {
	background: transparent;
}

.light-theme .m-table .table {
	color: #282828;
}

.light-theme .m-table thead {
	background: #EFEFEF;
}

.light-theme .m-table .table-striped tbody tr:nth-of-type(odd) {
	background: #ffffff;
}

.light-theme .m-table thead th {
	border-bottom: 2px solid #EFEFEF;
	border-right: 1px solid #ffffff;
	color: #14325f;
}

.light-theme .m-table tbody tr {
	background: #F6F6F6;
}

.light-theme #tabs {
	border: 1px solid #d8d8d8;
	background: transparent;
}

@media (min-width: 768px) {
	.light-theme #tabs {
		background: #ffffff;
	}
}

.light-theme .m-tabs .ui-tabs-nav li {
	background: #14325f;
	color: #ffffff;
}

.light-theme .m-tabs .a-tab-panel {
	border: 1px solid transparent;
	border-top: 0;
}

.light-theme .m-tabs .ui-tab:hover {
	background: #EFEFEF;
}

.light-theme .m-tabs .ui-tab:hover a {
	color: #14325f;
}

.light-theme .m-tabs .ui-tabs-tab {
	background: #EFEFEF;
}

.light-theme .m-tabs .ui-tabs-tab a {
	color: #ffffff;
}

.light-theme .m-tabs .tabs-nav {
	border-top: 0px;
}

.light-theme .m-tabs .tabs-nav li:first-child {
	border-left: 1px solid transparent;
}

.light-theme .m-tabs .tabs-nav li:last-child {
	border-right: 1px solid #14325f;
}

.light-theme .m-tabs .tabs-nav li:last-child:hover {
	border-right: 0px !important;
}

.light-theme .m-tabs .tabs-nav li:last-child.ui-tabs-active {
	border-right: 1px solid transparent;
}

.light-theme .m-tabs .tabs-nav li:last-child.ui-tabs-active:hover {
	border-right: 1px solid transparent !important;
}

.light-theme .m-tabs .ui-tab {
	background: #14325f;
}

.light-theme .m-tabs .ui-tabs-tab {
	border-top-left-radius: 0px !important;
	border-top-right-radius: 0px !important;
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent;
	border-bottom: 1px solid #d8d8d8;
}

@media (min-width: 768px) {
	.light-theme .m-tabs .ui-tabs-tab {
		border-top: 1px solid transparent;
		border-left: 1px solid #d8d8d8;
		border-right: 0px;
		border-bottom: 1px solid #14325f;
	}
	.light-theme .m-tabs .ui-tabs-tab:hover {
		border-top: 1px solid transparent;
		border-left: 1px solid #d8d8d8;
		border-right: 1px solid #d8d8d8 !important;
		border-bottom: 1px solid transparent;
	}
}

.light-theme .m-tabs .ui-tabs-tab:hover {
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent !important;
	border-bottom: 1px solid transparent;
}

.light-theme .m-tabs .ui-tabs-tab.ui-tabs-active {
	border-radius: 0px !important;
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent;
	border-bottom: 1px solid #d8d8d8;
}

@media (min-width: 768px) {
	.light-theme .m-tabs .ui-tabs-tab.ui-tabs-active {
		border-top: 1px solid transparent;
		border-left: 1px solid transparent;
		border-right: 1px solid transparent;
		border-bottom: 0px;
	}
	.light-theme .m-tabs .ui-tabs-tab.ui-tabs-active:hover {
		border-right: 1px solid transparent !important;
	}
}

.light-theme .m-tabs .ui-tabs-tab.ui-tabs-active:hover {
	border-right: 1px solid transparent !important;
	border-radius: 0px !important;
	border-top-left-radius: 0px !important;
	border-top-right-radius: 0px !important;
}

.light-theme .m-tabs .ui-tabs-active a:active {
	color: #282828 !important;
	background: #ffffff !important;
}

.light-theme .m-tabs .ui-tabs-active a:hover {
	color: #282828 !important;
	background: #ffffff !important;
}

.light-theme .m-tabs .ui-tabs-active {
	background: #ffffff !important;
}

.light-theme .m-tabs .ui-tabs-active a {
	color: #282828 !important;
	border: 0px;
}

.light-theme .m-card--horizontal {
	background: #F6F6F6;
}

.light-theme .m-card--homecustom {
	background: #282828;
}

.light-theme .m-card--homecustom h2, .light-theme .m-card--homecustom h3, .light-theme .m-card--homecustom h4, .light-theme .m-card--homecustom h5, .light-theme .m-card--homecustom h6 {
	color: #ffffff;
	border-bottom: 0;
}

.light-theme .m-card--homecustom p {
	color: #ffffff;
}

.light-theme .m-card--homecustom:hover {
	border-bottom: 5px solid #00CC36;
}

.light-theme .o-tabs-accordion--theme .state-has-border--right {
	border-right: 0;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .state-has-border--right {
		border-right: 1px solid #00CC36;
	}
}

.light-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor {
	background: #14325f;
	color: #ffffff;
	border: 1px solid transparent;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor {
		border: 2px solid #14325f;
	}
}

.light-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor:hover {
	background: #EFEFEF;
	border: 1px solid #EFEFEF;
	color: #14325f;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor:hover {
		border: 2px solid #EFEFEF;
	}
}

.light-theme .o-tabs-accordion--theme .ui-tabs-panel h2, .light-theme .o-tabs-accordion--theme h3, .light-theme .o-tabs-accordion--theme h4, .light-theme .o-tabs-accordion--theme h5, .light-theme .o-tabs-accordion--theme h6 {
	color: #14325f;
}

.light-theme .o-tabs-accordion--theme .ui-tabs-panel ul li a {
	color: #003893;
}

.light-theme .o-tabs-accordion--theme .ui-tabs-panel p, .light-theme .o-tabs-accordion--theme .ui-tabs-panel ul li {
	color: #282828 !important;
}

.light-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor {
	background: #ffffff;
	border: 1px solid transparent;
	color: #282828;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor {
		border: 2px solid transparent;
	}
}

.light-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor:hover {
	background: #ffffff !important;
	color: #282828 !important;
	border: 1px solid transparent;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor:hover {
		border: 2px solid transparent;
	}
}

.light-theme .o-tabs-accordion--theme .ui-tabs-tab {
	border-top: 1px solid #14325f;
	border-left: 1px solid #14325f;
	border-right: 1px solid #14325f;
	border-bottom: 1px solid #ffffff;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .ui-tabs-tab {
		border-right: 1px solid #ffffff;
		border-top: #14325f;
		border-left: #14325f;
		border-bottom: 1px solid #14325f;
	}
	.light-theme .o-tabs-accordion--theme .ui-tabs-tab:hover {
		border-bottom: 1px solid transparent;
	}
}

.light-theme .o-tabs-accordion--theme .m-events {
	border-right: 0;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .m-events {
		border-right: 1px solid #00CC36;
	}
}

.light-theme .o-tabs-accordion--theme .m-events .m-event--dates, .light-theme .o-tabs-accordion--theme .m-events .a-date-month, .light-theme .o-tabs-accordion--theme .m-events .a-date-number {
	color: #14325f !important;
}

.light-theme .o-tabs-accordion--theme .ui-tabs-active {
	border: 1px solid #ffffff;
}

@media (min-width: 768px) {
	.light-theme .o-tabs-accordion--theme .ui-tabs-active {
		border: 1px solid transparent;
	}
}

.light-theme #home-cards h2, .light-theme #home-cards h3, .light-theme #home-cards h4, .light-theme #home-cards h5, .light-theme #home-cards h6 {
	color: #282828;
}

.light-theme #home-cards p {
	color: #282828;
}

.light-theme #home-cards .m-card--vertical {
	background: #282828;
}

.light-theme #home-cards .m-card--vertical h2, .light-theme #home-cards h3, .light-theme #home-cards h4, .light-theme #home-cards h5, .light-theme #home-cards h6 {
	color: #ffffff;
}

.light-theme #home-cards .m-card--vertical p {
	color: #ffffff;
}

.light-theme #home-cards .m-card-image {
	border: 1px solid #282828;
}

.light-theme #fast-facts .a-fast--fact {
	color: #CF4B06;
}

.light-theme #fast-facts p {
	color: #282828;
}

.light-theme #events h2, .light-theme #events h3, .light-theme #events h4, .light-theme #events h5, .light-theme #events h6, .light-theme #events span {
	color: #14325f;
}

.light-theme .o-footer-middle.state-noBgImage .a-base-button {
	background: #d8d8d8;
	border: 1px solid #d8d8d8;
}

.light-theme .o-footer-middle.state-noBgImage .a-base-button:hover {
	background: #cfcfcf;
}

.light-theme .m-back-to-top {
	background: #14325f;
}

.light-theme .m-back-to-top span {
	color: #ffffff;
}

.light-theme .m-card--vertical {
	background: #F6F6F6;
}

.light-theme .card {
	position: relative;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	min-width: 0;
	word-wrap: break-word;
	background-color: #f6f6f6;
	background-clip: border-box;
	border: 1px solid rgba(0, 0, 0, 0.125);
	border-radius: 0.25rem;
}

.light-theme .o-slider .a-slide-caption {
	background: #14325f;
}

.light-theme .o-slider p {
	color: #ffffff;
}

.light-theme .o-slider .slick-dots li button:before {
	color: #14325f;
}

.light-theme .o-slider .fa {
	color: #9b9b9b;
}

.light-theme .a-button--primary {
	border: 1px solid #0e2343;
	background: #14325f;
	color: #ffffff !important;
}

.light-theme .a-button--primary:hover {
	background: #0e2343;
	text-decoration: none;
}

.light-theme .a-button--secondary {
	border: 1px solid #00CC36;
	background: #00CC36;
	color: #282828;
}

.light-theme .a-button--secondary:hover {
	background: #00db3a;
	color: #282828;
}

.light-theme .a-button--success {
	border: 1px solid #218739;
	background: #218739;
	color: #ffffff;
}

.light-theme .a-button--success:hover {
	background: #19682c;
}

.light-theme .a-button--danger {
	border: 1px solid #dc3545;
	background: #dc3545;
	color: #ffffff;
}

.light-theme .a-button--danger:hover {
	background: #b62a37;
}

.light-theme .a-button--warning {
	border: 1px solid #ffc107;
	background: #ffc107;
}

.light-theme .a-button--warning:hover {
	background: #ebb000;
	color: #282828;
}

.light-theme .a-button--info {
	border: 1px solid #CF4B06;
	background: #CF4B06;
	color: #ffffff;
}

.light-theme .a-button--info:hover {
	background: #b93a00;
}

.light-theme .a-button--light {
	border: 1px solid #d8d8d8;
	background: #d8d8d8;
	color: #282828 !important;
}

.light-theme .a-button--light:hover {
	background: #cfcfcf;
}

.light-theme .a-button--dark {
	border: 1px solid #0B0B0B;
	background: #0B0B0B;
	color: #ffffff;
}

.light-theme .a-button--dark:hover {
	background: #0B0B0B;
	color: #ffffff;
}

.light-theme .a-button--primary-trans {
	border: 1px solid #14325f;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--primary-trans:hover {
	background: #14325f;
	color: #ffffff;
}

.light-theme .a-button--secondary-trans {
	border: 1px solid #00CC36;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--secondary-trans:hover {
	background: #00CC36;
	color: #282828;
}

.light-theme .a-button--primary-trans-alt {
	border: 1px solid #14325f;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--primary-trans-alt:hover {
	background: #14325f;
	color: #ffffff;
}

.light-theme .a-button--secondary-trans-alt {
	border: 1px solid #00CC36;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--secondary-trans-alt:hover {
	background: #00CC36;
	color: #282828;
}

.light-theme .a-button--success-trans {
	border: 1px solid #218739;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--success-trans:hover {
	background: #218739;
	color: #ffffff;
}

.light-theme .a-button--danger-trans {
	border: 1px solid #dc3545;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--danger-trans:hover {
	background: #dc3545;
	color: #ffffff;
}

.light-theme .a-button--warning-trans {
	border: 1px solid #ffc107;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--warning-trans:hover {
	background: #ffc107;
	color: #282828;
}

.light-theme .a-button--info-trans {
	border: 1px solid #CF4B06;
	background: transparent;
	color: #282828;
}

.light-theme .a-button--info-trans:hover {
	background: #CF4B06;
	color: #ffffff;
}

.light-theme .a-button--light-trans {
	border: 1px solid #d8d8d8;
	background: transparent;
}

.light-theme .a-button--light-trans:hover {
	background: #d8d8d8;
	color: #282828;
}

.light-theme .a-button--dark-trans {
	border: 1px solid #0B0B0B;
	background: transparent;
	color: #0B0B0B !important;
}

.light-theme .a-button--dark-trans:hover {
	background: #0B0B0B;
	color: #ffffff !important;
}

.light-theme .a-quotation .a-quote-icon {
	fill: #14325f;
}

.light-theme .a-quotation:before, .light-theme .a-quotation:after {
	border-top: 0.5px solid #00CC36;
	border-bottom: 0.5px solid #00CC36;
}

.light-theme .m-alert {
	background: #CF4B06;
	color: #ffffff;
}

.light-theme .m-list-group .active.list-group-item {
	background: #ffffff;
	border-color: #d8d8d8;
}

.light-theme .m-list-group .list-group-item {
	background: #EFEFEF;
}

.light-theme .m-list-group .list-group-item:hover {
	background: #14325f;
	color: #ffffff;
}

.light-theme .m-list-group .list-group-item:hover h3 {
	color: #ffffff !important;
}

.light-theme .m-list-group .list-group-item:hover p {
	color: #ffffff;
}

.light-theme .m-list-group .list-group-item:hover small {
	color: #ffffff;
}

.light-theme .modal-header {
	border-bottom: 1px solid #e8e8e8;
}

.light-theme .close {
	color: #9b9b9b;
}

.light-theme .close:focus, .light-theme .close:hover {
	color: #9b9b9b;
}

.light-theme .m-lightbox figure {
	background: #14325f;
}

.light-theme .m-lightbox figcaption p {
	color: #ffffff;
}

.light-theme .m-scrollspy .list-group-item {
	border: 1px solid #d8d8d8;
	color: #14325f;
	background: #EFEFEF;
}

.light-theme .m-scrollspy .list-group-item.active {
	background: #ffffff;
	color: #14325f;
}

.light-theme .m-scrollspy a.list-group-item:hover {
	background: #14325f;
	color: #ffffff;
}

.light-theme .scrollspy-content-container {
	border-top: 1px solid #d8d8d8;
	border-bottom: 1px solid #d8d8d8;
	border-right: 1px solid #d8d8d8;
}

.light-theme .scrollspy-content::-webkit-scrollbar-track {
	-webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	border-radius: 10px;
	background-color: #e8e8e8;
}

.light-theme .scrollspy-content::-webkit-scrollbar {
	width: 12px;
	background-color: transparent;
}

.light-theme .scrollspy-content::-webkit-scrollbar-thumb {
	border-radius: 10px;
	-webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	background-color: #14325f;
}

.light-theme .tooltip.bs-tooltip-top .arrow::before, .light-theme .tooltip.bs-tooltip-auto[x-placement^="top"] .arrow::before {
	border-top-color: #EFEFEF;
}

.light-theme .tooltip-inner {
	background: #EFEFEF;
	color: #282828;
}

.light-theme .m-cta--blue {
	background: #003893;
	border-top: 5px solid #003893;
	border-bottom: 5px solid #003893;
}

.light-theme .m-cta--blue:hover {
	background: #14325f;
	border-top: 5px solid #14325f;
	border-bottom: 5px solid #00CC36;
}

.light-theme .m-cta--blue .has-border {
	border-bottom: 1px solid #ffffff;
}

.light-theme .page-link {
	color: #282828;
}

.light-theme .page-link:hover {
	background: #F6F6F6;
}

.light-theme span.fa.fa-angle-left, .light-theme span.fa.fa-angle-right, .light-theme span.fa.fa-angle-double-right, .light-theme span.fa.fa-angle-double-left {
	color: #9b9b9b;
}

.light-theme .page-link.active {
	color: #003893;
}

.light-theme .m-dropdown {
	display: block;
	width: 100%;
	position: relative;
	padding: 1rem 0;
}

.light-theme .m-dropdown ul {
	background: transparent;
	border-left: 1px solid #d8d8d8;
	border-right: 1px solid #d8d8d8;
	border-bottom: 1px solid #d8d8d8;
	border-top: 0;
}

.light-theme .m-dropdown ul li {
	display: block;
	float: left;
	width: 100%;
}

.light-theme .m-dropdown ul li a {
	color: #282828;
}

.light-theme .m-dropdown ul li a:focus {
	font-weight: bold;
	color: #14325f;
}

.light-theme .m-dropdown ul li a:active {
	font-weight: bold;
	color: #14325f;
}

.light-theme .m-dropdown ul li a:hover {
	background: transparent;
	color: #14325f;
	font-weight: bold;
}

.light-theme .m-dropdown .a-dropdown-menu {
	color: #282828;
	border-top: 1px solid #d8d8d8;
	border-left: 1px solid #d8d8d8;
	border-right: 1px solid #d8d8d8;
	border-bottom: 1px solid #d8d8d8;
	background: transparent;
}

.light-theme .m-dropdown .a-dropdown-menu:after {
	font-family: "Font Awesome 5 Free";
	font-weight: 900;
	content: "\f104";
	color: #9b9b9b;
}

.light-theme .m-dropdown.open ul {
	display: block;
	position: relative;
	top: 100%;
	padding: 1rem;
}

@media (min-width: 576px) {
	.light-theme .m-dropdown.open ul {
		position: relative;
	}
}

.light-theme .label-reveals {
	color: #ffffff !important;
}

.light-theme .a-input-text-label {
	color: #282828;
}

.light-theme .form-check label {
	color: #282828;
}

.light-theme .m-form .a-input-text:-webkit-autofill {
	-webkit-box-shadow: 0 0 0 1000px #ffffff inset;
	box-shadow: 0 0 0 1000px #ffffff inset;
}

.light-theme .m-form .a-input-text:focus {
	background-color: #ffffff;
}

.light-theme .m-form .a-input-text:focus + .a-input-text-label {
	border-bottom: 1px solid transparent;
	-webkit-box-shadow: inset 0 18px 0 1px #14325f;
	box-shadow: inset 0 18px 0 1px #14325f;
	color: #ffffff;
}

.light-theme .form-control {
	border: 1px solid #d8d8d8;
}

.light-theme .form-control + .input-group-addon:not(:first-child) {
	background: transparent;
}

.light-theme .input-group-item input[type="text"] {
	border: 1px solid #d8d8d8;
}

.light-theme .form-group input[type="text"], .light-theme .form-group input[type="email"], .light-theme .form-group input[type="number"], .light-theme .form-group select, .light-theme .form-group textarea {
	color: #282828;
	border: 1px solid #d8d8d8;
}

.light-theme .form-group input[type="checkbox"],
.light-theme .form-group input[type="radio"] {
	background: #ffffff;
}

.light-theme .form-group input[type="checkbox"] + label:before,
.light-theme .form-group input[type="radio"] + label:before,
.light-theme .form-group input[type="checkbox"]:hover + label:before,
.light-theme .form-group input[type="radio"]:hover + label:before {
	border-color: #282828;
	background: #ffffff;
}

.light-theme .form-group input[type="checkbox"] + label:before,
.light-theme .form-group input[type="radio"] + label:before {
	border: 2px solid #d8d8d8;
}

.light-theme .form-group input[type="checkbox"] + label:after,
.light-theme .form-group input[type="radio"] + label:after {
	background-color: #14325f;
}

.light-theme .form-group input[type="checkbox"]:checked + label:after,
.light-theme .form-group input[type="radio"]:checked + label:before {
	background-color: #ffffff;
}

.light-theme .form-group input[type="checkbox"]:checked + label:after {
	background-color: #14325f;
}

.light-theme .form-group input[type="checkbox"] + label:after {
	background-color: #14325f;
}

.light-theme .form-control::-ms-expand {
	background-color: transparent;
}

.light-theme .form-control:focus {
	color: #282828;
	background-color: #ffffff;
}

.light-theme .form-control::-webkit-input-placeholder {
	color: #282828;
}

.light-theme .form-control::-moz-placeholder {
	color: #282828;
}

.light-theme .form-control:-ms-input-placeholder {
	color: #282828;
}

.light-theme .form-control:-moz-placeholder {
	color: #282828;
}

.light-theme .form-control::-ms-input-placeholder {
	color: #282828;
}

.light-theme .form-control::placeholder {
	color: #282828;
}

.light-theme .form-control-textarea::-webkit-input-placeholder {
	color: #282828;
}

.light-theme .form-control-textarea::-moz-placeholder {
	color: #282828;
}

.light-theme .form-control-textarea:-ms-input-placeholder {
	color: #282828;
}

.light-theme .form-control-textarea:-moz-placeholder {
	color: #282828;
}

.light-theme .form-control-textarea::-ms-input-placeholder {
	color: #282828;
}

.light-theme .form-control-textarea::placeholder {
	color: #282828;
}

.light-theme .file-input > .label {
	color: #282828;
}

.light-theme .custom-select {
	color: #282828;
	background: #ffffff url('data:image/svg+xml;charset=utf8,<svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 952.38"><g id="khgtJn"><image id="khgtJn-2" data-name="khgtJn" xlink:href="data:image/png;base64,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"/></g><g id="_6geJrq" data-name="6geJrq"><image id="_6geJrq-2" data-name="6geJrq" width="512" height="512" transform="translate(0 440.38)" xlink:href="data:image/png;base64,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"/></g></svg>') no-repeat center right !important;
		background-size: 2.8rem 2rem !important;
		border: 1px solid #282828;
		}

.light-theme .custom-select:focus::-ms-value {
	color: #282828;
	background-color: #ffffff;
}

.light-theme .custom-select:disabled {
	color: #EFEFEF;
	background-color: transparent;
}

.light-theme .localist-widget-hl .event-card {
	background: #F6F6F6;
}

.light-theme .localist-widget-hl .event-card p {
	font-size: 0.875rem;
}

.light-theme .localist-widget-hl .event-card:hover, .light-theme .localist-widget-hl .event-card:active {
	border-bottom: 4px solid #00CC36;
}

.light-theme .localist-widget-hl .event-details {
	background: rgba(20, 50, 95, 0.8);
}

.light-theme .localist-widget-hl .event-list .event-overview .content {
	border: 1px solid #F6F6F6;
	background: #F6F6F6;
}

.light-theme .event-details dd {
	color: #ffffff;
}

.light-theme .localist-widget-hl .event-card .content p {
	color: #282828;
}

.light-theme .localist-widget-hl .event-card .content:before {
	background: #F6F6F6;
}

.light-theme .localist-embed .prev:before, .light-theme .localist-embed .next:before {
	color: #9b9b9b;
}

.light-theme .localist-embed .prev:before:active, .light-theme .localist-embed .next:before:active {
	border: 0px !important;
}

.light-theme #campus-life h3:hover {
	text-decoration: underline;
}

.light-theme #campus-life .grid-content h2, .light-theme #campus-life h3, .light-theme #campus-life h4, .light-theme #campus-life h5, .light-theme #campus-life h6, .light-theme #campus-life .grid-content p {
	color: #ffffff;
}

.light-theme #campus-life .grid-image--solid {
	background: #F6F6F6;
}

.light-theme #campus-life .grid-image--solid > .grid-content h2, .light-theme #campus-life .grid-image--solid > .grid-content h3, .light-theme #campus-life .grid-image--solid > .grid-content h4, .light-theme #campus-life .grid-image--solid > .grid-content h5, .light-theme #campus-life .grid-image--solid > .grid-content h6 {
	color: #14325f;
}

.light-theme #campus-life .grid-image--solid > .grid-content p {
	color: #282828;
}

.light-theme #search-table_wrapper {
	border: 1px solid #d8d8d8;
	background: #F6F6F6;
}

.light-theme .dataTables_filter label {
	color: #282828;
}

.light-theme .dataTables_length label {
	color: #282828;
}

.light-theme .dataTables_length select {
	background: #EFEFEF;
	color: #282828;
	border: 1px solid #d8d8d8;
}

.light-theme .dataTables_wrapper .dataTables_filter input {
	color: #282828;
	border: 1px solid #d8d8d8;
	background: #ffffff;
}

.light-theme #search-table_info {
	color: #282828;
}

.light-theme .paginate_button.current {
	background: #F6F6F6 !important;
}

.light-theme .dataTables_wrapper .dataTables_paginate .paginate_button.current, .light-theme .dataTables_wrapper .dataTables_paginate .paginate_button.current:hover {
	color: #282828 !important;
}

.light-theme #search-table_previous, .light-theme #search-table_next {
	border: 1px solid #14325f;
	background: transparent;
	color: #282828;
}

.light-theme #search-table_previous:hover, .light-theme #search-table_next:hover {
	background: #14325f;
	color: #ffffff;
}

.light-theme .dataTables_wrapper .dataTables_paginate .paginate_button.disabled, .light-theme .dataTables_wrapper .dataTables_paginate .paginate_button.disabled:hover, .light-theme .dataTables_wrapper .dataTables_paginate .paginate_button.disabled:active {
	color: #282828 !important;
}

.light-theme .table.dataTable.display tbody tr.odd > .sorting_1 {
	background-color: #EFEFEF;
}

.light-theme .table.dataTable.display tbody tr.even > .sorting_1 {
	background-color: #EFEFEF;
}

.light-theme table.dataTable.hover tbody tr:hover, .light-theme table.dataTable.display tbody tr:hover {
	background-color: #F6F6F6;
}

.light-theme table.dataTable.hover tbody tr:hover.selected, .light-theme table.dataTable.display tbody tr:hover.selected {
	background-color: #F6F6F6;
}

.light-theme #search-table_wrapper .table-bordered th, .light-theme .table-bordered td {
	border: 1px solid #d8d8d8;
}

.light-theme table.dataTable.no-footer {
	border-bottom: 1px solid #d8d8d8;
}

.light-theme .j-loading {
	border: 4px solid #14325F !important;
}

.light-theme .j-loading:before {
	background-color: #14325F;
}

.light-theme .juicer-feed {
	background-color: #FFF !important;
}

.light-theme .juicer-feed a {
	color: #0054A0;
}

.light-theme .juicer-feed .j-meta a {
	color: #0054A0;
}

.light-theme .juicer-feed a, .light-theme .j-poster h3 {
	color: #14325F;
}

.light-theme .juicer-feed a:hover {
	color: #003893 !important;
}

.light-theme .juicer-feed li.feed-item {
	background-color: #F6F6F6 !important;
}

.light-theme .juicer-feed li.feed-item:before {
	content: '' !important;
}

.light-theme .juicer-feed.modern li.feed-item .j-message a {
	color: #0054A0;
}

.light-theme .juicer-feed .j-message, .light-theme .juicer-feed .j-message p {
	color: #14325F !important;
	font-size: 1em;
	font-weight: 500;
}

.light-theme .juicer-button, .light-theme .j-paginate {
	-moz-transition: all 0.2s ease-in-out;
	-o-transition: all 0.2s ease-in-out;
	-webkit-transition: all 0.2s ease-in-out;
	transition: all 0.2s ease-in-out;
	display: inline-block;
	border: 2px solid #14325F !important;
	font-size: 12px;
	font-weight: bold;
	letter-spacing: 0.5px;
	color: #14325F !important;
	text-align: center;
	padding: 12px 0 10px;
	cursor: pointer;
	background-color: transparent;
	width: 150px;
	display: block;
	text-transform: uppercase;
}

.light-theme .j-display-filters {
	padding-left: 0px !important;
	-webkit-padding-start: 0px !important;
}

.light-theme .juicer-feed .j-display-filters {
	text-align: left;
	margin: 0px 0px 15px;
	font-weight: 700;
	font-size: 18px;
	text-transform: uppercase;
	color: #14325F;
}

.light-theme .juicer-feed .j-display-filters li:before {
	margin-right: 6px;
	line-height: 11px;
	font-size: 50px;
	font-weight: 100;
	position: relative;
}

.light-theme .juicer-feed .j-display-filters li {
	display: inline-block;
	margin: 0px 5px 0px 0px !important;
	padding: 25px 0px 5px 5px;
	cursor: pointer;
	border-bottom: 1px solid #FFF;
}

.light-theme .juicer-feed .j-display-filters li.all:before {
	font-size: 46px;
	bottom: 15px !important;
}

.light-theme .juicer-feed .j-display-filters li.all {
	color: #14325F;
	background: #FFF !important;
	color: white;
	margin-top: 10px;
	margin-left: -0px;
}

.light-theme .all:before {
	content: "\f021" !important;
	font-family: 'Font Awesome 5 Free' !important;
	font-weight: 900;
}

.light-theme .juicer-feed .j-display-filters .all:before {
	content: "\f021" !important;
	font-family: 'Font Awesome 5 Free' !important;
	font-weight: 900;
}

.light-theme .juicer-feed .j-display-filters li.all.highlight, .light-theme .juicer-feed .j-display-filters li.all {
	background: #FFF !important;
	color: #14325F;
	margin-top: 20px;
	margin-left: -0px;
}

.light-theme .juicer-feed .j-display-filters li.all.highlight, .light-theme .juicer-feed .j-display-filters li.all:hover {
	background: #FFF !important;
	color: #0054A0;
	border-bottom: 1px solid #CF4B00 !important;
	margin-top: 30px;
}

.light-theme .j-facebook-text:before {
	color: #14325F;
}


.light-theme .juicer-feed .j-facebook:before {
	content: "\f082" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .j-facebook:before {
	content: "\f082" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .j-facebook .j-facebook-hover .j-social-icon:before {
	content: "\f082" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .juicer-feed .j-facebook-hover.highlight:before, .light-theme .juicer-feed .j-facebook-hover:before {
	color: #14325F;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-facebook-hover.highlight:before, .light-theme .juicer-feed .j-facebook-hover:hover:before {
	color: #0054A0;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-facebook-hover.highlight, .light-theme .juicer-feed .j-facebook-hover:hover {
	background: #FFF !important;
	color: #FFF;
	border-bottom: 1px solid #CF4B00 !important;
}

.light-theme .j-facebook .j-social:before {
	content: "\f39e" !important;
	font-family: "Font Awesome 5 Brands" !important;
	font-weight: 400;
}

.light-theme .j-instagram-text:before {
	color: #14325F;
}

.light-theme .juicer-feed .j-instagram:before {
	content: "\f16d" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.light-theme .j-instagram:before {
	content: "\f16d" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.light-theme .j-instagram .j-instagram-hover .j-social-icon:before {
	content: "\f16d" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .juicer-feed .j-instagram-hover.highlight:before, .light-theme .juicer-feed .j-instagram-hover:before {
	color: #14325F;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-instagram-hover.highlight:before, .light-theme .juicer-feed .j-instagram-hover:hover:before {
	color: #0054A0;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-instagram-hover.highlight, .light-theme .juicer-feed .j-instagram-hover:hover {
	background: #FFF !important;
	color: #FFF;
	border-bottom: 1px solid #CF4B00 !important;
}

.light-theme .j-instagram .j-social:before {
	content: "\f16d" !important;
}

.j-x-twitter {
	display: none !important;
}

.light-theme .j-twitter-text:before {
	color: #14325F;
}

.light-theme .juicer-feed .j-twitter:before {
	content: "\f081" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .j-twitter:before {
	content: "\f081" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .j-twitter .j-twitter-hover .j-social-icon:before {
	content: "\f081" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .juicer-feed .j-twitter-hover.highlight:before, .light-theme .juicer-feed .j-twitter-hover:before {
	color: #14325F;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-twitter-hover.highlight:before, .light-theme .juicer-feed .j-twitter-hover:hover:before {
	color: #0054A0;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-twitter-hover.highlight, .light-theme .juicer-feed .j-twitter-hover:hover {
	background: #FFF !important;
	color: #FFF;
	border-bottom: 1px solid #CF4B00 !important;
}

.light-theme .j-twitter .j-social:before {
	content: "\f099" !important;
}

.light-theme .juicer-feed .j-twitter-post-icon:before {
	color: #0054A0 !important;
}

.light-theme .juicer-feed .j-twitter-post-icon:hover:before {
	color: #003893 !important;
}

.light-theme .j-youtube-text:before {
	color: #14325F;
}

.light-theme .juicer-feed .j-youtube:before {
	content: "\f431" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .j-youtube:before {
	content: "\f431" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .j-youtube .j-youtube-hover .j-social-icon:before {
	content: "\f431" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.light-theme .juicer-feed .j-youtube-hover.highlight:before, .light-theme .juicer-feed .j-youtube-hover:before {
	color: #14325F;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-youtube-hover.highlight:before, .light-theme .juicer-feed .j-youtube-hover:hover:before {
	color: #0054A0;
	padding: 5px 5px;
}

.light-theme .juicer-feed .j-youtube-hover.highlight, .light-theme .juicer-feed .j-youtube-hover:hover {
	background: #FFF !important;
	color: #FFF;
	border-bottom: 1px solid #CF4B00 !important;
}

.light-theme .j-youtube .j-social:before {
	content: "\f167" !important;
}

.light-theme .j-poster .j-date {
	float: right;
	font-size: 14px;
	margin-top: 4px;
	color: #14325F;
}

.light-theme .juicer-feed .j-meta li {
	display: inline-block;
	margin: 0 10px 0 0;
	padding: 0;
	background-image: none;
	border: none;
	font-size: 1em;
	font-weight: 500;
	height: auto;
	width: auto;
}

.light-theme .juicer-feed .j-meta a.j-social {
	font-size: 1.8em;
	font-weight: 100;
	line-height: 1;
	float: none;
	margin: 0;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-facebook {
	color: #0054A0;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-facebook:hover {
	color: #003893;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-instagram {
	color: #0054A0;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-instagram:hover {
	color: #003893;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-twitter {
	color: #0054A0;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-twitter:hover {
	color: #003893;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-youtube {
	color: #0054A0;
}

.light-theme .juicer-feed.colored-icons .j-meta a.j-social.j-youtube:hover {
	color: #003893;
}

.light-theme .j-poster {
	overflow: hidden;
	margin: 0 0 0 0;
	height: 30px;
}

.light-theme .j-overlay {
	position: fixed;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	background: rgba(0, 0, 0, 0.6);
	padding-top: 50px;
	z-index: 99999999;
	outline: none;
}

.light-theme .j-message a {
	color: #0054A0;
}

.light-theme .j-message a:hover {
	color: #003893;
}

.light-theme .j-overlay .j-overlay-content {
	margin: 0 auto;
	background: #FFF;
	position: relative;
	color: #3A3A3A;
	font-weight: normal;
	max-height: 90%;
	overflow-y: auto;
	outline: none;
	max-width: 980px;
}

.light-theme .j-post-overlay.juicer-feed {
	overflow: hidden;
	margin: 0 !important;
}

.light-theme .j-post-overlay.juicer-feed a.juicer-button {
	float: left;
	-moz-transition: all 0.2s ease-in-out;
	-o-transition: all 0.2s ease-in-out;
	-webkit-transition: all 0.2s ease-in-out;
	transition: all 0.2s ease-in-out;
	display: inline-block;
	border: 2px solid #14325F;
	font-size: 12px;
	font-weight: bold;
	letter-spacing: 0.5px;
	color: #14325F;
	text-align: center;
	padding: 12px 0 10px;
	cursor: pointer;
	background-color: transparent;
	width: 200px;
}

.light-theme .j-post-overlay.juicer-feed a.juicer-button:hover {
	background: #14325F;
	color: #FFF !important;
}

.light-theme .j-post-overlay.juicer-feed a.juicer-button:hover::before {
	background: #14325F;
	color: #FFF !important;
}

.light-theme .j-post-overlay.juicer-feed a.juicer-button:before {
	font-family: 'Font Awesome 5 Brands', Helvetica, Arial, sans-serif;
	font-size: 1rem;
	position: relative;
	left: -10px;
	top: 1px;
	font-weight: normal;
	color: #14325F;
}

.light-theme .juicer-feed .j-email::before {
	content: "";
	font-family: 'Font Awesome 5 Free' !important;
	font-weight: 900;
}

.light-theme .j-post-overlay.juicer-feed ul.j-share a:hover {
	background: #FFF;
	color: #FFF !important;
}

.light-theme .j-post-overlay.juicer-feed ul.j-share a:hover::before {
	background: #FFF;
	color: #003893 !important;
}

.light-theme .j-post-overlay.juicer-feed ul.j-share a:before {
	font-family: 'Font Awesome 5 Brands', Helvetica, Arial, sans-serif;
	font-size: 16px;
	color: #14325F;
	position: relative;
	font-weight: 400;
	top: 1px;
}

.light-theme a.j-facebook.share {
	background: #FFF;
	margin-right: 1px;
}

.light-theme a.j-facebook.share:hover {
	border-bottom: solid 1px #CF4B00;
	margin-right: 1px;
}

.light-theme a.j-twitter.share {
	background: #FFF;
	margin-right: 1px;
}

.light-theme a.j-twitter.share:hover {
	border-bottom: solid 1px #CF4B00;
	margin-right: 1px;
}

.light-theme a.j-googleplus.share {
	background: #FFF;
	margin-right: 1px;
}

.light-theme a.j-googleplus.share:hover {
	border-bottom: solid 1px #CF4B00;
	margin-right: 1px;
}

.light-theme .j-post-overlay.juicer-feed ul.j-share a.j-pinterest.share {
	display: none;
}

.light-theme a.j-pinterest.share {
	background: #FFF;
	margin-right: 1px;
}

.light-theme a.j-pinterest.share:hover {
	border-bottom: solid 1px #CF4B00;
	margin-right: 1px;
}

.light-theme a.j-linkedin.share {
	background: #FFF;
	margin-right: 1px;
}

.light-theme a.j-linkedin.share:hover {
	border-bottom: solid 1px #CF4B00;
	margin-right: 1px;
}

.light-theme a.j-email.share {
	background: #FFF;
}

.light-theme a.j-email.share:hover {
	border-bottom: solid 1px #CF4B00;
}

.light-theme .j-post-overlay.juicer-feed .j-navigate a.j-previous, .light-theme .j-post-overlay.juicer-feed .j-navigate a.j-next {
	cursor: pointer;
	color: #0054A0;
}

.light-theme a.juicer-button.j-facebook:before {
	content: "\f09a" !important;
}

.light-theme .juicer-feed, .light-theme a.j-facebook.share:before {
	content: "\f09a" !important;
}

.light-theme a.juicer-button.j-twitter:before {
	content: "\f099" !important;
}

.light-theme .juicer-feed, .light-theme a.j-twitter.share:before {
	content: "\f099" !important;
}

@media only screen and (max-width: 1270px) {
	.light-theme ul.j-share {
		float: right !important;
		display: block;
		-webkit-padding-start: 0px !important;
	}
}

@media (max-width: 1190px) {
	.light-theme ul.j-share {
		float: left !important;
		display: block;
		-webkit-padding-start: 0px !important;
	}
}

.light-theme .j-overlay .j-close {
	padding: 10px;
	top: 10px;
}

.light-theme .j-overlay .j-close:hover {
	padding: 10px;
	top: 10px;
}

/* *** Accordion UI States and Icons ***  */
.light-theme .ui-accordion .ui-state-default {
	background: #EFEFEF;
	color: #14325f;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-accordion .ui-state-default:hover {
	background: #14325f !important;
	color: #ffffff !important;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-accordion .ui-state-focus {
	background: #14325f;
	color: white;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-accordion .ui-state-active {
	background: white;
	color: #14325f;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-accordion .ui-state-hover {
	background: #14325f;
	color: white;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-accordion .ui-state-default .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_14325f_256x240.png);
}
.light-theme .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.light-theme .ui-accordion .ui-state-focus .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.light-theme .ui-accordion .ui-state-active .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_14325f_256x240.png);
}
.light-theme .ui-accordion-header-active .ui-state-focus .ui-icon,
.light-theme .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}

/* *** Nested Accordions in Tab Set UI States and Icons *** */
.light-theme .ui-tabs .ui-accordion .ui-state-default {
	background: #EFEFEF;
	color: #14325f;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-tabs .ui-accordion .ui-state-focus {
	background: #14325f;
	color: white;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-tabs .ui-accordion .ui-state-active {
	background: white;
	color: #14325f;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-tabs .ui-accordion .ui-state-hover {
	background: #14325f;
	color: white;
	border-bottom: 1px solid #D8D8D8;
}
.light-theme .ui-tabs .ui-accordion .ui-state-default .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_14325f_256x240.png);
}
.light-theme .ui-tabs .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.light-theme .ui-tabs .ui-accordion .ui-state-focus .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.light-theme .ui-tabs .ui-accordion .ui-state-active .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_14325f_256x240.png);
}
.light-theme .ui-tabs .ui-accordion-header-active .ui-state-focus .ui-icon,
.light-theme .ui-tabs .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.light-theme  [id^="tabs"] [id^="accordion-"] .ui-widget-content {
	border: 1px solid #D8D8D8;
	background: #ffffff;
}
.light-theme [id*="tabs"] [id^="accordion-"] .ui-state-default, .light-theme [id*="tabs"] [id^="accordion-"] .ui-widget-content .ui-state-default {
	/*   border-top: 1px solid #D8D8D8 !important; */
	border-left: 1px solid #D8D8D8 !important;
	border-right: 1px solid #D8D8D8 !important;
	border-bottom: 0px solid transparent;
}
.light-theme [id*="tabs"] [id^="accordion-"] .ui-state-hover, .light-theme  [id*="tabs"] [id^="accordion-"] .ui-widget-content .ui-state-hover {
	border-top: 1px solid #D8D8D8 !important;
	border-bottom: 1px solid #ffffff;
}

.light-theme .ui-state-active, .light-theme .ui-widget-content .ui-state-active, .light-theme .ui-widget-header .ui-state-active {
	background: #ffffff !important;
}

div[id|="tabs"] .light-theme .ui-state-hover, .light-theme ui-widget-content .ui-state-hover, .light-theme  .ui-widget-header .ui-state-hover {
	background-color: #EFEFEF !important;
}

.light-theme [id*="tabs"] .ui-widget-header .ui-state-hover {
	border-top: 1px solid #D8D8D8 !important;
	border-left: 1px solid #D8D8D8 !important;
	border-right: 1px solid #D8D8D8 !important;
}

.light-theme [id*="tabs"] [id|="accordion-"] .ui-state-hover, .light-theme .ui-widget-content [id*="tabs"] [id|="accordion-"] .ui-state-hover, .light-theme .ui-widget-header .ui-state-active {
	color: #ffffff !important;
}

.light-theme [id*="tabs"] [id|="accordion-"] .ui-state-hover,
.ui-widget-content [id*="tabs"] [id|="accordion-"] .ui-state-hover,
.ui-widget-header [id*="tabs"] [id|="accordion-"] .ui-state-hover {
	border-top: 1px solid #D8D8D8 !important;
	border-left: 1px solid #D8D8D8 !important;
	border-right: 1px solid #D8D8D8 !important;
	background: #EFEFEF !important;
	font-weight: bold;
	/*     color: #14325f; */
}

.light-theme [id*="tabs"] [id^="accordion-"]  .ui-state-active {
	border-top: 1px solid #D8D8D8 !important;
	border-left: 1px solid #D8D8D8 !important;
	border-right: 1px solid #D8D8D8 !important;
}

.light-theme [id*="tabs"] [id^="accordion-"] .ui-widget-header {
	border-top: 0px solid;
	border-left: 0px solid;
	border-right: 0px solid;
	border-bottom: 1px solid #d8d8d8;
	background: #ffffff;
	font-weight: bold;
}
.light-theme #tabs li.ui-tabs-tab.ui-corner-top.ui-state-default.ui-tab.ui-tabs-active.ui-state-active {
	padding: 0px;
	margin-bottom: -2px !important;
	border-bottom: 1px solid #ffffff !important;
}
/* jQuery UI - a */
.light-theme .ui-widget-content a {
	color: #003893;
}

.light-theme [id^="tabs"] .ui-widget-content {
	border-top: 1px solid #d8d8d8;
	background: #ffffff !important;
	/* color: #fff !important; */
}

.light-theme [id*="tabs"] [id^="accordion-"] .ui-state-active a, .light-theme [id*="tabs"] [id^="accordion-"] .ui-state-hover a:link {
	color: #14325f !important;
}

.light-theme [id*="tabs"] [id^="accordion-"] .ui-state-hover a:link {
	color: #ffffff !important;
}

/* ================================
Google CSE - Light Theme
================================ */
.light-theme .search-box {
	width: 98%;
	max-width: 450px;
	margin-left: 5px;
}

.light-theme .search-results {
	background-color: #282828;
	width: 100%;
	max-width: 800px;
}

.light-theme .gs-snippet {
	margin-top: 1px;
	padding-left: 8px;
}

/* ================================
Search Results - Outer Border
================================ */
.light-theme .gsc-control-cse {
	border-color: #FFF !important;
	padding-left: 5px !important;
	background-color: #FFF;
}

/* ================================
Search Input Field
================================ */
.light-theme input.gsc-input {
	/*	height: 30px !important; */
	width: 100% !important;
	-webkit-appearance: none;
}

.light-theme input#gsc-i-id1.gsc-input {
	background: none !important;
	text-indent: 0 !important;
}

.light-theme table.gsc-search-box td.gsc-input {
	padding-right: 0 !important;
}

.light-theme .gsc-input-box {
	border: 1px solid #D9D9D9;
	background: #fff;
	height: 31px !important;
}

.light-theme .gsc-input-box-focus {
	border: 1px solid #66afe9 !important;
}

/* ================================
Search Clear X
================================ */
.light-theme .gsst_a {
	padding-top: 5.5px;
}

.light-theme .gsst_a .gscb_a {
	color: #72849F !important;
	cursor: pointer;
	padding-top: 3px;
}

.light-theme .gsst_a:hover .gscb_a {
	color: #14325F !important;
	cursor: pointer;
}

/* ================================
Search Button 
================================ */
.light-theme .gsc-clear-button {
	display: none;
}

.light-theme .gsc-search-button {
	font: 700 13px/16px arial,helvetica,sans-serif !important;
	color: #FFF !important;
	background-color: #14325F !important;
	border: 1px solid #14325F !important;
	border-radius: 0 !important;
	-webkit-appearance: none;
}

.light-theme .gsc-search-button:hover {
	font: 700 13px/16px arial,helvetica,sans-serif !important;
	color: #FFF !important;
	background-color: #003893 !important;
	border: 1px solid #003893 !important;
	border-radius: 0 !important;
	-webkit-appearance: none;
}

.light-theme input.gsc-search-button:hover {
	background: #003893 !important;
	cursor: pointer;
	border: 0 none;
}

.light-theme .gsc-search-button-v2 {
	border-color: #14325F !important;
	background-color: #14325F !important;
	background-image: -webkit-gradient(linear,left top,left bottom,from(#14325F),to(#14325F))!important;
	background-image: -webkit-linear-gradient(top,#14325F,#14325F)!important;
}

.light-theme .gsc-search-button-v2:hover {
	border-color: #003893 !important;
	background-color: #003893 !important;
	background-image: -webkit-gradient(linear,left top,left bottom,from(#003893),to(#003893))!important;
	background-image: -webkit-linear-gradient(top,#003893,#003893)!important;
}

/* ================================
Results Filters
================================ */
.light-theme .gsc-tabsArea {
	font-size: 18px !important;
	border-bottom: 1px solid #72849F !important;
	height: 30px !important;
}

.light-theme .gsc-tabHeader {
	padding-bottom: 1px !important;
	padding-left: 16px !important;
	padding-right: 16px !important;
	padding-top: 0px !important;
	margin-right: 2px;
	margin-top: 2px !important;
	height: 28px !important;
	text-align: center !important;
}

.light-theme .gsc-tabHeader.gsc-tabhActive {
	font-weight: 600;
	color: #14325F !important;
	background-color: #FFF;
	border: 1px solid;
	border-top: 1px solid !important;
	border-color: #72849F !important;
	border-top-color: none !important;
	border-bottom-color: #FFF !important;
	margin-top: 1px !important;
}

.light-theme .gsc-tabHeader.gsc-tabhInactive {
	font-weight: 600;
	color: #FFF !important;
	background-color: #14325F !important;
	border: 1px solid;
	border-color: #72849F;
	border-bottom: 1px solid #FFF;
	text-align: center !important;
}

.light-theme .gsc-tabHeader.gsc-tabhInactive:hover {
	font-weight: 600;
	color: #14325F !important;
	background-color: #EFEFEF !important;
	border: 1px solid;
	border-color: #72849F !important;
	border-top: 1px solid #72849F;
	border-bottom: none;
}

/* ================================
Tab Spacer
================================ */
.light-theme .gsc-tabsArea .gs-spacer {
	display: inline-block !important;
	width: 5px;
}

/* ================================
Spelling
================================ */
.light-theme .gs-spelling {
	color: #333;
	padding-left: 7px;
	padding-right: 7px;
}

.light-theme .gs-spelling a {
	color: #0054A0 !important;
	cursor: pointer;
	text-decoration: underline;
}

.light-theme .gs-spelling a:hover {
	color: #003893 !important;
	cursor: pointer;
	text-decoration: underline;
}

/* ================================	
Results
================================ */
.light-theme .gsc-control-cse .gsc-table-result {
	width: 100%;
	font-family: Helvetica,Arial,sans-serif !important;
	font-size: 14px !important;
	line-height: 1.5 !important;
}

.light-theme .gsc-result-info {
	text-align: left;
	color: #333;
	font-size: 14px;
	padding-left: 8px;
	margin: 10px 0 10px 0;
}

.light-theme .gs-result .gs-title, .light-theme .gs-result .gs-title * {
	color: #14325F !important;
	text-decoration: underline;
}

.light-theme .gsc-control-cse .gs-result .gs-title a:hover {
	text-decoration:underline;
	color: #003893 !important;
}

.light-theme .gsc-control-cse .gs-result .gs-title,.gsc-control-cse .gs-result .gs-title * {
	font-family: Helvetica,Arial,sans-serif !important;
	font-size: 18px !important;
	line-height: 22px;
	padding-bottom: 5px;
	text-decoration: none;
	font-weight: 700;
	color: #14325F !important;
	margin-bottom: 5px;
}

.light-theme .gsc-webResult.gsc-result {
	padding: 15px !important;
	border-left: 8px solid #fff !important;
	margin: 0 !important;
	border-bottom: 1px solid #ccc !important;
	border-top: 1px solid transparent;
	border-right: 1px solid transparent;
	margin-top: -2px !important;
	margin-bottom: -2px !important;
}

.light-theme .gsc-webResult.gsc-result:hover {
	border-left: 8px solid #003893 !important;
	border-bottom: 1px solid #ccc !important;
	border-top: 1px solid transparent !important;
	border-right: 1px solid #fff !important;
	margin-bottom: -2px !important;
	margin-top: -2px !important;
}

.light-theme .gsc-webResult.gsc-result:hover .gs-title * {
	color: #003893 !important;
}

.light-theme .gs-result .gs-visibleUrl {
	color: #0054A0 !important;
	text-decoration: none;
	font-size: 1rem;
}

.light-theme .gs-bidi-start-align.gs-snippet {
	line-height: 1.5;
}

.light-theme .gsc-preview-reviews, .light-theme .gsc-control-cse .gs-snippet, .light-theme .gsc-control-cse .gs-promotion em, .light-theme .gsc-control-cse .gs-snippet, .light-theme .gsc-control-cse .gs-promotion em {
	color: #333 !important;
	font-size: 1rem;
}

.light-theme span.gs-fileFormat {
	color: #fff;
	font-size: 12px;
	padding-left: 8px;
}

.light-theme .gs-webResult div.gs-per-result-labels a.gs-label {
	text-decoration: underline;
	cursor: pointer;
	padding: 3px;
	color: #003893;
	font-size: 14px;
}

.light-theme .gsc-above-wrapper-area {
	/*     border-bottom: 1px solid #E9E9E9; */
	padding: 5px 0 5px 0;
}

/* ================================
Hide thumbnail images in results
================================ */
.light-theme .gsc-thumbnail {
	display: none;
}

/* ================================
Pagination
================================ */
.light-theme .gsc-results .gsc-cursor-box {
	margin-bottom: 10px;
	padding-top: 15px;
}

.light-theme .gsc-results .gsc-cursor-box .gsc-cursor-page {
	border: 1px solid #72849F !important;
	background-color: #14325F;
	padding: 8px !important;
	color: #FFF !important;
	text-decoration: none !important;
	margin-right: 10px;
	display: inline;
	font-size: 15px;
}

.light-theme .gsc-results .gsc-cursor-box .gsc-cursor-page:hover {
	border: 1px solid #72849F;
	background-color: #EFEFEF;
	padding: 5px;
	color: #14325F !important;
	text-decoration: none;
}

.light-theme .gsc-results .gsc-cursor-box .gsc-cursor-current-page {
	cursor: default;
	color: #14325F !important;
	background-color: #EFEFEF !important;
	font-weight: 700;
	text-decoration: underline !important;
}

.light-theme .gs-per-result-labels {
	padding-left: 8px;
}

/* ================================
No Results
================================ */
.light-theme .gs-no-results-result .gs-snippet,.gs-error-result .gs-snippet {
	padding: 5px;
	margin: 5px;
	border: 1px solid #72849F !important;
	background-color: #EFEFEF !important;
	color: #14325F !important;
	font-weight: 700;
}

/* ================================
Branding
================================ */
.light-theme .gcsc-branding {
	display: none !important;
}

.light-theme .gssb_a > div > img {
	display: none;
}

.light-theme .gssb_a > div > span {
	display: none;
}

/* ===============================
Bootstrap Light Theme Overrides
================================== */

.light-theme caption {
	padding-top: 0.75rem;
	padding-bottom: 0.75rem;
	color: #212529;
	text-align: left;
	caption-side: top;
}


/* Remove search input X */
.light-theme input[type="search"]::-webkit-search-decoration,
.light-theme input[type="search"]::-webkit-search-cancel-button,
.light-theme input[type="search"]::-webkit-search-results-button,
.light-theme input[type="search"]::-webkit-search-results-decoration { 
	display: none;
}

/* =========================
END LIGHT THEME CSS
============================ */

/*
*** DARK THEME
*/
.dark-theme {
	background: #282828;
	/*
	** Small Help Text for Forms
	*/
	/*
	*** SUBNAV DARK THEME
	*/
	/*
	*** ACCORDION DARK THEME MOLECULES
	*/
	/*
	*** TABLE DARK THEME MOLECULES
	*/
	/*
	*** jQuery TABS DARK THEME MOLECULES ***
	*/
	/**
	** Landscape Card CTAs Molecules
	**/
	/*
	*** Vertical Card CTAs Molecules
	*/
	/*
	*** Home Tabs to Accordion Organisms Dark Theme
	*/
	/*
	*** HOME CARDS ORGANISMS ***
	*/
	/*
	*** FAST FACTS ORGANISMS
	*/
	/*
	*** EVENTS ORGANISMS
	*/
	/*
	*** FOOTER MIDDLE NO BACKGROUND IMAGE
	*/
	/*
	*** Back To Top Molecules
	*/
	/*
	*** Right Sidebar Card Molecules
	*/
	/*
	*** Slider Organism
	*/
	/*
	*** Base Button Dark Theme Atoms
	*/
	/*
	*** Light Box Molecules
	*/
	/*
	*** Scrollspy Dark Theme Molecules
	*/
	/*
	*** Tooltip Dark Theme Mmolecules
	*/
	/*
	*** Blue CTA Light Theme Molecule
	*/
	/*
	*** Pagination Molecule Dark Theme
	*/
	/*
	*** Custom Dropdown Dark Theme Molecule
	*/
	/*
	*** Form Dark Theme Molecules
	*/
	/*
	*** Home Page Events - What's Happening At WVC Dark Theme Styles - Localist Calendar
	*/
	/*
	*** Home Page Campus Life Section Dark Theme
	*/
	/*
	*** TABLE MOLECULES  DARK THEME***
	*/
	/* ====================================
	JUICER - DARK THEME - Overrides

	version: 1.01
	last modified: 2018-03-02
	author: D.Niemann
	email: wv.webmaster@westvalley.edu
	website: westvalley.edu

	Versions:
	1.00: Initial
	1.01: Fix .j-close for .j-overloay modal close - Ln 544 - remove background-size add top property
	1.02: Properties for .j-twiiter-post-icon:before - Ln 302
	======================================= */
	/* =====================
	FEED STYLES
	======================= */
	/* CARD BACKGROUND */
	/* =====================
	FILTERS STYLES
	======================= */
	/* =====================
	FILTER - ALL STYLES
	======================== */
	/* ==========================
	FILTER - FACEBOOK STYLES
	============================= */
	/* ===========================
	FILTER - INSTAGRAM STYLES
	============================== */
	/* =========================
	FILTER - TWITTER STYLES
	============================ */
	/* =========================
	FILTER - YOUTUBE STYLES
	============================ */
	/* =====================
	POSTER FEED STYLES
	======================== */
	/* SOCIAL ICON - LINK ON POSTER CARD */
	/* =============================
	POPUP POSTER OVERLAY STYLES
	================================ */
	/*======================================
	GLOBAL FIXES - POPUP OVERLAY
	======================================== */
}

.dark-theme #moon-button, .dark-theme #mobile-moon-button, .dark-theme #tablet-moon-button {
	background-image: url("/_resources/img/moon-green.svg");
	background-size: contain;
}

.dark-theme #subnav-aside .top-level-menu-item:hover {
	border-left: 4px solid #7ABFFF;
}

.dark-theme #subnav-aside .top-level-menu-item.list-item-open {
	border-left: 4px solid #7ABFFF;
}

.dark-theme .m-card--link:focus .m-card--homecustom, .dark-theme .m-card--link:focus .m-card--vertical, .dark-theme .m-card--link:focus .m-card--horizontal, .dark-theme .m-cta--link:focus .m-cta--blue {
	border-bottom: 4px solid #00CC36;
}

.dark-theme #fileHelp {
	color: #ffffff !important;
}

.dark-theme html, .dark-theme main, .dark-theme aside {
	background: #282828;
	color: #ffffff;
	-webkit-transition: all 0ms ease;
	-o-transition: all 0ms ease;
	-moz-transition: all 0ms ease;
	transition: all 0ms ease;
}


.dark-theme h1, .dark-theme h2, .dark-theme h3, .dark-theme h4, .dark-theme h5, .dark-theme h6 {
	color: #ffffff;
}

.dark-theme .has-border {
	border-bottom: 1px solid #ffffff;
}

.dark-theme .heading-link--has-border:hover, .dark-theme .heading-link--has-border:active {
	text-decoration: underline;
	border-bottom: 0;
	color: #ffffff;
}

.dark-theme h3 {
	color: #ffffff;
}

.dark-theme h4 {
	color: #ffffff;
}

.dark-theme a {
	color: #7abfff;
}

.dark-theme p {
	color: #ffffff;
}

.dark-theme small {
	color: #ffffff;
}

.dark-theme figure {
	background: #CF4B06;
	color: #ffffff;
}

.dark-theme .m-pull-quote {
	background: #1F1F1F;
	color: #ffffff;
	border-left: 5px solid #00CC36;
}

.dark-theme .o-footer-top {
	background: #1F1F1F;
}

.dark-theme #temps, .dark-theme #weather {
	color: #ffffff;
}

.dark-theme .m-footer-social-icons .fa {
	color: #ffffff;
}

.dark-theme #o-right-sidebar h3 {
	border-bottom: 1px solid #ffffff;
}

.dark-theme .state-noBgImage {
	background: #1F1F1F;
	-webkit-box-shadow: 0px -4px 4px rgba(0, 0, 0, 0.1);
	box-shadow: 0px -4px 4px rgba(0, 0, 0, 0.1);
}

.dark-theme .state-noBgImage .a-footer-links--heading {
	color: #ffffff;
	border-bottom: 1px solid #ffffff;
}

.dark-theme .state-noBgImage a {
	color: #ffffff;
}

.dark-theme .state-noBgImage .a-base-button {
	background: #0B0B0B;
	color: #ffffff;
}

.dark-theme .state-noBgImage .a-base-button:hover {
	background: #00CC36;
	color: #282828;
}

.dark-theme .subnav-container .section-title {
	background: #1F1F1F;
	color: #ffffff;
}

@media (min-width: 992px) {
	.dark-theme .subnav-container .section-title {
		background: transparent;
		color: #ffffff;
	}
}
.dark-theme .subnav-container .section-title:before {
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f105";
	color: #9b9b9b;
}

.dark-theme .subnav-container #subnavigation {
	border-bottom: 1px solid #ffffff;
}

.dark-theme .subnav-container ul.subnav {
	background: #282828;
}

@media (min-width: 576px) {
	.dark-theme .subnav-container ul.subnav {
		background: transparent;
	}
}

.dark-theme .subnav-container ul.subnav > li > a {
	border-top: 1px solid #ffffff;
	color: #ffffff;
}
.dark-theme .subnav-container ul.subnav > li span {
	border-top: 1px solid #ffffff;
}

.dark-theme .subnav-container ul.subnav > li:hover {
	background: #1F1F1F;
}

.dark-theme .subnav-container ul.sub-menu {
	background: transparent;
}

@media (min-width: 768px) {
	.dark-theme .subnav-container ul.sub-menu {
		background: transparent;
	}
}

.dark-theme .subnav-container ul.sub-menu li a {
	color: #ffffff;
}

.dark-theme #subnavigation > ul > li.top-level-menu-item.menu-item-has-children.list-item-open > span {
	background: #151515;
	margin-bottom: 5px;
	-webkit-box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.1);
	box-shadow: 0px 3px 4px rgba(5, 5, 5, 0.2);
}

.dark-theme #subnav-aside .top-level-menu-item > ul, li.list-item-open {
	/*     border-left: 4px solid #7ABFFF; */
	margin-left: -6px;
}
.dark-theme .subnav-container .menu-item-has-children button.list-toggle {
	background: transparent;
}

.dark-theme .subnav-container .menu-item-has-children button.list-toggle:before {
	display: inline-block;
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f105";
	color: #ffffff;
}

.dark-theme .subnav-container .menu-item-has-children button.list-toggle:hover {
	color: #ffffff;
}

.dark-theme .extra-info {
	background: transparent;
}

.dark-theme .subnav-container li a, .dark-theme .supplementary-content li a {
	background: transparent;
}

@media (min-width: 768px) {
	.dark-theme .subnav-container li a, .dark-theme .supplementary-content li a {
		background: none;
	}
}

.dark-theme .subnav-container li a:hover, .dark-theme .supplementary-content li a:hover {
	color: #7abfff;
}

.dark-theme .subnav-container #top-level-link--active, .dark-theme .supplementary-content #top-level-link--active {
	color: #7abfff;
	font-weight: 600;
}

.dark-theme .subnav-container #current-page-item, .dark-theme .supplementary-content #current-page-item {
	color: #ffffff;
}

.dark-theme .accordion-container .accordion-card {
	background: #232323;
}

.dark-theme .accordion-container .accordion-card a[data-toggle=collapse] {
	color: #ffffff;
}

.dark-theme .accordion-container .accordion-card .card-header {
	padding: 0;
}

.dark-theme .accordion-container .accordion-card .card-header a:active {
	border: 0;
}

.dark-theme .accordion-container .accordion-card .accordion-link.collapsed {
	border-top: 1px solid #151515;
	border-left: 1px solid #151515;
	border-right: 1px solid #151515;
	border-bottom: 1px solid #151515;
	background: #232323;
}

.dark-theme .accordion-container .accordion-card .accordion-link.collapsed a:before {
	color: #ffffff;
}

.dark-theme .accordion-container .accordion-card .accordion-link.collapsed:hover {
	background: #151515;
	border: 1px solid #151515;
	color: #ffffff;
}

.dark-theme .accordion-container .accordion-card .accordion-link {
	padding: 1rem;
	border-top: 1px solid #0B0B0B;
	border-left: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
	border-bottom: 1px solid #0B0B0B;
	background: #2D2D2D;
}

.dark-theme .accordion-container .accordion-card .card-block {
	margin-top: -1px;
	border-top: 0;
	background: #2D2D2D;
	border-left: 1px solid #151515;
	border-right: 1px solid #151515;
	border-bottom: 1px solid #151515;
	-webkit-transition: all 150ms linear;
	-o-transition: all 150ms linear;
	-moz-transition: all 150ms linear;
	transition: all 150ms linear;
}

.dark-theme .m-cta--card {
	background: #1F1F1F;
}

.dark-theme .m-cta--card h2, .dark-theme .m-cta--card h3, .dark-theme .m-cta--card h4, .dark-theme .m-cta--card h5, .dark-theme .m-cta--card h6 {
	color: #ffffff;
}

.dark-theme ol, .dark-theme ul {
	color: #ffffff;
}

.dark-theme .m-table {
	background: transparent;
}

.dark-theme .m-table .table-header {
	background: transparent;
}

.dark-theme .m-table .table {
	color: #ffffff;
}

.dark-theme .m-table thead {
	background: #151515;
	border-top: 1px solid #0B0B0B;
}

.dark-theme .m-table .table-striped tbody tr:nth-of-type(odd) {
	background: #282828;
}

.dark-theme .m-table thead th {
	border-bottom: 2px solid #1F1F1F;
	border-right: 1px solid #1F1F1F;
	border-top: 1px solid #1F1F1F;
}

.dark-theme .m-table tbody tr {
	background: #1F1F1F;
}

.dark-theme .m-table tbody th, .dark-theme .m-table td {
	border-top: 1px solid #1F1F1F;
	border-right: 1px solid #282828;
}

.dark-theme .m-table tr {
	border: 0;
}

.dark-theme #tabs {
	border-top: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
	border-bottom: 1px solid transparent;
	border-left: 1px solid #0B0B0B;
}

@media (min-width: 768px) {
	.dark-theme #tabs {
		border: 1px solid #0B0B0B;
		background: #2D2D2D;
	}
}

.dark-theme .m-tabs .ui-tabs-nav li {
	background: #0B0B0B;
	color: #ffffff;
}

.dark-theme .m-tabs .a-tab-panel {
	border: 1px solid transparent;
	border-top: 0;
	background: #2D2D2D;
}

.dark-theme .m-tabs .ui-tab:hover {
	background: #232323;
}

.dark-theme .m-tabs .ui-tab:hover a {
	color: #ffffff;
}

.dark-theme .m-tabs .ui-tabs-tab {
	background: #2D2D2D;
}

.dark-theme .m-tabs .ui-tabs-tab a {
	color: #ffffff;
}

.dark-theme .m-tabs .tabs-nav {
	border-top: 0px;
}

.dark-theme .m-tabs .tabs-nav li:first-child {
	border-left: 1px solid transparent;
}

.dark-theme .m-tabs .tabs-nav li:last-child {
	border-right: 1px solid #0B0B0B;
}

.dark-theme .m-tabs .tabs-nav li:last-child:hover {
	border-right: 1px solid transparent !important;
}

.dark-theme .m-tabs .tabs-nav li:last-child.ui-tabs-active {
	border-right: 1px solid transparent;
}

.dark-theme .m-tabs .tabs-nav li:last-child.ui-tabs-active:hover {
	border-right: 1px solid transparent !important;
}

.dark-theme .m-tabs .ui-tab {
	background: #232323;
}

.dark-theme .m-tabs .ui-tabs-tab {
	border-top-left-radius: 0px !important;
	border-top-right-radius: 0px !important;
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent;
	border-bottom: 1px solid #0B0B0B !important;
}

@media (min-width: 768px) {
	.dark-theme .m-tabs .ui-tabs-tab {
		border-top: 1px solid transparent;
		border-left: 1px solid #2D2D2D;
		border-right: 1px solid transparent;
		border-bottom: 1px solid transparent !important;
	}
	.dark-theme .m-tabs .ui-tabs-tab:hover {
		border-top: 1px solid transparent;
		border-left: 1px solid #2D2D2D;
		border-right: 1px solid #2D2D2D !important;
		border-bottom: 1px solid transparent;
	}
}

.dark-theme .m-tabs .ui-tabs-tab:hover {
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent !important;
	border-bottom: 1px solid transparent;
}

.dark-theme .m-tabs .ui-tabs-tab.ui-tabs-active {
	border-radius: 0px !important;
	border-top: 1px solid transparent;
	border-left: 1px solid transparent;
	border-right: 1px solid transparent;
	border-bottom: 1px solid #0B0B0B;
}

@media (min-width: 768px) {
	.dark-theme .m-tabs .ui-tabs-tab.ui-tabs-active {
		border-top: 1px solid transparent;
		border-left: 1px solid transparent;
		border-right: 1px solid transparent;
		border-bottom: 1px solid #2D2D2D !important;
	}
	.dark-theme .m-tabs .ui-tabs-tab.ui-tabs-active:hover {
		border-right: 1px solid transparent !important;
	}
}

.dark-theme .m-tabs .ui-tabs-tab.ui-tabs-active:hover {
	border-right: 1px solid transparent !important;
	border-radius: 0px !important;
	border-top-left-radius: 0px !important;
	border-top-right-radius: 0px !important;
}

.dark-theme .m-tabs .ui-tabs-active a:active {
	color: #ffffff !important;
	background: #2D2D2D !important;
}

.dark-theme .m-tabs .ui-tabs-active a:hover {
	color: #ffffff !important;
	background: #2D2D2D !important;
}

.dark-theme .m-tabs .ui-tabs-active {
	background: #2D2D2D !important;
}

.dark-theme .m-tabs .ui-tabs-active a {
	color: #ffffff !important;
	border: 0px;
}

.dark-theme .m-card--horizontal {
	background: #1F1F1F;
}

.dark-theme .m-card--homecustom {
	background: #ffffff;
}

.dark-theme .m-card--homecustom h2, .dark-theme .m-card--homecustom h3, .dark-theme .m-card--homecustom h4, .dark-theme .m-card--homecustom h5, .dark-theme .m-card--homecustom h6 {
	color: #282828;
	border-bottom: 0;
}

.dark-theme .m-card--homecustom p {
	color: #282828;
}

.dark-theme .m-card--homecustom:hover {
	border-bottom: 5px solid #00CC36;
}

.dark-theme .o-tabs-accordion--theme .state-has-border--right {
	border-right: 0;
}

@media (min-width: 768px) {
	.dark-theme .o-tabs-accordion--theme .state-has-border--right {
		border-right: 1px solid #00CC36;
	}
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor {
	background: #1F1F1F;
	color: #ffffff;
	border: 2px solid transparent;
}

@media (min-width: 768px) {
	.dark-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor {
		border: 2px solid transparent;
	}
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-tab .ui-tabs-anchor:hover {
	background: #0B0B0B;
	border: 2px solid #0B0B0B;
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-panel h2, .dark-theme .o-tabs-accordion--theme h3, .dark-theme .o-tabs-accordion--theme h4, .dark-theme .o-tabs-accordion--theme h5, .dark-theme .o-tabs-accordion--theme h6, .dark-theme .o-tabs-accordion--theme .ui-tabs-panel p, .dark-theme .o-tabs-accordion--theme .ui-tabs-panel ul li {
	color: #ffffff !important;
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-panel ul li a {
	color: #7abfff;
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor {
	background: #282828;
	border: 1px solid #282828;
	color: #ffffff;
}

@media (min-width: 768px) {
	.dark-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor {
		border: 2px solid #282828;
	}
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor:hover {
	background: #282828 !important;
	border: 1px solid transparent;
}

@media (min-width: 768px) {
	.dark-theme .o-tabs-accordion--theme .ui-tabs-active .ui-tabs-anchor:hover {
		border: 2px solid transparent;
	}
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-tab {
	border-top: 1px solid transparent;
	border-right: 1px solid transparent;
	border-bottom: 1px solid #282828;
	border-left: 1px solid transparent;
}

@media (min-width: 768px) {
	.dark-theme .o-tabs-accordion--theme .ui-tabs-tab {
		border-top: 2px solid transparent;
		border-bottom: 2px solid transparent;
		border-right: 1px solid transparent;
		border-left: 1px solid transparent;
	}
}

.dark-theme .o-tabs-accordion--theme .a-date-number {
	color: #ffffff;
}

.dark-theme .o-tabs-accordion--theme .ui-tabs-active {
	border: 2px solid #282828;
}

.dark-theme #home-cards h2, .dark-theme #home-cards h3, .dark-theme #home-cards h4, .dark-theme #home-cards h5, .dark-theme #home-cards h6, .dark-theme #home-cards p {
	color: #ffffff;
}

.dark-theme #home-cards .m-card--vertical {
	background: #ffffff;
}

.dark-theme #home-cards .m-card--vertical h2, .dark-theme #home-cards h3, .dark-theme #home-cards h4, .dark-theme #home-cards h5, .dark-theme #home-cards h6 {
	color: #CF4B06;
}

.dark-theme #home-cards .m-card--vertical p {
	color: #282828;
}

.dark-theme #home-cards .m-card-image {
	border: 1px solid #ffffff;
}

.dark-theme #fast-facts .a-fast--fact, .dark-theme #fast-facts p {
	color: #ffffff;
}

.dark-theme #events h2, .dark-theme #events h3, .dark-theme #events h4, .dark-theme #events h5, .dark-theme #events h6, .dark-theme #events p, .dark-theme #events span {
	color: #ffffff;
}

.dark-theme #events .m-card--horizontal {
	background: #1F1F1F;
}

.dark-theme #events .m-card-image {
	border: 1px solid #1F1F1F;
}

.dark-theme .o-footer-middle.state-noBgImage .a-base-button {
	background: #0B0B0B;
	border: 1px solid #0B0B0B;
}

.dark-theme .o-footer-middle.state-noBgImage .a-base-button:hover {
	border: 1px solid #151515;
	background: #151515;
	color: #ffffff;
}

.dark-theme .m-back-to-top {
	background: #ffffff;
}

.dark-theme .m-back-to-top span {
	color: #0054A0;
}

.dark-theme .m-card--vertical {
	background: #1F1F1F;
}

.dark-theme .card {
	position: relative;
	display: -ms-flexbox;
	display: flex;
	-ms-flex-direction: column;
	flex-direction: column;
	min-width: 0;
	word-wrap: break-word;
	background-color: #1f1f1f;
	background-clip: border-box;
	border: 1px solid rgba(0, 0, 0, 0.125);
	border-radius: 0.25rem;
}

.dark-theme .m-card--vertical h2, .dark-theme .m-card--vertical h3, .dark-theme .m-card--vertical h4, .dark-theme .m-card--vertical h5, .dark-theme .m-card--vertical h6 {
	color: #ffffff;
}

.dark-theme .m-card--vertical p {
	color: #ffffff;
}

.dark-theme .o-slider .a-slide-caption {
	background: #CF4B06;
}

.dark-theme .o-slider p {
	color: #ffffff;
}

.dark-theme .o-slider .slick-dots li button:before {
	color: #ffffff;
}

.dark-theme .o-slider .slick-dots li.slick-active button:before {
	color: #7abfff;
}

.dark-theme .o-slider .fa {
	color: #9b9b9b;
}

.dark-theme .a-button--primary {
	border: 1px solid #14325f;
	background: #14325f;
	color: #ffffff !important;
}

.dark-theme .a-button--primary:hover {
	background: #0e2343;
	border: 1px solid #0e2343;
}

.dark-theme .a-button--secondary {
	border: 1px solid #00CC36;
	background: #00CC36;
	color: #282828;
}

.dark-theme .a-button--secondary:hover {
	background: #00db3a;
}

.dark-theme .a-button--success {
	border: 1px solid #218739;
	background: #218739;
	color: #ffffff;
}

.dark-theme .a-button--success:hover {
	background: #19682c;
	border: 1px solid #19682c;
}

.dark-theme .a-button--danger {
	border: 1px solid #dc3545;
	background: #dc3545;
	color: #ffffff;
}

.dark-theme .a-button--danger:hover {
	background: #b62a37;
	border: 1px solid #b62a37;
}

.dark-theme .a-button--warning {
	border: 1px solid #ffc107;
	background: #ffc107;
	color: #282828;
}

.dark-theme .a-button--warning:hover {
	background: #ebb000;
}

.dark-theme .a-button--info {
	border: 1px solid #CF4B06;
	background: #CF4B06;
	color: #ffffff;
}

.dark-theme .a-button--info:hover {
	background: #b93a00;
}

.dark-theme .a-button--light {
	border: 1px solid #d8d8d8;
	background: #d8d8d8;
	color: #282828 !important;
}

.dark-theme .a-button--light:hover {
	background: #cfcfcf;
}

.dark-theme .a-button--dark {
	border: 1px solid #151515;
	background: #151515;
	color: #ffffff;
}

.dark-theme .a-button--dark:hover {
	background: #0B0B0B;
	border: 1px solid #0B0B0B;
}

.dark-theme .a-button--primary-trans {
	border: 1px solid #7abfff;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--primary-trans:hover {
	background: #14325f;
	border: 1px solid #14325f;
}

.dark-theme .a-button--secondary-trans {
	border: 1px solid #00CC36;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--secondary-trans:hover {
	background: #00CC36;
	color: #282828;
}

.dark-theme .a-button--primary-trans-alt {
	border: 1px solid #151515;
	background: #151515;
	color: #ffffff;
}

.dark-theme .a-button--primary-trans-alt:hover {
	border: 1px solid #0B0B0B;
	background: #0B0B0B;
}

.dark-theme .a-button--secondary-trans-alt {
	border: 1px solid #d8d8d8;
	background: #d8d8d8;
	color: #282828;
}

.dark-theme .a-button--secondary-trans-alt:hover {
	border: 1px solid #cfcfcf;
	background: #cfcfcf;
}

.dark-theme .a-button--success-trans {
	border: 1px solid #218739;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--success-trans:hover {
	background: #218739;
}

.dark-theme .a-button--danger-trans {
	border: 1px solid #dc3545;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--danger-trans:hover {
	background: #dc3545;
}

.dark-theme .a-button--warning-trans {
	border: 1px solid #ffc107;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--warning-trans:hover {
	background: #ffc107;
	color: #282828;
}

.dark-theme .a-button--info-trans {
	border: 1px solid #CF4B06;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--info-trans:hover {
	background: #CF4B06;
}

.dark-theme .a-button--light-trans {
	border: 1px solid #d8d8d8;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--light-trans:hover {
	background: #d8d8d8;
	color: #282828;
}

.dark-theme .a-button--dark-trans {
	border: 1px solid #151515;
	background: transparent;
	color: #ffffff;
}

.dark-theme .a-button--dark-trans:hover {
	border: 1px solid #0B0B0B;
	background: #0B0B0B;
}

.dark-theme .m-alert {
	background: #CF4B06;
	color: #ffffff;
}

.dark-theme .m-list-group p, .dark-theme .m-list-group small {
	color: #ffffff;
}

.dark-theme .m-list-group .list-group-item {
	background: #0B0B0B;
}

.dark-theme .m-list-group .active.list-group-item {
	background: #1F1F1F;
	border-color: #0B0B0B;
}

.dark-theme .m-list-group .list-group-item:hover {
	background: #1F1F1F;
	color: #ffffff;
}

.dark-theme .a-quotation .a-quote-icon {
	fill: #ffffff;
}

.dark-theme .a-quotation:before, .dark-theme .a-quotation:after {
	border-top: 0.5px solid #00CC36;
	border-bottom: 0.5px solid #00CC36;
}

.dark-theme .modal-content {
	background: #1F1F1F;
}

.dark-theme .modal-footer .close-modal {
	background: #d8d8d8;
	border: 1px solid #d8d8d8;
}

.dark-theme .modal-footer .save-modal {
	background: #0B0B0B;
	color: #ffffff;
	border: 1px solid #0B0B0B;
}

.dark-theme .close {
	color: #9b9b9b;
}

.dark-theme .close:focus, .dark-theme .close:hover {
	color: #9b9b9b;
}

.dark-theme .m-lightbox figure {
	background: #CF4B06;
}

.dark-theme .m-lightbox figcaption p {
	color: #ffffff;
}

.dark-theme .m-scrollspy .list-group-item {
	border: 1px solid #0B0B0B;
	color: #ffffff;
	background: #0B0B0B;
}

.dark-theme .m-scrollspy .list-group-item.active {
	background: #282828;
	color: #ffffff;
}

.dark-theme .m-scrollspy a.list-group-item:hover {
	background: #1F1F1F;
	color: #ffffff;
}

.dark-theme .scrollspy-content-container {
	border-top: 1px solid #0B0B0B;
	border-bottom: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
}

.dark-theme .scrollspy-content::-webkit-scrollbar-track {
	-webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	border-radius: 10px;
	background-color: #e8e8e8;
}

.dark-theme .scrollspy-content::-webkit-scrollbar {
	width: 12px;
	background-color: transparent;
}

.dark-theme .scrollspy-content::-webkit-scrollbar-thumb {
	border-radius: 10px;
	-webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
	background-color: #7abfff;
}

.dark-theme .tooltip.bs-tooltip-top .arrow::before, .dark-theme .tooltip.bs-tooltip-auto[x-placement^="top"] .arrow::before {
	border-top-color: #1F1F1F;
}

.dark-theme .tooltip-inner {
	background: #1F1F1F;
	color: #ffffff;
}

.dark-theme .m-cta--blue {
	background: #0054A0;
	border-top: 5px solid #0054A0;
	border-bottom: 5px solid #0054A0;
}

.dark-theme .m-cta--blue:hover {
	background: #003893;
	border-top: 5px solid #003893;
	border-bottom: 5px solid #00CC36;
}

.dark-theme .m-cta--blue .has-border {
	border-bottom: 1px solid #ffffff;
}

.dark-theme .page-link {
	color: #ffffff;
	background: transparent;
}

.dark-theme .page-link:hover {
	background: #333333;
}

.dark-theme span.fa.fa-angle-left, .dark-theme span.fa.fa-angle-right, .dark-theme span.fa.fa-angle-double-right, .dark-theme span.fa.fa-angle-double-left {
	color: #9b9b9b;
}

.dark-theme .page-link.active {
	color: #7abfff;
}

.dark-theme .m-dropdown {
	display: block;
	width: 100%;
	position: relative;
	padding: 1rem 0;
}

.dark-theme .m-dropdown ul {
	background: #333333;
	border-left: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
	border-bottom: 1px solid #0B0B0B;
	border-top: 0;
}

.dark-theme .m-dropdown ul li {
	display: block;
	float: left;
	width: 100%;
}

.dark-theme .m-dropdown ul li a {
	color: #ffffff;
}

.dark-theme .m-dropdown ul li a:active {
	font-weight: bold;
	color: #7abfff;
}

.dark-theme .m-dropdown ul li a:hover {
	background: transparent;
	color: #7abfff;
	font-weight: bold;
}

.dark-theme .m-dropdown .a-dropdown-menu {
	color: #ffffff;
	border-top: 1px solid #0B0B0B;
	border-left: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
	border-bottom: 1px solid #0B0B0B;
	background: #333333;
}

.dark-theme .m-dropdown .a-dropdown-menu:after {
	font-family: "Font Awesome 5 Free";
	font-weight: 900;
	content: "\f104";
	color: #9b9b9b;
}

.dark-theme .m-dropdown.open ul {
	display: block;
	position: relative;
	top: 100%;
	padding: 1rem;
}

@media (min-width: 576px) {
	.dark-theme .m-dropdown.open ul {
		position: relative;
	}
}

.dark-theme .label-reveals {
	color: #333333 !important;
}

.dark-theme .a-input-text-label {
	color: #ffffff;
}

.dark-theme .form-check label {
	color: #ffffff;
}

.dark-theme .m-form .a-input-text:-webkit-autofill {
	-webkit-box-shadow: 0 0 0 1000px #0B0B0B inset;
	box-shadow: 0 0 0 1000px #0B0B0B inset;
}

.dark-theme .m-form .a-input-text:focus + .a-input-text-label {
	border-bottom: 1px solid transparent;
	-webkit-box-shadow: inset 0 18px 0 1px #ffffff;
	box-shadow: inset 0 18px 0 1px #ffffff;
	color: #ffffff;
}

.dark-theme .ms-parent {
	background: #333333;
}

.dark-theme .ms-choice {
	background-color: #333333;
	color: #ffffff;
}

.dark-theme .ms-drop {
	border: 1px solid #0B0B0B;
	background: #333333;
}

.dark-theme .ms-drop ul {
	background-color: #333333;
}

.dark-theme .ms-drop ul > li label {
	color: #ffffff;
}

.dark-theme .form-control {
	border: 1px solid #0B0B0B;
	color: #ffffff;
	background: #333333;
}

.dark-theme .form-control + .input-group-addon:not(:first-child) {
	background: transparent;
}

.dark-theme .input-group-item input[type="text"] {
	border: 1px solid #0B0B0B;
}

.dark-theme .form-group input[type="text"], .dark-theme .form-group input[type="email"], .dark-theme .form-group input[type="number"], .dark-theme .form-group input[type="search"], .dark-theme .form-group select, .dark-theme .form-group textarea {
	color: #ffffff;
	border: 1px solid #0B0B0B;
	background: #333333;
}

.dark-theme .form-group input[type="checkbox"],
.dark-theme .form-group input[type="radio"] {
	background: #333333;
}

.dark-theme .form-group input[type="checkbox"] + label:before,
.dark-theme .form-group input[type="radio"] + label:before,
.dark-theme .form-group input[type="checkbox"]:hover + label:before,
.dark-theme .form-group input[type="radio"]:hover + label:before {
	border-color: #0B0B0B;
	background: #333333;
}

.dark-theme .form-group input[type="checkbox"] + label:before,
.dark-theme .form-group input[type="radio"] + label:before {
	border: 2px solid #0B0B0B;
}

.dark-theme .form-group input[type="checkbox"] + label:after,
.dark-theme .form-group input[type="radio"] + label:after {
	background-color: #7abfff;
}

.dark-theme .form-group input[type="checkbox"] + label:after input[type="checkbox"]:checked + label:after,
.dark-theme .form-group input[type="checkbox"] + label:after input[type="radio"]:checked + label:before,
.dark-theme .form-group input[type="radio"] + label:after input[type="checkbox"]:checked + label:after,
.dark-theme .form-group input[type="radio"] + label:after input[type="radio"]:checked + label:before {
	background-color: #333333;
}

.dark-theme .form-group input[type="checkbox"] + label:after input[type="checkbox"]:checked + label:after,
.dark-theme .form-group input[type="radio"] + label:after input[type="checkbox"]:checked + label:after {
	background-color: #7abfff;
}

.dark-theme .form-group input[type="checkbox"] + label:after input[type="checkbox"] + label:after,
.dark-theme .form-group input[type="radio"] + label:after input[type="checkbox"] + label:after {
	background-color: #7abfff;
}

.dark-theme .form-control::-ms-expand {
	background-color: transparent;
}

.dark-theme .form-control:focus {
	color: #ffffff;
	background-color: #333333;
}

.dark-theme .form-control::-webkit-input-placeholder {
	color: #ffffff;
}

.dark-theme .form-control::-moz-placeholder {
	color: #ffffff;
}

.dark-theme .form-control:-ms-input-placeholder {
	color: #ffffff;
}

.dark-theme .form-control:-moz-placeholder {
	color: #ffffff;
}

.dark-theme .form-control::-ms-input-placeholder {
	color: #ffffff;
}

.dark-theme .form-control::placeholder {
	color: #ffffff;
}

.dark-theme .form-control-textarea::-webkit-input-placeholder {
	color: #ffffff;
}

.dark-theme .form-control-textarea::-moz-placeholder {
	color: #ffffff;
}

.dark-theme .form-control-textarea:-ms-input-placeholder {
	color: #ffffff;
}

.dark-theme .form-control-textarea:-moz-placeholder {
	color: #ffffff;
}

.dark-theme .form-control-textarea::-ms-input-placeholder {
	color: #ffffff;
}

.dark-theme .form-control-textarea::placeholder {
	color: #ffffff;
}

.dark-theme .file-input > .label {
	color: #ffffff;
}

.dark-theme .custom-select {
	color: #ffffff;
	background: #333333 url('data:image/svg+xml;charset=utf8,<svg id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512 952.38"><g id="khgtJn"><image id="khgtJn-2" data-name="khgtJn" xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAgAAAAIBCAYAAAA/JAdfAAAACXBIWXMAAAsSAAALEgHS3X78AAAdwklEQVR4Xu3dfbS1aV0XcNAIeVGQkEiX1lrZWtlKWv1BrZb+A4mSEgKFiRFkVKZGqJURYChFJSaohNnrSpzhzHXmPM/MANMwJBYv8mIoZJICurRlS21FK8kwEZjpumb2mXnmmfOc733O2Xvf133dnz8+nGHmu/c5+96/fX1/85x9zjzgzjvvfAAAsC4xAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAYx9HlWz7joBx9wQ2Hlx5fPWXj8e3vvfa6gwen2wPjiAFgWWqZP6jcePmJ1StquR/Vj2+rHz9Y/Xr96zuD/139XPXW6rB6eb2/L731tts/PX1eYFliAOjf9QeHj6ll/dzqxuqjE4r+rP5XdX31ddWj0tcD9C8GgD7VIv699d/qX1K9u/rUhBLflk/Wz/f2+vGFh0c3fW76OoE+xQDQl4Ny9Ohavq+qJfxbE8p6136zekXxpwKwODEA9OHyzW94WC3a7yi7+SP+C2nvL2h/GnHd68rD0+MA+hADwLw2b+r75urXUhHPrS4B/6N6gZ8ogP7FADCfWqpPrIX686l4e1O/5v9WPTU9PmA+MQDMoxbpN1afSGXbsTvqEvBd9bE8MD1WYP9iANiv9jP3tThfPaFgF6E+ljcclKNHpMcN7FcMAPtzdPmWR9bSfHMq1aVpv4iofvyi9PiB/YkBYD9qQX5hufu38MVCXaj/Uz0tXQdgP2IA2L2DcvSEcvdv20slunR3VC+70/sCYHYxAOxWLcQnd/JLffbpB++0BMCsYgDYnbLO8j9mCYAZxQCwG2Xd5X+X+vhfc6clAGYRA8D2FeV/j80SEK8ZsF0xAGxXUf73YwmA/YsBYHuK8j/NP03XD9ieGAC2oyj/KSwBsCcxAFxcUf5nYQmAPYgB4GKK8j+z9t9CSNcVuJgYAM6vKP9zswTAbsUAcD5F+W/DD6TrDJxPDABnV5T/NlkCYAdiADibovx3wRIAWxYDwHRF+e/S96frD0wXA8A0RfnvgyUAtiQGgKwo/72p1/n70vMBZDEAnK4o/72zBMDFxQBwbUX5z8YSABcTA8DJivLvwavS8wScLAaA+yvKvyeWADiHGADuqyj/HlkC4IxiALhXUf49e2V6/oB7xQBwt6L8l8ASABPFAKD8l6Q+T9+bnk/AAgBRUf6LYwmALAZgzYryXyxLAJwuBmCtivIfwT9JzzOsVQzAGhXlPxJLAJwgBmBtivIfTn0+vyc977A2MQBrUpT/sCwBcF8xAGtRlP/wLAFwrxiANSjKf01ekeYB1iAGYHRF+a+RJYDViwEYWVH+a/bdaT5gZDEAoyrKH0sAKxYDMKKi/LmXJYBVigEYTVH+XKXOwz9OcwOjiQEYSVH+XIMlgLWJARhFUf5k/yjNEYwiBmAERfkznSWAVYgBWLqi/Dk7SwDDiwFYsqL8Oac6N/8wzRcsWQzAUhXlzwVZAhhZDMASFeXP9rw8zRssUQzA0hTlz/ZZAhhODMCSFOXP7lgCGEoMwFIU5c/u/YM0h7AUMQBLUJQ/+2MJYAgxAL0ryp89q/P299NcQu9iAHpWlD8zsQSwdDEAvSrKn5lZAliyGIAeFeVPP16W5hV6FAPQm6L86Y8lgMWJAehJUf50qs7ld6X5hZ7EAPSiKH86ZwlgSWIAelCUPwthCWApYgDmVpQ/y/Odaa5hbjEAcyrKn+X6zjTfMKcYgLkU5c/yvTTNOcwlBmAORfkzjpemeYc5xADsW1H+jOelae5h32IA9qkofwZV5/rvpfmHfYoB2Jei/BmcJYCexADsQ1H+rMd3pNcD7EMMwK4V5c/6WAKYXQzALhXlz0rVuX9Jen3ALsUA7EpR/qycJYA5xQDsQlH+cBdLAHOJAdi2ovzhai9OrxvYthiAbSrKH67FEsBexQBsS1H+kLwovY5gW2IAtqEof5jKEsBexABcVFH+cFaWAHYuBuAiivKHc6mvm7+bXl9wETEA51WUP1yIJYBdigE4j6L8YVtemF5vcB4xAGdVlD9smyWArYsBOIui/GFXLAFsVQzAVEX5w07V19ffSa9DmCoGYIqi/GEvLAFsSwxAUpQ/7Nu3p9clJDEApynKH+ZiCeBCYgCupSh/mJslgHOLAThJUf7Qi7+dXq9wkhiAqxXlD72xBHBmMQBXKsofulRfl38rvX7hSjEAx4ryh65ZAjiLGICmKH9YBEsAU8UAFOUPS/M30+saYoB1K8oflsoSwKligPUqyh+WzhLANcUA61SUPwyhvo6/Lb3eWacYYH2K8oehWAI4SQywLkX5w6i+Nb3+WZcYYD2K8ofRWQK4RwywDkX5w1pYArhLDDC+ovxhbb4lnQuMLwYYW1H+sFaWgJWLAcZVlD+sWn39vyCdE4wrBhhTUf7AjZaANYsBxlOUP3AFS8A6xQBjKcofONnfSOcHY4kBxlGUP3A6S8CKxABjKMofmMYSsBIxwPIV5Q+czfPTucLyxQDLVpQ/cD6WgMHFAMtVlD9wAfX8+OvpnGG5YoBlKsof2AJLwLhigOUpyh/YIkvAmGKAZSnKH9iNb07nD8sSAyxHUf7AblkCBhIDLENR/sAe1HPmm9J5xDLEAP0ryh/YI0vAGGKAvhXlD8zAErB8MUC/ivIH5nNH9Y3pnKJfMUCfivIH5mcJWLAYoD9F+QP9sAQsVAzQl6L8gf60JeCvpfOLvsQA/SjKH+iXJWBhYoA+FOUP9O+Oek59QzrP6EMMML+i/IHlsAQsRAwwr6L8geWxBCxADDCfovyB5WrvCfir6ZxjPjHAPIryB5bPEtCxGGD/ivIHxmEJ6FQMsF9F+QPjae8J+Cvp/GO/YoD9KcofGJcloDMxwH4U5Q+MzxLQkRhg94ryB9ajvSfgL6dzkd2LAXarKH9gfSwBHYgBdqcof2C92hLwvHROsjsxwG4U5Q9gCZhRDLB9RfkDHLMEzCQG2K6i/AGu1n464C+l85PtigG2pyh/gGuxBOxZDLAdRfkDJJaAPYoBLq4of4BJ6ln5qfrx69O5ysXFABdTlD/AmVgC9iMGOL+i/OnbhzdSDvbOErB7McD5FOVP3z58/cHh5zXFEkCn2hJQ/cV03nI+McDZFeVP3+4q/+N5tQTQM0vA7sQAZ1OUP3370JXlf2yzBHxowu1h7zbfDnhuOn85mxhguqL86duJ5X/MEkDPLAHbFwNMU5Q/fTu1/I9ZAuiZJWC7YoCsKH/69qHDo5s+N83xsZYtlgA6tVkCnpPmmCwGOF1R/nSszuYHz1L+x9pt2m3T/cMcLAHbEQNcW1H+dOy85X/MEkDPLAEXFwOcrCh/OnbR8j9mCaBnmx8R/AtpjjlZDHB/RfnTsVbYB+Xo96Q5nqrdlyWAXlkCzi8GuK+i/Onbz22z/I+1+2z3PeHzw95ZAs4nBrhXUf70bSflf8wSQM827wl4dppj7hUD3K0of/q20/I/ZgmgZ5aAs4kBlD99q7P5s0eXb3lsmuNtaZ+rfc70dcEcLAHTxcDaFeVPx/Zd/scsAfRs856AP5/meO1iYM2K8qdjc5X/MUsAnfukJeB0MbBWRfnTsbnL/5glgM5ZAk4RA2tUlD99+689lP+x9rW0r2nC1w1z+GT1dWmO1ygG1qYof/rWivZ3pznet/Y1FUsA/bIEnCAG1qQof/rWZfkfK5YA+mYJuEoMrEVR/vTtA6Xj8j9W7l4CPjDh8cAc2hLwrDTHaxEDa1CUP31bRPkfK5YA+mYJ2IiB0RXlT98WVf7HiiWAvrWfDvjaNMeji4GRFeVP3z5w/cHhY9Ic96p97cUSQL9WvwTEwKiK8qdjdTZ/Zsnlf6w9hvZY0uOFmax6CYiBERXlT8dGKf9jlgA6194T8OfSHI8oBkZTlD8dG638j1kC6Nwql4AYGElR/vTtv9x46ebPSXO8VO2xtcc44TrAHFa3BMTAKIryp29Dl/8xSwCda+8J+Jo0x6OIgREU5U/fVlH+xywBdG41S0AMLF1R/vRtVeV/zBJA5z6xhiUgBpasKH86Vmfzp9dY/sfaY2/XIF0nmMknqmemOV6yGFiqovzpWCu+g3L06DTHo2vXwBJAx4ZeAmJgiYryp2PK/74sAXRu2CUgBpamKH/69p+V//21a9KuzYTrB3NoS8CfTXO8NDGwJEX50zflfwpLAJ0bbgmIgaUoyp++Kf8JLAF0bqglIAaWoCh/+vb+Sze9/nelOeZu7Vq1azbhusIc2o8I/pk0x0sQA70ryp++Kf9zsATQuSGWgBjoWVH+9E35X4AlgM4tfgmIgV4V5U/flP8WWALoXHtPwDPSHPcqBnpUlD8dq7P5PuW/Pe1atmuarjvMZLFLQAz0pih/OrYpqkelOeZs2jW1BNCxRS4BMdCTovzpmPLfrWIJoGN1Nn+7enqa457EQC+K8qdvP1WU/861a7y51un5gL1b2hIQAz0oyp++Kf89KpYAOrakJSAG5laUP31T/jMolgA61paA+vFpaY7nFgNzKsqfjtXZ/Mmi/GdT7n5PwE+m5wnmsIQlIAbmUpQ/HWvFc/3B4WenOWa32nNgCaBXvS8BMTCHovzpmPLviyWAnm2WgK9OczyHGNi3ovzp23uVf3/ac9KemwnPH+xdr0tADOxTUf70Tfl3zBJAz3pcAmJgX4ryp2/KfwEsAfRs8yOCT01zvC8xsA9F+dO3/3R0+ZZHpjmmD+25as/ZhOcV9q6nJSAGdq0of/qm/BfIEkDnPt7DEhADu1SUP31T/gtmCaBzsy8BMbArRfnTN+U/AEsAnft49afTHO9KDOxCUf50rM7mTyj/cbTnsj2n6XmHmcy2BMTAthXlT8eU/5gsAXRuliUgBrapKH861grioBw9Is0xy9SeW0sAHWvvCXhKmuNtioFtKcqfvr1H+Y+vPcftuZ4wDzCHvS4BMbANRfnTN+W/IpYAOre3JSAGLqoof/qm/FfIEkDnPn54dNNXpTm+qBi4iKL86VidzXcr//XavCfg3WlOYCY7XwJi4LyK8qdj7eC/+fW3flaaY8bWZsASQMd2ugTEwHkU5U/HlD9XsgTQs02XfmWa4/OIgbMqyp++vUv5c7U2E202JswP7N2uloAYOIui/Omb8ueaLAH0bBdLQAxMVZQ/fVP+RJYAetY6tvpTaY6nioEpivKnb+9U/ky1WQLeOWGuYO+2uQTEQFKUP3175+HRTZ+Z5hiu1GamWALo1LaWgBg4TVH+9E35c26WAHq26d4npzk+TQxcS1H+dKzO5o8rfy6qzVCbpTRvMIeLLgExcJKi/OmY8mebLAH07CJLQAxc7aAcfbnyp1fKn12wBNCz1smtm9McXy0GrlQ/wRfXT/Qb6YuBmbxD+bMrm/cEvGPCHMLetW5uHZ3m+EoxcOz6g8PH1E/yS+mLgJm847rXlYenOYaLaDNWLAH065daV6c5PhYDzWuvO3iwP/6iY8qfvbEE0LPW1a2z0xw3MdDUO/2R9ElhDnXY36782bc2c2320nzCTH4kzXATA/WOXjThk8HeKX/mZAmgcy9KM3zqP6x38IzqjgmfCPbtbcqfuW2+HfC2CfMK+9a6+xmnze81/8FBOfqCut1+bMIngX1T/nTDEkCvWoe3Lr/W7F5zqOuNfzjdOcxA+dMdSwAd++Frze2Jf7Pe4HF1c/jUhDuGfXrr5Zvf8LB0GMMc2my2GZ0wx7A3my5/3Ekze+Ig1/Bt6U5hz5Q/3bME0KnbTprX+/2NGnzihDuDfVL+LIYlgE498epZvXp4H1hD751wR7AXNxxe+o/Kn6VpM9tmN8037NF762w+8Mo5vc/Q1sCzJtwJ7IXyZ8ksAXToWVfO6H0Gtv7DD0+4A9g55c8ILAF05sNXzuc9f3F4dNMfmXBj2If/cFCOHpoOV1iCNsttpifMPexc6/rj2bxnSOuW+pJ0Q9gD5c9wLAH0onX98VzeM6D1H7wn3RB2TPkzLEsAnXjP8Uze9T9Hl295bPE7/5lR3Up/TPkzujbjbdbT6wF26I7W+W0e7xrK+jeeN+FGsBPKnzWxBNCB57VZvGsg6zDeMuEGsHXKnzWyBDCn1vltDtsf/3+G/+ofM3mL8metNu8JeMuE1wlsVev81v1tCL80hWEH3nLrbbc/JB2SMLL2GiiWAGbQur99//+ZKQhb9qPKH+62WQJ+dMLrBrbpmW0BeP6EIGyL8oerWAKYwfPbAvDyCUHYBuUP12AJYM9e3n4C4F9PCMKF1Dn798ofTtdeI+21kl5PcFGt+9ufALwxBeEilD9MZwlgT97YFoD3TgjCuSh/ODtLAHvw3vYtgP8+IQjn8WblD+ezeU/Amye8zuDMWve3PwH4eArCOby5/aKJdMgB19ZeQ8USwG58vC0AH5kQhLNQ/rAllgB25CPtWwA/MyEIk9R5ul35w3ZtfmX77en1B2fwgfYnAH4NJVuh/GF3LAFsU/uPUbUF4PoUhAnepPxhtzbfDnjThNcjnKouAAdtAXhlCkKg/GFPLAFsQ10Avq8tAN+egnAK5Q97ZglgC17UFoDnTAjCSW577XUHD06HFbB97bXXXoMTXqdwkue1BeArJgThasofZmYJ4LxuOLz0lAfceOnmz09BuIryh05YAjiP1v13DVDdBN6XwtDUWfl3yh/60l6T7bWZXr+w8f42N3cNT/0/L5twA1ZO+UO/LAGcwcvbzNw1OHVoHj/hBqzbrcof+rb5dsCtE17PrNjh0U1/os3L8eA8sC4Bv5JuxGopf1gISwCnqV3/P1/9mh/6tDYr9wxN/Zv/It2QVVL+sDCWAK6ldv1rj+fknoFpPxKQbsjqvFH5wzJtloA3TnidsyK167/meEbuGZZbb7v9IfUffCzdmNV4Y52J35kOGaBf7TVcLAHc6+MH5egRx/Nxn2GpC8D3TLgDBlfn4A3KH8bQXsvtNZ1e94yv/f7/K2fjPoNydPmWR9bQR9KdMC7lD+OxBFB9tP7b/6OvnIv7DUodkhdMuCMGpPxhXJaA1Xvx1TNxvyGpG8KDavDDE+6Msbxe+cPYNu8JeP2E84CBtB/zr93+0Kvn4cQhqTd4RrpDhqL8YSUsAetTF4BvOGkWrjkk9QZvT3fKEJQ/rIwlYD1ql3/wXe/+id9x0hxcc0AOytEfrze+I905y1UH4xblD+u0eU/ALemcYNnqc/z0a83AqQNSb/yidOcsk/IHLAHD+8HTnv84IPUO/uWET8Ky3Nze7Jmee2B8mzd+3zzh3GBZ3nKtP/o/Foej3UG9ozdN+GQsg/IH7sMSMJz2k3yPSs97HIzm8Oimz6x39v4Jn5S+KX/gRJaAMdxweOnX63P5B9Pz3cTAsesPDj+v3vkvp09Ot25S/sBpNkvATRPOE/r0yerJ6Xk+FgNXqnf8uOqjE74I+qL8gUksAYv2Len5vVIMnDAcT/BfDVyO+lxdVv7AWbQzo50d6XyhK69Mz+vVYuAk9RM9sfrNCV8QM1L+wHlZAhblVen5PEkMXEuxBHRN+QMXZQlYhHOVfxMDpymWgF5dUv7ANmzeE3BpwrnD/p27/JsYSOoX8CeLJaAbdVs/Sr/8AeAs2pnSzpZ0/rBXFyr/JgamKJaALih/YFcsAV25cPk3MTBVsQTMSvkDu2YJ6MJWyr+JgbMoloC53Kj8gX3Y/Hr4GyecS2zf1sq/iYGzqtvhlxVLwD4pf2CvLAGz2Gr5NzFwHpaAvTlU/sAcNkvA4YRziovbevk3MXBeloCdU/7ArCwBe7GT8m9i4CIsATuj/IEuWAJ2amfl38TARVkCtqtez6L8gZ5sfjqgpPOLM9lp+TcxsA31gTyp+n8THjCnUP5ArywBW7Xz8m9iYFuKJeCibrj1tts/PV1ngLm0M6qdVRPOM65tL+XfxMA2FUvAeSl/YBEsAReyt/JvYmDbiiXgrJQ/sCiWgHPZa/k3MbALB+Xoy4slILrh8NKB8geWqJ1d7QxL5xx32Xv5NzGwK5aA0yl/YOksAZPMUv5NDOySJeCaXqf8gRFsvh3wugnn3hrNVv5NDOyaJeB+lD8wFEvAiWYt/yYG9qFeiK8oloBG+QNDsgTcx+zl38TAvhRLwPXKHxjZZgm4fsJ5OLIuyr+JgX0q610ClD+wCitfArop/yYG9q2sbAm44fDSdcofWJPNTwdcl87HwXRV/k0MzKFeqC+pPjLhgi7dK1/9mh/6tHQ9AEbTzr66BHzvhHNy0epj/FT1bel6zCEG5nJ0+ZY/UC/az6eLu0RtIOrH56drADC6eh5+Uz0PP5nOzYX6aPWV6RrMJQbmdOOlmz+nXrx3TbjIi1GH/WPVU9NjB1iLw6Obvqqej/83nZ8L8wu1w/5QeuxzioG53Xrb7Q+pF/LShIu9BL9Wy//x6TEDrE09H/9oPR9/ZcI5ugRvPShHj06PeW4x0IP2vaJ6QV854aJ3qw72z15/cPj70mMFWKv6b8yfX8/Kn07naef+VS3/B6XH2oMY6Em9sM9Z2oa4+X7/v6nl/9np8QGs3c2vv/Wz6pn5z6pPpPO1J5tu+vr0+HoSA725fPMbHlYv8kvLMr5f9KbqcekxAXBf9ez8olqqb5hwzs6tvdHvxfXf+h+aHlNvYqBXR5dveWy96P+89Pnu0fdXT0qPAYDT1WJ9Qj1Pf2rCubtXdTn57frxB9qb1dNj6FUM9K69y7KjLfGXq+f62X6ArXpgPVufszlj0zm8a3dUN9TF5PdP+Lq7FgNLUZ+QP1Z9d3uz3YQncJs+Wj9nqR+f3X5iIX2dAJzP5qfCnr05cz864Xzemvo531c/vqwW/xenr3MpYmCJ6pP0hdW31ifsx8oO3khS7/cX68fvrx+/bCnv9gQYSTt72xm8OYt/MZ3bZ1Xv87fqx9vaLypqP52Qvp4lioGlO7p8yyPrE/i11Wuqy9WP1yf1F0p+E2F7b8Gvbra+9ma+f1u98PDopj+cPicA+9XO5nZGb87qN23O7l8t4X1iNfcb9eOHq3fUvz4qdy8UT29vOE+fc+liYGTXva48vH0fp9z93x54WvWk6nHXHxw+xvfxAZavneXtTG9n++aMb2f9l7Szfw0lf5oYAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDxxAAAMJ4YAADGEwMAwHhiAAAYTwwAAOOJAQBgPDEAAIwnBgCA8cQAADCeGAAAxhMDAMB4YgAAGE8MAADjiQEAYDwxAACMJwYAgPHEAAAwnhgAAMYTAwDAeGIAABhPDAAA44kBAGA8MQAAjCcGAIDx/H+t/vg25qztdQAAAABJRU5ErkJggg=="/></g><g id="_6geJrq" data-name="6geJrq"><image id="_6geJrq-2" data-name="6geJrq" width="512" height="512" transform="translate(0 440.38)" xlink:href="data:image/png;base64,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"/></g></svg>') no-repeat center right !important;
		background-size: 2.8rem 2rem !important;
		border: 1px solid #0B0B0B;
		}

.dark-theme .custom-select:focus::-ms-value {
	color: #ffffff;
	background-color: #333333;
}

.dark-theme .custom-select:disabled {
	color: #1F1F1F;
	background-color: transparent;
}

.dark-theme .li.event {
	background: #282828;
}

.dark-theme .localist-widget-hl .event-card {
	background: #0B0B0B;
}

.dark-theme .localist-widget-hl .event-card p {
	font-size: 0.875rem;
}

.dark-theme .localist-widget-hl .event-card:hover, .dark-theme .localist-widget-hl .event-card:active {
	border-bottom: 4px solid #00CC36;
}

.dark-theme .localist-widget-hl .event-details {
	background: rgba(20, 50, 95, 0.8);
}

.dark-theme .localist-widget-hl .event-list .event-overview .content {
	border: 1px solid #0B0B0B;
	background: #0B0B0B;
}

.dark-theme .event-details dd {
	color: #ffffff;
}

.dark-theme .localist-widget-hl .event-card .content p {
	color: #ffffff;
}

.dark-theme .localist-widget-hl .event-card .content:before {
	background: #0B0B0B;
}

.dark-theme #campus-life h3:hover {
	text-decoration: underline;
}

.dark-theme #campus-life h2, .dark-theme #campus-life h3, .dark-theme #campus-life h4, .dark-theme #campus-life h5, .dark-theme #campus-life h6 {
	color: #ffffff;
}

.dark-theme #campus-life .grid-image--solid {
	background: #1F1F1F;
}

.dark-theme #search-table_wrapper {
	border: 1px solid #151515;
}

.dark-theme .dataTables_filter label {
	color: #ffffff;
}

.dark-theme .dataTables_length label {
	color: #ffffff;
}

.dark-theme .dataTables_length select {
	background: #333333;
	color: #ffffff;
	border: 1px solid #0B0B0B;
}

.dark-theme .dataTables_wrapper .dataTables_filter input {
	color: #ffffff;
	border: 1px solid #0B0B0B;
	background: #333333;
}

.dark-theme #search-table_info {
	color: #ffffff;
}

.dark-theme .paginate_button.current {
	background: #282828 !important;
}

.dark-theme .dataTables_wrapper .dataTables_paginate .paginate_button.current, .dark-theme .dataTables_wrapper .dataTables_paginate .paginate_button.current:hover {
	color: #ffffff !important;
}

.dark-theme #search-table_previous, .dark-theme #search-table_next {
	border: 1px solid #151515;
	background: #151515;
	color: #ffffff !important;
}

.dark-theme #search-table_previous:hover, .dark-theme #search-table_next:hover {
	border: 1px solid #0B0B0B;
	background: #0B0B0B;
}

.dark-theme .dataTables_wrapper .dataTables_paginate .paginate_button.disabled, .dark-theme .dataTables_wrapper .dataTables_paginate .paginate_button.disabled:hover, .dark-theme .dataTables_wrapper .dataTables_paginate .paginate_button.disabled:active {
	color: #9b9b9b !important;
}

.dark-theme .table.dataTable.display tbody tr.odd > .sorting_1 {
	background-color: #0B0B0B;
}

.dark-theme .table.dataTable.display tbody tr.even > .sorting_1 {
	background-color: #0B0B0B;
}

.dark-theme table.dataTable.hover tbody tr:hover, .dark-theme table.dataTable.display tbody tr:hover {
	background-color: #333333;
}

.dark-theme table.dataTable.hover tbody tr:hover.selected, .dark-theme table.dataTable.display tbody tr:hover.selected {
	background-color: #0B0B0B;
}

.dark-theme #search-table_wrapper .table-bordered th, .dark-theme .table-bordered td {
	border: 1px solid #333333;
}

.dark-theme .j-loading {
	border: 4px solid #FFF !important;
}

.dark-theme .j-loading:before {
	background-color: #FFF;
}

.dark-theme .juicer-feed {
	background-color: #4A4A4A !important;
	background-color: #282828 !important;
}

.dark-theme .juicer-feed a {
	color: #7ABFFF;
}

.dark-theme .juicer-feed .j-meta a {
	color: #FFF;
}

.dark-theme .juicer-feed a, .dark-theme .j-poster h3 {
	color: #FFF;
}

.dark-theme .juicer-feed a:hover {
	color: #7ABFFF !important;
}

.dark-theme .juicer-feed li.feed-item {
	background-color: #3E3E3E !important;
	background-color: #1F1F1F !important;
	border: none !important;
}

.dark-theme .juicer-feed li.feed-item:before {
	content: '' !important;
}

.dark-theme .juicer-feed.modern li.feed-item .j-message a {
	color: #7ABFFF;
}

.dark-theme .juicer-feed.modern li.feed-item .j-message a:hover {
	text-decoration: underline !important;
}

.dark-theme .juicer-feed .j-message, .dark-theme .juicer-feed .j-message p {
	color: #FFF !important;
	font-size: 1em;
	font-weight: 500;
}

.dark-theme .juicer-button, .dark-theme .j-paginate {
	-moz-transition: all 0.2s ease-in-out;
	-o-transition: all 0.2s ease-in-out;
	-webkit-transition: all 0.2s ease-in-out;
	transition: all 0.2s ease-in-out;
	display: inline-block;
	border: 2px solid #FFF !important;
	font-size: 12px;
	font-weight: bold;
	letter-spacing: 0.5px;
	color: #FFF !important;
	text-align: center;
	padding: 12px 0 10px;
	cursor: pointer;
	background-color: transparent;
	width: 150px;
	display: block;
	text-transform: uppercase;
}

.dark-theme .juicer-feed .j-paginate:hover {
	background: #242424;
	color: #FFF !important;
	border: 2px solid #242424 !important;
}

.dark-theme .j-display-filters {
	padding-left: 0px !important;
	-webkit-padding-start: 0px !important;
}

.dark-theme .juicer-feed .j-display-filters {
	text-align: left;
	margin: 0px 0px 15px;
	font-weight: 700;
	font-size: 18px;
	text-transform: uppercase;
	color: #FFF;
}

.dark-theme .juicer-feed .j-display-filters li:before {
	margin-right: 6px;
	line-height: 11px;
	font-size: 50px;
	font-weight: 100;
	position: relative;
}

.dark-theme .juicer-feed .j-display-filters li {
	display: inline-block;
	margin: 0px 5px 0px 0px !important;
	padding: 25px 0px 5px 5px;
	cursor: pointer;
	border-bottom: 1px solid #282828;
}

.dark-theme .juicer-feed .j-display-filters li.all:before {
	font-size: 46px;
	bottom: 15px !important;
}

.dark-theme .juicer-feed .j-display-filters li.all {
	color: #FFF;
	background: #282828 !important;
	color: white;
	margin-top: 10px;
	margin-left: -0px;
}

.dark-theme .juicer-feed .j-display-filters li {
	background: none !important;
}

.dark-theme .all:before {
	content: "\f021" !important;
	font-family: 'Font Awesome 5 Free' !important;
	font-weight: 900;
}

.dark-theme .juicer-feed .j-display-filters .all:before {
	content: "\f021" !important;
	font-family: 'Font Awesome 5 Free' !important;
	font-weight: 900;
}

.dark-theme .juicer-feed .j-display-filters li.all.highlight, .dark-theme .juicer-feed .j-display-filters li.all {
	background: #282828 !important;
	color: #FFF;
	margin-top: 20px;
	margin-left: -0px;
}

.dark-theme .juicer-feed .j-display-filters li.all.highlight, .dark-theme .juicer-feed .j-display-filters li.all:hover {
	background: #282828 !important;
	color: #FFF;
	border-bottom: 1px solid #FFF !important;
	margin-top: 30px;
}

.dark-theme .j-facebook-text:before {
	color: #FFF;
}

.dark-theme .juicer-feed .j-facebook:before {
	content: "\f082" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-facebook:before {
	content: "\f082" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-facebook .j-facebook-hover .j-social-icon:before {
	content: "\f082" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.dark-theme .juicer-feed .j-facebook-hover.highlight:before, .dark-theme .juicer-feed .j-facebook-hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-facebook-hover.highlight:before, .dark-theme .juicer-feed .j-facebook-hover:hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-facebook-hover.highlight, .dark-theme .juicer-feed .j-facebook-hover:hover {
	background: #282828 !important;
	color: white;
	border-bottom: 1px solid #FFF !important;
}

.dark-theme .j-facebook .j-social:before {
	content: "\f39e" !important;
}

.dark-theme .j-instagram-text:before {
	color: #FFF;
}

.dark-theme .juicer-feed .j-instagram:before {
	content: "\f16d" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-instagram:before {
	content: "\f16d" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-instagram .j-instagram-hover .j-social-icon:before {
	content: "\f16d" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.dark-theme .juicer-feed .j-instagram-hover.highlight:before, .dark-theme .juicer-feed .j-instagram-hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-instagram-hover.highlight:before, .dark-theme .juicer-feed .j-instagram-hover:hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-instagram-hover.highlight, .dark-theme .juicer-feed .j-instagram-hover:hover {
	background: #282828 !important;
	color: white;
	border-bottom: 1px solid #FFF !important;
}

.dark-theme .j-instagram .j-social:before {
	content: "\f16d" !important;
}

.dark-theme .j-twitter-text:before {
	color: #FFF;
}

.dark-theme .juicer-feed .j-twitter:before {
	content: "\f081" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-twitter:before {
	content: "\f081" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-twitter .j-twitter-hover .j-social-icon:before {
	content: "\f081" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.dark-theme .juicer-feed .j-twitter-hover.highlight:before, .dark-theme .juicer-feed .j-twitter-hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-twitter-hover.highlight:before, .dark-theme .juicer-feed .j-twitter-hover:hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-twitter-hover.highlight, .dark-theme .juicer-feed .j-twitter-hover:hover {
	background: #282828 !important;
	color: white;
	border-bottom: 1px solid #FFF !important;
}

.dark-theme .j-twitter .j-social:before {
	content: "\f099" !important;
}

.dark-theme .juicer-feed .j-twitter-post-icon:before {
	color: #FFF !important;
}

.dark-theme .juicer-feed .j-twitter-post-icon:hover:before {
	color: #7ABFFF !important;
}

.dark-theme .j-youtube-text:before {
	color: #FFF;
}

.dark-theme .juicer-feed .j-youtube:before {
	content: "\f431" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-youtube:before {
	content: "\f431" !important;
	font-family: 'Font Awesome 5 Brands';
	font-weight: 400;
}

.dark-theme .j-youtube .j-youtube-hover .j-social-icon:before {
	content: "\f431" !important;
	font-family: 'Font Awesome 5 Brands' !important;
	font-weight: 400;
}

.dark-theme .juicer-feed .j-youtube-hover.highlight:before, .dark-theme .juicer-feed .j-youtube-hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-youtube-hover.highlight:before, .dark-theme .juicer-feed .j-youtube-hover:hover:before {
	color: #FFF;
	padding: 5px 5px;
}

.dark-theme .juicer-feed .j-youtube-hover.highlight, .dark-theme .juicer-feed .j-youtube-hover:hover {
	background: #282828 !important;
	color: white;
	border-bottom: 1px solid #FFF !important;
}

.dark-theme .j-youtube .j-social:before {
	content: "\f167" !important;
}

.dark-theme .j-poster .j-date {
	float: right;
	font-size: 14px;
	margin-top: 4px;
	color: #FFF;
}

.dark-theme .juicer-feed .j-meta li {
	display: inline-block;
	margin: 0 10px 0 0;
	padding: 0;
	background-image: none;
	border: none;
	font-size: 1em;
	font-weight: 500;
	height: auto;
	width: auto;
}

.dark-theme .juicer-feed .j-meta a.j-social {
	font-size: 1.8em;
	font-weight: 100;
	line-height: 1;
	float: none;
	margin: 0;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-facebook {
	color: #FFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-facebook:hover {
	color: #7ABFFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-instagram {
	color: #FFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-instagram:hover {
	color: #7ABFFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-twitter {
	color: #FFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-twitter:hover {
	color: #7ABFFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-youtube {
	color: #FFF;
}

.dark-theme .juicer-feed.colored-icons .j-meta a.j-social.j-youtube:hover {
	color: #7ABFFF;
}

.dark-theme .j-poster {
	overflow: hidden;
	margin: 0 0 0 0;
	height: 30px;
}

.dark-theme .j-overlay {
	position: fixed;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	background: rgba(0, 0, 0, 0.6);
	padding-top: 50px;
	z-index: 99999999;
	outline: none;
}

.dark-theme .j-message a {
	color: #7ABFFF;
}

.dark-theme .j-message a:hover {
	color: #7ABFFF;
	text-decoration: underline !important;
}

.dark-theme .j-overlay .j-overlay-content {
	margin: 0 auto;
	background: #FFF;
	position: relative;
	color: #3E3E3E;
	font-weight: normal;
	max-height: 90%;
	overflow-y: auto;
	outline: none;
	max-width: 980px;
}

.dark-theme .j-post-overlay.juicer-feed {
	overflow: hidden;
	margin: 0 !important;
}

.dark-theme .j-post-overlay.juicer-feed a.juicer-button {
	float: left;
	-moz-transition: all 0.2s ease-in-out;
	-o-transition: all 0.2s ease-in-out;
	-webkit-transition: all 0.2s ease-in-out;
	transition: all 0.2s ease-in-out;
	display: inline-block;
	border: 2px solid #14325F;
	font-size: 12px;
	font-weight: bold;
	letter-spacing: 0.5px;
	color: #14325F;
	text-align: center;
	padding: 12px 0 10px;
	cursor: pointer;
	background-color: transparent;
	width: 200px;
}

.dark-theme .j-post-overlay.juicer-feed a.juicer-button:hover {
	background: #0B0B0B;
	color: #FFF !important;
	border: 2px solid #0B0B0B !important;
}

.dark-theme .j-post-overlay.juicer-feed a.juicer-button:hover::before {
	background: #0B0B0B;
	color: #FFF !important;
}

.dark-theme .j-post-overlay.juicer-feed a.juicer-button:before {
	font-family: 'Font Awesome 5 Brands', Helvetica, Arial, sans-serif;
	font-size: 1rem;
	position: relative;
	left: -10px;
	top: 1px;
	font-weight: normal;
	color: #FFF;
}

.dark-theme .juicer-feed .j-email::before {
	content: "";
	font-family: 'Font Awesome 5 Free' !important;
	font-weight: 900;
}

.dark-theme .j-post-overlay.juicer-feed ul.j-share a:hover {
	background: #282828;
	color: #FFF !important;
}

.dark-theme .j-post-overlay.juicer-feed ul.j-share a:hover::before {
	background: #282828;
	color: #FFF !important;
}

.dark-theme .j-post-overlay.juicer-feed ul.j-share a:before {
	font-family: 'Font Awesome 5 Brands', Helvetica, Arial, sans-serif;
	font-size: 16px;
	color: #FFF;
	position: relative;
	font-weight: 100;
	top: 1px;
}

.dark-theme a.j-facebook.share {
	background: #282828;
	margin-right: 1px;
}

.dark-theme a.j-facebook.share:hover {
	border-bottom: solid 1px #FFF;
	margin-right: 1px;
}

.dark-theme a.j-twitter.share {
	background: #282828;
	margin-right: 1px;
}

.dark-theme a.j-twitter.share:hover {
	border-bottom: solid 1px #FFF;
	margin-right: 1px;
}

.dark-theme a.j-googleplus.share {
	background: #282828;
	margin-right: 1px;
}

.dark-theme a.j-googleplus.share:hover {
	border-bottom: solid 1px #FFF;
	margin-right: 1px;
}

.dark-theme .j-post-overlay.juicer-feed ul.j-share a.j-pinterest.share {
	display: none;
}

.dark-theme a.j-pinterest.share {
	background: #282828;
	margin-right: 1px;
}

.dark-theme a.j-pinterest.share:hover {
	border-bottom: solid 1px #FFF;
	margin-right: 1px;
}

.dark-theme a.j-linkedin.share {
	background: #282828;
	margin-right: 1px;
}

.dark-theme a.j-linkedin.share:hover {
	border-bottom: solid 1px #FFF;
	margin-right: 1px;
}

.dark-theme a.j-email.share {
	background: #282828;
}

.dark-theme a.j-email.share:hover {
	border-bottom: solid 1px #FFF;
}

.dark-theme .j-post-overlay.juicer-feed .j-navigate a.j-previous, .dark-theme .j-post-overlay.juicer-feed .j-navigate a.j-next {
	cursor: pointer;
	color: #FFF;
}

.dark-theme a.juicer-button.j-facebook:before {
	content: "\f09a" !important;
}

.dark-theme .juicer-feed, .dark-theme a.j-facebook.share:before {
	content: "\f09a" !important;
}

.dark-theme a.juicer-button.j-twitter:before {
	content: "\f099" !important;
}

.dark-theme .juicer-feed, .dark-theme a.j-twitter.share:before {
	content: "\f099" !important;
}

@media only screen and (max-width: 1270px) {
	.dark-theme ul.j-share {
		float: right !important;
		display: block;
		-webkit-padding-start: 0px !important;
	}
}

@media (max-width: 1190px) {
	.dark-theme ul.j-share {
		float: left !important;
		display: block;
		-webkit-padding-start: 0px !important;
	}
}

.dark-theme .j-overlay .j-close {
	padding: 10px;
	top: 10px;
}

.dark-theme .j-overlay .j-close:hover {
	padding: 10px;
	top: 10px;
}

/* *** Accordion UI States and Icons ***  */
.dark-theme .ui-accordion .ui-state-default {
	background: #282828;
	color: #ffffff;
	border-bottom: 1px solid #0B0B0B;
	border-top: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
	border-left: 1px solid #0B0B0B;
}
.dark-theme .ui-accordion .ui-state-default:hover {
	background: #151515 !important;
	color: #ffffff;
	border-bottom: 1px solid #0B0B0B;
}
.dark-theme .ui-accordion .ui-state-focus {
	background: #151515;
	color: #ffffff;
	border-bottom: 1px solid #0B0B0B;
}
.dark-theme .ui-accordion .ui-state-active {
	background: #2D2D2D;
	color: #ffffff;
	border-bottom: 1px solid #0B0B0B;
}
.dark-theme .ui-accordion .ui-state-hover {
	background: #151515;
	color: white;
	border-bottom: 1px solid #0B0B0B;
}

.dark-theme .ui-accordion .ui-widget-content {
	background: #2D2D2D;
	border-bottom: 1px solid #0B0B0B;
	border-right: 1px solid #0B0B0B;
	border-left: 1px solid #0B0B0B;
}

.dark-theme .ui-accordion .ui-state-default .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-accordion .ui-state-focus .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-accordion .ui-state-active .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_fffff_256x240.png);
}
.dark-theme .ui-accordion-header-active .ui-state-focus .ui-icon,
.dark-theme .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}

/* *** Nested Accordions in Tab Set UI States and Icons *** */
.dark-theme .ui-tabs .ui-accordion .ui-state-default {
	background: #232323;
	color: #ffffff;
	border-bottom: 0px solid #0B0B0B;
}
.dark-theme .ui-tabs .ui-accordion .ui-state-focus {
	background: #151515;
	color: white;
	border-bottom: 1px solid #0B0B0B;
}
.dark-theme .ui-tabs .ui-accordion .ui-state-active {
	background: #2D2D2D;
	color: #ffffff;
	/* border-bottom: 0px solid #0B0B0B; */
}
.dark-theme .ui-tabs .ui-accordion .ui-state-hover {
	background: #151515;
	color: white;
	/* 	border-bottom: 1px solid #0B0B0B; */
}
.dark-theme .ui-tabs .ui-accordion .ui-state-default .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-tabs .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-tabs .ui-accordion .ui-state-focus .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-tabs .ui-accordion .ui-state-active .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme .ui-tabs .ui-accordion-header-active .ui-state-focus .ui-icon,
.dark-theme.ui-tabs .ui-accordion .ui-state-hover .ui-icon {
	background-image: url(/_resources/images/jquery/ui-icons_ffffff_256x240.png);
}
.dark-theme [id^="tabs"] [id^="accordion-"] .ui-widget-content {
	border: 1px solid #0B0B0B;
	background: #2D2D2D;
	color: #ffffff;
}
.dark-theme  [id*="tabs"] [id^="accordion-"] .ui-state-default, .dark-theme .ui-widget-content .ui-state-default {
	border-top: 1px solid #0B0B0B !important;
	border-left: 1px solid #0B0B0B !important;
	border-right: 1px solid #0B0B0B !important;
	/* border-bottom: 1px solid #0B0B0B; */
}

/*  Homepage .o-tab-accordion border fix */
.dark-theme .o-tabs-accordion .ui-state-default {
	border-top: 1px solid #EFEFEF !important;
	border-left: 1px solid #EFEFEF !important;
	border-right: 1px solid #282828 !important;
}

.dark-theme .o-tabs-accordion .ui-state-hover {
	border-top: 1px solid #14325f !important;
	border-left: 1px solid #14325f !important;
	border-right: 1px solid #14325f !important;
}

.dark-theme .o-tabs-accordion .ui-state-active {
	border-top: 1px solid #14325f !important;
	border-left: 1px solid #14325f !important;
	border-right: 1px solid #14325f !important;
}

.dark-theme [id*="tabs"] [id^="accordion-"] .ui-state-default a, .dark-theme [id*="tabs"] [id^="accordion-"] .ui-state-default a:link {
	color: #ffffff !important;
}
.dark-theme .ui-state-active, .dark-theme .ui-widget-content .ui-state-active, .dark-theme .ui-widget-header .ui-state-active {
	background: #2D2D2D !important;
	color: #ffffff !important;
}
.dark-theme  [id^="tabs"] [id^="accordion-"] .ui-state-default, .dark-theme .ui-widget-content .ui-state-default, .dark-theme .ui-widget-header .ui-state-default {
	background: #0B0B0B;
}
.dark-theme  [id^="tabs"] [id^="accordion-"] .ui-state-hover, .dark-theme .ui-widget-content .ui-state-hover, .dark-theme .ui-widget-header .ui-state-hover {
	background: #232323 !important;
}

.dark-theme  [id^="tabs"] [id^="accordion-"] .ui-tabs .ui-tabs-nav li.ui-tabs-active {
	margin-bottom: -1px;
	border-bottom: 1px solid #2D2D2D;
}
.dark-theme [id*="tabs"] [id*="accordion-"] .ui-widget-header  {
	border-top: 0px solid;
	border-left: 0px solid;
	border-right: 0px solid;
	border-bottom: 1px solid #0B0B0B;
	background: #2D2D2D !important;
	font-weight: bold;
}
.dark-theme #tabs li.ui-tabs-tab.ui-corner-top.ui-state-default.ui-tab.ui-tabs-active.ui-state-active {
	padding: 0px;
	margin-bottom: -2px !important;
	border-bottom: 1px solid #2D2D2D !important;
}

/* jQuery UI - a */
.dark-theme .ui-widget-content a {
	color: #7abfff;
}

.dark-theme .ui-tabs .ui-tabs-nav .ui-tabs-anchor {
	color: #FFFFFF;
}

/* Homepage tabs - Anchor */
.dark-theme .o-tabs-accordion--custom .ui-tabs-tab .ui-tabs-anchor {
	color: #282828;
}

.dark-theme .o-tabs-accordion--custom .ui-tabs-tab .ui-tabs-anchor:hover {
	color: #FFFFFF;
}

.dark-theme [id^="tabs"] .ui-widget-content {
	border-top: 1px solid #0B0B0B;
	background: #2D2D2D !important;
	color: #fff !important;
}

.dark-theme .ui-widget-content {
	background: #2D2D2D;
}

.dark-theme [id*="tabs"] [id^="accordion-"] .ui-state-active a, .dark-theme .ui-state-active a:link {
	color: #ffffff !important;
}
.dark-theme [id*="tabs"] [id^="accordion-"] .ui-state-active a, .dark-theme .ui-state-hover a:link {
	color: #ffffff !important;
}
.dark-theme [id*="tabs"] [id^="accordion-"] .ui-state-default a:hover, .dark-theme .ui-state-active a:link:hover {
	color: #ffffff !important;
}

/* ================================
Google CSE - Dark Theme
================================ */
.dark-theme .search-box {
	width:98%;
	max-width: 450px;
	margin-left: 5px;
}

.dark-theme .search-results {
	background-color: #282828;
	width:100%;
	max-width:800px;
}

.dark-theme .gs-snippet {
	margin-top: 1px;
	padding-left: 8px;
}

/* ================================
Search Results - Outer Border
================================ */
.dark-theme .gsc-control-cse {
	border-color:#282828!important;
	padding-left:5px!important;
	background-color: #282828;
}

/* ================================
Search Input Field
================================ */
.dark-theme input.gsc-input {
	/*	height: 30px !important; */
	width:100%!important;
	-webkit-appearance:none;
}

.dark-theme input#gsc-i-id1.gsc-input {
	background:none!important;
	text-indent:0!important;
}

.dark-theme table.gsc-search-box td.gsc-input {
	padding-right:0!important;
}

.dark-theme .gsc-input-box {
	border:1px solid #D9D9D9;
	background:#fff;
	height:30px!important;
}

.dark-theme .gsc-input-box-focus {
	border:1px solid #66afe9!important;
}

/* ================================
Search Clear X
================================ */
.dark-theme .gsst_a {
	padding-top:5.5px;
}

.dark-theme .gsst_a .gscb_a {
	color: #151515 !important;
	cursor: pointer;
	padding-top: 3px;
}

.dark-theme .gsst_a:hover .gscb_a {
	color: #0B0B0B !important;
	cursor: pointer;
}

/* ================================
Search Button 
================================ */
.dark-theme .gsc-clear-button {
	display:none;
}

.dark-theme .gsc-search-button {
	font:700 13px/16px arial,helvetica,sans-serif!important;
	color:#FFF!important;
	background-color: #151515 !important;
	border: 1px solid #151515 !important;
	border-radius:0!important;
	-webkit-appearance:none;
}

.dark-theme .gsc-search-button:hover {
	font:700 13px/16px arial,helvetica,sans-serif!important;
	color:#FFF!important;
	background-color: #0B0B0B !important;
	border: 1px solid #0B0B0B !important;
	border-radius:0!important;
	-webkit-appearance:none;
}

.dark-theme input.gsc-search-button:hover {
	background:#003893!important;
	cursor:pointer;
	border:0 none;
}

.dark-theme .gsc-search-button-v2 {
	border-color: #151515 !important;
	background-color: #151515 !important;
	background-image: -webkit-gradient(linear,left top,left bottom,from(#151515),to(#151515))!important;
	background-image: -webkit-linear-gradient(top,#151515,#151515)!important;
}

.dark-theme .gsc-search-button-v2:hover {
	border-color: #0B0B0B !important;
	background-color: #0B0B0B !important;
	background-image: -webkit-gradient(linear,left top,left bottom,from(#0B0B0B),to(#0B0B0B))!important;
	background-image: -webkit-linear-gradient(top,#0B0B0B,#0B0B0B)!important;
}

/* ================================
Results Filters
================================ */
.dark-theme .gsc-tabsArea {
	font-size: 18px !important;
	border-bottom: 1px solid #0B0B0B !important;
	height: 30px !important;
}

.dark-theme .gsc-tabHeader {
	padding-bottom: 1px !important;
	padding-left: 16px !important;
	padding-right: 16px !important;
	padding-top: 0px !important;
	margin-right:2px;
	margin-top: 2px !important;
	height:28px!important;
	text-align:center!important;
}

.dark-theme .gsc-tabHeader.gsc-tabhActive {
	font-weight: 600;
	color: #FFFFFF !important;
	background-color: #2D2D2D;
	border: 1px solid;
	border-top: 1px solid !important;
	border-color: #0B0B0B !important;
	border-top-color: #0B0B0B;
	border-bottom-color: #282828 !important;
	margin-top: 1px !important;
}

.dark-theme .gsc-tabHeader.gsc-tabhInactive {
	font-weight: 600;
	color: #FFFFFF !important;
	background-color: #0B0B0B !important;
	border: 1px solid;
	border-color: #0B0B0B;
	border-bottom: 1px solid #0B0B0B;
	text-align: center !important;
}

.dark-theme .gsc-tabHeader.gsc-tabhInactive:hover {
	font-weight:600;
	color: #fff !important;
	background-color: #232323 !important;
	border:1px solid;
	border-color: #0B0B0B!important;
	border-top:1px solid #151515;
	border-bottom:none;
}

/* ================================
Tab Spacer
================================ */
.dark-theme .gsc-tabsArea .gs-spacer {
	display:inline-block !important;
	width:5px;
}

/* ================================
Spelling
================================ */
.dark-theme .gs-spelling {
	color: #fff;
	padding-left: 7px;
	padding-right: 7px;
}

.dark-theme .gs-spelling a {
	color:#7abfff !important;
	cursor:pointer;
	text-decoration:underline;
}

.dark-theme .gs-spelling a:hover {
	color:#7abfff !important;
	cursor:pointer;
	text-decoration:underline;
}

/* ================================	
Results
================================ */
.dark-theme .gsc-control-cse .gsc-table-result {
	width:100%;
	font-family:Helvetica,Arial,sans-serif!important;
	font-size:14px!important;
	line-height:1.5!important;
	/* padding-left: 5px !important; */
}

.dark-theme .gsc-result-info {
	text-align: left;
	color: #ffffff;
	font-size: 14px;
	padding-left: 8px;
	margin: 10px 0 10px 0;
}

.dark-theme .gs-result .gs-title, .dark-theme .gs-result .gs-title * {
	color:#7abfff !important;
	text-decoration:underline;
}

.dark-theme .gsc-control-cse .gs-result .gs-title a:hover {
	text-decoration:underline;
	color:#7abfff !important;
}

.dark-theme .gsc-control-cse .gs-result .gs-title, .dark-theme .gsc-control-cse .gs-result .gs-title * {
	font-family: Helvetica,Arial,sans-serif!important;
	font-size: 18px !important;
	line-height: 22px;
	padding-bottom: 5px;
	text-decoration: none;
	font-weight: 700;
	color: #7abfff !important;
	margin-bottom: 5px;
}

.dark-theme .gsc-webResult.gsc-result {
	padding: 15px !important;
	border-left: 8px solid #282828 !important;
	margin:0!important;
	/* border-bottom: 1px solid #FFF !important; */
	border-top: 1px solid transparent;
	border-right: 1px solid transparent;
	margin-top: -2px !important;
	margin-bottom: -2px !important;
}

.dark-theme .gsc-webResult.gsc-result:hover {
	border-left: 8px solid #7abfff !important;
	/* 	border-bottom: 1px solid #FFF !important; */
	border-top: 1px solid transparent !important;
	border-right: 1px solid #282828 !important;
	margin-bottom: -2px !important;
	margin-top: -2px !important;
}

.dark-theme .gsc-webResult.gsc-result:hover .gs-title * {
	color:#7abfff!important;
}

.dark-theme .gs-result .gs-visibleUrl {
	color:#7abfff !important;
	text-decoration:none;
}

.dark-theme .gs-bidi-start-align.gs-snippet {
	line-height:1.5;
}

.dark-theme .gsc-preview-reviews, .dark-theme .gsc-control-cse .gs-snippet, .dark-theme .gsc-control-cse .gs-promotion em, .dark-theme .gsc-control-cse .gs-snippet, .dark-theme .gsc-control-cse .gs-promotion em {
	color: #ffffff !important;
}

.dark-theme span.gs-fileFormat {
	color: #fff;
	font-size: 12px;
	padding-left: 8px;
}

.dark-theme .gs-webResult div.gs-per-result-labels a.gs-label {
	text-decoration: underline;
	cursor: pointer;
	padding: 3px;
	color: #7abfff;
	font-size: 14px;
}

.dark-theme .gsc-above-wrapper-area {
	border-bottom: 1px solid #E9E9E9;
	padding: 5px 0 5px 0;
}

/* ================================
Hide thumbnail images in results
================================ */
.dark-theme .gsc-thumbnail {
	display:none;
}

/* ================================
Pagination
================================ */
.dark-theme .gsc-results .gsc-cursor-box {
	margin-bottom: 10px;
	padding-top: 15px;
}

.dark-theme .gsc-results .gsc-cursor-box .gsc-cursor-page {
	border: 1px solid #0B0B0B !important;
	background-color: #0B0B0B;
	padding: 8px !important;
	color: #FFF !important;
	text-decoration: none !important;
	margin-right: 10px;
	display: inline;
	font-size: 15px;
}

.dark-theme .gsc-results .gsc-cursor-box .gsc-cursor-page:hover {
	border: 1px solid #0B0B0B;
	background-color: #282828;
	padding: 5px;
	color: #FFF !important;
	text-decoration: none;
}

.dark-theme .gsc-results .gsc-cursor-box .gsc-cursor-current-page {
	cursor:default;
	color: #fff !important;
	background-color: #2D2D2D !important;
	font-weight:700;
	text-decoration:underline!important;
}

.dark-theme .gs-per-result-labels {
	padding-left: 8px;
}

/* ================================
No Results
================================ */
.dark-theme .gs-no-results-result .gs-snippet,.gs-error-result .gs-snippet {
	padding:5px;
	margin:5px;
	border:1px solid #0B0B0B!important;
	background-color:#2D2D2D!important;
	color: #FFF!important;
	font-weight:700;
}

/* ================================
Branding
================================ */
.dark-theme .gcsc-branding {
	display:none!important;
}

.dark-theme .gssb_a > div > img {
	display: none;
}

.dark-theme .gssb_a > div > span {
	display: none;
}

/* ===============================
Bootstrap Dark Theme Overrides
================================== */

.dark-theme caption {
	padding-top: 0.75rem;
	padding-bottom: 0.75rem;
	color: #fff;
	text-align: left;
	caption-side: top;
}

.dark-theme .table-striped tbody tr:nth-of-type(odd) {
	background-color: rgba(0, 0, 0, 0.20);
}

/* ===============================
jQuery DataTables Dark Theme Overrides
================================== */

.dark-theme .dataTables_wrapper .dataTables_info {
	color: #fff;
}

/* =========================
END DARK THEME CSS
============================ */

/*
*** CUSTOM THEME
*/
.o-footer-middle.state-hasBgImage--blue .a-footer-links--heading {
	color: #ffffff;
	border-bottom: 1px solid #ffffff;
}

.o-footer-middle.state-hasBgImage--blue a, .o-footer-middle.state-hasBgImage--blue li a {
	color: #ffffff;
}

.o-footer-middle.state-hasBgImage--blue .a-home-white-btn-skin {
	color: #14325f;
}

.o-footer-middle.state-hasBgImage--blue .a-base-button {
	background: #ffffff;
	border: 1px solid #ffffff;
	color: #14325f;
}

.o-footer-middle.state-hasBgImage--blue .a-base-button:hover {
	background: #14325f;
	color: #ffffff;
	border: 1px solid #14325f;
}

h1,
.a-fullcolor-h1,
h3,
.a-fullcolor-h3,
h5,
.a-fullcolor-h5,
h6,
.a-fullcolor-h6 {
	color: #ffffff;
}

h2,
.a-fullcolor-h2 {
	color: #003893;
	padding-bottom: 0.5rem;
}

.a-fullcolor-h2-alt {
	color: #ffffff;
	padding-bottom: 0.5rem;
	margin-bottom: 2rem;
}

h4,
.a-fullcolor-h4 {
	color: #003893;
}

.a-fullcolor-h4-alt {
	color: #ffffff;
	padding-bottom: 0.5rem;
	margin-bottom: 1rem;
	border-bottom: 1px solid #ffffff;
}

.a-fullcolor-p {
	color: #282828;
}

.--layout-fullcolor-card-bg {
	background: #ffffff;
}

.m-cta--link {
	text-decoration: none !important;
}

.m-cta--link h2, .m-cta--link h3, .m-cta--link h4, .m-cta--link h5, .m-cta--link h6 {
	color: #ffffff;
	text-transform: capitalize;
	padding-bottom: 6px;
}

.m-cta--link p {
	color: #ffffff;
	margin-bottom: 0;
}

/* Fix for links in alerts */
.alert a {
	text-decoration: underline;
}
.dark-theme .alert a {
	color: #14325f;
}

/* Fix for .alert-warning dark theme p, li, a  */
.dark-theme .alert-warning p {
	color: #000000;
}

.dark-theme .alert-warning li {
	color: #000000;
}

.dark-theme .alert-warning a {
	color: #003893;
}

/* Remove Search X */
.dark-theme input[type="search"]::-webkit-search-decoration,
.dark-theme input[type="search"]::-webkit-search-cancel-button,
.dark-theme input[type="search"]::-webkit-search-results-button,
.dark-theme input[type="search"]::-webkit-search-results-decoration { 
	display: none;
}


/* =========================
OCELOT EMBED FIXES
============================ */
.dark-theme .MaxAI p, .dark-theme .MaxAI li {
	color: #282828;
}

.app-begin {
  text-align: center;
  text-decoration: underline;
}

.app-begin-container {
  display: flex;
  column-gap: 160px;
  justify-content: center;
  flex-wrap: wrap;
}
</style>
