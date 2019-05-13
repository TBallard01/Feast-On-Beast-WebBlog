# Feast On Beast

<h3>Initial Outlook</h3>

Feast On Beast is an interactive web application that will serve as a source of information for anyone interested in hunting, or the outdoors. Will also host media options such as pictures, and videos that I will upload for the viewers entertainment.  The web application will also host recipes for cooking wild game meats, and vegetation for all levels of expertise/diets. The main purpose of this web app is to educate the masses the importance of wild life conservation, and hopefully influence others to take action towards helping save the environment. The secondary purpose is to allow those who may not be able to hunt, or go out in the true outdoors the opportunity to read about my experiences and in a sense live through it.

<h3>Currently Implementing</h3>

- Blog Posts
- User authorizations
- Image upload and streaming by using a content folder within project

<h3>Backlog</h3>

- Using blobs to implement photos
- Recipes page
- Gear review page
- Gallery page
- embedding youtube videos

<h3>Future Implementations</h3>

- Google map with pins that will be dropped in the areas I go to hunt or explore with information on the wild life/ vegetation available in that area

<h3>Testing</h3>

| Requirement ID | Description | Test Method | Test Procedure | Current Status | TimeStamp |
| --- | --- | --- | --- | --- | --- |
| 1 | Ensure admin priveleges work exclusively for admin role | Test | Run application in production environment, then attempted to access admin privleges by both roles, ensuring only admin role has access to admin privleges | Tested | 20:14:38 | 
| 2 | Can post blogs to main page as admin | Test | As admin create a new post and ensure it not only posts but posts to main page. | Tested | 20:18:20 |
| 3 | Can post recipes as admin that are successfully stored in recipe database | Test | As admin create new recipe post then access database via azure portal and ensure new post is in recipe database | Tested | N/A |
| 4 | Can post recipes as admin that are sorted via a category of meat and posted to meat recipe page | Test | As admin create new recipe with category of meat and ensure it is posted on meat recipe page | Test Failed | N/A |
| 5 | Can post recipes as admin that are sorted via a category of fish and posted to fish recipe page | Test | As admin create new recipe with category of fish and ensure it is posted on meat recipe page | Test Failed | N/A |
| 6 | Can post recipes as admin that are sorted via a category of vegetarian and posted to vegetarian recipe page | Test | As admin create new recipe with category of vegetarian and ensure it is posted on vegetarian recipe page | Test Failed | N/A |
| 7 | Can post images to media page as admin | Test | Click on unit tests folder, then unit tests class, and run unit test postImage | Not Tested | N/A |
| 8 | Can embed youtube videos to media page as admin | Test | Click on unit tests folder, then unit tests class, and run unit test postVideo | Not Tested | N/A |
| 9 | Can post gear reviews to gear page as admin | Test | Click on unit tests folder, then unit tests class, and run unit test postGear | Not Tested | N/A |

<h3>View Project</h3>

- Project can be viewed by entering https://feastonbeast.azurewebsites.net/ into your preferred web browser. 
