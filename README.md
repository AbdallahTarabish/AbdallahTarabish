```php
<?php

namespace Tarabish;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Atyaf Co',
                'position' => 'Backend Developer'         
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
            Graphql::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
## Contribution Graph <img width="40" src="https://c.tenor.com/8Bhx4_d52goAAAAi/mic-drop-busy-bee.gif" />
<img src="https://activity-graph.herokuapp.com/graph?username=AbdallahTarabish&theme=dracula&color=B994E6&bg_color=2B2D3D" />

