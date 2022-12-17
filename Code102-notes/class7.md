# JavaScript Functions

A function can:

- Assigned to variables
- Assigned to a property of an object
- Passed as an paramter
- Returned as function result
- Created using literals

Function is not a named entity: function keyword creates a Function instance and assigned it to a window property if you delcare such at top-level. For example, the following two forms are the same:

    function myFunc() {
        alert('I am working');
    }


    myFunc = function() {
        alert('I am working');
    }
