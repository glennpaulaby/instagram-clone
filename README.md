A custom made Instagram Clone using HTML and CSS by training provided from DevTwon 'Instagram Clone using HTML and CSS Workshop'

the landing page -
![image](https://user-images.githubusercontent.com/91583403/218315480-9d2d5182-c618-4b8c-9e7b-ed3f17fc0c4a.png)
![image](https://user-images.githubusercontent.com/91583403/218315485-08fba22f-97fc-4b5b-8229-7eac20a66b31.png)

the header of HTML code - 

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
    <link
      href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css"
      rel="stylesheet"
    />
  </head>
  <body>
    <!-- Sidebar -->
    <div class="sidebar">
      <a href="#" class="logo">
        <img src="img1/logo.png" alt="logo" />
      </a>
      <!-- Profile Image -->
      <div class="profile">
        <div class="profile-img">
          <img src="img1/profile.jpeg" alt="profile" />
        </div>
        <div class="name">
          <h1>Glenn Paul Aby</h1>
          <img src="img1/verify.png" alt="verify" />
        </div>
        <span>@glenn</span>
      </div>
      
code for the sidebar -
              <a href="#" >
            <span class= "icon">
                <i class="ri-function-line"></i>
            </span>
            Feed
          </a>
          <a href="#" >
              <span class= "icon">
                  <i class="ri-notification-4-line"></i>
              </span>
              Notification
            </a>
            <a href="#" >
                <span class= "icon">
                    <i class="ri-search-line"></i>
                </span>
                Explore
              </a>
              <a href="#" ">
                  <span class= "icon">
                      <i class="ri-mail-unread-fill"></i>
                  </span>
                  Message
                </a>
                <a href="#" >
                    <span class= "icon">
                        <i class="ri-send-plane-fill"></i>
                    </span>
                    Direct
                  </a>
                  <a href="#" >
                      <span class= "icon">
                          <i class="ri-bar-chart-2-fill"></i>
                      </span>
                      Stats
                    </a>
                    <a href="#" >
                        <span class= "icon">
                            <i class="ri-settings-5-line"></i>
                        </span>
                        Settings 
                      </a>
                      <a href="#" >
                          <span class= "icon">
                              <i class="ri-logout-box-r-line"></i>
                          </span>
                          Logout
                        </a>
    
stories block - 
 
          <!--Stories 1-->
          <div class="stories-img color">
            <img src="img1/profile.jpeg" alt="profile" />
            <div class="add">+</div>
          </div>
          <!--Stories 2-->
          <div class="stories-img">
            <img src="img1/profile1.jpeg" alt="profile" />
          </div>
          <!--Stories 3-->
          <div class="stories-img">
            <img src="img1/profile2.jpeg" alt="profile" />
          </div>
          <!--Stories 4-->
          <div class="stories-img">
            <img src="img1/profile3.jpeg" alt="profile" />
          </div>
          <!--Stories 5-->
          <div class="stories-img">
            <img src="img1/profile4.jpeg" alt="profile" />
          </div>
          <!--Stories 6-->
          <div class="stories-img">
            <img src="img1/profile5.jpeg" alt="profile" />
          </div>
          <!--Stories 7-->
          <div class="stories-img">
            <img src="img1/profile6.jpg" alt="profile" />
          </div>
          <!--Stories 8-->
          <div class="stories-img">
            <img src="img1/profile7.jpg" alt="profile" />
          </div>
          <!--Stories 9-->
          <div class="stories-img">
            <img src="img1/profile8.jpg" alt="profile" />
          </div>
          <!--Stories 10-->
          <div class="stories-img">
            <img src="img1/profile9.jpg" alt="profile" />
          </div>
        </div>
      <div class="feed">
        <h1>Feed</h1>
        <div class="feed-text">
          <h2>Latest</h2>
          <span>Popular</span>
        </div>
      </div>
      
      
format for eact individual main posts -
      
       <div class="main-post">
          <!-- Box1 -->
          <div class="post-box">
            <img src="img1/post1.png" alt="post">
            <div class="post-info">
              <div class="post-profile">
                <div class="post-img">
                  <img src="img1/profile10.jpeg" alt="profile">
                </div>
                <h3>Sidemen</h3>
              </div>
              <div class="likes">
                  <i class="ri-heart-line"></i>
                  <span>13m</span>
                  <i class="ri-chat-3-line"></i>
                  <span>200k</span>
                  
              </div>
            </div>
          </div>
