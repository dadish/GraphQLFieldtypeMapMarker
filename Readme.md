GraphQLFieldtypeMapMarker
=========================

This module adds GraphQL support for FieldtypeMapMarker. It is only intended for 
use with [ProcessGraphQL][graphql] module.

### Description
ProcessGraphQL comes with support for almost all core ProcessWire fieldtypes. 
However that might be not enough for everyone. Luckily there is a way to add support 
for your desired fieldtypes via third-party modules. This module is an example for 
that. ProcessGraphQL does not support FieldtypeMapMarker out of the box. But once 
you install this module it seamlessly adds support for FieldtypeMapMarker.

### Installation
This module's files should be placed in /site/modules/ProCache/ 
[How to install or uninstall modules](http://modules.processwire.com/install-uninstall/)

### Usage
Everything works behind the scenes for this module. After you installed it, FieldtypeMapMarker 
fields will be available in your GraphQL api.

To learn about how you can create your own GraphQL extension modules for ProcessWire 
see [documentation][graphql-third-party] at ProcessGraphQL's github repository.

[graphql]: https://github.com/dadish/ProcessGraphQL#processgraphql
[graphql-third-party]: https://github.com/dadish/processgraphql#third-party-fieldtypes-support
