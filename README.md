# ServiceNow ES12 Polyfill
Sick and tired of ServiceNow's lacking implementation of ES12? Use this library to polyfill all the missing methods!

## Installation
> [!TIP]
> To minimize impact on the performance use the minified version of the library

1. Create a new Script Include in global scope named "ES12Polyfill"
2. Allow for script execution in all scopes and in the sandbox context
3. Copy-paste code from `servicenow-es12-polyfill.min.js` or `servicenow-es12-polyfill.js` file

## Usage
At the top of the server-script code include:
```javascript
ES12Polyfill()
```
