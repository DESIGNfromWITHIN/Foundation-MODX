Foundation MODX
MODX Revolution template based on Foundation from Zurb (http://foundation.zurb.com/)

-----------------------------
ABOUT
-----------------------------

This is a very minimal MODX Revolution template, with this template you can quickly install to start using the fantastic Foundation framework.

-----------------------------
QUICK-START LIST
-----------------------------

You need:
- to move all files in: <your_website_root>/assets/templates/foundation_modx/
- "template_header" chunk (static file: <your_website_root>/assets/templates/foundation_modx/template_header.html)
- "template_footer" chunk (static file: <your_website_root>/assets/templates/foundation_modx/template_footer.html)
- "Basic page" template (static file: <your_website_root>/assets/templates/foundation_modx/template_basic_page.html)
- logo.png (uploaded to: <your_website_root>/assets/templates/foundation_modx/images/)
- "footer_content" chunk (with the HTML content for the footer)
- Wayfinder (install the latest Wayfinder package)

-----------------------------
INSTALLATION
-----------------------------

- Copy the files folder to:
<your_website_root>/assets/templates/foundation_modx/

- Create a Chunk called "template_header"
Select "Is Static"
Select "Filesystem" under "Media Source for Static File"
Point "Static File" to: "<your_website_root>/assets/templates/foundation_modx/template_header.html"

- Create a Chunk called "template_footer"
Select "Is Static"
Select "Filesystem" under "Media Source for Static File"
Point "Static File" to: "<your_website_root>/assets/templates/foundation_modx/template_footer.html"

- Create a Template called "Basic page"
Select "Is Static"
Select "Filesystem" under "Media Source for Static File"
Point "Static File" to: "<your_website_root>/assets/templates/foundation_modx/template_basic_page.html"

- Add a logo
Upload your website logo (as a PNG called "logo.png") to: "<your_website_root>/assets/templates/foundation_modx/images/"

- Create a Chunk called "footer_content"
Add the (HTML) content for your footer here.

- Install the latest version of "Wayfinder"
Go to "System" > "Package Management" > "Download Extras" > Search for "Wayfinder" > Install "Wayfinder".