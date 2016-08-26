# JQuery Nigeria State and LGA selection

This library allows you to programmatically retrieve all the states of Nigeria, or to get all the local governments in a particular state

To make use of this library, just include the script via
> <script src="jquery.stateLga.js"></script>

You must note that the library depends on jQuery and will not *actually* work without jQuery.

### Retrieving all the states in Nigeria
<script>
console.log($.nigeria.states());
</script>

### Retrieving all the local government in a given state
<script>
console.log($.nigeria.abia);
</script>

### How About UI Implementation?
You can have 2 dropdown lists that allows you to have a dropdown list of states, and when a state is selected, populates another dropdown of the local governments
This can be found in the index.html example

### Version
1.0.0



