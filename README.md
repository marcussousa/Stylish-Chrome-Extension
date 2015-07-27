# Stylish-Chrome-Extension
A bunch of CSS customizations for Stylish Extension (Chrome)

Link to Stylish Extension -> https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?utm_source=chrome-ntp-icon


Facebook
-------

Grab this -> https://userstyles.org/styles/53261/facebook-wide-flat-design

& extend with:

    #leftCol {
        position: fixed
    }
    #navItem_983686418327131,
    #navItem_230259100322928,
    #eventsNav,
    #pagelet_welcome_box,
    #interestsNav,
    #pagesNav,
    #pagelet_sidebar,
    #pinnedNav,
    #findFriendsNav,
    #u_0_f,
    #appsNav ,
    #developerNav,
    #pagelet_side_ads {
        display: none;
    }
    /* 
    ======  
    modal 
    ======  
    */
    ._3qx ._3ixn {
        background-color: #868695;
        opacity: .4;
    }
    ._n3 {
        border: 1px solid rgba(0,0,0,.2);
        box-shadow: 0 8px 55px rgba(54,65,89,.3)
    }


----------

Whats App (responsive mode)
-------

Hover the header to show the list of friends

> **Note:**

> - Makes more sense if you use as a single window on your desktop

    @media screen and (max-width: 500px) {
   		.app-wrapper-main.app-wrapper {
   			min-width:100%
   		}
    	
    	.drawer-container-mid,.drawer-container-right,
    	.pane-chat,.pane-intro {
	    	width:100%
    	}
    	
    	.pane-list,
    	.drawer-container-left {
	    	height:60px;
	    	position:absolute;
	    	width:100%
    	}
    	
    	.pane-list:hover,
    	.drawer-container-left:hover {
	    	border:1px solid rgba(0,0,0,.8);
	    	border-top:none;
	    	box-shadow:0 8px 45px rgba(54,65,89,1);
	    	cursor:pointer;
	    	height:80%
    	}
    	
    	.pane-chat-header {
	    	margin-top:60px
    	}
    	
    	.pane-list:hover .pane-list-header {
	    	background:#009688
    	}
    }

 
