# Uncommon HTML Bug: Modifying Non-Existent Element's innerHTML

This repository demonstrates a subtle bug in HTML where attempting to modify the `innerHTML` of a non-existent element results in a silent failure. The code tries to update an element with the id 'nonExistentElement', but this element does not exist in the HTML structure.

This is an uncommon scenario because typically, developers check for the element's existence before manipulating it. However, this example highlights a potential point of failure if such checks are omitted.