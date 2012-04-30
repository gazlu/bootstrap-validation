bootstrap-validation
====================

Validation framework for Bootstrap, from Twitter [http://twitter.github.com/bootstrap/index.html]

 - This is a very simple and powerful validation framework for bootstrap.

Usage
=====
 - Html:
    use the following code for your html form, 
    it explains the custom attributes to be used for the validation section, required, data-type validation etc.
    
    
    <pre>
    &lt;form id=&quot;todo-form&quot; onSubmit=&quot;return subCommonForm(0, 'main')&quot; class=&quot;form-horizontal&quot; action=&quot;action&quot; method=&quot;POST&quot;&gt;
  &lt;fieldset&gt;
    &lt;legend&gt;formTitle&lt;/legend&gt;
    &lt;div id=&quot;genMsg&quot; style=&quot;display:none;&quot; class=&quot;alert alert-error&quot;&gt;&lt;/div&gt;
    &lt;div class=&quot;control-group&quot;&gt;
      &lt;label for=&quot;email&quot; class=&quot;control-label&quot;&gt;User Name&lt;/label&gt;
      &lt;div class=&quot;controls&quot;&gt;
        &lt;input type=&quot;text&quot; class=&quot;span6&quot; placeholder=&quot;enter email&quot; req=&quot;true&quot; valsection=&quot;main&quot; valdata=&quot;email&quot; name=&quot;email&quot; value=&quot;&quot;/&gt;
        &lt;span class=&quot;help-inline&quot;&gt;Email of the user&lt;/span&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;control-group&quot;&gt;
      &lt;label for=&quot;login&quot; class=&quot;control-label&quot;&gt;User Name&lt;/label&gt;
      &lt;div class=&quot;controls&quot;&gt;
        &lt;input type=&quot;text&quot; class=&quot;span6&quot; placeholder=&quot;enter login&quot; req=&quot;true&quot; valsection=&quot;main&quot; name=&quot;login&quot; value=&quot;&quot;/&gt;
        &lt;span class=&quot;help-inline&quot;&gt;User name for the user&lt;/span&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;control-group&quot;&gt;
      &lt;label for=&quot;password&quot; class=&quot;control-label&quot;&gt;Password&lt;/label&gt;
      &lt;div class=&quot;controls&quot;&gt;
        &lt;input type=&quot;password&quot; class=&quot;span6&quot; placeholder=&quot;enter password&quot; req=&quot;true&quot; valsection=&quot;main&quot; name=&quot;password&quot; value=&quot;&quot;/&gt;
        &lt;span class=&quot;help-inline&quot;&gt;Password for the user&lt;/span&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;control-group&quot;&gt;
      &lt;label for=&quot;confirmPassword&quot; class=&quot;control-label&quot;&gt;Confirm Password&lt;/label&gt;
      &lt;div class=&quot;controls&quot;&gt;
        &lt;input type=&quot;password&quot; class=&quot;span6&quot; placeholder=&quot;enter password&quot; req=&quot;true&quot; valsection=&quot;main&quot; name=&quot;confirmPassword&quot; value=&quot;&quot;/&gt;
        &lt;span class=&quot;help-inline&quot;&gt;Confirm password for the user&lt;/span&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;control-group&quot;&gt;
      &lt;label for=&quot;firstName&quot; class=&quot;control-label&quot;&gt;First Name&lt;/label&gt;
      &lt;div class=&quot;controls&quot;&gt;
        &lt;input type=&quot;text&quot; class=&quot;span6&quot; placeholder=&quot;enter first name&quot; req=&quot;true&quot; valsection=&quot;main&quot; valdata=&quot;alpha&quot; name=&quot;firstName&quot; value=&quot;&quot;/&gt;
        &lt;span class=&quot;help-inline&quot;&gt;First name of the user&lt;/span&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;control-group&quot;&gt;
      &lt;label for=&quot;lastName&quot; class=&quot;control-label&quot;&gt;Last Name&lt;/label&gt;
      &lt;div class=&quot;controls&quot;&gt;
        &lt;input type=&quot;text&quot; class=&quot;span6&quot; placeholder=&quot;enter last name&quot; req=&quot;true&quot; valsection=&quot;main&quot; valdata=&quot;alpha&quot; name=&quot;lastName&quot; value=&quot;&quot;/&gt;
        &lt;span class=&quot;help-inline&quot;&gt;Last name of the user&lt;/span&gt;
      &lt;/div&gt;
    &lt;/div&gt;
    &lt;div class=&quot;form-actions&quot;&gt;
      &lt;input type=&quot;submit&quot; class=&quot;btn btn-primary&quot; value=&quot;Submit&quot;/&gt;
    &lt;/div&gt;
  &lt;/fieldset&gt;
&lt;/form&gt;
   </pre>
      
Installation:
=============
  - Download bootstrap-validate.js and use it along with JQuery.

Contribution:
=============
 - Please try to contribute for the data-type validation and pending Html From controls with your valuable expertise.
 
Contact:
========
  - Email: sushskulkarni[at]gmail[.]com
  - Tweet: [at]sushskulkarni