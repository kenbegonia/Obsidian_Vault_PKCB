# CPOSTech 

### WP Login URL
```
https://cpostechnologies.com/wp-login.php?redirect_to=https%3A%2F%2Fcpostechnologies.com%2Fwp-admin%2Fpost.php&reauth=1
```

### WordPress Credentials
- `Username:` CPOSTECH  
- `Password:` Eb&EPtMyy9vEP(fVB*4j)fog

### Fiuu Credentials
- `Merchant ID`: condor_Dev  
- `Verify Key`: b0114ba30cdab604f925a584c0a0ec8c  
- `Secret Key`: 587bea875f10cc64a7be86787c8980f8  
- `Return URL`:  (see below)
  
```
	<script type='text/javascript'>  
	var sa = 'condor_Dev';  
	window.onload = function() {  
	    m = document.createElement('IFRAME');  
	    m.setAttribute('src', "[https://www.onlinepayment.com.my/MOLPay/API/chkstat/returnipn.php?treq=0&sa=](https://www.onlinepayment.com.my/MOLPay/API/chkstat/returnipn.php?treq=0&sa= "https://www.onlinepayment.com.my/MOLPay/API/chkstat/returnipn.php?treq=0&sa=")" + sa);  
	    m.setAttribute('seamless', 'seamless');  
	    m.setAttribute('width', 0);  
	    m.setAttribute('height', 0);  
	    m.setAttribute('frameborder', 0);  
	    m.setAttribute('scrolling', 'no');  
	    m.setAttribute('style', 'border:none !important;');  
	    document.body.appendChild(m);  
	};  
	</script>
```
