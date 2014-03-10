================================================================================
[Author] mayanktechpro

OPENCART SEO PACK  v2.5                                            02 Apr 2012


[Description]
This pack contains the following extensions:
1. Keywords Generator for all products
2. Meta Description Generator
3. Related Products Generator
4. Tag Generator + BONUS
5. Product SEO Plus 2 more SEO features
6. Canonical Categories & Brands
7. Canonical Product
8. Friendly SEO URLS Generator
9. SEO Friendly URLs
10. Custom Titles
11. Clear SEO
12. SEO Report

[Compatibility]
Supports OpenCart Version 1.5.1.3-1.5.2.x (vqmod required)

================================================================================

--------------------------------------------------------------------------------
[Installation]
--------------------------------------------------------------------------------
		0. Make sure you have vqmod installed. If you don't have vqmod installed:
			- To install vqmod, you will have to download it from http://code.google.com/p/vqmod/downloads/list  
			- Download latest version : vqmod-2.1.6-opencart.zip
			- Copy it into vqmod folder in the root of your site and install it ( http://yoursite.com/vqmod/install )
		1. No files will be overridden
		2. Copy 'vqmod' and 'admin' folders in the root folder of your website
		3. Grant rights in admin area -> System -> Users -> User Groups
		4. Enter in Opencart SEO Pack interface admin area -> Catalog -> SEO Pack 
		
--------------------------------------------------------------------------------
[Others]

Enable Opencart SEO

In order to enable Opencart SEO, you will have to make 2 important steps:

1. You will have to enable SEO URLS  in Admin Area -> System -> Settings -> Your main store -> Edit -> Server tab -> Use SEO URL's 

2. The second step is to assure that your hosting has mod-rewrite enabled and then you will have to rename htaccess.txt to .htaccess in the root of your site.

If your OC is installed in a subfolder of your domain, edit .htaccess:
	- FIND 					RewriteBase /
	- REPLACE WITH 			RewriteBase /yoursubfolder/
	

--------------------------------------------------------------------------------
[Updating from Opencart SEO Pack 1.1]

		1. Back-up and remove the following files:
			- vqmod/xml/tag_generator.xml 
			- vqmod/xml/keywords_generator.xml
			- vqmod/xml/meta_description_generator.xml
			- vqmod/xml/rp_generator.xml 
			- vqmod/xml/clear_seo.xml
			- vqmod/xml/seo_url_generator.xml
		2. Copy 'vqmod' and 'admin' folders in the root folder of your website. Some Opencart SEO Pack old files will be overridden.
		3. Grant rights in admin area -> System -> Users -> User Groups
		4. Enter in Opencart SEO Pack interface admin area -> Catalog -> SEO Pack 	