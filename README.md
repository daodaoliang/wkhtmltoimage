wkhtmltoimage
=============

http://wkhtmltopdf.org/usage/wkhtmltopdf.txt

and most important usage like:
wkhtmltoimage --width 354 --custom-header 'User-Agent' 'Mozilla/5.0 (iPhone; U; XXXXX like Mac OS X; eAppleWebKit/420+ (KHTML, like Gecko) Version/3.0 Mobile/241 Safari/419.3' --custom-header-propagation --run-script '<script>var all = document.getElementsByTagName("img");for (var i = 0; i < all.length; i++) {document.write("aaaaaaaaaaaaaa"+i)}</script>' --debug-javascript   --javascript-delay 5000 --quality 40  'http://lee.tmall.com/' 1.jpg 

