# workbench
My Version of WorkBench . Extended features.

=> Creates default readme.md
=> Makes default Console command for project
=> displays at the end provider path for config/app.php

composer.json

	"repositories": [
	      {
	      "type": "git",
	       "url": "git@github.com:shivergard/workbench.git"
	      }
	 ],


	"require": {
    ...
		"illuminate/workbench": "dev-destabilizator"
	},
	

In config/app.php
  	'providers' => [
  	  ...
  		'Illuminate\Workbench\WorkbenchServiceProvider',
  	];
