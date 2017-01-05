# Static Split

**-- In Development --**
A Static Site A/B Testing Tool that preserves canonical URLs

 
###What Is It
Static Split allows static sites to easily A/B test landing pages while preserving the canonical URL of the original URL path.

###How It Works
Using URL parameters and javascript, Static Split will search your site's top level directory for a folder matching the value of the URL parameter **'?lp='**, and pull the index.html file for this. 

**Example:**
http://heath.co/about?lp=bio

Upon loading the domain path **/about** and adding the URL parameter **?lp** with the value **bio**, Static Site will import the index.html file from heath.co/**bio** and replace **/about** with it. 

###What Purpose Does Static Split Serve
This allows tools such as Google Analytics still recognize traffic going to a target domain path while allowing the content of said page to be easily interchangeable. 