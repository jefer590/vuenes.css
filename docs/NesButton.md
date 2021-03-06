# nes-button 

Vue Component implementation of the Nes Button 

- **author** - Jesus Fernando Alvarez Franco 
- **license** - MIT 

## slots 

- `default` Use this slot for the content Inside the button 

## props 

- `primary` ***Boolean*** (*optional*) `default: false` 

  Prop that define if the Button is type Primary. Will use the `is-primary` class 

- `success` ***Boolean*** (*optional*) `default: false` 

  Prop that define if the Button is type Success. Will use the `is-success` class 

- `warning` ***Boolean*** (*optional*) `default: false` 

  Prop that define if the Button is type Warning. Will use the `is-warning` class 

- `error` ***Boolean*** (*optional*) `default: false` 

  Prop that define if the Button is type Error. Will use the `is-error` class 

- `disabled` ***Boolean*** (*optional*) `default: false` 

  Prop that define if the Button is type Disabled. Will use the `is-disabled` class and will not trigger the click event 

## computed properties 

- `buttonClasses` 

  Computed Property that uses the button classes depending of the props used. 

   **dependencies:** `primary`, `success`, `warning`, `error`, `disabled` 


## events 

- `click` 

## methods 

- `click()` 

  Method that emits the click event 

