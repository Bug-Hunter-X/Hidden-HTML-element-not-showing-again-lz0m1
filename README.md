# Uncommon HTML Bug: Hidden Element Not Showing Again

This repository demonstrates a simple HTML bug where an element is hidden using JavaScript, but there's no mechanism to make it visible again.  The bug occurs because the `myFunction()` removes the div element using display:none; but there is no provision to make it visible again. 

## Bug Description

A button click hides a div element. The element remains hidden even after multiple button clicks, causing unexpected behavior.  This is problematic because the missing restore condition breaks the functionality and makes the div permanently hidden.