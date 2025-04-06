# Api Requests

## Authenticating requests <a href="#authenticating-requests" id="authenticating-requests"></a>

To authenticate requests, include an **`Authorization`** header with the value **`"Bearer {YOUR_LICENSE_KEY}"`**.

## Get license info

Request:\
`GET` [https://tinyinstaller.top/api/v1/my/info](https://tinyinstaller.top/api/v1/me/info)\
Headers:\
`Authorization`: `Bearer {YOUR_LICENSE_KEY}`

### Get images

`GET` [https://tinyinstaller.top/api/v1/my/images](https://tinyinstaller.top/api/v1/me/images)\
Headers:\
`Authorization`: `Bearer {YOUR_LICENSE_KEY}`\
Body Parameters:\
`q`  Search keyword. Example win2012\
`page` Pagination page. Example: 2

### Get instances

`GET`  [https://tinyinstaller.top/api/v1/my/instances](https://tinyinstaller.top/api/v1/me/instances)\
Headers:\
`Authorization`: `Bearer {YOUR_LICENSE_KEY}` \
Body Parameters:\
`ip_address` Filter by ip address. Example 123.123.123.123\
`status` Filter by status, available statuses: new, wait\_for\_tiny, installing, installed, error, timed\_out, done\
`page` Pagination page. Example 2\
&#x20;

### Get instance detail

`GET` [https://tinyinstaller.top/api/v1/my/instances/{id}](https://tinyinstaller.top/api/v1/me/instances/%7Bid%7D)\
Headers:\
`Authorization`: `Bearer {YOUR_LICENSE_KEY}` \
Url parameters:\
`id` Instance id from list. Example: 22353604-ae4a-47b3-8d70-ef919a9445e2

