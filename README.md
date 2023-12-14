<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmtmeHN1MzdpMGR6Mjc3MWVmbXNuNHExcG93bDgyZmUxYnN0eTZ0NCZjdD1z/L0t5istHtiDgJ40PZw/giphy.gif" width="50"></h2>
<h2> Hi, I'm Kim! <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMjFhMDU3Yjg4NDU2NTlkZDI0MzQ5Mzk4MDNjNjU0ZmY5YjBjNjAwYyZjdD1z/A9dZqpVpbLsju/giphy.gif" width="80"></h2>

```php
<?php

namespace KimQuax;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'CleanUpp',
                'position' => 'Software Developer(back-end)'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            CakePHP:class,
            Laravel::class,
            Symfony::class,
            Json::class,
            MySQL::class,
            JavaScript::class,
            Docker::class,
            PHPStorm::class,
            Azure::class,
        ];
    }
    
    public function getInterests(): array
   {
         return [
            Festivals::class,
            Traveling::class,
            BoardGames::class,
            DungeonsAndDragons::class,
            Baking::class,
            Reading::class,
         ];
    }

    public function getFutureGoal(): string
    {
        return 'Travel more.';
    }
}
```
 [![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=Esmaraldaa1&theme=onedark)](https://git.io/streak-stats) 
