```php
<?php

namespace Dantsec;

class About extends Me
{
    public function getContact(): array
    {
        return [
            'website' => 'https://dantsec.github.io/',
            'mail' => 'dantsec@proton.me'
        ];
    }

    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Scaffold Education',
                'position' => 'Trainee Backend Developer'
            ]
        ];
    }

    public function getPersonInformation(): array
    {
        return [
            'country' => 'São Paulo, Brazil 🇧🇷',
            'hobbies' => [
                'Computer Science',
                'Math',
                'Physics',
                'Music'
            ],
            'computer' => [
                'os' => 'Manjaro Linux',
                'host' => 'Aspire ES1-572'
            ]
        ];
    }

    public function getKnowledge(): array
    {
        return [
            'programming_languages' => [
                C::class,
                Php::class,
                Python::class,
                Javascript::class,
                ShellScript::class,
            ],
            'databases' => [
                MySQL::class
            ],
            'frameworks' => [
                Laravel::class,
                Bootstrap::class,
                jQuery::class
            ],
            'tools' => [
                Vim::class,
                Git::class,
                Linux::class,
                Windows::class,
                VisualStudioCode::class
                MySQLWorkbench::class
            ]
        ];
    }
}
```
