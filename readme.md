> ng update

Ng update is a command available in Angular CLI which is used to update your application and its dependencies.

> ng update --all

You can use it to update all packages in the package. json file via the --all option that could take true or false or specific versions via the --packages option.

> ng add

For example you run the command ng add @angular/material — Install, it will automatically install the package and configure in angular.json file too.

> npm update

This command will update all the packages listed to the latest version (specified by the tag config), respecting semver. It will also install missing packages.

> npm list

Show the installed packages in the current project as a dependency tree.

> npm list --depth=n

Show the dependency tree with a specified depth.

> npm list --prod

Show packages in the dependencies .

> npm list --dev

Show packages in the devDependencies .

> npm view connect versions

This command shows data about a package and prints it to stdout.

> npm outdated

It will identify packages that should be updated

> ng generate @angular/core:inject-migration

> ng generate @angular/core:standalone

> ng generate @angular/core:control-flow


ng g component --type=smart-component
ng g component --type=ui-component
