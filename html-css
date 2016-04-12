<script language='javascript' src='https://ajax.googleapis.com/ajax/libs/jquery/1.6.4/jquery.min.js' type='text/javascript'/>
<script type='text/javascript'>//<![CDATA[
/**
this script was written by Confluent Forms LLC http://www.confluentforms.com
for the BlogXpertise website http://www.blogxpertise.com
any updates to this script will be posted to BlogXpertise
please leave this message and give credit where credit is due!
**/
$(document).ready(function() {
  // change the dimension variable below to be the pixel size you want
  var dimension = 640;
  // this identifies the Mobile Index Thumbnail div element, finds each image in it, and resizes it
  $('.mobile-index-thumbnail').find('img').each(function(n, image){
    var image = $(image);
    image.attr({src : image.attr('src').replace(/s\B\d{2,4}/,'s' + dimension)});
    image.attr('width',dimension);
    image.attr('height',dimension);
  });
});
//]]></script>
<style>
.mobile-index-thumbnail img {
width: 100% !important;
height: 100% !important;
text-align: center;
margin: 0 auto;
padding: 5px;
display: block;
  }
.mobile-index-thumbnail {
float: none;
margin: 0 auto;
padding: 5px;
}
</style>
