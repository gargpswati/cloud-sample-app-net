# Deliver Dancing Goat .NET MVC 5 sample application

## SUMMARY

Dancing Goat .NET MVC Application is a sample website utilizing Kentico Deliver service to manage and retrieve content.

## PREREQUISITIES

1. Environment that is capable of running the .NET MVC 5 application such as Visual Studio 2013+.
2. Account at https://app.kenticocloud.com with sample Kentico Deliver project. You can read more about Kentico Deliver service activation here: https://kenticocloud.com/docs#enabling-kentico-deliver .

## CONTENT ADMINISTRATION

1. Navigate to https://app.kenticocloud.com in your browser.
2. Sign in with your credentials.
3. You are redirected to content administration interface of your Dancing Goat project. For more details about the content editing, please see https://kenticocloud.com/docs .

## APPLICATION SETUP

1. Copy the Project ID from the https://app.kenticocloud.com. More details about getting Project ID: https://kenticocloud.com/docs#getting-project-id .
2. Insert the Project ID to the value of the ProjectId application setting in the Web.config file. 
3. Run the application.

## PREVIEW CONTENT

1. To preview the unpublished content you need to provide the Preview API key to the application.
2. Copy the Preview API key from the https://app.kenticocloud.com . For more details, please read: https://kenticocloud.com/docs#previewing-unpublished-content-using-deliver-api .
3. Insert the Preview API key to the string value of the PreviewToken application setting in the Web.config file.
4. Run the application.

## CONTENT DELIVERY

1. The whole content can be reached through http://deliver.kenticocloud.com/<PROJECT_ID>/items URL, which is also a base URL for all the request on your project.
2. To read more about the Kentico Deliver API, please see http://docs.kenticodeliver.apiary.io .
