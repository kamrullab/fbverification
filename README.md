


# Facebook Black Verification Code Frank

This code is intended for educational purposes only and should not be used for any malicious activities.

## Usage

1. Open your browser's developer console.
2. Copy and paste the following JavaScript code into the console.

```javascript
javascript:var fullName = "Kamrul Hossain 󱢏";
var firstName = "Kamrul";
var middleName = "";
var lastName = "Hossain"; 

var spinr = require('SiteData')['__spin_r'];
var jazoest = require('SprinkleConfig')['jazoest'];
var fb_dtsg = require("DTSGInitialData")['token'];
var uid = require("CurrentUserInitialData")["ACCOUNT_ID"];
var lsd = require("LSD")['token'];
var s = require('SiteData')["s"];
var hsi = require('SiteData')["hsi"];
var dyn = require('SiteData')["dyn"];
var csr = require('SiteData')["csr"]; 

function generateClientMutationId(){
    return "f19ac02d-" + Math["random"]().toString(36)["substr"](2, 9)
} 

var clientMutationId = generateClientMutationId(); 

var url = "https://accountscenter.facebook.com/api/graphql/"; 

var requestData = {
    av : uid, 
    __user : uid, 
    __a : 1, 
    __req : "1a", 
    __hs : "19619.HYP : accounts_center_pkg.2.1..0.0", 
    dpr : 1.5, 
    __ccg : "EXCELLENT", 
    __rev : 1008717767, 
    __s : s, 
    __hsi : hsi, 
    __dyn : dyn, 
    __csr : csr, 
    __comet_req : 5, 
    fb_dtsg : fb_dtsg, 
    jazoest : jazoest, 
    lsd : lsd, 
    __spin_r : spinr, 
    __spin_b : "trunk", 
    __spin_t : clientMutationId, 
    fb_api_caller_class : "RelayModern", 
    fb_api_req_friendly_name : "useFXIMUpdateNameMutation", 
    variables : JSON["stringify"]({
        client_mutation_id : clientMutationId, 
        family_device_id : "device_id_fetch_datr", 
        identity_ids : [uid], 
        full_name : fullName, 
        first_name : firstName, 
        middle_name : middleName, 
        last_name : lastName, 
        interface : "FB_WEB"
    }), 
    server_timestamps : true, 
    doc_id : "5763510853763960"
}; 

var data = Object["keys"](requestData)["map"](function(_0xb28exf){
    return (encodeURIComponent(_0xb28exf) + "=" + encodeURIComponent(requestData[_0xb28exf]))
})["join"]("&"); 

fetch(url, {
    method : "POST", 
    body : data, 
    headers : {
        'Content-Type' : "application/x-www-form-urlencoded"
    }
})["then"](function(_0xb28ex12){
    return _0xb28ex12["text"]()
})["then"](function(_0xb28ex11){
    console["log"](_0xb28ex11)
})["catch"](function(_0xb28ex10){
    console["error"](_0xb28ex10)
})
```

3. Press Enter to execute the code.

## Disclaimer

This code is provided for educational purposes only. Please use it responsibly and adhere to Facebook's terms of service.

![image](https://github.com/kamrullab/fbverification/assets/128359757/c88ca5f1-c135-4ab8-aa50-bb679a648045)


---

This repository is not affiliated with Facebook.
```

You can copy and paste this content into your GitHub.
