```php
<?php

namespace Dantsec;

class About extends Me
{
    public function getContact(): array
    {
        return [
            'blog' => 'https://dantsec.github.io/',
            'mail' => 'dantsec@proton.me'
        ];
    }

    public function getPersonalInformation(): array
    {
        return [
            'country' => 'São Paulo, Brazil',
            'work'    => 'Trainee Backend Developer'
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
                ShellScript::class
            ],

            'databases' => [
                MySQL::class,
                SQLite::class
            ],

            'frameworks' => [
                jQuery::class,
                Laravel::class
            ],

            'tools' => [
                Git::class,
                Jira::class,
                Postman::class,
                DBeaver::class
            ]
        ];
    }
}
```
