Guzzle-oAuth-Meetup
===================

Example code to use Guzzle oAuth with another provider then one of the big four (linkedin, google, facebook, twitter).

See: http://github.com/VDMi/Guzzle-oAuth

```php
// Make sure the Composer autoloader is loaded
require 'vendor/autoload.php';
$config = array(
  // see Guzzle oAuth
);
$client = \GuzzleOauthMeetUp::factory($config);
```
