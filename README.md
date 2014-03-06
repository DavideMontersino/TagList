TagList
=======

A simple Jquery UI widget that populates a tag list given an array of objects

Usage
=====

        $('selector').TagList(
          {
              name: "name", // (required) name for hidden fields, allows widget to be read using jquery's serialize() method
              values: [], // (required) array of objects to be used
              valueField: "Value", // (not required) name of the field to be used as Value for the tag
              textField: "Text" // (not required) name of the field to be used as Text for the tag
          });
  
