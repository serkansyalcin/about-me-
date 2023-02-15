
## Hi there, I'm Serkan Yalcin 👋
```php
<?php

namespace SerkanYalcin;

class About extends Me
{
    public 
    function getBio(): string
    {
        return 'I'm a software developer specializing in PHP and JavaScript.
                I develop modern technology web applications with popular frameworks like Laravel, Vue and React.
                SaaS,
                multi-tenancy,
                e-Commerce,
                RestFull API
                I develop advanced software with software architectures.
                Eternal student.';
    } 

    public 
    function getMore(): array
    {
        return [
            'work' => [
                'Software Developer - T-SOFT',
                'Full Stack Developer - Bayer Bilişim',
                'Software Developer - Karaca',
                'Software Developer - BookLogic',
            ]
        ];
    }

    public 
    function getCurrentState(): array 
    {
        return [
            'working_on' => [
                'Ekipik - Cloud-based personnel management software (SaaS)',
                'PestForm - Send dynamic forms without the need for a backend (SaaS)'
            ],
            'learning' => [
                'Advance Programing Techniques',
                'Goo Lang'
            ]
        ];
    }

    public 
    function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
