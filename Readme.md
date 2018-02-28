GraphQLFieldtypeMapMarker
=========================

This module adds GraphQL support for FieldtypeMapMarker. It is only intended for 
use with [ProcessGraphQL][graphql] module.

ProcessGraphQL comes with support for almost all core ProcessWire fieldtypes. 
However that might be not enough for everyone. Luckily  there is a way to add support 
for your desired fieldtypes via third-party modules. This module is an example for 
that. ProcessGraphQL does not support FieldtypeMapMarker out of the box. But once 
you install this module it seamlessly adds support for FieldtypeMapMarker.

There is nothing else needed after you install this module. Everything works behind 
the scenes and FieldtypeMapMarker fields will be available in your GraphQL api.

To learn about how you can create your own GraphQL extension modules for ProcessWire 
see [documentation][graphql-third-party] at ProcessGraphQL's github repository.

[graphql]: https://github.com/dadish/ProcessGraphQL#processgraphql
[graphql-third-party]: https://github.com/dadish/processgraphql#third-party-fieldtypes-support
