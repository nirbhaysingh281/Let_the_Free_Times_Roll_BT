# Codel
Using AWS Continuous Deployment tools.

Manually uploading and deploying code to update applications is a thing of the past. Using AWS tools like CodePipeline, CodeBuild, & S3 students will build a system that allows them to write and push code that triggers seamless and automatic deployments. Students will also setup an email notification that is sent to developers if a status change is made in the build process using CloudWatch & SNS.


## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `npm run build -prod` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Deploy
Using CodePipeline and CodeBuild we will configure the buildspec.yml in the root directory to deploy our build artificats to S3 using `aws s3 sync`.


