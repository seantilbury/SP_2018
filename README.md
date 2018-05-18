# SP_2018
SP_2018 dev child theme


## Colours

**Black** 	    #000000

**Dark Grey** 	#202020

**White**		    #FFFFFF

**Red** 		    #E52027

## Fonts

Rajdhani (google font)

## Popups trigger classes

.16plus = Age restricion 16+ popup

.popup-contact = Book Now Popup

## Shortcodes for Prices and Packages

**Single Activities**
Price of Single Activity

[pods name="single_activity" slug="slug-of-activity" template="Single Activity Template"]



Special Offers

[pods name="multiple_activity_pa" where="quads.meta_value='1'" template="Multi Activity Package List"]




## Font Awesome Icons
https://fontawesome.com/icons

Phone ```<i class="fas fa-phone"></i>```

Map ```<i class="fas fa-map"></i>```

Plane ```<i class="fas fa-plane" data-fa-transform="rotate-315"></i>```

Facebook ```<i class="fab fa-facebook-square"></i> ```

Twitter ```<i class="fab fa-twitter-square"></i> ```
 
Youtube ``` <i class="fab fa-youtube"></i> ```

Instagram ```<i class="fab fa-instagram"></i> ```

Visa ```<i class="fab fa-cc-visa"></i>```

Mastercard ```<i class="fab fa-cc-mastercard"></i>```

Paypal ```<i class="fab fa-paypal"></i>```

Tripadvisor ```<i class="fab fa-tripadvisor"></i> ```

Checkout ``` <i class="fas fa-shopping-cart"></i> ```

FAQ ``` <i class="fas fa-question-circle"></i> ```

## Code Locations

**functions.php** 
```Call Us``` ```Book Now ``` ```Directions```
floating footer

**header.php**

```Just a short drive from Gatwick Airport```

## Image Sizes
Special Offer images
350x350

Header Slider Frontpage
1520 x 440

Activity pages slider image sizes
1100x450

Activity Banner 990x100 **no longer used replaced by slider**

Posts Featured Image 300x300

## Duplicating Pages

Navigate to the page you wish to copy (the source)
click "Page Builder"
top left, dropdown 
"Duplicate Layout"
Change Page title 
change URL / Permalink
click "Launch Page Builder"

## 301 Redirects
Old > New
https://www.southernpursuits.co.uk/corporate-events/team-building-days/ .co.uk/team-building-days/


## .htaccess (production only) 'Leverage Browser Caching'

<IfModule mod_expires.c>
  FileETag MTime Size
  AddOutputFilterByType DEFLATE text/plain text/html text/xml text/css application/xml application/xhtml+xml application/rss+xml application/javascript application/x-javascript
  ExpiresActive On
  ExpiresDefault "access plus 1 seconds"
  ExpiresByType text/html "access plus 600 seconds"
  ExpiresByType application/xhtml+xml "access plus 600 seconds"
  ExpiresByType text/css "access plus 1 month"
  ExpiresByType text/javascript "access plus 1 month "
  ExpiresByType application/javascript "access plus 1 month"
  ExpiresByType application/x-javascript "access plus 1 month"
  ExpiresByType image/x-icon "access plus 1 year"
  ExpiresByType image/jpeg "access plus 1 year"
  ExpiresByType image/png "access plus 1 year"
  ExpiresByType image/gif "access plus 1 year"
</IfModule>
