# L4-yaml file parser

this using symfony2 yaml component

## installing

add this code on **app/config/app.php**

    array(
      'providers' => array (
            other providers,
            'Pieter\Yaml\YamlServiceProvider',
        ),
      'aliases' => array (
            other aliases,
            'Yaml'            => 'Pieter\Yaml\Facades\Yaml',
        )
      ),
    )


## How to use

just create in yaml on app/config folder and call from your controller

    \Yaml::setFile('[your_file].yml');
    return \Yaml::parsing();


enjoy it !


