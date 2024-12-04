# Blog App API - Documentation

## Resources

- App Base Url
    - https://movieapp-api-lms1.onrender.com

- Admin User
    - email: "admin@mail.com"
    - password: "admin123"

## References

## Endpoints

### Users

#### [POST] - "/users/login"

- Sample Request Body

    ```json

    {
        "email": "user@mail.com",
        "password": "userPW123"
    }

    ```

#### [POST] - "/users/register"

- Sample Request Body

    ```json

    {
        "email": "user@mail.com",
        "username": "userone",
        "password": "userPW123"
    }

    ```
      
### Blogs

#### [POST] - "/blogs/addBlog"

- Sample Request Body

    ```json

    {
        "title": "Sample: The Blog",
        "content": "Sample L. Jackson",
        "author": 2024
    }

    ```

#### [GET] - "/blogs/getBlogs"

- No Request Body

#### [GET] - "/blogs/getBlog/:id"

- No Request Body

#### [DELETE] - "/blogs/deleteBlog/:id"

- No Request Body

#### [POST] - "/blogs/addComment/:id"

- Sample Request Body

    ```json

    {
        "comment": "Sample 2: The Reckoning is the best sample update of all time.",
    }

    ```
#### [GET] - "/blogs/getComments/:id"

- No Request Body

#### [DELETE] - "/blogs/deleteComment/:id"

 Sample Request Body

    ```json

    {
        "comment": "commentId",
    }

    ```