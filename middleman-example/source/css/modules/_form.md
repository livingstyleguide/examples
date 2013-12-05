# Forms

## Base

All “normal” forms have the class `.form` attached. Non-normal forms
could be search fields etc.

~~~ example
<form class="***form***">
  Content goes here.
</form>
~~~

## Text Fields

Simple default example:

~~~ example
<form class="form">
  ***
  <div class="form--field">
    <label class="form--label" for="example-id-1">Some label</label>
    <div class="form--field-container">
      <input id="example-id-1" class="form--textfield" type="text">
    </div>
  </div>
  ***
</form>
~~~

Required field:

~~~ example
<form class="form">
  <div class="form--field ***is-required***">
    <label class="form--label" for="example-id-1">Some label</label>
    <div class="form--field-container">
      <input id="example-id-1" class="form--textfield" type="text" value="jiji" ***required***>
    </div>
  </div>
</form>
~~~

Disabled field:

~~~ example
<form class="form">
  <div class="form--field ***is-disabled***">
    <label class="form--label" for="example-id-1">Some label</label>
    <div class="form--field-container">
      <input id="example-id-1" class="form--textfield" type="text" value="jiji" ***disabled***>
    </div>
  </div>
</form>
~~~

For numbers:

~~~ example
<form class="form">
  <div class="form--field ***is-number***">
    <label class="form--label" for="example-id-2">Some label</label>
    <div class="form--field-container">
      <input id="example-id-2" class="form--textfield" type="text">
    </div>
  </div>
</form>
~~~

