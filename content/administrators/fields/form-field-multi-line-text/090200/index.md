---
topic: form-field-multi-line-text
locale: en
title: Form Field: Multi-Line Text
dnneditions: Evoq Engage
dnnversion: 09.02.00
parent-topic: administrators-forms-overview
related-topics: form-field-address,form-field-date-time,form-field-dropdown,form-field-email,form-field-esignature,form-field-multiple-choice,form-field-name,form-field-number,form-field-phone-number,form-field-single-line-text,form-field-static-text,form-field-terms-conditions,form-field-url-website,form-field-submit
---

# Form Field: Multi-Line Text

## General Settings

  

![Settings for Multi-Line Text field](img/scr-FormField-MultiLineText-generalsettings.gif)

  

Field

Description

Title/Label

Name of the field. You can change the name either in the General Settings panel or directly above the field on the canvas.

Required

If enabled (On),

*   The field name is marked as required.
*   The message you enter in the provided text box will be displayed if the user does not provide a value in the field.

## Help Text

  

![Settings for Multi-Line Text field](img/scr-FormField-MultiLineText-helptext.gif)

  

Field

Description

Inside Field

Help text to be displayed inside the field. Maximum length: 140 characters. (This value is not displayed if a default value is specified.)

Below Field

Help text to be displayed below the field. Maximum length: 140 characters.

Tooltip

If enabled (On) and the user hovers/clicks/taps over the information icon (i) next to the field name, displays the help text you enter in the provided text box. Maximum length: 140 characters.

## Default Value

  

![Settings for Multi-Line Text field](img/scr-FormField-MultiLineText-defaultvalue.gif)

  

Field

Description

Default Value

The value to assign to the field if the user does not provide a custom value. If blank, the Help Text Inside Field value is displayed.

Set Default Value as Hidden

If checked,

*   The default value is not displayed to the user.
*   Required must be Off.

## Validation

  

![Settings for Multi-Line Text field](img/scr-FormField-MultiLineText-validation.gif)

  

Field

Description

Number of Characters

If enabled (On), the message you enter in the provided text box will be displayed if the user provides a value outside the valid range. You must indicate the valid range:

*   Minimum. The valid range is from the value you enter in Min to infinity.
*   Maximum. The valid range is from infinity to the value you enter in Max.
*   Between. The valid range is from the value you enter in Min to the value you enter in Max.

Min must be less than Max.

Error Message

The message to display if the user entered data that does not meet the requirements for the field.