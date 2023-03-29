```php
<?php

namespace Tarabish;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
               [ 
                'company' => 'Atyaf Co',
                'position' => 'Backend Developer'  
              ] ,
              [  
                "compnay"=>"ICT Solutions Co",
                "position"=>"Full Stack Developer"   
              ],   
              [
               "company"=>"Ministry Of Finance" ,
               "position"=>"Devops Engineer"   
              ]   
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Livewire::class,
            JQuery::class,
            Ajax::class,
            RestApi::class,
            React::class,
            Graphql::class,
            Apache::class,
            Nginx::class,
            Zabbix::class,
            Docker::class , 
            Wso2::class ,
            
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

