EdpModuleLayouts
================
Version 2.0 Created by Alexander Lampret

Introduction
------------

EdpModuleLayouts is a very simple Laminas module (less than 20 lines) that simply
allows you to specify alternative layouts to use for each module.

Usage
-----

Using EdpModuleLayouts is very, very simple. In any module config or autoloaded
config file simply specify the following:

```php
[
    'module_layouts' => [
        'ModuleName' => 'layout/some-layout',
    ]
];
```

That's it!
