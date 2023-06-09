# Little Lemon API
## API endpoints
| Endpoints | Role | Methods |
| --- | --- | --- |
| `/auth/users/` | no role required | `POST` |
| `/auth/token/login` | no role required | `POST` |
| `/auth/token/logout` | no role required | `POST` |
| `/restaurant/menu/` | no role required | `GET` |
| `/restaurant/menu/` | User | `POST`, `PUT`, `DELETE` |
| `/restaurant/menu/:id` | no role required | `GET` |
| `/restaurant/menu/:id` | User | `POST`, `PUT`, `DELETE` |
| `/restaurant/booking/` | no role required | `GET` |

## Images of APIs response
### Authenctication images
Create User using `POST` method
![](./screenshots/create_user.png)

User login token using `POST` method
![](./screenshots/login_token.png)


### Menu API's Images
View All Menu using `GET` method
![](./screenshots/get_menu_all.png)

View Single Menu using `GET` method
![](./screenshots/single_menu.png)

Add Menu Item using `POST` method
![](./screenshots/add_item.png)
![](./screenshots/add_item_token.png)