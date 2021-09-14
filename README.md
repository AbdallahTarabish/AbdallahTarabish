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
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```

https://github-readme-stats.vercel.app/api?username=AbdallahTarabish&show_icons=true&theme=dracula&count_private=true
