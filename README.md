# Datepicker

# Description
This widget can be used to select dates. You can choose different layouts and formats. Both input fields and dropdown elements are implemented.

# Typical usage scenario
Typical usages are birthdays or other dates that are not near to the current date.

# Features and limitations

Variations are:
* Drop down DD + MM inputfield for YYYY
* Drop down MM inputfield for DD + YYYY
* Input fields DD + MM + YYYY

## Languages supported: 
(both long and short names)- Dutch, English, French, German 

## Form orientation supported:
Vertical & Horizontal (if horizontal is used, label width can be set)

## Date order supported:  
DD/MM/YYYY- MM/DD/YYYY- YYYY/MM/DD

Custom error messages can be set.

## emptyAttributeOnError

If this option is set to true then inline validation of the date
is disabled, and instead the returned date entity will be empty if
a problem occurs.

If emptyAttributeOnError isn't selected, when editing an existing
date and if an invalid year is entered, the previous year could be retained in the date attribute returned.

# Credits:
Based on [Mendix boilerplate](https://github.com/mendix/AppStoreWidgetBoilerplate)
