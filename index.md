<!DOCTYPE html>
<html>
<head>
<title>Experience Rads</title>
<link rel="stylesheet" href="/CSS/index.css">
</head>
<body>
      <ul class="navbar">
          <li class="logo"><a href="">Experience<strong>Rads</strong></a></li>
          <li><a href="cc_TributePage.html">Tribute Page</a></li>
          <li><a href="cc_Survey.html">Survey Form</a></li>
          <li><a href="cc_LandingPage.html">Landing Page</a></li>
          <li><a href="cc_TechnicalPage.html">Technical Page</a></li>
          <li><a href="portfolio.html">Portfolio</a></li>
      </ul>
    <div id="main">  
    <div><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam magna ex, pharetra ac ex id, suscipit condimentum arcu. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vestibulum placerat justo id lorem lobortis aliquam. Proin varius elementum blandit. Duis sagittis blandit augue, non rhoncus orci aliquet iaculis. Morbi condimentum leo et ante condimentum egestas. Sed a cursus tortor, vitae convallis eros. Sed mollis, odio in viverra semper, dui mi porta risus, sit amet pulvinar arcu odio nec risus. Aliquam augue lorem, dictum a ullamcorper id, dignissim id nibh. Cras a blandit massa. Aenean nulla sem, malesuada eget erat tempor, vulputate egestas felis. Phasellus placerat in quam euismod congue. Cras porttitor fermentum maximus.

    In sed porttitor mi. Phasellus egestas efficitur justo vitae elementum. Phasellus leo nisi, tempus nec sapien eget, maximus scelerisque neque. Praesent sed eleifend risus, gravida interdum velit. Sed vel est feugiat, lobortis nunc ac, pulvinar felis. Donec metus tellus, laoreet et nisi et, tempus ornare lectus. Integer ullamcorper sit amet nunc vitae vehicula. Mauris laoreet ex in nulla vulputate, eget pellentesque neque tempus. Aenean vel consectetur mi, non sollicitudin quam. Duis placerat leo non elit dapibus, vel commodo sapien maximus. Donec sed turpis et augue vulputate tempus eu nec nunc.
    
    Morbi ligula nunc, rutrum id ex vel, lacinia dictum sapien. Ut varius mi sit amet nisi gravida, quis faucibus ante auctor. Morbi convallis imperdiet turpis sit amet pretium. Nam ultricies sodales blandit. Nulla a nulla maximus, tempor sem a, semper odio. Morbi imperdiet convallis varius. Phasellus tincidunt, lacus imperdiet vulputate vestibulum, ipsum urna posuere felis, a venenatis mi nulla tempus nulla. In ut tempor nunc, ac imperdiet magna. Proin pulvinar consequat lorem vitae condimentum.
    
    Cras maximus, arcu eu varius efficitur, diam dui scelerisque diam, eget tempor libero erat sit amet leo. Integer sit amet fermentum ligula. Mauris in nulla vitae enim bibendum ornare. Sed maximus iaculis metus eget tincidunt. Vestibulum quis diam nec dui feugiat posuere vitae sed ante. Pellentesque fermentum, mauris quis hendrerit elementum, leo nisl pellentesque dui, id suscipit mauris velit id arcu. Cras odio libero, lobortis vel fringilla vitae, maximus et lacus. Nulla suscipit efficitur ipsum, pulvinar lobortis tellus egestas sed. Sed ultricies pharetra lectus, et eleifend est tempus eget. Nunc eu massa nec risus iaculis fringilla at ut nisl. Fusce a blandit felis. Praesent eget volutpat arcu. Fusce at ante blandit, iaculis mi vel, consequat magna. Fusce non libero ultricies, vestibulum enim vitae, mollis orci.
    
    Quisque finibus nibh leo, in tristique dui venenatis non. Sed cursus euismod felis, a condimentum metus egestas at. Suspendisse interdum quis nisl quis dictum. Aliquam imperdiet sem lacus, non mollis nisi rhoncus eu. Vestibulum ullamcorper pharetra felis, et placerat massa. Etiam turpis est, porttitor quis congue vitae, consequat nec eros. In quis nibh vitae ligula vestibulum vehicula a vitae erat. Nulla ornare, augue non ullamcorper mattis, erat massa pulvinar risus, cursus blandit lorem orci in nibh.</p></div>
    </div>
<!-- Start of Button w/ Modal Component -->
<button id="myBtn">Site<br>Info</button>
<div id="myModal" class="modal"> 
    <div class="modal-content"> <!-- Modal content -->
        <span class="close">&times;</span>
        <h4>First ever Page</h4>
        <p>The first site I made. I used the limited skills i gained while going though FreeCodeCamps HTML and CSS Course. I will probably turn this into a landing page for the EXPerience Rads Media Group<br> Code: HTML, CSS and JavaScript (Only for this button so far).<br> Hosting: nginx.<br> Misc: Git, GitHub.<br>Last Updated: 14/07/2020. </p>
    </div> 

</div> 
<!-- End of Button w/ Modal Component -->
<footer id="ER-footer">
    <h6 id="ER-footer-header">experience<strong>Rads</strong> network</h6>
    <div id="ER-footer-div">
        <a class="ER-footer-link" href="index.nginx-debian.html">experienceRads</a>
        <a class="ER-footer-link" href="cc_Portfolio.html">Jai's Portfolio</a>
        <a class="ER-footer-link" href="cc_TechnicalPage.html">Technical Page</a>
        <a class="ER-footer-link" href="cc_LandingPage.html">Landing Page</a>
        <a class="ER-footer-link" href="cc_Survey.html">Survey Form</a>
        <a class="ER-footer-link" href="cc_TributePage.html">TributePage</a>
    
    </div>
</footer>
</body>
<script>

    // Start of Button w/ Modal component
    // Get the modal
    var modal = document.getElementById("myModal");
    // Get the button that opens the modal
    var btn = document.getElementById("myBtn");
    // Get the <span> element that closes the modal
    var span = document.getElementsByClassName("close")[0];
    // When the user clicks the button, open the modal 
    btn.onclick = function() {
      modal.style.display = "block";
    }
    // When the user clicks on <span> (x), close the modal
    span.onclick = function() {
      modal.style.display = "none";
    }
    // When the user clicks anywhere outside of the modal, close it
    window.onclick = function(event) {
      if (event.target == modal) {
        modal.style.display = "none";
      }}
    // End of Button w/ Modal component

    </script>
</html>
