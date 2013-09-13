#Documentation for Mobile Web Extensions


Mobile Web Extensions (MWE) are a set of frameworks selected by the Mosaic team to help our clients build consistent and content-rich web pages that serve as an extention to the currently native modules that are currently offered on the Mosaic Platform. A MWE is best used in cases where the data is more static than dynamic (news feeds, etc.). The sample code provided in this repo is designed to serve as a template to speed up the design and layout
process of the mobile website. 

What is a MWE Capable of?
===

Implementing a MWE is designed for a user that has a working knowledge of HTML and CSS, and ideally some working experience with modern frameworks like jQuery or Bootstrap. 


<p>Through a series of web frameworks selected by the Mosaic team for their mobile-friendly capabilities, broad community support, and long-term sustainability. The samples provided by the are designed for clients that may not have the development resources nor have near-future plans to create mobile-friendly sites. </p>

<p>A sample &#8216;module&#8217; consists of:</p>

<ul>
<li>a &#8216;home page&#8217;</li>
<li>a sample menu structure</li>
<li>examples of sub pages</li>
</ul>

In this sampple, two types of modules that are commonly implemented by our clients were used as examples to show best practices. 

+ Admissions
+ Alumni


The advantages of using a MWE is a starter version of a single codebase that, when deployed, will be able to render information properly on any mobile device. To make this possible, we ask that you try to adhere to the grid http://getbootstrap.com/css/#grid layout methodology used by the bootstrap framework. 


What frameworks are used in the samples?
===


Bootstrap 3.0 / jQuery 1.10.1 / Fontawesome 3.2.1 / normalize.css 2.1.3 / modernizr 2.6.2 

[Bootstrap](getbootstrap.com), an open-source, mobile-first framework maintained by a few employees at Twitter, is a rapidly growing framework supported by all modern smartphones and desktop browsers. Bootstrap is currently at release 3.0 and provides a consistent and responsive platform for presenting your content on the website, with simple tools that allow you to quickly layout your content and user interface elements.

[jQuery](jquery.org) is a very popular open-source Javascript library that runs on top of (and plays well with) the Bootstrap framework. It is currently used by 65% of the top 10,000 websites. jQuery can be used in cases that require actions to be performed to the site or the site&#8217;s data, i.e. Forms and Searching.

[Fontawesome](fontawesome.io) is a set of over 350 free scalable vector icons that allow you to add quick graphics to your website, and include a full set of commonly used social media icons for your use.

These frameworks are loaded into the sample documents by linking out to a Content Delivery Network, or CDN, and are not hosted or maintained by the Mosaic Team. These frameworks are updated quite often, and you will be notified of any major changes to these frameworks that might break your webpage. 


The sample also includes a suggested menu structure, which is built using [Pushy](https://github.com/christophery/pushy), a plugin for Bootstrap/jQuery, [[normalize]], a CSS plugin, and [modernizr](modernizr.com), a JS plugin.

#Making the sample content your own!

Feel free to use any text editor (we love [SubEthaEdit](http://www.codingmonkeys.de/subethaedit/) or [Brackets](brakets.io)) to edit the files.

Implementation
===



<p>To get this site up and running, copy the entire folder to your server, and add a link to the directory on your Mosaic Springboard. </p>
Using the sample content as a template, change the colors, branding and body text to your own.

Resources
===


<p>Though we do not directly provide support for MWE, we specifically chose our frameworks for their excellent community base. Here is a partial listing of great resources that will be helpful as you build new pages:</p>

[Bootstrap form generator](http://minikomi.github.io/Bootstrap-Form-Builder/) - a drag-and-drop interface for bulding out forms. <br>
[Bootsnipp](http://bootsnipp.com/snipps) - code snippets of common interface patterns <br>
[Bootsrap Documentation](http://getbootstrap.com/getting-started/) - great resource highlighting all the possible UI patterns available out-of-the-box

Warranty
===


<ul>
THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
</ul>


#Internal Documentation

Internal Maintenance Plan

Current Versions:
Bootstrap 3.0 / jQuery 1.10.1 / Fontawesome 3.2.1 / normalize.css 2.1.3 / modernizr 2.6.2




This set of frameworks are *usually* backwards compatible and upgrading to a newer version of a framework. 

Bootstrap: Release notes at http://blog.getbootstrap.com/
jQuery: http://blog.jquery.com/2013/07/03/jquery-1-10-2-and-2-0-3-released/
font awesome: http://fontawesome.io/whats-new/
normalize: https://github.com/necolas/normalize.css/
modernizr: http://modernizr.com/download/

These are all actively developed frameworks and JS libraries, and major updates to mobile web extensions should be made when release notes mention that there are deprecations or major feature changes to the libraries. For example, Bootstrap 3.0 changes many CSS classes cause updating the CSS/JS without replacing the HTML <div> tags will cause a website to break. Changes like this will not happen often. 

It is recommended that clients and client coaches that are looking to implement a MWE look into these frameworks and 

Ideally, release notes should be digested by the CSM team and relevant changes to the frameworks should be pushed to the clients along with a set of instructions for updating their own code. 

The menu structure is a fork of https://github.com/christophery/pushy, and the underlying js/CSS should be updated once the development reaches a 1.0 milestone. 




#Outstanding issues:

Tablet support: though all of these frameworks support responsive layouts, it is the responsibility of the client to take care of their content layout. Clients should try to adhere to http://getbootstrap.com/css/#grid grid guidelines to optimize display on multiple devices. 


Support of News and Events
Though we do not want to replicate things that are already offered as part of our native module selection, many currently existing mobile web modules implemented do contain a news/events feed functionality that allows you to drill deeper into a MW app. If a client does request functionality, we have tried using the zRSSfeed jquery plugin, which is a very simple code injection that allows you to load rss feed entries. This is not supported, and has many dependencies, including a google feeds API that has the potential to be deprecated. 



Finding a counselor (admissions only)
Apps made by other companies like Straxis offer an admissions module that allows you to find a counselor. Because this uses many native API and SDK integrations, many of these functions (geolocation, larger database work, etc.) is not possible or very hard to do through a mobile web extension. We should advise our clients to rethink how they want to present information like counselor information and point them towards a more static presentation model. 















Sample copy text:

This is a sample body text for your home page. We suggest keeping the front page to a minimum, and allowing a user to discover links through the menu and links on this page. use this page to explain the benefits of the alumni organization, while linking to a more detailed list of benefits. 

Also use this page to include enticing photos. 




Sample networking page:

The Networking page can include many links to different areas that might provide career advancement or alumni networking links. 

Facebook Alumni Page
Linkedin University Page http://www.linkedin.com/edu/?tab=schools










