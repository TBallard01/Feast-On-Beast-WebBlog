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
| 1 | Ensure admin priveleges work exclusively for admin role | Demonstration | Run application in production environment, then attempted to access admin privleges by both roles, ensuring only admin role has access to admin privleges | Tested | 20:14:38 | 
| 2.0 | Can post blogs to main page as admin | Demonstration | As admin create a new post and ensure it not only posts but posts to main page. | Tested | 20:18:20 |
| 2.1 | Can access blogs on main page as user | Implementation | As user click newly created blog post and ensure blog post image, title, and body are displayed. | Tested | 20:28:00 |
| 3.0 | Can post recipes as admin that are successfully stored in recipe database | Demonstration | As admin create new recipe post then access database via azure portal and ensure new post is in recipe database | Tested | N/A |
| 3.1 | Can post recipes as admin that are sorted via a category of meat and posted to meat recipe page | Implementation | As admin create new recipe with category of meat and ensure it is posted on meat recipe page | Test Failed | N/A |
| 3.2 | Can view recipes as user that is sorted via a category of meat and posted on the meat recipe page | Implementation | As user view recipe post with category of meat on the meat recipe page | Test Failed | N/A |
| 3.3 | Can post recipes as admin that are sorted via a category of fish and posted to fish recipe page | Implementation | As admin create new recipe with category of fish and ensure it is posted on fish recipe page | Test Failed | N/A |
| 3.4 | Can view recipes as user that is sorted via a category of fish and is posted to the fish recipe page | Implementation | As user view recipe with a category of fish on the fish recipe page | Test Failed | N/A |
| 3.5 | Can post recipes as admin that are sorted via a category of vegetarian and is posted to vegetarian recipe page | Implementation | As user view recipe with a category of vegetarian on the vegetarian recipe page | Test Failed | N/A |
| 3.6 | Can view recipes as user that are sorted via a category of vegetarian and posted to the vegetarian recipe page | Implementation | As admin create new recipe with category of vegetarian and ensure it is posted on vegetarian recipe page | Test Failed | N/A |
| 4.0 | Can embed youtube videos to tips & tricks page as admin | Demonstration | Click on unit tests folder, then unit tests class, and run unit test postVideo | Tested | N/A |
| 4.1 | Can view youtube videos on tips & tricks page as user | Demonstration | Click on embedded youtube video and ensure it streams | Tested | N/A |
| 5.0 | Can post gear reviews to gear page as admin | Implementation | Click on unit tests folder, then unit tests class, and run unit test postGear | Not Tested | N/A |
| 5.1 | Can view gear reviews on gear page as user | Implementation | Click on gear reviews tab on the nav bar, then select a gear review post and ensure all of its content is displayed to the user | Not Tested | N/A |

<h3>View Project</h3>

- Project can be viewed by entering https://feastonbeast.azurewebsites.net/ into your preferred web browser. 
