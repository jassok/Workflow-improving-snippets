Clearfix
--------

Trigger: clearfix
````html
<div class="clearfix">&nbsp;</div>
````

Comments
--------
Trigger: bug, fixme, note, todo
````php
<?php //-- BUG: ${1} ?>
<?php //-- FIXME: ${1} ?>
<?php //-- NOTE: ${1} ?>
<?php //-- TODO: ${1} ?>
````

IFIE
----
Trigger: ifie
````html
<!--[if ${1}]>${2}<![endif]-->
````

Inputs
------
Trigger: finput
````html
<input type="${1}" name="${2}" />
````

Stylesheet
----------
Trigger: chref
````html
<link rel="stylesheet" type="text/css" href="${1}" />
````

jQuery
------
Trigger: jquery
````javascript
<script type="text/javascript">
\$(function () {
${1}
});
</script>
````

External Script
---------------
Trigger: jsrc
````html
<script type="text/javascript" src="${1}"></script>
````