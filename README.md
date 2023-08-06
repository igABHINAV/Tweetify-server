# Tweetify-server
A backend created in NodeJS for a social media platform like Twitter, with features such as tweets, likes, and comments, along with 8 different endpoints.
# End-points
http://localhost:5000/user/login   : User login
http://localhost:5000/user/signup  : User signup with name , username and password
http://localhost:5000/post/upload  : To upload post
http://localhost:5000/post/like/:id : Get request to like a post
http://localhost:5000/post/comment/:id : Request to comment on a post
http://localhost:5000/post/allposts : To get all the posts in sorted order by time
http://localhost:5000/post/:id : To get a perticular post
http://localhost:5000/post/user/all : To get all posts by a perticular user
