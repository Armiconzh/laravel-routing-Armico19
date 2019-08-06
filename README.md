# Laravel API - Module-02 Routing

Laravel API Project - Dingo Api implementation

## Tutorials

- [dingo/api](https://github.com/dingo/api/wiki/Creating-API-Endpoints) configuration

## Challenge
- Clone this repositories
- Install depedencies
```text
$ composer install
```
- Create .env file
```text
$ cp .env.example .env
```
- Genereate laravel key
```text
$ php artisan key:generate
```
- Create API Endpoint using dingo/api with conditions:
1. /me : will display biodata, use GET method
2. /login : for login process, use POST method
3. /register: for register login, use POST method
4. /logout: will destroy token, use DELETE method
- Show list of router
```text
$ php artisan api:routes
```
- Use the postman to check the API that has been made
- Push project to this repositories
- Take a screenshot of your repositories link, postman process/output and then post to the [KK4-B Google Classroom](https://classroom.google.com)

### Example Output
- endpoint /me, access using GET method
```json
{
    "status": 200,
    "data": {
        "name": "Indra Hehe Aja",
        "nickname": "goeroeku",
        "gender": "Male",
        "class": "Pro Akut"
    }
}
```
- endpoint /login and /register, access using POST method
```json
{
    "status": 204,
    "data": "Success"
}
```
- endpoint /logout, access using DELETE method
```json
{
    "status": 204,
    "data": "Success"
}
```
