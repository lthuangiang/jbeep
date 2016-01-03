# Example: Multiple beeps #

## Javascript function ##

```javascript

function jBeeps(times, sleep) {

var i;

for(i = 0; i < times; i++) {

setTimeout("jBeep()", i * sleep);

}

}
```

## Usage ##

```javascript

jBeeps(times, interval);
```