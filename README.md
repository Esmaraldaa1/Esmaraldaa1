<h2> Hi, I'm Kim! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>

```php
<?php

namespace KimQuax;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Endeavour_Haarlem',
                'position' => 'Intern'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Symfony::class,
            Json::class,
            MySQL::class,
            Javascript::class,
            Docker::class,
            PHPStorm::class,
            Jira::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To get a job as a junior backend developer.';
    }
}
```
 [![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=Esmaraldaa1&theme=onedark)](https://git.io/streak-stats) 
