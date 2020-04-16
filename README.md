### Simple Blog - Backend

## createPost

- # Url
  /create
- # Method
  `Post`
- # Success response
  - _Code_: 200
    Content:
    ```
    {
      message: "Success! A new post has been created",
      post: newPost,
    }
    ```
- # Error response
  - _Code_: 404

## getAllPosts

- # Url
  /
- # Method
  `Get`
- # Success response
  - _Code_: 200
    Content:
    ```
    { message: "Success! All posts have been queried", posts }
    ```
- # Error response
  - _Code_: 404

## getSinglePost

- # Url
  /get
- # Method
  `Get`
- # Success response
  - _Code_: 200
    Content:
    ```
    { message: "Success! A post has been queried", post }
    ```
- # Error response
  - _Code_: 404
