# Shopify-Slider-1
Shopify dev slider free code


Go to this file

Layout > theme.liquid

Add this code in </head> tag above

 {{ 'section-main-product.css' | asset_url | stylesheet_tag }}
 
 {{ 'section-featured-product.css' | asset_url | stylesheet_tag }}
 
 {{ 'component-price.css' | asset_url | stylesheet_tag }}
 
 {{ 'bootstrap.min.css' | asset_url | stylesheet_tag }}
 
 
add this code in </body> tag above


<script src="{{ 'product-form.js' | asset_url }}" defer="defer"></script>


<script src="{{ 'bootstrap.bundle.min.js' | asset_url }}"></script>


<script src="{{ 'popper.min.js' | asset_url }}"></script>


<script src="{{ 'bootstrap.min.js' | asset_url }}"></script>

