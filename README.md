
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

A material design [checkbox](https://www.google.com/design/spec/components/selection-controls.html#selection-controls-checkbox)

`paper-checkbox` is a button that can be either checked or unchecked.  User
can tap the checkbox to check or uncheck it.  Usually you use checkboxes
to allow user to select multiple options from a set.  If you have a single
ON/OFF option, avoid using a single checkbox and use `paper-toggle-button`
instead.

Example:
<!--
```
<custom-element-demo>
  <template>
    <link rel=”import” href="paper-checkbox/paper-checxbox.html”>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-checkbox>label</paper-checkbox>
<paper-checkbox checked> label</paper-checkbox>
```
