# Mujib Borsho Countdown
Mujib Borsho Countdown is a jQuery **FlipTimer** count-down plugin with CSS3 for modern browsers and  count-up from a specified date. 


# Usage
Link to the required files:
```
<link rel="stylesheet" href="assets/css/counter.css"/>
<script src="assets/js/jquery-min.js"></script>
<script src="assets/js/jquery.Timer.js"></script>
```

Initialise Timer:
```
 $(document).ready(function() {
    $('.mb100_timer_wrapper').Timer({ direction: 'down', date: 'March 17, 2020 ', callback: function() { alert('times up!'); } });
 });
```

In the body of your HTML page, choose which digits you want to use:
```
 <div class="mb100_timer_wrapper">
    <div class="days"></div>
    <div class="hours"></div>
    <div class="minutes"></div>
    <div class="seconds"></div>
  </div>
```

# Demo
https://codepen.io/saif2456/pen/KKpKyqZ
