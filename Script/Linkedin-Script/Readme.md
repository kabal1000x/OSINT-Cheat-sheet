# Copy and paste the below bookmarklets into a new bookmark in your browser of choice

# Extract Larger Profile Photo (Must be activated when viewing a Linkedin Profile)

javascript: 

```
var currentLocation = window.location.href;  
var newLocation = currentLocation + "detail/photo/";  
window.location.replace(newLocation);   
```

# View Recent Activity on a profile

javascript:  

```
var currentLocation = window.location.href;   
var newLocation = currentLocation + "detail/recent-activity/";   
window.location.replace(newLocation);
```

# Find Account Via Email (Functionality removed by LinkedIn)

javascript:  

```
var email = prompt("Please enter target's email address: ");   
var url = "https://www.linkedin.com/sales/gmail/profile/viewByEmail/" + email;   
window.open(url,"_self");
```

Source by : https://github.com/sinwindie/OSINT/blob/master/LinkedIn/Bookmarklet%20Tools