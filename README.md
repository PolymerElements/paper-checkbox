
<!---

This README is automatically generated from the comments in these files:
paper-checkbox.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/paper-checkbox.svg?branch=master)](https://travis-ci.org/PolymerElements/paper-checkbox)

_[Demo and API docs](https://elements.polymer-project.org/elements/paper-checkbox)_

##&lt;paper-checkbox&gt;

`paper-checkbox` is a [material design checkbox](https://www.google.com/design/spec/components/selection-controls.html#selection-controls-checkbox). 
User can tap the checkbox to check or uncheck it.  Usually you use checkboxes
to allow user to select multiple options from a set.  If you have a single
ON/OFF option, avoid using a single checkbox and use `paper-toggle-button`
instead.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-checkbox.html">
    <style is="custom-style">
      paper-checkbox {
        font-family: 'Roboto', sans-serif;
        margin: 24px;
      }
        
      paper-checkbox:first-child {
        --primary-color: #ff5722;
      }
      
      paper-checkbox.styled {
        align-self: center;
        border: 1px solid var(--paper-green-200);
        padding: 8px 16px;
        --paper-checkbox-checked-color: var(--paper-green-500);
        --paper-checkbox-checked-ink-color: var(--paper-green-500);
        --paper-checkbox-unchecked-color: var(--paper-green-900);
        --paper-checkbox-unchecked-ink-color: var(--paper-green-900);
        --paper-checkbox-label-color: var(--paper-green-500);
        --paper-checkbox-label-spacing: 0;
        --paper-checkbox-margin: 8px 16px 8px 0;
        --paper-checkbox-vertical-align: top;
      }

      paper-checkbox .subtitle {
        display: block;
        font-size: 0.8em;
        margin-top: 2px;
        max-width: 150px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-checkbox checked>Checked</paper-checkbox>
<paper-checkbox class="styled">
  Checkbox
  <span class="subtitle">
    With a longer label
  </span>
</paper-checkbox>
<paper-checkbox disabled>Disabled</paper-checkbox>
```
