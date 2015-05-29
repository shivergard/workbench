To Start using it add to composer.json repozitory

    "repositories": [
      {
      "type": "git",
       "url": "git@github.com:{{lower_vendor}}/{{lower_name}}.git"
      }
    ],

and add requirements

	"require": {
		...
        "{{lower_vendor}}/{{lower_name}}" : "dev-master" ,
    },

and add service provider

		'providers' => [
		...
      '{{vendor}}\{{name}}\{{name}}ServiceProvider',
		...