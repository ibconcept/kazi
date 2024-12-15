AngularJS App Structure:

project-root/
├── index.html
├── app/
│   ├── components/
│   │   ├── landingPage/
│   │   │   ├── landingPage.html          --> View (HTML template)
│   │   │   └── landingPageController.js  --> Controller for Landing Page
│   │   ├── login/
│   │   │   ├── login.html                --> View (HTML template)
│   │   │   └── loginController.js        --> Controller for Login
│   │   ├── signUp/
│   │   │   ├── signUp.html               --> View (HTML template)
│   │   │   └── signUpController.js       --> Controller for Sign Up
│   │   ├── kaziJobUpload/
│   │   │   ├── jobUpload.html            --> View (HTML template)
│   │   │   └── jobUploadController.js    --> Controller for Job Upload
│   │   ├── kaziSkillUpload/
│   │   │   ├── skillUpload.html          --> View (HTML template)
│   │   │   └── skillUploadController.js  --> Controller for Skill Upload
│   │   ├── kaziCasuals/
│   │   │   ├── casuals.html              --> View (HTML template)
│   │   │   └── casualsController.js      --> Controller for Casuals
│   │   ├── kaziHomeProfile/
│   │   │   ├── homeProfile.html          --> View (HTML template)
│   │   │   └── homeProfileController.js  --> Controller for Home/Profile
│   │   ├── kaziFeedback/
│   │   │   ├── feedback.html             --> View (HTML template)
│   │   │   └── feedbackController.js     --> Controller for Feedback
│   │   ├── chatPages/
│   │   │   ├── chat.html                 --> View (HTML template)
│   │   │   └── chatController.js         --> Controller for Chat
│   │   ├── kaziLive/
│   │   │   ├── live.html                 --> View (HTML template)
│   │   │   └── liveController.js         --> Controller for Live
│   │   ├── kaziDashboard/
│   │   │   ├── dashboard.html            --> View (HTML template)
│   │   │   └── dashboardController.js    --> Controller for Dashboard
│   │   └── kaziBlogs/
│   │       ├── blogs.html                --> View (HTML template)
│   │       └── blogsController.js        --> Controller for Blogs
│   ├── services/
│   │   ├── userService.js                --> Service for User-related functionalities
│   │   ├── jobService.js                 --> Service for Job-related functionalities
│   │   └── chatService.js                --> Service for Chat-related functionalities
│   └── app.js                            --> Main AngularJS application module and configuration
└── lib/
    └── angular.min.js                    --> AngularJS library
