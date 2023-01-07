#Pipeline description
1. Push commit to github
2. CircleCI reads the config file to start integration
3. Start build job
4. Install frontend dependencies
5. Install api dependencies
6. lint the frontend
7. build frontend
8. build api
9. hold to approve/disapprove
10. set environment variables to EB
11. deploy the app