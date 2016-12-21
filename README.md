# vegeta.js
JavaScript for Bulma.io
[![npm](https://img.shields.io/npm/v/vegeta.js.svg)](https://www.npmjs.com/package/vegeta.js)

### installation
```npm install vegeta.js```

## example
```javascript
// new vegeta!
var v = new Vegeta();

v.bind_nav_toggle();    // bind navigation toggle
v.bind_notif('.trunk'); // bind notification to <div class='.trunk' />

// call notifications
$('#btn-default').click(function(){
  v.notif('Default message');
});
$('#btn-info').click(function(){
  v.notif_info('Info message');
});
$('#btn-primary').click(function(){
  v.notif_primary('Primary message');
});
$('#btn-success').click(function(){
  v.notif_success('Success message');
});
$('#btn-warning').click(function(){
  v.notif_warning('Warning message');
});
$('#btn-danger').click(function(){
  v.notif_danger('Danger message');
});
```
### demo
:zap: <a href='https://diewland.github.io/vegeta.js/'>LIVE</a>
