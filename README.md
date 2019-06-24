# demo
AskDevOps.org Demo Repository

How it works?
-------------
JQuery is used to call this file
Server side data is stored in `qa-cache/mydat.txt`

INSTALLATION:
-------------
- Copy the below files to the root of Q2A website
  - `c.php`
  - `qa-cache/mydat.txt`
- Paste the below code where you need to display the online user count

`<script>$(window).on('load', function() {$("#_c1").load("/c.php");});</script><span id="_c1">..</span>`
