---
layout: page
title: People
---
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
      img {
        height: 240px;
        width: 20%;
        padding-left: 25px;
        padding-right: 25px;
      }
     /* The Modal (background) */
      .modal {
        display: none; /* Hidden by default */
        position: fixed; /* Stay in place */
        z-index: 1; /* Sit on top */
        padding-top: 100px; /* Location of the box */
        left: 0;
        top: 0;
        width: 100%; /* Full width */
        height: 100%; /* Full height */
        overflow: auto; /* Enable scroll if needed */
        background-color: rgb(0,0,0); /* Fallback color */
        background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
      }
      .modal-content {
        position: relative;
        background-color: #fefefe;
        margin: auto;
        padding: 0;
        border: 1px solid #888;
        width: 50%;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
        -webkit-animation-name: animatetop;
        -webkit-animation-duration: 0.4s;
        animation-name: animatetop;
        animation-duration: 0.4s
      }
      @-webkit-keyframes animatetop {
        from {top:-300px; opacity:0} 
        to {top:0; opacity:1}
      }
      @keyframes animatetop {
        from {top:-300px; opacity:0}
        to {top:0; opacity:1}
      }
      .close {
        color: black;
        float: right;
        font-size: 28px;
        font-weight: bold;
      }
      .close:hover,
      .close:focus {
        color: #000;
        text-decoration: none;
        cursor: pointer;
      }
      .modal-header {
        padding: 2px 16px;
        background-color: white;
        color: black;
        border-bottom: 1px solid #e9ecef;
      }
      .modal-body {padding: 2px 16px;}

   </style>
  </head> 
 
 </html>

<img src="/photos/AKilicarslan.jpeg" alt="Atilla Kilicarslan" align="left"/>
<h3>Atilla Kilicarslan</h3>


<h4>akilica2@central.uh.edu</h4>

<!-- Trigger/Open The Modal -->
<button class="modal-button" href="#akilicarslan">About Atilla</button>

<!-- The Modal -->
<div id="akilicarslan" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
    <div class="modal-header">
      <span class="close">×</span>
      <h2>Atilla Kilicarslan, PHD</h2>
    </div>
    <div class="modal-body">
      <img src="/photos/AKilicarslan.jpeg" alt="Atilla Kilicarslan" align="left"/>
      <p>Dr Atilla Kilicarslan (Co-PI) is a Research Assistant Professor at the University of Houston, Electrical and Computer Engineering Department. He specializes in Robotics, Control systems, Bain Machine Interfaces, Adaptive systems, Signal De-noising, and Spatial Sensory Data Enhancement.</p>
    </div>
   </div>

</div>



<!-- Trigger/Open The Modal -->
<button class="modal-button" href="#myModal2">About First Name</button>

<!-- The Modal -->
<div id="myModal2" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
    <div class="modal-header">
      <span class="close">×</span>
      <h2>Modal Header</h2>
    </div>
    <div class="modal-body">
      <p>Some text in the Modal Body</p>
      <p>Some other text...</p>
    </div>
    <div class="modal-footer">
      <h3>Modal Footer</h3>
    </div>
  </div>

</div>





<script>
// Get the button that opens the modal
var btn = document.querySelectorAll("button.modal-button");

// All page modals
var modals = document.querySelectorAll('.modal');

// Get the <span> element that closes the modal
var spans = document.getElementsByClassName("close");

// When the user clicks the button, open the modal
for (var i = 0; i < btn.length; i++) {
 btn[i].onclick = function(e) {
    e.preventDefault();
    modal = document.querySelector(e.target.getAttribute("href"));
    modal.style.display = "block";
 }
}

// When the user clicks on <span> (x), close the modal
for (var i = 0; i < spans.length; i++) {
 spans[i].onclick = function() {
    for (var index in modals) {
      if (typeof modals[index].style !== 'undefined') modals[index].style.display = "none";    
    }
 }
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target.classList.contains('modal')) {
     for (var index in modals) {
      if (typeof modals[index].style !== 'undefined') modals[index].style.display = "none";    
     }
    }
}
</script>




      
        
      
      
     


