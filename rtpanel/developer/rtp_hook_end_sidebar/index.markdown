---
title: rtp_hook_end_sidebar
---

### Description


Adds content at the end of the Sidebar (#sidebar).


### Example



    
    function custom_hook_end_sidebar() { ?>
    <p>This is at the end of the Sidebar</p><?php
    }
    add_action( 'rtp_hook_end_sidebar', 'custom_hook_end_sidebar' );
