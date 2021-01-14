Muntra referral react widget

# Placing a widget on a page

First, place the <div> tag in the site markup, with the following attributes:
  
  Required attributes:
  
  - `class`: "muntra-referral-widget",
  - `muntra_clinic_id`: "clinic_id".
  
  Example: 
  
  ````
    <div
     class="muntra-referral-widget"
     muntra_clinic_id="1"
    />
  ````

  Secondly, place a tag:
    
  ````
  <script type = "text/javascript" src = "https://muntra-dev.github.io/referral-page/index.js"> </script>
  ````
  At the end of the body, to connect the widget to the page.
  
Expample of connecting widget to a page:

````
 <body>
   <div
     class="muntra-referral-widget"
     muntra_clinic_id="1"
   ></div>
   <script type="text/javascript" src="https://muntra-dev.github.io/referral-page/index.js"></script>
 </body>
````

# Styling a widget window

Use muntra-referral-widget styles to style the widget window:
````
.muntra-referral-widget {
  height: 1000px;
  margin: 10px auto 0;
}
````
