##Bower

###init
```
bower init
```

###Configure bower.json
```
{
  "name": "APP NAME",
  "version": "1.0",
  "dependencies" : {
    endencies"	: {
		"jquery" 			: "*",
		"backbone-amd"		: "*",
		"underscore-amd" 	: "*",
		"requirejs"			: "*",
		"twitter"			: "*"
    },
  "ignore": [
    "**/.*",
    "node_modules",
    "components",
    "bower_components",
    "test",
    "tests"
  ]
}
```

###.bowerrc
```
{
		"directory":"app/scripts/vendor"
}
```

###install
```
bower install
```